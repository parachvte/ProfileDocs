Мінімальний розмір обʼєкта
====

Цей параметр контролює мінімальну ширину деталей моделі, яка буде надрукована. Усе, що тонше цього, не буде надруковано.

Деталі, менші за розмір сопла, навряд чи будуть добре друкуватися. Це обмеження принтера. Однак Luban все одно може спробувати їх надрукувати, погоджуючись на те, що швидкість екструзії не буде високою, або що деталі будуть товщі, ніж змодельовано.

Зменшення мінімального розміру обʼєкта дозволяє принтеру друкувати менші деталі. Залежно від [мінімальної ширини лінії тонкої стінки](min_bead_width.md), ці крихітні деталі можуть бути надруковані шляхом дуже незначної спричиняючи [недоекструзію](../troubleshooting/underextrusion.md) або шляхом екструзії більш прийнятної ширини лінії, але їх розмір буде більшим. Встановлення цього значення на 0 змушує принтер проникати до самих кінчиків кожного гострого кута.

Збільшення мінімального розміру обʼєкта дозволяє принтеру не турбуватися про дрібні деталі, які все одно не вийдуть добре. Це економить час і може зробити друк чистішим.
