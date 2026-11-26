تم، سأدوّن الشريحتين الأولى والثانية من شابتر 4 (Slides 1 & 2 — Supertypes and Subtypes: Objectives & Purpose) بنفس القالب المنظم تماماً:

---

الشريحتان الأولى والثانية (Slides 1 & 2)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 4-1 Supertypes and Subtypes (تصميم قواعد البيانات: 4-1 الأنواع الفائقة والأنواع الفرعية).

2. Slide Number (رقم الشريحة)

• Slides 1 & 2 (ترقيم أوراكل 1 و 3 من درس 4-1: Objectives & Purpose).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Supertype (النوع الفائق / الكيان الأب): تُنطق (سوبرتايب) — الكيان العام الرئيسي الذي يضم الصفات والعلاقات المشتركة بين جميع الأنواع الفرعية التابعة له (مثل PAYMENT أو EXAM).

• Subtype (النوع الفرعي / الكيان الابن): تُنطق (سابتايب) — تقسيم فرعي متخصص داخل الكيان الأب يمتلك صفات أو علاقات خاصة به وحده دون بقية الأنواع (مثل CASH, CHECK, CREDIT CARD).

• Choices (خيارات / تصنيفات): تُنطق (تشويسز) — الأنواع المتعددة لشيء واحد في الواقع، وهي المفتاح الذي يدلنا على وجود Supertype و Subtypes.

• Evaluate (يُقيّم / يفحص): تُنطق (إيفاليويت) — فحص دقة مخطط ERD للتأكد من تطبيق قواعد الأنواع الفائقة والفرعية بشكل سليم.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Database Design 4-1: Supertypes and Subtypes
Objectives (Slide 3):
This lesson covers the following objectives:

Define and give an example of a subtype

Define and give an example of a supertype

State the rules relating to entities and subtypes, and give examples of each

Apply the rules of supertype and subtype by evaluating the accuracy of ER diagrams that represent them

Apply the rules of supertype and subtype and include them in a diagram when appropriate

Purpose (Slide 4):

Supertypes and subtypes occur frequently in the real world:
– food order types (eat in, to go)
– grocery bag types (paper, plastic)
– payment types (check, cash, credit)

You can typically associate 'choices' of something with supertypes and subtypes.

For example, what will be the method of payment – cash, check or credit card?

Understanding real world examples helps us understand how and when to model them.

5. Explanation in Arabic (الشرح باللغة العربية)

تُقدّم هذه الشرائح الفكرة الجوهرية للدرس من خلال ربطها بأمثلة يومية بسيطة جداً:

• متى نستخدم Supertype و Subtype؟ عندما يكون لدينا كيان عام واحد (Supertype) يتفرع منه خيارات أو أنواع (Choices) مختلفة (Subtypes).

• الأمثلة الثلاثة من الواقع في الشريحة 4:

· أنواع طلبات الطعام (Food order types): تناول في المطعم (eat in) أو سفري (to go).
· أنواع أكياس البقالة (Grocery bag types): ورقي (paper) أو بلاستيكي (plastic).
· أنواع الدفع (Payment types): نقدي (cash)، شيك (check)، أو بطاقة ائتمان (credit card).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا المفهوم باسم "التخصص والتعميم" (Specialization and Generalization أو IS-A Hierarchy)؛ فكل نوع فرعي هو نوع من النوع الفائق ("Cash IS-A Payment"، "Credit Card IS-A Payment"), مما يسمح بتجميع الخصائص المشتركة في الأعلى وتخصيص الفروقات في الأسفل دون تكرار الجداول.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· كلمة السر لاكتشاف Supertype & Subtype في أي نص: كلمة Choices / Types (خيارات أو أنواع لشيء واحد).
· احفظي الأمثلة الثلاثة في الشريحة 4:
  · Food order types ➔ eat in, to go.
  · Grocery bag types ➔ paper, plastic.
  · Payment types ➔ check, cash, credit.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الشريحة 4):
   Which real-world concept is typically associated with modeling Supertypes and Subtypes in a database?
   A) Flat file delimiters such as commas and tabs
   B) "Choices" or different types of a general thing (such as payment methods: cash, check, or credit card)
   C) Recursive relationships between managers and employees
   • الإجابة الصحيحة: B (نربط عادةً الخيارات والأنواع المتعددة لشيء ما بـ Supertypes and Subtypes).
2. Short Question (سؤال مقالي قصير):
   Give three real-world examples of supertypes and their corresponding subtypes mentioned in the lecture.
   • الإجابة النموذجية:

· Food order types: eat in, to go.
· Grocery bag types: paper, plastic.
· Payment types: check, cash, credit card.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية (Evaluating Entities: مشكلة الدفع PAYMENT - CASH, CHECK, CREDIT CARD في شرائح 5, 6, 7)!


تم، سأدوّن الشرائح الثلاث التالية من درس 4-1 (Slides 3, 4, & 5 — Evaluating Entities: مشكلة الدفع PAYMENT) بنفس القالب المنظم تماماً:

---

الشرائح الثالثة والرابعة والخامسة (Slides 3, 4, & 5)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 4-1 Supertypes and Subtypes (تصميم قواعد البيانات: 4-1 الأنواع الفائقة والأنواع الفرعية).

2. Slide Number (رقم الشريحة)

• Slides 3, 4, & 5 (ترقيم أوراكل 5, 6, 7 من درس 4-1: Evaluating Entities).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Evaluating Entities (تقييم الكيانات): تُنطق (إيفاليويتينج إينتيتيز) — فحص الكيان لمعرفة هل نبقيه كياناً واحداً، أم نقسمه إلى كيانات منفصلة، أم نستخدم Supertype و Subtypes.

• Common attributes (الصفات المشتركة): تُنطق (كومون أتريبيوتس) — الأعمدة التي تشترك فيها جميع أنواع الكيان بدون استثناء (مثل تاريخ الدفع payment date ومبلغ الدفع payment amount).

• Specialized / Specific attributes (الصفات المتخصصة / الخاصة): تُنطق (سبيشالايزد أتريبيوتس) — صفات أو علاقات تخص نوعاً فرعياً واحداً فقط ولا توجد عند البقية (مثل رقم البطاقة card number لبطاقة الائتمان فقط).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Evaluating Entities (Slide 5):

Often some instances of an entity have attributes and/or relationships that other instances do not have.

Imagine a business which needs to track payments from customers. Customers can pay by cash, by check, or by credit card. (Diagram: PAYMENT ➔ CASH, CHECK, CREDIT CARD)

Evaluating Entities (Slide 6):

All payments have some common attributes: payment date, payment amount, and so on.

But only credit cards would have a "card number" attribute.

And for credit card and check payments, we may need to know which CUSTOMER made the payment, while this is not needed for cash payments.

Evaluating Entities (Slide 7):

Should we create a single PAYMENT entity or three separate entities CASH, CHECK, and CREDIT CARD?

And what happens if in the future we introduce a fourth method of payment?

5. Explanation in Arabic (الشرح باللغة العربية وتحليل المشكلة)

تطرح هذه الشرائح الثلاث المشكلة التصميمية التي تحلها الأنواع الفائقة والفرعية (Supertypes & Subtypes) من خلال مثال الدفع (PAYMENT):

• جوهر المشكلة (الشريحة 5 و 6):

· جميع عمليات الدفع (CASH, CHECK, CREDIT CARD) تشترك في صفات عامة مثل: تاريخ الدفع (payment date) ومبلغ الدفع (payment amount).
· ولكن فقط بطاقة الائتمان (CREDIT CARD) تحتاج لصفة رقم البطاقة (card number) (فالكاش والشيك ليس لهما رقم بطاقة!).
· وأيضاً، الدفع بـ بطاقة الائتمان (CREDIT CARD) والشيك (CHECK) يحتاجان لعلاقة مع جدول CUSTOMER لمعرفة هوية العميل، بينما الدفع الكاش (CASH) لا يحتاج لمعرفة هوية العميل.

• لماذا يفشل الحلان التقليديان (الشريحة 7)؟

· الحل الفاشل 1 (كيان واحد PAYMENT فقط): لو وضعنا كل الأعمدة في جدول واحد، ستبقى خانة card number وخانة العميل فارغة (NULL) في كل مرة يدفع فيها زبون كاش!
· الحل الفاشل 2 (3 كيانات منفصلة CASH, CHECK, CREDIT CARD): سنضطر لتكرار نفس الأعمدة المشتركة (payment date, payment amount) في الجداول الثلاثة، وإذا أضافت الشركة طريقة دفع رابعة مستقبلاً (مثل الدفع الإلكتروني)، سنضطر لإعادة تصميم النظام.

• الحل الذكي: جعل PAYMENT كياناً فائقاً (Supertype) يحتوي على الصفات المشتركة، وبداخله 3 أنواع فرعية (Subtypes: CASH, CHECK, CREDIT CARD) كلٌ منها يحمل صفاته وعلاقاته الخاصة فقط!

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التصميم بحل معضلة "الكيانات متباينة الصفات" (Heterogeneous Attribute Entities)؛ فدمجها في جدول مسطح واحد يسبب كثرة القيم الفارغة (Sparse Columns / Excessive NULLs)، وفصلها إلى كيانات مستقلة يسبب تكرار الهيكل (Schema Redundancy). لذا يجمع نمط Supertype/Subtype بين عدم تكرار الصفات المشتركة وبين عزل الصفات والعلاقات الخاصة لكل نوع فرعي.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· متى نحتاج Supertype و Subtype؟ (القاعدة الذهبية من الشريحة 5):
  · عندما يكون لبعض السجلات صفات (Attributes) أو علاقات (Relationships) لا تمتلكها السجلات الأخرى في نفس الكيان!
· تذكري تفاصيل مثال PAYMENT في الشريحة 6:
  · مشترك للكل (PAYMENT): payment date, payment amount.
  · خاص بـ CREDIT CARD فقط: صفة card number.
  · خاص بـ CREDIT CARD و CHECK (وليس CASH): العلاقة مع CUSTOMER.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الشريحة 5 و 6):
   When is it appropriate to subdivide an entity into a Supertype and Subtypes?
   A) When all instances of the entity share the exact same attributes and relationships.
   B) When some instances of an entity have specialized attributes and/or relationships that other instances do not have.
   C) When the entity has fewer than ten rows of data.
   • الإجابة الصحيحة: B (عندما تمتلك بعض المثيلات صفات أو علاقات لا تمتلكها المثيلات الأخرى).
2. True or False (صح أم خطأ — من مثال الشريحة 6):
   Statement: "In the PAYMENT scenario, payment date and card number are common attributes shared by all payment types (cash, check, and credit card)." (True / False)
   • الإجابة: False (خطأ) — payment date صفة مشتركة للجميع، أما card number فهي صفة خاصة بـ CREDIT CARD فقط.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية (Subdivide an Entity & Drawing a Subtype: تعريف Supertype و Subtype وقواعد رسمهما في شرائح 8 و 10)!


تم، سأدوّن الشريحتين التاليتين من درس 4-1 (Slides 6 & 7 — Subdivide an Entity & Drawing a Subtype) بنفس القالب المنظم تماماً:

---

الشريحتان السادسة والسابعة (Slides 6 & 7)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 4-1 Supertypes and Subtypes (تصميم قواعد البيانات: 4-1 الأنواع الفائقة والأنواع الفرعية).

2. Slide Number (رقم الشريحة)

• Slides 6 & 7 (ترقيم أوراكل 8 من درس 4-1 مع الشريحة المرفقة DFo 3-3 رقم 10: Subdivide an Entity & Drawing a Subtype).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Subdivide (يُقسّم فرعياً): تُنطق (ساب-ديفايد) — تقسيم الكيان الواحد الكبير إلى مجموعات فرعية متخصصة.

• Entity Supertype (الكيان الفائق): تُنطق (إينتيتي سوبرتايب) — كيان يُبنى بالصفات والعلاقات المشتركة بين جميع الأنواع الفرعية المرتبطة به (مثل ANIMAL).

• Entity Subtype (الكيان الفرعي): تُنطق (إينتيتي سابتايب) — كيان مبني على الكيان الفائق لكنه يتميز بصفات وغرض متخصص خاص به (مثل VERTEBRATE الفقاريات و INVERTEBRATE اللافقاريات).

• Enclosed within (مُحاط بـ / مرسوم داخل): تُنطق (إنكلوزد ويذين) — قاعدة الرسم الأساسية في أوراكل؛ يُرسم المستطيل الفرعي (Subtype) داخل المستطيل الكبير للكيان الفائق (Supertype).

• Inherited (موروثة): تُنطق (إنهيريتيد) — انتقال جميع الصفات والعلاقات الموجودة في الكيان الفائق تلقائياً إلى كل كيان فرعي بداخله.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Subdivide an Entity (Slide 8):

Sometimes it makes sense to subdivide an entity into subtypes.

This may be the case when a group of instances has special properties, such as attributes or relationships that exist only for that group.

In this case, the entity is called a "supertype" and each group is called a "subtype". (Diagram: ANIMAL containing VERTEBRATE and INVERTEBRATE)

Definitions & Drawing a Subtype (DFo 3-3 Slide 10):

entity supertype - an entity that is constructed with attributes that will be common to all of the subtypes related to it.

entity subtype - an entity that is based on a supertype, but is different from the supertype because of its specialized attributes and purpose.

Rules for Drawing a Subtype:
– Each subtype is a specialization of a supertype and therefore must be enclosed within an entity.
– The common attributes and relationships for all subtypes must be listed only in the supertype, but they are inherited in every subtype.
– A subtype can and would generally have attributes and relationships of its own.
– There can never be just one subtype; another subtype should be created to contain the rest. (Diagram: SUPERTYPE A enclosing SUBTYPE B and OTHER A)

5. Explanation in Arabic (الشرح باللغة العربية وقواعد الرسم الأربعة)

تضع هذه الشرائح التعريف الرسمي لـ Supertype و Subtype وتحدد القواعد الأربع الصارمة لرسمهما في مخططات أوراكل (ERD):

• القاعدة 1: الاحتواء الداخلي (Must be enclosed within an entity):
في منهج أوراكل، لا نرسم خطاً خارجياً يربط الابن بالأب، بل نرسم مستطيل الـ Subtype داخل مستطيل الـ Supertype مباشرة (كما رأينا VERTEBRATE و INVERTEBRATE مرسومين داخل مربع ANIMAL).

• القاعدة 2: عدم التكرار والوراثة (Listed only in supertype, inherited in every subtype):
الصفات المشتركة (مثل الاسم، الوزن، العمر) تُكتب مرة واحدة فقط في الأعلى داخل الـ Supertype، وتُعتبر موروثة (Inherited) تلقائياً لكل نوع فرعي بداخله دون إعادة كتابتها.

• القاعدة 3: التخصص (Attributes and relationships of its own):
كل نوع فرعي يمتلك داخل مستطيله الصغير صفاته وعلاقاته الخاصة التي تميزه عن إخوته.

• القاعدة 4: ممنوع وجود نوع فرعي وحيد (There can never be just one subtype):
لا يجوز أبداً رسم Subtype واحد فقط داخل Supertype! يجب أن يكون هناك اثنان على الأقل؛ فإذا لم يكن هناك نوع ثانٍ محدد، ننشئ نوعاً ثانياً نسميه OTHER لاحتواء بقية الحالات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف مبدأ "ممنوع وجود نوع فرعي وحيد" (Never Just One Subtype) بـ "قاعدة الجدوى التقسيمية" (Partitioning Utility Rule)؛ لأنه إذا كان هناك نوع فرعي واحد فقط يغطي جميع الحالات، فلا داعي للتقسيم أصلاً وتُدمج صفاته في الكيان الأصلي، أما إذا كان يغطي بعض الحالات فقط، فلا بد من وجود نوع فرعي ثانٍ (OTHER) لاستيعاب الحالات المتبقية.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 4 قواعد ذهبية لرسم Subtype (موضع أسئلة مؤكدة):
  · المكان: يُرسم داخل الكيان الأب (Enclosed within).
  · الصفات المشتركة: تُكتب في الأب فقط وتُورَّث للأبناء (Listed only in supertype, inherited).
  · الصفات الخاصة: تُكتب داخل الابن (Attributes of its own).
  · العدد: ممنوع ابن واحد فقط! أقل عدد هو 2 (وإذا لم يوجد ثانٍ نضع OTHER).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. True or False (صح أم خطأ — القاعدة الرابعة المشهورة في الامتحانات):
   Statement: "If a supertype only has one specialized group of instances, it is valid to draw just one subtype inside the supertype." (True / False)
   • الإجابة: False (خطأ) — لا يمكن أبداً وجود نوع فرعي واحد فقط (There can never be just one subtype)؛ يجب إنشاء نوع فرعي آخر (مثل OTHER) لاحتواء البقية.
2. Multiple Choice (سؤال مباشر من قواعد الرسم):
   Where should the common attributes and relationships shared by all subtypes be listed in an ER diagram?
   A) Repeated inside every individual subtype box.
   B) Listed only once in the supertype, as they are automatically inherited by every subtype.
   C) Omitted completely from the ER diagram.
   • الإجابة الصحيحة: B (تُكتب الصفات والعلاقات المشتركة في الكيان الفائق Supertype فقط وتُورَّث تلقائياً لكل نوع فرعي).
3. Short Definition Question (سؤال مقالي قصير):
   Define "Entity Supertype" and "Entity Subtype", and state the four rules for drawing a subtype.
   • الإجابة النموذجية:

· Entity Supertype: An entity constructed with attributes that are common to all of the subtypes related to it.
· Entity Subtype: An entity based on a supertype, but different from it because of its specialized attributes and purpose.
· Four Rules:
  1. Each subtype must be enclosed within the supertype entity.
  2. Common attributes and relationships must be listed only in the supertype (inherited by subtypes).
  3. A subtype can have attributes and relationships of its own.
  4. There can never be just one subtype (create an OTHER subtype if needed).

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية (Supertype Example: مثال الامتحان EXAM ووراثة الصفات والعلاقات في شرائح 10 و 11)!

تم، سأدوّن الشريحتين التاليتين من درس 4-1 (Slides 8 & 9 — Supertype Example: EXAM) بنفس القالب المنظم تماماً:

---

الشريحتان الثامنة والتاسعة (Slides 8 & 9)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 4-1 Supertypes and Subtypes (تصميم قواعد البيانات: 4-1 الأنواع الفائقة والأنواع الفرعية).

2. Slide Number (رقم الشريحة)

• Slides 8 & 9 (ترقيم أوراكل 10 و 11 من درس 4-1: Supertype Example — EXAM).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Written component (الجزء الكتابي / التحريري): تُنطق (ريتن كومبوننت) — صفة مشتركة بين جميع أنواع الامتحانات (الدرجة المخصصة للجزء الكتابي).

• Oral presentation (العرض الشفهي): تُنطق (أورال بريزينتيشن) — صفة خاصة بامتحان منتصف الفصل (MIDTERM) فقط.

• Optional paper (بحث / ورقة عمل اختيارية): تُنطق (أوبشينال بيبر) — صفة خاصة بالامتحان النهائي (FINAL) فقط للحصول على نقاط إضافية (extra points).

• Bonus question (سؤال إضافي / بونص): تُنطق (بونص كويستشن) — كيان مستقل مرتبط بعلاقة خاصة مع الاختبار القصير (QUIZ) فقط دون بقية أنواع الامتحانات.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Supertype Example — Attributes (Slide 10):

EXAM is a supertype of QUIZ, MIDTERM, and FINAL.

The subtypes have several attributes in common. These common attributes are listed at the supertype level.

Supertype Example — Relationships (Slide 11):

The same applies to relationships.

Subtypes inherit all attributes and relationships of the supertype entity.

(تفاصيل مخطط EXAM المرسوم في الشريحتين 10 و 11):

Supertype (EXAM):
– الصفات المشتركة (الموروثة للجميع): # number, * description, * weight, * date, * grade for written component
– العلاقة المشتركة (الموروثة للجميع): STUDENT take ⟷ taken by EXAM

Subtypes (مرسومة داخل EXAM):

MIDTERM: يمتلك صفة خاصة به: * grade for oral presentation

FINAL: يمتلك صفة خاصة به: * extra points for optional paper

QUIZ: لا يمتلك صفات خاصة إضافية، لكنه يمتلك علاقة خاصة مع كيان BONUS QUESTION (QUIZ includes ⟷ included in BONUS QUESTION).

5. Explanation in Arabic (الشرح باللغة العربية وتحليل المخطط)

تقدم هاتان الشريحتان أروع مثال عملي يوضح مبدأ الوراثة (Inheritance) للصفات وللعلاقات معاً في مخططات ERD:

• الكيان الفائق (EXAM - الأب):
يحتوي في الأعلى على 5 صفات مشتركة يمتلكها أي امتحان سواء كان كويز أو نصفي أو نهائي: رقم الامتحان (# number)، الوصف (* description)، الوزن (* weight)، التاريخ (* date)، ودرجة الجزء الكتابي (* grade for written component).
ويرتبط بعلاقة عامة مع كيان STUDENT (الطالب يقدم الامتحان).

• الأنواع الفرعية الثلاثة (QUIZ, MIDTERM, FINAL - الأبناء):

· ماذا يرثون؟ كل واحد منهم يرث تلقائياً الـ 5 صفات الموجودة في EXAM + العلاقة مع STUDENT (فلا نعيد كتابتها داخلهم).
· بماذا يتميز كل ابن عن إخوته؟
  · MIDTERM: يتميز بوجود صفة خاصة هي درجة العرض الشفهي (* grade for oral presentation).
  · FINAL: يتميز بوجود صفة خاصة هي النقاط الإضافية للورقة البحثية (* extra points for optional paper).
  · QUIZ: يتميز بوجود علاقة خاصة مع كيان BONUS QUESTION (لأن الكويز فقط قد يتضمن سؤال بونص إضافي).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد هذا المخطط نموذجاً مثالياً لـ "توريث الصفات والعلاقات معاً" (Attribute & Relationship Inheritance)؛ فبينما ترتبط STUDENT بالحدود الخارجية لـ EXAM (مما يعني أن الطالب يقدم كل أنواع الامتحانات)، يرتبط BONUS QUESTION مباشرة بحدود مستطيل QUIZ الداخلي، مما يحصر هذه العلاقة في الكويز فقط ويمنع ارتباط سؤال البونص بالامتحان النهائي أو النصفي!

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· خريطة مثال EXAM في 3 سطور (موضع سؤال مؤكد):
  · Supertype (EXAM): 5 صفات مشتركة + علاقة عامة مع STUDENT.
  · MIDTERM: صفة خاصة (grade for oral presentation).
  · FINAL: صفة خاصة (extra points for optional paper).
  · QUIZ: علاقة خاصة مع BONUS QUESTION.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال تحليل مخطط EXAM في الشريحتين 10 و 11):
   In the EXAM supertype/subtype diagram, which subtype has a specific relationship with the BONUS QUESTION entity, and which subtype has the * grade for oral presentation attribute?
   A) FINAL relates to BONUS QUESTION, and QUIZ has * grade for oral presentation.
   B) QUIZ relates to BONUS QUESTION, and MIDTERM has * grade for oral presentation.
   C) MIDTERM relates to BONUS QUESTION, and FINAL has * grade for oral presentation.
   • الإجابة الصحيحة: B (QUIZ يرتبط بعلاقة خاصة مع BONUS QUESTION، و MIDTERM يمتلك صفة درجة العرض الشفهي * grade for oral presentation).
2. True or False (صح أم خطأ):
   Statement: "In a supertype/subtype hierarchy, subtypes inherit all common attributes from the supertype, but they do NOT inherit relationships from the supertype." (True / False)
   • الإجابة: False (خطأ) — تنص الشريحة 11 حرفياً على أن الأنواع الفرعية ترث جميع الصفات والعلاقات معاً من الكيان الفائق (Subtypes inherit all attributes and relationships of the supertype entity).

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح الأخيرة في شابتر 4 (Exhaustive, Mutually Exclusive, & Nested Subtypes - الشمولية والتنافي والتداخل في شرائح 13, 15, 16, 17, 18)!

تم، سأدوّن الشرائح الخمس الأخيرة من درس 4-1 (Slides 10, 11, 12, 13, & 14 — Exhaustive, Mutually Exclusive, Nested Subtypes, Terminology & Summary) بنفس القالب المنظم تماماً:

---

الشرائح العاشرة والحادية عشرة والثانية عشرة والثالثة عشرة والرابعة عشرة (Slides 10, 11, 12, 13, & 14)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 4-1 Supertypes and Subtypes (تصميم قواعد البيانات: 4-1 الأنواع الفائقة والأنواع الفرعية).

2. Slide Number (رقم الشريحة)

• Slides 10, 11, 12, 13, & 14 (ترقيم أوراكل 13, 15, 16, 17, 18 من درس 4-1: Exhaustive, Mutually Exclusive, & Nested Subtypes).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Exhaustive (شامل / مستوعب لجميع الحالات): تُنطق (إجزوستيف) — شرط يضمن أن الأنواع الفرعية تغطي كل الحالات الممكنة للكيان الفائق دون استثناء (وهنا نستخدم نوع OTHER في مرحلة النمذجة المفاهيمية لضمان الشمولية).

• Mutually exclusive (متنافٍ بشكل متبادل / غير متداخل): تُنطق (ميوتشوالي إكسكلوسيف) — شرط يضمن أن كل مثيل (Instance) ينتمي إلى نوع فرعي واحد وواحد فقط ولا يمكن أن يتبع نوعين في نفس الوقت.

• Nested Subtypes (الأنواع الفرعية المتداخلة): تُنطق (نيستيد سابتايبس) — وجود نوع فرعي داخل نوع فرعي آخر على شكل مستويات متدرجة (مثل: حيوان ANIMAL ➔ فقاري VERTEBRATE ➔ طائر BIRD أو ثديي MAMMAL).

• Readability (سهولة القراءة والوضوح): تُنطق (ريدابيليتي) — معيار تصميمي ينصح بالاكتفاء بمستويين (Two levels) فقط من التداخل لكي يظل المخطط واضحاً وسهل القراءة.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Always More Than One Subtype (Slide 13):

At the conceptual modeling stage, it is good practice to include an OTHER subtype to make sure that your subtypes are exhaustive -- that you are handling every instance of the supertype. (Diagram: WALL COVERING enclosing PAINT, WALLPAPER, FABRIC, OTHER)

Correctly Identifying Subtypes (Slide 15 — الأسئلة الثلاثة للاختبار):

When modeling supertypes and subtypes, you can use three questions to see if the subtype is correctly identified:

Is this subtype a kind of supertype?

Have I covered all possible cases? (exhaustive)

Does each instance fit into one and only one subtype? (mutually exclusive) (Diagram: SNOWSPORT enclosing SKI, SNOWBOARD, CROSS COUNTRY, OTHER)

Nested Subtypes (Slide 16):

You can nest subtypes.

For ease of reading -- "readability" -- you would usually show subtypes with only two levels, but there is no rule that would stop you from going beyond two levels. (Diagram: ANIMAL ➔ VERTEBRATE [BIRD, REPTILE, MAMMAL, OTHER] & INVERTEBRATE)

Terminology & Summary (Slides 17 & 18):

Key terms: Exhaustive, Mutually exclusive, Subtype, Supertype.

Summary: Define and give examples of supertypes/subtypes, state rules, and evaluate/construct accurate ER diagrams representing them.

5. Explanation in Arabic (الشرح باللغة العربية وتلخيص القواعد النهائية)

تُعطيكِ هذه الشرائح المعايير الذهبية الثلاثة لاختبار صحة أي تصميم يحتوي على Supertype و Subtype (موضع أسئلة مؤكدة في الامتحان):

• الأسئلة الثلاثة للتحقق من صحة الأنواع الفرعية (الشريحة 15):

· السؤال الأول (اختبار الانتماء IS-A): هل هذا النوع الفرعي هو نوع من النوع الفائق؟ (Is this subtype a kind of supertype?) — مثلاً: التزلج (SKI) هو نوع من الرياضات الثلجية (SNOWSPORT).
· السؤال الثاني (الشمولية Exhaustive): هل غطيتُ جميع الحالات الممكنة؟ (Have I covered all possible cases?) — لضمان ذلك، نضيف دائماً مربع OTHER في مرحلة النمذجة المفاهيمية لاستيعاب أي حالة إضافية لم تُذكر.
· السؤال الثالث (عدم التداخل Mutually exclusive): هل كل مثيل ينتمي إلى نوع فرعي واحد وواحد فقط؟ (Does each instance fit into one and only one subtype?) — فلا يجوز أن تنتمي نفس العملية النقدية إلى CASH و CHECK في نفس اللحظة.

• التداخل بين الأنواع الفرعية (Nested Subtypes - الشريحة 16):

· يمكن وضع نوع فرعي داخل نوع فرعي آخر (مثل: ANIMAL بداخلها VERTEBRATE وبداخلها BIRD, REPTILE, MAMMAL, OTHER).
· قاعدة القراءة (Readability): يُفضّل الاكتفاء بـ مستويين فقط (Two levels) لكي لا يصبح المخطط مزدحماً وصعب القراءة، مع العلم أنه لا توجد قاعدة تمنع تجاوز المستويين عند الضرورة (no rule that would stop you from going beyond two levels).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف اجتماع شرطي Exhaustive و Mutually Exclusive باسم "التقسيم المنفصل الشامل" (Disjoint & Total Specialization)؛ فالشمولية (Exhaustive) تضمن عدم وجود سجلات يتيمة خارج الأنواع الفرعية (بفضل وجود OTHER)، والتنافي (Mutually Exclusive) يضمن أن كل سجل ينتمي لفرع واحد فقط دون ازدواجية، وهو ما يسهل تحويل الهيكل لاحقاً إلى جداول فيزيائية نظيفة.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· احفظي المعنيين الدقيقين لأهم مصطلحين في الشابتر (موضع سؤال تعريف مؤكد):
  · Exhaustive (شامل): Covered all possible cases (تغطية كل الحالات الممكنة — سرها إضافة OTHER).
  · Mutually exclusive (متنافٍ): One and only one subtype (كل مثيل يتبع نوعاً فرعياً واحداً فقط).
· قاعدة المستويات في Nested Subtypes: يُفضّل مستويان فقط (Two levels) لسهولة القراءة (Readability)، ولكن لا يوجد قانون يمنع الزيادة عن مستويين.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال التعريفات الأساسية في الشريحة 15):
   What does it mean for subtypes to be "mutually exclusive"?
   A) Every possible case of the supertype is covered by at least one subtype.
   B) Each instance of the supertype fits into one and only one subtype.
   C) Subtypes cannot inherit any attributes from the supertype.
   • الإجابة الصحيحة: B (التنافي المتبادل Mutually exclusive يعني أن كل مثيل ينتمي إلى نوع فرعي واحد وواحد فقط).
2. True or False (صح أم خطأ — قاعدة المستويات المتداخلة):
   Statement: "Database modeling rules strictly forbid nesting subtypes beyond two levels." (True / False)
   • الإجابة: False (خطأ) — يُفضَّل الاكتفاء بمستويين لسهولة القراءة (Readability)، ولكن لا توجد قاعدة تمنع تجاوز المستويين (there is no rule that would stop you from going beyond two levels).
3. Short Essay Question (سؤال مقالي قصير — متوقع جداً):
   List the three questions used to verify that subtypes are correctly identified, and explain why an OTHER subtype is included at the conceptual modeling stage.
   • الإجابة النموذجية:

· Three Questions:
  1. Is this subtype a kind of supertype?
  2. Have I covered all possible cases? (exhaustive)
  3. Does each instance fit into one and only one subtype? (mutually exclusive)
· Purpose of OTHER: Including an OTHER subtype ensures that the subtypes are exhaustive—meaning every possible instance of the supertype is handled.

---

ألف مبروك! أنهيتِ الآن تدوين شابتر 1 و 2 و 3 و 4 بالكامل في دفتركِ. هل تودين أن نختم بـ امتحان تجريبي شامل (Mock Exam) يغطي شابتر 3 وشابتر 4 معاً بنمط أسئلة الامتحان، أم لديكِ ملف لشابتر 5؟


تم، سأدوّن الشرائح الأولى من درس 5-1 (Pages 1–4 — Relationship Transferability: Objectives, Purpose, & Examples) بنفس القالب المنظم تماماً:

---

الصفحات الأولى والثانية والثالثة والرابعة (Pages 1–4)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-1 Relationship Transferability (تصميم قواعد البيانات: 5-1 قابلية نقل العلاقات).

2. Slide Number (رقم الشريحة)

• Pages 1–4 (شرائح العنوان، الأهداف، الغرض، والأمثلة في درس 5-1 — ترقيم أوراكل 1, 3, 4).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Relationship Transferability (قابلية نقل العلاقة): تُنطق (ريليشنشيب ترانسفيرابيليتي) — خاصية تحدد ما إذا كان يمكن تغيير ارتباط سجل من مثيل معين إلى مثيل آخر في المستقبل أم أن الارتباط ثابت لا يتغير أبداً.

• Transferable Relationship (علاقة قابلة للنقل / التغيير): تُنطق (ترانسفيرابل ريليشنشيب) — علاقة يُسمح فيها بتحديث المفتاح الأجنبي ونقل السجل من كيان لآخر (مثل نقل صف دراسي من مدرس لآخر، أو نقل موظف من قسم لآخر).

• Nontransferable Relationship (علاقة غير قابلة للنقل / ثابتة): تُنطق (نان-ترانسفيرابل ريليشنشيب) — علاقة دائمة لا يمكن نقلها لشخص أو جهة أخرى بعد إنشائها (مثل الفاتورة أو الإيصال المالي أو الطلب الإلكتروني بعد تأكيده).

• Allocated (مُخصَّص / مُسند لـ): تُنطق (آلوكيتيد) — إسناد صف دراسي أو مهمة لمدرس معين.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 2):
This lesson covers the following objectives:

Describe and give an example of relationship transferability

Understand the difference between transferable and nontransferable relationships

Illustrate nontransferable relationships on ERDs

Purpose (Page 3):

Once a class has been allocated to a teacher, can that class later be transferred to another teacher, possibly in mid-semester?

Usually yes, because if not, what would we do if the original teacher becomes sick?

Some health clubs allow memberships to be transferred from one person to another, but other health clubs don't.

This business rule is normally determined by what is most efficient and most profitable for the club.

Examples (Page 4):

A person may change departments or jobs within a company, so the relationship is transferable.

A person places an order from an internet company, once the order is placed by someone, that relationship cannot change. non-transferable.

5. Explanation in Arabic (الشرح باللغة العربية)

توضح هذه الشرائح الأربع مفهوم "قابلية نقل العلاقة" (Transferability) من خلال سؤال بسيط: بعد ربط سجلين ببعضهما في قاعدة البيانات، هل يسمح قانون المؤسسة (Business Rule) بنقل هذا الارتباط إلى سجل آخر مستقبلاً؟

• العلاقة القابلة للنقل (Transferable Relationship):

· هي العلاقة التي تقبل التغيير والتحديث.
· أمثلتها في الشرائح:
  · الصف الدراسي والمدرس: إذا مرض المدرس في منتصف الفصل الدراسي، يمكن نقل الصف الدراسي لمدرس بديل.
  · الموظف والقسم أو الوظيفة: يمكن للموظف أن ينتقل من قسم لآخر أو يغير وظيفته داخل الشركة.

• العلاقة غير القابلة للنقل (Nontransferable Relationship):

· هي العلاقة التي تُقفل للأبد بمجرد إنشائها ولا يمكن تحويلها لطرف آخر.
· أمثلتها في الشرائح:
  · الطلب الإلكتروني (Order): بمجرد أن يطلب العميل طلباً من شركة إنترنت، يرتبط هذا الطلب بهذا العميل ولا يمكن نقله لعميل آخر.
  · عضوية النادي الصحي (Health club membership): بعض النوادي تمنع نقل العضوية من شخص لآخر حسب سياسة النادي (Business rule).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُترجم مفهوم Nontransferable Relationship عند التنفيذ الفيزيائي إلى "المفتاح الأجنبي غير القابل للتحديث" (Immutable Foreign Key)؛ فبينما تسمح العلاقة القابلة للنقل بتنفيذ أمر UPDATE لتغيير قيمة DEPARTMENT_ID في جدول الموظفين، تفرض العلاقة غير القابلة للنقل قيداً برمجياً (Trigger) يمنع تعديل CUSTOMER_ID في جدول الفواتير والطلبات لحفظ النزاهة المحاسبية والتدقيق المالي (Audit Trail).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· مقارنة الأمثلة الأربعة في الشرائح (موضع سؤال مؤكد):
  · Transferable (قابلة للنقل): Teacher ⟷ Class (تغيير المدرس عند المرض) + Employee ⟷ Department/Job (نقل الموظف لقسم أو وظيفة أخرى).
  · Nontransferable (غير قابلة للنقل): Customer ⟷ Internet Order (الطلب الإلكتروني بعد تأكيده) + Health Club Membership (في النوادي التي تمنع النقل).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الأمثلة في الصفحة 4):
   Which of the following is an example of a "nontransferable" relationship?
   A) An employee changing departments within a company.
   B) A class being reassigned to another teacher when the original teacher gets sick.
   C) A customer placing an order with an internet company, where once placed, the order cannot be reassigned to another customer.
   • الإجابة الصحيحة: C (الطلب الإلكتروني بمجرد تقديمه لا يمكن تغييره أو نقله لشخص آخر non-transferable).
2. True or False (صح أم خطأ):
   Statement: "Whether a relationship is transferable or nontransferable is determined by the business rules of the organization." (True / False)
   • الإجابة: True (صح) — تنص الصفحة 3 على أن قاعدة العمل (Business rule) هي التي تحدد قابلية النقل بناءً على ما هو أكثر كفاءة وربحية للمؤسسة.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية في درس 5-1 (مراجعة العلاقة والرمز الهندسي المعين Diamond للعلاقة غير القابلة للنقل في الصفحات 5 إلى 12)!

تم، سأدوّن الشرائح المتبقية من درس 5-1 (Pages 5–12 — Relationship Review, Diamond Symbol, Terminology, & Summary) بنفس القالب المنظم تماماً:

---

الصفحات الخامسة إلى الثانية عشرة (Pages 5–12)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-1 Relationship Transferability (تصميم قواعد البيانات: 5-1 قابلية نقل العلاقات).

2. Slide Number (رقم الشريحة)

• Pages 5–12 (ترقيم أوراكل 5, 6, 7, 8, 9, 10, 12, 13 من درس 5-1: Relationship Review, Diamond Symbol, Terminology, & Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Diamond (المعيّن الهندسي ◇): تُنطق (دايموند) — الرمز الرسمي المعتمد في مخططات أوراكل (ERD) ويُوضع على خط العلاقة للدلالة على أن العلاقة غير قابلة للنقل (Nontransferable).

• Study Group (مجموعة دراسية): تُنطق (ستادي جروب) — مثال على العلاقة القابلة للنقل؛ حيث يُسمح للطالب (STUDENT) بالانتقال من مجموعة دراسية إلى أخرى.

• Receipt (إيصال مالي / وصل دفع): تُنطق (ريسيت) — مثال على العلاقة غير القابلة للنقل؛ فالإيصال الصادر لطالب معين لا يمكن نقله لطالب آخر أبداً، وإذا صدر بالخطأ يجب إلغاؤه (Cancelled) وإصدار إيصال جديد.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Relationship Review — The Three Questions (Pages 5–7):

Optionality: Must every EMPLOYEE be assigned to a DEPARTMENT? Must every DEPARTMENT be responsible for an employee?

Cardinality: How many EMPLOYEEs can a DEPARTMENT be responsible for? How many DEPARTMENTs can an EMPLOYEE be assigned to?

Transferability: Can an EMPLOYEE be transferred from one DEPARTMENT to another DEPARTMENT? (Yes — Transferable)

Transferable Relationship Example (Page 8):

Transferable: A STUDENT being allowed to move from one STUDY GROUP to another.

(Diagram: خط عادي بدون رمز معيّن بين STUDENT و STUDY GROUP).

Nontransferable Relationship Example & Symbol (Pages 9 & 10):

Nontransferable: A STUDENT can be issued a RECEIPT for paying tuition fees, taking a certification exam, or purchasing items at the bookstore.

Once a RECEIPT has been issued, it cannot be transferred to another STUDENT.

If it was issued in error, it would have to be cancelled, and another RECEIPT would have to be written up.

A nontransferable relationship is represented with the diamond (◇) on the relationship.

Terminology & Summary (Pages 11 & 12):

Key terms: Nontransferable, Transferable.

Summary: Describe/give examples of transferability, understand the difference between transferable and nontransferable relationships, and illustrate nontransferable relationships on ERDs.

5. Explanation in Arabic (الشرح باللغة العربية وقواعد الرسم)

تُكمل هذه الشرائح الصورة الكاملة لقراءة ورسم أي علاقة بإضافة البُعد الثالث لها وهو Transferability، وتوضح الرمز البصري الخاص بها:

• الأسئلة الثلاثة الشاملة لأي علاقة (الصفحات 5–7): عند تحليل أي خط بين جدولين، نسأل 3 أسئلة:

· Optionality: هل يجب؟ (Must / May).
· Cardinality: كم العدد؟ (One / Many).
· Transferability: هل يمكن نقل السجل لطرف آخر مستقبلاً؟ (Can it be transferred?).

• الفرق البصري على الرسمة (مهم جداً للامتحان):

· العلاقة القابلة للنقل (Transferable): تُرسم كخط عادي بدون أي رمز إضافي (مثل انتقال الطالب STUDENT من STUDY GROUP إلى أخرى).
· العلاقة غير القابلة للنقل (Nontransferable): نضع عليها رمز المعيّن (Diamond ◇) بالقرب من الكيان الذي لا يمكن نقله (مثل الإيصال المالي RECEIPT المرتبط بطالب STUDENT؛ إذا أخطأ المحاسب في اسم الطالب، لا يجوز تعديل اسم الطالب على الإيصال، بل يُلغى الإيصال Cancelled ويُكتب إيصال جديد).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات المحاسبية والمالية بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف الإجراء المذكور في الصفحة 10 ("إذا صدر الإيصال بالخطأ يجب إلغاؤه وإصدار إيصال جديد") باسم "مبدأ السجلات غير القابلة للتعديل / قيود العكس المحاسبي" (Immutability & Reversal Ledger Principle)؛ وهو حجر الزاوية في أنظمة البنوك والفواتير لمنع التلاعب المالي وضمان وجود سجل تدقيق (Audit Log) لكل عملية إلغاء وإعادة إصدار.

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· الرمز السحري للامتحان (موضع سؤال مؤكد):
  · Diamond (◇) على خط العلاقة = Nontransferable (غير قابلة للنقل).
  · بدون معيّن = Transferable (قابلة للنقل — وهي الحالة الافتراضية).
· مثالان للحفظ السريع:
  · STUDENT ⟷ STUDY GROUP = Transferable (ينتقل لمجموعة أخرى عادي).
  · RECEIPT ⟷ STUDENT = Nontransferable (◇) (الإيصال المالي ممنوع نقله لطالب آخر).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال الرمز الهندسي في الشريحة 9):
   How is a "nontransferable" relationship visually represented on an Oracle ER diagram?
   A) With an asterisk (*) on the relationship line
   B) With a diamond (◇) on the relationship line
   C) With a crow's foot at both ends
   • الإجابة الصحيحة: B (تُمثَّل العلاقة غير القابلة للنقل بوضع شكل المعيّن Diamond على خط العلاقة).
2. True or False (صح أم خطأ — من مثال الإيصال المالي في الصفحة 10):
   Statement: "If a student's RECEIPT was issued in error, the accountant can simply transfer the existing receipt to another student instead of cancelling it." (True / False)
   • الإجابة: False (خطأ) — لأن العلاقة بين STUDENT و RECEIPT غير قابلة للنقل (Nontransferable)، يجب إلغاء الإيصال (cancelled) وكتابة إيصال جديد.

---

ألف مبروك! أنهيتِ الآن تدوين الدرس الأول من شابتر 5 (5-1 Relationship Transferability) بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الثاني (5-2 Relationship Types: أنواع العلاقات 1:1, 1:M, M:M, والعلاقات المكررة Redundant Relationships في الصفحات 13 إلى 22)!


تم، سأدوّن شرائح الدرس الثاني الأولى (Pages 13–17 — Relationship Types: Objectives, Purpose, & One-to-Many Relationships) بنفس القالب المنظم تماماً:

---

الصفحات الثالثة عشرة إلى السابعة عشرة (Pages 13–17)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-2 Relationship Types (تصميم قواعد البيانات: 5-2 أنواع العلاقات).

2. Slide Number (رقم الشريحة)

• Pages 13–17 (ترقيم أوراكل 1, 3, 4, 5 من درس 5-2 مع الشريحة المرفقة DFo 3-6 رقم 11: Objectives, Purpose, & One-to-Many (1:M) Relationships).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• One-to-Many Relationship (1:M) (علاقة واحد إلى متعدد): تُنطق (وَن-تو-ميني ريليشنشيب) — النوع الأكثر شيوعاً في قواعد البيانات العلائقية؛ حيث يرتبط سجل واحد في الجدول الأول بعدة سجلات في الجدول الثاني (مثل: قسم واحد يضم عدة موظفين).

• Many-to-One Relationship (M:1) (علاقة متعدد إلى واحد): تُنطق (ميني-تو-وَن ريليشنشيب) — نفس علاقة 1:M ولكن عند قراءتها من الاتجاه المعاكس (مثل: عدة موظفين يعملون في قسم واحد).

• Zero-or-more vs. One-or-more (صفر أو أكثر مقابل واحد أو أكثر): تُنطق (زيرو أور مور مقابل وَن أور مور) — قاعدة توضح أن كلمة "متعدد (Many)" تعني واحد أو أكثر إذا كانت العلاقة إلزامية (Solid line)، وتعني صفر أو أكثر إذا كانت العلاقة اختيارية (Dashed line).

• Sales Representative (مندوب مبيعات): تُنطق (سيلز ريبريزينتاتيف) — مثال توضيحي لعلاقة 1:M؛ فمندوب المبيعات الواحد يخدم عدة عملاء (CUSTOMERs).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 14):
This lesson covers the following objectives:

Recognize and give examples of a one-to-one relationship

Recognize and give examples of a one-to-many relationship

Recognize and give examples of a many-to-many relationship

Recognize redundant relationships and remove them from the ERD

Purpose (Page 15):

Can one PERSON own many DVDs, or only one?

Can one DVD be owned by many PERSONs?

As we refine and improve our model, we want to make sure our entity relationships correctly model our business rules.

Remember, you can avoid future costly mistakes by thinking through the details early on.

One-to-Many (1:M) / Many-to-One (M:1) Relationships (Pages 16 & 17):

The various types of 1:M relationships are most common in an ER Model.

"Many" can mean one-or-more or zero-or-more, depending on the optionality. (Example: DEPARTMENT 1:M EMPLOYEE)

DFo 3-6 Slide 11: Many-to-one and one-to-many relationships (M:1 and 1:M) have cardinality of one or more in one direction and one and only one in the other direction.
– Each CUSTOMER must be visited by one and only one SALES REPRESENTATIVE.
– Each SALES REPRESENTATIVE may be assigned to one or more CUSTOMERs.

5. Explanation in Arabic (الشرح باللغة العربية)

تُقدّم هذه الشرائح نظرة شاملة على أنواع العلاقات الثلاثة (1:1, 1:M, M:M) وتبدأ بشرح النوع الأول والأكثر انتشاراً وهو علاقة واحد إلى متعدد (1:M):

• لماذا 1:M هي الأكثر شيوعاً؟ لأن أغلب العلاقات في الواقع تتبع هذا النمط: قسم واحد يضم عدة موظفين، مندوب مبيعات واحد يتابع عدة عملاء، أم واحدة لديها عدة أبناء.

• خصائص علاقة 1:M (أو M:1):

· في أحد الاتجاهين تكون التعددية مفردة (One and only one - Single toe).
· وفي الاتجاه المقابل تكون التعددية جمعاً (One or more - Crow's foot).

• قاعدة معنى كلمة Many (مهمة جداً للامتحان):
كلمة Many (رِجل الغراب) لا تعني دائماً "واحد على الأقل"، بل يعتمد حدها الأدنى على الاختيارية (Optionality):

· إذا كان الخط عند رِجل الغراب متصلاً (Mandatory) ➔ تعني one-or-more (واحد أو أكثر).
· إذا كان الخط عند رِجل الغراب متقطعاً (Optional) ➔ تعني zero-or-more (صفر أو أكثر — أي قد يكون القسم جديداً وبداخله صفر موظفين).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد فهم علاقة 1:M (واحد إلى متعدد) حجر الأساس للتنفيذ الفيزيائي؛ لأن القاعدة الذهبية لتحويل مخطط ERD إلى جداول هي: "المفتاح الأساسي من جهة الواحد (1) ينتقل كمفتاح أجنبي (Foreign Key) إلى جهة المتعدد (M)" (فمثلاً DEPARTMENT_ID ينتقل إلى جدول EMPLOYEE، و SALES_REP_ID ينتقل إلى جدول CUSTOMER).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 3 حقائق ذهبية عن 1:M للامتحان:
  · هي الأكثر شيوعاً (Most common) في مخططات ER.
  · لها Single toe في طرف، و Crow's foot في الطرف الآخر.
  · معنى Many يتغير حسب الخط: متصل = one-or-more | متقطع = zero-or-more.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 16):
   Which type of relationship is the MOST common in an Entity Relationship (ER) model?
   A) One-to-One (1:1)
   B) One-to-Many (1:M)
   C) Many-to-Many (M:M)
   • الإجابة الصحيحة: B (علاقات الواحد إلى متعدد 1:M هي الأكثر شيوعاً في نماذج ER).
2. True or False (صح أم خطأ — قاعدة معنى كلمة Many):
   Statement: "In a 1:M relationship, 'Many' can mean either one-or-more or zero-or-more, depending on the optionality of the relationship." (True / False)
   • الإجابة: True (صح) — هذا هو النص المذكور بالخط العريض أسفل الصفحة 16 حرفياً.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية في درس 5-2 (علاقات متعدد إلى متعدد M:M وعلاقات واحد إلى واحد 1:1 والعلاقات المكررة Redundant في الصفحات 18 إلى 22)!

تم، سأدوّن شرائح الدرس الثاني الأولى (Pages 13–17 — Relationship Types: Objectives, Purpose, & One-to-Many Relationships) بنفس القالب المنظم تماماً:

---

الصفحات الثالثة عشرة إلى السابعة عشرة (Pages 13–17)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-2 Relationship Types (تصميم قواعد البيانات: 5-2 أنواع العلاقات).

2. Slide Number (رقم الشريحة)

• Pages 13–17 (ترقيم أوراكل 1, 3, 4, 5 من درس 5-2 مع الشريحة المرفقة DFo 3-6 رقم 11: Objectives, Purpose, & One-to-Many (1:M) Relationships).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• One-to-Many Relationship (1:M) (علاقة واحد إلى متعدد): تُنطق (وَن-تو-ميني ريليشنشيب) — النوع الأكثر شيوعاً في قواعد البيانات العلائقية؛ حيث يرتبط سجل واحد في الجدول الأول بعدة سجلات في الجدول الثاني (مثل: قسم واحد يضم عدة موظفين).

• Many-to-One Relationship (M:1) (علاقة متعدد إلى واحد): تُنطق (ميني-تو-وَن ريليشنشيب) — نفس علاقة 1:M ولكن عند قراءتها من الاتجاه المعاكس (مثل: عدة موظفين يعملون في قسم واحد).

• Zero-or-more vs. One-or-more (صفر أو أكثر مقابل واحد أو أكثر): تُنطق (زيرو أور مور مقابل وَن أور مور) — قاعدة توضح أن كلمة "متعدد (Many)" تعني واحد أو أكثر إذا كانت العلاقة إلزامية (Solid line)، وتعني صفر أو أكثر إذا كانت العلاقة اختيارية (Dashed line).

• Sales Representative (مندوب مبيعات): تُنطق (سيلز ريبريزينتاتيف) — مثال توضيحي لعلاقة 1:M؛ فمندوب المبيعات الواحد يخدم عدة عملاء (CUSTOMERs).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 14):
This lesson covers the following objectives:

Recognize and give examples of a one-to-one relationship

Recognize and give examples of a one-to-many relationship

Recognize and give examples of a many-to-many relationship

Recognize redundant relationships and remove them from the ERD

Purpose (Page 15):

Can one PERSON own many DVDs, or only one?

Can one DVD be owned by many PERSONs?

As we refine and improve our model, we want to make sure our entity relationships correctly model our business rules.

Remember, you can avoid future costly mistakes by thinking through the details early on.

One-to-Many (1:M) / Many-to-One (M:1) Relationships (Pages 16 & 17):

The various types of 1:M relationships are most common in an ER Model.

"Many" can mean one-or-more or zero-or-more, depending on the optionality. (Example: DEPARTMENT 1:M EMPLOYEE)

DFo 3-6 Slide 11: Many-to-one and one-to-many relationships (M:1 and 1:M) have cardinality of one or more in one direction and one and only one in the other direction.
– Each CUSTOMER must be visited by one and only one SALES REPRESENTATIVE.
– Each SALES REPRESENTATIVE may be assigned to one or more CUSTOMERs.

5. Explanation in Arabic (الشرح باللغة العربية)

تُقدّم هذه الشرائح نظرة شاملة على أنواع العلاقات الثلاثة (1:1, 1:M, M:M) وتبدأ بشرح النوع الأول والأكثر انتشاراً وهو علاقة واحد إلى متعدد (1:M):

• لماذا 1:M هي الأكثر شيوعاً؟ لأن أغلب العلاقات في الواقع تتبع هذا النمط: قسم واحد يضم عدة موظفين، مندوب مبيعات واحد يتابع عدة عملاء، أم واحدة لديها عدة أبناء.

• خصائص علاقة 1:M (أو M:1):

· في أحد الاتجاهين تكون التعددية مفردة (One and only one - Single toe).
· وفي الاتجاه المقابل تكون التعددية جمعاً (One or more - Crow's foot).

• قاعدة معنى كلمة Many (مهمة جداً للامتحان):
كلمة Many (رِجل الغراب) لا تعني دائماً "واحد على الأقل"، بل يعتمد حدها الأدنى على الاختيارية (Optionality):

· إذا كان الخط عند رِجل الغراب متصلاً (Mandatory) ➔ تعني one-or-more (واحد أو أكثر).
· إذا كان الخط عند رِجل الغراب متقطعاً (Optional) ➔ تعني zero-or-more (صفر أو أكثر — أي قد يكون القسم جديداً وبداخله صفر موظفين).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد فهم علاقة 1:M (واحد إلى متعدد) حجر الأساس للتنفيذ الفيزيائي؛ لأن القاعدة الذهبية لتحويل مخطط ERD إلى جداول هي: "المفتاح الأساسي من جهة الواحد (1) ينتقل كمفتاح أجنبي (Foreign Key) إلى جهة المتعدد (M)" (فمثلاً DEPARTMENT_ID ينتقل إلى جدول EMPLOYEE، و SALES_REP_ID ينتقل إلى جدول CUSTOMER).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 3 حقائق ذهبية عن 1:M للامتحان:
  · هي الأكثر شيوعاً (Most common) في مخططات ER.
  · لها Single toe في طرف، و Crow's foot في الطرف الآخر.
  · معنى Many يتغير حسب الخط: متصل = one-or-more | متقطع = zero-or-more.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 16):
   Which type of relationship is the MOST common in an Entity Relationship (ER) model?
   A) One-to-One (1:1)
   B) One-to-Many (1:M)
   C) Many-to-Many (M:M)
   • الإجابة الصحيحة: B (علاقات الواحد إلى متعدد 1:M هي الأكثر شيوعاً في نماذج ER).
2. True or False (صح أم خطأ — قاعدة معنى كلمة Many):
   Statement: "In a 1:M relationship, 'Many' can mean either one-or-more or zero-or-more, depending on the optionality of the relationship." (True / False)
   • الإجابة: True (صح) — هذا هو النص المذكور بالخط العريض أسفل الصفحة 16 حرفياً.

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح التالية في درس 5-2 (علاقات متعدد إلى متعدد M:M وعلاقات واحد إلى واحد 1:1 والعلاقات المكررة Redundant في الصفحات 18 إلى 22)!

تم، سأدوّن الشرائح الخمس المتبقية من درس 5-2 (Pages 18–22 — Many-to-Many, One-to-One, Redundant Relationships, Terminology & Summary) بنفس القالب المنظم تماماً:

---

الصفحات الثامنة عشرة إلى الثانية والعشرين (Pages 18–22)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-2 Relationship Types (تصميم قواعد البيانات: 5-2 أنواع العلاقات).

2. Slide Number (رقم الشريحة)

• Pages 18–22 (ترقيم أوراكل 6, 7, 11, 12 من درس 5-2 مع الشريحة المرفقة DFo 3-6 رقم 13: Many-to-Many, One-to-One, Redundant Relationships, Terminology, & Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Many-to-Many Relationship (M:M) (علاقة متعدد إلى متعدد): تُنطق (ميني-تو-ميني ريليشنشيب) — علاقة تحتوي على Crow's foot عند كلا الطرفين (مثل: الطالب يدرس عدة مساقات، والمساق يدرسه عدة طلاب)، وتظهر في النسخة الأولى فقط ثم تُحل وتختفي.

• First version of an ER model (النسخة الأولى من المخطط): تُنطق (فيرست فيرجن أوف آن إي آر موديل) — المرحلة الأولية التي تظهر فيها علاقات M:M قبل تفكيكها بكيان وسيط.

• One-to-One Relationship (1:1) (علاقة واحد إلى واحد): تُنطق (وَن-تو-وَن ريليشنشيب) — علاقة نادرة نسبياً يكون فيها الطرفان مفردين (Single toe عند كلا الجانبين)، وتُستخدم غالباً لتمثيل الأدوار (Roles) أو المكونات الحصرية (مثل الحاسوب واللوحة الأم COMPUTER & MOTHERBOARD).

• Roles (الأدوار الوظيفية / الاجتماعية): تُنطق (رولز) — مثال شائع لعلاقة 1:1 إلزامية من طرف واحد؛ مثل الشخص (PERSON) الذي قد يؤدي دور مدرس (TEACHER) أو دور طالب (STUDENT).

• Redundant Relationship (العلاقة المكررة / الزائدة): تُنطق (ريداندانت ريليشنشيب) — علاقة مباشرة بين جدولين يمكن استنتاجها أصلاً عبر مسار علاقة أخرى تمر بجدول ثالث، لذا يجب حذفها من المخطط لمنع التكرار والتناقض.

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Many-to-Many (M:M) Relationships (Page 18):

The various types of M:M relationships are common, particularly in a first version of an ER model.

In later stages of the modeling process, all M:M relationships will be resolved, and disappear. (Example: STUDENT learns from ⟷ educates TEACHER)

One-to-One (1:1) Relationships For Roles (Page 19):

Usually you will find just a few of the various types of 1:1 relationships in every ER model.

Mandatory at one end of the 1:1 relationship commonly occurs when roles are modeled. (Example: PERSON acting as ⟷ role of TEACHER / STUDENT)

One-to-One (1:1) Relationships — Component Example (DFo 3-6 Page 20):

One-to-one relationships (1:1) have cardinality of one and only one in both directions. (Example: COMPUTER contain ⟷ contained in MOTHERBOARD)
– Each COMPUTER must contain one and only one MOTHERBOARD.
– Each MOTHERBOARD must be contained in one and only one COMPUTER.

Terminology & Summary (Pages 21 & 22):

Key terms: Many-to-many (M:M), One-to-many (1:M), One-to-one (1:1), Redundant.

Summary: Recognize and give examples of 1:1, 1:M, M:M relationships, and recognize redundant relationships and remove them from the ERD.

5. Explanation in Arabic (الشرح باللغة العربية وتلخيص الأنواع)

تُكمل هذه الشرائح أنواع العلاقات وتشرح مصير كل نوع في مخطط ERD:

• علاقة متعدد إلى متعدد (M:M - الصفحة 18):

· تظهر بكثرة في المسودة الأولى (First version) للمخطط (مثل: الطالب يتعلم من عدة مدرسين، والمدرس يُعلّم عدة طلاب — رِجل غراب في الطرفين).
· مصيرها الحتمي: لا يمكن تنفيذ علاقة M:M مباشرة في قواعد البيانات العلائقية؛ لذا في المراحل اللاحقة تُحل وتختفي (will be resolved, and disappear) بتحويلها إلى كيان وسيط (كما سندرس بالتفصيل في الدرس القادم 5-3).

• علاقة واحد إلى واحد (1:1 - الصفحتان 19 و 20):

· قليلة الوجود (Just a few) في المخططات، ولها حالتان مشهورتان في الشرائح:
  · تمثيل الأدوار (Roles): مثل كيان PERSON يرتبط بعلاقة 1:1 مع TEACHER و STUDENT (كل مدرس يجب أن يكون شخصاً واحداً، وكل شخص قد يؤدي دور مدرس واحد).
  · المكونات الحصرية: مثل الحاسوب واللوحة الأم (COMPUTER و MOTHERBOARD)؛ كل حاسوب يحتوي على لوحة أم واحدة فقط، وكل لوحة أم موجودة في حاسوب واحد فقط.

• العلاقات المكررة (Redundant Relationships):
هي خط علاقة زائد يمكن الوصول إليه عبر كيانات أخرى في المخطط (مثلاً إذا كان القسم مرتبطاً بالموظف، والموظف مرتبطاً بالمشروع التابع للقسم، فرسم خط مباشر إضافي بين القسم والمشروع قد يكون مكرراً إذا كان يعطي نفس المعلومة)، ويجب حذفها (remove them from the ERD).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى إزالة العلاقات المكررة (Redundant Relationships) على أنها "تقليل الحلقات الدلالية" (Eliminating Semantic Cycles)؛ لأن وجود مسارين لنفس المعلومة في قاعدة البيانات قد يؤدي إلى تناقض التحديث (Update Anomaly) إذا عُدِّل مسار وتُرك المسار الآخر. كما تبيّن Stanford أن علاقات 1:1 للأدوار (PERSON ➔ TEACHER/STUDENT) تُعد بديلاً مرناً لنمط Supertype/Subtype عندما يمكن للشخص الواحد أن يلعب الدورين معاً (معيد يدرس مساقات دراسات عليا في نفس الوقت).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· مقارنة سريعة لأنواع العلاقات الثلاثة (1:M, M:M, 1:1) للامتحان:
  · 1:M: الأكثر شيوعاً (Most common) وتبقى في المخطط النهائي.
  · M:M: تظهر في النسخة الأولى فقط (First version) ثم تُحل وتختفي (Resolved and disappear).
  · 1:1: قليلة جداً (Just a few) وتحدث غالباً عند نمذجة الأدوار (Roles) أو المكونات الفريدة (COMPUTER ⟷ MOTHERBOARD).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مصير علاقات M:M في الصفحة 18):
   What happens to Many-to-Many (M:M) relationships in the later stages of the database modeling process?
   A) They remain unchanged and are implemented directly as a single foreign key.
   B) They are resolved (using an intersection entity) and disappear from the final ERD.
   C) They are converted into One-to-One (1:1) relationships.
   • الإجابة الصحيحة: B (تُحل جميع علاقات M:M في المراحل اللاحقة وتختفي will be resolved, and disappear).
2. Multiple Choice (سؤال علاقات 1:1 في الصفحة 19):
   When does a One-to-One (1:1) relationship that is mandatory at one end commonly occur in an ER model?
   A) When modeling roles (such as a PERSON acting as a TEACHER or STUDENT).
   B) When modeling a customer placing multiple orders.
   C) When resolving a many-to-many relationship between students and courses.
   • الإجابة الصحيحة: A (تحدث غالباً عند نمذجة الأدوار when roles are modeled).
3. True or False (صح أم خطأ):
   Statement: "Redundant relationships provide helpful backup paths in an ER diagram and should always be kept." (True / False)
   • الإجابة: False (خطأ) — يجب اكتشاف العلاقات المكررة وإزالتها من مخطط ERD (Recognize redundant relationships and remove them from the ERD).

---

ألف مبروك! أنهيتِ الآن تدوين الدرس الثاني من شابتر 5 (5-2 Relationship Types) بالكامل. أخبريني عندما تكونين جاهزة للانتقال إلى الدرس الثالث والأخير (5-3 Resolving Many-to-Many Relationships: حل علاقات متعدد إلى متعدد والكيان الوسيط والعلاقات القاطعة Barred Relationships في الصفحات 23 إلى 34)!

تم، سأدوّن شرائح الدرس الثالث الأولى (Pages 23–28 — Resolving Many-to-Many Relationships: Objectives, Purpose, Relationship Hiding an Attribute, & Resolution) بنفس القالب المنظم تماماً:

---

الصفحات الثالثة والعشرين إلى الثامنة والعشرين (Pages 23–28)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-3 Resolving Many-to-Many Relationships (تصميم قواعد البيانات: 5-3 حل علاقات متعدد إلى متعدد).

2. Slide Number (رقم الشريحة)

• Pages 23–28 (ترقيم أوراكل 1, 3, 4, 5, 6, 7 من درس 5-3: Objectives, Purpose, Relationship Hiding an Attribute, & Resolution of a M:M Relationship).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Resolving Many-to-Many Relationships (حل علاقات متعدد إلى متعدد): تُنطق (ريزولفينج ميني-تو-ميني ريليشنشيبس) — تفكيك العلاقة المباشرة من نوع M:M بين جدولين إلى جدولين من نوع 1:M عن طريق إضافة جدول ثالث وسيط.

• Relationship Hiding an Attribute (علاقة تُخفي صفة بداخلها): تُنطق (ريليشنشيب هايدينج آن أتريبيوت) — مشكلة تصميمية تحدث عندما توجد صفة (مثل الدرجة Grade) لا تنتمي للجدول الأول بمفرده ولا للجدول الثاني بمفرده، بل تنتمي للتفاعل بينهما.

• Intersection Entity (كيان التقاطع / الكيان الوسيط): تُنطق (إنترسيكشن إينتيتي) — الكيان الثالث الجديد الذي ننشئه لكسر علاقة M:M واستيعاب الصفات المشتركة الناتجة عن التقاء الكيانين (مثل ENROLLMENT بين STUDENT و SUBJECT).

• Scope of your data model (نطاق نموذج البيانات): تُنطق (سكوب أوف يور داتا موديل) — حدود النظام؛ أي أننا ننمذج فقط ما هو مهم لعمل المؤسسة (what is of importance to the business).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Objectives (Page 24):
This lesson covers the following objectives:

Identify attributes which belong to many-to-many relationships

Demonstrate the steps to resolve a many-to-many relationship using an intersection entity

Identify the UID of an intersection entity and represent it in the entity relationship diagram

Purpose (Page 25):

This lesson will help you complete your model - you may need to create new entities or new relationships based on the business needs.

It will also help you define the scope of your data model - you only model what is of importance to the business.

Relationship Hiding an Attribute — Example (Pages 26 & 27):

In a school, a STUDENT may study one or more SUBJECTs. Each SUBJECT may be studied by one or more STUDENTs. (M:M Relationship)

When a student enrolls for a subject, we want to be able to record the grade they attain for that subject.

Which entity would the attribute "Grade" belong to?
– If we put "Grade" in the STUDENT entity, how would we know which SUBJECT it is for?
– If we put "Grade" in the SUBJECT entity, how would we know which STUDENT got that grade?

Resolution of a M:M Relationship (Page 28):

A third entity is needed to resolve the M:M relationship. This is called an "intersection" entity.

5. Explanation in Arabic (الشرح باللغة العربية وتحليل المشكلة)

تشرح هذه الشرائح الست السبب المنطقي الذي يجعل علاقة M:M غير قابلة للتنفيذ مباشرة، وتكشف كيف نحلها:

• مشكلة "الصفة المخفية" (Relationship Hiding an Attribute - الصفحتان 26 و 27):

· لدينا علاقة M:M بين الطالب (STUDENT) والمادة (SUBJECT): الطالب يدرس عدة مواد، والمادة يدرسها عدة طلاب.
· الآن تريد المدرسة تسجيل الدرجة (Grade) التي يحصل عليها الطالب في المادة.
· السؤال المحيّر: أين نضع عمود Grade؟
  · لو وضعناه في جدول STUDENT، سنعرف درجة الطالب (مثلاً 95)، لكننا لن نعرف هذه الدرجة لأي مادة!
  · ولو وضعناه في جدول SUBJECT، سنعرف أن المادة فيها درجة 95، لكننا لن نعرف أي طالب حصل عليها!

• الحل (Intersection Entity - الصفحة 28):
صفة Grade لا تتبع الطالب وحده ولا المادة وحدها، بل تتبع عملية تسجيل الطالب في المادة؛ لذا نحتاج لإنشاء كيان ثالث وسيط (Intersection Entity) نسميه مثلاً ENROLLMENT (التسجيل)، ونضع بداخله صفة Grade.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف الكيان الوسيط (Intersection Entity) باسم "الكيان الترابطي" (Associative Entity)؛ وهو تحويل العلاقة M:M نفسها إلى كيان مستقل (Reification of a Relationship) لكي يتمكن من حمل صفات التفاعل (مثل الدرجة Grade أو تاريخ التسجيل) ولكي تتوزع المفاتيح الأجنبية بشكل نظيف يحقق شروط التطبيع (Normalization).

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· مفتاح تذكر الدرس 5-3 في 3 خطوات:
  · المشكلة: علاقة M:M تخفي بداخلها صفة (مثل Grade بين STUDENT و SUBJECT).
  · الحل: ننشئ كياناً ثالثاً (Third entity) يُسمى Intersection Entity (مثل ENROLLMENT).
  · النتيجة: تتحول العلاقة M:M إلى علاقتي 1:M نظيفتين.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 28):
   What is the name of the third entity created to resolve a Many-to-Many (M:M) relationship in an ER diagram?
   A) Recursive entity
   B) Intersection entity
   C) Flat file entity
   • الإجابة الصحيحة: B (الكيان الثالث الذي يحل علاقة M:M يُسمى كيان التقاطع Intersection entity).
2. True or False (صح أم خطأ — من مثال الدرجة في الصفحة 27):
   Statement: "In a Many-to-Many relationship between STUDENT and SUBJECT, the Grade attribute should be placed directly inside the STUDENT entity." (True / False)
   • الإجابة: False (خطأ) — وضع صفة Grade في STUDENT لن يحدد لأي مادة تعود الدرجة، ووضعها في SUBJECT لن يحدد أي طالب حصل عليها؛ بل يجب وضعها في كيان التقاطع (ENROLLMENT).

---

أخبريني عندما تنتهين من كتابة هذه الشرائح لننتقل مباشرة إلى الشرائح الأخيرة في شابتر 5 (الكيان الوسيط ENROLLMENT والعلاقات ذات الخطوط القاطعة Barred Relationships وأمثلة TV Shows و Cleaning Services في الصفحات 29 إلى 34)!

تم، سأدوّن الشرائح الست الأخيرة من درس 5-3 (Pages 29–34 — Intersection Entity, Barred Relationships, Examples, Terminology, & Summary) بنفس القالب المنظم تماماً:

---

الصفحات التاسعة والعشرين إلى الرابعة والثلاثين (Pages 29–34)

1. Chapter Name (اسم الفصل / الموضوع)

• Database Design: 5-3 Resolving Many-to-Many Relationships (تصميم قواعد البيانات: 5-3 حل علاقات متعدد إلى متعدد).

2. Slide Number (رقم الشريحة)

• Pages 29–34 (ترقيم أوراكل 8, 9, 10, 11, 12, 13 من درس 5-3: Intersection Entity, Barred Relationships, Examples, Terminology, & Summary).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

• Barred Relationships (العلاقات ذات الخطوط القاطعة): تُنطق (بارد ريليشنشيبس) — علاقات ترتبط بكيان التقاطع (Intersection Entity) ويُوضع على خطها خط عرضي صغير (Bar —|—) عند جهة Crow's foot للدلالة على أن المعرّف الفريد (UID) لهذا الكيان الوسيط هو معرّف مركب (Composite UID) مأخوذ من الكيانين الأصليين.

• Originating Entities / Relationships (الكيانات / العلاقات الأصلية): تُنطق (أوريجينيتينج إينتيتيز) — الكيانان الأساسيان اللذان كانا مرتبطين بعلاقة M:M قبل فكها (مثل STUDENT و SUBJECT).

• Composite UID (المعرّف الفريد المركب): تُنطق (كومبوزيت يو آي دي) — معرّف يتكون من دمج المعرّفات الفريدة القادمة من العلاقات الأصلية (مثل دمج STUDENT ID + SUBJECT ID معاً لتمييز كل سجل في ENROLLMENT).

• Viewing Record / Cleaning Schedule: أمثلة لكيانات تقاطع (Intersection Entities) تحل علاقات M:M بين (TV SHOW و PERSON) وبين (CLEANING COMPANY و CLEANING SERVICE).

4. Exact Text on Slide (النص المكتوب في الشرائح كما هو)

Intersection Entity (Page 29):

An intersection entity – ENROLLMENT – has been added, including the "Grade" attribute.

The original M:M relationship has become two 1:M relationships.

What would be the UID of the intersection entity?

Barred Relationships (Page 30):

The unique identifier (UID) of the intersection entity often comes from the originating relationships and is represented by the bars.

In this case, the relationships from the originating entities to the intersection entity are called "barred" relationships.

(ملاحظة الرسمة في الصفحة 30): UID is a combination (Composite UIDs) — يُرسم خط قاطع صغير (Bar) على خطي العلاقة المتجهين نحو ENROLLMENT عند طرفي Crow's foot.

M:M Resolution Examples (Pages 31 & 32):

TV Shows: TV SHOW (M:M) PERSON ➔ يُحل بإضافة كيان التقاطع VIEWING RECORD مع Barred Relationships من الطرفين.

Cleaning Services: CLEANING COMPANY (M:M) CLEANING SERVICE ➔ يُحل بإضافة كيان التقاطع CLEANING SCHEDULE مع Barred Relationships من الطرفين.

Terminology & Summary (Pages 33 & 34):

Key terms: Barred relationship, Intersection entity.

Summary: Identify attributes belonging to M:M relationships, demonstrate steps to resolve M:M using an intersection entity, and identify/represent the UID of an intersection entity on an ERD.

5. Explanation in Arabic (الشرح باللغة العربية وقواعد الرسم والاتجاهات)

تُكمل هذه الشرائح الصورة الهندسية الكاملة لحل علاقات M:M وتوضح كيف يتغير شكل الخطوط ونوع العلاقات (موضع أسئلة دقيقة جداً في الامتحانات):

• تحول نوع العلاقة (M:M ➔ Two 1:M):
عند وضع كيان التقاطع ENROLLMENT في المنتصف بين STUDENT و SUBJECT:

· تصبح العلاقة بين STUDENT و ENROLLMENT علاقة 1:M (الطالب الواحد يسجل في عدة مواد، وكل سجل تسجيل يخص طالباً واحداً).
· وتصبح العلاقة بين SUBJECT و ENROLLMENT علاقة 1:M (المادة الواحدة يسجل فيها عدة طلاب، وكل سجل تسجيل يخص مادة واحدة).

• انتبهي لاتجاه الإلزامية والاختيارية في الرسمة (مهم جداً):

· من الكيانات الأصلية (STUDENT / SUBJECT) إلى ENROLLMENT: الخط متقطع (Optional / May) مع Crow's foot (لأن الطالب قد يسجل في صفر أو أكثر من المواد).
· من ENROLLMENT إلى الكيانات الأصلية: الخط متصل (Mandatory / Must) مع Single toe (لأن أي سجل تسجيل يجب أن يعود لطالب واحد ومادة واحدة).

• ما هو الـ UID لكيان التقاطع؟ وكيف نرسمه؟ (Barred Relationships - الصفحة 30):

· غالباً لا نضع رقماً جديداً داخل ENROLLMENT، بل نأخذ معرّف الطالب (STUDENT ID) + معرّف المادة (SUBJECT ID) معاً كـ معرّف مركب (Composite UID).
· كيف نمثل ذلك على الرسمة؟ نضع خطاً قاطعاً صغيراً (Bar) يقطع خط العلاقة قبل دخوله في رِجل الغراب (Crow's foot) عند كيان التقاطع ENROLLMENT؛ وتُسمى هذه العلاقة بـ Barred relationship.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

• المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف الكيان الوسيط الذي يعتمد في تعريفه على خطوط قاطعة (Barred Relationships) باسم "الكيان الضعيف المعتمد في التعريف" (ID-Dependent Weak Entity)؛ فعند تحويل المخطط المنطقي إلى جداول فيزيائية في Oracle، يتحول كل خط قاطع (Bar) إلى عمود يلعب دورين معاً (Primary Key + Foreign Key أو ما رأيناه في شابتر 2 برمز PF)، مما يشكل مفتاحاً أساسياً مركباً (Composite Primary Key) يضمن عدم تسجيل نفس الطالب في نفس المادة مرتين!

• خدع سريعة للحفظ والتدوين (Memory Tricks):

· 4 حقائق ذهبية لحل M:M للامتحان:
  · علاقة M:M تتحول إلى علاقتي 1:M (Two 1:M relationships).
  · الكيان الثالث في المنتصف يُسمى Intersection Entity (مثل ENROLLMENT, VIEWING RECORD, CLEANING SCHEDULE).
  · رِجل الغراب (Crow's foot) تكون دائماً عند كيان التقاطع، والطرف المفرد (Single toe) عند الكيانات الأصلية.
  · الخط العرضي الصغير (Bar) على خط العلاقة يُسمى Barred relationship ويعني أن الـ UID هو Composite UID قادم من الكيانات الأصلية.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على هذه الشرائح)

1. Multiple Choice (سؤال مباشر من الصفحة 29):
   When a Many-to-Many (M:M) relationship is resolved using an intersection entity, what does the original M:M relationship become?
   A) One 1:1 relationship
   B) Two 1:M relationships
   C) Two M:M relationships
   • الإجابة الصحيحة: B (تتحول العلاقة الأصلية M:M إلى علاقتي واحد إلى متعدد two 1:M relationships).
2. Multiple Choice (سؤال تعريف Barred Relationships في الصفحة 30):
   What do the small bars drawn across the relationship lines entering an intersection entity (called "barred relationships") indicate?
   A) That the relationship is transferable.
   B) That the UID of the intersection entity is a composite UID derived from the originating relationships.
   C) That the intersection entity has no attributes or keys.
   • الإجابة الصحيحة: B (تشير الخطوط القاطعة Bars إلى أن المعرّف الفريد لكيان التقاطع هو معرّف مركب Composite UID قادم من العلاقات الأصلية).
3. Practical Resolution Question (سؤال تطبيقي متوقع — حل علاقة M:M):
   In a hospital database, a DOCTOR may treat one or more PATIENTs, and each PATIENT may be treated by one or more DOCTORs. We also need to record the treatment date and diagnosis. Explain how to resolve this M:M relationship.
   • الإجابة النموذجية:

· Create an intersection entity (e.g., APPOINTMENT or TREATMENT) and place the treatment date and diagnosis attributes inside it.
· Replace the single M:M relationship with two 1:M relationships connecting DOCTOR to TREATMENT and PATIENT to TREATMENT (with crow's feet at the TREATMENT end).
· Use barred relationships from DOCTOR and PATIENT to TREATMENT to indicate a composite UID derived from both originating entities.

---

ألف مبروك! أنهيتِ الآن تدوين شابتر 1 و 2 و 3 و 4 و 5 بالكامل في دفتركِ! هل تودين أن نختم الآن بـ امتحان تجريبي شامل (Comprehensive Final Mock Exam) يجمع أهم الأسئلة المتوقعة على الشباتر الخمسة بنمط اختبارات الكلية، أم لديكِ شابتر إضافي؟
