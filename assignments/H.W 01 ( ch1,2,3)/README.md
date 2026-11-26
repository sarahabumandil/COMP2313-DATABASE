Assignment #1: University Training Center Management System

1. Entities, Unique Identifiers (UIDs), and Attributes

Notation: # = Unique Identifier (UID), * = Mandatory attribute, o = Optional attribute. All entity names are singular and UPPERCASE.

1.1 DEPARTMENT

· # * department id
· * name
· * office location

1.2 STUDENT

· # * student id
· * full name
· * date of birth
· * university email
· o mobile number

1.3 TRAINER

· # * trainer id
· * full name
· * hire date
· * official email
· o personal phone number

1.4 WORKSHOP

· # * workshop id
· * title
· * category
· * fee

1.5 SESSION

· # * session id
· * date
· * start time
· * maximum number of seats

1.6 ROOM

· # * room id
· * room code
· * building
· * capacity

1.7 REGISTRATION

Intersection entity resolving the M:M relationship between STUDENT and SESSION, with its own artificial UID.

· # * registration id
· * registration date
· * status (Confirmed, Waitlisted, or Cancelled)

1.8 STUDENT CARD

· # * card id
· * issue date
· * expiry date

---

2. Visual ER Diagram (Oracle Academy — Barker's Notation)

The diagram below shows all eight entities and their nine relationships, including the recursive relationship on TRAINER (supervisor) and the 1:1 relationship for STUDENT CARD.

```text
+-----------------------+                         +---------------------------+
|      DEPARTMENT       |                         |          TRAINER          |
|  # * department id    |                         |  # * trainer id           |
|  *   name             |                         |  *   full name            |
|  *   office location  |                         |  *   hire date            |
+-----------------------+                         |  *   official email       |
        |            |                            |  o   personal phone number|
        | include    | employ                     +---------------------------+
        | (Dashed)   | (Dashed)                          |            ^
        |            |                                   | supervise  |
        v (Crow)     v (Crow)                            | (Dashed)   |
   belongs to      works in                               v (Crow)     | (Dashed/Toe)
   (Solid/Toe)     (Solid/Toe)                            +------------+ (recursive)
        |            |                                    |
        |            |                                    | teach (Dashed)
+-----------------------+                         +---------------------------+
|        STUDENT        |                         |          SESSION          |
|  # * student id       |                         |  # * session id           |
|  *   full name        |                         |  *   date                 |
|  *   date of birth    |                         |  *   start time           |
|  *   university email |                         |  *   maximum seats        |
|  o   mobile number    |                         +---------------------------+
+-----------------------+                              ^            |
        |            |                                 |            |
        | own        | make                            | belongs to | take place in
        | (Dashed)   | (Dashed)                        | (Solid/Toe)| (Solid/Toe)
        v (Toe)      v (Crow)                          |            v
+-----------------------+                         +---------------------------+
|     STUDENT CARD      |                         |           ROOM            |
|  # * card id          |                         |  # * room id              |
|  *   issue date       |                         |  *   room code            |
|  *   expiry date      |                         |  *   building             |
+-----------------------+                         |  *   capacity             |
        |                                         +---------------------------+
        | receives (Dashed/Crow)
        v
+-----------------------+          have (Solid/Crow)         +-----------------------+
|       WORKSHOP        |<------------------------------------|      REGISTRATION     |
|  # * workshop id      |                                     |  # * registration id  |
|  *   title            |                                     |  *   registration date|
|  *   category         |                                     |  *   status           |
|  *   fee              |                                     +-----------------------+
+-----------------------+                                                |
                                                                         | for (Solid/Toe)
                                                                         v
                                                                     SESSION
```

Legend

Symbol Meaning
Solid line must (mandatory)
Dashed line may (optional)
Single toe one and only one
Crow's foot one or more

---

3. Complete ERDish Statements (9 Relationships × 2 Directions = 18 Sentences)

Relationship 1: DEPARTMENT and STUDENT (1:M)

Drawing Specs: Solid line with a single toe at DEPARTMENT; dashed line with a crow's foot at STUDENT.

· Direction 1 (STUDENT ➔ DEPARTMENT): Each STUDENT must belong to one and only one DEPARTMENT.
· Direction 2 (DEPARTMENT ➔ STUDENT): Each DEPARTMENT may include one or more STUDENTs.

Relationship 2: DEPARTMENT and TRAINER (1:M)

Drawing Specs: Solid line with a single toe at DEPARTMENT; dashed line with a crow's foot at TRAINER.

· Direction 1 (TRAINER ➔ DEPARTMENT): Each TRAINER must work in one and only one DEPARTMENT.
· Direction 2 (DEPARTMENT ➔ TRAINER): Each DEPARTMENT may employ one or more TRAINERs.

Relationship 3: TRAINER and TRAINER (Recursive 1:M — Supervisor)

Drawing Specs: Dashed line with a single toe at the supervisor end; dashed line with a crow's foot at the supervised trainer end.

· Direction 1 (Subordinate ➔ Supervisor): Each TRAINER may be supervised by one and only one TRAINER.
· Direction 2 (Supervisor ➔ Subordinate): Each TRAINER may supervise one or more TRAINERs.

Relationship 4: WORKSHOP and SESSION (1:M — Mandatory at Both Ends)

Drawing Specs: Solid line with a single toe at WORKSHOP; solid line with a crow's foot at SESSION.

· Direction 1 (WORKSHOP ➔ SESSION): Each WORKSHOP must have one or more SESSIONs.
· Direction 2 (SESSION ➔ WORKSHOP): Each SESSION must belong to one and only one WORKSHOP.

Relationship 5: TRAINER and SESSION (1:M)

Drawing Specs: Solid line with a single toe at TRAINER; dashed line with a crow's foot at SESSION.

· Direction 1 (SESSION ➔ TRAINER): Each SESSION must be taught by one and only one TRAINER.
· Direction 2 (TRAINER ➔ SESSION): Each TRAINER may teach one or more SESSIONs.

Relationship 6: ROOM and SESSION (1:M)

Drawing Specs: Solid line with a single toe at ROOM; dashed line with a crow's foot at SESSION.

· Direction 1 (SESSION ➔ ROOM): Each SESSION must take place in one and only one ROOM.
· Direction 2 (ROOM ➔ SESSION): Each ROOM may host one or more SESSIONs.

Relationship 7: STUDENT and REGISTRATION (1:M)

Drawing Specs: Solid line with a single toe at STUDENT; dashed line with a crow's foot at REGISTRATION (not barred, since REGISTRATION has its own artificial UID # registration id).

· Direction 1 (REGISTRATION ➔ STUDENT): Each REGISTRATION must be made by one and only one STUDENT.
· Direction 2 (STUDENT ➔ REGISTRATION): Each STUDENT may make one or more REGISTRATIONs.

Relationship 8: SESSION and REGISTRATION (1:M)

Drawing Specs: Solid line with a single toe at SESSION; dashed line with a crow's foot at REGISTRATION (not barred).

· Direction 1 (REGISTRATION ➔ SESSION): Each REGISTRATION must be for one and only one SESSION.
· Direction 2 (SESSION ➔ REGISTRATION): Each SESSION may receive one or more REGISTRATIONs.

Relationship 9: STUDENT and STUDENT CARD (1:1)

Drawing Specs: Solid line with a single toe at STUDENT; dashed line with a single toe at STUDENT CARD.

· Direction 1 (STUDENT CARD ➔ STUDENT): Each STUDENT CARD must belong to one and only one STUDENT.
· Direction 2 (STUDENT ➔ STUDENT CARD): Each STUDENT may own one and only one STUDENT CARD.

---

4. Summary Table of Relationships

# Parent Entity Child Entity Cardinality Optionality Relationship Name
1 DEPARTMENT STUDENT 1:M Child mandatory / Parent optional include / belongs to
2 DEPARTMENT TRAINER 1:M Child mandatory / Parent optional employ / works in
3 TRAINER TRAINER 1:M (recursive) Both optional supervise / supervised by
4 WORKSHOP SESSION 1:M Both mandatory have / belongs to
5 TRAINER SESSION 1:M Child mandatory / Parent optional teach / taught by
6 ROOM SESSION 1:M Child mandatory / Parent optional host / take place in
7 STUDENT REGISTRATION 1:M Child mandatory / Parent optional make / made by
8 SESSION REGISTRATION 1:M Child mandatory / Parent optional receive / for
9 STUDENT STUDENT CARD 1:1 Child mandatory / Parent optional own / belongs to
