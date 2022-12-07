Ривки початкового шару
====

### **Опис**

Цей параметр визначає швидкість, з якою сопло може проходити через кути під час друку початкового шару. Його можна налаштувати окремо від решти шарів.

### **Вплив**

Проходження крізь гострі кути на великих швидкостях призводить не лише до горизонтальної вібрації робочої головки. Це також може призвести до вертикальної вібрації робочого столу. Це негативно впливає на зчеплення деталі з робочим столом. Ретельніше проходження кутів під час нанесення першого шару забезпечує стабільніше зчеплення шару, але друк займе більше часу.

Крім того, зменшення ривка зазвичай змушує принтер залишати більше матеріалу в гострих кутах, оскільки сопло сповільнюється, тоді як подача матеріалу має деяку затримку. Ці гострі кути часто є місцем, де друк відстає від робочого столу через деформацію. Тоді доцільно додати додатковий матеріал у ці кути, оскільки це покращить зчеплення кутів.

### **Використання**

Окремі структури друку можуть мати різні значення ривка. Існують окремі налаштування для заповнення, нижньої сторони, зовнішньої та внутрішньої стінок, опори та праймер-вежі. Це налаштування замінить їх усі. Лише параметр [Ривки спідниці/поля](jerk_skirt_brim.md) перевизначає цей ривок, оскільки спідниця та поле можуть з’являтися лише в першому шарі.