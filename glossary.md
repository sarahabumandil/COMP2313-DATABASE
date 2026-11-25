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

# Glossary — Relational Database (Chapter 2)


| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **Single Table** | سينجل تيبل | جدول واحد | «A flat file database is a type of database that stores data in a single table.» — كل البيانات في جدول واحد فقط |
| 2 | **Flat file database** | فلات فايل داتابيس | قاعدة بيانات ملف مسطح | «Generally in plain-text form, where each line holds only one record.» — كل سطر يحمل سجلًا واحدًا فقط |
| 3 | **Plain-text form** | بلين تكست فورم | صيغة نصية بسيطة | الصيغة العامة للـ flat file — نص عادي بلا بنية معقدة |
| 4 | **Record** | ريكورد | سجل | سطر واحد كامل في الجدول يمثّل عنصرًا واحدًا |
| 5 | **Repetition of values** | ريبِتيشن أوف فالويز | تكرار القيم | «There is a repetition of values.» — نفس القيمة (مثل `AD0003`) تتكرر في أكثر من سجل |
| 6 | **Data inconsistency** | داتا إنكونسيستنسي | عدم اتساق البيانات | عيب من عيوب الـ flat file — نفس المعلومة تظهر بقيم مختلفة في أماكن مختلفة |
| 7 | **Data redundancy** | داتا ريداندنسي | تكرار البيانات | عيب من عيوب الـ flat file — تخزين المعلومة نفسها أكثر من مرة |
| 8 | **Less security** | ليس سيكيوريتي | أمان أقل | عيب من عيوب الـ flat file — حماية ضعيفة للبيانات |
| 9 | **Cumbersome sharing of information** | كامبِرسَم شيرينج | مشاركة معلومات مرهقة/صعبة | عيب من عيوب الـ flat file — صعوبة مشاركة المعلومات بين التطبيقات |
| 10 | **Slow for huge databases** | سلو فور هيوج داتابيسز | بطيء لقواعد البيانات الضخمة | عيب من عيوب الـ flat file — الأداء ينهار مع كبر حجم البيانات |
| 11 | **Easy to understand / implement / extract** | إيزي تو أندرستاند / إمبلمنت / إكستركت | سهل الفهم / التنفيذ / الاستخراج | مزايا من مزايا الـ flat file |
| 12 | **Less hardware and software requirements** | ليس هاردوير آند سوفتوير ريكوايرمنتس | متطلبات عتاد وبرمجيات أقل | ميزة من مزايا الـ flat file |
| 13 | **Relational database** | ريليشنال داتابيس | قاعدة بيانات علائقية | «Presents information in tables with rows and columns.» — كل عمود نوع معلومة، وكل صف سجل واحد، والجداول مترابطة بعمود مشترك |
| 14 | **Column** | كولوم | عمود | «Represents a particular type of information (a field).» — نوع واحد من المعلومات |
| 15 | **Field** | فيلد | حقل | «The one value found at the intersection of a row and column.» — القيمة الواحدة عند تقاطع صف وعمود |
| 16 | **Row** | رو | صف | «Lists one record.» — يسرد سجلًا واحدًا |
| 17 | **Common field** | كومون فيلد | حقل مشترك | «The tables are then related to one another by using a common field.» — الحقل الذي يربط جدولين |
| 18 | **Key** | كي | مفتاح | «A unique field called a key is used to identify each record.» — حقل فريد يميّز كل سجل |
| 19 | **Unique field** | يونيك فيلد | حقل فريد | حقل لا تتكرر قيمه داخل الجدول |
| 20 | **Primary Key** | برايمري كي | مفتاح أساسي | «The unique identifier for each row» — عمود يميّز كل صف تمييزًا فريدًا |
| 21 | **Foreign Key** | فورين كي | مفتاح أجنبي | «A column that refers to a primary key column in another table» — عمود يشير لمفتاح أساسي في جدول آخر |
| 22 | **Unique Key** | يونيك كي | مفتاح فريد | مفتاح لا تتكرر قيمه — يميّز الصف لكنه ليس بالضرورة الـ primary key (مثل `PAYROLL_ID` في سلايد 10) |
| 23 | **Relationship** | ريليشنشيب | علاقة | «A PRIMARY_KEY column in one table is designated as a FOREIGN_KEY column in a related table to form a relationship.» — الربط بين جدولين عبر مفتاح أساسي/أجنبي |
| 24 | **Relational Tables** | ريليشنال تيبِلز | جداول علائقية | «A table is a simple structure where data is organized and stored.» — بنية بسيطة لتنظيم وتخزين البيانات |
| 25 | **Table** | تيبل | جدول | «A basic storage structure.» — بنية التخزين الأساسية |
| 26 | **Distinct table name** | ديستنكت تيبل نيم | اسم جدول مميز | قاعدة: «Each table has a distinct name.» — كل جدول له اسم مميز لا يتكرر |
| 27 | **Unique column name** | يونيك كولوم نيم | اسم عمود فريد | قاعدة: «Each column in a table has a unique name.» — كل عمود داخل الجدول له اسم فريد |
| 28 | **Single values** | سينجل فاليوز | قيم مفردة | قاعدة: «Entries in columns are single values.» — كل خلية تحوي قيمة واحدة فقط (لا قوائم) |
| 29 | **Same kind** | سيم كايند | نفس النوع | قاعدة: «Entries in columns are of the same kind.» — كل القيم في العمود من نوع واحد |
| 30 | **Insignificant order** | إنسيجنيفيكانت أوردر | ترتيب غير مهم | قاعدة: «Order of rows and columns is insignificant.» — ترتيب الصفوف والأعمدة لا يؤثر |
| 31 | **Less redundancy** | ليس ريداندنسي | تكرار أقل | ميزة من مزايا الـ relational database مقارنة بالـ flat file |
| 32 | **Avoidance of inconsistency** | أفويدنس أوف إنكونسيستنسي | تجنّب عدم الاتساق | ميزة من مزايا الـ relational database |
| 33 | **Efficiency** | إفيشنسي | كفاءة | ميزة من مزايا الـ relational database |
| 34 | **Data integrity** | داتا إنتجريتي | سلامة/تكامل البيانات | ميزة من مزايا الـ relational database — البيانات صحيحة ومتسقة |
| 35 | **Confidentiality** | كونفيدنشياليتي | سرية | ميزة من مزايا الـ relational database — التحكم في من يرى ماذا |
| 36 | **Conceptual Model** | كونسبتوال مودل | نموذج مفاهيمي | «Captures the functional and informational needs of a business.» — يلتقط احتياجات العمل دون الدخول في التنفيذ |
| 37 | **Functional needs** | فانكشنال نيدز | احتياجات وظيفية | ما يجب أن يفعله النظام (العمليات) |
| 38 | **Informational needs** | إنفورميشنال نيدز | احتياجات معلوماتية | ما يجب أن يعرفه النظام (البيانات) |
| 39 | **Entity (conceptual)** | إنتبتي | كيان | «Objects that become tables in database.» — أشياء تتحول لجداول في قاعدة البيانات |
| 40 | **Relationships among entities** | ريليشنشيبس أمونج إنتبتيز | العلاقات بين الكيانات | «Identifies relationships among entities.» — يحدد كيف ترتبط الكيانات ببعضها |
| 41 | **Attributes** | أتريبيوتس | خصائص | «Objects that become columns or fields in database.» — تتحول لأعمدة في قاعدة البيانات (لا تُحدَّد في الـ conceptual model) |
| 42 | **Unique Identifiers (UID)** | يونيك أيدنتيفايرز | معرّفات فريدة | «Attribute that becomes primary key in database.» — خاصية تتحول لمفتاح أساسي |
| 43 | **Business Information Requirements** | بيزنس إنفورميشن ريكوايرمنتس | متطلبات معلومات العمل | أعلى الهرم في عملية التطوير — ما تحتاجه الشركة من النظام |
| 44 | **Conceptual Data Modeling** | كونسبتوال داتا مودلينج | النمذجة المفاهيمية للبيانات | مرحلة Strategy & Analysis — تحويل المتطلبات إلى كيانات وعلاقات |
| 45 | **Database Design** | داتابيس ديزاين | تصميم قاعدة البيانات | مرحلة Design — تحويل النموذج المفاهيمي إلى جداول ومفاتيح |
| 46 | **Database Build** | داتابيس بيلد | بناء قاعدة البيانات | مرحلة Build — تنفيذ التصميم فعليًا لإنتاج قاعدة البيانات |
| 47 | **Database Administrators (DBA)** | داتابيس أدمينيستريتورز | مديرو قواعد البيانات | «The conceptual model can be used for further discussion between designers, database administrators, and application developers.» — أحد أطراف الحوار حول النموذج المفاهيمي |
| 48 | **Application Developers** | أبليكيشن ديفيلوبرز | مطورو التطبيقات | أحد أطراف الحوار حول النموذج المفاهيمي — يبنون التطبيقات فوق قاعدة البيانات |
| 49 | **Logical Model** | لوجيكال مودل | نموذج منطقي | «Includes all entities and relationships among them» — يشمل كل الكيانات والعلاقات، ويُسمى Entity Relationship Model (ERM) ويُرسَم كـ ERD |
| 50 | **Entity Relationship Model (ERM)** | إنتبتي ريليشنشيب مودل | نموذج العلاقات بين الكيانات | اسم آخر للنموذج المنطقي — «Is called an entity relationship model (ERM).» |
| 51 | **ERD** (Entity Relationship Diagram) | إي آر دي | مخطط العلاقات بين الكيانات | «Is illustrated in an ERD.» — الرسم التوضيحي للنموذج المنطقي |
| 52 | **Attribute optionality** | أتريبيوت أوبشناليتي | اختيارية الخاصية | «Determines attribute optionality.» — هل الخاصية إلزامية أم اختيارية |
| 53 | **Relationship optionality** | ريليشنشيب أوبشناليتي | اختيارية العلاقة | «Determines relationship optionality.» — هل العلاقة إلزامية أم اختيارية |
| 54 | **Cardinality** | كارديناليتي | عددية العلاقة | «Determines relationship cardinality.» — هل الطرف الآخر واحد أم أكثر |
| 55 | **Physical Model** | فيزيكال مودل | نموذج فيزيائي | «Is an extension to a logical data model» — يمتد النموذج المنطقي ليصف التنفيذ الفعلي |
| 56 | **Table definitions** | تيبل ديفينيشِنز | تعريفات الجداول | «Defines table definitions, data types, and precision.» — تحديد بنية الجدول وأنواع البيانات ودقتها |
| 57 | **Data types** | داتا تايبس | أنواع البيانات | تحديد نوع كل عمود (NUMBER, VARCHAR2, DATE...) |
| 58 | **Precision** | بريسيجن | دقة / عدد الخانات | تحديد طول/دقة القيم الرقمية |
| 59 | **Views** | فيوز | عروض | «Identifies views, indexes, and other database objects.» — كائنات قاعدة بيانات تُحدَّد في النموذج الفيزيائي |
| 60 | **Indexes** | إنديكسيز | فهارس | كائنات تُحدَّد في النموذج الفيزيائي لتسريع الاستعلامات |
| 61 | **Other database objects** | أذر داتابيس أوبجكتس | كائنات قاعدة بيانات أخرى | كائنات إضافية (sequences, synonyms, ...) تُعرَّف في النموذج الفيزيائي |
| 62 | **Columns / Primary keys / Foreign keys (physical)** | كولومز / برايمري كيز / فورين كيز | الأعمدة / المفاتيح الأساسية / الأجنبية | «Shows all table structures, including columns, primary keys, and foreign keys.» — النموذج الفيزيائي يعرض كل بنية الجدول صراحة |


# Glossary — Identifying Relationships (Chapter 3)



| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **Relationship** | ريليشنشيب | علاقة | «A bidirectional, significant association between two entities or between an entity and itself.» — رابطة ذات اتجاهين وذات معنى بين كيانين أو بين كيان ونفسه |
| 2 | **Bidirectional** | بايدايركشنال | ثنائي الاتجاه | «Are bi-directional» — العلاقة تُقرأ من الطرفين، ولكل طرف اسم يصف الطرف الآخر |
| 3 | **Significant** | سيجنيفيكانت | ذو significance / مهم | «Represent something of significance or importance to the business.» — تمثّل شيئًا مهمًا للعمل وليس مجرد ربط شكلي |
| 4 | **Named at both ends** | نيمد آت بوث إندز | مُسمّاة من الطرفين | «Are named at both ends» — كل طرف من العلاقة له اسم (مثل `contain` / `assigned to` في مثال DEPARTMENT–EMPLOYEE) |
| 5 | **Entity** | إنتبتي | كيان | «Exist only between entities (or one entity and itself)» — العلاقات لا توجد إلا بين الكيانات أو بين الكيان ونفسه |
| 6 | **Association** | أسوسييشن | ارتباط | «Relationships represents an association between two or more entities.» — العلاقة تمثّل ارتباطًا بين كيانين أو أكثر |
| 7 | **Optionality** | أوبشناليتي | اختيارية العلاقة | «Relationships are either mandatory or optional.» — «Whether the relationship must exist» — هل يجب أن توجد العلاقة أم لا |
| 8 | **Mandatory** | مانداتوري | إلزامي | «At least one matching record in each entity» — يجب أن يوجد سجل مطابق على الأقل |
| 9 | **Optional** | أوبشنال | اختياري | «Zero matching records» — يمكن ألا يوجد أي سجل مطابق |
| 10 | **Must every employee have a job?** | ماست إيفري إمبلوي هاف أ جوب | هل يجب أن يكون لكل موظف وظيفة؟ | السؤال الأول لتحديد الـ optionality في مثال EMPLOYEE–JOB |
| 11 | **Must every job be assigned to an employee?** | ماست إيفري جوب بي أسايند | هل يجب أن تُسند كل وظيفة لموظف؟ | السؤال الثاني لتحديد الـ optionality — السؤالان معًا يحددان طبيعة العلاقة من الطرفين |
| 12 | **Cardinality** | كارديناليتي | عددية العلاقة | «Measures the quantity of something» — «Determines the degree to which one entity is related to another by answering the question 'How many?'» — تحدد عدد الأطراف المرتبطة |
| 13 | **Quantity** | كوانتيتي | كمية | «Cardinality measures the quantity of something.» — ما تقيسه الكارديناليتي |
| 14 | **"How many?"** | هاو ماني | كم؟ | السؤال الذي تجيب عليه الكارديناليتي (وليس الـ optionality) |
| 15 | **Singular or plural** | سينجولار أور بلورال | مفرد أم جمع | «The cardinality of a relationship only answers whether the number is singular or plural; it does not answer with a specific plural number.» — الكارديناليتي لا تعطي عددًا محددًا، فقط مفرد أو جمع |
| 16 | **One and only one** | ون آند أونلي ون | واحد فقط لا غير | «Line: Use 'one and only one'» — تعبير الكارديناليتي للطرف المفرد |
| 17 | **One or more** | ون أور مور | واحد أو أكثر | «Crow's feet: Use 'one or more'» — تعبير الكارديناليتي للطرف المتعدد |
| 18 | **Must / Must be** | ماست / ماست بي | يجب / يجب أن يكون | «Mandatory: Use 'must be' or 'must'» — الصياغة اللفظية للـ mandatory |
| 19 | **May / May be** | مي / مي بي | يمكن / يمكن أن يكون | «Optional: Use 'may be' or 'may'» — الصياغة اللفظية للـ optional |
| 20 | **Solid line** | سوليد لاين | خط متصل | «The relationship line on the diagram is either solid (mandatory)» — الخط المتصل يعني إلزامي |
| 21 | **Dashed line** | داشد لاين | خط متقطع | «Or dashed (optional)» — الخط المتقطع يعني اختياري |
| 22 | **Single toe** | سينجل تو | نهاية بإصبع واحد | «Single toe (one instance)» — نهاية الخط على شكل مفرد تعني «واحد فقط» |
| 23 | **Crow's foot** | كروز فوت | قدم الغراب | «Crow's foot (one or more instance)» — نهاية الخط متفرعة كقدم الغراب تعني «واحد أو أكثر» |
| 24 | **Relationship name** | ريليشنشيب نيم | اسم العلاقة | «The label that appears close to the entity it is assigned to. Make sure that all relationship names are in lowercase» — اسم مكتوب بحروف صغيرة قرب الكيان |
| 25 | **Matching record** | ماتشينج ريكورد | سجل مطابق | السجل في الطرف الآخر الذي يطابق العلاقة — عدد السجلات المطابقة هو ما يحدد optionality |
| 26 | **Zero matching records** | زيرو ماتشينج ريكوردز | صفر سجلات مطابقة | تعريف الـ Optional — يمكن ألا يوجد أي سجل مطابق |
| 27 | **At least one matching record** | آت ليست ون ماتشينج ريكورد | سجل مطابق واحد على الأقل | تعريف الـ Mandatory — يجب وجود سجل مطابق واحد على الأقل |
| 28 | **Minimum and maximum** | مينيمم آند ماكسيمم | الحد الأدنى والأقصى | «The minimum and maximum number of values in the relationship» — ما تعبّر عنه الكارديناليتي |
| 29 | **Business rule** | بيزنس رول | قاعدة عمل | الجملة التي تصف العلاقة بين كيانين — تُقرأ وتُترجم إلى رسم |
| 30 | **Business rule syntax** | بيزنس رول سينتاكس | صيغة قاعدة العمل | «Each entity1 {must be or may be} relationship name {one or more or one and only one} entity2.» — الصيغة القياسية لكتابة قاعدة العلاقة |
| 31 | **Recursive / Self relationship** | ريكيرسيف / سيلف ريليشنشيب | علاقة ذاتية | «A relationship can join one entity to itself.» — علاقة تربط الكيان بنفسه (مثل EMPLOYEE يدير EMPLOYEE) |
| 32 | **Unary relationship** | يوناري ريليشنشيب | علاقة أحادية | مصطلح مرادف للعلاقة الذاتية — طرف واحد متكرر (غير مذكور صراحة في السلايد لكنه مفهوم من مثال الموظف/المدير) |
| 33 | **Business Scenario** | بيزنس سيناريو | سيناريو عمل | وصف نصي لحالة أعمال حقيقية (مطعم / شركة) لاستخراج العلاقات منه |
| 34 | **Customer** | كاستمر | عميل | في السيناريو 1: يقدّم طلبًا لنفسه أو لغيره، ويدفع، ويمكنه تقديم طلبات كثيرة |
| 35 | **Order** | أوردر | طلب | في السيناريو 1: يُقدَّم من عميل واحد فقط — لكل طلب عميل واحد لا غير |
| 36 | **Places** | بليسز | يقدّم | «A customer walks up to the counter and places their order» — الفعل الذي يصف العلاقة بين CUSTOMER وORDER |
| 37 | **Manager** | مانجر | مدير | في السيناريو 2: موظف يدير موظفين آخرين — «Each manager can manage several employees» |
| 38 | **Managing director** | مانجينج دايركتور | المدير التنفيذي | «Every employee has one manager, including the managing director who manages him/herself» — يدير نفسه، وهو ما يجعل العلاقة الذاتية ممكنة |
| 39 | **Employee** | إمبلوي | موظف | في السيناريو 2: الكيانان هما EMPLOYEE وEMPLOYEE — «Since managers are also employees, both are listed in the same entity» |
| 40 | **One-to-one** | ون تو ون | واحد لواحد | علاقة فيها الطرفان «one and only one» (مفهومة من Crow's foot notation — غير مذكورة بالاسم في السلايد) |
| 41 | **One-to-many** | ون تو ماني | واحد لمتعدد | علاقة طرفها الأول «one and only one» والثاني «one or more» — مثال CUSTOMER–ORDER |
| 42 | **Many-to-one** | ماني تو ون | متعدد لواحد | عكس One-to-many — مثال ORDER–CUSTOMER |
| 43 | **ERD** (Entity Relationship Diagram) | إي آر دي | مخطط العلاقات بين الكيانات | الرسم الذي تظهر فيه الكيانات والعلاقات مع الرموز (خط متصل/متقطع + إصبع/قدم غراب) |
| 44 | **Component of a relationship** | كومبوننت أوف أ ريليشنشيب | مكوّن من مكونات العلاقة | المكونات الثلاثة: Name · Cardinality · Optionality |
| 45 | **Read the sentence** | ريد ذا سينتنس | قراءة الجملة | الطريقة التي تُقرأ بها قاعدة العمل: «Each entity1 must be/may be relationship name one and only one/one or more entity2» |

# Glossary — Supertypes and Subtypes (Chapter 4)



| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **Supertype** | سوبر تايب | النوع الأعلى / الكيان الأعلى | «An entity that is constructed with attributes that will be common to all of the subtypes related to it» — كيان يحمل الخصائص المشتركة لكل الأنواع الفرعية المرتبطة به |
| 2 | **Subtype** | ساب تايب | النوع الفرعي / الكيان الفرعي | «An entity that is based on a supertype, but is different from the supertype because of its specialized attributes and purpose» — كيان مبني على النوع الأعلى لكنه يختلف عنه بخصائصه المتخصصة وغرضه |
| 3 | **Specialization** | سبشيالايزيشن | تخصيص | «Each subtype is a specialization of a supertype» — كل نوع فرعي هو تخصيص للنوع الأعلى |
| 4 | **Inherited / Inherit** | إنهيريتد / إنهيريت | يُورَث / يُشتقّ | «They are inherited in every subtype» — «Subtypes inherit all attributes and relationships of the supertype entity» — الأنواع الفرعية ترث كل خصائص وعلاقات النوع الأعلى |
| 5 | **Common attributes** | كومون أتريبيوتس | خصائص مشتركة | «The common attributes and relationships for all subtypes must be listed only in the supertype» — تُكتب في النوع الأعلى فقط ولا تتكرر في الفرعية |
| 6 | **Specialized attributes** | سبشيالايزد أتريبيوتس | خصائص متخصصة | «Different from the supertype because of its specialized attributes and purpose» — خصائص توجد في نوع فرعي فقط ولا توجد في غيره |
| 7 | **Special properties** | سبشيال بروبرتيز | خصائص خاصة | «A group of instances has special properties, such as attributes or relationships that exist only for that group.» — سبب اللجوء إلى تقسيم الكيان |
| 8 | **Subdivide an entity** | سابديفايد آن إنتبتي | تقسيم الكيان | «Sometimes it makes sense to subdivide an entity into subtypes.» — تحويل الكيان إلى نوع أعلى + أنواع فرعية |
| 9 | **Enclosed within an entity** | إنكلوزد ويذين آن إنتبتي | مُحاط داخل كيان | «Each subtype is a specialization of a supertype and therefore must be enclosed within an entity.» — الأنواع الفرعية تُرسَم داخل حدود النوع الأعلى |
| 10 | **Supertype level** | سوبر تايب ليفل | مستوى النوع الأعلى | «These common attributes are listed at the supertype level.» — مكان كتابة الخصائص المشتركة |
| 11 | **Exhaustive** | إجزهوستيف | شامل / مستوفي | «Make sure that your subtypes are exhaustive — that you are handling every instance of the supertype.» — تغطية كل الحالات الممكنة |
| 12 | **Mutually exclusive** | ميوتشوالي إكسكلوسيف | متنافي / متباين | مصطلح من Terminology — الكيانات الفرعية لا تتداخل: النسخة الواحدة تنتمي لنوع فرعي واحد فقط |
| 13 | **Finitely exclusive** | فاينتلي إكسكلوسيف | محدود التباين | «Only some subtypes? (finitely exclusive)» — صياغة السؤال الثالث لتحديد صحة الأنواع الفرعية |
| 14 | **OTHER subtype** | أذر ساب تايب | النوع الفرعي «أخرى» | «It is good practice to include an OTHER subtype to make sure that your subtypes are exhaustive» — يضمن الشمولية ويلتقط الحالات غير المتوقعة |
| 15 | **Nested subtypes** | نيستد ساب تايبس | أنواع فرعية متداخلة | «You can nest subtypes.» — أنواع فرعية داخل أنواع فرعية (مثال: ANIMAL → VERTEBRATE → BIRD/REPTILE/MAMMAL) |
| 16 | **Readability** | ريدابيليتي | سهولة القراءة | «For ease of reading — 'readability' — you would usually show subtypes with only two levels, but there is no rule that would stop you from going beyond two levels.» |
| 17 | **Two levels** | تو ليفلز | مستويان | «You would usually show subtypes with only two levels» — المستوى الموصى به في الرسم |
| 18 | **Only one subtype (rule)** | أونلي ون ساب تايب | نوع فرعي واحد فقط | «There can never be just one subtype; another subtype should be created to contain the rest.» — قاعدة التصميم |
| 19 | **Choices** | تشويسز | خيارات | «You can typically associate 'choices' of something with supertypes and subtypes.» — مثل طريقة الدفع أو نوع التغليف |
| 20 | **Instances** | إنستنسيز | نسخ / حالات | «Often some instances of an entity have attributes and/or relationships that other instances do not have.» — سبب وجود الأنواع الفرعية |
| 21 | **Three questions (for identifying subtypes)** | ثري كويستشنز | الأسئلة الثلاثة | الأسئلة الثلاثة لاختبار صحة النوع الفرعي: (1) Is this subtype a kind of supertype? (2) Have I covered all possible cases? (exhaustive) (3) Only some subtypes? (finitely exclusive) |
| 22 | **"A kind of" test** | أ كايند أوف تست | اختبار «هو نوع من» | «Is this subtype a kind of supertype?» — السؤال الأول؛ مثال: QUIZ هو نوع من EXAM |
| 23 | **Conceptual modeling stage** | كونسبتوال مودلينج ستيج | مرحلة النمذجة المفاهيمية | «At the conceptual modeling stage, it is good practice to include an OTHER subtype» — المرحلة التي تُطبَّق فيها قاعدة OTHER |
| 24 | **Entity** | إنتبتي | كيان | «An entity that is constructed with attributes...» — وحدة النمذجة التي يُبنى عليها الـ supertype والـ subtype |
| 25 | **Attributes** | أتريبيوتس | خصائص | «Attributes that will be common to all of the subtypes related to it» — ما يُكتب في النوع الأعلى |
| 26 | **Relationships** | ريليشنشيبس | علاقات | «Subtypes inherit all attributes and relationships of the supertype entity» — العلاقات تُورَث أيضًا |
| 27 | **Purpose** | بيربوز | غرض | «Different from the supertype because of its specialized attributes and purpose» — الغرض المختلف هو ما يميّز النوع الفرعي |
| 28 | **PAYMENT** | بايمنت | الدفع | مثال السلايد: النوع الأعلى بأنواعه CASH / CHECK / CREDIT CARD |
| 29 | **CASH / CHECK / CREDIT CARD** | كاش / تشيك / كريديت كارد | نقد / شيك / بطاقة ائتمان | الأنواع الفرعية الثلاثة لكيان PAYMENT |
| 30 | **Card number** | كارد نمبر | رقم البطاقة | «But only credit cards would have a 'card number' attribute.» — مثال على خاصية متخصصة |
| 31 | **Payment date / Payment amount** | بايمنت ديت / بايمنت أمونت | تاريخ الدفع / مبلغ الدفع | «All payments have some common attributes: payment date, payment amount, and so on.» — أمثلة على الخصائص المشتركة |
| 32 | **Single PAYMENT entity vs three separate entities** | سينجل بايمنت إنتبتي فيرسِس ثري سيبِريت إنتبتيز | كيان واحد أم ثلاثة كيانات | «Should we create a single PAYMENT entity or three separate entities CASH, CHECK, and CREDIT CARD?» — سؤال التصميم الذي يبرر supertype/subtype |
| 33 | **Fourth method of payment** | فورث ميثود أوف بايمنت | طريقة الدفع الرابعة | «What happens if in the future we introduce a fourth method of payment?» — تحدي التوسّع المستقبلي |
| 34 | **EXAM** | إجزام | اختبار | Supertype لـ QUIZ / MIDTERM / FINAL — «EXAM is a supertype of QUIZ, MIDTERM, and FINAL.» |
| 35 | **QUIZ / MIDTERM / FINAL** | كويز / ميدتيرم / فاينال | كويز / اختبار نصفي / اختبار نهائي | الأنواع الفرعية لكيان EXAM |
| 36 | **EXAM common attributes** | إجزام كومون أتريبيوتس | خصائص EXAM المشتركة | «# number, * description, * weight, * date, * grade for written component» — تُكتب في النوع الأعلى فقط |
| 37 | **EXAM specialized attributes** | إجزام سبشيالايزد أتريبيوتس | خصائص EXAM المتخصصة | MIDTERM له «grade for oral presentation»، وFINAL له «extra points for optional paper» — خصائص خاصة بكل نوع فرعي |
| 38 | **WALLCOVERING** | وول كافرينج | تغطية الجدران | Supertype لـ PAINT / WALLPAPER / FABRIC / OTHER |
| 39 | **PAINT / WALLPAPER / FABRIC** | بينت / وول بيبر / فابريك | طلاء / ورق جدران / قماش | الأنواع الفرعية لكيان WALLCOVERING |
| 40 | **SNOWSPORT** | سنو سبورت | رياضة الثلج | Supertype لـ SKI / SNOWBOARD / CROSS COUNTRY / OTHER |
| 41 | **SKI / SNOWBOARD / CROSS COUNTRY** | سكي / سنوبورد / كروس كانتري | تزلج / تزلج بلوحة / تزلج ريفي | الأنواع الفرعية لكيان SNOWSPORT |
| 42 | **ANIMAL** | أنيمال | حيوان | Supertype لـ VERTEBRATE / INVERTEBRATE — مثال على الأنواع الفرعية المتداخلة |
| 43 | **VERTEBRATE / INVERTEBRATE** | فيرتيبريت / إنفيرتيبريت | فقاري / لافقاري | الأنواع الفرعية لكيان ANIMAL |
| 44 | **BIRD / REPTILE / MAMMAL / OTHER** | بيرد / ريبتايل / مامال / أذر | طائر / زاحف / ثديي / أخرى | أنواع فرعية متداخلة داخل VERTEBRATE (المستوى الثاني) |
| 45 | **Food order types** | فود أوردر تايبس | أنواع طلبات الطعام | «food order types (eat in, to go)» — مثال واقعي على supertype/subtype |
| 46 | **Eat in / To go** | إيت إن / تو جو | داخل المطعم / سفري | نوعان فرعيان لطلبات الطعام |
| 47 | **Grocery bag types** | جروسري باج تايبس | أنواع أكياس البقالة | «grocery bag types (paper, plastic)» — مثال واقعي |
| 48 | **Paper / Plastic** | بيبر / بلاستيك | ورقي / بلاستيكي | نوعان فرعيان لأكياس البقالة |
| 49 | **Payment types** | بايمنت تايبس | أنواع الدفع | «payment types (check, cash, credit)» — مثال واقعي |
| 50 | **Common to all** | كومون تو أول | مشترك بين الجميع | «Attributes that will be common to all of the subtypes related to it» — شرط كتابة الخاصية في النوع الأعلى |

# Glossary — Relationship Transferability & Types (Chapter 5)

| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **Relationship Transferability** | ريليشنشيب ترانسفيرابيليتي | قابلية نقل العلاقة | خاصية تحدد هل يمكن نقل العلاقة من كيان إلى آخر بعد إنشائها أم لا — موضوع الفصل كاملًا |
| 2 | **Allocated** | ألوكيتد | مُخصَّص / مُسنَد | «Once a class has been allocated to a teacher, can that class later be transferred to another teacher?» — الحالة التي تكون فيها العلاقة قابلة للتحويل |
| 3 | **Transferred** | ترانسفيرد | منقول | «Can that class later be transferred to another teacher, possibly in mid-semester?» — نقل العلاقة من طرف لآخر |
| 4 | **Mid-semester** | ميد-سيميستر | منتصف الفصل الدراسي | مثال على أن النقل قد يحدث في أي وقت وليس فقط في البداية |
| 5 | **Business rule** | بيزنس رول | قاعدة عمل | «This business rule is normally determined by what is most efficient and most profitable for the club.» — القاعدة التي تحدد إن كانت العلاقة قابلة للنقل أم لا |
| 6 | **Efficient** | إفيشنت | فعّال / كفء | أحد المعيارين اللذين يحددان قابلية النقل |
| 7 | **Profitable** | بروفيتابل | مُربِح | المعيار الثاني — المنفعة المالية للعمل |
| 8 | **Transferable** | ترانسفيرابل | قابل للنقل | «A person may change departments or jobs within a company, so the relationship is transferable.» — العلاقة يمكن استبدال أحد طرفيها بطرف آخر |
| 9 | **Nontransferable** | نون-ترانسفيرابل | غير قابل للنقل | «Once the order is placed by someone, that relationship cannot change.» — العلاقة تُقفل بمجرد إنشائها |
| 10 | **EMPLOYEE–DEPARTMENT** | إمبلوي–ديبارتمنت | الموظف–القسم | المثال المرجعي في السلايد 5–7 لتوضيح Optionality ثم Cardinality ثم Transferability |
| 11 | **Assigned to** | أسايند تو | مُسنَد إلى | اسم العلاقة من جهة EMPLOYEE تجاه DEPARTMENT في مثال السلايد 5 |
| 12 | **Responsible for** | ريسبونسيبل فور | مسؤول عن | اسم العلاقة من جهة DEPARTMENT تجاه EMPLOYEE |
| 13 | **Optionality (review)** | أوبشناليتي (ريفيو) | اختيارية العلاقة | «Must every EMPLOYEE be assigned to a DEPARTMENT? Must every DEPARTMENT be responsible for an employee?» — إعادة مراجعة قبل تحديد Transferability |
| 14 | **Cardinality (review)** | كارديناليتي (ريفيو) | عددية العلاقة | «How many EMPLOYEEs can a DEPARTMENT be responsible for? How many DEPARTMENTs can an EMPLOYEE be assigned to?» — إعادة مراجعة |
| 15 | **Transferability question** | ترانسفيرابيليتي كويستشن | سؤال قابلية النقل | «Can an EMPLOYEE be transferred from one DEPARTMENT to another DEPARTMENT?» — السؤال الفاصل بين النوعين |
| 16 | **STUDENT–STUDY GROUP** | ستيودنت–ستادي جروب | الطالب–مجموعة الدراسة | مثال على علاقة **Transferable** — «A STUDENT being allowed to move from one STUDY GROUP to another.» |
| 17 | **Join** | جوين | ينضم | اسم العلاقة من جهة STUDENT تجاه STUDY GROUP |
| 18 | **Have** | هاف | يمتلك / يحتوي | اسم العلاقة من جهة STUDY GROUP تجاه STUDENT |
| 19 | **STUDENT–RECEIPT** | ستيودنت–ريسيبت | الطالب–الإيصال | مثال على علاقة **Nontransferable** — «Once a RECEIPT has been issued, it cannot be transferred to another STUDENT.» |
| 20 | **Receipt** | ريسيبت | إيصال | «A STUDENT can be issued a RECEIPT for paying tuition fees, taking a certification exam, or purchasing items at the bookstore.» |
| 21 | **Issued to** | إيشود تو | صادر إلى | اسم العلاقة من جهة RECEIPT تجاه STUDENT |
| 22 | **Issued** | إيشود | صادِر | اسم العلاقة من جهة STUDENT تجاه RECEIPT |
| 23 | **Diamond** | داياموند | معيّن (شكل) | «A nontransferable relationship is represented with the diamond on the relationship.» — الرمز الذي يميّز العلاقة غير القابلة للنقل على الـ ERD |
| 24 | **Cancelled** | كانسيلد | مُلغى | «If it was issued in error, it would have to be cancelled, and another RECEIPT would have to be written up.» — الحل الوحيد في العلاقة غير القابلة للنقل |
| 25 | **Written up** | ريتِن أب | يُحرَّر / يُصدَر من جديد | إصدار إيصال جديد بدلًا من الإيصال المُلغى |
| 26 | **One-to-Many (1:M)** | ون-تو-ماني | واحد إلى متعدد | «The various types of 1:M relationships are most common in an ER Model.» — النوع الأكثر شيوعًا |
| 27 | **Many-to-One (M:1)** | ماني-تو-ون | متعدد إلى واحد | الوجه الآخر للـ 1:M — نفس العلاقة تُقرأ من الطرف المقابل |
| 28 | **"Many"** | ماني | «متعدد» | «'Many' can mean one-or-more or zero-or-more, depending on the optionality.» — المتعدد يعتمد على الـ optionality |
| 29 | **One-or-more** | ون-أور-مور | واحد أو أكثر | معنى "Many" عندما تكون العلاقة **mandatory** على ذلك الطرف |
| 30 | **Zero-or-more** | زيرو-أور-مور | صفر أو أكثر | معنى "Many" عندما تكون العلاقة **optional** على ذلك الطرف |
| 31 | **Many-to-Many (M:M)** | ماني-تو-ماني | متعدد إلى متعدد | «The various types of M:M relationships are common, particularly in a first version of an ER model.» — شائعة في المسودة الأولى |
| 32 | **Resolved (M:M)** | ريزولفد | مُحلّ | «In later stages of the modeling process, all M:M relationships will be resolved, and disappear.» — تتحول إلى 1:M عبر كيان وسيط في المراحل المتقدمة |
| 33 | **One-to-One (1:1)** | ون-تو-ون | واحد إلى واحد | «Have cardinality of one and only one in both directions.» — الطرفان بنفس العددية |
| 34 | **Role** | رول | دور | «Mandatory at one end of the 1:1 relationship commonly occurs when roles are modeled.» — سبب ظهور 1:1 في الـ ERD |
| 35 | **Acting as** | أكتينج آز | يعمل بصفة | اسم العلاقة من جهة PERSON تجاه TEACHER أو STUDENT في مثال الأدوار |
| 36 | **Role of** | رول أوف | دور | اسم العلاقة من جهة TEACHER/STUDENT تجاه PERSON |
| 37 | **PERSON–TEACHER** | بيرسون–تيتشر | الشخص–المعلم | مثال على 1:1 ناتج عن نمذجة الأدوار |
| 38 | **PERSON–STUDENT** | بيرسون–ستيودنت | الشخص–الطالب | نفس المنطق — نفس PERSON قد يكون طالبًا ومعلمًا في نفس الوقت |
| 39 | **COMPUTER–MOTHERBOARD** | كومبيوتر–مَذر بورد | الحاسوب–اللوحة الأم | مثال على 1:1 صريح: «Each COMPUTER must contain one and only one MOTHERBOARD. Each MOTHERBOARD must be contained in one and only one COMPUTER.» |
| 40 | **Contain** | كونتاين | يحتوي | اسم العلاقة من جهة COMPUTER تجاه MOTHERBOARD |
| 41 | **Contained in** | كونتايند إن | محتوى داخل | اسم العلاقة من جهة MOTHERBOARD تجاه COMPUTER |
| 42 | **CUSTOMER–SALES REPRESENTATIVE** | كاستمر–سيلز ريبريزنتاتيف | العميل–مندوب المبيعات | مثال على 1:M مع Optionality: «Each CUSTOMER must be visited by one and only one SALES REPRESENTATIVE. Each SALES REPRESENTATIVE may be assigned to one or more CUSTOMERS.» |
| 43 | **Visited by** | فيزيتد باي | مُزار بواسطة | اسم العلاقة من جهة CUSTOMER تجاه SALES REPRESENTATIVE |
| 44 | **Assigned to (sales)** | أسايند تو | مُسنَد إلى | اسم العلاقة من جهة SALES REPRESENTATIVE تجاه CUSTOMER |
| 45 | **STUDENT–TEACHER** | ستيودنت–تيتشر | الطالب–المعلم | مثال على **M:M**: طالب واحد يتعلم من عدة معلمين، ومعلم واحد يعلّم عدة طلاب |
| 46 | **Learns from** | ليرنز فروم | يتعلم من | اسم العلاقة من جهة STUDENT تجاه TEACHER |
| 47 | **Educates** | إديوكيتس | يعلّم | اسم العلاقة من جهة TEACHER تجاه STUDENT |
| 48 | **PERSON–DVD** | بيرسون–دي في دي | الشخص–الأسطوانة | مثال السلايد 15 لتوضيح الأسئلة: «Can one PERSON own many DVDs, or only one? Can one DVD be owned by many PERSONs?» |
| 49 | **Redundant relationships** | ريداندنت ريليشنشيبس | علاقات زائدة | «Recognize redundant relationships and remove them from the ERD.» — علاقات مكررة بنفس المعنى يجب حذفها |
| 50 | **Refine and improve the model** | ريفاين آند إمبروف | تحسين وتطوير النموذج | «As we refine and improve our model, we want to make sure our entity relationships correctly model our business rules.» — هدف تحديد نوع العلاقة بدقة |
| 51 | **Costly mistakes** | كوستلي ميستيكس | أخطاء مكلفة | «You can avoid future costly mistakes by thinking through the details early on.» — سبب أهمية تحديد النوع مبكرًا |
| 52 | **ER Model** | إي آر مودل | نموذج العلاقات | «The various types of 1:M relationships are most common in an ER Model.» — الوعاء الذي تظهر فيه أنواع العلاقات |
| 53 | **Cardinality of one or more** | كارديناليتي أوف ون أور مور | عددية واحد أو أكثر | «M:1 and 1:M relationships have cardinality of one or more in one direction» — وصف أحد طرفي العلاقة |
| 54 | **One and only one** | ون آند أونلي ون | واحد فقط لا غير | وصف الطرف الآخر في 1:M — وأيضًا وصف الطرفين في 1:1 |
| 55 | **First version of an ER model** | فيرست فيرجن أوف إي آر مودل | المسودة الأولى للنموذج | «M:M relationships are common, particularly in a first version of an ER model.» — تظهر بكثرة في البداية ثم تُحلّ لاحقًا |
| 56 | **Later stages of the modeling process** | لاتر ستيجز أوف ذا مودلينج بروسيس | المراحل المتأخرة من النمذجة | «In later stages, all M:M relationships will be resolved, and disappear.» — مرحلة الحل |

# Glossary — Artificial, Composite, and Secondary UIDs (Chapter 6)



| # | Term | النطق بالعربي | الترجمة | التعريف كما ورد بالسلايد |
|:-:|---|---|---|---|
| 1 | **UID (Unique Identifier)** | يو آي دي (يونيك أيدنتيفاير) | المعرّف الفريد | «It is the value or combination of values that enables the user to find that one unique item among all the rest.» — القيمة أو مجموعة القيم التي تمكّن المستخدم من إيجاد عنصر واحد فريد بين كل العناصر |
| 2 | **Simple UID** | سيمبل يو آي دي | معرّف بسيط | «A UID that is a single attribute is a simple UID.» — معرّف مكوّن من خاصية واحدة فقط |
| 3 | **Composite UID** | كومبوزيت يو آي دي | معرّف مركّب | «If the UID is a combination of attributes, it is called a composite UID.» — معرّف مكوّن من مجموعة خصائص معًا |
| 4 | **Artificial UID** | آرتيفيشال يو آي دي | معرّف اصطناعي | «Those that don't occur in the natural world but are created for purposes of identification in a system.» — قيمة غير موجودة طبيعيًا، تُنشَأ داخل النظام للتعريف فقط |
| 5 | **Candidate UID** | كانديديت يو آي دي | معرّف مرشَّح | «One of several UIDs that could be used to identify something» — أحد عدة معرّفات صالحة للاستخدام للتعريف |
| 6 | **Primary UID** | برايمري يو آي دي | معرّف أساسي | «A candidate UID that is the primary identifier of something» — المرشَّح المختار فعليًا ليكون المعرّف الرسمي |
| 7 | **Secondary UID** | سيكندري يو آي دي | معرّف ثانوي | «A candidate UID that also identifies something, but is not the primary UID» — مرشَّح صالح لكنه لم يُختَر كأساسي |
| 8 | **Barred Relationship** | بارد ريليشنشيب | علاقة مقيَّدة (بخط عمودي) | علاقة يحمل فيها طرفها خطًا عموديًا صغيرًا يعني أن المعرّف يورَّث من ذلك الطرف — الخط العمودي هو العلامة المميزة |
| 9 | **Intersection Entity** | إنتيرسيكشن إنتبتي | كيان تقاطعي | كيان ناتج عن حل علاقة M:M بين كيانين أصليين — يحمل مفاتيح الطرفين معًا |
| 10 | **M:M Relationship Resolution** | ريزولوشن أوف إم تو إم ريليشنشيب | حل علاقة متعدد-متعدد | «The resolution of a M:M relationship often results in barred relationships from the intersection entity to the original ones.» — تحويل M:M إلى كيان تقاطعي + علاقتين 1:M مقيَّدتين |
| 11 | **Identification** | أيدنتيفيكيشن | تعريف / تمييز | «The unique identifier enables you to find your record in a file, a particular card in a deck of cards, your package in a warehouse, or a specific piece of data in a database.» — عملية تمييز عنصر واحد عن باقي العناصر |
| 12 | **Distinguish** | ديستنجويش | يميّز | «Unique identifiers make it possible for us to distinguish one instance of an entity from another.» — الوظيفة الأساسية للـ UID |
| 13 | **Primary key** | برايمري كي | مفتاح أساسي | «These become primary keys in the database.» — ما يتحول إليه الـ UID عند تنفيذ قاعدة البيانات |
| 14 | **Access a specific record** | أكسِس أ سبيسيفيك ريكورد | الوصول لسجل محدد | «A primary key allows you to access a specific record in a database.» — وظيفة الـ primary key |
| 15 | **CONCERT TICKET** | كونسيرت تيكِت | تذكرة حفل | مثال السلايد 4 — التذكرة يمكن تعريفها بـ `ticket number` (Simple UID) أو بـ `date of performance + seat number` (Composite UID) |
| 16 | **Ticket number** | تيكِت نمبر | رقم التذكرة | مثال على Simple UID في CONCERT TICKET |
| 17 | **Date of performance / Seat number** | ديت أوف بيرفورمانس / سيت نمبر | تاريخ الحفل / رقم المقعد | مثالان على Composite UID — لا يكفي أحدهما وحده للتمييز |
| 18 | **CUSTOMER** | كاستمر | العميل | مثال السلايد 5 — إضافة `id` كـ Artificial UID للعميل |
| 19 | **Create an artificial UID** | كرييت آن آرتيفيشال يو آي دي | إنشاء معرّف اصطناعي | الإجراء الممثَّل بالسهم الأحمر في السلايد 5 — إضافة عمود `# id` للكيان |
| 20 | **SHOE** | شو | الحذاء | مثال السلايد 6 — «A shoe has a color, a size, a style, but no truly descriptive 'number'.» — لذلك يُنشَأ `shoe ID` |
| 21 | **Shoe ID** | شو آي دي | معرّف الحذاء | Artificial UID مُنشَأ لتُميَّز كل زوج أحذية |
| 22 | **STUDENT** | ستيودنت | الطالب | مثال السلايد 7 — الطالب لا يمكن تمييزه بـ first name + last name إلا إذا كان التركيب فريدًا |
| 23 | **Student ID** | ستيودنت آي دي | رقم الطالب | Artificial UID يُنشَأ للطالب لأنه أبسط من التحقق من تركيب الاسم الكامل |
| 24 | **ACCOUNT** | أكاونت | الحساب | مثال السلايد 8 — «What is the UID of ACCOUNT? Is it artificial? Is it composite?» — يحتاج Bank number + Account number |
| 25 | **BANK** | بانك | البنك | الطرف الآخر في العلاقة — رقم الحساب مكرر بين بنوك مختلفة، فتُضاف علاقة البنك لتعريف الحساب |
| 26 | **Bank routing number** | بانك راوتينج نمبر | رقم توجيه البنك | «Bank to bank transfers always need the bank routing number in addition to the bank account number.» — مثال واقعي على أن الـ UID قد يأتي من علاقة |
| 27 | **UID from Barred Relationship** | يو آي دي فروم بارد ريليشنشيب | معرّف من علاقة مقيَّدة | «Sometimes the UID is a combination of an attribute and a relationship.» — عندما يأتي جزء من الـ UID من علاقة |
| 28 | **ENROLLMENT** | إنرولمنت | التسجيل | Intersection entity بين STUDENT وSUBJECT — «The UID of ENROLLMENT comes from STUDENT and SUBJECT.» |
| 29 | **STUDENT–SUBJECT (M:M)** | ستيودنت–سبجيكت | الطالب–المادة | العلاقة M:M التي حلّها ENROLLMENT — العلاقتان `enrolls for` و`subject of` مقيَّدتان |
| 30 | **Enrolls for** | إنرولز فور | يسجّل في | اسم العلاقة من جهة STUDENT تجاه ENROLLMENT |
| 31 | **Subject of** | سبجيكت أوف | مادة لـ | اسم العلاقة من جهة SUBJECT تجاه ENROLLMENT |
| 32 | **For** | فور | لـ / من أجل | اسم العلاقة من جهة ENROLLMENT تجاه الطرفين (for ... for) |
| 33 | **Artificial UID Intersection Entity** | آرتيفيشال يو آي دي إنتيرسيكشن إنتبتي | كيان تقاطعي بمعرّف اصطناعي | «It is possible for an intersection entity to use an artificial attribute as the UID, instead of the barred relationships to the originating entities.» — بديل لحل الـ M:M بعلاقات مقيَّدة |
| 34 | **CATALOG ITEM** | كاتالوج آيتِم | عنصر الكتالوج | Intersection entity بين MANUFACTURER وPRODUCT — يستخدم `number` كـ Artificial UID بدلًا من العلاقات المقيَّدة |
| 35 | **MANUFACTURER** | مانيوفاكتشرر | المُصنِّع | «Each MANUFACTURER may produce one or more PRODUCTS.» — الطرف الأول في العلاقة M:M |
| 36 | **PRODUCT** | برودكت | المنتج | «Each PRODUCT may be produced by one or more MANUFACTURERS.» — الطرف الثاني في العلاقة M:M |
| 37 | **Supplied by** | سابلايد باي | مُوَرَّد بواسطة | اسم العلاقة من جهة CATALOG ITEM تجاه MANUFACTURER |
| 38 | **Supply** | سابلَي | يُوَرِّد | اسم العلاقة من جهة MANUFACTURER تجاه CATALOG ITEM |
| 39 | **Has** | هاز | يمتلك / له | اسم العلاقة من جهة CATALOG ITEM تجاه PRODUCT |
| 40 | **Manufacturer number + Product code** | مانيوفاكتشرر نمبر + برودكت كود | رقم المصنّع + كود المنتج | «An item in a catalog can be uniquely identified by the manufacturer number and the product code.» — Composite UID الطبيعي البديل |
| 41 | **Catalog number** | كاتالوج نمبر | رقم الكتالوج | Artificial UID الذي حلّ محل العلاقات المقيَّدة — «The relationships are not barred, because an artificial UID — catalog number — has been created instead.» |
| 42 | **Not barred** | نوت بارد | غير مقيَّدة | «The relationships are not barred, because an artificial UID has been created instead.» — العلاقات بدون خط عمودي لأن الـ UID اصطناعي |
| 43 | **Person doc id** | بيرسون دوك آي دي | رقم هوية الشخص | مثال على Candidate UID في السلايد 13 — يمكن استخدامه أو استخدام الإيميل كـ UID |
| 44 | **Email address** | إيميل أدرس | عنوان البريد الإلكتروني | مرشَّح آخر للـ UID — «Each of these uniquely identifies you.» |
| 45 | **Candidate UIDs (example)** | كانديديت يو آي دي | معرّفات مرشَّحة | «Sometimes two or more possible UIDs exist. For example, Person doc id, email address.» — كلاهما يعرّفك، وكلاهما مرشَّح |
| 46 | **One primary UID** | ون برايمري يو آي دي | معرّف أساسي واحد | «Only one of the candidate UIDs is chosen as the actual UID.» — قاعدة الاختيار |
| 47 | **One secondary UID** | ون سيكندري يو آي دي | معرّف ثانوي واحد | مثال STUDENT في السلايد 14 — `badge number` كمعرّف ثانوي بجانب `student ID` الأساسي |
| 48 | **Two secondary UIDs** | تو سيكندري يو آي دي | معرّفان ثانويان | مثال STUDENT الثاني — `badge number` (مفرد) + `first name + last name` (مركّب) بجانب `student ID` |
| 49 | **Badge number** | بادج نمبر | رقم الشارة | مثال على Secondary UID في بطاقة الطالب |
| 50 | **First name + Last name (composite secondary)** | فيرست نيم + لاست نيم | الاسم الأول + الاسم الأخير | مثال على Secondary UID مركّب — يظهر بالعلامة `(#2-1)` و `(#2-2)` |
| 51 | **Alternative means of searching** | ألترناتيف مينز أوف سيرشينج | وسيلة بحث بديلة | «Secondary UIDs can be useful as an alternative means of searching for data.» — فائدتها العملية |
| 52 | **Forgot your student ID** | فورجوت يور ستيودنت آي دي | نسيت رقمك الجامعي | «Example: You forgot your student ID, but you have your email with you.» — السيناريو الواقعي لاستخدام الـ Secondary UID |
| 53 | **Real world identification** | ريال وورلد أيدنتيفيكيشن | التعريف في العالم الواقعي | «In the real world, however, it is sometimes not so easy to distinguish one thing from another.» — الفرق بين العالم الواقعي وقاعدة البيانات |
| 54 | **Keys need label** | كيز نيد ليبل | المفاتيح تحتاج ملصقًا | مثال السلايد 16 — مفاتيح متشابهة يلزمها ملصق لكل واحد لتمييزه (استعارة للـ UID) |
| 55 | **First name / Last name** | فيرست نيم / لاست نيم | الاسم الأول / الاسم الأخير | «Could we use a combination of first name and last name? Only if we are sure that the combination is unique.» — ليس دائمًا UID صالح |
| 56 | **Address / Tel number** | أدرس / تيل نمبر | العنوان / رقم الهاتف | خصائص ليست UID غالبًا — عنوان أو رقم هاتف قد يتغير أو يتكرر |
| 57 | **Color / Size / Style** | كالر / سايز / ستايل | اللون / المقاس / الطراز | خصائص SHOEE الوصفية — «A shoe has a color, a size, a style, but no truly descriptive 'number'.» — لذلك يُنشَأ Shoe ID |
| 58 | **Balance / Date opened** | بالانس / ديت أوبند | الرصيد / تاريخ الفتح | خصائص ACCOUNT — ليست UID، بل وصفية |
