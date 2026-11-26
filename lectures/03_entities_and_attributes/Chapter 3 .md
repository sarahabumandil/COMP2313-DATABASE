تم، سأدوّن الشريحة الأولى من شابتر 3 (Slide 1 & 2 — Identifying Relationships & Objectives) بنفس القالب المنظم تماماً:

---

الشريحة الأولى والثانية (Slide 1 & 2)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slide 1 & 2 (شريحة العنوان وأهداف الدرس الأول: Identifying Relationships & Objectives).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Identifying Relationships (تحديد العلاقات): تُنطق (آيدنتيفايينج ريليشنشيبس) — اكتشاف الروابط المنطقية التي تجمع بين الكيانات (الجداول) في النظام.

• Relationship Cardinality (تعددية العلاقة): تُنطق (ريليشنشيب كارديناليتي) — تحديد الكمية أو العدد في العلاقة (هل هو مفرد One أم جمع One or more؟).

• Relationship Optionality (اختيارية العلاقة): تُنطق (ريليشنشيب أوبشيناليتي) — تحديد ما إذا كانت العلاقة إجبارية (Mandatory / Must) أم اختيارية (Optional / May).

• Relate / Connect / Join (يربط / يصل): تُنطق (ريليت / كونيكت / جوين) — عملية ربط الكيانات ببعضها وفق قواعد التعددية والاختيارية.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Database Design 3-1: Identifying Relationships
Objectives:
This lesson covers the following objectives:

Interpret and describe relationship optionality

Interpret and describe relationship cardinality

Relate (connect or join) entities by applying the rules of cardinality and optionality

5. Explanation in Arabic (الشرح باللغة العربية)

يمثل هذا الدرس حجر الأساس في بناء مخطط الكيانات والعلاقات (ERD)؛ فبعد أن تعلمنا في شابتر 2 كيف نحدد الكيانات (Entities) والصفات (Attributes)، نتعلم في شابتر 3 كيف نرسم الخطوط التي تربط بين هذه الكيانات ونقرأها بدقة:

• فهم ووصف الاختيارية (Optionality): أي الإجابة عن سؤال "هل يجب؟" (Must أم May؟)؛ مثلاً: هل يجب أن يمتلك كل موظف وظيفة (Must) أم قد يكون بدون وظيفة (May)؟

• فهم ووصف التعددية (Cardinality): أي الإجابة عن سؤال "كم العدد؟" (One أم One or more؟)؛ مثلاً: كم وظيفة يمكن أن يشغلها الموظف الواحد؟

• ربط الكيانات ببعضها (Relate entities): تطبيق قواعد الاختيارية والتعددية لرسم خطوط العلاقات الصحيحة بين الجداول.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف ضبط Optionality و Cardinality باسم "تحديد قيود المشاركة والدرجة" (Participation & Cardinality Constraints)؛ لأن أي خطأ في تحديد هل العلاقة إلزامية أم اختيارية يغير لاحقاً تصميم المفاتيح الأجنبية (Foreign Keys) وهل تقبل القيمة الفارغة (NULL) أم تمنعها (NOT NULL).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· مفتاح الدرس 3-1 كله في كلمتين:
  · Optionality = تسأل: هل يجب؟ (Must vs May).
  · Cardinality = تسأل: كم العدد؟ (One vs One or more).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من أهداف الدرس):
   Which two main rules are applied when relating (connecting) entities together in an ER diagram?
   A) Data types and precision
   B) Optionality and cardinality
   C) Delimiters and flat files
   • الإجابة الصحيحة: B (تُربط الكيانات ببعضها بتطبيق قواعد الاختيارية Optionality والتعددية Cardinality).
2. Short Question (سؤال مقالي قصير):
   List the three main objectives of Lesson 3-1 (Identifying Relationships).
   • الإجابة النموذجية:

· Interpret and describe relationship optionality.
· Interpret and describe relationship cardinality.
· Relate (connect or join) entities by applying the rules of cardinality and optionality.

---

أخبريني عندما تنتهين من كتابة هذه المقدمة لننتقل مباشرة إلى الشريحة التالية (Relationships in Data Models: الخصائص السبعة للعلاقات في نماذج البيانات)!


تم، سأدوّن الشريحة الثالثة من شابتر 3 (Slide 3 — Relationships in Data Models) بنفس القالب المنظم تماماً:

---

الشريحة الثالثة (Slide 3)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slide 3 (وترقيمها في منهج أوراكل 6 من درس 3-1: Relationships in Data Models — وتليها شريحة التعريف من منهج الأساسيات DFo 2-5).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Bi-directional (ثنائية الاتجاه): تُنطق (باي-دايريكشنال) — صفة تعني أن كل علاقة تُقرأ وتُفهم من كلا الطرفين (من اليمين لليسار ومن اليسار لليمين).

• Named at both ends (مُسمّاة عند كلا الطرفين): تُنطق (نيمد آت بوث إيندز) — وضع اسم/وصف للعلاقة عند كل جهة من جهتي الخط الرابط بين الكيانين.

• Recursive / Self-referencing (علاقة ذاتية / مع الكيان نفسه): تُنطق (ريكيرسيف) — ارتباط الكيان مع نفسه، مثل ارتباط الموظف مع المدير (وكلاهما في جدول EMPLOYEE).

• Significant association (رابط مهم / ذو دلالة): تُنطق (سِجنيفيكانت أسوسيييشن) — علاقة منطقية تهم المؤسسة وتُترجم سير العمل بين الكيانات.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Relationships in Data Models
Relationships:
• Represent something of significance or importance to the business
• Show how entities are related to each other
• Exist only between entities (or one entity and itself)
• Are bi-directional
• Are named at both ends
• Have optionality
• Have cardinality
(إضافة من الشريحة المرفقة أسفلها DFo 2-5 Relationships):
• A relationship is a bidirectional, significant association between two entities or between an entity and itself. (مثال: DEPARTMENT contain / assigned to EMPLOYEE).

5. Explanation in Arabic (الشرح باللغة العربية)

تحدد هذه الشريحة الخصائص السبع الأساسية لأي علاقة في مخططات قواعد البيانات (ERD):

1. ذات أهمية للعمل (Significance to the business): لا نرسم خط علاقة عشوائياً، بل فقط إذا كان يمثل قاعدة عمل حقيقية ومهمة للمؤسسة.
2. توضح كيفية ارتباط الكيانات (Show how entities are related): تشرح العلاقة التفاعلية بين جدول وآخر (مثل: القسم يضم موظفين، والموظف معيَّن في قسم).
3. توجد بين الكيانات فقط أو بين الكيان ونفسه (Exist only between entities or one entity and itself): العلاقة تربط مربع كيان بكيان آخر (مثل DEPARTMENT و EMPLOYEE)، أو تربط الكيان بنفسه (مثل الموظف والمدير داخل جدول EMPLOYEE)، ولا تُرسم العلاقة مع صفة (Attribute) أبداً.
4. ثنائية الاتجاه (Bi-directional): تُقرأ العلاقة من كلا الجانبين؛ من DEPARTMENT إلى EMPLOYEE ومن EMPLOYEE إلى DEPARTMENT.
5. مُسمّاة عند الطرفين (Named at both ends): نكتب فعلاً أو عبارة وصفية عند طرف كل كيان (مثل contain عند جهة القسم، و assigned to عند جهة الموظف).
6. لها اختيارية (Have optionality): تحدد هل العلاقة إلزامية (Must) أم اختيارية (May).
7. لها تعددية (Have cardinality): تحدد الكمية في العلاقة (One أم One or more).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُشار إلى النقطة الثالثة (between an entity and itself) بـ "العلاقة الأحادية / الدائرية" (Unary / Recursive Relationship)، وتُترجم في قاعدة البيانات الفعلية إلى مفتاح أجنبي ذاتي (Self-Referencing Foreign Key) داخل الجدول نفسه (مثل عمود MANAGER_ID الذي يشير إلى EMPLOYEE_ID في جدول الموظفين). كما تُعد ثنائية الاتجاه (Bi-directional) ضرورية لضمان فهم العلاقة من منظور كلا الطرفين دون غموض.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· احفظي الخصائص السبع في 3 مجموعات:
  · المعنى (2): مهمة للعمل (Significance) + توضح كيف ترتبط الكيانات (How entities relate).
  · الهيكل والاتجاه (3): بين الكيانات فقط أو الكيان ونفسه (Entities or itself) + ثنائية الاتجاه (Bi-directional) + مسماة عند الطرفين (Named at both ends).
  · القيود (2): اختيارية (Optionality) + تعددية (Cardinality).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. True or False (صح أم خطأ — فخ ارتباط الكيان بنفسه):
   Statement: "A relationship in a data model can only exist between two different entities; an entity cannot have a relationship with itself." (True / False)
   • الإجابة: False (خطأ) — تنص الشريحة حرفياً على أن العلاقات توجد بين الكيانات أو بين الكيان ونفسه (Exist only between entities or one entity and itself).
2. Multiple Choice (سؤال مباشر من خصائص العلاقات):
   Which of the following is TRUE about relationships in data models?
   A) They are uni-directional and named at only one end.
   B) They are bi-directional, named at both ends, and have optionality and cardinality.
   C) They connect an attribute directly to another attribute.
   • الإجابة الصحيحة: B (العلاقات ثنائية الاتجاه، مسماة عند الطرفين، ولها اختيارية وتعددية).
3. Short Definition Question (سؤال مقالي قصير):
   Define a "Relationship" in data modeling and list at least FIVE of its characteristics.
   • الإجابة النموذجية: A relationship is a bidirectional, significant association between two entities or between an entity and itself. Its characteristics include:
4. Represents something of significance to the business.
5. Exists only between entities (or one entity and itself).
6. Is bi-directional and named at both ends.
7. Has optionality.
8. Has cardinality.

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (What is Optionality in a Relationship? - شرح الاختيارية وأسئلتها)!



تم، سأدوّن الشريحة الرابعة من شابتر 3 (Slide 4 — What is Optionality in a Relationship?) بنفس القالب المنظم تماماً:

---

الشريحة الرابعة (Slide 4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slide 4 (وترقيمها في منهج أوراكل 7 من درس 3-1: What is Optionality in a Relationship?).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Optionality (الاختيارية / الإلزامية): تُنطق (أوبشيناليتي) — خاصية تحدد هل وجود العلاقة إجباري أم اختياري لكل طرف من طرفي العلاقة.

• Mandatory (إلزامي / إجباري): تُنطق (مانداتوري) — تعني أن العلاقة يجب أن توجد (Must) لكل مثيل، ويُعبَّر عنها بكلمة Must أو Must be وخط متصل (Solid line).

• Optional (اختياري): تُنطق (أوبشينال) — تعني أن العلاقة قد توجد أو لا توجد (May) لكل مثيل، ويُعبَّر عنها بكلمة May أو May be وخط متقطع (Dashed line).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

What is Optionality in a Relationship?

Relationships are either mandatory or optional.

Consider the two entities EMPLOYEE and JOB. Based on what you know about instances of the entities, you can determine optionality by answering two questions:
– Must every employee have a job?

In other words, is this a mandatory or optional relationship for an employee?
– Must every job be assigned to an employee?

In other words, is this a mandatory or optional relationship for a job?

5. Explanation in Arabic (الشرح باللغة العربية وتطبيق الأسئلة)

توضح هذه الشريحة كيفية تحديد الاختيارية (Optionality) بين أي كيانين من خلال طرح سؤال يبدأ بكلمة "هل يجب؟" (Must...?) لكل طرف على حدة:

• الاحتمالان الوحيدان للاختيارية: أي طرف في العلاقة يكون إما إلزامياً (Mandatory) أو اختيارياً (Optional).

• تطبيق المثال (EMPLOYEE و JOB):

· السؤال الأول (من جهة الموظف): "هل يجب أن يمتلك كل موظف وظيفة؟ (Must every employee have a job?)"
  · الجواب المنطقي: نعم، لا يوجد موظف في الشركة بلا مسمى وظيفي؛ إذن العلاقة من جهة الموظف إلزامية (Mandatory - Must).
· السؤال الثاني (من جهة الوظيفة): "هل يجب أن تكون كل وظيفة معيَّنة لموظف؟ (Must every job be assigned to an employee?)"
  · الجواب المنطقي: لا، قد تفتح الشركة وظيفة شاغرة (مثل "محاسب" أو "مطور") ولم يُعيَّن عليها أحد بعد؛ إذن العلاقة من جهة الوظيفة اختيارية (Optional - May).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُسمى هذا المفهوم "قيود المشاركة الكلية والجزئية" (Total vs. Partial Participation Constraints)؛ فالمشاركة الكلية (Mandatory) تعني أن كل صف في الجدول يجب أن يشارك في العلاقة (مما يفرض قيد NOT NULL على المفتاح الأجنبي)، بينما المشاركة الجزئية (Optional) تسمح بوجود سجلات غير مرتبطة (مثل وظيفة شاغرة بلا موظف).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· كلمة السر لاختبار Optionality: ابدئي سؤالكِ دائماً بكلمة Must...? (هل يجب؟).
· ترجمة الجواب:
  · إذا كان الجواب نعم (يجب) ➔ Mandatory (كلمة السر: Must).
  · إذا كان الجواب لا (ليس بالضرورة) ➔ Optional (كلمة السر: May).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
   Which question helps determine the "Optionality" of a relationship between EMPLOYEE and JOB?
   A) How many jobs can one employee hold?
   B) Must every employee have a job, and must every job be assigned to an employee?
   C) What is the data type of the job title?
   • الإجابة الصحيحة: B (الأسئلة التي تبدأ بـ Must...? تحدد الاختيارية Optionality، أما How many? فتحدد التعددية Cardinality).
2. True or False (صح أم خطأ):
   Statement: "If a company can have a newly created JOB position that is not yet assigned to any EMPLOYEE, then the relationship from JOB to EMPLOYEE is mandatory." (True / False)
   • الإجابة: False (خطأ) — لأن الوظيفة قد تكون شاغرة بدون موظف، فالعلاقة من جهة الوظيفة اختيارية (Optional).

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (What is Cardinality in a Relationship? - شرح التعددية وسؤال How many?)!


تم، سأدوّن الشريحة الخامسة من شابتر 3 (Slide 5 — What is Cardinality in a Relationship?) بنفس القالب المنظم تماماً:

---

الشريحة الخامسة (Slide 5)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slide 5 (وترقيمها في منهج أوراكل 8 من درس 3-1: What is Cardinality in a Relationship?).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Cardinality (التعددية): تُنطق (كارديناليتي) — خاصية تقيس الكمية وتحدد عدد المثيلات المرتبطة في العلاقة (One مفرد أم One or more جمع).

• Quantity (الكمية / العدد): تُنطق (كوانتيتي) — المقدار العددي الذي تقيسه التعددية.

• Degree (الدرجة / المدى): تُنطق (ديجري) — مدى ارتباط كيان بكيان آخر من حيث العدد.

• Singular or plural (مفرد أو جمع): تُنطق (سينجيولار أور بلورال) — القاعدة الذهبية للتعددية؛ فهي تجيب فقط بـ "مفرد (One and only one)" أو "جمع (One or more)" ولا تحدد رقماً دقيقاً مثل 3 أو 5.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

What is Cardinality in a Relationship?

Cardinality measures the quantity of something.

In a relationship, it determines the degree to which one entity is related to another by answering the question, "How many?"

For example:
– How many jobs can one employee hold? One job only? Or more than one job?
– How many employees can hold one specific job? One employee only? Or more than one employee?

Note: The cardinality of a relationship only answers whether the number is singular or plural; it does not answer with a specific plural number.

5. Explanation in Arabic (الشرح باللغة العربية وتطبيق الأسئلة)

توضح هذه الشريحة المفهوم الثاني في بناء العلاقات وهو التعددية (Cardinality):

• سؤال التعددية السحري (How many?): تقيس التعددية الكمية وتجيب عن سؤال "كم العدد؟" من كلا طرفي العلاقة:

· من جهة الموظف (EMPLOYEE): "كم وظيفة يمكن أن يشغلها الموظف الواحد؟ وظيفة واحدة فقط أم أكثر من وظيفة؟" (في الشركات التقليدية، يشغل الموظف وظيفة واحدة فقط One job only).
· من جهة الوظيفة (JOB): "كم موظفاً يمكن أن يشغل وظيفة محددة (مثل وظيفة 'مبرمج')؟ موظف واحد فقط أم أكثر من موظف؟" (يمكن لأكثر من موظف شغل نفس المسمى الوظيفي More than one employee).

• ملاحظة الامتحان الجوهرية (Note): التعددية في مخططات ERD تُجيب فقط بـ مفرد (Singular - One and only one) أو جمع (Plural - One or more)، ولا تذكر رقماً محدداً للجمع (فلا نقول مثلاً "وظيفة يشغلها 4 موظفين"، بل نقول "واحد أو أكثر").

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا المبدأ باسم "نسب التعددية البنيوية" (Structural Cardinality Ratios: 1:1, 1:N, M:N)؛ حيث تُفصل القيود الهيكلية العامة (مفرد مقابل جمع) عن القيود الرقمية الدقيقة (مثل الحد الأقصى 5 مساقات للطالب) التي تُترك لقواعد العمل (Business Rules) أو برمجة التطبيق (Triggers).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· كلمة السر لاختبار Cardinality: اسألي دائماً How many? (كم العدد؟).
· الإجابات المسموحة فقط (2 لا ثالث لهما):
  · Singular (مفرد) ➔ One and only one (واحد وواحد فقط).
  · Plural (جمع) ➔ One or more (واحد أو أكثر — ممنوع كتابة أرقام محددة مثل 3 أو 10).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الملاحظة في الشريحة):
   Which statement is TRUE regarding the "Cardinality" of a relationship in an ER diagram?
   A) It specifies the exact maximum number of records (e.g., exactly 5 employees per job).
   B) It answers the question "How many?" only in terms of singular (one) or plural (one or more), without a specific plural number.
   C) It determines whether the relationship line is drawn as solid or dashed.
   • الإجابة الصحيحة: B (التعددية تجيب عن سؤال How many? بالمفرد أو الجمع فقط دون تحديد رقم جمع معين).
2. True or False (صح أم خطأ):
   Statement: "Cardinality measures the quantity in a relationship by answering the question 'Must or May?'." (True / False)
   • الإجابة: False (خطأ) — سؤال Must or May? يحدد الاختيارية (Optionality)، بينما سؤال How many? هو الذي يحدد التعددية (Cardinality).

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (Optionality and Cardinality Examples + رموز الخطوط والطرفين Solid/Dashed & Single Toe/Crow's Foot)!


تم، سأدوّن الشريحة السادسة من شابتر 3 (Slide 6 — Optionality and Cardinality Examples مع رموز الخطوط) بنفس القالب المنظم تماماً:

---

الشريحة السادسة (Slide 6)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slide 6 (وترقيمها في منهج أوراكل 9 من درس 3-1: Optionality and Cardinality Examples — مع الشريحة المرفقة لرموز الخطوط DFo 2-5).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Solid line (خط متصل): تُنطق (سوليد لاين) — خط مستمر غير متقطع يمثل العلاقة الإلزامية (Mandatory / Must).

• Dashed line (خط متقطع): تُنطق (داشت لاين) — خط مكون من شرطات متقطعة يمثل العلاقة الاختيارية (Optional / May).

• Single toe (إصبع واحد / خط مفرد): تُنطق (سينجل تو) — نهاية الخط التي تشبه خطاً مستقيماً واحداً، وتمثل التعددية المفردة (One and only one).

• Crow's foot (رِجل الغراب): تُنطق (كروز فوت) — نهاية الخط المتشعبة إلى ثلاثة خطوط كقدم الطائر، وتمثل التعددية الجمع (One or more).

• Classified by (مُصنَّف حسب): تُنطق (كلاسيفايد باي) — اسم العلاقة التي تربط المنتج (PRODUCT) بنوعه (PRODUCT TYPE).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Optionality and Cardinality
Examples:

Each EMPLOYEE must hold one and only one JOB

Each JOB may be held by one or more EMPLOYEEs

Each PRODUCT must be classified by one and only one PRODUCT TYPE

Each PRODUCT TYPE may classify one or more PRODUCTs

(إضافة من الشريحة المرفقة أسفلها DFo 2-5 Relationships):

The relationship line on the diagram is either solid (mandatory) or dashed (optional).

These lines terminate in either a "single toe" (one instance) or a "crow's foot" (one or more instances).

5. Explanation in Arabic (الشرح باللغة العربية وتحويل الجمل إلى رموز رسم)

تُجمّع هذه الشريحة بين الاختيارية (Must / May) والتعددية (One and only one / One or more) في جمل تصميمية كاملة، وتربطها بالرموز البصرية التي نرسمها على المخطط:

• الرموز البصرية للخطوط ونهاياتها (مهمة جداً للرسم والامتحان):

· شكل الخط (Optionality):
  · خط متصل (Solid line) = إلزامي (Mandatory / Must).
  · خط متقطع (Dashed line) = اختياري (Optional / May).
· نهاية الخط (Cardinality):
  · خط مفرد مستقيم (Single toe) = واحد وواحد فقط (One and only one).
  · رِجل الغراب المتفرعة (Crow's foot) = واحد أو أكثر (One or more).

• تحليل الجمل الأربع في الشريحة:

· المثال الأول (EMPLOYEE و JOB):
  · Each EMPLOYEE must hold one and only one JOB ➔ خط متصل ينتهي بـ Single toe عند JOB.
  · Each JOB may be held by one or more EMPLOYEEs ➔ خط متقطع ينتهي بـ Crow's foot عند EMPLOYEE.
· المثال الثاني (PRODUCT و PRODUCT TYPE):
  · Each PRODUCT must be classified by one and only one PRODUCT TYPE ➔ خط متصل ينتهي بـ Single toe عند PRODUCT TYPE.
  · Each PRODUCT TYPE may classify one or more PRODUCTs ➔ خط متقطع ينتهي بـ Crow's foot عند PRODUCT.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا الأسلوب في الرسم باسم "ترميز باركر / رجل الغراب" (Barker's / Crow's Foot Notation)، وهو المعيار الرسمي المعتمد في أدوات Oracle Data Modeler؛ لأن العين البشرية تستطيع تمييز الخط المتصل (Mandatory) من المتقطع (Optional)، وتمييز التفرع الثلاثي (Crow's foot = Many) من الخط الواحد (Single toe = One) في أجزاء من الثانية دون قراءة أي نص.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· جدول التحويل البصري السحري (احفظيه عن ظهر قلب):
  · Must (إلزامي) = Solid line (خط متصل).
  · May (اختياري) = Dashed line (خط متقطع).
  · One and only one (مفرد) = Single toe (خط واحد).
  · One or more (جمع) = Crow's foot (رجل الغراب المتفرعة).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الرموز البصرية):
   In Oracle ER diagramming notation, what do a "dashed line" and a "crow's foot" represent respectively?
   A) Mandatory optionality and singular cardinality (one and only one).
   B) Optional relationship (may) and plural cardinality (one or more).
   C) Primary key and foreign key.
   • الإجابة الصحيحة: B (الخط المتقطع Dashed line يمثل العلاقة الاختيارية Optional، ورِجل الغراب Crow's foot تمثل التعددية الجمع One or more).
2. Fill in the Blanks (سؤال إكمال من أمثلة الشريحة):
   Complete the two business rule sentences for PRODUCT and PRODUCT TYPE:

· Each PRODUCT __________ be classified by __________ PRODUCT TYPE.
· Each PRODUCT TYPE __________ classify __________ PRODUCTs.
  • الإجابة النموذجية:
  · must , one and only one
  · may , one or more

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (Business Scenario 1: المطعم والزبون والطلب CUSTOMER & ORDER في الشرائح 11-13)!


تم، سأدوّن الشرائح التطبيقية للسيناريو الأول (Slides 7, 8, & 9 — Business Scenario 1: CUSTOMER & ORDER) بنفس القالب المنظم تماماً:

---

الشرائح السابعة والثامنة والتاسعة (Slides 7, 8, & 9)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 7, 8, & 9 (وترقيمها في منهج أوراكل 11 و 12 و 13 من درس 3-1: Business Scenario 1: CUSTOMER & ORDER).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Business Scenario (سيناريو العمل): تُنطق (بزنس سيناريو) — قصة أو وصف عملي لطريقة سير العمل في مؤسسة ما لاستخراج العلاقات منها.

• Counter (كاونتر / طاولة الطلبات): تُنطق (كاونتر) — المكان الذي يتقدم إليه الزبون لتقديم طلبه في المطعم.

• Owns the order (يمتلك الطلب): تُنطق (أونز ذي أوردر) — الشخص المسجل كصاحب للطلب والمسؤول عن دفع قيمته.

• Responsible for payment (مسؤول عن الدفع): تُنطق (ريسبونسيبل فور بايمنت) — قاعدة عمل تحدد أن الفاتورة تُسجل باسم العميل الذي طلبها (مثل الأم التي تطلب لأطفالها).

4. Exact Text on Slide (النص المكتوب في الشرائح الثلاث كما هو)

Business Scenario 1 (Slide 11):
What are the relationships in the following business scenario?
"In our restaurant, a customer walks up to the counter and places their order. A customer can order for him or herself only, or for him/herself and others. For example, a mother orders for herself and her children. We consider the mother to be the customer who owns the order and is responsible for payment. Over a period of time, a customer can place as many orders as he wants."

Business Scenario 1 — Optionality & Cardinality (Slides 12 & 13):

CUSTOMER places ORDERs:

Optionality = Must or may?
– Each ORDER must be placed by one (and only one) CUSTOMER.
– Each CUSTOMER must place one or more ORDERs.

Cardinality = How many?
– Each ORDER must be placed by one and only one CUSTOMER.
– Each CUSTOMER must place one or more ORDERs.

5. Explanation in Arabic (الشرح باللغة العربية وتحليل السيناريو)

تُدرّبكِ هذه الشرائح الثلاث على مهارة استخراج الاختيارية (Optionality) والتعددية (Cardinality) من قصة عمل حقيقية (Business Scenario):

• تحليل القصة (المطعم والعميل والطلب):

· قيد صاحب الطلب: حتى لو طلبت الأم لنفسها ولأطفالها في فاتورة واحدة، يُعتبر الطلب مملوكاً لشخص واحد وواحد فقط (وهو الأم المسؤولة عن الدفع). كما لا يوجد طلب في النظام بدون عميل يطلبه.
· قيد الزبون في المطعم: لا يُسجَّل الشخص كـ CUSTOMER في نظام المطعم إلا إذا تقدم للكاونتر وقدم طلباً واحداً على الأقل؛ ومع مرور الوقت يمكنه تقديم عدد غير محدود من الطلبات (as many orders as he wants).

• صياغة العلاقة النهائية من كلا الطرفين:

· من جهة الطلب (ORDER ➔ CUSTOMER): كل طلب يجب (Must - Mandatory) أن يُطلب من قِبل عميل واحد وواحد فقط (One and only one).
· من جهة العميل (CUSTOMER ➔ ORDER): كل عميل يجب (Must - Mandatory) أن يطلب طلباً واحداً أو أكثر (One or more).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا السيناريو بـ "علاقة الواحد إلى متعدد الإلزامية من الطرفين" (Mandatory 1:N Relationship)؛ فبينما تكون العلاقة في المتاجر الإلكترونية اختيارية من جهة العميل (لأن الزائر ينشئ حساباً قبل أن يشتري)، فإن نظام الكاونتر في هذا المطعم يُنشئ سجل CUSTOMER فقط لحظة تقديم ORDER، مما يجعل العلاقة إلزامية (Must) من الجانبين.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· لاحظي أن كلمة must تكررت في الجملتين في هذا السيناريو:
  · Each ORDER must be placed by one and only one CUSTOMER.
  · Each CUSTOMER must place one or more ORDERs.
· شكل الخط في الرسمة: لأن العلاقة إلزامية من الطرفين (Must و Must)، فالخط بينهما متصل بالكامل (Solid line) من أوله لآخره، ينتهي بـ Single toe عند CUSTOMER وبـ Crow's foot عند ORDER.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من السيناريو):
   In Business Scenario 1 (Restaurant Orders), what are the optionality and cardinality from ORDER to CUSTOMER?
   A) Each ORDER may be placed by one or more CUSTOMERs.
   B) Each ORDER must be placed by one and only one CUSTOMER.
   C) Each ORDER must be placed by zero or more CUSTOMERs.
   • الإجابة الصحيحة: B (كل طلب يجب أن يُطلب من قِبل عميل واحد وواحد فقط must be placed by one and only one CUSTOMER).
2. True or False (صح أم خطأ):
   Statement: "In the restaurant scenario, if a mother orders for herself and her children, the order is owned by multiple customers." (True / False)
   • الإجابة: False (خطأ) — تعتبر الأم وحدها العميل الذي يملك الطلب والمسؤول عن الدفع (one and only one CUSTOMER).

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (Business Scenario 2: العلاقة الذاتية Recursive Relationship للموظف والمدير في الشرائح 14-15)!


تم، سأدوّن الشرائح التطبيقية للسيناريو الثاني (Slides 10 & 11 — Business Scenario 2: EMPLOYEE Self-Relationship) بنفس القالب المنظم تماماً:

---

الشرائح العاشرة والحادية عشرة (Slides 10 & 11)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 10 & 11 (وترقيمها في منهج أوراكل 14 و 15 من درس 3-1: Business Scenario 2: EMPLOYEE Self-Relationship).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Join one entity to itself (ربط الكيان بنفسه): تُنطق (جوين وَن إينتيتي تو إتسيلف) — العلاقة الذاتية أو الدائرية (Recursive / Unary Relationship) التي ينطلق فيها خط العلاقة من كيان ويعود إلى نفس الكيان (ويُسمى شكلها في أوراكل بـ Pig's Ear).

• Managing Director (المدير العام / العضو المنتدب): تُنطق (مانيجينج دايريكتور) — أعلى منصب إداري في الشركة، ويدير نفسه (Manages him/herself).

• Managed by / Manage (يُدار بواسطة / يُدير): تُنطق (مانيجد باي / مانيج) — اسما طرفي العلاقة الذاتية داخل كيان الموظفين (EMPLOYEE).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Business Scenario 2 (Slide 14):

A relationship can join one entity to itself.

Examine the following scenario:
– "We need to keep track of our employees and their managers. Every employee has one manager, including the managing director who manages him/herself. Each manager can manage several employees."

Business Scenario 2 — Solution (Slide 15):

Since managers are also employees, both are listed in the same entity: EMPLOYEE.

Each EMPLOYEE may be managed by one and only one EMPLOYEE

Each EMPLOYEE may manage one or more EMPLOYEEs

5. Explanation in Arabic (الشرح باللغة العربية وتحليل السيناريو)

توضح هذه الشرائح فكرة هندسية ذكية جداً تُعرف بـ العلاقة الذاتية (Recursive Relationship)، حيث لا ننشئ جدولين منفصلين للموظفين والمديرين، بل ندمجهما في كيان واحد هو EMPLOYEE:

• لماذا ندمج المديرين والموظفين في كيان واحد (EMPLOYEE)؟
لأن المدير هو في الأصل موظف في الشركة (Managers are also employees)، فله رقم وظيفي واسم وراتب وتاريخ تعيين مثل أي موظف آخر؛ وإنشاء جدول منفصل للمديرين سيسبب تكراراً للبيانات.

• قراءة العلاقة الذاتية من كلا الطرفين (مهمة جداً للامتحان):

· الطرف الأول (من الموظف إلى المدير): Each EMPLOYEE may be managed by one and only one EMPLOYEE (كل موظف قد يُدار بواسطة موظف/مدير واحد وواحد فقط — لاحظي أن كلمة may وُضعت في الحل رغم أن كل موظف له مدير، لأن العلاقة الذاتية في أوراكل تُرسم اختيارية Optional عند الطرف المفرد لتجنب حلقة لا نهائية عند إدخال المدير العام أول مرة!).
· الطرف الثاني (من المدير إلى الموظفين): Each EMPLOYEE may manage one or more EMPLOYEEs (كل موظف قد يُدير موظفاً واحداً أو أكثر — اختيارية may لأن الموظف العادي لا يُدير أحداً).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التصميم باسم "العلاقة الأحادية / الدائرية" (Unary / Recursive Relationship) أو "أذن الخنزير" (Pig's Ear)؛ وتُؤكد Stanford على قاعدة تقنية حاسمة: يجب أن تكون العلاقة الذاتية اختيارية (Optional / Dashed) من جهة الطرف المفرد (may be managed by one and only one)؛ لأنه عند إدخال أول صف في الجدول (المدير العام Managing Director) لن يكون له مدير مسجل قبله، ولو كانت العلاقة إلزامية (Must) لرفض النظام إدخال أول سجل للأبد!

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة الحفظ السريعة في السيناريو 2:
  · كيان واحد فقط: EMPLOYEE (المدير هو موظف أيضاً).
  · كلمة السر في الجملتين معاً هي may (الخط متقطع بالكامل من الطرفين!):
    · Each EMPLOYEE may be managed by one and only one EMPLOYEE.
    · Each EMPLOYEE may manage one or more EMPLOYEEs.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من السيناريو الثاني):
   In Business Scenario 2 (Employees and Managers), why are managers not placed in a separate MANAGER entity?
   A) Because managers do not have employee IDs or salaries.
   B) Because managers are also employees, so both are listed in the same EMPLOYEE entity using a recursive relationship.
   C) Because relational databases do not allow more than two entities.
   • الإجابة الصحيحة: B (لأن المديرين هم موظفون أيضاً، فيتم وضعهم في نفس كيان EMPLOYEE وربط الكيان بنفسه).
2. True or False (صح أم خطأ):
   Statement: "In the recursive relationship on the EMPLOYEE entity, the correct ERDish statements are: 'Each EMPLOYEE may be managed by one and only one EMPLOYEE' and 'Each EMPLOYEE may manage one or more EMPLOYEEs'." (True / False)
   • الإجابة: True (صح) — هذا هو النص الحرفي في الشريحة 15.

---

أخبريني عندما تنتهين من كتابة هذه الشريحة لننتقل مباشرة إلى الشريحة التالية (Components of a Relationship & Business Rule Syntax - مكونات العلاقة وصيغة كتابة قواعد العمل في شرائح DFo 2-5 10-12)!

تم، سأدوّن الشرائح الخاصة بمكونات العلاقة وصيغة كتابة قواعد العمل (Slides 12, 13, & 14) بنفس القالب المنظم تماماً:

---

الشرائح الثانية عشرة والثالثة عشرة والرابعة عشرة (Slides 12, 13, & 14)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-1 Identifying Relationships (تصميم قواعد البيانات: 3-1 تحديد العلاقات ومكوناتها).

2. Slide Number (رقم الشريحة)

• Slides 12, 13, & 14 (وترقيمها في منهج أوراكل DFo 2-5 أرقام 10, 11, 12 مع شريحتي المصطلحات والملخص 16, 17 لدرس 3-1).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Lowercase (أحرف صغيرة): تُنطق (لوَركيس) — قاعدة تسمية أسماء العلاقات في مخطط ERD؛ يجب كتابة اسم العلاقة دائماً بأحرف صغيرة (مثل contain و assigned to)، بعكس أسماء الكيانات التي تُكتب بأحرف كبيرة (DEPARTMENT, EMPLOYEE).

• Matching record (سجل مطابق / مرتبط): تُنطق (ماتشينج ريكورد) — الصف المرتبط في الجدول الآخر؛ فالإلزامي (Mandatory) يعني وجود سجل مرتبط واحد على الأقل، والاختياري (Optional) يسمح بصفر سجلات مرتبطة.

• Business rule syntax (صيغة قاعدة العمل): تُنطق (بزنس رول سينتاكس) — القالب القياسي الثابت لكتابة وقراءة أي علاقة بين كيانين باللغة الإنجليزية.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Components of a Relationship (Slide 10):
The components of the relationship include the following:

Name: The label that appears close to the entity it is assigned to. Make sure that all relationship names are in lowercase.

Cardinality: The minimum and maximum number of values in the relationship:
– One and only one matching record
– One or more matching records

Optionality: Whether the relationship must exist:
– Optional (zero matching records)
– Mandatory (at least one matching record in each entity)

Business Rule Syntax (Slide 11):
When reading the business rule sentence, use the following wording:

Optional: Use "may be" or "may."

Mandatory: Use "must be" or "must."

Line (Single toe): Use "one and only one."

Crow's feet: Use "one or more."

Syntax: Each entity1 {must be or may be} relationship_name {one or more or one and only one} entity2.

Visual Diagram Example (Slide 12):

DEPARTMENT contain (Optional / Dashed + Crow's foot) ⟷ (Mandatory / Solid + Single toe) assigned to EMPLOYEE
– Each DEPARTMENT may contain one or more EMPLOYEEs.
– Each EMPLOYEE must be assigned to one and only one DEPARTMENT.

5. Explanation in Arabic (الشرح باللغة العربية وتلخيص نهاية درس 3-1)

تُجمّع هذه الشرائح القواعد الذهبية التي تضمن لكِ رسم وقراءة أي علاقة في الامتحان بدون أي خطأ:

• المكونات الثلاثة لأي علاقة (Components of a Relationship):

· الاسم (Name): يُكتب بجانب الكيان ويُكتب دائماً بأحرف صغيرة (lowercase) مثل contain و assigned to.
· التعددية (Cardinality): إما one and only one (سجل واحد فقط) أو one or more (سجل واحد أو أكثر).
· الاختيارية (Optionality): إما Optional (صفر سجلات مرتبطة مسموح) أو Mandatory (سجل مرتبط واحد على الأقل إجباري).

• القالب الثابت لقراءة العلاقة (Business Rule Syntax):
Each + الكيان الأول + (must / may) + اسم العلاقة + (one and only one / one or more) + الكيان الثاني.

• تطبيق المثال البصري (DEPARTMENT و EMPLOYEE):

· من القسم إلى الموظف: كل قسم قد (may — خط متقطع) يحتوي على موظف واحد أو أكثر (one or more — رِجل غراب).
· من الموظف إلى القسم: كل موظف يجب أن (must be — خط متصل) يُعيَّن في قسم واحد وواحد فقط (one and only one — خط مفرد).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف دمج Optionality و Cardinality معاً باسم "الحد الأدنى والأقصى للمشاركة" (Min-Max Notation)؛ فالاختيارية (Optional = 0، Mandatory = 1) تحدد الحد الأدنى للسجلات المرتبطة، بينما التعددية (One = 1، Many = N) تحدد الحد الأقصى للسجلات المرتبطة.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة الحروف الكبيرة والصغيرة (CASE RULE):
  · ENTITY = UPPERCASE (أحرف كبيرة دائماً، مثل DEPARTMENT).
  · relationship name = lowercase (أحرف صغيرة دائماً، مثل contain).
· جدول التحويل الرباعي السريع:
  · Optional = may / may be = Dashed line (0 records allowed).
  · Mandatory = must / must be = Solid line (at least 1 record required).
  · Single toe = one and only one.
  · Crow's foot = one or more.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من قاعدة كتابة الأسماء في الشريحة):
   According to Oracle ER diagramming rules, how should relationship names be formatted on a diagram?
   A) In ALL UPPERCASE letters
   B) In all lowercase letters
   C) Enclosed in quotation marks
   • الإجابة الصحيحة: B (تُكتب جميع أسماء العلاقات بأحرف صغيرة lowercase، بينما تُكتب أسماء الكيانات بأحرف كبيرة UPPERCASE).
2. Diagram-to-Text Translation (سؤال تحويل الرسمة إلى جملة — متوقع جداً):
   Based on the DEPARTMENT and EMPLOYEE diagram in Slide 12 (where the line near DEPARTMENT is solid with a single toe, and the line near EMPLOYEE is dashed with a crow's foot), write the two ERDish sentences.
   • الإجابة النموذجية:

· Each DEPARTMENT may contain one or more EMPLOYEEs.
· Each EMPLOYEE must be assigned to one and only one DEPARTMENT.

---

ألف مبروك! أنهيتِ الآن تدوين الدرس الأول من شابتر 3 (3-1 Identifying Relationships) بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الثاني (3-2 ER Diagramming Conventions: قواعد ومعايير رسم مخططات ERD)!


تم، سأدوّن الشرائح الأولى من الدرس الثاني (Slides 1, 2, 3, & 4 — ER Diagramming Conventions) بنفس القالب المنظم تماماً:

---

الشرائح الأولى والثانية والثالثة والرابعة (Slides 1, 2, 3, & 4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-2 ER Diagramming Conventions (تصميم قواعد البيانات: 3-2 قواعد ومعايير رسم مخططات الكيانات والعلاقات).

2. Slide Number (رقم الشريحة)

• Slides 1, 2, 3, & 4 (شرائح العنوان، الهدف، الغرض من الرموز العالمية، والمعايير المشتركة في درس 3-2 — ترقيم أوراكل 1, 3, 4, 6).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Diagramming Conventions (قواعد / معايير الرسم): تُنطق (داياجرامينج كونفينشنز) — القوانين والأشكال المتفق عليها عالمياً لرسم مخططات قواعد البيانات بحيث يفهمها أي مصمم أو مبرمج في العالم.

• Construct (يبني / يُنشئ): تُنطق (كونستراكت) — رسم وتجميع مكونات المخطط (الكيانات، الصفات، والعلاقات) وفق القواعد القياسية.

• Globally understood (مفهومة عالمياً): تُنطق (جلوبالي أندرستود) — رموز موحدة (مثل إشارات المرور والمطارات) تتجاوز اختلاف اللغات واللهجات.

• Accent (لهجة / نبرة): تُنطق (آكسينت) — اختلاف طريقة النطق أو الكتابة بين البشر، وهو ما تتغلب عليه لغة الرسم الموحدة (ER Diagramming).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Database Design 3-2: ER Diagramming Conventions
Objective (Slide 3):

Construct ER diagram components that represent entities, attributes and relationships according to diagramming conventions

Purpose (Slide 4):

People speak different languages throughout the world, but some signs are understood globally. (International Signs)

A Shared Convention (Slide 6):

It is efficient to communicate information in a way that can easily be understood by many people.

ER diagramming is like that -- you may say or write things differently because of the way you speak, your accent, and so on, but everyone draws ER diagrams according to the same conventions.

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الشرائح التمهيدية لماذا نلتزم بقواعد رسم موحدة عند تصميم مخطط ERD:

• فكرة الإشارات العالمية (International Signs): تماماً مثل إشارات المرور أو إشارة ممنوع التدخين أو إشارة المطعم في المطارات؛ مهما اختلفت لغة الشخص أو بلده، فإنه يفهم معنى الإشارة فوراً بمجرد النظر إليها.

• توحيد لغة المصممين (A Shared Convention): قد يختلف المبرمجون والمصممون في لغتهم أو أسلوب كتابتهم للوثائق، ولكن عندما يرسمون مخطط ERD باستخدام القواعد القياسية (مثل شكل المربع للكيان، والنجمة للعمود الإلزامي، ورِجل الغراب للتعددية)، يصبح المخطط مفهوماً لأي مهندس قواعد بيانات في أي مكان في العالم دون الحاجة لشرح إضافي.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات هندسة البرمجيات وهندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف الالتزام بالمعايير الرسومية بـ "تقييس التوثيق الهندسي" (Standardization of Technical Schematics)؛ فكما يلتزم المهندس الكهربائي برموز موحدة للمقاومة والمكثف في الدوائر الكهربائية، يلتزم مهندس قواعد البيانات برموز موحدة للكيانات والصفات والعلاقات لمنع أي سوء تفسير عند تسليم التصميم لفرق التطوير.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· اربطي درس 3-2 بمثال إشارات المرور (International Signs): الهدف من ER Diagramming Conventions هو جعل مخطط قاعدة البيانات لغة بصرية عالمية موحدة يفهمها الجميع بغض النظر عن لغتهم.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الشريحة 6):
   Why is it important to follow standard ER diagramming conventions when designing a database?
   A) Because they automatically translate SQL code into different spoken languages.
   B) Because they provide a shared visual standard so that anyone can easily understand the diagram regardless of how they speak or write.
   C) Because they eliminate the need for entities and attributes.
   • الإجابة الصحيحة: B (تُعد قواعد الرسم معياراً مشتركاً يتيح لأي شخص فهم المخطط بسهولة بغض النظر عن لغته أو أسلوب كتابته).
2. True or False (صح أم خطأ):
   Statement: "Every database designer is free to invent their own custom shapes and symbols for entities and relationships in an ER diagram." (True / False)
   • الإجابة: False (خطأ) — الجميع يرسم مخططات ER وفق نفس القواعد والمعايير المتفق عليها (according to the same conventions).

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشريحة التالية (HR System Case Scenario: مثال نظام الموارد البشرية EMPLOYEEs, JOBs, and DEPARTMENTs في شرائح 7 و 8)!

تم، سأدوّن الشريحتين التاليتين من درس 3-2 (Slides 5 & 6 — HR System: EMPLOYEEs, JOBs, and DEPARTMENTs) بنفس القالب المنظم تماماً:

---

الشريحتان الخامسة والسادسة (Slides 5 & 6)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-2 ER Diagramming Conventions (تصميم قواعد البيانات: 3-2 قواعد ومعايير رسم مخططات الكيانات والعلاقات).

2. Slide Number (رقم الشريحة)

• Slides 5 & 6 (ترقيم أوراكل 7 و 8 من درس 3-2: HR System: EMPLOYEEs, JOBs, and DEPARTMENTs).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Hire Date (تاريخ التعيين): تُنطق (هاير ديت) — التاريخ الذي بدأ فيه الموظف العمل في الشركة (صفة إلزامية *).

• Commission (العمولة / نسبة المبيعات): تُنطق (كوميشن) — مكافأة مالية إضافية تُمنح فقط للموظفين العاملين في المبيعات؛ لذا فهي صفة اختيارية (o) لبقية الموظفين.

• Allocated (مُخصَّص له): تُنطق (آلوكيتيد) — منح رقم وظيفي فريد لكل موظف (unique employee number).

• Reports to (يتبع إدارياً لـ): تُنطق (ريبورتس تو) — تبعية الموظف لقسم معين (مثل المحاسبة Accounting، المبيعات Sales، أو التطوير Development).

• Min / Max Salary (الحد الأدنى والأقصى للراتب): تُنطق (مين / ماكس سالاري) — نطاق الراتب المحدد لكل مسمى وظيفي (JOB).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

HR System: EMPLOYEEs, JOBs, and DEPARTMENTs (Slide 7):

"We need to store data about each of our company's employees. We need to track each employee's first name, last name, hire date and salary. For each employee on commission, we also need to track his/her potential commission."

"Each employee is allocated a unique employee number."

"Our company is divided into departments. Each employee reports to a department - for example, accounting, sales, or development."

HR System: EMPLOYEEs, JOBs, and DEPARTMENTs (Slide 8):

"We need to know the department responsible for each employee. Each department has a unique number."

"All employees hold an assigned job, and we keep track of the job title, max and min salary for each job. Every job has a unique job id."

(مخطط ERD المستخرج في الشريحة 8):

EMPLOYEE: # ID, * First Name, * Last Name, * Hire Date, * Salary, o Commission

DEPARTMENT: # ID, * Name

JOB: # Job ID, * Title, * Max Salary, * Min Salary

العلاقات:
– EMPLOYEE works in ⟷ responsible for DEPARTMENT
– EMPLOYEE assigned ⟷ assigned to JOB

5. Explanation in Arabic (الشرح باللغة العربية وتحليل السيناريو)

تُدرّبكِ هاتان الشريحتان على ترجمة نص متطلبات العمل إلى مخطط ERD كامل خطوة بخطوة:

• استخراج الكيانات الثلاثة (Entities): من النص نستنتج أن لدينا ثلاثة كيانات أساسية: الموظف (EMPLOYEE)، القسم (DEPARTMENT)، والوظيفة (JOB).

• استخراج الصفات والمفاتيح (Attributes & UIDs):

· في EMPLOYEE: الرقم الوظيفي (# ID)، الاسم الأول (* First Name)، اسم العائلة (* Last Name)، تاريخ التعيين (* Hire Date)، والراتب (* Salary) كلها إلزامية (*). أما العمولة (o Commission) فوضعنا بجانبها دائرة o (اختيارية) لأن النص قال "للموظفين الذين يعملون بالعمولة فقط" (فموظف المحاسبة ليس له عمولة).
· في DEPARTMENT: رقم القسم (# ID)، واسم القسم (* Name).
· في JOB: رقم الوظيفة (# Job ID)، المسمى الوظيفي (* Title)، أعلى راتب (* Max Salary)، وأقل راتب (* Min Salary).

• رسم العلاقات (Relationships):

· الموظف يعمل في قسم واحد (works in — خط متصل ينتهي بـ Single toe)، والقسم قد يكون مسؤولاً عن موظف واحد أو أكثر (responsible for — خط متقطع ينتهي بـ Crow's foot).
· الموظف معيّن في وظيفة واحدة (assigned — خط متصل ينتهي بـ Single toe)، والوظيفة قد تُسند لموظف واحد أو أكثر (assigned to — خط متقطع ينتهي بـ Crow's foot).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد تحويل عمود Commission إلى صفة اختيارية (o Commission) تطبيقاً دقيقاً لفهم قيود الواقع؛ فبينما يمتلك كل موظف راتباً أساسياً (* Salary)، فإن العمولة تنطبق على فئة فرعية فقط (موظفي المبيعات)، مما يوجب السماح بالقيمة الفارغة (NULL) في هذا العمود.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· انتبهي للعمود الاختياري الوحيد في هذا المثال: o Commission (العمولة اختيارية لأن ليس كل الموظفين يحصلون على عمولة).
· تذكري قاعدة الخطوط في الرسمة:
  · من EMPLOYEE إلى DEPARTMENT و JOB: خط متصل (Must) ينتهي بـ Single toe (One and only one).
  · من DEPARTMENT و JOB إلى EMPLOYEE: خط متقطع (May) ينتهي بـ Crow's foot (One or more).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من تحليل الصفات في السيناريو):
   In the HR System case scenario (EMPLOYEE, DEPARTMENT, JOB), why is the Commission attribute marked with a circle (o)?
   A) Because it is the Unique Identifier (UID) of the EMPLOYEE entity.
   B) Because it is an optional attribute; only employees on commission have a potential commission value.
   C) Because it is a mandatory attribute required for every employee.
   • الإجابة الصحيحة: B (العمولة صفة اختيارية Optional لأنها تخص الموظفين العاملين بالعمولة فقط).
2. Diagram Reading Question (قراءة العلاقات من مخطط HR System):
   Based on the HR System ER diagram in Slide 8, translate the relationship between EMPLOYEE and JOB into two ERDish sentences.
   • الإجابة النموذجية:

· Each EMPLOYEE must be assigned one and only one JOB.
· Each JOB may be assigned to one or more EMPLOYEEs.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية (ER Drawing Conventions: القواعد الرسومية للكيانات والصفات والعلاقات والمصطلحات في شرائح 9-13 من درس 3-2)!

تم، سأدوّن الشرائح الخمس الأخيرة من درس 3-2 (Slides 7, 8, 9, 10, & 11 — ER Drawing Conventions, Terminology, & Summary) بنفس القالب المنظم تماماً:

---

الشرائح السابعة والثامنة والتاسعة والعاشرة والحادية عشرة (Slides 7, 8, 9, 10, & 11)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-2 ER Diagramming Conventions (تصميم قواعد البيانات: 3-2 قواعد ومعايير رسم مخططات الكيانات والعلاقات).

2. Slide Number (رقم الشريحة)

• Slides 7, 8, 9, 10, & 11 (ترقيم أوراكل 9, 10, 11, 12, 13 من درس 3-2: ER Drawing Conventions, Terminology, & Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Softbox (مستطيل ناعم الزوايا): تُنطق (سوفت بوكس) — الشكل الهندسي المعتمد في أوراكل لتمثيل الكيان (Entity)؛ وهو مستطيل زواياه دائرية ناعمة وليست حادة.

• Singular (مفرد): تُنطق (سينجيولار) — قاعدة تسمية الكيانات؛ يُكتب اسم الكيان دائماً بصيغة المفرد (مثل EMPLOYEE, JOB, DEPARTMENT) وبأحرف كبيرة بالكامل (ALL CAPITAL LETTERS).

• Terminate in (تنتهي بـ): تُنطق (تيرمينيت إن) — نهاية خط العلاقة عند التقاءه بالكيان، وتكون إما Single toe (مفرد) أو Crow's foot (جمع).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

ER Drawing Conventions — Entities (Slide 9):

Entities are represented by softboxes.

Entity names go in the softboxes.

Entity names are always singular and written with all capital letters. (Examples: EMPLOYEE, JOB, DEPARTMENT)

Drawing Conventions — Attributes (Slide 10):

Attributes are listed under the entity names.

Mandatory attributes are marked with an asterisk: "*"

Optional attributes are marked with a circle: "o"

Unique identifiers are marked with a hash sign: "#"

Drawing Conventions — Relationships (Slide 11):

Relationships are lines that connect entities. These lines are either solid or dashed.

These lines terminate in either a "single toe" or a "crow's foot" at the end of each entity.

Terminology & Summary (Slides 12 & 13):

Key terms: Softbox, ER Diagramming, Crow's Foot, Single Toe.

Summary: Construct ER diagram components that represent entities and attributes according to diagramming conventions.

5. Explanation in Arabic (الشرح باللغة العربية وتلخيص قواعد الرسم الثلاث)

تُلخص هذه الشرائح الدليل الكامل لقواعد الرسم القياسية في منهج Oracle مقسماً إلى ثلاثة محاور رئيسية (موضع أسئلة مؤكدة في الامتحان):

• قواعد رسم الكيانات (Entities Conventions):

· تُرسم داخل مستطيل ناعم الزوايا يُسمى Softbox.
· يُكتب اسم الكيان بصيغة المفرد (Singular) دائماً (نكتب EMPLOYEE وليس EMPLOYEES).
· يُكتب اسم الكيان بأحرف كبيرة بالكامل (ALL CAPITAL LETTERS).

• قواعد رسم الصفات (Attributes Conventions):

· تُكتب قائمة الصفات أسفل اسم الكيان داخل الـ Softbox.
· الصفة الإلزامية تُسبق بنجمة *، والاختيارية تُسبق بدائرة o، والمعرّف الفريد يُسبق بعلامة مربع #.

• قواعد رسم العلاقات (Relationships Conventions):

· تُرسم كخطوط تصل بين الكيانات، وتكون إما متصلة (Solid = إلزامية) أو متقطعة (Dashed = اختيارية).
· ينتهي كل طرف من أطراف الخط إما بـ Single toe (خط مفرد = واحد وواحد فقط) أو بـ Crow's foot (رِجل الغراب = واحد أو أكثر).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد التفريق بين تسمية الكيان في التصميم المنطقي (مفرد: EMPLOYEE) وبين تسمية الجدول في قاعدة البيانات الفيزيائية (جمع: EMPLOYEES) قاعدة تنظيمية مهمة؛ لأن المخطط المنطقي (ERD) يصف سجل الكيان الواحد (Each EMPLOYEE...)، بينما الجدول الفيزيائي في SQL يمثل حاوية تضم مجموعة من السجلات.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 3 شروط لاسم الكيان في ERD (احفظيها كمعادلة):
  · الشكل: Softbox (مستطيل ناعم الزوايا).
  · العدد: Singular (مفرد دائماً: JOB وليس JOBS).
  · الحروف: ALL CAPITAL LETTERS (أحرف كبيرة بالكامل).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من قواعد رسم الكيانات):
   According to Oracle ER diagramming conventions, how are entities represented and named?
   A) Represented by sharp-edged rectangles, named in plural and lowercase.
   B) Represented by softboxes, with names always singular and written in all capital letters.
   C) Represented by circles, with names written in singular and lowercase.
   • الإجابة الصحيحة: B (تُمثَّل الكيانات بمستطيلات ناعمة الزوايا softboxes، وتُكتب أسماؤها دائماً بالمفرد singular وبأحرف كبيرة بالكامل all capital letters).
2. True or False (صح أم خطأ — فخ الجمع والمفرد):
   Statement: "In an ER diagram, entity names should always be written in plural form (such as EMPLOYEES and DEPARTMENTS) in all capital letters." (True / False)
   • الإجابة: False (خطأ) — أسماء الكيانات في مخطط ERD تُكتب دائماً بصيغة المفرد (Always singular) مثل EMPLOYEE و DEPARTMENT.

---

ألف مبروك! أنهيتِ الآن تدوين الدرس الثاني من شابتر 3 (3-2 ER Diagramming Conventions) بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الثالث (3-3 Speaking ERDish & Drawing Relationships: لغة قراءة ورسم العلاقات)!

تم، سأدوّن شرائح الدرس الثالث الأولى (Slides 1, 2, 3, & 4 — Speaking ERDish) بنفس القالب المنظم تماماً:

---

الشرائح الأولى والثانية والثالثة والرابعة (Slides 1, 2, 3, & 4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-3 Speaking ERDish & Drawing Relationships (تصميم قواعد البيانات: 3-3 التحدث بلغة ERDish ورسم العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 1, 2, 3, & 4 (ترقيم أوراكل 1, 3, 4, 5, 6 من درس 3-3: Objectives, Purpose, ERD Language, & The Components of ERDish).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• ERDish (لغة مخططات الكيانات والعلاقات): تُنطق (إي آر ديش) — المصطلحات والصياغة القياسية الدقيقة التي نستخدمها لقراءة وترجمة العلاقات المرسومة على مخطط ERD إلى جمل مفهومة للعملاء ومبرمجي قواعد البيانات.

• Industry-specific terminology (مصطلحات خاصة بالمجال): تُنطق (إنداستري-سبيسيفيك تيرمينولوجي) — المفردات المتخصصة في مهنة معينة (مثل الطب أو البنوك أو نمذجة البيانات) لتسهيل التواصل الدقيق.

• Database Administrators / DBAs (مديرو قواعد البيانات): تُنطق (داتابيس آدمنيستريتورز) — المهندسون المسؤولون عن بناء وتنفيذ وإدارة قواعد البيانات الفعلية بناءً على التصميم.

• Precise words (كلمات دقيقة / محددة): تُنطق (بريسايس ووردز) — صياغة خالية من الغموض تحدد الإلزامية والتعددية بدقة متناهية.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Slide 3):

State relationships between entities in precise words (ERDish)

Draw and label relationships correctly on an ERD

Purpose & ERD Language (Slides 4 & 5):

ERDish—the vocabulary used to clearly communicate the business rules that are captured on an ERD—will give you a common language both when collecting the business rules from your client and communicating them to the Database Administrators who will implement your design.

ERDish is the language we use to state relationships between entities in an ERD.

The Components of ERDish (Slide 6 — القالب المكون من 6 أجزاء):

EACH

Entity A

OPTIONALITY (must be / may be)

RELATIONSHIP NAME

CARDINALITY (one and only one / one or more)

Entity B

5. Explanation in Arabic (الشرح باللغة العربية)

تُقدّم هذه الشرائح مفهوم "لغة الـ ERDish" وتُقسم أي جملة علاقة إلى 6 أجزاء مرتبة لا تتغير أبداً:

• ما هي لغة ERDish؟ هي اللغة المشتركة التي تحول الخطوط والرموز الموجودة في مخطط ERD إلى جمل إنجليزية دقيقة، لتكون حلقة الوصل بين العميل (Client) الذي يملي القوانين وبين مدير قاعدة البيانات (DBA) الذي سيبني الجداول.

• الأجزاء الستة الثابتة لأي جملة ERDish: لقراءة أي علاقة، نرتب الكلمات الست بالترتيب التالي:

· الجزء 1: كلمة EACH (كل).
· الجزء 2: اسم Entity A (الكيان الأول الذي نبدأ منه القراءة).
· الجزء 3: OPTIONALITY (الاختيارية: نكتب must / must be إذا كان الخط متصلاً، أو may / may be إذا كان الخط متقطعاً).
· الجزء 4: RELATIONSHIP NAME (اسم العلاقة المكتوب بجانب الكيان الأول).
· الجزء 5: CARDINALITY (التعددية عند الطرف المقابل: نكتب one and only one إذا انتهى الخط بـ Single toe، أو one or more إذا انتهى بـ Crow's foot).
· الجزء 6: اسم Entity B (الكيان الثاني).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات هندسة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد تحويل المخططات الرسومية إلى جمل نصية قياسية (ERDish) آلية تحقق متبادلة (Bidirectional Validation)؛ فعندما تقرأين جملة ERDish بصوت عالٍ على العميل ("Each employee must work in one and only one department")، يستطيع العميل اكتشاف أي خطأ في فهم متطلبات شركته فوراً دون الحاجة لتعلم رموز ERD.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· احفظي الأجزاء الستة بالترتيب الرقمي (1 ➔ 6):
  · EACH
  · Entity A
  · Optionality (شكل الخط: متصل must / متقطع may)
  · Relationship Name (الفعل المكتوب قرب Entity A)
  · Cardinality (نهاية الخط عند Entity B: خط واحد one and only one / رِجل غراب one or more)
  · Entity B

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال تعريف لغة ERDish):
   What is "ERDish" in database modeling?
   A) A programming language used to write database triggers.
   B) The standard vocabulary and precise phrasing used to state relationships and communicate business rules captured on an ERD.
   C) A type of flat-file delimiter used in spreadsheets.
   • الإجابة الصحيحة: B (لغة ERDish هي المفردات القياسية المستخدمة للتعبير عن العلاقات وقواعد العمل في مخطط ERD).
2. Ordering / Fill in the Blanks (ترتيب مكونات جملة ERDish الستة):
   Arrange the six components of an ERDish sentence in their exact standard order:
   (Relationship Name, Entity A, Cardinality, EACH, Entity B, Optionality)
   • الإجابة النموذجية:
3. EACH
4. Entity A
5. Optionality (must be / may be)
6. Relationship Name
7. Cardinality (one and only one / one or more)
8. Entity B

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية (قراءة العلاقة من اليسار لليمين ومن اليمين لليسار + مثال BOOK و AUTHOR في شرائح 7-11 من درس 3-3)!

تم، سأدوّن الشرائح التطبيقية المتبقية من درس 3-3 (Slides 5, 6, 7, 8, & 9 — قراءة العلاقات في كلا الاتجاهين + مثال BOOK و AUTHOR + الملخص) بنفس القالب المنظم تماماً:

---

الشرائح الخامسة والسادسة والسابعة والثامنة والتاسعة (Slides 5, 6, 7, 8, & 9)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-3 Speaking ERDish & Drawing Relationships (تصميم قواعد البيانات: 3-3 التحدث بلغة ERDish ورسم العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 5, 6, 7, 8, & 9 (ترقيم أوراكل 7, 8, 9, 10, 11 من درس 3-3 وشريحتي DFo 2-6 أرقام 19, 20).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Left to right / Top to bottom (من اليسار لليمين / من الأعلى للأسفل): تُنطق (ليفت تو رايت / توب تو بوتوم) — الاتجاه الأول لقراءة العلاقة حسب تخطيط المخطط (ERD layout).

• Right to left (من اليمين لليسار): تُنطق (رايت تو ليفت) — الاتجاه المعاكس لقراءة الطرف الثاني من العلاقة.

• Dotted / Dashed line (خط متقطع): تُنطق (دوتيد / داشت لاين) — خط مكون من نقاط أو شرطات يدل على أن العلاقة اختيارية (Optional / may be).

• Solid line (خط متصل): تُنطق (سوليد لاين) — خط مستمر يدل على أن العلاقة إلزامية (Mandatory / must / must be).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Reading Relationships in Both Directions (Slides 7, 8, & 9):

Since each relationship has two sides, we read the relationship from left to right (or top to bottom, depending on the ERD layout) first, then from right to left.

Example 1: EMPLOYEE and DEPARTMENT (Slides 7–9):

Left to Right:

EACH ➔ 2. EMPLOYEE (entity A) ➔ 3. MUST (optionality, solid line) ➔ 4. WORK IN (relationship name) ➔ 5. ONE (AND ONLY ONE) (cardinality, single toe) ➔ 6. DEPARTMENT (entity B)

Right to Left:

EACH ➔ 2. DEPARTMENT (entity B) ➔ 3. MAY BE (optionality, dotted line) ➔ 4. RESPONSIBLE FOR (relationship name) ➔ 5. ONE OR MORE (cardinality, crow's foot) ➔ 6. EMPLOYEE (entity A)

Example 2: BOOK and AUTHOR (DFo 2-6 Slides 19–20):

Left to Right: EACH BOOK MUST BE WRITTEN BY ONE (AND ONLY ONE) AUTHOR.

Right to Left: EACH AUTHOR MAY BE THE AUTHOR OF ONE OR MORE BOOK.

Terminology & Summary (Slides 10 & 11):

Key term: ERDish

Summary: State relationships between entities in precise words (ERDish) & Draw and label relationships correctly on an ERD.

5. Explanation in Arabic (الشرح باللغة العربية وتعلم القاعدة الذهبية للرسم)

تُعطيكِ هذه الشرائح القاعدة البصرية الذهبية التي تمنع أي لخبطة عند قراءة أو رسم أي خط في الامتحان:

• القاعدة البصرية الذهبية لقراءة أي خط (كيف نقرأ من A إلى B؟):
عندما تبدئين القراءة من الكيان A متجهة نحو الكيان B:

· اقرئي اسم العلاقة المكتوب بجانب الكيان A (نقطة البداية).
· اقرئي شكل الخط (متصل must أو متقطع may) الخارج من الكيان A.
· اقرئي نهاية الخط (Single toe مفرد أو Crow's foot جمع) المتصلة بالكيان B (نقطة الوصول).

• تطبيق القاعدة على مثال الكتاب والمؤلف (BOOK و AUTHOR):

· من اليسار لليمين (BOOK ➔ AUTHOR):
  · الكيان الأول: BOOK، واسم العلاقة بجانبه: written by.
  · الخط الخارج من BOOK متصل (Solid line) ➔ نكتب MUST BE.
  · نهاية الخط عند AUTHOR هي خط مفرد (Single toe) ➔ نكتب ONE (AND ONLY ONE).
  · الجملة الكاملة: Each BOOK must be written by one (and only one) AUTHOR.
· من اليمين لليسار (AUTHOR ➔ BOOK):
  · الكيان الأول: AUTHOR، واسم العلاقة بجانبه: the author of.
  · الخط الخارج من AUTHOR متقطع (Dotted line) ➔ نكتب MAY BE.
  · نهاية الخط عند BOOK هي رِجل غراب (Crow's foot) ➔ نكتب ONE OR MORE.
  · الجملة الكاملة: Each AUTHOR may be the author of one or more BOOK.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التصميم الذي يكون فيه نصف الخط متصلاً ونصفه متقطعاً باسم "المشاركة غير المتماثلة" (Asymmetric Participation)؛ ففي مثال الكتاب والمؤلف (BOOK و AUTHOR)، لا يمكن إدخال كتاب في قاعدة البيانات بدون مؤلف (Mandatory من جهة الكتاب)، بينما يمكن تسجيل مؤلف جديد في النظام قبل أن يُنشر له كتاب (Optional من جهة المؤلف).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة البداية والنهاية (لمنع أي خطأ في القراءة):
  · الاسم والخط (Must / May) يُؤخذان من نقطة البداية (الكيان الذي تبدئين منه).
  · نهاية الخط (One / Many) تُؤخذ من نقطة الوصول (الكيان الذي تصلين إليه).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (تحليل الخطوط في مثال BOOK و AUTHOR):
   In the BOOK and AUTHOR ERD example, why is the relationship line solid near BOOK and dotted near AUTHOR?
   A) Because each BOOK must be written by an AUTHOR (mandatory), whereas an AUTHOR may or may not have written a BOOK yet (optional).
   B) Because each BOOK has many authors, and each AUTHOR writes only one book.
   C) Because AUTHOR is a weak attribute of BOOK.
   • الإجابة الصحيحة: A (الخط المتصل بجانب BOOK يعني أنه يجب أن يكون له مؤلف Must be، والخط المتقطع بجانب AUTHOR يعني أنه قد يكون مؤلفاً لكتاب أو أكثر May be).
2. Diagram Construction Question (سؤال رسم علاقة من جمل ERDish — متوقع جداً):
   Given the following two ERDish sentences, describe how to draw the relationship line between STUDENT and LOCKER:

· Each STUDENT may be assigned one and only one LOCKER.
· Each LOCKER must be assigned to one and only one STUDENT.
  • الإجابة النموذجية:
  · Near STUDENT: Dashed (dotted) line (since it is optional: may be) terminating in a single toe at STUDENT (since a locker is assigned to one and only one student).
  · Near LOCKER: Solid line (since it is mandatory: must be) terminating in a single toe at LOCKER (since a student is assigned one and only one locker).

---

ألف مبروك! أنهيتِ الآن تدوين الدرس الثالث من شابتر 3 (3-3 Speaking ERDish & Drawing Relationships) بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الرابع والأخير (3-4 Matrix Diagrams: مخططات المصفوفات لاكتشاف العلاقات)!


تم، سأدوّن شرائح الدرس الرابع الأولى (Slides 1, 2, 3, & 4 — Matrix Diagrams: Objectives, Purpose, & Travel Agency Scenario) بنفس القالب المنظم تماماً:

---

الشرائح الأولى والثانية والثالثة والرابعة (Slides 1, 2, 3, & 4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-4 Matrix Diagrams (تصميم قواعد البيانات: 3-4 مخططات المصفوفات لاكتشاف العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 1, 2, 3, & 4 (ترقيم أوراكل 1, 3, 4, 5, 6 من درس 3-4: Objectives, Purpose, & Travel Agency Business Scenario).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Matrix Diagram (مخطط المصفوفة): تُنطق (ماتريكس داياجرام) — جدول شبكي ثنائي الأبعاد يُستخدم لتنظيم واكتشاف جميع العلاقات الممكنة بين عدد كبير من الكيانات دون نسيان أي علاقة.

• Uncover / Discover relationships (اكتشاف العلاقات): تُنطق (أنكافر / ديسكافر ريليشنشيبس) — إيجاد الروابط المنطقية المخفية بين الجداول في الأنظمة الكبيرة.

• Travel agency (وكالة سفر وسياحة): تُنطق (ترافيل إيجنسي) — مثال تطبيقي يربط بين المسافر (TRAVELER) والدولة (COUNTRY) والمعلم السياحي (LANDMARK).

• Customize tours (تخصيص الجولات السياحية): تُنطق (كاستومايز تورز) — تصميم رحلات مخصصة للعملاء بناءً على سجل الدول التي زاروها والمعالم التي شاهدوها.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Slide 3):

Identify relationships using a matrix diagram

Draw an ERD from a matrix diagram

Purpose (Slides 4 & 5):

It is useful to know more than one way to discover relationships.

It may be simple enough to identify relationships given three entities (e.g., TEACHER, COURSE, CLASS). But what about finding relationships when you have thirteen or more entities? (e.g., TEACHER, COURSE, STUDENT, CLASS, EXAM, SEMESTER, CAFETERIA, GRADE, CLUB, CLASSROOM, SCHOOL, SCHOOL EQUIPMENT, MAINTENANCE STAFF, ...etc.)

Using a matrix diagram, especially when you are dealing with many entities, is a good way to make sure that you haven't missed any relationships.

Business Scenario (Slide 6):

"I work for a travel agency. I keep a record of the countries that our customers have visited and the landmarks they've seen in each country. It helps us customize tours for them."

We can use the matrix diagram to uncover relationships: (TRAVELER, COUNTRY, LANDMARK).

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الشرائح أهمية أداة مخطط المصفوفة (Matrix Diagram) في مرحلة تحليل المتطلبات قبل رسم مخطط ERD:

• المشكلة عند كثرة الكيانات: إذا كان نظامكِ صغيراً (مثل 3 كيانات فقط: مدرس، مساق، صف)، فمن السهل اكتشاف العلاقات بالنظر. أما في الأنظمة الضخمة (مثل نظام جامعة يضم 13 كياناً أو أكثر: طلاب، امتحانات، كافيتيريا، أندية، قاعات، معدات، موظفي صيانة...)، فمن السهل جداً أن ينسى المصمم علاقة مهمة بين جدولين.

• الحل (Matrix Diagram): نضع جميع الكيانات في الصفوف ونكررها بنفس الترتيب في الأعمدة؛ وبذلك نمر على كل مربع تقاطع بين كيانين ونسأل: "هل توجد علاقة بينهما؟".

• تطبيق وكالة السفر (Travel Agency): لدينا 3 كيانات (TRAVELER, COUNTRY, LANDMARK) نضعها في صفوف وأعمدة المصفوفة لنستخرج العلاقات بينها بدقة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف مخطط المصفوفة بـ "المراجعة المنهجية الشاملة للعلاقات" (Exhaustive Pairwise Relationship Audit)؛ فإذا كان لديكِ N كياناً، فإن المصفوفة تضمن فحص جميع الأزواج الممكنة (N(N-1)/2 زوجاً) دون إغفال أي رابط، وتُظلل مربعات القطر الرئيسي (تقاطع الكيان مع نفسه مثل TRAVELER مع TRAVELER) إلا إذا وجدت علاقة ذاتية (Recursive Relationship).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· متى نستخدم Matrix Diagram؟ (كلمة السر في الامتحان): When dealing with MANY entities (عند التعامل مع عدد كبير من الكيانات، مثل 13 كياناً أو أكثر، لضمان عدم نسيان أي علاقة to make sure that you haven't missed any relationships).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الشريحة 5):
   When is using a "Matrix Diagram" especially useful during database design?
   A) When writing SQL queries to delete duplicate rows.
   B) When dealing with many entities (e.g., 13 or more), to make sure no relationships are missed.
   C) When specifying column data types and precision in a physical model.
   • الإجابة الصحيحة: B (تُستخدم المصفوفة خصوصاً عند التعامل مع العديد من الكيانات لضمان عدم تفويت أي علاقة).
2. Short Question (سؤال مقالي قصير):
   State the two main objectives of Lesson 3-4 (Matrix Diagrams) and explain the main purpose of using a matrix diagram.
   • الإجابة النموذجية:

· Objectives: 1. Identify relationships using a matrix diagram. 2. Draw an ERD from a matrix diagram.
· Purpose: Especially when dealing with many entities, it ensures that the designer has not missed any relationships between entities.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح الأخيرة في شابتر 3 (قواعد قراءة وكتابة المصفوفة + حدود المصفوفة + مثال المستودع والطلبات CUSTOMER, ITEM, ORDER, WAREHOUSE في شرائح 7-11)!


تم، سأدوّن الشرائح الأخيرة من درس 3-4 (Slides 5, 6, 7, 8, & 9 — قواعد قراءة وكتابة المصفوفة + حدود المصفوفة + تحويل المصفوفة إلى ERD في مثال المستودع والطلبات) بنفس القالب المنظم تماماً:

---

الشرائح الخامسة والسادسة والسابعة والثامنة والتاسعة (Slides 5, 6, 7, 8, & 9)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 3-4 Matrix Diagrams (تصميم قواعد البيانات: 3-4 مخططات المصفوفات لاكتشاف العلاقات).

2. Slide Number (رقم الشريحة)

• Slides 5, 6, 7, 8, & 9 (ترقيم أوراكل 7, 8, 9, 10, 11 من درس 3-4 وشريحتي DFo 3-6 أرقام 17, 18).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Consistent in one direction (الالتزام باتجاه واحد ثابت): تُنطق (كونسيستنت إن وَن دايريكشن) — قاعدة ذهبية في قراءة وكتابة المصفوفة؛ نقرأ دائماً إما (من الصف إلى العمود) أو (من العمود إلى الصف) دون خلط الاتجاهين.

• Do not show optionality and cardinality (لا تُظهر الاختيارية والتعددية): من أهم خصائص المصفوفة؛ فهي تكشف وجود العلاقة واسمها فقط، ولا توضح هل هي إلزامية أم اختيارية (Must/May) ولا عددها (One/Many).

• Mapping the contents to an ERD (تحويل محتويات المصفوفة إلى مخطط ERD): تُنطق (مابينج ذا كونتنتس تو آن إي آر دي) — نقل أسماء العلاقات من خلايا المصفوفة إلى خطوط تربط الكيانات على مخطط ERD ثم إضافة الاختيارية والتعددية لها.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Matrix Diagrams — Reading Direction (Slide 7):

To avoid confusion, be consistent in writing to and reading from the matrix in only one direction.

Examples (Row ➔ Column):
– correct: COUNTRY visited by TRAVELER
– correct: LANDMARK seen by TRAVELER
– incorrect: TRAVELER visited by COUNTRY (عكس الاتجاه)
– incorrect: TRAVELER seen by LANDMARK (عكس الاتجاه)

Matrix Diagrams — Limitations & Next Step (Slides 8 & 9):

Relationships discovered via the matrix diagram are then drawn on the ERD.

Matrix diagrams do not show optionality and cardinality.

(Upon drawing on the ERD, we add optionality and cardinality, e.g.: Each COUNTRY may be visited by one or more TRAVELERs. Each TRAVELER may visit one or more COUNTRY.)

Relationship Matrix: Collecting & Mapping Information (DFo 3-6 Slides 17 & 18):

Entities: CUSTOMER, ITEM, ORDER, WAREHOUSE

Relationships mapped to ERD:
– CUSTOMER place ⟷ placed by ORDER
– ORDER issued for ⟷ contained on ITEM
– ITEM stored in ⟷ store WAREHOUSE

Terminology & Summary (Slides 10 & 11):

Key term: Matrix diagram

Summary: Identify relationships using a matrix diagram & Draw an ERD from a matrix diagram.

5. Explanation in Arabic (الشرح باللغة العربية وتعلم القاعدة الذهبية للمصفوفة)

تُختتم هذه الشرائح شابتر 3 بثلاث قواعد جوهرية ومضمونة في الامتحانات:

• قاعدة الاتجاه الواحد في القراءة (Row ➔ Column):
في مصفوفة وكالة السفر (TRAVELER, COUNTRY, LANDMARK)، نبدأ دائماً بقراءة اسم الكيان في الصف (يساراً) ➔ ثم الفعل داخل المربع ➔ ثم اسم الكيان في العمود (أعلى):

· صف COUNTRY + خلية visited by + عمود TRAVELER = COUNTRY visited by TRAVELER (صحيح ✅).
· صف TRAVELER + خلية visit + عمود COUNTRY = TRAVELER visit COUNTRY (صحيح ✅).
· أما قراءة العمود قبل الصف فتعطي جملة مقلوبة خاطئة (TRAVELER visited by COUNTRY ❌).

• أهم قيود المصفوفة (What Matrix Diagrams DO NOT Show):
المصفوفة أداة أولية لاكتشاف العلاقات وتسميتها فقط؛ فهي لا تُظهر الاختيارية (Optionality) ولا التعددية (Cardinality) (لا يوجد فيها خطوط متصلة أو متقطعة ولا رِجل غراب). نضيف هذه الرموز فقط عندما ننقل العلاقات من المصفوفة إلى مخطط ERD.

• التحويل العملي من المصفوفة إلى ERD (مثال المستودع والطلبات):
نأخذ كل علاقة مكتوبة في المصفوفة (مثل CUSTOMER place ORDER وعكسها ORDER placed by CUSTOMER) ونرسمها كخط يربط الكيانين على مخطط ERD، بينما المربعات الفارغة في المصفوفة (مثل تقاطع CUSTOMER مع WAREHOUSE) تعني عدم وجود علاقة مباشرة بينهما.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف مخطط المصفوفة بأنه "مصفوفة التجاور الدلالي" (Semantic Adjacency Matrix)؛ حيث تُظلل خلايا القطر الرئيسي (Diagonal Cells مثل تقاطع ORDER مع ORDER) إلا إذا وجدت علاقة ذاتية (Recursive Relationship)، وتكون المصفوفة متناظرة وظيفياً بحيث تحتوي الخلية (i, j) على الفعل المباشر وتحتوي الخلية (j, i) على الفعل العكسي. وبعد الانتهاء من المصفوفة، ينتقل المهندس إلى مرحلة إثراء القيود (Constraint Enrichment) على مخطط ERD لإضافة Optionality و Cardinality.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة الحقيقة المطلقة في الامتحان (موضع سؤال مؤكد):
  · Matrix diagrams DO NOT show optionality and cardinality (مخططات المصفوفات لا تُظهر الاختيارية ولا التعددية).
· قاعدة قراءة المصفوفة في 3 كلمات: صف ➔ خلية ➔ عمود (Row ➔ Cell ➔ Column).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. True or False (صح أم خطأ — السؤال الأشهر في درس 3-4):
   Statement: "Matrix diagrams clearly display both the optionality (mandatory/optional) and cardinality (one/many) of every relationship." (True / False)
   • الإجابة: False (خطأ) — تنص الشريحة 8 حرفياً على أن مخططات المصفوفات لا تُظهر الاختيارية والتعددية (Matrix diagrams do not show optionality and cardinality).
2. Multiple Choice (سؤال قاعدة قراءة المصفوفة):
   In the Travel Agency matrix diagram, if the row is LANDMARK, the intersecting cell contains seen by, and the column is TRAVELER, what is the correct way to read this relationship?
   A) TRAVELER seen by LANDMARK
   B) LANDMARK seen by TRAVELER
   C) COUNTRY seen by LANDMARK
   • الإجابة الصحيحة: B (نقرأ دائماً باتجاه واحد ثابت من الصف إلى العمود: LANDMARK ➔ seen by ➔ TRAVELER).
3. Diagram Mapping Question (قراءة العلاقات من مصفوفة المستودع في الشريحة 17):
   Look at the Relationship Matrix in Slide 17 (CUSTOMER, ITEM, ORDER, WAREHOUSE). Which entity has NO direct relationship with CUSTOMER?
   A) ORDER
   B) WAREHOUSE (and ITEM)
   • الإجابة الصحيحة: B (في صف CUSTOMER، الخلية الوحيدة الممتلئة هي مع ORDER بكلمة place، بينما الخلايا مع ITEM و WAREHOUSE فارغة تماماً).

---

ألف مبروك! أنهيتِ الآن تدوين شابتر 3 بالكامل (جميع الدروس الأربعة: 3-1 و 3-2 و 3-3 و 3-4) في دفتركِ! هل تودين أن نختم الآن بـ امتحان تجريبي شامل (Mock Exam) على شابتر 3 بالكامل بنمط أسئلة الكلية، أم لديكِ شرائح لشابتر 4؟

