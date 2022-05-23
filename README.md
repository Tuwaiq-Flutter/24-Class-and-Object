# Class and Object
عند البدء في كتابة برامجك فسوف تجد أنك بحاجة إلى تنظيم برنامجك بتنظيم الشيفرات البرمجية الي تكتبها بطريقة تُساعدك على جعل البرنامج مُقسم بطريقة منظمة تكون قابلة للإضافة والحذف والمعالجة والتصحيح وغيرها من عمليات التطوير الي يقوم بها المبرمج بالإضافة إلى أنها قابلة لإعادة الاستخدام في برامج أخرى إن أمكن. توفر لغة Dart البرمجة بأسلوب Object Oriented Porgramming واختصاره OOP . يوفر لك هذا الأسلوب أوالنموذج البرمجي طريقة منظمة لكتابة برمجياتك وتصحيحها والتعامل معها بشكل يساعدك على التطوير المستمر للشيفرة البرمجية وتوفر الوقت والجهد في ذلك من خال القدرة على إعادة استخدامها كما ذكرنا في برامج أخرى.
لذى لغة  Dart هي لغة برمجة object-oriented programming ، فهي تدعم مفهوم Class ، Object ,Inheritance ... إلخ.  


## مقدمة في مفهوم Object Oriented Programming في لغة Dart 

توفر Dart دعمًا مكثفًا لتطوير التطبيقات Object Oriented Programming واختصارها OOP، وهي طريقة برمجة تتضمن تقسيم متطلباتنا إلى أجزاء أصغر يمكن إدارتها. كل جزء منفصل قائم بذاته، ويمكن إعادة استخدامه في مكان اخر، وهذهِ الأجزاء هي ما نشير إليها باسم Object. عندما نخطط/نبرمج  Object فإننا نفعل ذلك مع Class، ويمكن اعتبار Class على أنه مخطط Object.
ننفذ Object من خلال Classes، وهذا يسمى نسخة من Class. كمثال للتوضيح عندما يكون هناك مخطط منزل فلا يمكننا العيش فيه لكن يمكننا بناء منزل من هذا المخطط لذلك يمكننا إنشاء نسخة منه. في كثير من الأحيان عندما نصمم Classes لتطبيقاتنا نكتبها لتمثيل أشياء من العالم الحقيقي. 

مبادئ OOP الأساسية ثلاثة وهي: Encapsulation و Polymorphism و Inheritance وسنتعرف عليها لاحقًا. 



## مفهوم Object

يمكننا تعريف بساطة في حال نظرنا للأشياء في عالمنا الواقعي على أنها مجموعة  objects ، فمثل لو نظرنا للناس على أنها مجموعة كائنات وكل شخص هو عبارة عن كائن object ونظرنا للسيارات على أنها كائنات وكل سيارة منها عبارة عن كائن object ونظرنا لكل ما حولنا من أشياء بهذا الأسلوب فسيصبح العالم من حولنا هو عبارة عن مجموعة من الكائنات المترابطة مع بعضها البعض والي تتواصل مع بعضها البعض بطريقة معينة.
يحتوي Object على بيانات data ودوال function تمثل العمليات.يتم تسمية البيانات بإسم attributes او Properties ويتم تسمية الدوال بإسم methods وهنا نقول أن Object هو عبارة عن مجموعة من البيانات attributes والدوال methods .يتكون الكائنات (Objects) ياخذ هذه الصفات من Class 

## مفهوم Class  ****

إذا قلنا أنك  object ، فأنت لست وحدك على هذه الأرض! هناك أشخاص آخرين، أليس كذلك؟ وهم object أيضاً، فأنت شخص، وهناك شخص غيرك أيضاً وإذا نظرنا لكل شخص على أنه object فسنقول أنهم يتشاركون في أشياء ويختلفون في أشياء، 
لذى نستطيع تعريف Class هو عبارة عن حاوية لمجموعة من التعليمات البرمجية التي يمكن أن تحتوي على دوال ومتغيرات وحلقات وغيرها، ويمكن  تعريف كل Class جديد في ملف dart منفصل. ويكون اسم الملف بنفس اسم Class. ويمكن انشاء من هذا الكلاس object 


مالذي استنتجناه من مما سبق ؟
يتم تمثيل Class بشكل بسيط على انه هو الهيكل العام او المخطط لشيء معين
ويتم تمثيل Object على انه هو شيء حقيقي تم انشاءه بهذا الهيكل او المخطط 

مثال توضيحي :

نستطيع انشاء Class خاص في الطلاب وهو الهيكل العام لوصف الطالب بشكل عام ويحتوي على خصائص التاليه :

-  اسم الطالب  
- الرقم الأكاديمي
- عمره 
- درجاته 

ويمكن تعريف الدوال بانها هي السلوك والتصرفات الخاصه في الطالب :

- مثل التحدث
- الحضور والغياب

وما إلى ذلك 
 


## تعريف Class في Dart ****

قبل أن يتم إنشاء Object، نحتاج أولاً إلى إنشاء Class كما ذكرنا مسبقًا ليكون مخطط Object.
عند إنشاء Class في Kotlin نستخدم الكلمة المحجوزة class وبعدها يتم كتابة اسم لـ Class.
الصيغة الأساسية كما يلي:
**Syntax:**  


    class class_name {
    
       // Body of class comtains Properties and Methods}
    }

كلمة Class هي الكلمه الاساسية المستخدمه لانشاء Class  وما يوجد داخل {} يعتبر هو الجسم الخاص في Class 


داخل Class  يمكن كتابة  Properties وهي المتغيرات والثوابت التي يتم تضمينها في Class، ويتم تعريفها بنفس الطريقة التي يتم بها تعريف أي متغير آخر في Dart.
يوجد قسم الدوال Methods ويتم تعريف الدوال ليتم استدعاؤها. هذهِ الدوال خاصة في Class التي تؤدي عملية معينة عند استدعائها.



في المثال التالي سننشئ Class حساب بنكي:


    class BankAccount {
     
    }

الآن بعد أن أصبح لدينا Class، فإن الخطوة التالية هي إضافة بعض الخصائص إليه.

## إضافة الخصائص Properties إلى Class ****

الهدف الرئيسي من OOP هو مفهوم يشار إليه باسم Data encapsulation أي تغليف البيانات. الفكرة وراء هذا المفهوم هو أنه يجب تخزين البيانات داخل Classes والوصول إليها فقط من خلال الطرق المحددة في تلك Class. وهي بستخدام dot notation و  يشار إلى البيانات المغلفة في Class على أنها خصائص أو متغيرات.
سنحتاج لنسخة من BankAccount class لدينا لتخزين بعض البيانات، وتحديدًا رقم الحساب المصرفي والرصيد الموجود حاليًا داخل الحساب. يتم إنشاء الخصائص بنفس الطريقة التي يتم بها إنشاء المتغيرات في Dart. لذلك يمكننا إضافة هذهِ المتغيرات على النحو التالي:

    class BankAccount {
        num accountBalance = 0.0;
        int accountNumber = 0;
    }

بعد تحديد الخصائص، فإن الخطوة التالية هي إضافة بعض الدوال.

وللوصول الى هذه المتغيرات الموجوده داخل Class يجب انشاء Object من هذا Class ثم استخدام مفهوم dot notation للوصول الى المتغيرات من داخل هذا Object الذي اخذ تفاصيل Class كما في المثال التالي : 


     class BankAccount {
       String accountName = "Fahad";
        num accountBalance = 0.0;
        int accountNumber = 0;
    }
    main(){
     BankAccount account1 = BankAccount();
     print(account1.accountName);
      print(account1.accountNumber);
      print(account1.accountBalance);
    }

المخرجات :


    Fahad
    0
    0



## مفهوم الدوال Methods  ****

يعتبر Methods class في الأساس إجراءات من الأوامر يمكن استدعاؤها لأداء مهام محددة ضمن سياق أي Class.
يتم إنشاء Methods داخل أقواس Class ويتم إنشائها باستخدام صيغة Function التي تعرفنا عليها بالسابق.
على سبيل المثال، سوف ننشئ Method لعرض رصيد الحساب، وسنقوم بإنشائه على النحو التالي:


    class BankAccount {
        var accountBalance: Double = 0.0
        String accountName = "";
     
     class BankAccount {
        num accountBalance = 0.0;
        int accountNumber = 0;
      
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    }


## عمل نسخة من Class  ****

كل ما فعلناه حتى الآن هو تحديد مخطط Class فقط من أجل استخدام هذا Class، نحتاج إلى إنشاء Instance له. الخطوة الأولى في هذهِ العملية هي تعريف متغير لتخزين مرجع Instance عند إنشائه.
 نقوم بهذا على النحو التالي:

    BankAccount account1 = BankAccount();

عند التنفيذ سيتم إنشاء Instance من BankAccount class الخاصة بنا ويمكن الوصول إليها عبر متغير account1.
على النحو التالي:

    class BankAccount {
        num accountBalance = 0.0;
        String accountName = "";
     
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount();
     account1.accountBalance = 103.5;
     account1.accountName = "Fahad Alazmi";
    }

نلاحظ في داخل دالة Main استطعنا الوصول الى accountBalance عن طريق Object account1 الذي تم انشائه داخل Class BankAccount وتم اعطائه رصيد 103.5

 وايضاً تم الوصول الى accountName بنفس الطريقه وعطائه اسم Fahad Alazmi
 
 الان لو ادنا استعراض الرصيد يتم عن الطريق التالي :


    class BankAccount {
        num accountBalance = 0.0;
        String accountName = "";  
        displayBalance()
        {
           print("Name $accountName");
           print("Current balance is $accountBalance");
        }
    }
    
    main(){
     BankAccount account1 = BankAccount();
     account1.accountBalance = 103.5;
     account1.accountName = "Fahad Alazmi";
    
     account1.displayBalance(); //display Balance
    }

المخرجات :


    Name Fahad Alazmi
    Current balance is 103.5

بستخدام الدوالة باسم displayBalance تم عرض الرصيد ورقم الحساب لان Object باسم  account1 اخذ الخصائص والدوال الموجوده داخل class BankAccount 


