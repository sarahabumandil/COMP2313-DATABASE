أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل الجدول المذكور في النص إلى جدول Markdown احترافي لتسهيل القراءة):

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — مقارنة مع الجدول الواحد).

2. Slide Number (رقم الشريحة)

· Slide 2 (الشريحة الثانية في ملف شابتر 2 — أعلى صورة image_zwcjAC.png: Single Table).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Single Table (الجدول الواحد): تُنطق (سينجل تيبل) — تصميم قاعدة البيانات بحيث تُوضع جميع البيانات في جدول واحد فقط.
· Flat File Database (قاعدة بيانات الملف المسطح): تُنطق (فلات فايل داتابيس) — نوع من قواعد البيانات يخزن البيانات في جدول واحد غير مرتبط بجداول أخرى.
· Plain-text form (صيغة نصية بسيطة): تُنطق (بلاين-تيكست فورم) — تخزين البيانات كسطور نصية عادية (مثل ملف المفكرة أو الإكسل البسيط) دون هياكل برمجية معقدة.
· Record (سجل): تُنطق (ريكورد) — السطر الأفقي الواحد في الجدول الذي يمثل بيانات شخص أو عنصر واحد (مثل Record 1 للعميل Rick Carmen).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Single Table

· As discussed previously, a flat file database is a type of database that stores data in a single table.
· Flat file databases are generally in plain-text form, where each line holds only one record.

 CUSTOMER_ID FIRST_NAME LAST_NAME ADDRESS CITY
Record 1 CN0001 Rick Carmen King Street Boston
Record 2 CN0002 Nick Doris 6 Rotrat Boston
Record 3 CN0003 Mary Pink Centrale Lagos

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تُمهّد هذه الشريحة للمقارنة بين الجدول الواحد (Single Table) وبين قاعدة البيانات العلائقية (Relational Database):

1. تخزين كل شيء في جدول واحد: بغض النظر عن البرنامج المستخدم (سواء كتبتِ الجدول على ملف Word، أو Excel، أو حتى أنشأتِ جدولاً واحداً يتيماً على Oracle أو Access كما أوضح المحاضر في التفريغ)، طالما أن كل البيانات محصورة في جدول واحد غير مرتبط بجداول أخرى، فهو يُسمى Single Table.
2. سطر واحد لكل سجل (One record per line): في هذا الجدول، كل سطر أفقي يمثل سجلاً واحداً كاملاً لعميل معين (مثلاً Record 1 يخص العميل رقم CN0001 واسمه Rick Carmen).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات علوم الحاسوب بجامعتي Harvard (CS50) و Stanford (CS145)، يُطلق على هذا التصميم اسم "التخزين المسطح غير المُطبّع" (Unnormalized Flat Storage)؛ فهو يبدو مقبولاً ما دمتِ تخزنين نوعاً واحداً فقط من البيانات (العملاء فقط)، لكنه ينهار ويسبب تكراراً وتضارباً بمجرد محاولة إضافة بيانات أخرى (مثل طلبات الشراء أو الكتب) إلى نفس الجدول.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة التذكر السريع: Flat File Database = Single Table (الملف المسطح هو نفسه الجدول الواحد).
  · قاعدة السطر: كل سطر يمثل سجلاً واحداً فقط (Each line holds only one record).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
Which of the following best defines a "Flat File / Single Table" database?

· A) A database that distributes data across multiple linked tables using foreign keys.
· B) A type of database that stores all data in a single table, generally in plain-text form where each line holds one record.
· C) A database organized in a strict parent-child tree structure.
· الإجابة الصحيحة: B (هذا هو التعريف الحرفي في الشريحة لقاعدة بيانات الجدول الواحد Single Table / Flat File).

2. True or False (صح أم خطأ):
Statement: "In a flat file (single table) database, each line generally holds multiple unrelated records." (True / False)

· الإجابة: False (خطأ) — كل سطر يحمل سجلاً واحداً فقط (Each line holds only one record).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 2، أخبريني لننتقل مباشرة إلى Slide 3 (Advantages and Disadvantages of a Flat File Database)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل الجدول المذكور في النص إلى جدول Markdown احترافي لتسهيل القراءة):

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — مثال عملي على عيوب الملف المسطح).

2. Slide Number (رقم الشريحة)

· Slide 4 (الشريحة الرابعة في ملف شابتر 2 — أسفل صورة image_zwcjAC.png: Example of a Flat File Database).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Repetition of values (تكرار القيم): تُنطق (ريبيتيشن أوف فاليوز) — إعادة كتابة نفس البيانات (مثل رقم المؤلف واسمه) في عدة سجلات داخل الجدول الواحد.
· Single Table (جدول واحد): تُنطق (سينجل تيبل) — دمج أكثر من موضوع أو كيان (الكتب + المؤلفين) في جدول واحد فقط.
· AUTHOR_ID (معرّف المؤلف): تُنطق (أوثور آي دي) — العمود الخاص بالرقم التعريفي الفريد للمؤلف.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Example of a Flat File Database

 AUTHOR_ID AUTHOR_NAME TITLE
Record 1 AD0001 Oscar Wilde A Vision
Record 2 AD0002 Leo Tolstoy War and Peace
Record 3 AD0003 Oliver Goldsmith Citizen of the World
Record 4 AD0003 Oliver Goldsmith Androcles and the Lion

Notice that both the details for the books and authors are stored in this single table, and there is a repetition of values.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تقدم هذه الشريحة مثالاً عملياً يثبت كيف يتحول التكرار (Redundancy) إلى تناقض وعدم تناسق (Inconsistency) في الجدول الواحد:

· دمج الكتب والمؤلفين في جدول واحد: وضعنا رقم المؤلف واسمه مع عنوان الكتاب في جدول واحد.
· حدوث التكرار (Repetition of values): في Record 3 و Record 4، تكرر رقم المؤلف AD0003 واسمه Oliver Goldsmith مرتين لأن لديه كتابين مختلفين.
· السيناريو الكارثي الذي شرحه المحاضر في التفريغ:
  · قال المحاضر: "تخيلوا لو جئت في Record 3 وعدّلت اسم المؤلف أو رقمه، ونسيت تعديله في Record 4!".
  · النتيجة: سيصبح لنفس المؤلف رقمان مختلفان أو اسمان مختلفان داخل نفس الملف (تماماً كأن يكون لطالب واحد رقمان جامعيان!)، وهنا تقع كارثة Data Inconsistency التي تمنعنا من الوثوق بدقة البيانات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى هذا المثال كبرهان عملي على "مبدأ الكيان الواحد لكل جدول" (One Entity Per Table Principle)؛ فالخطأ هنا هو خلط صفتين لكيانين مختلفين (AUTHOR_NAME يصف المؤلف، و TITLE يصف الكتاب) في جدول واحد، مما يسبب تكرار بيانات الأب (المؤلف) بعدد مرات ظهور الابن (الكتب). الحل هو فصل الجدول إلى جدولين (AUTHORS و BOOKS).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري السطرين 3 و 4 (Oliver Goldsmith): هما الدليل العملي على اجتماع العيبين معاً: التكرار (Redundancy) أولاً، ثم عدم التناسق (Inconsistency) إذا عُدِّل أحدهما ونُسي الآخر.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
In the provided Flat File example (AUTHOR_ID, AUTHOR_NAME, TITLE), if an administrator updates Oliver Goldsmith's ID in Record 3 but forgets to update it in Record 4, what problem occurs?

· A) Data Encryption
· B) Data Inconsistency
· C) Faster Querying
· الإجابة الصحيحة: B (تعديل القيمة المكررة في سجل ونسيانها في السجل الآخر يؤدي إلى عدم تناسق البيانات Data Inconsistency).

2. True or False (صح أم خطأ):
Statement: "Storing both book details and author details in a single table eliminates the repetition of data values." (True / False)

· الإجابة: False (خطأ) — تخزين تفاصيل الكتب والمؤلفين في جدول واحد يسبب تكرار القيم (Repetition of values) كما ظهر في السطرين 3 و 4.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 4، أخبريني لننتقل مباشرة إلى Slide 5 (Relational Databases: خصائص قاعدة البيانات العلائقية)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية).

2. Slide Number (رقم الشريحة)

· Slide 5 (الشريحة الخامسة في ملف شابتر 2 — أعلى صورة image_kmqKLB.png: Relational Databases).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Particular type of information (نوع محدد من المعلومات): تُنطق (بارتيكيولار تايب أوف إنفورميشن) — تخصيص كل عمود في الجدول لتخزين نوع واحد محدد من البيانات (مثل عمود الاسم الأخير LAST_NAME أو تاريخ الميلاد DATE_OF_BIRTH).
· Field (حقل): تُنطق (فيلد) — مرادف للعمود (Column) في سياق وصف نوع المعلومة، أو الخلية الواحدة في الجدول.
· Record (سجل): تُنطق (ريكورد) — مرادف للصف (Row) في الجدول، ويمثل جميع بيانات عنصر أو شخص واحد بالكامل.
· Common field (حقل مشترك): تُنطق (كومون فيلد) — العمود المشترك بين جدولين لربطهما ببعضهما البعض (Primary Key في جدول و Foreign Key في الجدول الآخر).
· Unique field / Key (حقل فريد / مفتاح): تُنطق (يونيك فيلد / كي) — عمود لا تتكرر قيمه ويُستخدم لتمييز كل سجل في الجدول عن بقية السجلات (مثل الرقم الجامعي).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Relational Databases

· A relational database presents information in tables with rows and columns.
· Each column represents a particular type of information (a field), and each row lists one record.
· The tables are then related to one another by using a common field.
· A unique field called a key is used to identify each record in a relational database.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تُلخص هذه الشريحة المكونات الأربعة الأساسية لقاعدة البيانات العلائقية (Relational Database) كما شرحها المحاضر بالتفصيل:

1. العرض في جداول (Tables with rows and columns): تُنظم المعلومات في مجموعة جداول مكونة من صفوف أفقية وأعمدة رأسية.
2. وظيفة العمود والصف (Column = Field, Row = Record):
   · كل عمود (Column) يمثل نوعاً محدداً من البيانات (مثل عمود اسم العائلة LAST_NAME، وعمود تاريخ الميلاد DATE_OF_BIRTH).
   · كل صف (Row) يسرد سجلاً واحداً (One record) لكيان معين (مثل جميع بيانات طالب واحد).
3. الربط عبر حقل مشترك (Common field): لا تعمل الجداول منعزلة، بل نربطها ببعضها باستخدام عمود مشترك بينها (مثل ربط جدول الطلاب بجدول المساقات).
4. المفتاح الفريد (Unique field called a key): كل جدول يجب أن يحتوي على عمود فريد (لا يتكرر) يُسمى المفتاح (Key) لتمييز كل سجل عن الآخر؛ وضرب المحاضر مثالاً بطالبين يحملان نفس اسم العائلة "أبو راس" وتاريخ الميلاد والعنوان، وكيف أن عمود الرقم الجامعي (Key) هو الوحيد الذي يميز هذا الطالب عن ذاك.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى هذه النقاط الأربع باعتبارها "الهندسة المعمارية للنموذج العلائقي" (Relational Architecture)؛ فبدلاً من استخدام مؤشرات ذاكرة معقدة كما في النماذج القديمة، يربط النموذج العلائقي الجداول منطقياً عبر تطابق القيم في حقل مشترك (Common field)، ويضمن الوصول المباشر لأي سجل دون لبس عبر المفتاح (Key).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلات المصطلحات الأربعة في الشريحة:
    1. Column = Particular type of information (a field) (نوع معلومة محدد).
    2. Row = One record (سجل واحد).
    3. Common field = Relates tables to one another (يربط الجداول ببعضها).
    4. Unique field (Key) = Identifies each record (يميز كل سجل).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من النقطة الثالثة):
How are tables related to one another in a relational database?

· A) By storing all tables inside a single plain-text file.
· B) By using a common field shared between the tables.
· C) By arranging records in a parent-child tree without keys.
· الإجابة الصحيحة: B (الجداول ترتبط ببعضها باستخدام حقل مشترك By using a common field).

2. Fill in the Blanks / Multiple Choice (سؤال تعريف المفتاح):
A unique field called a __________ is used to identify each record in a relational database.

· A) Delimiter
· B) Key
· C) Record
· الإجابة الصحيحة: B (الحقل الفريد الذي يميز كل سجل يُسمى المفتاح Key).

3. True or False (صح أم خطأ):
Statement: "In a relational database, each row represents a particular type of information (a field), and each column lists one complete record." (True / False)

· الإجابة: False (خطأ) — العكس هو الصحيح؛ كل عمود (Column) يمثل نوعاً محدداً من المعلومات (Field)، وكل صف (Row) يسرد سجلاً واحداً (One record).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 5، أخبريني لننتقل مباشرة إلى Slide 6 (Relational Database: Example - مثال ربط جدول الطلاب STUDENTS بجدول المساقات COURSES)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — مميزات قاعدة البيانات متعددة الجداول).

2. Slide Number (رقم الشريحة)

· Slide 7 (الشريحة السابعة في ملف شابتر 2 — أسفل صورة image_kmqKLB.png: Advantages of a Relational (Multiple-Table) Database).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Less redundancy (تقليل التكرار): تُنطق (ليس ريداندانسي) — خفض تكرار البيانات إلى الحد الأدنى من خلال توزيعها على جداول منفصلة.
· Avoidance of inconsistency (تجنب عدم التناسق): تُنطق (أفويدانس أوف إنكونسيستانسي) — منع تضارب البيانات وتناقضها؛ لأن أي تعديل في مكان واحد ينعكس تلقائياً على بقية النظام.
· Efficiency (الكفاءة والفعالية): تُنطق (إفيشينسي) — سرعة وكفاءة تخزين البيانات واسترجاعها والبحث فيها وتوفير مساحة التخزين.
· Data integrity (تكامل ودقة البيانات): تُنطق (داتا إنتيجريتي) — ضمان صحة وجودة وسلامة البيانات ومنع إدخال قيم فارغة أو خاطئة عبر القيود البرمجية (مثل NOT NULL و Primary Key).
· Confidentiality (السرية والخصوصية): تُنطق (كونفيدينشياليتي) — حماية البيانات الحساسة وتوزيع الصلاحيات بين المستخدمين (طالب، مدرس، موظف) وتشفير البيانات الهامة مثل كلمات المرور.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Advantages of a Relational (Multiple-Table) Database

· Less redundancy
· Avoidance of inconsistency
· Efficiency
· Data integrity
· Confidentiality
· *See Notes for more detail

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تُلخص هذه الشريحة المزايا الخمس الكبرى التي تجعل قاعدة البيانات العلائقية (متعددة الجداول) تتفوق على الملف المسطح، وقد شرحها المحاضر في التفريغ بعمق وأمثلة واقعية:

1. تقليل التكرار (Less redundancy): لم يقل "انعدام التكرار 100%" لأن رقم المساق أو القسم يتكرر كمفتاح أجنبي (Foreign Key) للربط، لكنه تكرار منطقي ومحدود جداً مقارنة بالملف المسطح.
2. تجنب عدم التناسق (Avoidance of inconsistency): إذا تغير رقم مساق مقدمة في قواعد البيانات من A1 إلى A10 في جدول المساقات، ينعكس ذلك فوراً على جميع الطلاب المسجلين فيه دون الحاجة لتعديله يدوياً في مئات الصفوف.
3. الكفاءة (Efficiency): الوصول للبيانات وتعديلها وحذفها يتم بسرعة ودقة عالية جداً دون استهلاك مساحات تخزين ضائعة.
4. تكامل ودقة البيانات (Data integrity): ضرب المحاضر مثال موظف القبول والتسجيل المضغوط بالعمل؛ فبفضل قيود قاعدة البيانات العلائقية (مثل قيد NOT NULL على اسم الطالب وقيد Primary Key على رقمه الجامعي)، يمنع النظام حفظ سجل طالب بدون اسم أو برقم مكرر، مما يضمن دقة البيانات وصحتها.
5. السرية والخصوصية (Confidentiality): تمكّنك من إخفاء جداول أو أعمدة معينة عن مستخدمين محددين (مثلاً الطالب لا يرى جداول المدرسين)، بالإضافة إلى إمكانية تشفير البيانات الحساسة مثل عمود كلمات المرور (Passwords).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات أنظمة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُفسَّر اختيار مصطلح Less redundancy بدلاً من Zero redundancy بأن المفتاح الأجنبي (Foreign Key) يمثل تكراراً مضبوطاً (Controlled Redundancy)؛ لأننا نكرر معرف القسم فقط للربط بدلاً من تكرار اسم القسم وعنوانه وميزانيته. كما تفرق MIT بدقة بين Integrity (حماية البيانات من الأخطاء والفساد عبر القيود) و Confidentiality (حماية البيانات من الاطلاع غير المصرح به عبر الصلاحيات والتشفير).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · احفظي المزايا الخمس بقاعدة الحروف (L - A - E - D - C):
    1. Less redundancy (تقليل التكرار).
    2. Avoidance of inconsistency (تجنب عدم التناسق).
    3. Efficiency (الكفاءة).
    4. Data integrity (تكامل ودقة البيانات).
    5. Confidentiality (السرية).
  · اربطي كل ميزة بمثال المحاضر: Data integrity = قيد NOT NULL على اسم الطالب | Confidentiality = تشفير الباسوورد وصلاحيات القبول والتسجيل.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
Which of the following is NOT listed as an advantage of a Relational (Multiple-Table) Database?

· A) Less redundancy
· B) Data integrity
· C) Confidentiality
· D) High data inconsistency
· الإجابة الصحيحة: D (قاعدة البيانات العلائقية تحقق تجنب عدم التناسق Avoidance of inconsistency، وليس زيادته).

2. Multiple Choice (ربط المفهوم بمثال المحاضر):
Enforcing constraints like NOT NULL on a student's name and PRIMARY KEY on student IDs to ensure accurate and valid data falls under which advantage of relational databases?

· A) Confidentiality
· B) Data integrity
· C) Data redundancy
· الإجابة الصحيحة: B (ضمان دقة وصحة البيانات ومنع القيم الفارغة أو الخاطئة يُعرف بـ Data integrity).

3. Short Essay / Enumeration (سؤال مقالي قصير):
List the five advantages of a Relational (Multiple-Table) Database and briefly explain Data integrity and Confidentiality.

· الإجابة النموذجية: 
  The five advantages are: Less redundancy, Avoidance of inconsistency, Efficiency, Data integrity, and Confidentiality.
  · Data integrity: Ensures the accuracy, quality, and validity of data by enforcing constraints (e.g., NOT NULL and Primary Key rules).
  · Confidentiality: Protects sensitive data through role-based access permissions and data encryption (e.g., encrypting passwords).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 7، أخبريني لننتقل مباشرة إلى Slide 8 (Relational Tables: جدول الموظفين EMPLOYEES وأنواع المفاتيح PK, FK, UK)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — مميزات قاعدة البيانات متعددة الجداول).

2. Slide Number (رقم الشريحة)

· Slide 7 (الشريحة السابعة في ملف شابتر 2 — أسفل صورة image_kmqKLB.png: Advantages of a Relational (Multiple-Table) Database).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Less redundancy (تقليل التكرار): تُنطق (ليس ريداندانسي) — خفض تكرار البيانات إلى الحد الأدنى من خلال توزيعها على جداول منفصلة.
· Avoidance of inconsistency (تجنب عدم التناسق): تُنطق (أفويدانس أوف إنكونسيستانسي) — منع تضارب البيانات وتناقضها؛ لأن أي تعديل في مكان واحد ينعكس تلقائياً على بقية النظام.
· Efficiency (الكفاءة والفعالية): تُنطق (إفيشينسي) — سرعة وكفاءة تخزين البيانات واسترجاعها والبحث فيها وتوفير مساحة التخزين.
· Data integrity (تكامل ودقة البيانات): تُنطق (داتا إنتيجريتي) — ضمان صحة وجودة وسلامة البيانات ومنع إدخال قيم فارغة أو خاطئة عبر القيود البرمجية (مثل NOT NULL و Primary Key).
· Confidentiality (السرية والخصوصية): تُنطق (كونفيدينشياليتي) — حماية البيانات الحساسة وتوزيع الصلاحيات بين المستخدمين (طالب، مدرس، موظف) وتشفير البيانات الهامة مثل كلمات المرور.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Advantages of a Relational (Multiple-Table) Database

· Less redundancy
· Avoidance of inconsistency
· Efficiency
· Data integrity
· Confidentiality
· *See Notes for more detail

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تُلخص هذه الشريحة المزايا الخمس الكبرى التي تجعل قاعدة البيانات العلائقية (متعددة الجداول) تتفوق على الملف المسطح، وقد شرحها المحاضر في التفريغ بعمق وأمثلة واقعية:

1. تقليل التكرار (Less redundancy): لم يقل "انعدام التكرار 100%" لأن رقم المساق أو القسم يتكرر كمفتاح أجنبي (Foreign Key) للربط، لكنه تكرار منطقي ومحدود جداً مقارنة بالملف المسطح.
2. تجنب عدم التناسق (Avoidance of inconsistency): إذا تغير رقم مساق مقدمة في قواعد البيانات من A1 إلى A10 في جدول المساقات، ينعكس ذلك فوراً على جميع الطلاب المسجلين فيه دون الحاجة لتعديله يدوياً في مئات الصفوف.
3. الكفاءة (Efficiency): الوصول للبيانات وتعديلها وحذفها يتم بسرعة ودقة عالية جداً دون استهلاك مساحات تخزين ضائعة.
4. تكامل ودقة البيانات (Data integrity): ضرب المحاضر مثال موظف القبول والتسجيل المضغوط بالعمل؛ فبفضل قيود قاعدة البيانات العلائقية (مثل قيد NOT NULL على اسم الطالب وقيد Primary Key على رقمه الجامعي)، يمنع النظام حفظ سجل طالب بدون اسم أو برقم مكرر، مما يضمن دقة البيانات وصحتها.
5. السرية والخصوصية (Confidentiality): تمكّنك من إخفاء جداول أو أعمدة معينة عن مستخدمين محددين (مثلاً الطالب لا يرى جداول المدرسين)، بالإضافة إلى إمكانية تشفير البيانات الحساسة مثل عمود كلمات المرور (Passwords).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات أنظمة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُفسَّر اختيار مصطلح Less redundancy بدلاً من Zero redundancy بأن المفتاح الأجنبي (Foreign Key) يمثل تكراراً مضبوطاً (Controlled Redundancy)؛ لأننا نكرر معرف القسم فقط للربط بدلاً من تكرار اسم القسم وعنوانه وميزانيته. كما تفرق MIT بدقة بين Integrity (حماية البيانات من الأخطاء والفساد عبر القيود) و Confidentiality (حماية البيانات من الاطلاع غير المصرح به عبر الصلاحيات والتشفير).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · احفظي المزايا الخمس بقاعدة الحروف (L - A - E - D - C):
    1. Less redundancy (تقليل التكرار).
    2. Avoidance of inconsistency (تجنب عدم التناسق).
    3. Efficiency (الكفاءة).
    4. Data integrity (تكامل ودقة البيانات).
    5. Confidentiality (السرية).
  · اربطي كل ميزة بمثال المحاضر: Data integrity = قيد NOT NULL على اسم الطالب | Confidentiality = تشفير الباسوورد وصلاحيات القبول والتسجيل.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
Which of the following is NOT listed as an advantage of a Relational (Multiple-Table) Database?

· A) Less redundancy
· B) Data integrity
· C) Confidentiality
· D) High data inconsistency
· الإجابة الصحيحة: D (قاعدة البيانات العلائقية تحقق تجنب عدم التناسق Avoidance of inconsistency، وليس زيادته).

2. Multiple Choice (ربط المفهوم بمثال المحاضر):
Enforcing constraints like NOT NULL on a student's name and PRIMARY KEY on student IDs to ensure accurate and valid data falls under which advantage of relational databases?

· A) Confidentiality
· B) Data integrity
· C) Data redundancy
· الإجابة الصحيحة: B (ضمان دقة وصحة البيانات ومنع القيم الفارغة أو الخاطئة يُعرف بـ Data integrity).

3. Short Essay / Enumeration (سؤال مقالي قصير):
List the five advantages of a Relational (Multiple-Table) Database and briefly explain Data integrity and Confidentiality.

· الإجابة النموذجية: 
  The five advantages are: Less redundancy, Avoidance of inconsistency, Efficiency, Data integrity, and Confidentiality.
  · Data integrity: Ensures the accuracy, quality, and validity of data by enforcing constraints (e.g., NOT NULL and Primary Key rules).
  · Confidentiality: Protects sensitive data through role-based access permissions and data encryption (e.g., encrypting passwords).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 7، أخبريني لننتقل مباشرة إلى Slide 8 (Relational Tables: جدول الموظفين EMPLOYEES وأنواع المفاتيح PK, FK, UK)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل جدول الموظفين المذكور في النص إلى جدول Markdown احترافي لتسهيل القراءة):

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — الجداول العلائقية وأنواع المفاتيح).

2. Slide Number (رقم الشريحة)

· Slide 8 (الشريحة الثامنة في ملف شابتر 2 — أعلى صورة image_eYPQC_.png: Relational Tables).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Relational Tables (الجداول العلائقية): تُنطق (ريليشنال تيبلز) — هياكل بسيطة مكونة من صفوف وأعمدة لتنظيم وتخزين البيانات في قاعدة البيانات العلائقية.
· Primary Key Column / PK (عمود المفتاح الأساسي): تُنطق (برايمري كي كولوم) — العمود الرسمي المعتمد للبحث وتمييز كل سجل في الجدول، ولا يقبل التكرار أو القيم الفارغة (مثل EMPLOYEE_ID).
· Foreign Key Column / FK (عمود المفتاح الأجنبي): تُنطق (فورين كي كولوم) — العمود الذي يربط هذا الجدول بجدول آخر (مثل DEPARTMENT_ID)، وتُسمح فيه القيم المكررة.
· Unique Key Column / UK (عمود المفتاح الفريد): تُنطق (يونيك كي كولوم) — عمود آخر في الجدول قيمه فريدة ولا تتكرر (مثل رقم كشف الرواتب PAYROLL_ID أو الإيميل الجامعي)، لكنه لم يُختَر ليكون المفتاح الأساسي الرسمي للجدول.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Relational Tables

A table is a simple structure where data is organized and stored.

Table: EMPLOYEES

EMPLOYEE_ID (PK) LAST_NAME FIRST_NAME DEPARTMENT_ID (FK) PAYROLL_ID (UK) NICKNAME
100 SMITH DANA 10 21215 Dana
310 ADAMS TYLER 15 59877 Ty
210 CHEN LAWRENCE 10 1101 Larry
405 GOMEZ CARLOS 10 52 Chaz
378 LOUNGANI NEIL 22 90386 Neil

· Primary Key Column (PK): EMPLOYEE_ID
· Foreign Key Column (FK): DEPARTMENT_ID
· Unique Key Column (UK): PAYROLL_ID

** Note : types of keys shown here will be discussed later in the lesson and course.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تستعرض هذه الشريحة جدول الموظفين (EMPLOYEES) لتوضيح الفرق العملي بين أنواع المفاتيح الثلاثة (PK, FK, UK) داخل الجدول الواحد، وقد ربطها المحاضر في التفريغ بمثال الطالب في الكلية الجامعية:

· المفتاح الأساسي (PK - EMPLOYEE_ID):
  · هو الرقم الوظيفي للموظف (100, 310, 210...).
  · لا يتكرر أبداً، لا يقبل قيمة فارغة (NOT NULL)، وهو المرجع الرئيسي الذي نستخدمه دائماً للبحث عن الموظف وتمييزه (تماماً مثل الرقم الجامعي للطالب).
· المفتاح الأجنبي (FK - DEPARTMENT_ID):
  · هو رقم القسم الذي يعمل فيه الموظف (10, 15, 22).
  · لاحظي أن الرقم 10 تكرر ثلاث مرات (للموظفين SMITH, CHEN, GOMEZ)؛ لأن المفتاح الأجنبي يُسمح بتكرار قيمه لربط عدة موظفين بنفس القسم.
· المفتاح الفريد (UK - PAYROLL_ID):
  · هو عمود قيمه لا تتكرر (21215, 59877, 1101, 52, 90386)، لكنه ليس المفتاح الأساسي الرسمي للجدول.
  · مثال المحاضر لتوضيح الفرق بين PK و UK: في جدول الطالب بالكلية الجامعية، كل طالب له رقم جامعي لا يتكرر (PK)، وله أيضاً إيميل جامعي لا يتكرر (UK). كلاهما فريد، لكننا نعتمد الرقم الجامعي كمفتاح أساسي (PK) في جميع معاملاتنا، بينما نضع قيد Unique Key (UK) على الإيميل الجامعي لمنع إعطاء نفس الإيميل لطالبين مختلفين.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا المفهوم باسم "المفاتيح المرشحة والمفاتيح البديلة" (Candidate Keys & Alternate Keys)؛ فالجدول قد يمتلك أكثر من عمود صالح لتمييز الصفوف، فنختار واحداً ليكون Primary Key (PK)، ونضع قيد Unique Key (UK) على البقية لضمان عدم تكرارها. وتؤكد MIT على فرق برمجي مهم في أوراكل: عمود PK يمنع التكرار ويمنع القيم الفارغة (NOT NULL) قطعياً، بينما عمود UK يمنع التكرار ولكنه قد يسمح بقيمة فارغة (NULL) إذا لم نمنعها صراحةً.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قاعدة المحاضر الذهبية (الفرق بين PK و UK):
    · كل Primary Key هو بالضرورة Unique (فريد تلقائياً).
    · ولكن ليس كل Unique Key هو Primary Key (الإيميل الجامعي فريد UK، لكنه ليس المفتاح الأساسي PK).
  · مقارنة الأعمدة الثلاثة في الجدول:
    · EMPLOYEE_ID (PK) ➔ لا يتكرر، وهو الأساس.
    · DEPARTMENT_ID (FK) ➔ يتكرر (لاحظي 10 مكررة 3 مرات)، ويربط مع جدول الأقسام.
    · PAYROLL_ID (UK) ➔ لا يتكرر، لكنه عمود إضافي فريد وليس المفتاح الأساسي.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من جدول الشريحة):
In the EMPLOYEES table shown in the lecture, which column is designated as a Unique Key (UK)?

· A) EMPLOYEE_ID
· B) DEPARTMENT_ID
· C) PAYROLL_ID
· D) NICKNAME
· الإجابة الصحيحة: C (يشير السهم الثالث أسفل الجدول بوضوح إلى أن عمود PAYROLL_ID هو عمود المفتاح الفريد Unique Key Column - UK).

2. True or False (صح أم خطأ — قاعدة المحاضر الذهبية):
Statement: "Every Primary Key column is implicitly Unique, and every Unique Key column is automatically considered a Primary Key." (True / False)

· الإجابة: False (خطأ) — كل مفتاح أساسي هو فريد تلقائياً، أما المفتاح الفريد (Unique Key مثل الإيميل الجامعي أو PAYROLL_ID) فيمنع التكرار ولكنه لا يُعتبر مفتاحاً أساسياً (Primary Key).

3. Short Essay / Comparison Question (سؤال مقالي قصير):
Compare between Primary Key (PK), Foreign Key (FK), and Unique Key (UK) using examples from the EMPLOYEES table (or university database).

· الإجابة النموذجية:
  · Primary Key (PK): The main column used to uniquely identify each row in a table; it cannot contain duplicates or NULL values (e.g., EMPLOYEE_ID or Student ID).
  · Foreign Key (FK): A column that refers to a Primary Key in another table to establish a relationship; duplicate values are allowed (e.g., DEPARTMENT_ID appearing multiple times in EMPLOYEES).
  · Unique Key (UK): A column whose values must be unique (no duplicates allowed), but it is not chosen as the table's primary identifier (e.g., PAYROLL_ID or a student's university email).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 8، أخبريني لننتقل مباشرة إلى Slide 9 (Rules for Relational Database Tables: القواعد السبعة للجداول في قاعدة البيانات العلائقية)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — القواعد السبعة للجداول العلائقية).

2. Slide Number (رقم الشريحة)

· Slide 9 (الشريحة التاسعة في ملف شابتر 2 — وسط صورة image_eYPQC_.png: Rules for Relational Database Tables).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Distinct name (اسم مميز / فريد): تُنطق (ديستينكت نيم) — اسم خاص لكل جدول داخل قاعدة البيانات لا يتكرر مع جدول آخر.
· Single values (قيم مفردة): تُنطق (سينجل فاليوز) — احتواء كل خلية (تقاطع صف وعمود) على قيمة واحدة فقط وليس مجموعة قيم.
· Of the same kind (من نفس النوع): تُنطق (أوف ذا سيم كايند) — تجانس نوع البيانات (Datatype) في العمود الواحد (أرقام فقط، أو نصوص فقط).
· Insignificant (غير مهم / غير مؤثر): تُنطق (إنسِجنيفيكانت) — صفة تشير إلى أن ترتيب الصفوف أو الأعمدة داخل الجدول لا يؤثر على صحة البيانات أو عمل قاعدة البيانات.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Rules for Relational Database Tables

· Each table has a distinct name.
· Each table may contain multiple rows.
· Each table has a value to uniquely identify the rows.
· Each column in a table has a unique name.
· Entries in columns are single values.
· Entries in columns are of the same kind.
· Order of rows and columns is insignificant.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تستعرض هذه الشريحة القوانين السبعة الصارمة التي تحكم بناء أي جدول في قاعدة البيانات العلائقية (على برنامج Oracle وغيره)، وقد شرحها المحاضر في التفريغ بأمثلة عملية واضحة:

· لكل جدول اسم مميز (Each table has a distinct name): داخل قاعدة البيانات الواحدة، ممنوع إنشاء جدولين بنفس الاسم (مثلاً جدولان باسم STUDENT).
· الجدول قد يحتوي على صفوف متعددة (Each table may contain multiple rows): يمكن أن يضم الجدول صفاً واحداً، أو عشرات الآلاف من الصفوف (السجلات).
· وجود قيمة لتمييز كل صف (Each table has a value to uniquely identify the rows): وجود عمود Primary Key يضمن عدم تشابه صفين أبداً (مثل الرقم الجامعي).
· كل عمود في الجدول له اسم فريد (Each column in a table has a unique name): داخل جدول STUDENT الواحد، لا يجوز تكرار اسم العمود ID مرتين؛ ولكن يجوز وجود عمود اسمه ID في جدول STUDENT وعمود آخر اسمه ID في جدول COURSE.
· المدخلات في الأعمدة هي قيم مفردة (Entries in columns are single values): ممنوع وضع قيمتين في نفس الخلية (مثل كتابة رقمين جامعيين أو مساقين في خلية واحدة لطالب واحد).
· المدخلات في العمود الواحد من نفس النوع (Entries in columns are of the same kind): إذا صممتِ عمود ID ليكون نوعه رقماً (Number)، سيرفض النظام إدخال نص مثل "Smith" فيه.
· ترتيب الصفوف والأعمدة غير مهم (Order of rows and columns is insignificant): لا يُشترط أن يكون عمود Primary Key هو العمود الأول على اليسار دائماً (رغم أنه متعارف عليه)، ولا يؤثر ترتيب الصفوف على بنية الجدول.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، تُعرف هذه القواعد السبعة باسم "خصائص العلاقة الرياضية" (Properties of a Relation)؛ فبينما يسمح جدول Excel العادي بدمج الخلايا وخلط الأرقام مع النصوص في نفس العمود، يفرض Relational Table ذرية القيم (Single values) وتجانس النطاق (Same kind / Domain) وعدم الاعتماد على الترتيب (Order is insignificant) لأن الجدول رياضياً هو مجموعة (Set) غير مرتبة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قسّمي القواعد السبعة إلى (2 للجدول + 2 للصفوف + 3 للأعمدة):
    · للجدول (2): اسم مميز (distinct name) + ترتيب أعمدته وصفوفه غير مهم (order is insignificant).
    · للصفوف (2): صفوف متعددة (multiple rows) + كل صف مميز بقيمة فريدة (uniquely identify the rows).
    · للأعمدة (3): اسم فريد داخل الجدول (unique name) + قيمة مفردة بالخلية (single values) + نفس نوع البيانات (same kind).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. True or False (صح أم خطأ — فخ موقع المفتاح الأساسي وترتيب الأعمدة):
Statement: "In a relational database table, the Primary Key must always be the first column on the left, because the order of columns is significant." (True / False)

· الإجابة: False (خطأ) — ترتيب الصفوف والأعمدة غير مهم (Order of rows and columns is insignificant)، ولا يُشترط أن يكون المفتاح الأساسي هو العمود الأول.

2. Multiple Choice (سؤال مباشر من القواعد السبعة):
Which of the following violates the rules for relational database tables?

· A) Having two different tables (STUDENTS and COURSES) that both have a column named ID.
· B) Storing two course codes (CS101, CS102) inside a single cell in a student's row.
· C) Changing the display order of columns in a table.
· الإجابة الصحيحة: B (تخزين قيمتين داخل خلية واحدة يخالف القاعدة الخامسة: Entries in columns are single values).

3. Short Essay / Enumeration (سؤال مقالي قصير):
List any FIVE of the seven rules for relational database tables.

· الإجابة النموذجية:
  1. Each table has a distinct name.
  2. Each table may contain multiple rows.
  3. Each table has a value to uniquely identify the rows.
  4. Each column in a table has a unique name.
  5. Entries in columns are single values.
  6. Entries in columns are of the same kind (same data type).
  7. Order of rows and columns is insignificant.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 9، أخبريني لننتقل مباشرة إلى Slide 10 (Key Terms: المصطلحات الأساسية الستة في أسفل صورة image_eYPQC_.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Relational Database

1. Chapter Name (اسم الفصل / الموضوع)

· Relational Database (قواعد البيانات العلائقية — المصطلحات الأساسية).

2. Slide Number (رقم الشريحة)

· Slide 10 (الشريحة العاشرة في ملف شابتر 2 — أسفل صورة image_eYPQC_.png: Key Terms).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Basic storage structure (بنية التخزين الأساسية): تُنطق (بيسيك ستوريج ستركتشر) — الوصف الرسمي للجدول (Table) باعتباره الوحدة الأساسية لتنظيم وحفظ البيانات.
· Table instance (نسخة / مثيل من الجدول): تُنطق (تيبل إنستانس) — الصف الواحد (Row) الذي يمثل حالة واحدة محددة داخل الجدول (مثل بيانات طالب واحد).
· Intersection (تقاطع): تُنطق (إنترسيكشن) — نقطة التقاء الصف الأفقي مع العمود الرأسي، والتي تُشكل الخلية أو الحقل (Field).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Key Terms

· Table: A basic storage structure
· Column: attribute that describes the information in the table
· Primary Key: the unique identifier for each row
· Foreign Key: a column that refers to a primary key column in another table
· Row: data for one table instance
· Field: the one value found at the intersection of a row and column

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تُعد هذه الشريحة قاموس التعريفات الرسمية لأهم 6 مصطلحات في مساق قواعد البيانات بأكمله، وقد نوه المحاضر في التفريغ إلى ضرورة حفظها وفهمها بدقة:

· الجدول (Table): هو بنية التخزين الأساسية (A basic storage structure) التي تُحفظ فيها البيانات على شكل صفوف وأعمدة.
· العمود (Column): هو الصفة (Attribute) التي تصف نوع المعلومة المخزنة في الجدول (مثل عمود الاسم، عمود الراتب).
· المفتاح الأساسي (Primary Key): هو المعرّف الفريد (Unique identifier) لكل صف في الجدول.
· المفتاح الأجنبي (Foreign Key): هو عمود في جدول يشير إلى عمود المفتاح الأساسي في جدول آخر (Refers to a primary key column in another table) لإنشاء علاقة بينهما.
· الصف (Row): هو البيانات الخاصة بحالة واحدة أو نسخة واحدة من الجدول (Data for one table instance)، مثل جميع بيانات موظف واحد.
· الحقل / الخلية (Field): هي القيمة الواحدة (The one value) الموجودة عند تقاطع الصف مع العمود (Intersection of a row and column).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات علوم الحاسوب بجامعتي Harvard (CS50) و Stanford (CS145)، يُشدد على الدقة الاصطلاحية (Terminological Precision)؛ فبينما يُستخدم مصطلح Field أحياناً كمرادف للعمود بشكل عام، فإنه في التصميم الدقيق للنموذج العلائقي يشير تحديداً إلى الخلية المفردة (Cell) الناتجة عن تقاطع صف محدد مع عمود محدد (Intersection of a row and column)، ولا يجوز أن تحتوي إلا على قيمة واحدة (The one value) تحقيقاً لمبدأ الذرية (Atomicity).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · اربطي كل مصطلح بكلمته المفتاحية السحرية في الامتحان:
    · Table ➔ Basic storage structure (بنية التخزين الأساسية).
    · Column ➔ Attribute (صفة).
    · Primary Key ➔ Unique identifier (معرّف فريد).
    · Foreign Key ➔ Refers to a primary key (يشير لمفتاح أساسي آخر).
    · Row ➔ One table instance (نسخة واحدة).
    · Field ➔ Intersection (تقاطع صف وعمود + قيمة واحدة).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال تعريف الحقل Field):
Which key term is defined as "the one value found at the intersection of a row and column"?

· A) Table
· B) Primary Key
· C) Field
· D) Foreign Key
· الإجابة الصحيحة: C (الحقل Field هو القيمة الواحدة الموجودة عند تقاطع الصف مع العمود Intersection of a row and column).

2. Matching / Fill in the Blanks (سؤال توصيل مصطلحات — متوقع جداً):
Match each term on the left with its correct definition on the right:

· Table ➔ ( ___ ) A) Data for one table instance
· Column ➔ ( ___ ) B) A column that refers to a primary key column in another table
· Primary Key ➔ ( ___ ) C) A basic storage structure
· Foreign Key ➔ ( ___ ) D) Attribute that describes the information in the table
· Row ➔ ( ___ ) E) The unique identifier for each row
· الإجابة النموذجية:
  · C (Table = A basic storage structure)
  · D (Column = Attribute that describes the information in the table)
  · E (Primary Key = The unique identifier for each row)
  · B (Foreign Key = A column that refers to a primary key column in another table)
  · A (Row = Data for one table instance)

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 10، أخبريني لننتقل مباشرة إلى Slide 11 (بداية درس 2-1 Conceptual and Physical Data Models: شريحة Database Development Process في الصورة image_DLFJbr.png)!


أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 16 (منتصف صورة image_H-9Mp9.png — ترقيم أوراكل السفلي 19: What Is a Logical Model?).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Logical Model (النموذج المنطقي): تُنطق (لوجيكال موديل) — المرحلة الثانية من التصميم التي نضيف فيها تفاصيل الأعمدة والمفاتيح والقيود إلى النموذج المفاهيمي.
· Entity Relationship Model / ERM (نموذج الكيانات والعلاقات): تُنطق (إينتيتي ريليشنشيب موديل) — الاسم العلمي الرسمي للنموذج المنطقي الذي يصف الكيانات وصفاتها وروابطها.
· Entity Relationship Diagram / ERD (مخطط الكيانات والعلاقات): تُنطق (إينتيتي ريليشنشيب داياجرام) — الرسم الهندسي المرئي الذي يُمثّل النموذج المنطقي (الخريطة التي يسلمها المصمم للمطور).
· UIDs / Unique Identifiers (المعرّفات الفريدة): تُنطق (يونيك آيدنتيفايرز) — الصفات التي تميز كل سجل في الكيان بشكل فريد (المفاتيح الأساسية والأجنبية).
· Attribute Optionality (اختيارية الصفة): تُنطق (أتريبيوت أوبشيناليتي) — تحديد ما إذا كان العمود إلزامياً (Mandatory / ممنوع تركه فارغاً) أو اختيارياً (Optional / يمكن تركه فارغاً مثل رقم الهاتف الأرضي).
· Relationship Optionality and Cardinality (اختيارية وتعددية العلاقة): تُنطق (ريليشنشيب أوبشيناليتي آند كارديناليتي) — تحديد شروط العلاقة بين جدولين (هل العلاقة إلزامية أم اختيارية؟ وكم عدد السجلات المرتبطة: واحد لواحد، واحد لمتعدد، أو متعدد لمتعدد؟).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

What Is a Logical Model?

· Includes all entities and relationships among them.
· Is called an entity relationship model (ERM).
· Is illustrated in an ERD.
· Specifies all attributes and UIDs for each entity.
· Determines attribute optionality.
· Determines relationship optionality and cardinality. *

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تشرح هذه الشريحة النقلة النوعية في مرحلة النموذج المنطقي (Logical Model)، حيث ننتقل من مجرد عناوين عامة في Conceptual Model إلى تفاصيل دقيقة، وقد أكد المحاضر في التفريغ أن الوصول لرسمة ERD يعني أنكِ أنجزتِ 90% من تصميم قاعدة البيانات:

· يشمل جميع الكيانات والعلاقات (Includes all entities and relationships): نتأكد أن كل الجداول المطلوبة موجودة ومرتبطة ببعضها.
· اسمه العلمي ورسمه (ERM & ERD): يُسمى النموذج نفسه ERM، ويُرسَم على شكل مخطط هندسي يُسمى ERD (وهو الخريطة التي يعتمد عليها المبرمج).
· تحديد جميع الصفات والمفاتيح (Specifies all attributes and UIDs): عكس النموذج المفاهيمي الذي تجاهل الأعمدة، هنا نكتب كل عمود (Attribute) داخل كل جدول، ونحدد المعرّفات الفريدة (UIDs) مثل المفتاح الأساسي (PK) والمفتاح الأجنبي (FK).
· تحديد إلزامية أو اختيارية الأعمدة (Attribute optionality): نحدد لكل عمود هل هو إجباري (Mandatory مثل اسم الطالب ورقمه الجامعي) أم اختياري (Optional مثل رقم الهاتف الأرضي أو رقم السيارة للموظف كما ضرب المحاضر المثل).
· تحديد شروط وتعددية العلاقات (Relationship optionality and cardinality): نحدد طبيعة العلاقة بين الجداول (مثل: الموظف الواحد يعمل في قسم واحد، والقسم الواحد يضم عدة موظفين).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد Logical Model (ERD) هو "الاكتمال الهيكلي المستقل عن المنصة" (Platform-Independent Structural Completeness)؛ أي أننا حددنا كل الجداول والأعمدة والمفاتيح والعلاقات والقيود المنطقية بالكامل، ولكننا لم نكتب بعد أنواع البيانات الخاصة ببرنامج معين (مثل VARCHAR2 في أوراكل)، مما يجعل هذا المخطط صالحاً للتطبيق على أي نظام قواعد بيانات.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · مقارنة ذهبية بين Conceptual و Logical (موضع سؤال مؤكد):
    · Conceptual: يحدد فقط Entities + Relationships (لا أعمدة، لا مفاتيح).
    · Logical: يضيف عليها Attributes (الأعمدة) + UIDs (المفاتيح) + Optionality (الإلزامية والاختيارية) + Cardinality (التعددية).
  · فرقي بين الاختصارين: ERM = Model (النموذج النظري) | ERD = Diagram (الرسمة والمخطط).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
Which data model specifies all attributes, unique identifiers (UIDs), attribute optionality, and relationship cardinality, and is illustrated in an ERD?

· A) Conceptual Data Model
· B) Logical Data Model
· C) Flat File Model
· الإجابة الصحيحة: B (النموذج المنطقي Logical Model هو الذي يحدد الصفات والمفاتيح والاختيارية والتعددية ويُرسَم في مخطط ERD).

2. True or False (صح أم خطأ — مقارنة مع النموذج المفاهيمي):
Statement: "Unlike a conceptual model, a logical model specifies all attributes and unique identifiers (UIDs) for each entity." (True / False)

· الإجابة: True (صح) — هذا هو الفرق الجوهري بين النموذج المفاهيمي والمنطقي.

3. Short Essay Question (سؤال مقالي قصير متوقع):
List FOUR key elements specified or determined in a Logical Data Model.

· الإجابة النموذجية:
  1. Includes all entities and relationships among them (illustrated in an ERD).
  2. Specifies all attributes and unique identifiers (UIDs) for each entity.
  3. Determines attribute optionality (mandatory vs. optional).
  4. Determines relationship optionality and cardinality.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 16، أخبريني لننتقل مباشرة إلى Slide 17 (What Is a Physical Model? - أسفل صورة image_H-9Mp9.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 17 (أسفل صورة image_H-9Mp9.png — What Is a Physical Model?).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Physical Model (النموذج الفيزيائي): تُنطق (فيزيكال موديل) — المرحلة الثالثة والأخيرة من التصميم، وهي امتداد للنموذج المنطقي تحول المفاهيم إلى تفاصيل تقنية جاهزة للتنفيذ الفعلي.
· Extension (امتداد / تكملة): تُنطق (إكستينشن) — وصف يوضح أن النموذج الفيزيائي يبني فوق النموذج المنطقي ولا يلغيه.
· Data types & Precision (أنواع البيانات والدقة/الحجم): تُنطق (داتا تايبس آند بريسيجن) — تحديد نوع البيانات لكل عمود (مثل NUMBER أو VARCHAR2 في أوراكل) وطول الخانات المسموح به (مثل NUMBER(9) لرقم الطالب الجامعي).
· Views & Indexes (العروض والفهارس): تُنطق (فيوز آند إنديكسيز) — كائنات برمجية متقدمة في قاعدة البيانات؛ الفهرس (Index) لتسريع البحث، والعرض (View) لتكوين جداول افتراضية مخصصة.
· Table structures (هياكل الجداول): تُنطق (تيبل ستركتشرز) — البنية الكاملة للجدول الجاهز للبناء، شاملة الأعمدة والمفاتيح الأساسية والأجنبية.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

What Is a Physical Model?

· Is an extension to a logical data model.
  · Defines table definitions, data types, and precision.
  · Identifies views, indexes, and other database objects. *
· Describes how the objects should be implemented in specific database.
· Shows all table structures, including columns, primary keys, and foreign keys.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تشرح هذه الشريحة المرحلة الأخيرة في التصميم وهي النموذج الفيزيائي (Physical Model)، حيث يصبح المخطط جاهزاً تماماً للتنفيذ على برنامج Oracle، وقد فصّل المحاضر عناصرها كالتالي:

· امتداد للنموذج المنطقي (Extension to a logical data model): نأخذ مخطط ERD المنطقي ونضيف إليه التفاصيل التقنية الدقيقة:
  · تعريف الجداول وأنواع البيانات والدقة (Table definitions, data types, and precision): نحدد لكل عمود نوعه وطوله؛ مثلاً عمود Student_ID نوعه NUMBER وطوله (Precision) 9 خانات، وعمود Title نوعه VARCHAR2(50) (أي نص بحد أقصى 50 حرفاً).
  · تحديد الكائنات المساعدة (Views, indexes, and other objects):
    · الفهرس (Index): يشبه فهرس الكتاب، ويُنشأ على أعمدة البحث المهمة (مثل الرقم الجامعي) لتسريع عملية البحث في عشرات الآلاف من السجلات.
    · العرض (View): جدول افتراضي (Virtual Table) يجمع بيانات من عدة جداول لعرضها عند الطلب.
· التخصيص لنظام محدد (Implemented in specific database): هنا نختار لغة وتفاصيل النظام الذي سنبني عليه فعلياً (مثل استخدام أنواع بيانات Oracle أو MySQL).
· إظهار الهياكل الكاملة (Shows all table structures): يعرض كل جدول بأعمدته وأنواعها، ومفاتيحه الأساسية (Primary Keys) والأجنبية (Foreign Keys) بوضوح تام.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف Physical Model بأنه "التخصيص المعتمد على المنصة وتحسين الأداء" (Platform-Specific Schema & Performance Tuning)؛ فبينما يركز النموذج المنطقي على صحة البيانات، يركز النموذج الفيزيائي على السرعة وكفاءة التخزين من خلال اختيار أحجام الأعمدة الدقيقة (Precision) وبناء الفهارس (Indexes) لتقليل زمن الاستعلام من ثوانٍ إلى أجزاء من الثانية.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · كلمات السر في النموذج الفيزيائي (Physical = تقني وبرمجي):
    · Extension to logical (امتداد للمنطقي).
    · Data types & Precision (أنواع البيانات وحجم الخانات، مثل VARCHAR2(50)).
    · Views & Indexes (العروض والفهارس لتسريع البحث).
    · Specific database (مرتبط ببرنامج محدد مثل Oracle).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
Which data model is an extension to a logical data model and defines data types, precision, views, and indexes for a specific database?

· A) Conceptual Data Model
· B) Hierarchical Model
· C) Physical Data Model
· الإجابة الصحيحة: C (النموذج الفيزيائي Physical Model هو الذي يحدد أنواع البيانات والدقة والفهارس والعروض لقاعدة بيانات محددة).

2. True or False (صح أم خطأ):
Statement: "A Physical Data Model is completely independent of the target database software and does not specify column data types or precision." (True / False)

· الإجابة: False (خطأ) — النموذج الفيزيائي يصف كيفية التنفيذ في قاعدة بيانات محددة (specific database) ويحدد أنواع البيانات (data types) والدقة (precision).

3. Short Essay Question (سؤال مقالي قصير):
What is a Physical Data Model, and what specific technical details does it add to the Logical Data Model?

· الإجابة النموذجية: A Physical Data Model is an extension to a logical data model that describes how objects should be implemented in a specific database. It adds table definitions, column data types and precision, views, indexes, and full table structures including columns, primary keys, and foreign keys.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 17، أخبريني لننتقل مباشرة إلى Slide 18 (Conceptual and Physical Models - مقارنة وتشبيه حلم العميل بالواقع الفيزيائي في الصورة image_bnX3lE.png)!


أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 18 (منتصف صورة image_bnX3lE.png — ترقيم أوراكل السفلي 21: Conceptual and Physical Models).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Desired outcome (النتيجة المرجوة / المطلوبة): تُنطق (ديزايرد آوتكام) — الهدف النهائي الناجح الذي نسعى للوصول إليه من خلال التخطيط الجيد.
· Data modeling (نمذجة البيانات): تُنطق (داتا موديلينج) — عملية التقاط المفاهيم والقواعد المهمة التي تشكل عمل المؤسسة ورسمها بصرياً في مخطط.
· Depicting visually (التمثيل البصري / الرسم التوضيحي): تُنطق (ديبيكتينج فيجوالي) — تحويل الكلام النظري والقواعد المكتوبة إلى رسومات ومخططات واضحة.
· Blueprint (المخطط الهندسي / الخريطة الأساسية): تُنطق (بلوبرينت) — الخريطة المعتمدة التي يعتمد عليها المنفذون لبناء النظام الفعلي (تماماً كخريطة المهندس المعماري).
· Client's dream (حلم العميل / فكرة صاحب العمل): تُنطق (كلاينتس دريم) — التصور والأفكار التي يتخيلها صاحب المؤسسة في ذهنه ويريد تحقيقها في نظامه.
· Physical reality (الواقع الملموس / الفيزيائي): تُنطق (فيزيكال رياليتي) — النظام الحقيقي المبني والعامل على الحاسوب بعد تنفيذ التصميم.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Conceptual and Physical Models

· The art of planning, developing, and communicating produces a desired outcome.
· Data modeling is the process of capturing the important concepts and rules that shape a business and depicting them visually in a diagram.
· This diagram becomes the blueprint for designing the physical thing.
· The client's dream (conceptual model) becomes a physical reality (physical model).

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تربط هذه الشريحة بين بداية الفكرة ونهاية التنفيذ بأسلوب سلس يوضح قيمة النمذجة الهندسية قبل كتابة أي كود:

· فن التخطيط والتواصل (Planning, developing, and communicating): نجاح أي مشروع برمجي يعتمد على حسن التخطيط والتواصل الواضح بين صاحب العمل والمصمم والمبرمج للوصول للنتيجة المطلوبة (Desired outcome).
· تعريف نمذجة البيانات (Data modeling): هي عملية جمع أهم المفاهيم والقوانين (Concepts and rules) التي تحكم المؤسسة وتحويلها إلى رسم بصري (Diagram).
· الرسم هو الخريطة (Blueprint): هذا المخطط البصري يصبح الخريطة الهندسية (Blueprint) التي يسير عليها المطور لبناء قاعدة البيانات الفعلية دون تخمين أو أخطاء.
· من الحلم إلى الواقع (Client's dream ➔ Physical reality): صاحب المؤسسة لديه أفكار وطموحات لنظامه في ذهنه؛ يقوم النموذج المفاهيمي (Conceptual Model) بتوثيق هذا "الحلم"، ثم يقوم النموذج الفيزيائي (Physical Model) بتحويله إلى "واقع ملموس" يعمل على الحاسوب.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة البرمجيات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف المخطط الهندسي (Blueprint) بأنه "أداة تقليل المخاطر" (Risk Mitigation Tool)؛ فالتواصل البصري عبر المخططات يكتشف سوء الفهم بين العميل والمهندس مبكراً، ويضمن أن النظام النهائي يطابق توقعات العميل بدقة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · المعادلة الذهبية في الشريحة (موضع سؤال مؤكد):
    · Client's dream (حلم العميل) = Conceptual Model (النموذج المفاهيمي).
    · Physical reality (الواقع الفيزيائي) = Physical Model (النموذج الفيزيائي).
  · تعريف Data modeling في كلمتين: Capturing concepts & rules (التقاط المفاهيم والقواعد) + Depicting visually (تمثيلها بصرياً في مخطط).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من النقطة الرابعة):
According to the lecture, how do the Conceptual Model and Physical Model relate to a client's requirements?

· A) The physical model is the client's dream, and the conceptual model is the hardware server.
· B) The client's dream (conceptual model) becomes a physical reality (physical model).
· C) Both models ignore the visual diagram and rely only on plain text.
· الإجابة الصحيحة: B (تنص النقطة الرابعة حرفياً على أن حلم العميل Conceptual model يصبح واقعاً ملموساً Physical model).

2. Fill in the Blanks (سؤال إكمال من تعريف نمذجة البيانات):
__________ is the process of capturing the important concepts and rules that shape a business and depicting them visually in a diagram.

· A) Data redundancy
· B) Data modeling
· C) Flat file sorting
· الإجابة الصحيحة: B (نمذجة البيانات Data modeling هي عملية التقاط المفاهيم والقواعد وتمثيلها بصرياً في مخطط).

3. True or False (صح أم خطأ):
Statement: "The visual diagram created during data modeling serves as the blueprint for designing the physical database." (True / False)

· الإجابة: True (صح) — هذا نص النقطة الثالثة في الشريحة.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 18، أخبريني لننتقل مباشرة إلى Slide 19 (Conceptual/Logical Model: Case Scenario - حوار الموظف والمصمم Matt في أسفل صورة image_bnX3lE.png)!


أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 19 (أسفل صورة image_bnX3lE.png — Conceptual/Logical Model: Case Scenario).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Faculty (عضو هيئة تدريس / موظف كلية): تُنطق (فاكالتي) — الشخص الذي يمثل الجهة الطالبة للنظام في هذا السيناريو.
· Simplified library database (قاعدة بيانات مكتبة مبسطة): تُنطق (سيمبليفايد لايبراري داتابيس) — نظام قاعدة بيانات مصغر لتخزين تفاصيل الكتب في القسم.
· Identifying entities and attributes (تحديد الكيانات والصفات): تُنطق (آيدنتيفايينج إينتيتيز آند أتريبيوتس) — الخطوة الأولى التي يقوم بها المصمم بتحليل الطلب وتحديد الجداول والأعمدة والعلاقات.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Conceptual/Logical Model: Case Scenario

Faculty: "Matt, I would like you to create a simplified library database to store the book details in our department."

Matt: "Sure. I will start by identifying the entities and attributes and their relationships."

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تقدم هذه الشريحة سيناريو حوارياً عملياً يوضح كيف تبدأ عملية تصميم قاعدة البيانات من طلب بسيط للعميل، وقد علق المحاضر في التفريغ على ردة فعل المصمم Matt بملاحظة ذكية جداً:

· طلب العميل (Faculty): طلب عضو هيئة التدريس من المصمم Matt إنشاء قاعدة بيانات مبسطة لتخزين تفاصيل الكتب في القسم.
· استجابة المصمم (Matt): قال Matt: "بالتأكيد، سأبدأ بتحديد الكيانات (Entities) والصفات (Attributes) والعلاقات بينها (Relationships)".
· ملاحظة المحاضر المهمة (الربط مع الشرائح السابقة): نبه المحاضر إلى أن Matt عندما ذكر أنه سيحدد الصفات (Attributes) بجانب الكيانات والعلاقات، فهذا يعني أنه يدمج الانتقال من مرحلة Conceptual Model (التي تحدد الكيانات والعلاقات فقط) إلى مرحلة Logical Model (التي تضيف الصفات والمفاتيح).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا الحوار بنقطة الانطلاق لتحليل المتطلبات؛ حيث يبدأ المصمم بترجمة طلب العميل إلى كيانات (Entities مثل BOOK, AUTHOR, MEMBER, PUBLISHER)، ثم يحدد صفات كل كيان (Attributes)، ثم يربطها بعلاقات منطقية (Relationships)، وهو ما سنراه مرسوماً خطوة بخطوة في الشرائح الثلاث القادمة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · اربطي اسم Matt بالخطوات الثلاث: عندما يطلب منكِ أحدهم بناء قاعدة بيانات (Library database)، ردي مثل Matt:
    1. Entities (الكيانات/الجداول).
    2. Attributes (الصفات/الأعمدة).
    3. Relationships (العلاقات بينها).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الحوار في الشريحة):
In the Library Database Case Scenario, how does Matt begin designing the database requested by the Faculty member?

· A) By immediately writing SQL code to create tables without planning.
· B) By identifying the entities, attributes, and their relationships.
· C) By storing all book details in a single flat text file.
· الإجابة الصحيحة: B (بدأ المصمم بتحديد الكيانات والصفات والعلاقات entities, attributes, and their relationships).

2. True or False (صح أم خطأ — ملاحظة المحاضر الدقيقة):
Statement: "When Matt includes 'attributes' alongside entities and relationships, he is transitioning from the Conceptual Model into the Logical Model." (True / False)

· الإجابة: True (صح) — لأن النموذج المفاهيمي يحدد الكيانات والعلاقات فقط، بينما إضافة الصفات (Attributes) تدخلنا في مرحلة النموذج المنطقي (Logical Model).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 19، أخبريني لننتقل مباشرة إلى Slide 20 (Case Scenario: Creating a Conceptual Model - أول شريحة في الصورة image_iNEQRJ.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 20 (أعلى صورة image_iNEQRJ.png — ترقيم أوراكل السفلي 23: Case Scenario: Creating a Conceptual Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Documents (يوثّق / يسجل): تُنطق (دوكيومنتس) — تدوين ورسم الكيانات والعلاقات بشكل رسمي وواضح.
· Relate to each other (ترتبط ببعضها البعض): تُنطق (ريليت تو إيتش أذر) — الروابط المنطقية التي توضح كيف يتعامل كيان مع آخر (مثل: العضو يستعير كتاباً).
· MEMBER (العضو / المشترك): تُنطق (ميمبر) — كيان يمثل الشخص المشترك في المكتبة الذي يستعير الكتب.
· BOOK (الكتاب): تُنطق (بوك) — الكيان المركزي في المكتبة الذي يتم تأليفه ونشره واستعارته.
· AUTHOR (المؤلف): تُنطق (أوثور) — كيان يمثل الكاتب الذي ألّف الكتاب.
· PUBLISHER (الناشر / دار النشر): تُنطق (بابليشر) — كيان يمثل الجهة أو دار النشر التي نشرت الكتاب.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Creating a Conceptual Model

A Conceptual data model documents important entities and how they relate to each other.

(المخطط التوضيحي المرسوم في الشريحة):

الكيانات الأربعة (Entities): MEMBER ، BOOK ، AUTHOR ، PUBLISHER

العلاقات بينها (Relationships):

· MEMBER ⟷ (borrows / borrowed by) ⟷ BOOK
· BOOK ⟷ (written by / writer of) ⟷ AUTHOR
· BOOK ⟷ (published by / publisher of) ⟷ PUBLISHER

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تقدم هذه الشريحة التطبيق العملي الأول للمصمم Matt لبناء قاعدة بيانات المكتبة، وتُثبت عملياً كل ما درسناه في تعريف النموذج المفاهيمي (Conceptual Model):

· تحديد الكيانات الأساسية الأربعة (Entities): حدد المصمم الجداول الرئيسية التي تحتاجها المكتبة وهي: العضو (MEMBER)، الكتاب (BOOK)، المؤلف (AUTHOR)، والناشر (PUBLISHER).
· رسم العلاقات بينها (Relationships): ربط المصمم كل كيان بالآخر بخطوط توضح طبيعة العلاقة من الطرفين:
  · العضو يستعير الكتاب (Member borrows Book)، والكتاب يُستعار من قِبل العضو (Book borrowed by Member).
  · الكتاب يُؤلَّف من قِبل المؤلف (Book written by Author)، والمؤلف يكتب الكتاب (Author writer of Book).
  · الكتاب يُنشر من قِبل دار النشر (Book published by Publisher)، ودار النشر تنشر الكتاب (Publisher publisher of Book).
· لاحظي ما ينقص الرسمة عمداً: لا يوجد في أي مستطيل أي عمود (Attributes) ولا أي مفتاح (Primary Key أو Foreign Key)؛ لأننا ما زلنا في مرحلة Conceptual Model.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا الأسلوب في قراءة العلاقات من الاتجاهين باسم "القراءة ثنائية الاتجاه للعلاقات" (Bidirectional Relationship Reading)؛ حيث تُكتب العلاقة بصيغة المبني للمعلوم من طرف (borrows / writes / publishes) وبصيغة المبني للمجهول من الطرف المقابل (borrowed by / written by / published by) لضمان عدم وجود أي غموض منطقي في فهم دور كل كيان.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · ارسمي الكيان المركزي في المنتصف (BOOK): الكتاب هو القلب، ويتصل به 3 كيانات حوله:
    · من اليسار: MEMBER (يستعير الكتاب).
    · من اليمين: AUTHOR (يؤلف الكتاب).
    · من الأسفل: PUBLISHER (ينشر الكتاب).
  · قاعدة التحقق: هل ترين أي أسماء أعمدة داخل المربعات الأربعة؟ لا! إذن هذا بالتأكيد Conceptual Model.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال تحليل الرسمة في الشريحة):
In the Library Conceptual Model example, which four main entities were identified?

· A) Student, Course, Teacher, Classroom
· B) Member, Book, Author, Publisher
· C) Employee, Department, Location, Job
· الإجابة الصحيحة: B (الكيانات الأربعة في مخطط المكتبة هي: MEMBER, BOOK, AUTHOR, PUBLISHER).

2. True or False (صح أم خطأ):
Statement: "The diagram in 'Creating a Conceptual Model' shows all table columns, primary keys, and data types for the library database." (True / False)

· الإجابة: False (خطأ) — المخطط المفاهيمي يوثق فقط الكيانات المهمة (Entities) وكيفية ارتباطها ببعضها (Relationships)، ولا يظهر الأعمدة أو المفاتيح أو أنواع البيانات.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 20، أخبريني لننتقل مباشرة إلى Slide 21 (Case Scenario: Creating a Logical Model - منتصف صورة image_iNEQRJ.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 21 (منتصف صورة image_iNEQRJ.png — ترقيم أوراكل السفلي 24: Case Scenario: Creating a Logical Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Information requirements (متطلبات المعلومات): تُنطق (إنفورميشن ريكوايرمنتس) — البيانات التفصيلية المطلوبة داخل كل جدول (الأعمدة والشروط) لتلبية احتياجات النظام.
· Intersection Entities (الكيانات الوسيطة / كيانات التقاطع): تُنطق (إنترسيكشن إينتيتيز) — جداول جديدة تُضاف في النموذج المنطقي لكسر العلاقات المتشابكة (متعدد إلى متعدد)، مثل جدول BOOK TRANSACTION وجدول BOOK AUTHOR.
· Mandatory / Optional Symbols ( و o)*: رموز تظهر بجانب أسماء الأعمدة في مخطط ERD؛ النجمة (*) تعني أن العمود إلزامي (Mandatory) وممنوع تركه فارغاً، والدائرة (o) تعني أن العمود اختياري (Optional).
· UID Symbol (#): رمز المربع (#) بجانب العمود ويعني أنه المعرّف الفريد (Unique Identifier / Primary Key) للجدول.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Creating a Logical Model

A logical data model documents the information requirements of the business.

(التغييرات والإضافات الجديدة في مخطط ERD المنطقي):

· إضافة جدولين جديدين لكسر العلاقات: BOOK TRANSACTION (بين MEMBER و BOOK) و BOOK AUTHOR (بين BOOK و AUTHOR).
· إضافة الأعمدة (Attributes) والمفاتيح (#) لكل جدول:
  · MEMBER: # * ID, * First Name, * Last Name, * Street Address, * City, * State, * Zip
  · BOOK TRANSACTION: # * Tran Date, * Type
  · BOOK: # * ID, * Title
  · PUBLISHER: # * ID, * Name
  · AUTHOR: # * ID, * Name
  · BOOK AUTHOR: جدول ربط وسيط بين الكتاب والمؤلف.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تُظهر هذه الشريحة كيف تحول المخطط البسيط من الشريحة السابقة إلى مخطط منطقي متكامل (Logical Model - ERD)، وقد أوضح المحاضر ثلاث نقلات رئيسية حدثت هنا:

· إضافة الصفات (Attributes) لكل جدول: كتبنا داخل كل مستطيل جميع الأعمدة المطلوبة (مثل رقم العضو، اسمه الأول والأخير، عنوانه، ورقم الكتاب وعنوانه).
· تحديد المفاتيح الأساسية (#) والإلزامية (*):
  · وضعنا رمز # بجانب ID في كل جدول للدلالة على أنه المفتاح الأساسي (Primary Key).
  · وضعنا رمز ***** بجانب الأعمدة للدلالة على أنها إلزامية (Mandatory / NOT NULL) لا يجوز تركها فارغة عند الإدخال.
· إضافة جدولين وسيطين جديدين (BOOK TRANSACTION و BOOK AUTHOR):
  · لماذا؟ لأن العلاقة بين العضو والكتاب هي علاقة استعارة تتكرر مع الزمن، فأضفنا جدول BOOK TRANSACTION لتسجيل تاريخ الاستعارة (Tran Date) ونوع العملية (Type).
  · ولأن الكتاب الواحد قد يؤلفه أكثر من مؤلف والمؤلف الواحد قد يكتب أكثر من كتاب، أضفنا جدول BOOK AUTHOR لكسر العلاقة بينهما (تماماً كما شرح المحاضر بالتفصيل).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف ظهور جدولين جديدين (BOOK TRANSACTION و BOOK AUTHOR) باسم "حل العلاقات من نوع متعدد إلى متعدد" (Resolving Many-to-Many Relationships)؛ ففي التمثيل المفاهيمي نقول ببساطة "المؤلف يكتب الكتاب"، أما في التمثيل المنطقي فلا يمكن تمثيل علاقة M:N مباشرة، فننشئ كيان تقاطع (Intersection Entity) يحول العلاقة إلى علاقتي 1:N نظيفتين تمنعان تكرار البيانات وتحفظان سجل المعاملات التاريخي.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · مفتاح قراءة رموز أوراكل في ERD:
    · # = مفتاح أساسي (Primary Key / UID).
    · ***** = إلزامي (Mandatory / NOT NULL).
    · o = اختياري (Optional / Nullable).
  · تذكري القفزة من Conceptual إلى Logical في المكتبة:
    · في المفاهيمي: كانوا 4 مربعات فارغة من الأعمدة.
    · في المنطقي: أصبحوا 6 مربعات (بإضافة BOOK TRANSACTION و BOOK AUTHOR) + ظهرت الأعمدة والمفاتيح!

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (تحليل التغيير بين المفاهيمي والمنطقي):
In the Library Case Scenario, what new elements appear when moving from the Conceptual Model to the Logical Model?

· A) Data types like VARCHAR2(50) and hardware server specifications.
· B) Attributes, unique identifiers (#), mandatory indicators (*), and intersection entities (BOOK TRANSACTION, BOOK AUTHOR).
· C) Plain-text delimiters such as commas and tabs.
· الإجابة الصحيحة: B (في النموذج المنطقي تظهر الأعمدة والمفاتيح ورموز الإلزامية والكيانات الوسيطة).

2. True or False (صح أم خطأ):
Statement: "In Oracle ERD notation, the # symbol indicates a Unique Identifier (Primary Key), and the * symbol indicates a mandatory attribute." (True / False)

· الإجابة: True (صح) — هذا هو المعنى الدقيق لرموز مخطط أوراكل المنطقي.

3. Short Essay Question (سؤال مقالي قصير متوقع):
Why were two new entities (BOOK TRANSACTION and BOOK AUTHOR) added in the Logical Model of the library database?

· الإجابة النموذجية: They were added as intersection (associative) entities to resolve many-to-many relationships: BOOK AUTHOR links books with multiple authors, and BOOK TRANSACTION records the borrowing/transaction history (Tran Date and Type) between members and books.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 21، أخبريني لننتقل مباشرة إلى Slide 22 (Physical Model: Case Scenario - أسفل صورة image_iNEQRJ.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 22 (أسفل صورة image_iNEQRJ.png — ترقيم أوراكل السفلي 25: Physical Model: Case Scenario).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Specifications (المواصفات التفصيلية): تُنطق (سبيسيفيكيشنز) — التفاصيل التقنية الدقيقة لكل جدول وعمود ونوع بياناته وحجمه الجاهز للبناء.
· Convert (تحويل): تُنطق (كونفيرت) — نقل وترجمة العناصر المفاهيمية والمنطقية إلى هياكل برمجية فعلية.
· Entities into Tables (تحويل الكيانات إلى جداول): تُنطق (إينتيتيز إنتو تيبلز) — تحويل كل مستطيل كيان (Entity) في النموذج المنطقي إلى جدول فعلي (Table) في قاعدة البيانات.
· Attributes into Columns (تحويل الصفات إلى أعمدة): تُنطق (أتريبيوتس إنتو كولومز) — تحويل كل صفة (Attribute) داخل الكيان إلى عمود (Column) له نوع بيانات محدد في الجدول.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Physical Model: Case Scenario

Faculty: "Matt, I want to know the specifications for all tables and columns required in the simplified library database."

Matt: "Sure. I will convert the entities and their attributes into tables and columns."

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تُمهد هذه الشريحة الحوارية للانتقال إلى المرحلة النهائية في التصميم وهي النموذج الفيزيائي (Physical Model)، وتوضح التحول المصطلحي والعملي الذي يقوم به المصمم:

· طلب المواصفات النهائية (Specifications): يطلب عضو هيئة التدريس (Faculty) من المصمم Matt المواصفات الفنية الكاملة لجميع الجداول والأعمدة المطلوبة في قاعدة بيانات المكتبة لكي تصبح جاهزة للتنفيذ الفعلي.
· استجابة المصمم (Matt): يوضح Matt آلية التحويل الأساسية من عالم التحليل والمنطق إلى عالم قاعدة البيانات الفيزيائية:
  · كل كيان (Entity) سيتحول إلى جدول (Table).
  · كل صفة (Attribute) ستتحول إلى عمود (Column) مع تحديد نوع بياناته (Data type) وحجمه (Precision) ومفاتيحه (PK و FK).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُسمى هذا التحول "الربط بين النمذجة والتنفيذ" (Logical-to-Physical Schema Mapping)؛ حيث تتغير المفردات من لغة التصميم التجريدية (Entity, Attribute, UID, Relationship) إلى لغة نظام إدارة قواعد البيانات الفعلي (Table, Column, Primary Key, Foreign Key, Data Type) لكي يتمكن المطور من كتابة أوامر CREATE TABLE في لغة SQL.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قاموس التحويل السحري (احفظي هذه المقابلات الأربع للامتحان):
    · Entity (كيان) ➔ Table (جدول).
    · Attribute (صفة) ➔ Column (عمود).
    · Unique Identifier (UID) ➔ Primary Key (PK).
    · Relationship (علاقة) ➔ Foreign Key (FK).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الحوار في الشريحة):
When transitioning to the Physical Model in the Library Case Scenario, how does Matt translate the logical design elements?

· A) By converting entities and their attributes into tables and columns.
· B) By deleting all attributes and keeping only entity names.
· C) By merging all entities into a single plain-text file.
· الإجابة الصحيحة: A (يقوم بتحويل الكيانات وصفاتها إلى جداول وأعمدة convert the entities and their attributes into tables and columns).

2. Fill in the Blanks (سؤال تحويل المصطلحات):
In a Physical Data Model, entities are converted into __________, and attributes are converted into __________.

· الإجابة النموذجية: Entities are converted into tables, and attributes are converted into columns.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 22، أخبريني لننتقل مباشرة إلى Slide 23 (Steps to Create a Physical Data Model - الخطوات الأربع لإنشاء النموذج الفيزيائي في أعلى صورة image_bnX3lE.png)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 23 (أعلى صورة image_bnX3lE.png — ترقيم أوراكل السفلي 26: Steps to Create a Physical Data Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Model entities as tables (نمذجة الكيانات كجداول): تُنطق (موديل إينتيتيز آز تيبلز) — الخطوة الأولى بتحويل كل كيان منطقي إلى جدول فعلي في قاعدة البيانات.
· Model relationships as foreign keys (نمذجة العلاقات كمفاتيح أجنبية): تُنطق (موديل ريليشنشيبس آز فورين كيز) — الخطوة الثانية بترجمة خطوط العلاقات بين الجداول إلى أعمدة مفاتيح أجنبية (Foreign Keys).
· Model attributes as columns (نمذجة الصفات كأعمدة): تُنطق (موديل أتريبيوتس آز كولومز) — الخطوة الثالثة بتحويل كل صفة إلى عمود وتحديد نوع بياناته (Data type).
· Physical constraints and requirements (القيود والمتطلبات الفيزيائية): تُنطق (فيزيكال كونسترينتس آند ريكوايرمنتس) — تعديل النموذج الفيزيائي ليناسب قيود النظام الفعلي وحجم البيانات والأداء المطلوب (مثل إضافة الفهارس Indexes وتحديد أحجام الأعمدة).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Steps to Create a Physical Data Model
(سهم كبير متجه من اليسار إلى اليمين يحتوي على 4 خطوات متسلسلة):

· Model entities as tables
· Model relationships as foreign keys
· Model attributes as columns
· Modify the physical data model based on physical constraints and requirements

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تلخص هذه الشريحة الخطوات العملية الأربع لتحويل التصميم المنطقي إلى نموذج فيزيائي (Physical Data Model) جاهز للتنفيذ على برنامج Oracle، كما شرحها المحاضر في التفريغ:

1. تحويل الكيانات إلى جداول (Model entities as tables): كل مستطيل كيان (MEMBER, BOOK, AUTHOR, PUBLISHER) يصبح جدولاً رسمياً في قاعدة البيانات (وغالباً ما يُسمى بصيغة الجمع مثل MEMBERS, BOOKS).
2. تحويل العلاقات إلى مفاتيح أجنبية (Model relationships as foreign keys): خطوط الربط تتحول إلى أعمدة مفاتيح أجنبية (Foreign Keys)؛ فمثلاً لربط الكتاب بالناشر، نأخذ رقم الناشر (PUBLISHER_ID) ونضعه كمفتاح أجنبي داخل جدول الكتب (BOOKS).
3. تحويل الصفات إلى أعمدة (Model attributes as columns): كل صفة داخل الكيان تتحول إلى عمود (Column) مع تحديد نوع البيانات (NUMBER, VARCHAR2, DATE) وحجم الخانات (Precision).
4. تعديل النموذج حسب القيود والمتطلبات الفيزيائية (Modify based on physical constraints and requirements): نضيف التحسينات والتعديلات التي يتطلبها الأداء الفعلي للنظام، مثل إنشاء الفهارس (Indexes) لتسريع البحث أو ضبط قيود التخزين والصلاحيات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التسلسل باسم "خوارزمية تحويل المخططات" (Schema Translation Algorithm)؛ فبينما تترجم الخطوات الثلاث الأولى البنية المنطقية (Entities, Relationships, Attributes) إلى بنية علائقية (Tables, Foreign Keys, Columns)، تتولى الخطوة الرابعة (Physical Constraints & Tuning) مواءمة التصميم مع خصائص محرك التخزين الفعلي لضمان سرعة الاستعلامات وكفاءة الذاكرة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · احفظي الخطوات الأربع بقاعدة (3 تحويلات Model ... as ... + 1 تعديل Modify):
    1. Entities ➔ Tables (كيانات ➔ جداول).
    2. Relationships ➔ Foreign keys (علاقات ➔ مفاتيح أجنبية).
    3. Attributes ➔ Columns (صفات ➔ أعمدة).
    4. Modify based on physical constraints & requirements (تعديل حسب القيود والمتطلبات الفيزيائية).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الخطوات الأربع):
In the steps to create a Physical Data Model, how are "relationships" between entities modeled?

· A) As separate databases
· B) As foreign keys
· C) As plain-text delimiters
· الإجابة الصحيحة: B (تُنمذج العلاقات كمفاتيح أجنبية Model relationships as foreign keys).

2. Multiple Choice (ترتيب أو تحديد الخطوة الرابعة):
What is the final step in creating a Physical Data Model after modeling entities, relationships, and attributes?

· A) Deleting all primary keys to save storage space.
· B) Modifying the physical data model based on physical constraints and requirements.
· C) Converting all tables back into a single flat file.
· الإجابة الصحيحة: B (الخطوة الرابعة هي تعديل النموذج الفيزيائي بناءً على القيود والمتطلبات الفيزيائية).

3. Short Essay / Enumeration (سؤال مقالي قصير — متوقع جداً):
List the four steps to create a Physical Data Model in order.

· الإجابة النموذجية:
  1. Model entities as tables.
  2. Model relationships as foreign keys.
  3. Model attributes as columns.
  4. Modify the physical data model based on physical constraints and requirements.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 23، أخبريني لننتقل مباشرة إلى Slide 24 (Case Scenario: Creating a Physical Model - مخطط الجداول الفيزيائية الكامل للمكتبة في أعلى صورة image_k2rrDF.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 24 (أعلى صورة image_k2rrDF.png — Case Scenario: Creating a Physical Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Modeling Performed (النمذجة المُنفّذة): تُنطق (موديلينج بيرفورمد) — ملخص عمليات التحويل التي طُبّقت للوصول إلى هذا المخطط الفيزيائي.
· VARCHAR2 (سلسلة نصية متغيرة الطول): تُنطق (فار كار تو) — نوع بيانات أساسي في قواعد بيانات Oracle لتخزين النصوص (مثل الأسماء والعناوين) مع تحديد الحد الأقصى لعدد الأحرف (مثل VARCHAR2(50)).
· NUMBER / DATE (رقم / تاريخ): تُنطق (نامبر / ديت) — أنواع بيانات قياسية في Oracle لتخزين الأرقام (مثل المعرّفات ID) والتواريخ (مثل تاريخ المعاملة Tran_Date).
· Composite Primary Key (المفتاح الأساسي المركب): تُنطق (كومبوزيت برايمري كي) — مفتاح أساسي يتكون من عمودين معاً (BOOKS_ID + AUTHORS_ID في جدول BOOK_AUTHORS) لمنع تكرار نفس الزوج مرتين.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Creating a Physical Model

Modeling Performed:

· Entities ➔ Tables.
· Attributes ➔ Columns.
· Relationships ➔ Foreign keys.

(التفاصيل التقنية الظاهرة في مخطط الجداول الستة):

· تحويل أسماء الكيانات إلى صيغة الجمع للجداول: MEMBERS, BOOK_TRANSACTIONS, BOOKS, BOOK_AUTHORS, PUBLISHERS, AUTHORS.
· تحديد أنواع البيانات والأحجام: مثل NUMBER, DATE, VARCHAR2(15), VARCHAR2(50).
· تحديد المفاتيح (PK, FK, UK):
  · مفتاح فريد (U) على عنوان الكتاب (BOOKS.Title).
  · مفتاح أساسي وأجنبي معاً (PF) في جدول الربط BOOK_AUTHORS لعمودي BOOKS_ID و AUTHORS_ID.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تُظهر هذه الشريحة الشكل النهائي الجاهز للتنفيذ على برنامج Oracle، وقد شرح المحاضر في التفريغ تفاصيل دقيقة ومهمة جداً فيها:

· ملخص التحويلات الثلاثة في أعلى الشريحة:
  · الكيانات (Entities) أصبحت جداول (Tables).
  · الصفات (Attributes) أصبحت أعمدة (Columns).
  · العلاقات (Relationships) أصبحت مفاتيح أجنبية (Foreign Keys).
· إضافة أنواع البيانات والدقة (Data Types & Precision): ظهر بجانب كل عمود نوعه باللون الأخضر؛ فالمعرّفات (ID) أخذت نوع NUMBER، وتاريخ الاستعارة أخذ نوع DATE، والنصوص أخذت VARCHAR2 بأحجام مختلفة (مثلاً 15 لرقم الكتاب، و 50 لعنوان الكتاب لأن العنوان طويل).
· شرح المحاضر العبقري لجدول BOOK_AUTHORS (رمز PF):
  · لماذا وضع المصمم عمودي BOOKS_ID و AUTHORS_ID معاً كمفتاح أساسي (PK)؟ لأن الكتاب رقم 1 قد يؤلفه المؤلف 20 والمؤلف 30 (فيكون الزوج 1, 20 مختلفاً عن 1, 30)، ولكن يُمنع تكرار الزوج 1, 20 مرتين!
  · ولماذا وضعهما أيضاً كمفاتيح أجنبية (FK)؟ لكي يرفض برنامج Oracle إدخال مؤلف رقم 40 غير موجود أصلاً في جدول AUTHORS.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف جدول BOOK_AUTHORS باسم "جدول الربط ذو المفتاح المركب" (Associative Table with Composite Key)؛ حيث يعمل الزوج (BOOKS_ID, AUTHORS_ID) كمفتاح أساسي مركب يضمن عدم تكرار نفس المؤلف لنفس الكتاب، بينما يعمل كل عمود منهما كمفتاح أجنبي مستقل يفرض التكامل المرجعي (Referential Integrity) نحو جدولي BOOKS و AUTHORS.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · احفظي المعادلة الثلاثية في أعلى الشريحة (موضع سؤال مؤكد):
    · Entities ➔ Tables
    · Attributes ➔ Columns
    · Relationships ➔ Foreign keys
  · تذكري معنى الرمز PF في جدول BOOK_AUTHORS: حرف P يعني Primary Key، وحرف F يعني Foreign Key (أي أن العمود يلعب الدورين معاً).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من أعلى الشريحة):
According to the "Creating a Physical Model" slide, how are Entities, Attributes, and Relationships modeled in the physical database?

· A) Entities ➔ Columns, Attributes ➔ Tables, Relationships ➔ Primary keys
· B) Entities ➔ Tables, Attributes ➔ Columns, Relationships ➔ Foreign keys
· C) Entities ➔ Views, Attributes ➔ Indexes, Relationships ➔ Delimiters
· الإجابة الصحيحة: B (الكيانات تتحول إلى جداول، والصفات إلى أعمدة، والعلاقات إلى مفاتيح أجنبية).

2. True or False (صح أم خطأ — سؤال من شرح المحاضر لجدول الربط):
Statement: "In the BOOK_AUTHORS physical table, BOOKS_ID and AUTHORS_ID act together as a composite Primary Key, and each one also acts individually as a Foreign Key." (True / False)

· الإجابة: True (صح) — هذا هو السبب في ظهور رمز PF بجانب العمودين في المخطط الفيزيائي.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 24، أخبريني لننتقل مباشرة إلى Slide 25 (Summary: ملخص درس 2-1 في منتصف صورة image_k2rrDF.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 2-1 Conceptual and Physical Data Models (أساسيات قواعد البيانات: 2-1 نماذج البيانات المفاهيمية والفيزيائية).

2. Slide Number (رقم الشريحة)

· Slide 25 (منتصف صورة image_k2rrDF.png — شريحة الملخص / Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Summary (ملخص الدرس): تُنطق (ساماري) — مراجعة سريعة لأهم المخرجات التعليمية التي يجب أن يتقنها الطالب بنهاية الدرس.
· Similarities and differences (أوجه التشابه والاختلاف): تُنطق (سيميلاريتيز آند ديفرينسيز) — المقارنة التحليلية بين مستويات النمذجة الثلاثة (المفاهيمي، المنطقي، والفيزيائي).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Summary
In this lesson, you should have learned how to:

· Describe a conceptual model
· Describe a logical model
· Describe a physical model
· Analyze the similarities and differences between conceptual and physical data models

5. Explanation in Arabic (الشرح باللغة العربية مع جدول المقارنة الذهبي)

تُختتم هذه الشريحة الدرس الأول من الوحدة الثانية (2-1) بتلخيص المهارات الأربع المطلوبة للامتحان، ولتحقيق الهدف الرابع (تحليل التشابه والاختلاف بين النماذج)، إليكِ المقارنة الشاملة كما شرحها المحاضر:

· أوجه التشابه (Similarities): النماذج الثلاثة تصف نفس قاعدة البيانات ونفس بيانات المؤسسة، وتعمل معاً كسلسلة متكاملة لنقل النظام من مجرد فكرة إلى واقع ملموس.
· أوجه الاختلاف الجوهرية (Differences):
  · النموذج المفاهيمي (Conceptual Model): يحدد الكيانات الرئيسية (Entities) والعلاقات بينها (Relationships) فقط، وهو مستقل تماماً عن التنفيذ التقني.
  · النموذج المنطقي (Logical Model - ERD): يضيف جميع الأعمدة (Attributes)، المفاتيح (UIDs)، إلزامية/اختيارية الأعمدة (Optionality)، وتعددية العلاقات (Cardinality).
  · النموذج الفيزيائي (Physical Model): يحول الكيانات إلى جداول (Tables)، الصفات إلى أعمدة (Columns)، العلاقات إلى مفاتيح أجنبية (Foreign Keys)، ويحدد أنواع البيانات (Data types) والدقة (Precision) والفهارس (Indexes) لبرنامج محدد مثل Oracle.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التدرج الثلاثي بـ "هرم التجريد التصميمي" (Three-Tier Design Abstraction)؛ حيث يبدأ بالتركيز على المشكلة التجارية (Conceptual)، ثم ينتقل إلى البنية المنطقية الصارمة (Logical)، وينتهي بـ التنفيذ الأمثل للأداء والتخزين (Physical).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري السلم الثلاثي (من العام إلى الخاص):
    · Conceptual = جداول وعلاقات فقط (Entities + Relationships).
    · Logical = أضف الأعمدة والمفاتيح والشروط (+ Attributes + Keys + Rules).
    · Physical = أضف أنواع البيانات والأحجام والفهارس لـ Oracle (+ Data types + Precision + Indexes).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مقارنة شاملة بين النماذج الثلاثة):
Which sequence correctly orders the data models from highest level of abstraction (business concepts) to lowest level (database implementation)?

· A) Physical Model ➔ Logical Model ➔ Conceptual Model
· B) Conceptual Model ➔ Logical Model ➔ Physical Model
· C) Logical Model ➔ Conceptual Model ➔ Physical Model
· الإجابة الصحيحة: B (الترتيب الصحيح من التجريد العالي إلى التنفيذ الفعلي هو: المفاهيمي، ثم المنطقي، ثم الفيزيائي).

2. Short Comparison Question (سؤال مقالي قصير — متوقع جداً من الهدف الرابع في الشريحة):
Compare between a Conceptual Data Model and a Physical Data Model (mention at least three key differences).

· الإجابة النموذجية:
  · Scope: A Conceptual model identifies only high-level entities and relationships, whereas a Physical model shows complete table structures, columns, keys, views, and indexes.
  · Technical Details: A Conceptual model does not specify attributes, primary keys, or data types, whereas a Physical model defines exact column data types and precision (e.g., VARCHAR2(50), NUMBER).
  · Implementation: A Conceptual model is implementation-free (captures the client's dream), whereas a Physical model is tailored for a specific DBMS (such as Oracle) to become a physical reality.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 25، أخبريني لننتقل مباشرة إلى Slide 26 (بداية درس 2-2: Entities, Instances, Attributes, and Identifiers في أسفل صورة image_k2rrDF.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Design

1. Chapter Name (اسم الفصل / الموضوع)

· Database Design: 2-2 Entities, Instances, Attributes, and Identifiers (تصميم قواعد البيانات: 2-2 الكيانات، المثيلات، الصفات، والمعرّفات).

2. Slide Number (رقم الشريحة)

· Slide 26 (أسفل صورة image_k2rrDF.png — شريحة العنوان والتمهيد للدرس 2-2).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Entities (الكيانات): تُنطق (إينتيتيز) — الأشياء أو العناصر الرئيسية التي نخزن عنها بيانات في النظام، والتي تتحول لاحقاً إلى جداول (Tables) (مثل الطالب، المدرس، المساق).
· Instances (المثيلات / النسخ): تُنطق (إنستانسيز) — الحالات أو السجلات الفردية داخل الكيان الواحد، والتي تتحول لاحقاً إلى صفوف (Rows) (مثل سجل طالب محدد اسمه "أحمد").
· Attributes (الصفات / الخصائص): تُنطق (أتريبيوتس) — المعلومات التفصيلية التي تصف الكيان، والتي تتحول لاحقاً إلى أعمدة (Columns) (مثل اسم الطالب، تاريخ ميلاده، عنوانه).
· Identifiers (المعرّفات): تُنطق (آيدنتيفايرز) — الصفات الفريدة (UIDs) التي تميز كل مثيل (صف) عن بقية المثيلات، والتي تتحول لاحقاً إلى مفاتيح أساسية (Primary Keys).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Database Design
2-2
Entities, Instances, Attributes, and Identifiers

5. Explanation in Arabic (الشرح باللغة العربية مع تشبيه المحاضر في التفريغ)

تمثل هذه الشريحة مدخلاً لـ المفاهيم الأربعة الجوهرية التي يبنى عليها أي تصميم لقاعدة بيانات (ERD)، وقد ربطها المحاضر في التفريغ بلغة البرمجة Java لتكون واضحة في ذهنكِ تماماً:

· الكيان (Entity): يشبه الـ Class في الجافا (مثلاً class Student)؛ وهو القالب العام الذي يجمع البيانات ويقابل الجدول (Table).
· الصفة (Attribute): تشبه المتغيرات (Variables) داخل الكلاس (مثل id, name, email)؛ وهي التفاصيل التي نريد تخزينها وتقابل الأعمدة (Columns).
· المثيل (Instance): يشبه الـ Object الذي ننشئه من الكلاس (مثل Student s = new Student())؛ وهو سجل فعلي لواحد من الطلاب ويقابل الصف (Row).
· المعرّف (Identifier): هو الصفة الفريدة التي تميز طالباً عن آخر (مثل رقم الطالب Student ID أو رقم الفاتورة) وتقابل المفتاح الأساسي (Primary Key).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى هذه المصطلحات الأربعة باعتبارها "لبنات البناء الأساسية للنموذج المفاهيمي والمنطقي"؛ حيث يُشترط على المهندس إتقان التفريق الدقيق بين القالب العام (Entity) وبين البيانات الفعلية المخزنة بداخله (Instances)، لأن الخطأ في التمييز بينهما يؤدي إلى إنشاء جداول زائدة أو مكررة في التصميم.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · خريطة التحويل الرباعية الذهبية (احفظيها كجدول مصغر في دفتركِ):
    · Entity (كيان) ➔ Table (جدول) ➔ يشبه Class.
    · Instance (مثيل) ➔ Row (صف) ➔ يشبه Object.
    · Attribute (صفة) ➔ Column (عمود) ➔ يشبه Variable.
    · Identifier (معرّف) ➔ Primary Key (مفتاح أساسي).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Matching / Multiple Choice (ربط المصطلحات التصميمية بالجدول العلائقي):
In database design, which sequence correctly maps (Entity, Instance, Attribute, Identifier) to physical database components?

· A) (Column, Table, Primary Key, Row)
· B) (Table, Row, Column, Primary Key)
· C) (Row, Column, Table, Foreign Key)
· الإجابة الصحيحة: B (Entity = جدول، Instance = صف، Attribute = عمود، Identifier = مفتاح أساسي).

2. True or False (صح أم خطأ):
Statement: "An Instance represents the general structure of a table, whereas an Entity represents a single row of data." (True / False)

· الإجابة: False (خطأ) — العكس هو الصحيح؛ الـ Entity هو الهيكل العام (الجدول)، بينما الـ Instance هو السجل أو الصف الواحد.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 26، أخبريني لننتقل مباشرة إلى Slide 27 (Purpose of Entities - أعلى صورة image_1dHs0o.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Design

1. Chapter Name (اسم الفصل / الموضوع)

· Database Design: 2-2 Entities, Instances, Attributes, and Identifiers (تصميم قواعد البيانات: 2-2 الكيانات، المثيلات، الصفات، والمعرّفات).

2. Slide Number (رقم الشريحة)

· Slide 27 (أعلى صورة image_1dHs0o.png — Purpose of Entities).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Organize and classify (تنظيم وتصنيف): تُنطق (أورجانايز آند كلاسيفاي) — ترتيب البيانات المبعثرة وتقسيمها إلى مجموعات متجانسة لتسهيل فهمها.
· Draw useful conclusions (استخلاص استنتاجات مفيدة): تُنطق (درو يوسفل كونكلوجنز) — القدرة على استخراج تقارير وقرارات ذكية من البيانات بعد تنظيمها.
· Seemingly random facts (حقائق تبدو عشوائية): تُنطق (سيمنجلي راندوم فاكتس) — البيانات الخام المتناثرة قبل ترتيبها في جداول منظمة.
· Structure and order (هيكلة وترتيب): تُنطق (ستركتشر آند أوردر) — وضع البيانات الضخمة في قوالب منظمة (جداول) بدلاً من تركها فوضوية.
· As a minimum (كحد أدنى): تُنطق (آز أ مينيمام) — أقل مجموعة أساسية من الجداول التي يحتاجها النظام للعمل.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Purpose of Entities

· Knowing how to organize and classify data makes it possible to draw useful conclusions about seemingly random facts.
· Our technology-rich world produces vast quantities of facts in need of structure and order.
· It is important to learn about entities because they are the things about which we store data.
· For example:
  · A school needs to store data about (as a minimum): STUDENTS, TEACHERS, COURSES, ROOMS, GRADES.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

توضح هذه الشريحة الغاية والهدف الأساسي من تعلم وتحديد الكيانات (Entities) عند تصميم أي قاعدة بيانات، كما شرحها المحاضر في التفريغ:

· تحويل الفوضى إلى نظام واستنتاجات مفيدة: عالمنا الرقمي ينتج كميات هائلة من البيانات المتناثرة (Seemingly random facts). عندما نعرف كيف نصنف وننظم هذه البيانات في كيانات (Entities)، نتمكن من استخلاص نتائج وتقارير مفيدة منها.
· الأشياء التي نخزن عنها بيانات (The things about which we store data): هذا هو التعريف العملي للـ Entity؛ فهي الحاويات (الجداول) التي تنظم وتخزن البيانات المتشابهة معاً.
· مثال المدرسة (School Example): لكي تصممي قاعدة بيانات لمدرسة أو كلية، فإنكِ تحتاجين كحد أدنى (As a minimum) إلى 5 كيانات رئيسية لتخزين البيانات عنها:
  · الطلاب (STUDENTS)
  · المدرسون (TEACHERS)
  · المساقات (COURSES)
  · الغرف الدراسية (ROOMS)
  · الدرجات/العلامات (GRADES)

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف تحديد الكيانات باسم "التصنيف الدلالي للبيانات" (Semantic Data Categorization)؛ فبدون تجميع الحقائق المتشابهة في كيانات مستقلة (فصل بيانات STUDENTS عن ROOMS و GRADES)، تتحول قاعدة البيانات إلى كومة من البيانات غير القابلة للاستعلام أو التحليل الإحصائي.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تعريف Entity في 5 كلمات من الشريحة: The things about which we store data (الأشياء التي نخزن عنها بيانات).
  · احفظي كيانات المدرسة الخمسة (School Minimum Entities):
    1. STUDENTS (الطلاب)
    2. TEACHERS (المدرسون)
    3. COURSES (المساقات)
    4. ROOMS (الغرف)
    5. GRADES (الدرجات)

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
Why is it important to learn about and identify "Entities" when designing a database?

· A) Because entities are the things about which we store data, giving structure and order to facts.
· B) Because entities replace the need for tables and rows in a relational database.
· C) Because entities automatically encrypt passwords without user permissions.
· الإجابة الصحيحة: A (تنص النقطة الثالثة حرفياً على أهمية الكيانات لأنها الأشياء التي نخزن عنها البيانات the things about which we store data).

2. Fill in the Blanks / Listing Question (سؤال من مثال المدرسة في الشريحة):
According to the lecture example, a school needs to store data about five entities as a minimum. Name them.

· الإجابة النموذجية: STUDENTS, TEACHERS, COURSES, ROOMS, and GRADES.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 27، أخبريني لننتقل مباشرة إلى Slide 28 (Purpose of Attributes - منتصف صورة image_1dHs0o.png)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 2: Database Design

1. Chapter Name (اسم الفصل / الموضوع)

· Database Design: 2-2 Entities, Instances, Attributes, and Identifiers (تصميم قواعد البيانات: 2-2 الكيانات، المثيلات، الصفات، والمعرّفات).

2. Slide Number (رقم الشريحة)

· Slide 28 (منتصف صورة image_1dHs0o.png — Purpose of Attributes).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Specific information (معلومات محددة / تفصيلية): تُنطق (سبيسيفيك إنفورميشن) — التفاصيل الدقيقة التي تصف الكيان وتوضح محتواه (مثل الاسم، العنوان، السعر).
· Distinguish (يميز / يفرّق بين): تُنطق (ديستينجويش) — القدرة على التفريق بين سجل وآخر داخل نفس الكيان من خلال تفاصيله.
· Greater detail (تفاصيل أكبر / أعمق): تُنطق (جريتر ديتيل) — المعلومات الإضافية التي تصف كل مثيل (Instance) بدقة.
· Individual items (العناصر الفردية): تُنطق (إنديفيجوال آيتمز) — الأصناف المفردة في طلب الزبون (مثل نوع الوجبة، سعرها، وكميتها) اللازمة لحساب الفاتورة.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Purpose of Attributes

· It is important to learn about attributes because they provide more specific information about an entity.
· Attributes help you distinguish between one instance and another by providing greater detail for the entity.
· For example:
  · In a restaurant, you need to list the individual items on a customer's order so that you can calculate the bill.
  · When building several sales reports, you must be able to identify a specific report from the list of reports.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

توضح هذه الشريحة الغاية والهدف من تحديد الصفات (Attributes — أي الأعمدة) بعد أن حددنا الكيانات (Entities — أي الجداول)، كما شرحها المحاضر في التفريغ:

· تقديم معلومات محددة وتفصيلية (Specific information): عندما نقول لدينا كيان اسمه STUDENT، هذا عنوان عام فقط. تأتي الصفات (Attributes) لتجيب عن سؤال: ما البيانات التي نريدها عن الطالب؟ فتعطينا التفاصيل المحددة مثل الاسم (Name)، الرقم (ID)، العنوان (Address)، والإيميل (Email).
· المساعدة في التمييز بين المثيلات (Distinguish between instances): من خلال إضافة تفاصيل أكثر لكل سجل (Greater detail)، نستطيع التفريق بين سجل وآخر داخل نفس الجدول.
· أمثلة عملية من الشريحة:
  · مثال المطعم (Restaurant): في طلب الزبون (Order)، نحتاج لتفصيل العناصر الفردية كصفات (أسماء الوجبات، أسعارها، والكمية) لكي نتمكن من حساب الفاتورة بدقة.
  · مثال تقارير المبيعات (Sales reports): عند إنشاء عدة تقارير مبيعات، نحتاج لصفات تصف كل تقرير (مثل تاريخ التقرير، اسم الفرع، أو رقمه) لكي نميز تقريراً محدداً من بين قائمة التقارير.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى العلاقة بين الكيان وصفاته كعلاقة "الحاوية والمحتوى الدلالي" (Container vs. Semantic Properties)؛ فالكيان (Entity) هو اسم الفئة فقط، بينما الصفات (Attributes) هي التي تمنح السجلات معنى وقيمة حسابية، وتمكّن النظام من إجراء العمليات الحسابية (مثل جمع أسعار الأصناف لحساب الفاتورة) وعمليات الفرز والتصفية.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · وظيفتان أساسيتان للـ Attributes (احفظيهما بكلمتين مفتاحيتين):
    1. Provide specific information (تقدم معلومات محددة عن الكيان).
    2. Distinguish between instances (تساعد في التمييز بين مثيل وآخر عبر تفاصيل أكبر).
  · مثالان في الشريحة: مطعم لحساب الفاتورة (Restaurant -> calculate the bill) + تقارير مبيعات (Sales reports -> identify a specific report).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
What is the primary purpose of "Attributes" in database design?

· A) To replace the need for entities and tables.
· B) To provide more specific information about an entity and help distinguish between instances.
· C) To link different databases across separate servers.
· الإجابة الصحيحة: B (تقدم الصفات معلومات محددة عن الكيان وتساعد في التمييز بين المثيلات بتوفير تفاصيل أكبر).

2. True or False (صح أم خطأ):
Statement: "Attributes provide greater detail for an entity, making it possible to distinguish between one instance and another." (True / False)

· الإجابة: True (صح) — هذا هو نص النقطة الثانية في الشريحة حرفياً.

3. Short Essay Question (سؤال مقالي قصير):
Explain the purpose of attributes in database design and give one real-world example from the lecture.

· الإجابة النموذجية: Attributes are important because they provide more specific information about an entity and help distinguish between one instance and another by providing greater detail. For example, in a restaurant, listing individual items (prices and quantities) as attributes on a customer's order allows the system to calculate the bill.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 28، أخبريني لننتقل مباشرة إلى Slide 29 (Purpose Unique Identifiers - أسفل صورة image_1dHs0o.png)!

