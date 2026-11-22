# Glossary — Introduction to Database


| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **Data** | داتا | بيانات | «Collected facts about a topic or item.» — حقائق مجمّعة عن موضوع أو عنصر |
| 2 | **Information** | إنفورميشن | معلومات | «The result of combining, comparing, and performing calculations on data.» — ناتج دمج ومقارنة وحساب البيانات |
| 3 | **Database** | داتابيس | قاعدة بيانات | «A centralized and structured set of data stored on a computer system» — توفر إمكانية الاسترجاع والإضافة والتعديل والحذف وتحويل البيانات إلى معلومات |
| 4 | **Redundant data** | ريداندنت داتا | بيانات مكررة | «Storing same information in more than one file.» — تخزين المعلومة نفسها في أكثر من ملف |
| 5 | **Sharing data** | شيرينج داتا | مشاركة البيانات | «More than one application uses the same data.» — أكثر من تطبيق يستخدم البيانات نفسها |
| 6 | **Relational database** | ريليشنال داتابيس | قاعدة بيانات علائقية | «Stores information in tables with rows and columns» — جداول مترابطة بعمود مشترك (common attribute) |
| 7 | **Table** | تيبل | جدول | «A collection of records.» — مجموعة من السجلات |
| 8 | **Row** | رو | صف | «Called a record (or instance).» — يُسمى سجل أو نسخة |
| 9 | **Record** | ريكورد | سجل | «A row is called a record (or instance).» — يمثّل عنصرًا واحدًا كاملًا |
| 10 | **Instance** | إنستنس | نسخة / حالة | مرادف لـ Record — «A row is called a record (or instance).» |
| 11 | **Column** | كولوم | عمود | «Referred to as a field (or attribute).» — يُسمى حقلًا أو خاصية |
| 12 | **Field** | فيلد | حقل | مرادف لـ Column — وحدة بيانات واحدة في الجدول |
| 13 | **Attribute** | أتريبيوت | خاصية | مرادف لـ Column — «A column is referred to as a field (or attribute).» |
| 14 | **Common attribute** | كومون أتريبيوت | خاصية مشتركة | «Tables are linked by a common attribute.» — العمود الذي يربط جدولين (مثل `CUSTOMER_ID`) |
| 15 | **DBMS** (Database Management System) | دي بي إم إس (داتابيس مانجمنت سيستم) | نظام إدارة قواعد البيانات | «Software that controls the storage, organization, and retrieval of data.» — برنامج يتحكم في تخزين وتنظيم واسترجاع البيانات |
| 16 | **Memory and Storage Management** | ميموري آند ستوريج مانجمنت | إدارة الذاكرة والتخزين | أحد عناصر الـ DBMS الثلاثة — إدارة مكان وطريقة حفظ البيانات |
| 17 | **Data Dictionary** | داتا ديكشنري | قاموس البيانات | أحد عناصر الـ DBMS الثلاثة — كتالوج يوصف بنية البيانات (metadata) |
| 18 | **Query Language** | كويري لانجواج | لغة الاستعلامات | أحد عناصر الـ DBMS الثلاثة — الوسيلة للاستعلام عن البيانات |
| 19 | **Database model** | داتابيس مودل | نموذج قاعدة بيانات | الطريقة التي تُنظَّم بها البيانات (خمسة أنواع في السلايدز) |
| 20 | **Flat File Model** | فلات فايل مودل | نموذج الملف المسطح | «A database designed around a single table» — جدول واحد فقط، كل سطر فيه سجل، والحقول مفصولة بـ delimiters |
| 21 | **Delimiters** | ديليميترز | فواصل | «The fields in the record are separated with delimiters, such as tabs and commas.» — علامات تفصل بين الحقول |
| 22 | **Plain-text form** | بلين تكست فورم | صيغة نصية بسيطة | «Generally in plain-text form, where each line holds only one record.» — كل سطر = سجل واحد |
| 23 | **Hierarchical Model** | هايراركيكال مودل | نموذج هرمي | «Data is organized in a tree-like structure» — السجلات متصلة بـ links، كل سجل له أب واحد |
| 24 | **Tree-like structure** | تري لايك ستراكتشر | هيكل شجري | «Data is stored as records connected through links» — عقدة جذر وفروع تحتها |
| 25 | **Links** | لينكس | روابط | «Records that are connected to one another through links.» — الروابط التي تصل السجلات ببعضها |
| 26 | **Network Model** | نيتورك مودل | نموذج شبكي | البيانات في شكل شبكة، السجل يمكن أن يكون له أكثر من أب (السلايد يعرضه كصورة) |
| 27 | **Object-Oriented Model** | أوبجكت أورينتيد مودل | نموذج كائني التوجه | «An entity is modeled as an object» — الكيان يُنمذَج ككائن له state و behavior، وكل object ينتمي لـ class واحدة، ويُشتق subclass من superclass |
| 28 | **Entity** | إنتبتي | كيان | «A entity is modeled as an object» — شيء له وجود مستقل في عالم الأعمال |
| 29 | **Object** | أوبجكت | كائن | «Modeled as an object» — له state و behavior |
| 30 | **State** | ستيت | حالة | «The set of values for the attributes of the object.» — قيم الخصائص في لحظة معينة |
| 31 | **Behavior** | بيهيفيور | سلوك | «The set of methods that operate on the state of the object.» — العمليات التي تعمل على الحالة |
| 32 | **Class** | كلاس | صنف | «An object must belong to only one class as an instance of that class.» — كل كائن ينتمي لصنف واحد فقط |
| 33 | **Subclass** | ساب كلاس | صنف فرعي | «A new class derived from an existing class» — صنف مشتق من صنف آخر |
| 34 | **Superclass** | سوبر كلاس | صنف أب | «An existing class from which a new class is derived» — الصنف الأصل الذي يُشتق منه |
| 35 | **Relational Model** | ريليشنال مودل | نموذج علائقي | البيانات في جداول مترابطة بعمود مشترك — الأساس لـ Oracle (السلايد يعرضه كصورة) |
| 36 | **Business Information Requirements** | بيزنس إنفورميشن ريكوايرمنتس | متطلبات معلومات العمل | أعلى الهرم في عملية التطوير — ما تحتاجه الشركة من النظام |
| 37 | **Conceptual Data Modeling** | كونسبتوال داتا مودلينج | النمذجة المفاهيمية للبيانات | مرحلة Strategy & Analysis — تحويل المتطلبات إلى كيانات وعلاقات (ERD) |
| 38 | **Database Design** | داتابيس ديزاين | تصميم قاعدة البيانات | مرحلة Design — تحويل النموذج المفاهيمي إلى جداول ومفاتيح وقيود |
| 39 | **Database Build** | داتابيس بيلد | بناء قاعدة البيانات | مرحلة Build — تنفيذ التصميم فعليًا لإنتاج قاعدة البيانات |
