Візерунок верха/низу
====

Цей параметр дозволяє вибрати спосіб заповнення верхніх і нижніх шарів матеріалом. Доступно кілька різних візерунків друку, але кількість шаблонів тут менше, ніж шаблонів для заповнення. Доступні лише візерунки, які створюють суцільні шари.

Лінії
---

![Lines](../images/top_bottom_pattern_lines.png)

Базовий шаблон друкує прямі лінії по поверхні. Ці лінії типово орієнтовані таким чином, щоб вони добре підтримувались заповненням та підтримками. Напрямок ліній змінюється між шарами.

* Забезпечує гарну якість поверхні.
* Міцно прилягає до стінок, створюючи відносно міцні частини.

Концентричний
----

![Concentric](../images/top_bottom_pattern_concentric.png)

Концентричний візерунок друкує контури від стінок до внутрішньої частини моделі.

* Однаково міцний у всіх напрямках.
* Запобігає утворенню повітряних кишень і щілин. За допомогою цього візерунка легше створювати водонепроникні об’єкти.
* Чудова якість друку нависань, оскільки лінії мають тенденцію дуже добре перетинатись.
* Якщо деталь кругла, це створить неприємну пляму в центрі, де сходяться контури.
* Якість поверхні нижча за ідеальну.

Зигзаг
---

![Zigzag](../images/top_bottom_pattern_zigzag.png)

Зигзагоподібний візерунок дуже схожий на лінійний візерунок, але замість того, щоб закінчувати лінії на стінах, він повертатиметься, коли торкнеться стін, і продовжуватиме друк до наступної лінії.

* Забезпечує чудову якість поверхні.
* Зберігає швидкість екструзії більш постійною, що покращує цілісність поверхні.
* Не прилипає до стін так добре, як лінійний шаблон. Ефект [Перекриття оболонок](../model_structure_optimization/skin_overlap.md) зменшено. Це робить деталь слабшою і знижує якість звисів.
