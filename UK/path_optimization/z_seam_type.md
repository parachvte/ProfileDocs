Положення шва Z
====

Цей параметр дозволяє вибрати, де розміщувати шов кожного контуру. Доступно кілька варіантів, які дають чудовий контроль над місцем розміщення шва, щоб мінімізувати його вплив або дозволити вам легше видалити шов під час подальшої обробки.

Шов – це місце, де починається і закінчується контур друку в шарі. За допомогою цього параметра видимість шва можна мінімізувати, сховавши його кудись або розвівши його положення між шарами.

Визначається користувачем
----

![Визначається користувачем](../images/z_seam_type_user.png)

Ця опція дозволяє вибрати місце вручну. Шов буде розміщено в кутку, найближчому до вибраного місця. Зазвичай це вирівнює шви дуже щільно один до одного, що дозволяє легко їх відрізати. Це також дозволяє точно контролювати місце шва.

Стандартно вибрано розташування в задній частині принтера.

Найкоротший бік
----

![Найкоротший бік](../images/z_seam_type_shortest.png)

Ця опція мінімізує довжину рухів шляхом розміщення початкової точки найближче до положення, де сопло завершує попередній шар. Оскільки шлях переміщення коротший, ви трохи заощадите час на цьому. Шов також буде трохи меншим, оскільки в місці, де сопло приземляється на контур, буде менше протікань пластику.

Потрібний кут усе ще зберігається, вибираючи кут ближче до місця, де знаходиться сопло. Вибирається не найближчий кут, але використовується зважене налаштування, щоб дещо мінімізувати переміщення, але також використовувати відповідний кут для параметра [Налаштування кута шва](z_seam_corner.md).

Довільно
----

![Довільно](../images/z_seam_type_random.png)

Для шва вибирається довільне місце на периметрі контуру. Це випадкове розташування змінюється на кожному шарі, тому шов буде рівномірно розподілений навколо моделі. Оскільки шви різних шарів не збігаються, шов майже не буде видно. Однак поверхня виглядатиме трохи неохайною.

Найгостріший кут
----

![Найгостріший кут](../images/z_seam_type_sharpest.png)

Шов буде розміщено в найгострішому куті всього контуру відповідно до параметрів кута, вибраного в налаштуванні [Налаштування кута шва](z_seam_corner.md). Це може спричинити довші переміщення, але гарантує, що шов буде прихований або максимально видимий відповідно до параметрів, встановлених для кутів.