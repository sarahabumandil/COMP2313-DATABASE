تم، سأدوّن الصفحات الأربع الأولى من شابتر 6 (Pages 1–4 — Artificial, Composite, and Secondary UIDs: Objectives, Purpose, & Simple vs. Composite UIDs) بنفس القالب المنظم تماماً:

---

الصفحات الأولى إلى الرابعة (Pages 1–4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 6-1 Artificial, Composite, and Secondary UIDs (تصميم قواعد البيانات: 6-1 المعرّفات الفريدة الاصطناعية، المركبة، والثانوية).

2. Slide Number (رقم الشريحة)

• Pages 1–4 (ترقيم أوراكل 1, 3, 4, 5 من درس 6-1: Objectives, Purpose, & Simple UIDs vs. Composite UIDs).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Simple UID (المعرّف الفريد البسيط): تُنطق (سيمبل يو آي دي) — معرّف فريد يتكون من صفة واحدة فقط (Single attribute) لتمييز كل سجل في الكيان.

• Composite UID (المعرّف الفريد المركب): تُنطق (كومبوزيت يو آي دي) — معرّف فريد يتكون من دمج صفتين أو أكثر معاً (Combination of attributes) عندما لا تكفي صفة واحدة بمفردها لتمييز السجل.

• Candidate UID (المعرّف الفريد المرشح): تُنطق (كانديديت يو آي دي) — أي صفة (أو مجموعة صفات) تصلح لأن تكون معرّفاً فريداً للكيان.

• Deck of cards / Warehouse (رزمة أوراق / مستودع): تشبيهات توضح كيف يمكّنكِ الـ UID من الوصول لعنصر واحد محدد وسط آلاف العناصر المتشابهة.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 2):
This lesson covers the following objectives:
• Define the different types of unique identifiers (UIDs)
• Define a candidate UID and explain why an entity can sometimes have more than one candidate UID
• Analyze business rules and choose the most suitable primary UID from the candidates
• Recognize and discuss the issues of identification in the real world

Purpose (Page 3):
• The unique identifier (UID) is very important in relational databases.
• It is the value or combination of values that enables the user to find that one unique item among all the rest.
• Identifying just the right attribute, or combination of attributes and relationships, is a skill that any database designer must master.
• The unique identifier enables you to find your record in a file, a particular card in a deck of cards, your package in a warehouse, or a specific piece of data in a database.

Simple UIDs vs. Composite UIDs (Page 4):
• A UID that is a single attribute is a simple UID.
• However, sometimes a single attribute is not enough to uniquely identify an instance of an entity.
• If the UID is a combination of attributes, it is called a composite UID.

(مثال تذكرة الحفلة CONCERT TICKET في الصفحة 4):
• Simple Unique Identifier: # ticket number, * name
• Composite Unique Identifier: # date of performance, # seat number

5. Explanation in Arabic (الشرح باللغة العربية)

تُمهّد هذه الصفحات الأربع للدرس بتوضيح أهمية المعرّف الفريد (UID) والفرق الأساسي بين نوعيه الأولين:

1. أهمية الـ UID في قواعد البيانات (الصفحة 3):
   · هو القيمة (أو مجموعة القيم) التي تمكّنكِ من الوصول إلى عنصر واحد محدد بدقة وسط آلاف العناصر المتشابهة (تماماً مثل رقم التتبع لطردكِ في مستودع ضخم، أو سجل محدد في قاعدة بيانات).
2. المقارنة بين Simple UID و Composite UID (الصفحة 4 — مثال تذكرة الحفلة CONCERT TICKET):
   · المعرّف البسيط (Simple UID): يعتمد على عمود واحد فقط؛ فإذا كانت كل تذكرة حفلة مطبوعاً عليها رقم تسلسلي فريد (# ticket number)، فهذا العمود الواحد يكفي لتمييز التذكرة.
   · المعرّف المركب (Composite UID): يعتمد على دمج عمودين أو أكثر معاً؛ فإذا لم يكن للتذكرة رقم تسلسلي، لا يكفي تاريخ الحفلة وحده (لأن هناك مئات المقاعد في نفس التاريخ)، ولا يكفي رقم المقعد وحده (لأن نفس المقعد يُحجز في حفلات وتواريخ مختلفة). لذا ندمج # date of performance + # seat number معاً لتكوين معرّف مركب لا يتكرر.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف Composite UID بـ "المفتاح المركب متعدد الصفات" (Multi-Attribute Key)؛ حيث يتحقق التفرد (Uniqueness) من تقاطع القيم معاً (Tuple Uniqueness) وليس من كل عمود على حدة (أي يمكن أن يتكرر التاريخ في عدة صفوف، ويمكن أن يتكرر رقم المقعد في عدة صفوف، لكن يُمنع تكرار نفس التاريخ مع نفس المقعد معاً).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة الحفظ السريعة (الصفحة 4):
  · 1 Attribute = Simple UID (مثال: # ticket number).
  · 2 or more Attributes = Composite UID (مثال: # date of performance + # seat number).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 4):
   In the CONCERT TICKET example, when a ticket does not have a single unique ticket number, combining # date of performance and # seat number creates what type of UID?
   A) Simple UID
   B) Composite UID
   C) Secondary UID
   • الإجابة الصحيحة: B (دمج صفتين أو أكثر معاً لتكوين معرّف فريد يُسمى Composite UID).
2. True or False (صح أم خطأ):
   Statement: "A Simple UID consists of a combination of two or more attributes to uniquely identify an entity instance." (True or False)
   • الإجابة: False (خطأ) — المعرّف البسيط (Simple UID) يتكون من صفة واحدة فقط (single attribute)، أما دمج صفتين أو أكثر فيُسمى Composite UID.

---

أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات التالية (Artificial UIDs: المعرّفات الاصطناعية وأمثلتها في الصفحات 5 إلى 7)!

تم، سأدوّن الصفحات الثلاث التالية من درس 6-1 (Pages 5–7 — Artificial UIDs & Examples) بنفس القالب المنظم تماماً:

---

الصفحات الخامسة والسادسة والسابعة (Pages 5–7)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 6-1 Artificial, Composite, and Secondary UIDs (تصميم قواعد البيانات: 6-1 المعرّفات الفريدة الاصطناعية، المركبة، والثانوية).

2. Slide Number (رقم الشريحة)

• Pages 5–7 (ترقيم أوراكل 6, 7, 8 من درس 6-1: Artificial UIDs & Artificial UID Example).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Artificial UID (المعرّف الفريد الاصطناعي): تُنطق (آرتيفيشال يو آي دي) — معرّف لا يوجد في العالم الطبيعي (فالإنسان أو الحذاء لا يُولد برقم)، بل ينشئه مصمم النظام أو المؤسسة خصيصاً لغرض التمييز والتعريف داخل النظام (مثل الرقم الجامعي، رقم العميل، أو رقم القطعة).

• Natural world (العالم الطبيعي): تُنطق (ناتشورال وورلد) — الواقع المادي للأشياء قبل أن يضيف لها النظام أرقاماً تعريفية اصطناعية.

• Straightforward (مباشر / بسيط وواضح): تُنطق (ستريت-فوروَرد) — صفة تبيّن أن إنشاء معرّف اصطناعي (Artificial UID) غالباً ما يكون أبسط وأضمن من محاولة دمج الأسماء أو الصفات الطبيعية.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Artificial UIDs (Page 5):

Artificial UIDs are those that don't occur in the natural world but are created for purposes of identification in a system.

People are not born with "numbers," but a lot of systems assign unique numbers to identify people: student numbers, customer IDs, etc.
– (Diagram: CUSTOMER without ID ➔ Create an artificial UID ➔ CUSTOMER with # id)

Artificial UIDs — Shoe Store Example (Page 6):

A shoe has a color, a size, a style, but no truly descriptive "number."

However, a shoe store will assign unique numbers to each pair of shoes so they can be uniquely identified.
– (Diagram: SHOE with * color, * size, * style ➔ Create an artificial UID ➔ SHOE with # shoe ID)

Artificial UID Example — Student (Page 7):

How can we uniquely identify a STUDENT?

Could we use a combination of first name and last name? – Only if we are sure that the combination is unique.

Often, it is simpler and more straightforward to create an artificial attribute and make it the unique identifier.

A UID can be both artificial and composite.
– (Diagram: STUDENT ➔ Create an artificial UID ➔ # student ID)

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الشرائح الثلاث مفهوم المعرّف الاصطناعي (Artificial UID) ولماذا يلجأ إليه المصممون في أغلب قواعد البيانات:

• ما هو المعرّف الاصطناعي (Artificial UID)؟
هو رقم أو كود لا يوجد في طبيعة الشيء أصلاً، بل نخترعه نحن في النظام لكي نميز كل سجل بسهولة:

· في كيان العميل (CUSTOMER - الصفحة 5): الإنسان لا يولد برقم، لكن المتجر أو البنك يعطيه رقماً اصطناعياً (# id).
· في متجر الأحذية (SHOE - الصفحة 6): الحذاء له لون ومقاس وموديل (color, size, style)، ولكن لا يوجد فيه رقم يميز كل زوج أحذية في المستودع؛ لذا يبتكر المتجر رقماً اصطناعياً (# shoe ID).
· في كيان الطالب (STUDENT - الصفحة 7): لا يمكن الاعتماد على دمج الاسم الأول واسم العائلة (first name + last name) لأن الأسماء تتشابه؛ لذا من الأبسط والأضمن إنشاء معرّف اصطناعي هو # student ID.

• ملاحظة الامتحان الذهبية (آخر سطر في الصفحة 7):
يمكن أن يكون المعرّف الفريد اصطناعياً ومركباً في نفس الوقت (A UID can be both artificial and composite)؛ مثلاً في جدول التسجيل الجامعي، عندما ندمج # student ID (اصطناعي) مع # course ID (اصطناعي) معاً، ينتج معرّف مركب واصطناعي في آنٍ واحد!

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف Artificial UID باسم "المفتاح البديل أو الاصطناعي" (Surrogate Key) مقابل "المفتاح الطبيعي" (Natural Key)؛ وتُشير Stanford إلى أن المفاتيح الاصطناعية (مثل student ID أو shoe ID) تتفوق هندسياً لأنها قصيرة، ثابتة لا تتغير (Immutable)، وخالية من الأخطاء الإملائية، مما يسرّع عمليات البحث والربط في قاعدة البيانات بشكل هائل.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· تعريف Artificial UID في 6 كلمات: Created for identification in a system (يُنشأ للتمييز داخل النظام ولا يوجد في العالم الطبيعي).
· أمثلة الشرائح الثلاثة: # id (للعميل)، # shoe ID (للحذاء)، # student ID (للطالب).
· احذري فخ الصح والخطأ: هل يمكن أن يكون الـ UID اصطناعياً ومركباً معاً؟ نعم (A UID can be both artificial and composite)!

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 5):
   What are UIDs that do NOT occur in the natural world, but are created specifically for purposes of identification in a system (such as student ID or shoe ID), called?
   A) Natural UIDs
   B) Artificial UIDs
   C) Optional attributes
   • الإجابة الصحيحة: B (تُسمى المعرّفات الاصطناعية Artificial UIDs).
2. True or False (صح أم خطأ — الجملة الأخيرة في الصفحة 7):
   Statement: "A Unique Identifier (UID) cannot be both artificial and composite at the same time." (True or Fals

   e)
   • الإجابة: False (خطأ) — تنص الصفحة 7 حرفياً على أنه يمكن للمعرّف الفريد أن يكون اصطناعياً ومركباً معاً (A UID can be both artificial and composite).

---


أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات التالية (UIDs from Barred Relationships & Artificial UID Intersection Entity في الصفحات 8 إلى 12)!

تم، سأدوّن الصفحات الخمس التالية من درس 6-1 (Pages 8–12 — UIDs from Barred Relationships & Artificial UID Intersection Entity) بنفس القالب المنظم تماماً:

---

الصفحات الثامنة إلى الثانية عشرة (Pages 8–12)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 6-1 Artificial, Composite, and Secondary UIDs (تصميم قواعد البيانات: 6-1 المعرّفات الفريدة الاصطناعية، المركبة، والثانوية).

2. Slide Number (رقم الشريحة)

• Pages 8–12 (ترقيم أوراكل 9, 10, 11, 12, 13 من درس 6-1: UIDs from Barred Relationships & Artificial UID Intersection Entity).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Bank Routing Number (الرقم التوجيهي / التعريفي للبنك): تُنطق (بانك راوتينج نامبر) — رقم فريد يميز كل بنك عن الآخر (مثل بنك فلسطين، البنك العربي)، ويُستخدم مع رقم الحساب البنكي لتمييز الحساب بدقة عند التحويلات المالية.

• Combination of an attribute and a relationship (دمج صفة مع علاقة): تُنطق (كومبينيشن أوف آن أتريبيوت آند أ ريليشنشيب) — تكوين معرّف فريد مركب من خلال أخذ عمود من نفس الجدول (ACCOUNT # number) ودمجه مع المعرّف القادم عبر خط علاقة قاطع (Barred relationship من BANK).

• Catalog Item (صنف الكتالوج): تُنطق (كاتالوج آيتم) — كيان تقاطع (Intersection Entity) يربط الشركة المُصنِّعة (MANUFACTURER) بالمنتج (PRODUCT)، ويمتلك معرّفاً اصطناعياً خاصاً به (# number — رقم الكتالوج) بدلاً من الخطوط القاطعة.

• Not barred (غير مقطوعة / بدون خط قاطع): تُنطق (نوت بارد) — وصف للعلاقات المتصلة بكيان التقاطع عندما نبتكر له معرّفاً اصطناعياً مستقلاً (Artificial UID)؛ فتختفي الخطوط القاطعة (Bars) من الرسمة.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

UIDs from Barred Relationships — Bank Account Example (Page 8):

Sometimes the UID is a combination of an attribute and a relationship.

Two people could have the same bank account number, but at different banks.

Bank to bank transfers always need the bank routing number in addition to the bank account number.
– (Diagram: ACCOUNT [# number, * balance, * date opened] connected via a barred relationship at ⟷ have to BANK [# number, * name, * location]).

UID from Barred Relationship Intersection Entity (Page 9):

As we've seen before, the resolution of a M:M relationship often results in barred relationships from the intersection entity to the original ones.

In this example, the UID of ENROLLMENT comes from STUDENT and SUBJECT. The bars on the relationships tell you this.

Artificial UID Intersection Entity (Pages 10–12):

It is possible for an intersection entity to use an artificial attribute as the UID, instead of the barred relationships to the originating entities.

Example (MANUFACTURER, CATALOG ITEM, PRODUCT):
– CATALOG ITEM resolves this many-to-many relationship.
– An item in a catalog can be uniquely identified by the manufacturer number and the product code.
– The relationships are not barred, because an artificial UID – catalog number – has been created instead.

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الصفحات الخمس طريقتين مختلفتين لتكوين المعرّف الفريد (UID) عند وجود علاقات قاطعة أو كيانات تقاطع (Intersection Entities):

• الحالة الأولى: دمج صفة مع علاقة (Attribute + Relationship - مثال البنك في الصفحة 8):

· قد يحمل شخصان نفس رقم الحساب البنكي (1050 مثلاً)، ولكن أحدهما في بنك فلسطين والآخر في البنك العربي.
· لذا لا يكفي # number داخل جدول ACCOUNT وحده لتمييز الحساب، بل ندمج صفة رقم الحساب (ACCOUNT # number) مع علاقة البنك (Barred relationship من BANK # number)؛ فيصبح المعرّف الفريد للحساب مكوناً من (رقم الحساب + رقم البنك معاً).

• الحالة الثانية: مقارنة طريقتي تعريف كيان التقاطع (Intersection Entity - الصفحات 9 إلى 12):

· الطريقة التقليدية (الصفحة 9 — ENROLLMENT): نستخدم الخطوط القاطعة (Barred relationships) من STUDENT و SUBJECT ليصبح المعرّف مركباً منهما معاً.
· الطريقة البديلة (الصفحات 10–12 — CATALOG ITEM): بدلاً من دمج رقم الشركة المُصنِّعة (MANUFACTURER # number) مع كود المنتج (PRODUCT # code) عبر خطوط قاطعة، نبتكر معرّفاً اصطناعياً خاصاً لكيان التقاطع نسميه رقم الكتالوج (# number)؛ وهنا نحذف الخطوط القاطعة (The relationships are NOT barred) لأن الكيان الوسيط أصبح يمتلك معرّفاً اصطناعياً مستقلاً يغنيه عنها!

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف البديل الموضح في الصفحات 10–12 باسم "استبدال المفتاح المركب بمفتاح بديل" (Surrogate Key Substitution in Associative Tables)؛ فبينما تفرض Barred Relationships مفتاحاً أساسياً مركباً (Composite PK)، فإن إنشاء Artificial UID (مثل Catalog Number أو Order_ID) يحول الكيان الوسيط إلى كيان مستقل بذاته (Strong Entity) يسهل ربطه مستقبلاً بجداول أخرى دون نقل مفاتيح مركبة ثقيلة.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاعدة الخط القاطع (Bar) في كيان التقاطع (موضع سؤال مؤكد):
  · يوجد Bar (Barred relationships) ➔ المعرّف مركب من الكيانات الأصلية (مثال: ENROLLMENT).
  · لا يوجد Bar (NOT barred) ➔ تم إنشاء معرّف اصطناعي (Artificial UID) داخل كيان التقاطع نفسه (مثال: CATALOG ITEM بوجود catalog number).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحات 10–12):
   In the CATALOG ITEM intersection entity example (between MANUFACTURER and PRODUCT), why are the relationships to the originating entities NOT barred?
   A) Because CATALOG ITEM has no unique identifier at all.
   B) Because an artificial UID (catalog number) was created inside CATALOG ITEM instead.
   C) Because the relationship between MANUFACTURER and PRODUCT is one-to-one (1:1).
   • الإجابة الصحيحة: B (العلاقات ليست مقطوعة not barred لأنه تم إنشاء معرّف اصطناعي catalog number بدلاً من ذلك).
2. True or False (صح أم خطأ — من مثال الحساب البنكي في الصفحة 8):
   Statement: "A Unique Identifier (UID) can sometimes be formed by a combination of an attribute and a barred relationship (such as ACCOUNT number combined with BANK number)." (True or False)
   • الإجابة: True (صح) — هذا هو النص الحرفي في الصفحة 8.

---

أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات الخمس الأخيرة في شابتر 6 (Candidate UIDs, Primary UID, Secondary UIDs, ومشاكل التعريف في العالم الحقيقي في الصفحات 13 إلى 17)!

تم، سأدوّن الصفحات الخمس الأخيرة من شابتر 6 (Pages 13–17 — Candidate, Primary, Secondary UIDs & Terminology) بنفس القالب المنظم تماماً:

---

الصفحات الثالثة عشرة إلى السابعة عشرة (Pages 13–17)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 6-1 Artificial, Composite, and Secondary UIDs (تصميم قواعد البيانات: 6-1 المعرّفات الفريدة الاصطناعية، المركبة، والثانوية).

2. Slide Number (رقم الشريحة)

• Pages 13–17 (ترقيم أوراكل 14, 15, 16, 17 من درس 6-1 مع شريحة التعريفات المرفقة: Candidate, Primary, & Secondary UIDs).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Candidate UID (المعرّف الفريد المرشح): تُنطق (كانديديت يو آي دي) — أي صفة (أو مجموعة صفات) تصلح لأن تكون معرّفاً فريداً لتمييز كل مثيل في الكيان (مثل الرقم الجامعي، رقم البطاقة، أو البريد الإلكتروني).

• Primary UID (المعرّف الفريد الأساسي): تُنطق (برايمري يو آي دي) — المعرّف المرشح الواحد الذي يختاره المصمم ليكون المعرّف الرسمي الرئيسي للكيان، ويُرمز له بعلامة المربع بدون أقواس #.

• Secondary UID (المعرّف الفريد الثانوي / البديل): تُنطق (سيكونداري يو آي دي) — بقية المعرّفات المرشحة التي لم تُختر كمفتاح أساسي؛ تُستخدم كوسيلة بحث بديلة، ويُرمز لها بعلامة المربع بين قوسين (#).

• Badge number (رقم الشارة / البطاقة): تُنطق (بادج نامبر) — رقم بطاقة الدخول أو الهوية الجامعية المطبوع، ويُعد مثالاً شائعاً على Secondary UID.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Candidate, Primary, and Secondary UIDs (Pages 13 & 15):
• Candidate UID: One of several UIDs that could be used to identify something (e.g., Person doc id, email address, student ID, badge number).
• Primary UID: A candidate UID that is chosen as the primary identifier of something. (Only one of the candidate UIDs is chosen as the actual/primary UID).
• Secondary UID: A candidate UID that also identifies something, but is not the primary UID.
• Secondary UIDs can be useful as an alternative means of searching for data. (Example: You forgot your student ID, but you have your email with you).

Drawing Notation in STUDENT Entity (Page 14):
• المثال الأول (مفتاح أساسي واحد + مفتاح ثانوي واحد):
– # student ID (Primary UID)
– (#) badge number (Secondary UID)
• المثال الثاني (مفتاح أساسي واحد + مفتاحان ثانويان أحدهما مركب):
– # student ID (Primary UID)
– (#1) badge number (Secondary UID #1)
– (#2-1) first name + (#2-2) last name (Composite Secondary UID #2)

Identification: Database vs. Real World & Terminology (Pages 16 & 17):
• Unique identifiers become primary keys in the database, allowing you to access a specific record.
• In the real world, it is sometimes not so easy to distinguish one thing from another (e.g., keys need labels for each one).
• Key terms: Artificial UID, Candidate UID, Composite UID, Primary UID, Secondary UID, Simple UID, UID.

5. Explanation in Arabic (الشرح باللغة العربية وتعلم رموز الأقواس)

توضح هذه الصفحات الخمس الفرق بين عائلة المعرّفات المرشحة وكيفية رسمها بدقة في مخططات أوراكل (ERD):

1. الفرق بين المصطلحات الثلاثة (Candidate, Primary, Secondary):
   · المرشح (Candidate UID): كل عمود يصلح لتمييز السجل (مثل: الرقم الجامعي، الإيميل الجامعي، رقم الباركود على البطاقة).
   · الأساسي (Primary UID): نختار مرشحاً واحداً فقط ليكون هو الأساس الرسمي للنظام (مثل student ID)، ونضع بجانبه # بدون أقواس.
   · الثانوي (Secondary UID): باقي المرشحين الذين لم نختَرهم كأساسي (مثل email أو badge number)؛ نحتفظ بهم لكي نمنع تكرارهم ولكي نستخدمهم كبديل للبحث (مثلاً: نسيتِ رقمكِ الجامعي عند موظف التسجيل، فيبحث عنكِ باستخدام إيميلكِ الجامعي!).
2. كيف نرسم Secondary UID في مخطط أوراكل؟ (مهم جداً للامتحان — الصفحة 14):
   · نضع علامة المربع داخل قوسين (#).
   · إذا كان لدينا أكثر من مفتاح ثانوي، نُرقّمها: (#1) للمفتاح الثانوي الأول، و (#2) للمفتاح الثانوي الثاني.
   · إذا كان المفتاح الثانوي الثاني مركباً من عمودين (مثل الاسم الأول + اسم العائلة معاً)، نكتبهما هكذا: (#2-1) first name و (#2-2) last name.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف Secondary UID باسم "المفتاح البديل" (Alternate Key)؛ فعند تحويل مخطط ERD إلى جداول فيزيائية في Oracle، يتحول الـ Primary UID (#) إلى قيد PRIMARY KEY، بينما يتحول كل Secondary UID ((#)) إلى قيد UNIQUE مع فهرس (Unique Index) لتسريع البحث البديل ومنع التكرار.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· قاموس رموز المعرّفات في مخطط ERD (احفظيها بدقة):
  · (بدون أقواس) = Primary UID (المعرّف الأساسي الوحيد).
  · (#) (داخل قوسين) = Secondary UID (معرّف ثانوي بديل للبحث).
  · (#2-1) و (#2-2) = Composite Secondary UID (معرّف ثانوي مركب من عمودين).
· فائدة Secondary UID في 5 كلمات: Alternative means of searching for data (وسيلة بديلة للبحث عن البيانات).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من رموز الصفحة 14):
   In Oracle ERD notation, what do the symbols # and (#) represent respectively?
   A) Foreign Key and Primary Key
   B) Primary UID and Secondary UID
   C) Mandatory attribute and Optional attribute
   • الإجابة الصحيحة: B (# بدون أقواس يدل على Primary UID، و (#) بين قوسين يدل على Secondary UID).
2. Multiple Choice (سؤال فائدة المعرّفات الثانوية في الصفحة 15):
   Why are Secondary UIDs useful in a database?
   A) They allow duplicate records to be stored for the same student.
   B) They serve as an alternative means of searching for data when the Primary UID is not available (e.g., searching by email instead of student ID).
   C) They replace the need for relationships between tables.
   • الإجابة الصحيحة: B (تُعد المعرّفات الثانوية وسيلة بديلة للبحث عن البيانات).
3. Notation Reading Question (قراءة الرموز المركبة في الصفحة 14):
   In the STUDENT entity diagram showing (#1) badge number, (#2-1) first name, and (#2-2) last name, what do the labels (#2-1) and (#2-2) indicate?
   • الإجابة النموذجية: They indicate that first name and last name combine together to form a single Composite Secondary UID (the second secondary UID of the STUDENT entity).

---

ألف مبروك! أنهيتِ الآن تدوين شابتر 1 و 2 و 3 و 4 و 5 و 6 بالكامل في دفتركِ! هل تودين أن أجهز لكِ الآن اختباراً سريعاً على شابتر 6 لتثبيت المفاهيم، أم لديكِ ملف لشابتر آخر؟

تم، سأدوّن الصفحات الأربع الأولى من درس 1-2 (Pages 1–4 — Relational Database Technology: Objectives, Relational Databases, & Accessing Data in an RDBMS) بنفس القالب المنظم تماماً:

---

الصفحات الأولى إلى الرابعة (Pages 1–4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Programming with SQL: 1-2 Relational Database Technology (البرمجة بلغة SQL: 1-2 تكنولوجيا قواعد البيانات العلائقية).

2. Slide Number (رقم الشريحة)

• Pages 1–4 (ترقيم أوراكل 1, 3, 5, 11 من درس 1-2: Objectives, Relational Databases, & Accessing Data in an RDBMS).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Common field (حقل مشترك): تُنطق (كومون فيلد) — العمود المشترك الذي يربط جدولين ببعضهما في قاعدة البيانات العلائقية (مثل REGION_ID).

• RDBMS / Relational Database Management System (نظام إدارة قواعد البيانات العلائقية): تُنطق (آر دي بي إم إس) — البرنامج الذي ينظم البيانات في صفوف وأعمدة مرتبطة ويدير الوصول إليها (مثل برنامج Oracle).

• Access route (مسار الوصول الفيزيائي): تُنطق (آكسيس روت) — المكان المادي أو المسار الذي تُخزن فيه البيانات على القرص الصلب؛ والمستخدم لا يحتاج لمعرفته عند استخدام SQL.

• SQL / Structured Query Language (لغة الاستعلام البنيوية): تُنطق (إس كيو إل أو سيكوال) — اللغة القياسية المستخدمة للتعامل مع البيانات واسترجاعها من قواعد البيانات العلائقية.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 2):
This lesson covers the following objectives:

Define and give an example of a relational database

Identify table-key terms, including row, column, field, primary key, and foreign key

Relate the importance of databases to everyday life

Relational Databases (Page 3):

A relational database allows tables to be related by means of a common field.

As few as two tables can be considered a relational database if they share a common field. (Table example: COUNTRY_ID, COUNTRY_NAME, REGION_ID)

Accessing Data in an RDBMS (Page 4):

A relational database-management system (RDBMS) organizes data into related rows and columns.

To access the data in a database, you do not need to know where the data is located physically, nor do you need to specify an access route to the tables.

You simply use structured query language (SQL) statements and operators.

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الصفحات الأربع الأساس العملي لكيفية عمل قواعد البيانات العلائقية (RDBMS) عند البدء بالبرمجة:

• الحد الأدنى لقاعدة البيانات العلائقية (الصفحة 3):

· يُمكّنكِ النظام العلائقي من ربط الجداول بواسطة حقل مشترك (Common field) (وهو المفتاح الأساسي في جدول والمفتاح الأجنبي في الجدول الآخر).
· يكفي وجود جدولين فقط (As few as two tables) يشتركان في حقل مشترك لاعتبارهما قاعدة بيانات علائقية.

• ميزة لغة SQL في الوصول للبيانات (الصفحة 4):

· عندما تطلبين بيانات من قاعدة البيانات، لا تحتاجين لمعرفة مكان تخزينها الفيزيائي على القرص الصلب، ولا تحتاجين لتحديد مسار الوصول (Access route) إلى الجداول؛ كل ما عليكِ فعله هو كتابة جملة SQL بسيطة (أي أن SQL لغة وصفية تطلبين فيها ماذا تريدين وليس كيف يبحث النظام في الملفات).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف ما ورد في الصفحة 4 باسم "استقلالية البيانات الفيزيائية" (Physical Data Independence) و"الطبيعة التصريحية للغة SQL" (Declarative Nature of SQL)؛ حيث يعزل نظام RDBMS المبرمج تماماً عن تفاصيل التخزين والفهارس والملفات على القرص، ويتولى محرك تحسين الاستعلامات (Query Optimizer) اختيار أسرع مسار للوصول للبيانات تلقائياً.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 3 حقائق سريعة للامتحان من هذه الصفحات:
  · أقل عدد جداول لتكوين قاعدة بيانات علائقية: 2 tables بشرط وجود Common field.
  · عند استخدام SQL، لا تحتاج لمعرفة المكان الفيزيائي (where located physically) ولا مسار الوصول (access route).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 3):
   What is the minimum number of tables required to be considered a relational database, and what must they share?
   A) Three tables sharing a flat-file delimiter
   B) Two tables sharing a common field
   C) One table with at least ten columns
   • الإجابة الصحيحة: B (يكفي جدولان فقط إذا اشتركا في حقل مشترك As few as two tables... if they share a common field).
2. True or False (صح أم خطأ — من الصفحة 4):
   Statement: "To access data in an RDBMS using SQL, you must know where the data is located physically on the disk and specify an exact access route to the tables." (True or False)
   • الإجابة: False (خطأ) — لا تحتاجين لمعرفة المكان الفيزيائي ولا تحديد مسار الوصول (you do not need to know where the data is located physically, nor do you need to specify an access route).

---

أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات التالية في درس 1-2 (التواصل مع الخادم Communicating With Databases وفئات أوامر SQL الأربعة DML, DDL, TCL, DCL في الصفحات 5 إلى 14)!

تم، سأدوّن الصفحات العشر المتبقية من درس 1-2 (Pages 5–14 — Communicating With Databases, Categories of SQL Statements, Terminology & Summary) بنفس القالب المنظم تماماً:

---

الصفحات الخامسة إلى الرابعة عشرة (Pages 5–14)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Programming with SQL: 1-2 Relational Database Technology (البرمجة بلغة SQL: 1-2 تكنولوجيا قواعد البيانات العلائقية).

2. Slide Number (رقم الشريحة)

• Pages 5–14 (ترقيم أوراكل 13, 14, 15, 16, 17, 18, 19, 20, 21, 22 من درس 1-2: Communicating With Databases & Categories of SQL Statements).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Oracle Application Express / APEX (بيئة أوراكل التطبيقية): تُنطق (أوراكل أبليكيشن إكسبريس) — الواجهة التي يكتب فيها المبرمج جملة SQL لإرسالها إلى الخادم.

• Oracle Server (خادم أوراكل): تُنطق (أوراكل سيرفر) — قاعدة البيانات التي تعمل على الحاسوب وتستقبل الطلب وتعالجه وتعيد النتائج.

• DML / Data Manipulation Language (لغة معالجة البيانات): تُنطق (داتا مانيبيوليشن لانجويج) — فئة أوامر التعامل مع الصفوف/البيانات داخل الجدول (INSERT, UPDATE, DELETE, MERGE).

• DDL / Data Definition Language (لغة تعريف البيانات): تُنطق (داتا ديفينيشن لانجويج) — فئة أوامر بناء وتعديل وحذف هياكل الجداول نفسها (CREATE, ALTER, DROP, RENAME, TRUNCATE).

• TCL / Transaction Control Language (لغة التحكم بالمعاملات): تُنطق (ترانزاكشن كونترول لانجويج) — فئة أوامر تثبيت أو التراجع عن التغييرات التي أحدثتها أوامر DML (COMMIT, ROLLBACK, SAVEPOINT).

• DCL / Data Control Language (لغة التحكم بالبيانات/الصلاحيات): تُنطق (داتا كونترول لانجويج) — فئة أوامر منح أو سحب صلاحيات الوصول (GRANT, REVOKE).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Communicating With Databases (Pages 5–7):

Communicating with an RDBMS is accomplished by entering a SQL statement in Oracle Application Express.

The request is then sent to the Oracle Server (a database running on a computer), the request is processed and the data returned is displayed.

In very large database systems, many users, servers, and tables make up the RDBMS.

Categories of SQL Statements (Pages 8–11):

Data retrieval statement: retrieves data from the database using the keyword SELECT.

There are four main categories of SQL statements:

Data manipulation language (DML): begins with INSERT, UPDATE, DELETE, or MERGE (used to modify table data: entering new rows, changing existing rows, or removing existing rows).

Data definition language (DDL): creates, changes, and removes data structures from the database using CREATE, ALTER, DROP, RENAME, and TRUNCATE.

Transaction control language (TCL): manages changes made by DML statements using COMMIT, ROLLBACK, and SAVEPOINT.

Data control language (DCL): uses GRANT and REVOKE to give or remove access rights to the database and its structures.

Terminology & Summary (Pages 12–14):

Key terms: DCL, DDL, DML, Field, Foreign key, RDBMS, Primary key, Relational database, Row, Table, TCL.

Summary: Define/give an example of a relational database, identify table-key terms, and relate databases to everyday life.

5. Explanation in Arabic (الشرح باللغة العربية وتصنيف أوامر SQL)

تُقدّم هذه الصفحات الخريطة الكاملة لجميع أوامر لغة SQL المقسمة إلى 4 فئات رئيسية (بالإضافة إلى أمر الاسترجاع SELECT):

• آلية التواصل مع قاعدة البيانات (الصفحات 5–7): يكتب المستخدم جملة SQL في واجهة مثل Oracle Application Express ➔ تُرسل الجملة إلى Oracle Server ➔ يقوم الخادم بمعالجتها وإرجاع الجدول المطلوب.

• الفئات الأربع الرئيسية لأوامر SQL (موضع أسئلة مؤكدة في الامتحان):

· أولاً: DML (معالجة الصفوف): تتعامل مع محتوى الجدول (الصفوف): إضافة صف (INSERT)، تعديل صف (UPDATE)، حذف صف (DELETE)، أو دمج (MERGE).
· ثانياً: DDL (تعريف الهياكل): تتعامل مع هيكل الجدول نفسه: إنشاء جدول (CREATE)، تعديل أعمدته (ALTER)، حذف الجدول بالكامل (DROP)، إعادة تسميته (RENAME)، أو تفريغه (TRUNCATE).
· ثالثاً: TCL (التحكم بالمعاملات): تحفظ أو تلغي تغييرات الـ DML: حفظ نهائي (COMMIT)، تراجع (ROLLBACK)، أو وضع نقطة حفظ مؤقتة (SAVEPOINT).
· رابعاً: DCL (الصلاحيات والأمان): تتحكم في من يملك حق الوصول: منح صلاحية (GRANT)، أو سحب صلاحية (REVOKE).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُشار إلى الفرق الجوهري بين DDL و DML من حيث الحفظ التلقائي؛ فأوامر DDL (مثل CREATE و DROP و TRUNCATE) تُنفّذ حفظاً تلقائياً فورياً (Auto-Commit) ولا يمكن التراجع عنها بـ ROLLBACK، بينما تغييرات أوامر DML (INSERT, UPDATE, DELETE) تبقى معلقة في الذاكرة حتى يؤكدها المبرمج أو يتراجع عنها باستخدام أوامر TCL (COMMIT أو ROLLBACK).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· جدول الحفظ السحري للفئات الأربع وكلماتها المفتاحية (احفظيه بدقة):
  · DML (للصفوف): INSERT, UPDATE, DELETE, MERGE.
  · DDL (للهياكل): CREATE, ALTER, DROP, RENAME, TRUNCATE.
  · TCL (للحفظ والتراجع): COMMIT, ROLLBACK, SAVEPOINT.
  · DCL (للصلاحيات): GRANT, REVOKE.
  · Data Retrieval (للاستعلام): SELECT.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (تصنيف أوامر SQL — سؤال مضمون في الامتحان):
   Which category of SQL statements includes the keywords CREATE, ALTER, DROP, RENAME, and TRUNCATE?
   A) Data Manipulation Language (DML)
   B) Data Definition Language (DDL)
   C) Transaction Control Language (TCL)
   D) Data Control Language (DCL)
   • الإجابة الصحيحة: B (أوامر DDL هي المسؤولة عن إنشاء وتعديل وحذف هياكل البيانات باستخدام CREATE, ALTER, DROP, RENAME, TRUNCATE).
2. Multiple Choice (سؤال فئة TCL):
   Which SQL commands belong to Transaction Control Language (TCL) and are used to manage changes made by DML statements?
   A) INSERT, UPDATE, DELETE
   B) GRANT, REVOKE
   C) COMMIT, ROLLBACK, SAVEPOINT
   • الإجابة الصحيحة: C (أوامر TCL هي COMMIT, ROLLBACK, SAVEPOINT).
3. True or False (صح أم خطأ):
   Statement: "The SQL keywords GRANT and REVOKE belong to Data Manipulation Language (DML)." (True / False)
   • الإجابة: False (خطأ) — هما ينتميان إلى لغة التحكم بالبيانات والصلاحيات Data Control Language (DCL).

---

ألف مبروك! أنهيتِ الآن تدوين درس 1-2 بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الثاني في الملف (1-3 Anatomy of a SQL Statement: تشريح جملة SELECT، الإسقاط والاختيار، العمليات الحسابية، NULL، والأسماء المستعارة Aliases في الصفحات 15 إلى 41)!

تم، سأدوّن الصفحات التسع الأولى من درس 1-3 (Pages 15–23 — Anatomy of a SQL Statement: SELECT Statement, Conventions, Projection & Selection, & Selecting Columns) بنفس القالب المنظم تماماً:

---

الصفحات الخامسة عشرة إلى الثالثة والعشرين (Pages 15–23)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Programming with SQL: 1-3 Anatomy of a SQL Statement (البرمجة بلغة SQL: 1-3 تشريح وبنية جملة SQL).

2. Slide Number (رقم الشريحة)

• Pages 15–23 (ترقيم أوراكل 1, 5, 6, 7, 8, 9, 10, 11, 12 من درس 1-3: SELECT Statement, Conventions, Projection & Selection, & Selecting Columns).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Keyword (كلمة مفتاحية): تُنطق (كي-وورد) — أمر فردي محجوز في لغة SQL مثل SELECT و FROM و WHERE.

• Clause (عبارة / فقرة برمجية): تُنطق (كلوز) — جزء من جملة SQL يبدأ بكلمة مفتاحية (مثل SELECT last_name أو FROM employees).

• Statement (جملة SQL كاملة): تُنطق (ستيتمنت) — دمج عبارتين (Clauses) أو أكثر معاً لتنفيذ أمر كامل (مثل SELECT last_name FROM employees;).

• Projection (الإسقاط — اختيار الأعمدة): تُنطق (بروجيكشن) — قدرة جملة SELECT على اختيار أعمدة محددة من الجدول لعرضها.

• Selection (الاختيار/التصفية — اختيار الصفوف): تُنطق (سيليكشن) — قدرة جملة SELECT (باستخدام WHERE) على اختيار صفوف محددة تحقق شرطاً معيناً.

• Asterisk (*) (علامة النجمة): تُنطق (آستيريسك) — رمز يُوضع بعد SELECT لعرض جميع الأعمدة (All columns) الموجودة في الجدول.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

SELECT Statement & Syntax (Pages 16 & 17):

The SELECT statement retrieves information from the database.

Syntax:

SELECT <column_name(s)> FROM <table_name>;

In its simplest form, a SELECT statement must include:

A SELECT clause, which specifies the columns to be displayed.

A FROM clause, which specifies the table containing the columns listed in the SELECT clause.

Conventions (Page 18):

A keyword refers to an individual SQL command (e.g., SELECT and FROM).

A clause is a part of a SQL statement (e.g., SELECT last_name).

A statement is a combination of two or more clauses (e.g., SELECT last_name FROM employees).

Capabilities of SELECT Statements (Pages 19 & 20):

Projection: Used to choose columns in a table.

Selection: Used to choose rows in a table (using WHERE).

Selecting All or Specific Columns (Pages 21–23):

All columns: SELECT * FROM countries; (or list all column names individually).

Specific columns: List column names separated by a comma (,) in the SELECT clause:

SELECT location_id, city, state_province FROM locations;

5. Explanation in Arabic (الشرح باللغة العربية)

تُقدّم هذه الصفحات التسع الأساس العملي لكتابة أول استعلام بلغة SQL:

• البنية الأساسية لأبسط جملة SELECT (الصفحة 17): يجب أن تحتوي على عبارتين أساسيتين على الأقل:

· SELECT: لتحديد أسماء الأعمدة التي نريد عرضها (نفصل بينها بفاصلة ,، أو نكتب * لعرض جميع الأعمدة).
· FROM: لتحديد اسم الجدول الذي يحتوي على تلك الأعمدة.

• الفرق بين Keyword و Clause و Statement (الصفحة 18):

· SELECT وحدها = Keyword (كلمة مفتاحية).
· SELECT last_name = Clause (عبارة).
· SELECT last_name FROM employees; = Statement (جملة كاملة).

• الفرق الجوهري بين Projection و Selection (الصفحتان 19 و 20 — موضع سؤال مؤكد في الامتحان):

· Projection (الإسقاط): يختار الأعمدة (Columns) الرأسية (مثلاً: نريد عرض عمود الراتب SALARY فقط).
· Selection (الاختيار): يختار الصفوف (Rows) الأفقية بناءً على شرط (مثلاً: نريد صف الموظف الذي اسمه 'Smith' فقط باستخدام WHERE).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُربط مصطلحا Projection (π) و Selection (σ) مباشرة بـ "الجبر العلائقي" (Relational Algebra)؛ فالإسقاط (Projection) هو عملية تقطيع رأسية للجدول لإزالة الأعمدة غير المطلوبة، بينما الاختيار (Selection) هو عملية تصفية أفقية للصفوف بناءً على شرط منطقي (Predicate)، واجتماعهما معاً يحدد الخلية أو المجموعة الدقيقة المطلوبة من الجدول.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· احفظي الفرق بين Projection و Selection بقاعدة الحروف:
  · ProjeCtion ➔ حرف C = Columns (تختار الأعمدة).
  · Selection ➔ Rows (تختار الصفوف).
· تدرج البناء في SQL: Keyword (كلمة) ➔ Clause (عبارة) ➔ Statement (جملة كاملة).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 19):
   Which capability of a SELECT statement is used to choose specific "columns" in a table, and which is used to choose specific "rows"?
   A) Selection chooses columns; Projection chooses rows.
   B) Projection chooses columns; Selection chooses rows.
   C) Both Projection and Selection choose only rows.
   • الإجابة الصحيحة: B (الإسقاط Projection يختار الأعمدة Columns، والاختيار Selection يختار الصفوف Rows).
2. Multiple Choice (سؤال مصطلحات SQL في الصفحة 18):
   In the query SELECT last_name FROM employees;, what are SELECT, SELECT last_name, and the entire query called respectively?
   A) Clause, Statement, Keyword
   B) Keyword, Clause, Statement
   C) Statement, Keyword, Clause
   • الإجابة الصحيحة: B (SELECT = Keyword، SELECT last_name = Clause، والجملة كاملة = Statement).
3. True or False (صح أم خطأ):
   Statement: "In its simplest form, a SELECT statement must include at least a SELECT clause and a FROM clause." (True / False)
   • الإجابة: True (صح) — هذا هو النص الحرفي في الصفحة 17.

---

أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات التالية في درس 1-3 (العمليات الحسابية وأولوياتها Precedence والقيم الفارغة NULL Values في الصفحات 24 إلى 34)!


تم، سأدوّن الصفحات الإحدى عشرة التالية من درس 1-3 (Pages 24–34 — Arithmetic Operators, Operator Precedence, & NULL Values) بنفس القالب المنظم تماماً:

---

الصفحات الرابعة والعشرين إلى الرابعة والثلاثين (Pages 24–34)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Programming with SQL: 1-3 Anatomy of a SQL Statement (البرمجة بلغة SQL: 1-3 تشريح وبنية جملة SQL).

2. Slide Number (رقم الشريحة)

• Pages 24–34 (ترقيم أوراكل 13 إلى 23 من درس 1-3: Arithmetic Operators, Operator Precedence, & NULL Values).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Arithmetic expressions (التعبيرات الحسابية): تُنطق (آريثميتيك إكسبريشنز) — عمليات رياضية (+, -, *, /) تُجرى على الأعمدة الرقمية داخل جملة SELECT لعرض نتائج محسوبة دون تعديل البيانات الأصلية في الجدول.

• Precedence (أولوية العمليات الحسابية): تُنطق (بريسيدينس) — الترتيب الذي يتبعه Oracle لتنفيذ العمليات الحسابية المختلفة في نفس التعبير (الضرب والقسمة * / قبل الجمع والطرح + -).

• Parentheses () (الأقواس): تُنطق (بارينثيسيز) — أقواس تُستخدم لإجبار Oracle على تنفيذ العملية بداخلها أولاً وتجاوز الأولوية الافتراضية.

• NULL Value (القيمة الفارغة / غير المعروفة): تُنطق (نَل فاليو) — قيمة غير متاحة (unavailable) أو غير مُعيّنة (unassigned) أو غير معروفة (unknown) أو غير منطبقة (inapplicable)؛ وهي ليست صفراً (0) وليست مسافة فارغة (Space).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Using Arithmetic Operators (Pages 24–26):

Operators: add (+), subtract (-), multiply (*), divide (/).

Note that arithmetic expressions do NOT create new columns in the tables or change the actual data values. The results appear only in the output.

Putting in blank spaces before and after an arithmetic operator will not affect the output. (Example: SELECT last_name, salary, salary + 300 FROM employees;)

Precedence in Arithmetic Operators (Pages 27–30):

Order of precedence: Multiplication and division (* /) are evaluated before addition and subtraction (+ -). (Mnemonic: My Dear Aunt Sally)

Equal precedence: Evaluated from left to right.

Parentheses (): Used to force the expression within parentheses to be evaluated first.
– Example without parentheses: 12 * salary + 100 (for salary 24000 ➔ 288100)
– Example with parentheses: 12 * (salary + 100) (for salary 24000 ➔ 289200)

NULL Values (Pages 31–34):

NULL is a value that is unavailable, unassigned, unknown, or inapplicable.

NULL is NOT the same as a zero or a space. (In SQL, a zero is a number, and a space is a character).

If any column value in an arithmetic expression is null, the result is null (or unknown).

If you try to divide by null, the result is null (or unknown). However, if you try to divide by zero, you get an error. (Example: salary * commission_pct returns NULL for employees whose commission_pct is NULL).

5. Explanation in Arabic (الشرح باللغة العربية)

تُغطي هذه الصفحات ثلاث قواعد برمجية حاسمة في لغة SQL (موضع أسئلة مؤكدة في الامتحان):

• العمليات الحسابية لا تغير الجدول الأصلي (الصفحة 25):
عندما تكتبين SELECT last_name, salary + 300 FROM employees; فإن الناتج يظهر في شاشة العرض (Output) فقط، ولا يضيف عموداً جديداً للجدول ولا يغير رواتب الموظفين المخزنة في قاعدة البيانات.

• أولوية العمليات الحسابية (Operator Precedence - الصفحات 27–30):

· يُنفّذ Oracle الضرب والقسمة (* و /) أولاً، ثم الجمع والطرح (+ و -)، ومن اليسار إلى اليمين عند تساوي الأولوية.
· لتغيير الترتيب نستخدم الأقواس ()؛ ففي المثال (صفحة 30): إذا كان الراتب 24000، فإن 12 * 24000 + 100 = 288100، بينما مع الأقواس 12 * (24000 + 100) = 289200.

• قواعد القيمة الفارغة NULL في الحسابات (الصفحات 31–34 — مهمة جداً):

· الـ NULL ليس صفراً (0) وليس مسافة (Space)، بل يعني "قيمة غير موجودة أو غير معروفة".
· قاعدة التلوث الحسابي بالـ NULL: أي عملية حسابية (جمع، طرح، ضرب، قسمة) يدخل فيها طرف قيمته NULL يكون ناتجها النهائي NULL دائماً (مثلاً 24000 * NULL = NULL).
· الفرق بين القسمة على NULL والقسمة على Zero:
  · القسمة على NULL (100 / NULL) ➔ النتيجة NULL.
  · القسمة على صفر (100 / 0) ➔ يعطي النظام خطأ برمجياً (Error).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف سلوك NULL في العمليات الحسابية باسم "انتشار القيم غير المعروفة في المنطق ثلاثي القيم" (Three-Valued Logic & NULL Propagation)؛ فبما أن NULL يمثل قيمة مجهولة، فإن ناتج ضرب أو قسمة أي رقم في قيمة مجهولة يظل مجهولاً (NULL)، وهو ما يستدعي لاحقاً استخدام دوال معالجة القيم الفارغة (مثل NVL في Oracle) عند حساب الرواتب الإجمالية.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· القاعدة الذهبية للـ NULL والقسمة (موضع سؤال مؤكد في كل امتحان SQL):
  · Number + / - / * / ÷ NULL = NULL (النتيجة NULL دائماً).
  · Number ÷ 0 = ERROR (القسمة على صفر تعطي خطأ!).
· جملة تذكر أولوية العمليات: My Dear Aunt Sally (Multiply *, Divide /, Add +, Subtract -).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال القسمة على NULL مقابل الصفر في الصفحة 33):
   In Oracle SQL, what happens if you divide a number by NULL, compared to dividing a number by zero (0)?
   A) Dividing by NULL gives an error; dividing by zero returns NULL.
   B) Dividing by NULL returns NULL (or unknown); dividing by zero gives an error.
   C) Both operations return zero (0).
   • الإجابة الصحيحة: B (القسمة على NULL تعطي NULL، أما القسمة على صفر فتعطي خطأ Error).
2. Output Calculation (سؤال حساب ناتج من الصفحة 30):
   If an employee's salary is 1000 and commission_pct is NULL, what will be the output of SELECT 12 * (salary + 100), salary * commission_pct FROM employees;?
   A) 12100 and 0
   B) 13200 and NULL
   C) 13200 and 1000
   • الإجابة الصحيحة: B (12 * (1000 + 100) = 12 * 1100 = 13200، وحاصل ضرب 1000 * NULL هو NULL).
3. True or False (صح أم خطأ — الصفحة 25):
   Statement: "Using an arithmetic expression such as salary + 300 in a SELECT statement permanently modifies the salary values stored in the employees table." (True or False)
   • الإجابة: False (خطأ) — العمليات الحسابية في جملة SELECT تظهر في شاشة العرض (Output) فقط ولا تغير البيانات الأصلية في الجدول.

---

أخبريني عندما تنتهين من كتابة هذه الصفحات لننتقل مباشرة إلى الصفحات السبع الأخيرة في الملف (Aliases — الأسماء المستعارة للأعمدة وقواعد علامات التنصيص ومصطلحات وملخص درس 1-3 في الصفحات 35 إلى 41)!


تم، سأدوّن الصفحات السبع الأخيرة من درس 1-3 (Pages 35–41 — Aliases, Using Column Aliases, Terminology, & Summary) بنفس القالب المنظم تماماً:

---

الصفحات الخامسة والثلاثين إلى الحادية والأربعين (Pages 35–41)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Programming with SQL: 1-3 Anatomy of a SQL Statement (البرمجة بلغة SQL: 1-3 تشريح وبنية جملة SQL).

2. Slide Number (رقم الشريحة)

• Pages 35–41 (ترقيم أوراكل 24 إلى 30 من درس 1-3: Aliases, Using Column Aliases, Terminology, & Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Column Alias (الاسم المستعار للعمود): تُنطق (كولوم ألياس) — طريقة لإعادة تسمية عنوان العمود في شاشة المخرجات (Output) فقط ليظهر باسم واضح ومفهوم بدلاً من الصيغة الحسابية الطويلة (مثل عرض "Annual Salary" بدلاً من 12*(SALARY + 100)).

• AS keyword (الكلمة المفتاحية اختيارية): تُنطق (آز كي-وورد) — كلمة اختيارية يمكن وضعها بين اسم العمود والاسم المستعار (مثل last_name AS name أو بدونها last_name "Name").

• Double quotation marks "" (علامات التنصيص المزدوجة): تُنطق (دابل كوتيشن ماركس) — علامات إجبارية تحيط بالاسم المستعار في 3 حالات محددة: إذا احتوى على مسافة (Spaces)، أو رموز خاصة (Special characters)، أو لإظهاره بحالة أحرف محددة (Case-sensitive).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Aliases & Rules (Pages 35 & 36):
• An Alias is a way of renaming a column heading in the output.
• Column aliases let you rename columns in the output (especially useful with calculations).
• Rules for a column alias:

1. Renames a column heading
2. Is useful with calculations
3. Immediately follows the column name
4. May have the optional AS keyword between the column name and alias
5. Requires double quotation marks (" ") if the alias contains spaces or special characters, or is case-sensitive

Using Column Aliases — Syntax & Examples (Page 37):
• Syntax: SELECT * | column | expr [ AS alias ], ... FROM table;
• Example 1 (بدون علامات تنصيص — يظهر في المخرجات بأحرف كبيرة بالكامل UPPERCASE):
SELECT last_name AS name, commission_pct AS comm
FROM employees;
(Output headings: NAME | COMM)
• Example 2 (باستخدام علامات تنصيص مزدوجة — يحافظ على المسافة وحالة الأحرف كما كُتبت):
SELECT last_name "Name", salary*12 "Annual Salary"
FROM employees;
(Output headings: Name | Annual Salary)

Terminology & Summary (Pages 38–41):
• Key terms: Arithmetic expression, Arithmetic operator, Clause, Column, Column alias, From clause, NULL, Projection, Select clause, Selection, Select statement, Statement, WHERE Clause, * (Asterisk).
• Summary: Match projection and selection, create basic SELECT statements, use arithmetic operators and precedence, define NULL and its effect in expressions, and construct queries using column aliases.

5. Explanation in Arabic (الشرح باللغة العربية وقواعد التنصيص)

تُكمل هذه الصفحات درس تشريح جملة SELECT بشرح كيفية تجميل عناوين الأعمدة في المخرجات (Column Aliases):

1. وظيفة الـ Column Alias: يغير اسم رأس العمود في المخرجات (Output) فقط ولا يغير اسم العمود الحقيقي داخل الجدول.
2. أهم قاعدة في الامتحان (متى نضع علامات التنصيص المزدوجة " "؟ — الصفحة 36 و 37):
   · إذا لم نضع علامات تنصيص (مثل AS name):
     · يجب أن يكون الاسم المستعار كلمة واحدة بدون مسافات أو رموز خاصة.
     · يقوم Oracle تلقائياً بتحويله في المخرجات إلى أحرف كبيرة بالكامل (NAME).
   · نُجبَر على وضع علامات تنصيص مزدوجة " " في 3 حالات:
     1. وجود مسافة (Space) مثل "Annual Salary".
     2. وجود رموز خاصة (Special characters) مثل "Salary ($)" أو "Bonus%".
     3. الحفاظ على حالة الأحرف (Case-sensitive) (أحرف كبيرة وصغيرة معاً) مثل "Name" بدلاً من أن يحولها Oracle إلى NAME.
   · ملاحظة مهمة: كلمة AS اختيارية (Optional)، ويمكن كتابة الاسم المستعار مباشرة بعد اسم العمود بمسافة واحدة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنبه الطلاب إلى التمييز الصارم في لغة Oracle SQL بين نوعي علامات التنصيص:

· علامات التنصيص المزدوجة (" " Double Quotes): تُستخدم حصراً لـ أسماء الكائنات والأسماء المستعارة (Identifiers & Column Aliases) مثل "Annual Salary".
· علامات التنصيص المفردة (' ' Single Quotes): تُستخدم حصراً لـ القيم النصية والتواريخ (String & Date Literals) داخل جملة WHERE مثل WHERE last_name = 'Smith'. (الخلط بينهما يسبب خطأً برمجياً فورياً في Oracle!).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 3 شروط تفرض وضع " " (Double Quotes) على الاسم المستعار (احفظيها كقائمة):
  1. Spaces (مسافات، مثل "Annual Salary").
  2. Special characters (رموز خاصة، مثل #, $, %).
  3. Case-sensitive (حساس لحالة الأحرف، مثل "Name" لتظهر أول حرف كبيراً والباقي صغيراً).
· فخ الامتحان: في Oracle، نستخدم Double Quotes " " مع Alias وليس Single Quotes ' '!

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال شروط علامات التنصيص في الصفحة 36):
   When is it REQUIRED to enclose a column alias in double quotation marks (" ") in Oracle SQL?
   A) Whenever the optional AS keyword is omitted.
   B) When the alias contains spaces, special characters, or needs to be case-sensitive.
   C) Whenever the column is a numeric data type.
   • الإجابة الصحيحة: B (تُشترط علامات التنصيص المزدوجة إذا احتوى الاسم المستعار على مسافات أو رموز خاصة أو كان حساساً لحالة الأحرف).
2. Output Prediction (سؤال توقع شكل عنوان العمود في المخرجات من الصفحة 37):
   How will the column headings be displayed in the output of the following query?
   SELECT last_name AS emp_name, salary*12 "Yearly Salary"
   FROM employees;
   A) emp_name and YEARLY SALARY
   B) EMP_NAME and Yearly Salary
   C) EMP_NAME and YEARLY SALARY
   • الإجابة الصحيحة: B (الاسم الأول بدون تنصيص AS emp_name يحوله Oracle تلقائياً إلى أحرف كبيرة EMP_NAME، بينما الثاني محاط بعلامتي تنصيص "Yearly Salary" فيحافظ على حالة أحرفه والمسافة كما هي).
3. True or False (صح أم خطأ):
   Statement: "The AS keyword is mandatory when creating a column alias in a SELECT statement; omitting it will cause a syntax error." (True or False)
   • الإجابة: False (خطأ) — كلمة AS اختيارية (Optional) تماماً بين اسم العمود والاسم المستعار.

---

ألف مبروك! أنهيتِ الآن تدوين دروس SQL (1-2 و 1-3) بالكامل في دفتركِ بجانب شباتر التصميم (1 إلى 6)! هل تودين أن أقدم لكِ الآن امتحاناً تجريبياً سريعاً على SQL (1-2 و 1-3) أم لديكِ ملف آخر؟

