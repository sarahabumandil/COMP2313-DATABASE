1. Entities, Unique Identifiers (UIDs), and Attributes

(تحديد الكيانات الثمانية، المعرّفات الفريدة #، الصفات الإلزامية *، والصفات الاختيارية o — جميع أسماء الكيانات بالمفرد وبأحرف كبيرة)

1. DEPARTMENT

• # * department id
• * name
• * office location

2. STUDENT

• # * student id
• * full name
• * date of birth
• * university email
• o mobile number

3. TRAINER

• # * trainer id
• * full name
• * hire date
• * official email
• o personal phone number

4. WORKSHOP

• # * workshop id
• * title
• * category
• * fee

5. SESSION

• # * session id
• * date
• * start time
• * maximum number of seats

6. ROOM

• # * room id
• * room code
• * building
• * capacity

7. REGISTRATION (Intersection Entity resolving M:M between STUDENT and SESSION with its own Artificial UID # registration id)

• # * registration id
• * registration date
• * status (Confirmed, Waitlisted, or Cancelled)

8. STUDENT CARD

• # * card id
• * issue date
• * expiry date

2. Visual ER Diagram (Oracle Academy Barker's Notation)

يوضح المخطط التالي جميع الكيانات الثمانية وعلاقاتها التسع (بما في ذلك العلاقة الذاتية للمدربين Recursive Relationship وكيان التقاطع REGISTRATION وعلاقة 1:1 للبطاقة الطلابية):
text
+-----------------------+

|      DEPARTMENT       |
| # * department id     |
| * name                |
| * office location     |
+-----------------------+

     |             |
     | include     | employ
     | (Dashed)    | (Dashed)
     |             |
     v (Crow)      v (Crow)
  belongs to     works in
  (Solid/Toe)    (Solid/Toe)
+-----------------------+       +---------------------------+

|        STUDENT        |       |          TRAINER          |
| # * student id        |       | # * trainer id            |
| * full name           |       | * full name               |
| * date of birth       |       | * hire date               |
| * university email    |       | * official email          |
| o mobile number       |       | o personal phone number   |
+-----------------------+       +---------------------------+

  |                   |            |  |                  ^
  | own               | make       |  | supervise        |
  | (Dashed)          | (Dashed)   |  | (Dashed/Crow)    |
  v (Toe)             v (Crow)     |  +--- supervised by-+
belongs to          made by        |       (Dashed/Toe)
(Solid/Toe)         (Solid/Toe)    | teach (Dashed)
+-----------------------+   +-----------------------+    |

|     STUDENT CARD      |   |     REGISTRATION      |    |
| # * card id           |   | # * registration id   |    |
| * issue date          |   | * registration date   |    |
| * expiry date         |   | * status              |    |
+-----------------------+   +-----------------------+    |

                                       |                 |
                                  for  | (Solid/Toe)     |
                                       v (Dashed/Crow)   |
                                  receives               |
+-----------------------+   +-----------------------+    |

|       WORKSHOP        |   |        SESSION        |<---+
| # * workshop id       |-->| # * session id        | taught by
| * title               |   | * date                | (Solid/Toe)
| * category            |   | * start time          |
| * fee                 |   | * maximum seats       |
+-----------------------+   +-----------------------+
  have (Solid/Crow)             ^               |
  belongs to (Solid/Toe)        | host          | take place in

                                | (Dashed/Crow) | (Solid/Toe)
                            +-----------------------+

                            |         ROOM          |
                            | # * room id           |
                            | * room code           |
                            | * building            |
                            | * capacity            |
                            +-----------------------+
Use code with caution.
(ملاحظة بصرية عند الرسم باليد أو في برنامج Oracle SQL Developer Data Modeler: الخط المتصل Solid يمثل must، والخط المتقطع Dashed يمثل may، والطرف المفرد Single Toe يمثل one and only one، ورِجل الغراب Crow's Foot تمثل one or more).

3. Complete ERDish Statements (9 Relationships × 2 Directions = 18 Sentences)


Relationship 1: DEPARTMENT and STUDENT (1:M)

• Drawing Specs: Solid line with a single toe at DEPARTMENT; dashed line with a crow's foot at STUDENT.
• Direction 1 (STUDENT ➔ DEPARTMENT):
Each STUDENT must belong to one and only one DEPARTMENT.
• Direction 2 (DEPARTMENT ➔ STUDENT):
Each DEPARTMENT may include one or more STUDENTs.

Relationship 2: DEPARTMENT and TRAINER (1:M)

• Drawing Specs: Solid line with a single toe at DEPARTMENT; dashed line with a crow's foot at TRAINER.
• Direction 1 (TRAINER ➔ DEPARTMENT):
Each TRAINER must work in one and only one DEPARTMENT.
• Direction 2 (DEPARTMENT ➔ TRAINER):
Each DEPARTMENT may employ one or more TRAINERs.

Relationship 3: TRAINER and TRAINER (Recursive 1:M — Supervisor)

• Drawing Specs: Dashed line with a single toe at the supervisor end; dashed line with a crow's foot at the supervised trainer end.
• Direction 1 (Subordinate ➔ Supervisor):
Each TRAINER may be supervised by one and only one TRAINER.
• Direction 2 (Supervisor ➔ Subordinate):
Each TRAINER may supervise one or more TRAINERs.

Relationship 4: WORKSHOP and SESSION (1:M — Mandatory at Both Ends)

• Drawing Specs: Solid line with a single toe at WORKSHOP; solid line with a crow's foot at SESSION.
• Direction 1 (WORKSHOP ➔ SESSION):
Each WORKSHOP must have one or more SESSIONs.
• Direction 2 (SESSION ➔ WORKSHOP):
Each SESSION must belong to one and only one WORKSHOP.

Relationship 5: TRAINER and SESSION (1:M)

• Drawing Specs: Solid line with a single toe at TRAINER; dashed line with a crow's foot at SESSION.
• Direction 1 (SESSION ➔ TRAINER):
Each SESSION must be taught by one and only one TRAINER.
• Direction 2 (TRAINER ➔ SESSION):
Each TRAINER may teach one or more SESSIONs.

Relationship 6: ROOM and SESSION (1:M)

• Drawing Specs: Solid line with a single toe at ROOM; dashed line with a crow's foot at SESSION.
• Direction 1 (SESSION ➔ ROOM):
Each SESSION must take place in one and only one ROOM.
• Direction 2 (ROOM ➔ SESSION):
Each ROOM may host one or more SESSIONs.

Relationship 7: STUDENT and REGISTRATION (1:M)

• Drawing Specs: Solid line with a single toe at STUDENT; dashed line with a crow's foot at REGISTRATION (not barred, since REGISTRATION has its own artificial UID # registration id).
• Direction 1 (REGISTRATION ➔ STUDENT):
Each REGISTRATION must be made by one and only one STUDENT.
• Direction 2 (STUDENT ➔ REGISTRATION):
Each STUDENT may make one or more REGISTRATIONs.

Relationship 8: SESSION and REGISTRATION (1:M)

• Drawing Specs: Solid line with a single toe at SESSION; dashed line with a crow's foot at REGISTRATION (not barred).
• Direction 1 (REGISTRATION ➔ SESSION):
Each REGISTRATION must be for one and only one SESSION.
• Direction 2 (SESSION ➔ REGISTRATION):
Each SESSION may receive one or more REGISTRATIONs.

Relationship 9: STUDENT and STUDENT CARD (1:1)

• Drawing Specs: Solid line with a single toe at STUDENT; dashed line with a single toe at STUDENT CARD.
• Direction 1 (STUDENT CARD ➔ STUDENT):
Each STUDENT CARD must belong to one and only one STUDENT.
• Direction 2 (STUDENT ➔ STUDENT CARD):
Each STUDENT may own one and only one STUDENT CARD.


