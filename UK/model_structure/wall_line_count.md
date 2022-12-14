Кількість ліній стінок
====

### **Опис**

Цей параметр визначає, скільки контурів стінки буде надруковано в кожному шарі.

![Two walls](../images/wall_thickness_0.8.png)
![Four walls](../images/wall_thickness_1.6.png)

Стінки моделі складаються із зовнішньої стінки та внутрішньої стінки. Зазвичай існує лише одна зовнішня стіна, проте кілька внутрішніх. Таким чином, зрештою, параметр встановлює кількість внутрішніх стінок, щоб досягти бажаної кількості ліній стінки.

### **Вплив**

Кількість ліній стінки є основним фактором, який визначає міцність друку. Оскільки стінки є суміжними, вони можуть зміцнювати одна одну, створюючи більш міцну деталь. Для більших моделей це може бути набагато ефективнішим способом отримання міцного об’єкта, ніж регулювання заповнення залежно від форми.

Збільшення товщини стінок:

* Значно підвищує міцність друку.
* Зменшує ефект просвічування, коли візерунок заповнення видно зовні.
* Покращення стійкості нависань.
* Робить модель більш водонепроникною.
* Значно збільшує час друку та матеріаломісткість друку.
