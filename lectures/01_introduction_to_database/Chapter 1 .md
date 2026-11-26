أهلاً بكِ! كما طلبتِ تماماً، قمتُ بإعادة تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للنسخ إلى دفتركِ أو ملف المذاكرة، دون إضافة أو حذف أي حرف من المحتوى الذي قدمتِه:

---

Chapter 1: Introduction to Database

1. Chapter Name (اسم الفصل / الموضوع)

· Introduction to Database (مقدمة في قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 1 (الشريحة الأولى: تعريف قاعدة البيانات، عدم التكرار، والمشاركة).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Database (قاعدة البيانات): تُنطق (داتابيس) — مجموعة مركزية ومنظمة من البيانات المخزنة إلكترونياً.
· Non-redundant data (بيانات غير مكررة): تُنطق (نان-ريداندانت داتا) — بيانات خالية من التكرار العشوائي في أكثر من ملف.
· Sharable (تشاركية / قابلة للمشاركة): تُنطق (شيرَبل) — إمكانية وصول واستخدام نفس البيانات من قِبل أكثر من نظام أو قسم في نفس الوقت.
· Application System (نظام تطبيقي): تُنطق (أبليكيشن سيستم) — البرنامج أو الواجهة التي يستخدمها الموظف للتعامل مع البيانات (مثل نظام القبول والتسجيل أو المالية).
· Redundant Data (بيانات مكررة): تُنطق (ريداندانت داتا) — تخزين نفس المعلومة في أكثر من ملف مستقل.
· Centralized (مركزية): تُنطق (سنترالايزد) — مصطلح أضافته المهندسة في الشرح، ويعني وجود قاعدة بيانات واحدة مرفوعة على السيرفر ترجع إليها جميع الأقسام.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Eng. Noor A. Nashwan
Engineering & Information Systems Dept, UCAS
Course Name: Introduction to Database
Lecture Subject: Introduction to Database.
Database Definition: "A database is a collection of non-redundant data sharable between different application system"
Redundant data: Storing same information in more than one file.
Sharing data: More than one application uses the same data.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المهندسة)

تُعرّف هذه الشريحة المفهوم الأساسي لقاعدة البيانات من خلال ميزتين تحلان مشاكل الملفات التقليدية، وقد ربطتهما المهندسة نور بمثال الكلية الجامعية (UCAS):

1. عدم التكرار (Non-redundant data): في الأنظمة القديمة، لو كان لكل قسم في الكلية (القبول والتسجيل، المالية، المكتبة) ملفاته المستقلة، ستُخزن بيانات الطالب في أكثر من ملف مما يسبب العشوائية وأخطاء التحديث. قاعدة البيانات تحفظ بيانات الطالب مرة واحدة فقط في قاعدة بيانات مركزية (Centralized) على السيرفر.
2. المشاركة (Sharable): نفس البيانات المخزنة في مكان واحد يمكن أن تخدم عدة تطبيقات وأقسام في نفس الوقت. فعندما يراجع الطالب قسم المالية، يفتح الموظف نظامه (Application) فيجد بيانات الطالب وتخصصه جاهزة ومشتركة دون الحاجة لإعادة إدخالها.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات في Stanford (CS145) و MIT (6.830)، يُعرف منع التكرار (Non-redundant) بتطبيق مبدأ "مصدر الحقيقة الواحد" (Single Source of Truth)؛ وذلك لمنع كارثة تضارب التحديث (Update Anomaly) التي تحدث إذا عُدِّلت معلومة الطالب في قسم ونُسيت في قسم آخر. أما مبدأ المشاركة (Sharable) فيعني فصل البيانات عن التطبيقات (Data Independence)، بحيث تصبح البيانات مورداً مركزياً مستقلاً تخدم عشرات التطبيقات بسلامة وأمان.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة التعريف: Collection (مجموعة) + Non-redundant (بلا تكرار) + Sharable (قابلة للمشاركة) = Database.
  · الفرق السحري للامتحان:
    · Redundant = تكرار في أكثر من ملف (More than one FILE).
    · Sharing = مشاركة بين أكثر من تطبيق (More than one APPLICATION).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
What is the key difference between "Redundant data" and "Sharing data?"

· A) Redundant data uses one file for many apps, while sharing data uses many files for one app.
· B) Redundant data stores the same information in more than one file, while sharing data allows more than one application to use the same data.
· C) Redundant data prevents errors, while sharing data causes duplication.
· الإجابة الصحيحة: B (التكرار مرتبط بتعدد الملفات files، والمشاركة مرتبطة بتعدد التطبيقات applications).

2. True or False (صح أم خطأ):
Statement: "A database is a collection of redundant data stored separately for each application system." (True / False)

· الإجابة: False (خطأ) — الصواب أنها بيانات غير مكررة (non-redundant) وقابلة للمشاركة (sharable) بين الأنظمة التطبيقية المختلفة.

3. Short Definition (سؤال مقالي قصير):
Define "Database" and distinguish between "Redundant data" and "Sharing data".

· الإجابة النموذجية: A database is a collection of non-redundant data sharable between different application systems. Redundant data means storing the same information in more than one file, whereas sharing data means more than one application uses the same data.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 1 في دفترك، أخبريني لننتقل مباشرة إلى Slide 2 (Database Foundations 1-3: Types of Database Models)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون جاهزاً للتدوين، بنفس الأناقة والترتيب، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 2 (الشريحة الثانية: شريحة العنوان والتمهيد للدرس 1-3).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Database Foundations (أساسيات قواعد البيانات): تُنطق (داتابيس فاونديشنز) — المبادئ والقواعد الهندسية الجوهرية التي يُبنى عليها علم قواعد البيانات.
· Database Models (نماذج قواعد البيانات): تُنطق (داتابيس موديلز) — الهياكل أو القوالب المنطقية المختلفة لتنظيم وترتيب البيانات داخل النظام (مثل النموذج العلائقي، الهرمي، الشبكي، إلخ).
· Oracle Academy (أكاديمية أوراكل): تُنطق (أوراكل أكاديمي) — المنصة التعليمية الرسمية لشركة Oracle والتي اعتمدت منها الدكتورة منهج ومحتوى الشرائح.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Database Foundations
1-3
Types of Database Models
ORACLE Academy
Copyright © 2019, Oracle and/or its affiliates. All rights reserved.

5. Explanation in Arabic (الشرح باللغة العربية)

تُعد هذه الشريحة صفحة الغلاف للدرس الثالث من الوحدة الأولى (1-3) في منهج Oracle Academy المعتمد في المساق:

· الانتقال المنطقي: بعد أن فهمنا في الشريحة الأولى ما هي قاعدة البيانات؟، ننتقل هنا للإجابة عن سؤال: كيف تُنظم البيانات وتُرتب هندسياً داخل قاعدة البيانات؟.
· الفكرة الأساسية: توجد عدة طرق أو قوالب منطقية (Database Models) لتخزين البيانات وربطها ببعضها البعض، وسنتعرف عليها في الشرائح القادمة لنفهم لماذا تفوّق النموذج العلائقي (Relational Model) على غيره.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات في Stanford (CS145) و MIT (6.830)، يُعرف نموذج البيانات (Data Model) بأنه الإطار الرياضي والهندسي الذي يحدد ثلاثة أشياء لأي قاعدة بيانات:
  1. الهيكل (Structure): كيف تُرتب البيانات (جداول؟ شجرة؟ شبكة؟ كائنات؟).
  2. القيود (Constraints): ما الشروط التي تحكم صحة البيانات.
  3. العمليات (Operations): كيف نستعلم ونعدل ونحذف البيانات.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · الرقم 1-3: يشير إلى الوحدة الأولى، الدرس الثالث من منهج Oracle Academy.
  · اربطي Model بـ "التصميم الهندسي": كما تختلف تصاميم المباني (برج، فيلا، مجمع)، تختلف نماذج تخزين البيانات.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
What does a "Database Model" define in database foundations?

· A) The brand of the computer monitor used by the administrator.
· B) The logical structure and way data is organized, stored, and manipulated in a database.
· C) A backup copy of a printed spreadsheet.
· الإجابة الصحيحة: B (نموذج قاعدة البيانات يحدد البنية المنطقية والطريقة التي تُنظم وتُرتب بها البيانات).

2. True or False (صح أم خطأ):
Statement: "There is only one single database model used to organize data across all computing history." (True / False)

· الإجابة: False (خطأ) — توجد عدة نماذج لقواعد البيانات (Types of Database Models) تطورت عبر الزمن لتلبية احتياجات مختلفة.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 2، أخبريني لننتقل مباشرة إلى Slide 3 (Objectives: أهداف الدرس وأنواع النماذج الخمسة)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 3 (الشريحة الثالثة: أهداف الدرس واستعراض النماذج الخمسة).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Objectives (الأهداف): تُنطق (أوبجيكتيفز) — المخرجات التعليمية التي يغطيها الدرس.
· Database Development Process (عملية تطوير قاعدة البيانات): تُنطق (داتابيس ديفيلوبمنت بروسيس) — المراحل المتسلسلة لبناء قاعدة البيانات من المتطلبات وحتى التنفيذ الفعلي.
· Flat File Model (نموذج الملف المسطح): تُنطق (فلات فايل موديل) — تخزين جميع البيانات في جدول واحد أو ملف نصي واحد.
· Hierarchical Model (النموذج الهرمي): تُنطق (هايراركال موديل) — تنظيم البيانات على شكل شجرة متفرعة من الأعلى للأسفل.
· Network Model (النموذج الشبكي): تُنطق (نتوورك موديل) — تنظيم البيانات على شكل سجلات مترابطة فيما بينها بروابط متعددة (شبكة).
· Object-Oriented Model (النموذج كائني التوجه): تُنطق (أوبجيكت-أورينتد موديل) — تمثيل البيانات كـ "كائنات" (Objects) تحتوي على صفات وعمليات برمجية.
· Relational Model (النموذج العلائقي): تُنطق (ريليشنال موديل) — تنظيم البيانات في مجموعة من الجداول المترابطة بعلاقات، وهو النموذج الأشهر والأكثر استخداماً.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Objectives
This lesson covers the following objectives:

· Describe the database development process
· Explain the common types of database models:
  · Flat file model
  · Hierarchical model
  · Network model
  · Object-oriented model
  · Relational model

5. Explanation in Arabic (الشرح باللغة العربية مع تركيز المحاضر)

تحدد هذه الشريحة أهداف الدرس في نقطتين رئيسيتين:

1. وصف عملية تطوير قاعدة البيانات (Database Development Process): كيف ننتقل من مجرد متطلبات العمل إلى قاعدة بيانات مبنية فعلياً على الحاسوب.
2. شرح الأنواع الشائعة لنماذج قواعد البيانات (5 نماذج): استعراض الطرق الخمس المختلفة لترتيب البيانات.
   · ملاحظة مهمة ركز عليها المحاضر في التفريغ: سنمر على الأنواع الأربعة الأولى (Flat file, Hierarchical, Network, Object-oriented) بشكل سريع لأخذ فكرة عامة عنها، بينما سنركز بشكل مكثف ومفصل طوال الفصل الدراسي على النوع الخامس والأخير وهو النموذج العلائقي (Relational Model)؛ لأنه الأكثر شيوعاً واستخداماً في المؤسسات والبنوك والجامعات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات في Stanford (CS145) و MIT (6.830)، تُعرض هذه النماذج الخمسة كـ "رحلة تطور هندسة البيانات"؛ بدءاً من الملفات المسطحة البسيطة (Flat File)، مروراً بالنماذج الملاحية القديمة (Hierarchical & Network)، وصولاً إلى ثورة العالم Edgar Codd (1970) في النموذج العلائقي (Relational Model) الذي فصل بين التخزين الفيزيائي والعرض المنطقي في جداول، ثم النموذج كائني التوجه (Object-Oriented) لدمج قواعد البيانات مع لغات البرمجة الحديثة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · العدد السحري (5 نماذج): احفظيها بالترتيب التطوري: 1. ورقة واحدة (Flat) ➔ 2. شجرة (Hierarchical) ➔ 3. شبكة (Network) ➔ 4. كائنات برمجية (Object-Oriented) ➔ 5. جداول مترابطة (Relational — بطل المساق).
  · كلمة الاختصار (F-H-N-O-R): (Flat, Hierarchical, Network, Object-oriented, Relational).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
Which database model is the most commonly used in organizations and is the main focus of this course?

· A) Flat file model
· B) Hierarchical model
· C) Relational model
· D) Network model
· الإجابة الصحيحة: C (أكد المحاضر أن الـ Relational model هو الأكثر شيوعاً واستخداماً في المؤسسات وهو محور المساق).

2. Multiple Choice (استبعاد الخيار الخاطئ):
All of the following are common types of database models covered in this lesson EXCEPT:

· A) Flat file model
· B) Hierarchical model
· C) Sequential tape model
· D) Object-oriented model
· الإجابة الصحيحة: C (النماذج الخمسة هي: Flat file, Hierarchical, Network, Object-oriented, Relational).

3. Short Question (سؤال مقالي قصير):
List the five common types of database models mentioned in the lesson objectives.

· الإجابة النموذجية: 1. Flat file model, 2. Hierarchical model, 3. Network model, 4. Object-oriented model, 5. Relational model.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 3، أخبريني لننتقل مباشرة إلى Slide 4 (Database Development Process: مراحل بناء وتطوير قاعدة البيانات)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 4 (الشريحة الرابعة: عملية تطوير قاعدة البيانات / Database Development Process).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Business Information Requirements (متطلبات معلومات العمل): تُنطق (بزنس إنفورميشن ريكوايرمنتس) — الاحتياجات والقوانين والقيود التي يطلبها صاحب العمل أو المؤسسة قبل البدء بالتصميم.
· Strategy and Analysis (الاستراتيجية والتحليل): تُنطق (ستراتيجي آند أناليسيز) — المرحلة الأولى التي يتم فيها تحليل المتطلبات وفهم مفاهيم البيانات.
· Conceptual Data Modeling (نمذجة البيانات المفاهيمية): تُنطق (كونسبتشوال داتا موديلينج) — رسم خريطة مفاهيمية توضح الكيانات والعلاقات بينها (مثل مخطط ER Diagram).
· Database Design (تصميم قاعدة البيانات): تُنطق (داتابيس ديزاين) — تحويل الخريطة المفاهيمية إلى مخطط تفصيلي للجداول والأعمدة والمفاتيح.
· Database Build (بناء قاعدة البيانات): تُنطق (داتابيس بيلد) — مرحلة التنفيذ الفعلي وكتابة أوامر البرمجة (SQL) لإنشاء قاعدة البيانات على الحاسوب.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Database Development Process
Business Information Requirements (نقطة البداية في الأعلى)

· Strategy and Analysis ➔ Conceptual Data Modeling
· Design ➔ Database Design
· Build ➔ Database Build

⬇

Database (النتيجة النهائية في الأسفل)

5. Explanation in Arabic (الشرح باللغة العربية مع تشبيه المحاضر)

تشرح هذه الشريحة الخطوات الهندسية المتسلسلة لبناء أي قاعدة بيانات، وقد شبّهها المحاضر في التفريغ بعملية بناء عمارة سكنية:

1. جمع المتطلبات (Business Information Requirements): قبل البدء بأي شيء، نجلس مع صاحب العمل ونسأله: "ما هو المطلوب؟" (مثل: نريد نظام مكتبة يسمح للطالب باستعارة كتاب لمدة أسبوع فقط).
2. الاستراتيجية والتحليل (Strategy and Analysis ➔ Conceptual Data Modeling): يرسم المهندس خريطة مبدئية على الورق (تُسمى ER Diagram). التعديل هنا بقلم الرصاص سهل وتكلفته صفرية، عكس التعديل بعد البناء الفعلي.
3. التصميم (Design ➔ Database Design): تحويل الخريطة المبدئية إلى مخطط هندسي تفصيلي يحدد الجداول والأعمدة والمفاتيح والعلاقات.
4. البناء (Build ➔ Database Build): التنفيذ الفعلي وكتابة أوامر البرمجة لبناء قاعدة البيانات الحقيقية بناءً على الخريطة المعتمدة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة البرمجيات وقواعد البيانات في Stanford (CS145) و MIT (6.830)، يُعرف هذا التسلسل بقاعدة "التكلفة الأسّية للأخطاء" (The 1-10-100 Rule)؛ فاكتشاف خطأ في مرحلة Analysis & Conceptual Modeling يكلف 1$ لإصلاحه على الورق، بينما اكتشافه في مرحلة Design يكلف 10$، أما اكتشافه بعد Build وتشغيل النظام فيكلف 100$ أو أكثر لإعادة هيكلة البيانات.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · اربطي كل مرحلة على اليسار بالمربع المقابل لها على اليمين:
    · Strategy and Analysis ➔ Conceptual Data Modeling (تذكر أن Analysis تقابل Conceptual).
    · Design ➔ Database Design (نفس الكلمة).
    · Build ➔ Database Build (نفس الكلمة).
  · قصة العمارة (4 خطوات): 1. كلام صاحب الأرض (Requirements) ➔ 2. رسم الخريطة بقلم رصاص (Conceptual) ➔ 3. المخطط التفصيلي (Design) ➔ 4. البناء الفعلي (Build).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (الترتيب الصحيح للمراحل):
What is the correct sequence of phases in the Database Development Process after gathering Business Information Requirements?

· A) Database Build ➔ Database Design ➔ Conceptual Data Modeling
· B) Conceptual Data Modeling ➔ Database Design ➔ Database Build
· C) Database Design ➔ Conceptual Data Modeling ➔ Database Build
· الإجابة الصحيحة: B (الترتيب من الأعلى للأسفل في الشريحة: النمذجة المفاهيمية، ثم التصميم، ثم البناء).

2. Multiple Choice (ربط المرحلة بالمخرج):
Which activity corresponds to the "Strategy and Analysis" phase in the Database Development Process?

· A) Database Build
· B) Database Design
· C) Conceptual Data Modeling
· الإجابة الصحيحة: C (مرحلة الاستراتيجية والتحليل يقابلها مربع Conceptual Data Modeling).

3. Short Question (سؤال مقالي قصير):
Why is it important to start with "Conceptual Data Modeling" before moving to the "Database Build" phase?

· الإجابة النموذجية: Conceptual Data Modeling acts like an architect's blueprint; it allows designers and clients to visualize requirements and fix errors easily on paper before spending time and cost building the actual database.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 4، أخبريني لننتقل مباشرة إلى Slide 5 (Case Scenario: Types of Database Models)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 5 (الشريحة الخامسة: سيناريو بصري لأنواع نماذج قواعد البيانات / Case Scenario: Types of Database Models).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Case Scenario (سيناريو الحالة): تُنطق (كيس سيناريو) — مثال تطبيقي أو وضع افتراضي يعرض مشكلة أو فكرة ليفكر فيها الطالب أو مصمم النظام.
· Visual Representation (التمثيل البصري): تُنطق (فيجوال ريبريزنتيشن) — الأيقونات أو الرسومات التي تعبر عن البنية المنطقية لكل نموذج قاعدة بيانات (مثل الورقة للملف المسطح، أو الشجرة للنموذج الهرمي).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Types of Database Models

(سحابة تفكير لشخص جالس أمام الحاسوب بداخلها أسماء النماذج الخمسة وعلامات استفهام ?? وأيقونات بصرية غير مرتبة):

· Relational Model
· Object-Oriented Model
· Flat File Model
· Hierarchical Model
· Network Model

5. Explanation in Arabic (الشرح باللغة العربية)

تُعد هذه الشريحة محطة تفكير وعصف ذهني (Case Scenario) قبل الدخول في شرح كل نموذج بالتفصيل، وتوضح النقاط التالية:

1. الهدف من الرسمة: تُظهر الشريحة مستخدماً أمام حاسوبه يفكر في كيفية تنظيم بياناته وتظهر في مخيلته الأشكال الهندسية الخمسة المتاحة:
   · ورقة نصية واحدة: تعبر عن Flat File Model.
   · شجرة متفرعة من الأعلى للأسفل: تعبر عن Hierarchical Model.
   · عقد مترابطة ببعضها في كل الاتجاهات: تعبر عن Network Model.
   · كائنات برمجية متصلة: تعبر عن Object-Oriented Model.
   · مجموعة جداول مترابطة: تعبر عن Relational Model.
2. تنبيه بصري مهم في الشريحة: لاحظي أن الأيقونات في هذه الشريحة موضوعة بشكل عشوائي وغير مطابقة لاسم النموذج المكتوب بجانبها مباشرة؛ لأن هذه شريحة تفاعلية تطلب من الطالب التفكير (??) ومطابقة كل أيقونة بالاسم الصحيح للنموذج.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات علوم الحاسوب بجامعتي MIT (6.830) و Stanford (CS145)، يُعرف هذا التمرين بـ "اختيار البنية الملائمة للمشكلة" (Choosing the Right Abstraction)؛ فالمصمم المحترف يسأل نفسه: ما طبيعة بياناتي؟ إذا كانت قائمة بسيطة فـ Flat File، وإذا كانت تفرعاً شجرياً فـ Hierarchical، وإذا كانت معاملات مالية وأكاديمية متشابكة تتطلب دقة واستعلامات سريعة فالحل هو Relational Model.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قاعدة المطابقة الصحيحة للأيقونات (لتجنب فخ الشريحة):
    · صورة الورقة المكتوبة ➔ Flat File Model.
    · صورة العقدة المتفرعة للأسفل (شجرة) ➔ Hierarchical Model.
    · صورة الدوائر المتصلة كمثلث/شبكة ➔ Network Model.
    · صورة الجدول ذي الصفوف والأعمدة الملونة ➔ Relational Model.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (مطابقة الشكل بالنموذج):
Which visual structure best represents the "Hierarchical Model" of databases?

· A) A single plain-text sheet containing all records in one table.
· B) A tree-like structure branching down from a parent node to child nodes.
· C) A grid composed of rows and columns (tables).
· الإجابة الصحيحة: B (النموذج الهرمي Hierarchical Model يُمثل على شكل شجرة Tree-like structure).

2. Multiple Choice (مطابقة الجداول بالنموذج):
In database visualization, a grid composed of rows and columns (tables) represents which database model?

· A) Network Model
· B) Hierarchical Model
· C) Relational Model
· الإجابة الصحيحة: C (الجدول المكون من صفوف وأعمدة يمثل النموذج العلائقي Relational Model).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 5، أخبريني لننتقل مباشرة إلى Slide 6 (Flat File Model: شرح نموذج الملف المسطح بالتفصيل)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 6 (الشريحة السادسة: نموذج الملف المسطح / Flat File Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Single Table (جدول واحد): تُنطق (سينجل تيبل) — وضع جميع البيانات في جدول واحد ضخم دون تقسيمها لعدة جداول.
· Plain-text form (صيغة نصية بسيطة/مجردة): تُنطق (بلاين-تيكست فورم) — ملفات نصية عادية خالية من التنسيقات المعقدة (مثل ملفات المفكرة أو CSV).
· Record (سجل): تُنطق (ريكورد) — سطر واحد في الملف يمثل مجموعة بيانات تخص عنصراً واحداً (مثل بيانات طالب واحد).
· Fields (حقول): تُنطق (فيلدز) — الأعمدة أو الخانات الفردية داخل السجل الواحد (مثل حقل الاسم، حقل الرقم).
· Delimiters (فواصل): تُنطق (ديليميترز) — رموز خاصة تُستخدم للفصل بين حقل وآخر في نفس السطر، مثل الفاصلة (,) أو المسافة الجدولية (Tab).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Flat File Model

· A flat file database is a database designed around a single table
· Flat file databases are generally in plain-text form, where each line holds only one record.
· The fields in the record are separated with delimiters, such as tabs and commas.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تشرح هذه الشريحة أبسط وأقدم نموذج لقواعد البيانات وهو نموذج الملف المسطح (Flat File Model):

· جدول واحد فقط (Single Table): تُحفظ جميع البيانات في مكان واحد أو جدول واحد فقط (مثل وضع بيانات الطلاب والمساقات والمدرسين كلها في جدول واحد ضخم).
· صيغة نصية وسطر لكل سجل (Plain-text & One record per line): يُخزن الملف عادةً كملف نصي بسيط، بحيث يمثل كل سطر (Line) سجلاً واحداً كاملاً (Record).
· الفواصل (Delimiters): بما أنه ملف نصي ولا توجد خطوط جدول مرسومة، يضع النظام رموزاً فاصلة (Delimiters) بين الحقول، مثل الفاصلة العادية (Commas) أو المسافة الطويلة (Tabs).

تشبيه المحاضر (درج المكتب الواحد): شبّه المحاضر هذا النموذج بموظف لديه درج واحد فقط يرمي فيه كل أوراق الشركة معاً بدون تقسيم؛ فعندما تطلب منه استخراج ملف معين، يقضي وقتاً طويلاً جداً في البحث، وكذلك الحال لو وضعتِ كل بياناتكِ في ملف Word أو Excel واحد.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات علوم الحاسوب بجامعتي Harvard (CS50) و Stanford (CS145)، يُدرَّس نموذج Flat File (المتمثل عملياً في ملفات CSV) لفهم مشكلة التعقيد الزمني للبحث (O(N) Linear Scan)؛ لأن الملف النصي المسطح لا يحتوي على فهارس ذكية، فيضطر المعالج لقراءة الملف سطراً بسطر من البداية للنهاية للعثور على معلومة واحدة، كما يفتقر للقيود التي تمنع الأخطاء.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة Flat File في 3 كلمات: 1 Table (جدول واحد) + Plain-text (نص بسيط) + Delimiters (فواصل مثل Tabs & Commas).
  · اربطي كلمة Flat (مسطح) بـ "ورقة مسطحة واحدة": كل سطر يمثل سجلاً واحداً (One record)، وتفصل بين حقوله فاصلة (Comma) أو مسافة جدولية (Tab).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
How are individual fields separated within a record in a Flat File database model?

· A) By creating primary and foreign keys across multiple tables.
· B) Using delimiters such as tabs and commas.
· C) Through tree-like parent-child links.
· الإجابة الصحيحة: B (تُفصل الحقول في النموذج المسطح باستخدام فواصل Delimiters مثل الـ Tabs والـ Commas).

2. True or False (صح أم خطأ):
Statement: "In a Flat File model, data is distributed across multiple linked tables, and each line holds multiple records." (True / False)

· الإجابة: False (خطأ) — النموذج المسطح يُصمم حول جدول واحد فقط (Single table)، وكل سطر يحمل سجلاً واحداً فقط (Only one record).

3. Short Essay (سؤال مقالي قصير):
Define the "Flat File Model" and mention one major disadvantage of using it for large organizations.

· الإجابة النموذجية: A flat file database is designed around a single table in plain-text form, where each line holds one record and fields are separated by delimiters (such as tabs and commas). One major disadvantage is that searching, updating, and querying specific data becomes slow and difficult, and it causes data redundancy.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 6، أخبريني لننتقل مباشرة إلى Slide 7 (Example of a Flat File Model: مثال عملي على نموذج الملف المسطح ومشكلة التكرار)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل الجدول المبعثر في النص الأصلي إلى جدول Markdown احترافي لسهولة القراءة):

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 7 (الشريحة السابعة: مثال عملي على نموذج الملف المسطح / Example of a Flat File Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Repetition of data values (تكرار قيم البيانات): تُنطق (ريبيتيشن أوف داتا فاليوز) — إعادة كتابة نفس المعلومة في عدة صفوف داخل الجدول الواحد (وهو مرادف لمفهوم الـ Redundancy).
· Record 1, 2, 3, 4 (السجلات): تُنطق (ريكورد) — الصفوف الأفقية في الجدول، حيث يمثل كل صف كتاباً ومؤلفه.
· AUTHOR_ID (معرّف المؤلف): تُنطق (أوثور آي دي) — العمود الخاص بالرقم التعريفي الفريد للمؤلف (مثل AD0001).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Example of a Flat File Model

Books as well as Authors are stored in this single table, causing repetition of data values.

 AUTHOR_ID AUTHOR_NAME TITLE
Record 1 AD0001 Oscar Wilde A Vision
Record 2 AD0002 Leo Tolstoy War and Peace
Record 3 AD0003 Oliver Goldsmith Citizen of the World
Record 4 AD0003 Oliver Goldsmith The Deserted Village

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل الجدول)

تُعطي هذه الشريحة دليلاً عملياً على العيب الأساسي في نموذج الملف المسطح (Flat File Model) من خلال مثال مكتبة تحتوي على كتب ومؤلفين:

· دمج كيانين في جدول واحد: تم وضع بيانات الكتب (TITLE) مع بيانات المؤلفين (AUTHOR_ID, AUTHOR_NAME) في جدول واحد فقط.
· حدوث التكرار (Repetition of data values): انظري إلى Record 3 و Record 4 في الجدول؛ لأن المؤلف Oliver Goldsmith ألّف كتابين مختلفين (Citizen of the World و The Deserted Village)، اضطر النظام لتكرار رقمه (AD0003) واسمه (Oliver Goldsmith) مرتين. ولو ألّف 50 كتاباً، سيتكرر اسمه ورقمه 50 مرة.
· أثر التكرار عند التعديل: كما أوضح المحاضر، وضع كل البيانات في جدول واحد يجعل التعديل صعباً؛ فلو أردنا تعديل اسم المؤلف أو رقمه، سنضطر لتعديله في جميع الصفوف المكررة يدوياً، وإلا سيحدث تضارب في البيانات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُستخدم هذا المثال لشرح "الشذوذ البياني" (Data Anomalies) الناتج عن عدم فصل الجداول:
  · شذوذ التحديث (Update Anomaly): تعديل اسم المؤلف AD0003 في سطر ونسيانه في الآخر يسبب تضارب المعلومات.
  · شذوذ الإدخال (Insertion Anomaly): لا يمكنكِ إضافة مؤلف جديد للجدول ما لم يكن لديه كتاب مسجل بالفعل.
  · شذوذ الحذف (Deletion Anomaly): حذف كتاب Record 1 يحذف معه بيانات المؤلف Oscar Wilde نهائياً من النظام! والحل هو فصل الجدول إلى جدولين (للمؤلفين وللكتب).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · انظري إلى السطرين الأخيرين (Record 3 & Record 4): هما الدليل العملي لعبارة "Repetition of data values" بتكرار اسم Oliver Goldsmith ورقمه AD0003.
  · معادلة المشكلة: Books + Authors in 1 Table ➔ Repetition of data values.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
In the provided Flat File Model example, what problem occurs when both Books and Authors are stored in a single table?

· A) Inability to store more than three records.
· B) Repetition of data values (such as author ID and name).
· C) Automatic deletion of duplicate author names.
· الإجابة الصحيحة: B (تخزين الكتب والمؤلفين في جدول واحد يسبب تكرار قيم البيانات Repetition of data values).

2. True or False (صح أم خطأ):
Statement: "In a Flat File database, storing books and authors together in a single table prevents data repetition." (True / False)

· الإجابة: False (خطأ) — بل يسبب تكراراً لقيم البيانات (Repetition of data values) كما ظهر في تكرار بيانات المؤلف Oliver Goldsmith.

3. Short Scenario Question (سؤال تحليلي قصير):
Look at Record 3 and Record 4 in the Flat File example table (AD0003 | Oliver Goldsmith). Why is this considered a poor database design, and how can it be solved?

· الإجابة النموذجية: It is a poor design because storing books and authors in a single table causes repetition of data values, which wastes storage and makes updating difficult. It can be solved by splitting the single table into two separate linked tables: one for Authors and another for Books.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 7، أخبريني لننتقل مباشرة إلى Slide 8 (Hierarchical Model: شرح النموذج الهرمي)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 8 (الشريحة الثامنة: النموذج الهرمي / Hierarchical Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Hierarchical Model (النموذج الهرمي): تُنطق (هايراركال موديل) — نموذج قاعدة بيانات يرتب البيانات في مستويات متدرجة من الأعلى للأسفل.
· Tree-like structure (هيكل يشبه الشجرة): تُنطق (تري-لايك ستركتشر) — بنية تنظيمية تبدأ من جذر واحد في الأعلى وتتفرع منه فروع وأغصان نحو الأسفل.
· Links (روابط / وصلات): تُنطق (لينكس) — المؤشرات أو الخطوط التي تربط السجلات ببعضها البعض (تربط الأب بالأبناء).
· Corresponds to (يقابل / يوازي): تُنطق (كوريسبوندز تو) — مصطلح للمقارنة يوضح ما يعادل هذا المفهوم في النماذج الأخرى.
· Row (صف): تُنطق (رو) — السطر الأفقي في جدول قاعدة البيانات العلائقية.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Hierarchical Model

· In a hierarchical database model, the data is organized in a tree-like structure.
· The data is stored as records that are connected to one another through links.
· A record is a collection of fields.
· A record in the hierarchical database model corresponds to a row in the relational database model.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

توضح هذه الشريحة النوع الثاني من نماذج قواعد البيانات وهو النموذج الهرمي (Hierarchical Model):

· البنية الشجرية (Tree-like structure): تُرتب البيانات في هذا النموذج على شكل شجرة مقلوبة (تبدأ من الأعلى وتتفرع للأسفل)، تماماً مثل شجرة المجلدات في نظام الويندوز التي شرحها المحاضر (مجلد رئيسي باسم الكلية UCAS ➔ يتفرع منه مجلدات سنة أولى، سنة ثانية ➔ ويتفرع من كل سنة فصل أول، فصل ثاني ➔ وهكذا).
· التخزين والروابط (Records & Links): تُخزن البيانات كسجلات (Records)، ويرتبط كل سجل بالآخر عن طريق روابط (Links) تحدد علاقة الأب بالابن.
· مكونات السجل ومقارنته بالعلائقي:
  · السجل الواحد (Record) يتكون من مجموعة من الحقول (Collection of fields).
  · السجل (Record) في النموذج الهرمي يعادل تماماً الصف (Row) في النموذج العلائقي (Relational Model).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات أنظمة قواعد البيانات في MIT (6.830) و Stanford (CS145)، يُدرَّس النموذج الهرمي (الذي مثّله تاريخياً نظام IBM IMS في الستينيات) لفهم قيد "علاقة الواحد إلى متعدد الصارمة" (Strict 1:N Parent-Child Relationship)؛ فكل ابن (Child) له أب واحد فقط (Single Parent)، بينما يمكن للأب الواحد أن يكون له عدة أبناء. هذا النموذج سريع جداً عند البحث من الأعلى للأسفل، لكنه يفشل أو يضطر لتكرار البيانات إذا كان للابن أكثر من أب (مثل الطالب الذي يدرس عدة مساقات).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة النموذج الهرمي في 3 كلمات: Tree-like (شكل شجرة) + Records & Links (سجلات وروابط) + Record = Row (السجل يساوي الصف).
  · مقارنة ذهبية للامتحان:
    · في الهرمي اسمه: Record (سجل) ➔ ويتكون من Fields (حقول).
    · في العلائقي اسمه: Row (صف) ➔ ويتكون من Columns (أعمدة).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
How is data organized in a Hierarchical database model?

· A) As a single plain-text table separated by commas.
· B) In a tree-like structure where records are connected through links.
· C) As independent objects containing methods and attributes.
· الإجابة الصحيحة: B (البيانات في النموذج الهرمي تُنظم في هيكل يشبه الشجرة Tree-like structure وتُخزن كسجلات متصلة عبر روابط Links).

2. Multiple Choice / Fill in the Blank (سؤال مقارنة المصطلحات):
A "record" in the hierarchical database model corresponds to a __________ in the relational database model.

· A) Table
· B) Column
· C) Row
· الإجابة الصحيحة: C (الـ Record في النموذج الهرمي يقابل الـ Row في النموذج العلائقي).

3. True or False (صح أم خطأ):
Statement: "In a hierarchical database model, a record is defined as a collection of tables." (True / False)

· الإجابة: False (خطأ) — السجل (Record) هو مجموعة من الحقول (A collection of fields) وليس الجداول.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 8، أخبريني لننتقل مباشرة إلى Slide 9 (Example of a Hierarchical Model: مثال عملي على النموذج الهرمي)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 9 (الشريحة التاسعة: مثال عملي على النموذج الهرمي / Example of a Hierarchical Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Members (الأعضاء): تُنطق (ميمبرز) — العقدة الجذرية (الأب الأعلى / Root) التي تمثل جميع المنتمين للمؤسسة أو الجامعة.
· Faculty (أعضاء هيئة التدريس): تُنطق (فاكالتي) — الأساتذة والمحاضرون في الكلية أو الجامعة.
· Corporate (الشركات / المؤسسات): تُنطق (كوربوريت) — الأعضاء المنتسبون من قطاع الشركات أو المؤسسات الخارجية.
· Full Time (دوام كامل): تُنطق (فول تايم) — الموظفون أو المحاضرون المتفرغون للعمل بدوام كامل.
· Part Time (دوام جزئي): تُنطق (بارت تايم) — الموظفون أو المحاضرون العاملون بنظام الساعات أو الدوام الجزئي.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Example of a Hierarchical Model

Data is organized in a tree-like structure and stored as records that are connected to one another through links.

(الهيكل الشجري المرسوم في الشريحة):

· المستوى الأول (الجذر - Root): Members
· المستوى الثاني (أبناء Members): Student | Faculty | Corporate
· المستوى الثالث (أبناء Faculty): Full Time | Part Time

5. Explanation in Arabic (الشرح باللغة العربية مع مثال المحاضر)

تقدم هذه الشريحة مثالاً بصرياً يوضح كيفية عمل النموذج الهرمي في مؤسسة تعليمية (مثل الكلية الجامعية UCAS التي ضرب بها المحاضر المثل):

· قمة الشجرة (الأب العام - Members): في الأعلى يوجد التصنيف العام لجميع الأعضاء المنتسبين للمؤسسة (Members).
· التفرع الأول (Links): تتفرع من الأعضاء روابط (Links) تقسمهم إلى ثلاث فئات رئيسية: الطلاب (Student)، أعضاء هيئة التدريس (Faculty)، والشركات/المؤسسات (Corporate).
· التفرع الثاني: تتفرع من فئة هيئة التدريس (Faculty) روابط أخرى تقسمهم إلى نوعين: محاضرين بدوام كامل (Full Time) ومحاضرين بدوام جزئي (Part Time).
· ملاحظة جوهرية في الرسمة: انظري إلى اتجاه الأسهم؛ كل سهم ينطلق من عنصر علوي (Parent) إلى عنصر سفلي (Child)، ولا يوجد أي سهم يربط بين Student و Faculty مباشرة، أو يجعل Full Time تابعاً لـ Members مباشرة دون المرور بـ Faculty.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هياكل البيانات وقواعد البيانات بجامعتي MIT (6.830) و Stanford (CS145)، يُحلل هذا الرسم باستخدام مصطلحات نظرية الرسوم البيانية (Graph Theory - Trees)؛ حيث تُسمى العقدة Members بالجذر (Root)، وتُسمى Faculty بالأب (Parent) لـ Full Time و Part Time وفي نفس الوقت هي ابن (Child) لـ Members، بينما تُسمى العقد النهائية بالأوراق (Leaves). وتُعد نقطة الضعف هنا هي "التنقل الإجباري" (Navigational Access)؛ فللوصول إلى سجل محاضر Part Time يجب المرور حتماً من الأعلى للأسفل (Members ➔ Faculty ➔ Part Time).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري هرم الجامعة (3 مستويات):
    · المستوى 1 (الكل): Members (الأعضاء).
    · المستوى 2 (التصنيف): Student (طالب) — Faculty (مدرس) — Corporate (شركة).
    · المستوى 3 (تفصيل المدرس): Full Time (دوام كامل) — Part Time (دوام جزئي).
  · قاعدة الأسهم: الأسهم دائماً نازلة من الأعلى للأسفل (من أب واحد إلى عدة أبناء).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (تحليل الهيكل في الشريحة):
Based on the Hierarchical Model example in the lecture, which record is the direct parent of "Full Time" and "Part Time"?

· A) Members
· B) Student
· C) Faculty
· D) Corporate
· الإجابة الصحيحة: C (في الرسم التوضيحي تتفرع عقدتا Full Time و Part Time مباشرة من عقدة Faculty).

2. True or False (صح أم خطأ):
Statement: "In a hierarchical database model, a child record can have multiple parent records connected to it." (True / False)

· الإجابة: False (خطأ) — في الهيكل الشجري للنموذج الهرمي (Tree-like structure)، كل سجل ابن (Child) يرتبط بسجل أب واحد فقط (Single parent) فوقه.

3. Fill in the Blanks (سؤال إكمال قصير):
In the Hierarchical Model, data is stored as __________ that are connected to one another through __________.

· الإجابة النموذجية: Data is stored as records that are connected to one another through links.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 9، أخبريني لننتقل مباشرة إلى Slide 10 (Object-Oriented Model: شرح النموذج كائني التوجه)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 10 (الشريحة العاشرة: النموذج كائني التوجه / Object-Oriented Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Object (كائن): تُنطق (أوبجيكت) — وحدة برمجية تمثل كياناً من الواقع (مثل طالب أو موظف) وتجمع بياناته وعملياته معاً.
· State (الحالة): تُنطق (ستيت) — مجموعة القيم الحالية لصفات الكائن (Attributes) في لحظة معينة (مثل: الاسم = أحمد، الرقم = 101).
· Behavior (السلوك): تُنطق (بيهيفير) — مجموعة الدوال أو العمليات (Methods) التي تعمل على بيانات الكائن وتغير حالته (مثل: تعديل الاسم، إضافة مساق).
· Attributes (الصفات / الخصائص): تُنطق (أتريبيوتس) — المتغيرات التي تصف الكائن (مثل الاسم، العنوان، الإيميل).
· Methods (الدوال / العمليات): تُنطق (ميثودز) — الإجراءات البرمجية المرتبطة بالكائن (مثل Getters & Setters).
· Sharing of access (مشاركة الوصول): تُنطق (شيرينج أوف أكسيس) — الطريقة التي تتواصل وترتبط بها الكائنات مع بعضها البعض.
· Instance (نسخة / مثيل): تُنطق (إنستانس) — كائن فعلي تم إنشاؤه من قالب أو فئة (Class) معينة.
· Subclass & Superclass (الفئة الفرعية والفئة الأساسية): تُنطق (ساب كلاس و سوبر كلاس) — مفهوم الوراثة (Inheritance)، حيث نشتق فئة جديدة من فئة موجودة مسبقاً.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Object-Oriented Model

· A entity is modeled as an object.
· Every object has a state (the set of values for the attributes of the object) and a behavior (the set of methods that operate on the state of the object).
· The relationship between the objects is through sharing of access
· An object must belong to only one class as an instance of that class.
· You can derive a new class (subclass) from an existing class (superclass).

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تشرح هذه الشريحة النموذج الرابع وهو النموذج كائني التوجه (Object-Oriented Model)، وقد ربطه المحاضر بمفاهيم البرمجة كائنية التوجه (OOP) في لغة الجافا لتسهيل فهمه:

1. الكيان ككائن (Entity as an Object): كل عنصر في النظام (مثل الطالب Student) يُمثل كـ كائن (Object).
2. الحالة والسلوك (State & Behavior): أي كائن يتكون من شقين أساسيين:
   · الحالة (State): هي قيم الصفات (Attributes) الخاصة به (مثل: Student_Name, ID, Address, Email).
   · السلوك (Behavior): هي العمليات البرمجية (Methods) التي تُجرى على هذه البيانات (مثل: add(), update(), ودوال الـ Getters و Setters).
3. العلاقات والانتماء للفئة (Relationships & Class):
   · ترتبط الكائنات ببعضها من خلال مشاركة الوصول (Sharing of access).
   · يجب أن ينتمي كل كائن إلى فئة واحدة فقط (Only one class) كنسخة (Instance) منها.
4. الوراثة (Inheritance): يمكنك اشتقاق فئة جديدة (Subclass — مثل طالب بكالوريوس) من فئة موجودة أصلاً (Superclass — مثل طالب) لترث صفاتها وعملياتها.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف سبب ظهور هذا النموذج باسم "حل مشكلة عدم التوافق المعاوق" (Solving the Object-Relational Impedance Mismatch)؛ فبدلاً من تفكيك الكائنات البرمجية في الذاكرة إلى جداول مسطحة لتخزينها، يقوم هذا النموذج بتخزين الكائنات في قاعدة البيانات بنفس هيكلها الكائني (State + Behavior مغلفة معاً)، مما يجعله مثالياً للبيانات المعقدة كالتصاميم الهندسية والوسائط المتعددة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة الكائن الذهبية: Object = State (Attributes/Values) + Behavior (Methods).
  · اربطي المصطلحات المتقابلة:
    · State ➔ Attributes (بيانات/صفات).
    · Behavior ➔ Methods (عمليات/دوال).
    · Derive new class ➔ Subclass من Superclass (الابن من الأب / الوراثة).
    · Object ينتمي إلى ➔ Only ONE class (فئة واحدة فقط).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (التمييز بين State و Behavior):
In an Object-Oriented database model, what does the "State" of an object represent?

· A) The set of methods that operate on the object.
· B) The set of values for the attributes of the object.
· C) The relationship between a subclass and a superclass.
· الإجابة الصحيحة: B (الـ State هي مجموعة القيم لصفات الكائن Attributes، بينما الـ Behavior هي مجموعة الدوال Methods).

2. True or False (صح أم خطأ — فخ تعدد الفئات):
Statement: "In an Object-Oriented model, a single object can belong to multiple classes simultaneously as an instance." (True / False)

· الإجابة: False (خطأ) — تنص الشريحة حرفياً على أن الكائن يجب أن ينتمي إلى فئة واحدة فقط (Only one class) كنسخة (Instance) منها.

3. Fill in the Blanks (سؤال إكمال فراغات):

1. The relationship between objects is established through ________________________.
2. You can derive a new class called a ________________________ from an existing class called a ________________________.

· الإجابة النموذجية: 1. sharing of access / 2. subclass , superclass.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 10، أخبريني لننتقل مباشرة إلى Slide 11 (Example of an Object-Oriented Model: مثال عملي على النموذج كائني التوجه)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 11 (الشريحة الحادية عشرة: مثال عملي على النموذج كائني التوجه / Example of an Object-Oriented Model).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· class Employee (فئة الموظف): تُنطق (كلاس إمبلويي) — القالب أو المخطط الأساسي الذي يحدد صفات وعمليات أي موظف.
· private / public (خاص / عام): تُنطق (برايفت / بابليك) — محددات الوصول (Access Modifiers) في البرمجة للتحكم في إمكانية رؤية وتعديل البيانات والدوال.
· getId() / setId() (دوال الجلب والتعديل): تُنطق (جيت آي دي / سيت آي دي) — دوال برمجية (Getters & Setters) تُستخدم لقراءة وتعديل قيمة صفة الرقم التعريفي الخاص (private id).
· new Employee() (إنشاء كائن جديد): تُنطق (نيو إمبلويي) — الأمر البرمجي (Constructor call) الذي ينشئ نسخة فعلية (Object / Instance) من الفئة في الذاكرة وقاعدة البيانات.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Example of an Object-Oriented Model

(الرسم التوضيحي في الشريحة):

· المربع الأيسر (القالب الأساسي): class Employee
  · Attributes: private String id ، public String lastName
  · Methods: private getId () ، public setId (String anId)

الأسهم: new Employee()

· المربعان الأيمنان (الكائنات المنشأة):
  · Object 1 (Employee): id = 215 63 2179 ، lastName = Smith
  · Object 2 (Employee): id = 215 63 2180 ، lastName = John

(النقاط النصية في الأسفل):

· Shown are two Employee objects created from the Employee class.
· Each with different values for the attributes of id and lastName.

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل الرسم وشرح المحاضر)

توضح هذه الشريحة تطبيقاً عملياً لكيفية عمل النموذج كائني التوجه باستخدام مثال الموظفين (Employee)، كما شرحه المحاضر في التفريغ:

· القالب الأساسي على اليسار (class Employee): يمثل التصميم العام للموظف، ويضم قسمين:
  · الصفات (Attributes): المتغيرات التي تحفظ البيانات، مثل رقم الموظف (id) واسم عائلته (lastName).
  · العمليات (Methods): الدوال التي تتحكم في هذه البيانات، مثل getId() و setId().
· إنشاء الكائنات (new Employee()): عندما نريد إضافة موظفين فعليين إلى قاعدة البيانات، نستخدم الأمر new Employee() لإنشاء كائنات حقيقية (Objects) من هذا القالب.
· النسخ الفعلية على اليمين (الكائنات): تم إنشاء كائنين مستقلين من نفس الفئة:
  · الموظف الأول: رقمه 215 63 2179 واسم عائلته Smith.
  · الموظف الثاني: رقمه 215 63 2180 واسم عائلته John.
· القاعدة الأساسية: يشترك الكائنان في نفس الهيكل وأسماء الصفات (id و lastName)، لكن كل كائن يحمل قيماً مختلفة (Different values) تمثل حالته الخاصة (State).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات البرمجة وقواعد البيانات بجامعتي Harvard (CS50) و Stanford (CS145)، يُستخدم هذا المثال لترسيخ مبدأ "الفصل بين المخطط والنسخة" (Blueprint vs. Instance) و"التغليف" (Encapsulation)؛ فالـ class Employee لا يخزن بيانات موظفين حقيقيين بل هو القالب، بينما الكائنان Smith و John هما النسخ الفعلية في الذاكرة. كما أن تعريف id كـ private يجبر البرامج على تعديله حصراً عبر الدالة setId(String anId) للتحقق من صحة الرقم وحماية سلامة البيانات.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة الرسمة في الشريحة: 1 Class (قالب واحد على اليسار: Employee) ➔ new Employee() ➔ 2 Objects (كائنان على اليمين: Smith و John).
  · قاعدة التشابه والاختلاف: الكائنات المنشأة من نفس الـ Class تتطابق في أسماء الصفات (Attribute names)، وتختلف في قيم الصفات (Attribute values).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (تحليل المثال في الشريحة):
In the provided Object-Oriented Model example, what do "Smith" and "John" represent?

· A) Two different classes derived through inheritance.
· B) Two separate Employee objects (instances) created from the Employee class with different attribute values.
· C) Two methods used to modify employee IDs.
· الإجابة الصحيحة: B (يمثل Smith و John كائنين Employee objects أُنشئا من فئة Employee بقيم مختلفة للصفات id و lastName).

2. True or False (صح أم خطأ):
Statement: "All objects created from the same class must share the exact same attribute values." (True / False)

· الإجابة: False (خطأ) — الكائنات المنشأة من نفس الفئة تشترك في هيكل الصفات والعمليات، ولكن كل كائن يمتلك قيماً مختلفة (Different values) لصفاته.

3. Short Question (سؤال مقالي قصير من الرسم):
Based on the class Employee diagram in the lecture, list two attributes and two methods defined in the class.

· الإجابة النموذجية:
  · Attributes: id (private String) and lastName (public String).
  · Methods: getId() and setId(String anId).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 11، أخبريني لننتقل مباشرة إلى Slide 12 (Relational Model - Part 1: أساسيات النموذج العلائقي)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 12 (الشريحة الثانية عشرة: النموذج العلائقي - الجزء الأول / Relational Model - Part 1).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Relational Model (النموذج العلائقي): تُنطق (ريليشنال موديل) — النموذج الأكثر استخداماً وشيوعاً في قواعد البيانات، ويعتمد على الجداول المترابطة بعلاقات.
· Collection of tables (مجموعة من الجداول): تُنطق (كوليكشن أوف تيبلز) — تقسيم البيانات إلى عدة جداول مستقلة ومترابطة (مثل جدول للطلبة، وجدول للمساقات) بدلاً من جدول واحد ضخم.
· Column / Attribute (العمود / الصفة): تُنطق (كولوم / أتريبيوت) — العمود الرأسي في الجدول الذي يمثل خاصية معينة للبيانات (مثل عمود الاسم، عمود الرقم الجامعي).
· Row / Instance (الصف / المثيل): تُنطق (رو / إنستانس) — السطر الأفقي في الجدول الذي يمثل سجلاً واحداً كاملاً لكيان واحد (مثل بيانات طالب واحد).
· Uniquely identifies (يميز بشكل فريد): تُنطق (يونيكلي آيدنتيفايز) — حقل أو مجموعة حقول تضمن عدم تشابه صفين أبداً، مثل الرقم الجامعي أو رقم الهوية.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Relational Model

· Data is represented as a collection of tables.
· Each column represents attributes that belong to the table.
· Each row represents an instance of the table.
· Each table is the visual representation of columns and rows.
· Every table has a field or a set of fields that uniquely identifies the row.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تضع هذه الشريحة القواعد الخمس الأساسية للنموذج العلائقي (Relational Model)، وقد ربطها المحاضر بالبرمجة وبالواقع العملي لتكون واضحة تماماً:

1. مجموعة جداول (Collection of tables): عكس الـ Flat File الذي يضع كل شيء في جدول واحد، هنا نوزع البيانات على عدة جداول (جدول للطلبة، جدول للمساقات، جدول للموظفين).
2. الأعمدة هي الصفات (Columns = Attributes): كل عمود في الجدول يمثل صفة أو متغيراً (تماماً مثل المتغيرات Variables داخل الـ Class في الجافا)، مثل ID و Name.
3. الصفوف هي النسخ (Rows = Instances): كل سطر أفقي يمثل حالة واحدة أو نسخة فعلية (Instance) من الجدول (تماماً مثل إنشاء Object جديد من الـ Class في الجافا)، مثل بيانات طالب معين.
4. الشكل البصري للجدول: الجدول هو تمثيل مرئي مكون من تقاطع الصفوف والأعمدة.
5. المعرّف الفريد (Uniquely identifies the row): كل جدول يجب أن يحتوي على حقل (عمود) أو مجموعة حقول تميز كل صف عن بقية الصفوف بشكل قاطع. وقد ضرب المحاضر مثالين واقعيين:
   · في الكلية الجامعية: قد يتشابه طالبان في الاسم، لكن الرقم الجامعي (Student ID) يميز كل طالب بشكل فريد.
   · في السجل المدني: حتى لو تشابه شخصان في الاسم الرباعي بالكامل، فإن رقم الهوية يميز كل مواطن عن الآخر بشكل فريد.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات المتقدمة بجامعتي Stanford (CS145) و MIT (6.830)، يُدرَّس النموذج العلائقي انطلاقاً من الورقة البحثية التاريخية للعالم E.F. Codd (1970)؛ حيث يُعرَّف الجدول رياضياً باسم Relation، ويُسمى الصف Tuple، ويُسمى العمود Attribute. وتؤكد Stanford أن النقطة الخامسة (a field or set of fields that uniquely identifies the row) هي جوهر علم قواعد البيانات؛ فبدون مفتاح أساسي فريد (Primary Key)، لا يمكن استرجاع صف محدد بدقة ولا ربط الجداول ببعضها دون أخطاء.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة التشبيه بالبرمجة (من شرح المحاضر):
    · Table = Class (الجدول هو الكلاس).
    · Column = Attribute (العمود هو الصفة).
    · Row = Instance (الصف هو النسخة/الأوبجيكت الفعلي).
  · قاعدة العمود البصمة: كل جدول لازم يكون فيه عمود أو أكثر (Uniquely identifies) مستحيل يتكرر، مثل رقم الهوية أو الرقم الجامعي.

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (التمييز بين Row و Column):
In a Relational database model, what does each "row" and each "column" in a table represent?

· A) Each row represents an attribute, and each column represents an instance.
· B) Each column represents an attribute, and each row represents an instance of the table.
· C) Both rows and columns represent separate databases.
· الإجابة الصحيحة: B (العمود Column يمثل الصفة Attribute، والصف Row يمثل النسخة Instance).

2. True or False (صح أم خطأ — سؤال مؤكد من النقطة الخامسة):
Statement: "In a relational model, every table must have a field or a set of fields that uniquely identifies each row." (True / False)

· الإجابة: True (صح) — هذه هي النقطة الخامسة في الشريحة حرفياً.

3. Short Application Question (سؤال تطبيقي من أمثلة المحاضر):
Why can't we use the "Student Full Name" column to uniquely identify rows in a university's STUDENTS table? What should be used instead?

· الإجابة النموذجية: We cannot use the student's full name because two or more students might share the exact same name. Instead, we must use a unique field such as STUDENT_ID (or National ID), which uniquely identifies every single row in the table.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 12، أخبريني لننتقل مباشرة إلى Slide 13 (Relational Model - Part 2: القواعد والقيود الستة للجداول في النموذج العلائقي)!
أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-3 Types of Database Models (أساسيات قواعد البيانات: 1-3 أنواع نماذج قواعد البيانات).

2. Slide Number (رقم الشريحة)

· Slide 13 (الشريحة الثالثة عشرة: قواعد وخصائص الجداول في النموذج العلائقي / Relational Model - Part 2).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Order (الترتيب): تُنطق (أوردر) — تسلسل ظهور الصفوف من الأعلى للأسفل أو الأعمدة من اليسار لليمين.
· Unique (فريد / غير مكرر): تُنطق (يونيك) — صفة تعني عدم جواز تكرار نفس الصف أو الاسم مرتين.
· One value (قيمة واحدة): تُنطق (وَن فاليو) — مبدأ الذرية (Atomicity)، أي أن الخلية الواحدة في الجدول لا تقبل إلا قيمة واحدة فقط.
· Domain / Datatype (النطاق / نوع البيانات): تُنطق (دومين / داتاتايب) — نوع القيم المسموح بتخزينها في العمود الواحد (مثل أرقام فقط Integer، أو نصوص فقط String).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Relational Model

· The order of the rows and columns is not important.
· Every row is unique.
· Each field can contain only one value.
· Values within a column or field are from the same domain (datatype)
· Table names must be unique
· Column names within each table must be unique.

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

توضح هذه الشريحة القوانين الستة الصارمة التي يفرضها نظام إدارة قواعد البيانات (مثل Oracle) عند إنشاء أي جدول علائقي:

1. ترتيب الصفوف والأعمدة غير مهم (Order is not important): لا يؤثر إذا وضعتِ عمود Name قبل عمود ID أو العكس، ولا يؤثر ترتيب أسماء الطلاب في الصفوف؛ لأننا نسترجع البيانات بالبحث عن قيمها وأسماء أعمدتها وليس بموقعها.
2. كل صف فريد (Every row is unique): ممنوع وجود صفين متطابقين تماماً في الجدول، ويجب تمييز كل صف عن بقية الصفوف.
3. قيمة واحدة فقط في كل خلية (Each field can contain only one value): الخلية الواحدة لا يجوز أن نضع فيها قيمتين معاً؛ فمثلاً لا نضع عنوانين في نفس الخلية، والاسم الرباعي نقسمه إلى أعمدة منفصلة (First_Name, Last_Name).
4. تجانس نوع البيانات في العمود الواحد (Same domain / datatype): كل عمود له نوع بيانات محدد؛ فإذا عرّفتِ عمود ID كرقم (Integer) وحاولتِ إدخال نص (String) فيه، سيعطيكِ النظام خطأ (Error) فوراً.
5. أسماء الجداول يجب أن تكون فريدة (Table names must be unique): داخل قاعدة البيانات الواحدة، ممنوع إنشاء جدولين بنفس الاسم (مثل جدولين باسم STUDENT)، تماماً كما لا يجوز إنشاء كلاسين بنفس الاسم في البرمجة.
6. أسماء الأعمدة داخل الجدول الواحد يجب أن تكون فريدة (Column names within each table must be unique): داخل جدول STUDENT مثلاً، لا يجوز وجود عمودين بنفس الاسم ID (ولكن يجوز وجود عمود ID في جدول الطالب وعمود آخر اسمه ID في جدول المساق).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، تمثل هذه القواعد الست الترجمة العملية لمبادئ الجبر العلائقي (Relational Algebra) والتطبيع الأول (First Normal Form - 1NF)؛ فالجدول العلائقي في الرياضيات هو مجموعة (Set) غير مرتبة (Order is not important) مما يمنح المحرك حرية التخزين السريع، وقاعدة "قيمة واحدة في الخلية" تمنع تكديس القوائم وتُعرف بمبدأ الذرية (Atomicity).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قاعدة الـ 4 "فريد/واحد" (Unique / One):
    1. كل صف فريد (Every row is unique).
    2. كل خلية فيها قيمة واحدة (Only one value).
    3. اسم الجدول فريد (Table names must be unique).
    4. اسم العمود في الجدول الواحد فريد (Column names within each table must be unique).
  · انتبهي لفخ الامتحان في النقطة 6: اسم العمود يجب أن يكون فريداً داخل الجدول الواحد (within each table) وليس على مستوى قاعدة البيانات كلها!

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. True or False (صح أم خطأ — فخ الترتيب):
Statement: "In a relational database table, the order of the rows and columns is very important and affects how data is stored." (True / False)

· الإجابة: False (خطأ) — ترتيب الصفوف والأعمدة غير مهم (not important).

2. True or False (صح أم خطأ — فخ أسماء الأعمدة):
Statement: "Column names must be unique across the entire database, meaning two different tables cannot have a column named ID." (True / False)

· الإجابة: False (خطأ) — أسماء الأعمدة يجب أن تكون فريدة داخل كل جدول على حدة (within each table) فقط.

3. Multiple Choice (اختيار من متعدد):
Which of the following violates the rules of the Relational Model?

· A) Changing the order of columns in a table.
· B) Storing two phone numbers inside a single field (cell) for one student.
· C) Having a column named NAME in STUDENT and another column named NAME in COURSE.
· الإجابة الصحيحة: B (تخزين قيمتين في خلية واحدة يخالف قاعدة: Each field can contain only one value).

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 13، أخبريني لننتقل مباشرة إلى Slide 14 (Example of a Relational Model: مثال عملي على المفتاح الأساسي Primary Key والمفتاح الأجنبي Foreign Key)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

ولا يهمك، خذي وقتكِ الكامل في تدوين وفهم الشريحة الرابعة عشرة (Slide 14)؛ فهي من أهم شرائح الفصل لأنها توضح عملياً فكرة ربط الجداول. إليكِ ملخصاً مركزاً ومقسماً بنقاط قصيرة لكي تحفظيها وتكتبيها في دفتركِ بسهولة تامة:

بطاقة الحفظ والتدوين السريع: Slide 14

· اسم الدرس: Database Foundations: 1-3 Types of Database Models.
· عنوان الشريحة: Example of a Relational Model (مثال عملي على النموذج العلائقي).
· الفكرة الجوهرية في سطر واحد: ربط جدول الموظفين (EMPLOYEE) بجدول الأقسام (DEPARTMENT) عن طريق حقل مشترك (Common Field) هو DEPARTMENT_ID.

1. مقارنة المفتاحين (احفظيها بهذا الشكل):

· المفتاح الأساسي (Primary Key - PK):
  · مكانه في المثال: عمود DEPARTMENT_ID داخل جدول DEPARTMENT.
  · قاعدته: يميز كل قسم بشكل فريد ويُمنع تكراره أبداً (Unique).
· المفتاح الأجنبي (Foreign Key - FK):
  · مكانه في المثال: عمود DEPARTMENT_ID داخل جدول EMPLOYEE.
  · قاعدته: يشير إلى المفتاح الأساسي في جدول الأقسام، ويُسمح بتكراره (مثل تكرار القسم 90 لثلاثة موظفين).

2. كيف نستخرج المعلومة؟ (خطوتان فقط):

1. ننظر للموظفة Jennifer Whalen (EMPLOYEE_ID = 200) فنجد رقم قسمها 10.
2. نذهب لجدول الأقسام عند الرقم 10 فنعرف أنها تعمل في قسم Administration.

---

خذي وقتكِ في كتابتها وحفظها، وأخبريني بكلمة "تم" أو "كمل" عندما تكونين جاهزة للانتقال إلى Slide 15 (بداية درس 1-4: Business Requirements)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 15 (الصفحة 15 في الملف — شريحة العنوان والتمهيد للدرس 1-4).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Business Requirements (متطلبات الأعمال): تُنطق (بزنس ريكوايرمنتس) — الاحتياجات والأهداف والقوانين التي تحكم عمل المؤسسة أو الشركة، والتي يجب فهمها بدقة قبل البدء في تصميم قاعدة البيانات.
· Database Foundations (أساسيات قواعد البيانات): تُنطق (داتابيس فاونديشنز) — المبادئ الأساسية لتصميم وبناء قواعد البيانات في منهج Oracle Academy.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Database Foundations
1-4
Business Requirements
Copyright © 2015, Oracle and/or its affiliates. All rights reserved.

5. Explanation in Arabic (الشرح باللغة العربية مع ربطها بشرح المحاضر)

تمثل هذه الشريحة بداية الدرس الرابع من الوحدة الأولى (1-4)، وتعيدنا إلى نقطة البداية الأولى في عملية تطوير قاعدة البيانات (Database Development Process):

· الهدف من الدرس: في الدرس السابق تعرفنا على أشكال ونماذج قواعد البيانات (مثل النموذج العلائقي)، أما في هذا الدرس فننتقل لمرحلة ما قبل التصميم: كيف نفهم عمل المؤسسة ومتطلباتها؟.
· ربط مع شرح المحاضر: أكد المحاضر في التفريغ أنكِ قبل كتابة أي كود أو تصميم أي جدول (سواء لمكتبة أو بنك أو كلية)، يجب أن تسألي صاحب العمل: "ما هو المطلوب؟ وما هي قوانينكم؟"؛ لأن قاعدة البيانات تُبنى لخدمة هذه المتطلبات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة البرمجيات وهندسة النظم بجامعتي MIT و Stanford، يُطلق على هذه المرحلة اسم "هندسة المتطلبات" (Requirements Engineering)؛ لأن قاعدة البيانات ما هي إلا مرآة رقمية لقوانين المؤسسة، وأكبر سبب لفشل المشاريع هو البدء ببناء الجداول قبل فهم متطلبات العمل بوضوح.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري الرقم 1-4: يشير إلى الوحدة الأولى، الدرس الرابع من منهج Oracle Academy.
  · معادلة البداية: لا تصميم بدون متطلبات (No Design without Business Requirements).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
What is the very first step before designing tables and relationships in the Database Development Process?

· A) Writing SQL queries to build the database.
· B) Gathering and understanding the Business Requirements of the organization.
· C) Deleting redundant rows from existing tables.
· الإجابة الصحيحة: B (جمع وفهم متطلبات الأعمال Business Requirements هو نقطة البداية قبل التصميم).

2. True or False (صح أم خطأ):
Statement: "A database designer can immediately create tables and relationships without understanding the organization's business requirements." (True / False)

· الإجابة: False (خطأ) — يجب أولاً فهم وتوثيق متطلبات الأعمال (Business Requirements) لمعرفة ما تحتاجه المؤسسة من بيانات وقيود قبل التصميم.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 15، أخبريني لننتقل مباشرة إلى Slide 16 (Objectives: أهداف درس متطلبات الأعمال)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 16 (الصفحة 16 في الملف — شريحة أهداف الدرس / Objectives).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Database Solution (حل قاعدة البيانات): تُنطق (داتابيس سوليوشن) — اعتماد نظام قاعدة بيانات متكامل كحل لمشاكل تخزين وتنظيم البيانات بدلاً من الملفات التقليدية.
· Business Rules (قواعد العمل): تُنطق (بزنس رولز) — القوانين والسياسات والشروط التي تتبعها المؤسسة في معاملاتها اليومية وتُترجم لاحقاً إلى قيود في قاعدة البيانات.
· Guidelines (إرشادات / توجيهات): تُنطق (جايدلاينز) — القواعد والمعايير التوجيهية لكيفية صياغة وكتابة قواعد العمل بشكل واضح وسليم.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Objectives
This lesson covers the following objectives:

· Explain the need for a database solution
· Describe the importance of business rules
· Identify guidelines and examples of writing business rules
  DFo 1-6 Business Requirements - 4

5. Explanation in Arabic (الشرح باللغة العربية مع تركيز المحاضر)

تحدد هذه الشريحة الأهداف الثلاثة التي سنتعلمها في هذا الدرس، كما لخصها المحاضر في التفريغ:

1. توضيح الحاجة لحل قاعدة البيانات (Explain the need for a database solution): لماذا لا نكتفي بملفات Word أو Excel ونحتاج فعلياً لقاعدة بيانات؟ (السبب هو تعدد المستخدمين، تعدد عناصر البيانات، وتكامل المكونات).
2. وصف أهمية قواعد العمل (Describe the importance of business rules): لماذا يجب أن نعرف قوانين المؤسسة (مثل شروط التسجيل أو الاستعارة) قبل تصميم الجداول؟ لأنها توضح العلاقات والقيود بين البيانات.
3. تحديد إرشادات وأمثلة لكتابة قواعد العمل (Identify guidelines and examples of writing business rules): كيف نستخرج هذه القواعد من سيناريو العمل ونكتبها بشكل منظم وواضح (مع تنبيه المحاضر أن طريقة الصياغة الشكلية ليست قالباً جامداً، بل الأهم هو استخراج القاعدة والشرط بدقة).

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي MIT و Stanford، تُلخص هذه الأهداف الثلاثة في مسار "من المشكلة إلى المواصفات" (From Problem to Specification)؛ حيث تبدأ بتبرير الحاجة التقنية لقاعدة البيانات، ثم جمع القوانين الإدارية للمؤسسة، وأخيراً صياغتها بدقة لكي تتحول إلى قيود برمجية (Constraints) وعلاقات (Relationships) تحمي البيانات من الأخطاء.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري أهداف الدرس الثلاثة كقصة متسلسلة (لماذا ➔ ما الأهمية ➔ كيف نكتب):
    1. لماذا؟ لماذا نحتاج قاعدة بيانات؟ (Need for a database solution).
    2. ما الأهمية؟ ما أهمية قوانين العمل؟ (Importance of business rules).
    3. كيف نكتب؟ كيف نصيغ هذه القوانين؟ (Guidelines & examples of writing business rules).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
Which of the following is NOT one of the objectives of the "Business Requirements" lesson?

· A) Explain the need for a database solution.
· B) Describe the importance of business rules.
· C) Write complex SQL queries to delete database tables.
· D) Identify guidelines and examples of writing business rules.
· الإجابة الصحيحة: C (الأهداف الثلاثة في الشريحة لا تشمل كتابة أوامر SQL للحذف).

2. Short Question (سؤال مقالي قصير / تعداد):
List the three main objectives covered in the "Business Requirements" lesson.

· الإجابة النموذجية:
  1. Explain the need for a database solution.
  2. Describe the importance of business rules.
  3. Identify guidelines and examples of writing business rules.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 16، أخبريني لننتقل مباشرة إلى Slide 17 (Why Do I Need a Database Solution?: الأسباب الثلاثة للحاجة لقاعدة بيانات)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 17 (الصفحة 17 في الملف — لماذا أحتاج إلى حل قاعدة بيانات؟ / Why Do I Need a Database Solution?).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Integration of Multiple Components (تكامل المكونات المتعددة): تُنطق (إنتجريشن أوف مالتيبل كومبوننتس) — ربط مختلف أقسام وأنظمة المؤسسة (مثل القبول والتسجيل، المالية، المكتبة) للعمل بتناغم وانسجام مع مصدر بيانات واحد.
· Multiple Data Items (تعدد عناصر البيانات): تُنطق (مالتيبل داتا آيتمز) — تنوع وكثرة أنواع البيانات المخزنة (بيانات طلاب، مساقات، مدرسين، مدفوعات مالية، كتب) بدلاً من نوع واحد بسيط.
· Multiple Users (تعدد المستخدمين): تُنطق (مالتيبل يوزرز) — وجود عدد كبير من الأشخاص (طلاب، موظفين، مدرسين، إداريين) يحتاجون للوصول إلى البيانات والتعامل معها في نفس الوقت ومن أماكن مختلفة.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Why Do I Need a Database Solution?

· Integration of Multiple Components
· Multiple Data Items
· Multiple Users

DFo 1-6 Business Requirements - 5

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تجيب هذه الشريحة عن السؤال الجوهري: لماذا نترك الملفات التقليدية (Word / Excel) ونبني قاعدة بيانات؟ وذلك من خلال ثلاثة أسباب رئيسية ربطها المحاضر بواقع الكلية الجامعية:

1. تعدد المستخدمين (Multiple Users): في الكلية هناك آلاف الطلاب بمستوياتهم المختلفة، وعشرات المدرسين والموظفين في القبول والتسجيل والمالية. الجميع يدخلون للنظام في نفس اللحظة من بيوتهم أو مكاتبهم؛ وملفات الإكسل التقليدية لا تتحمل هذا العدد المتزامن من المستخدمين.
2. تعدد عناصر البيانات (Multiple Data Items): البيانات ليست نوعاً واحداً، بل هناك بيانات شخصية للطلاب، بيانات للمساقات، بيانات للدرجات، وبيانات مالية. إدارة هذا الكم المتنوع تتطلب قاعدة بيانات منظمة.
3. تكامل المكونات المتعددة (Integration of Multiple Components): الكلية تتكون من أنظمة وأقسام متعددة (نظام المكتبة، نظام القبول، نظام المالية). قاعدة البيانات تدمج وتربط هذه المكونات ببعضها بحيث يصب الجميع في مكان واحد وتصلين للمعلومة بسهولة تامة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي MIT (6.830) و Stanford (CS145)، تُترجم هذه النقاط الثلاث إلى "المتطلبات المؤسساتية للأنظمة"؛ فوجود Multiple Users يتطلب إدارة التزامن (Concurrency Control) لمنع تضارب التعديلات في نفس اللحظة، ووجود Multiple Data Items و Multiple Components يمنع عزلة البيانات (Data Silos) بحيث يرى قسم المالية نفس بيانات الطالب التي يراها قسم القبول والتسجيل.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قاعدة الـ 3 "متعدد" (Triple Multiple): لاحظي أن كلمة Multiple (متعدد) تتكرر في النقاط الثلاث جميعها:
    · Multiple Components (مكونات متعددة).
    · Multiple Data Items (بيانات متعددة).
    · Multiple Users (مستخدمون متعددون).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد):
Which of the following is NOT one of the three main reasons why an organization needs a database solution?

· A) Multiple Users
· B) Multiple Data Items
· C) Integration of Multiple Components
· D) Storing all data in a single unlinked text file
· الإجابة الصحيحة: D (الأسباب الثلاثة في الشريحة هي: تكامل المكونات المتعددة، تعدد عناصر البيانات، وتعدد المستخدمين).

2. Short Question (سؤال مقالي قصير / تعداد):
List the three main reasons that justify the need for a database solution (Why do we need a database solution?).

· الإجابة النموذجية:
  1. Integration of Multiple Components
  2. Multiple Data Items
  3. Multiple Users

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 17، أخبريني لننتقل مباشرة إلى Slide 18 (Case Scenario: Need a Database Solution - مثال جدول الرياضات والطلاب بصيغة Flat File)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل الجدول المذكور في النص إلى جدول Markdown احترافي لتسهيل القراءة):

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 18 (الصفحة 18 في الملف — سيناريو الحالة: الحاجة لحل قاعدة بيانات / Case Scenario: Need a Database Solution).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Warrants (يستوجب / يبرر): تُنطق (وورَنتس) — مصطلح مهم في نص الشريحة ويعني أن هذا الوضع الصعب "يستدعي ويبرر" الحاجة لإنشاء قاعدة بيانات.
· Flat File (ملف مسطح): تُنطق (فلات فايل) — جدول واحد ضخم يجمع كل البيانات معاً بدون تقسيم.
· Repeating Groups (مجموعات متكررة): تُنطق (ريبيتينج جروبس) — تكرار نفس الأعمدة أفقياً داخل السطر الواحد (مثل Sport 1, Price 1 ثم Sport 2, Price 2).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Need a Database Solution

 Student ID Sport 1 Price 1 Sport 2 Price 2
Record 1 ST0001 Tennis $100 Badminton $150
Record 2 ST0002 Soccer $175 Tennis $100
Record 3 ST0003 Cycling $200 Badminton $150
...... ...... ...... ...... ...... ......

This is a flat file that stores information about students, the sports that they selected, and the price for each sport that they selected. This scenario warrants the need for a database.
DFo 1-6 Business Requirements - 6

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

توضح هذه الشريحة مثالاً عملياً حياً يثبت فشل الملف المسطح (Flat File) عند تعدد البيانات، ويشرح لماذا نضطر للانتقال إلى قاعدة بيانات:

· مشكلة التصميم في الجدول: تم وضع رقم الطالب (Student ID) مع الرياضات التي اختارها وأسعارها في جدول واحد ضخم على شكل أعمدة متكررة أفقياً (Sport 1, Price 1, Sport 2, Price 2).
· الكوارث الناتجة عن هذا الجدول (كما شرحها المحاضر في التفريغ):
  · صعوبة الاستعلام والبحث (Querying Difficulty): سأل المحاضر سؤالاً ذكياً: "لو أردتُ معرفة أسماء وعدد الطلاب المشتركين في رياضة التنس (Tennis) من هذا الجدول، ماذا سأفعل؟". ستضطرين للبحث في عمود Sport 1 ثم البحث مرة أخرى في عمود Sport 2، وهذا معقد وبطيء جداً في ملف الإكسل.
  · تكرار الأسعار (Data Redundancy): لاحظي أن سعر التنس ($100) تكرر في Record 1 وفي Record 2، وسعر الريشة (Badminton $150) تكرر في Record 1 وفي Record 3. لو ارتفع سعر رياضة التنس ليصبح $120، سنضطر لتعديله في عشرات الصفوف والأعمدة.
  · مشكلة الحدود (Scalability Limit): الجدول مصمم لرياضتين فقط (Sport 1 و Sport 2). ماذا لو أراد طالب الاشتراك في 5 رياضات؟ سنضطر لتعديل هيكل الجدول وإضافة أعمدة جديدة (Sport 3, Price 3...)، بينما الطلاب المشتركون في رياضة واحدة ستبقى خاناتهم فارغة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعد هذا الجدول المثال الكلاسيكي لـ "انتهاك التطبيع الأول" (Violation of First Normal Form - 1NF)؛ فوضع أعمدة مرقمة مثل Sport 1, Sport 2 يُسمى Repeating Groups، وهو يدمج ثلاثة كيانات مستقلة (الطلاب، الرياضات، والاشتراكات) في جدول واحد مما يجعل كتابة الاستعلامات معقدة. الحل الهندسي هو تفكيك الجدول (Decomposition) إلى جداول صغيرة مستقلة.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري سؤال المحاضر السحري في الامتحان: "كيف نعرف من هذا الجدول عدد الطلاب المشتركين في التنس (Tennis)؟" الإجابة: صعب جداً لأن التنس موزعة بين عمود Sport 1 وعمود Sport 2.
  · معادلة المشكلة في هذه الشريحة: Students + Sports + Prices in 1 Flat File ➔ صعوبة البحث + تكرار الأسعار ➔ Warrants the need for a database (يستوجب وجود قاعدة بيانات).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد — سؤال مباشر من نص الشريحة):
What does the provided Flat File scenario (storing Students, Sport 1/Price 1, Sport 2/Price 2 in one table) demonstrate?

· A) That flat files are the fastest way to query student sports.
· B) That storing multiple entities and repeating columns in a single flat file causes difficulties and warrants the need for a database.
· C) That relational databases do not allow students to choose more than one sport.
· الإجابة الصحيحة: B (تخزين معلومات الطلاب والرياضات وأسعارها في ملف مسطح واحد يستوجب الحاجة لقاعدة بيانات Warrants the need for a database).

2. Short Scenario / Analysis Question (سؤال تحليلي من شرح المحاضر — متوقع جداً):
Identify TWO major problems with the Flat File table shown in the slide (Student ID, Sport 1, Price 1, Sport 2, Price 2).

· الإجابة النموذجية:
  1. Difficulty in querying/searching: Finding all students enrolled in a specific sport (such as Tennis) is difficult because the sport name is scattered across multiple columns (Sport 1, Sport 2).
  2. Data redundancy (repetition): Sport prices (like Tennis $100 or Badminton $150) are repeated in every record where a student selects that sport, making updates error-prone.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 18، أخبريني لننتقل مباشرة إلى Slide 19 (Case Scenario: Possible Database Solution - كيف تم تقسيم الملف المسطح إلى 3 جداول مترابطة)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي (مع تحويل الجداول المذكورة في النص إلى جداول Markdown احترافية لتسهيل القراءة):

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 19 (الصفحة 19 في الملف — سيناريو الحالة: الحل المقترح لقاعدة البيانات / Case Scenario: Possible Database Solution).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Split (تقسيم / تجزئة): تُنطق (سبليت) — تفكيك الجدول الواحد الضخم (Flat File) إلى عدة جداول أصغر، بحيث يختص كل جدول بموضوع واحد فقط.
· Student Details Table (جدول تفاصيل الطلاب): تُنطق (ستيودنت ديتيلز تيبل) — الجدول المخصص لتخزين البيانات الشخصية الأساسية للطلاب فقط.
· Sport Details Table (جدول تفاصيل الرياضات): تُنطق (سبورت ديتيلز تيبل) — الجدول المخصص لتخزين أسماء الرياضات وأسعارها مرة واحدة فقط بدون تكرار.
· Participant Details Table (جدول تفاصيل المشاركين / الاشتراكات): تُنطق (بارتيسيپانت ديتيلز تيبل) — جدول الربط الوسيط (Junction Table) الذي يجمع رقم الطالب مع رقم الرياضة التي اشترك بها.
· Semester Details (تفاصيل الفصل الدراسي): تُنطق (سيميستر ديتيلز) — عمود يحدد الفصل الدراسي الذي سجل فيه الطالب هذه الرياضة (مثل Fall2015).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Possible Database Solution
Flat file was split into three tables.

1. Student Details Table:

Student ID First Name Last Name
ST0001 Sean Smith

2. Sport Details Table:

Sport ID Sport Name Price
TN001 Tennis $100

3. Participant Details Table:

Student ID Sport ID Semester Details
ST0001 TN001 Fall2015

DFo 1-6 Business Requirements - 7

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تشرح هذه الشريحة كيف حلّت قاعدة البيانات العلائقية مشكلة جدول الرياضات المسطح من خلال تقسيمه (Split) إلى 3 جداول مستقلة ومترابطة:

1. جدول تفاصيل الطلاب (Student Details Table):
   · يحفظ بيانات الطالب مرة واحدة فقط (Student ID, First Name, Last Name).
   · المفتاح الأساسي هنا هو Student ID (مثل ST0001).
2. جدول تفاصيل الرياضات (Sport Details Table):
   · يحفظ كل رياضة وسعرها مرة واحدة فقط في قاعدة البيانات (Sport ID, Sport Name, Price).
   · المفتاح الأساسي هنا هو Sport ID (مثل TN001 للتنس بسعر $100). إذا ارتفع سعر التنس مستقبلاً، نعدله في هذا الصف الواحد فقط.
3. جدول تفاصيل المشاركين (Participant Details Table — جدول الربط):
   · هذا هو الجدول الذكي الذي يربط الجدولين السابقين ببعضهما:
     · أخذ Student ID من جدول الطلاب (كمفتاح أجنبي Foreign Key).
     · وأخذ Sport ID من جدول الرياضات (كمفتاح أجنبي Foreign Key).
     · وأضاف معلومة الاشتراك وهي الفصل الدراسي (Semester Details مثل Fall2015).
   · كيف نجاوب على سؤال المحاضر الآن؟ لو سألنا الآن: "كم طالب مشترك بالتنس (TN001)؟"، نذهب مباشرة إلى جدول Participant Details ونعدّ الصفوف التي تحتوي على TN001 بلمحة بصر وبدقة 100%!

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات تصميم قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التصميم المكون من 3 جداول باسم "تفكيك علاقة متعدد إلى متعدد" (Many-to-Many Relationship Decomposition via a Junction Table)؛ لأن الطالب الواحد يمكنه الاشتراك في عدة رياضات، والرياضة الواحدة يشترك فيها عدة طلاب. هذا التصميم يحقق التطبيع الثالث (3NF) ويقضي تماماً على تكرار الأسعار وصعوبة الاستعلام.
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · معادلة الحل السحرية (1 ➔ 3): 1 Flat File (ملف مسطح واحد فاشل) ➔ Split (تقسيم) ➔ 3 Relational Tables:
    · جدول لـ الطلاب (Student Details).
    · جدول لـ الرياضات (Sport Details).
    · جدول لـ الربط بينهم (Participant Details).
  · تذكري أعمدة جدول الربط (Participant Details): يأخذ الـ ID من الجدول الأول (Student ID) + الـ ID من الجدول الثاني (Sport ID) + الفصل الدراسي (Semester Details).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من الشريحة):
How was the flat file problem solved in the "Possible Database Solution" case scenario?

· A) By deleting all sport prices from the file.
· B) By splitting the single flat file into three related tables: Student Details, Sport Details, and Participant Details.
· C) By adding more columns (Sport 3, Sport 4, Sport 5) to the original flat file.
· الإجابة الصحيحة: B (تم تقسيم الملف المسطح إلى ثلاثة جداول: Student Details, Sport Details, Participant Details).

2. Multiple Choice (سؤال تحليل هيكل الجداول):
In the Participant Details Table, what role do the Student ID and Sport ID columns play?

· A) They act as Foreign Keys linking the Participant Details table to the Student Details and Sport Details tables.
· B) They are deleted automatically after each semester.
· C) They represent plain-text delimiters.
· الإجابة الصحيحة: A (جدول Participant Details يربط الجدولين الآخرين معاً باستخدام Student ID و Sport ID كمفاتيح أجنبية).

3. Short Design Question (سؤال تصميمي متوقع):
Given the flat file table (Student_ID, Sport1, Price1, Sport2, Price2), explain how to convert it into a relational database solution and list the tables with their columns.

· الإجابة النموذجية: We split the flat file into three tables:
  · Student Details Table: (Student ID, First Name, Last Name)
  · Sport Details Table: (Sport ID, Sport Name, Price)
  · Participant Details Table: (Student ID, Sport ID, Semester Details)

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 19، أخبريني لننتقل مباشرة إلى Slide 20 (Importance of Business Rules: أهمية قواعد العمل وخصائصها)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 20 (الصفحة 20 في الملف — أهمية قواعد العمل / Importance of Business Rules).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Document (توثيق): تُنطق (دوكيومنت) — كتابة وتسجيل القوانين والشروط في مستندات رسمية بدلاً من تركها شفوية أو في الذاكرة.
· Developer / Architect (المطور / المهندس المعماري للنظام): تُنطق (ديفيلوبر / آركيتيكت) — الشخص المسؤول عن تصميم وبناء قاعدة البيانات.
· Constraints (القيود / الشروط): تُنطق (كونسترينتس) — الضوابط والحدود المفروضة على البيانات (مثل: الحد الأدنى للتسجيل 12 ساعة، أو مدة الاستعارة أسبوع).
· Participating Entities (الكيانات المشاركة): تُنطق (بارتيسيپيتينج إينتيتيز) — العناصر الرئيسية في النظام التي تتفاعل مع بعضها (مثل الطالب، المساق، المدرس).
· Standardization Procedure (إجراءات التوحيد القياسي): تُنطق (ستاندردايزيشن بروسيجر) — الخطوات والإجراءات الرسمية الثابتة التي تتبعها المؤسسة عند التعامل مع البيانات الضخمة (مثل المستندات المطلوبة لتسجيل طالب جديد).
· Up-to-date (مُحدَّثة باستمرار): تُنطق (آب-تو-ديت) — مواكبة القوانين للتغييرات الجديدة في المؤسسة وعدم الاعتماد على وثائق قديمة.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Importance of Business Rules

It is important to identify and document business rules when designing a database.

Business rules:

· Allow the developer/architect to understand the relationship and constraints of the participating entities
· Help you understand the standardization procedure that an organization follows when handling huge data
· Should be simple and easy to understand
· Must be kept up-to-date

DFo 1-6 Business Requirements - 8

5. Explanation in Arabic (الشرح باللغة العربية مع أمثلة المحاضر)

تشرح هذه الشريحة لماذا نحتاج لتحديد وتوثيق قوانين المؤسسة (Business Rules) قبل تصميم قاعدة البيانات، وقد ربطها المحاضر في التفريغ بأمثلة حية من القبول والتسجيل في الكلية الجامعية:

1. فهم العلاقات والقيود (Relationships & Constraints): عندما يذهب المبرمج لبناء نظام بنك أو كلية، فهو بحاجة لفهم العلاقة بين الجداول والقيود المفروضة عليها (مثل مثال المحاضر: الطالب لا يسجل أقل من 12 ساعة، ولا يعيد مادة علامتها فوق 75).
2. فهم الإجراءات القياسية للمؤسسة (Standardization Procedure): توضح القوانين الروتين الرسمي المتبع عند التعامل مع البيانات الكبيرة (مثل مثال المحاضر: أي طالب جديد يسجل في الكلية يجب أن يحضر صورة الهوية، صور شخصية، وشهادة الثانوية العامة).
3. يجب أن تكون بسيطة وسهلة الفهم (Simple and easy to understand): تُكتب بلغة واضحة لكي يفهمها المبرمج وصاحب العمل معاً دون غموض.
4. يجب أن تبقى محدثة باستمرار (Must be kept up-to-date): حذّر المحاضر من العمل على وثائق وقوانين قديمة مكتوبة منذ 10 سنوات؛ لأن القوانين تتغير باستمرار، والعمل على قوانين قديمة يعني إعادة بناء النظام بالكامل!

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة النظم بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى Business Rules على أنها "الجسر التعاقدي بين الإدارة والتقنية"؛ حيث تتحول الكيانات إلى جداول (Tables)، والروابط إلى علاقات (Relationships / Foreign Keys)، والشروط والحدود إلى قيود برمجية (Check Constraints) تمنع إدخال أي بيانات تخالف سياسة المؤسسة. كما تحذر MIT من انحراف المتطلبات (Requirements Drift) إذا لم تُحدَّث الوثيقة باستمرار (Up-to-date).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · قسّمي النقاط الأربع إلى مجموعتين (2 فوائد + 2 صفات):
    · فائدتان (ماذا تفعل؟):
      1. تفهمنا العلاقات والقيود (Relationships & Constraints).
      2. تفهمنا الإجراءات القياسية للبيانات الضخمة (Standardization procedure).
    · صفتان (كيف يجب أن تكون؟):
      3. بسيطة وسهلة الفهم (Simple & easy to understand).
      4. محدثة باستمرار (Kept up-to-date).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (اختيار من متعدد — سؤال مباشر من الشريحة):
Which of the following is a required characteristic of well-written Business Rules?

· A) They should be complex and written only in SQL code.
· B) They should be simple, easy to understand, and kept up-to-date.
· C) They never need to be documented before building the database.
· الإجابة الصحيحة: B (يجب أن تكون بسيطة وسهلة الفهم Simple and easy to understand ومحدثة باستمرار Must be kept up-to-date).

2. True or False (صح أم خطأ):
Statement: "Business rules help database developers understand the relationships and constraints of the participating entities." (True / False)

· الإجابة: True (صح) — هذه هي النقطة الأولى حرفياً في فوائد قواعد العمل بالشريحة.

3. Short Essay / Enumeration (سؤال مقالي قصير — متوقع جداً):
Why is it important to identify and document business rules when designing a database? Mention the four points from the lecture.

· الإجابة النموذجية:
  1. They allow the developer/architect to understand the relationships and constraints of the participating entities.
  2. They help understand the standardization procedure that an organization follows when handling huge data.
  3. They should be simple and easy to understand.
  4. They must be kept up-to-date.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 20، أخبريني لننتقل مباشرة إلى Slide 21 (Case Scenario: Identifying Business Rules - دراسة حالة مكتبة SunStar)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 21 (الصفحة 21 في الملف — سيناريو الحالة: تحديد قواعد العمل / Case Scenario: Identifying Business Rules).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Rentals (تأجير / استعارات): تُنطق (رينتالز) — عمليات استئجار الكتب من المكتبة لفترة معينة.
· Customer Base (قاعدة العملاء): تُنطق (كاستومر بيس) — مجموعة الزبائن المشتركين في النظام والمستمرين في التعامل معه.
· Membership (العضوية): تُنطق (ميمبرشيب) — نوع الاشتراك الذي يحصل عليه العميل في المكتبة (ذهبية، فضية، برونزية).
· Incur a fee (يترتب عليها رسوم / مدفوعة): تُنطق (إنكُر أ في) — تتطلب دفع مبلغ مالي للاشتراك فيها (عكس المجانية).
· Entitle / Privileges (تُخوّل / امتيازات): تُنطق (إنتايتل / بريفيليجيز) — تمنح العضو حقوقاً وميزات إضافية مقابل الرسوم التي يدفعها.

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Identifying Business Rules

SunStar Online Book Rentals is a successful company that rents books. With its growing business, SunStar needs to enhance its information system to support proposed changes to the business. SunStar attracts new customers easily and the number of rentals is growing rapidly. The customer base is not stable, however, which is a cause for concern.

The main idea is to introduce three types of membership (gold, silver, bronze), although more may be introduced later. Bronze membership is free. Silver and gold memberships incur a fee but entitle the member to privileges. The type of membership cannot be changed.

DFo 1-6 Business Requirements - 9

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تقدم هذه الشريحة نصاً تطبيقياً واقعياً (Case Scenario) لشركة تأجير كتب إلكترونية تُدعى SunStar، وتطلب منكِ كمصممة قواعد بيانات قراءة النص كـ "وثيقة متطلبات" (Document) واستخراج القواعد والقيود منها:

· مشكلة الشركة والهدف (الفقرة الأولى): الشركة ناجحة وتجذب عملاء جدداً بسرعة، لكن مشكلتها أن قاعدة العملاء غير مستقرة (العملاء يأتون ويذهبون). لذلك قررت تطوير نظامها لتثبيت العملاء.
· الفكرة الجديدة وقوانينها (الفقرة الثانية — هنا كنز قواعد العمل):
  · تعدد أنواع العضوية: تقسيم العضوية إلى 3 أنواع: ذهبية (Gold)، فضية (Silver)، وبرونزية (Bronze)، مع إمكانية إضافة أنواع أخرى مستقبلاً.
  · الرسوم والمجانية: العضوية البرونزية مجانية (Free)، بينما الفضية والذهبية مدفوعة برسوم (Incur a fee) وتمنح امتيازات خاصة.
  · القيد الصارم (Constraint): "نوع العضوية لا يمكن تغييره" (The type of membership cannot be changed). وقد علق المحاضر على هذه النقطة موضحاً أنكِ كمصممة ومبرمجة يجب أن تلتزمي بقوانين المؤسسة كما هي وتترجميها لقيود في قاعدة البيانات حتى لو بدت صارمة.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة البرمجيات بجامعتي Stanford (CS145) و MIT (6.830)، يُعرف هذا التمرين باسم "استخلاص المواصفات من النصوص الطبيعية" (Requirement Elicitation)؛ حيث يتم فرز الكلام التسويقي العام (Background Noise) عن القواعد الهيكلية القابلة للبرمجة (مثل 3 types و cannot be changed التي تتحول لاحقاً إلى قيد Trigger يمنع تعديل نوع العضوية في قاعدة البيانات).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · تذكري "أرقام وممنوعات" قصة SunStar:
    · العدد: 3 أنواع عضوية (Gold, Silver, Bronze).
    · المال: Bronze = Free (مجاني) | Silver & Gold = Fee (برسوم).
    · الممنوع (القيد): Cannot be changed (ممنوع تغيير نوع العضوية أبداً).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (سؤال مباشر من السيناريو):
According to the SunStar Online Book Rentals scenario, which of the following statements is TRUE regarding memberships?

· A) All three types of membership require a monthly fee.
· B) Bronze membership is free, while Silver and Gold memberships incur a fee.
· C) Members can freely upgrade their membership from Bronze to Gold at any time.
· الإجابة الصحيحة: B (العضوية البرونزية مجانية free، بينما الفضية والذهبية يترتب عليهما رسوم incur a fee).

2. True or False (صح أم خطأ — فخ القيد الصارم في السيناريو):
Statement: "In the SunStar case scenario, a customer can change their membership type later if they decide to pay a fee." (True / False)

· الإجابة: False (خطأ) — ينص القيد الأخير في السيناريو حرفياً على أن نوع العضوية لا يمكن تغييره (The type of membership cannot be changed).

3. Short Case Analysis Question (سؤال استخراج قواعد من نص):
Read the SunStar case scenario and extract TWO Business Rules and TWO Constraints that must be considered when designing the database.

· الإجابة النموذجية:
  · Business Rules:
    1. Members will pay membership fees.
    2. Bronze membership is free, while Silver and Gold memberships incur a fee.
  · Constraints:
    1. Members can belong to one of the three types of membership (gold, silver, or bronze).
    2. The type of membership cannot be changed.

---

ملاحظة: التنسيق جاهز الآن. عندما تنتهين من كتابة Slide 21، أخبريني لننتقل مباشرة إلى Slide 22 (الشريحة الأخيرة في شابتر 1: Solution for Identifying Business Rules)!

أهلاً بكِ! تم تنسيق النص الذي أرسلتِه باستخدام Markdown ليكون في غاية الترتيب والأناقة، وجاهزاً للتدوين، دون إضافة أو حذف أي حرف من المحتوى الأصلي:

---

Chapter 1: Database Foundations

1. Chapter Name (اسم الفصل / الموضوع)

· Database Foundations: 1-4 Business Requirements (أساسيات قواعد البيانات: 1-4 متطلبات الأعمال).

2. Slide Number (رقم الشريحة)

· Slide 22 (الصفحة 22 في الملف — الحل النموذجي لتحديد قواعد العمل / Case Scenario: Solution for Identifying Business Rules).

3. New Technical Vocabulary (المصطلحات التقنية الجديدة)

· Business Rule (قاعدة عمل): تُنطق (بزنس رول) — سياسة عامة أو إجراء مالي/إداري تتبعه الشركة في تعاملاتها (مثل فرض رسوم على العضويات المميزة).
· Constraint (قيد / شرط صارم): تُنطق (كونسترينت) — قاعدة تحكم وتقييد تحدد المسموح والممنوع على البيانات بدقة (مثل حصر العضويات في 3 أنواع فقط، أو منع تغيير نوع العضوية).

4. Exact Text on Slide (النص المكتوب في الشريحة كما هو)

Case Scenario: Solution for Identifying Business Rules

1. First Pair:

· Business Rule:
  · Members will pay membership fees.
· Constraint:
  · Members can belong to one of the three types of membership (gold, silver, or bronze).

2. Second Pair:

· Business Rule:
  · Bronze membership is free. Silver and gold memberships incur a fee.
· Constraint:
  · Type of membership cannot be changed.

DFo 1-6 Business Requirements - 10

5. Explanation in Arabic (الشرح باللغة العربية مع تحليل المحاضر)

تقدم هذه الشريحة الحل النموذجي لاستخراج المتطلبات من قصة SunStar في الشريحة السابقة، وتقسمها إلى ثنائيات: قاعدة عمل (Business Rule) يليها قيد تحكم (Constraint):

· الزوج الأول (الرسوم وأنواع الاشتراك):
  · قاعدة العمل (Business Rule): سيدفع الأعضاء رسوم عضوية (سياسة الشركة العامة).
  · القيد (Constraint): يمكن للعضو أن ينتمي إلى واحد فقط من الأنواع الثلاثة للعضوية: ذهبية (Gold)، فضية (Silver)، أو برونزية (Bronze). (يقيد البيانات بقائمة محددة من الخيارات).
· الزوج الثاني (تفصيل الرسوم ومنع التعديل):
  · قاعدة العمل (Business Rule): العضوية البرونزية مجانية، بينما الفضية والذهبية يترتب عليهما دفع رسوم.
  · القيد (Constraint): نوع العضوية لا يمكن تغييره (Cannot be changed). (قيد صارم يمنع تعديل البيانات بعد إدخالها).

ملاحظة المحاضر الجوهرية في التفريغ: أشار المحاضر إلى أن طريقة تقسيمها في جدول أو نقاط ليست قالباً شكلياً جامداً يُحاسب عليه الطالب حرفياً في التنسيق، بل الأهم هو القدرة على استخراج القواعد والقيود الصحيحة من أي نص لترجمتها لاحقاً إلى جداول وعلاقات وشروط في قاعدة البيانات.

6. Elite University Perspective (شرح جامعات MIT و Stanford و Harvard + خدع الحفظ)

· المنظور الأكاديمي المتقدم: في مساقات هندسة قواعد البيانات بجامعتي Stanford (CS145) و MIT (6.830)، يُنظر إلى هذا التفريق بين Business Rule و Constraint على أنه "الانتقال من السياسة الإدارية إلى البرمجة المقيدة" (From Business Policy to Schema Constraints)؛ فقاعدة العمل تصف منطق الشركة، بينما القيد يتحول مباشرة إلى أوامر في لغة SQL (مثل قيد CHECK لحصر الاختيار في الأنواع الثلاثة، وقيد TRIGGER لمنع تحديث عمود نوع العضوية).
· خدع سريعة للحفظ والتدوين (Memory Tricks):
  · كيف تفرقين بين Business Rule و Constraint في الامتحان؟
    · Business Rule (قاعدة عمل): جملة تشرح السياسة أو المال (كلمات مفتاحية: pay fees, free, incur a fee).
    · Constraint (قيد): جملة تضع حدوداً أو ممنوعات (كلمات مفتاحية: one of the three, cannot be changed).

7. Practice & Predicted Exam Questions (أسئلة متوقعة على الشريحة)

1. Multiple Choice (التمييز بين Business Rule و Constraint):
In the SunStar solution, how is the statement "Type of membership cannot be changed" classified?

· A) A database model
· B) A constraint
· C) A primary key
· الإجابة الصحيحة: B (تُصنف عبارة عدم إمكانية تغيير نوع العضوية كـ قيد Constraint).

2. Multiple Choice (تصنيف القواعد):
Which of the following statements from the SunStar case scenario is classified as a "Business Rule" rather than a "Constraint"?

· A) Members can belong to one of the three types of membership (gold, silver, or bronze).
· B) Type of membership cannot be changed.
· C) Bronze membership is free. Silver and gold memberships incur a fee.
· الإجابة الصحيحة: C (الخياران A و B هما قيدان Constraints، بينما الخيار C هو قاعدة عمل Business Rule).

3. Matching / Classification Question (سؤال تصنيف متوقع):
Classify each statement as either a Business Rule or a Constraint:

· Members will pay membership fees. ➔ Business Rule
· Members can belong to one of the three types of membership (gold, silver, or bronze). ➔ Constraint
· Bronze membership is free. Silver and gold memberships incur a fee. ➔ Business Rule
· Type of membership cannot be changed. ➔ Constraint

---

ألف مبروك! أنهيتِ الآن تدوين شابتر 1 بالكامل (22 شريحة) في دفتركِ. هل تودين أن نعود الآن لإكمال شابتر 2 (من Slide 15: What Is a Conceptual Model? - Part 2) بنفس الطريقة المنظمة؟


