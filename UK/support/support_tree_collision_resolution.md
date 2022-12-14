Розвʼязання перетину гілок
====

### **Опис**

Головним недоліком опори у вигляді дерева є те, що її нарізання займає багато часу. Більшість розрахунків, необхідних для дерева, спрямовані на те, щоб гілки дерева не зіткнулися з сіткою. Цей параметр визначає точність розрахунків уникнення зіткнень. Збільшення цієї роздільної здатності (нижча точність) заощадить багато часу на обчислення, але також призведе до того, що опора буде виглядати нерівною, коли вона буде біля сітки.

![A low resolution (0.2mm) causes the branches to become jagged](../images/support_tree_collision_resolution_lo.png)
![A high resolution (0.02mm) creates smooth branches](../images/support_tree_collision_resolution_hi.png)

### **Вплив**

Збільшення цього параметра заощадить багато часу на нарізку. Це також зробить опору більш зазубреною, що погіршить її міцність, збільшуючи ймовірність того, що опора відламається під час друку, що призведе до невдачі друку.
