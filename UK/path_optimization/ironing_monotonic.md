Монотонний порядок прасування
====

Зазвичай Luban впорядковую лінії прасування так, щоб відстань між ними була невеликою. Якщо цей параметр увімкнено, лінії прасування будуть упорядковані таким чином, що сусідні лінії завжди друкуватимуться з накладанням в одному напрямку.

Лінії прасування стандартно набагато тонші за отвір сопла, за допомогою якого вони друкуються, тому лінії будуть сильно накладатися на лінії поруч із ними. Це накладання надає лініям невеликий нахил, змушуючи їх по-різному відбивати світло в різних напрямках. Якщо сусідні лінії накладаються по-різному, це відбиття змінюється. Ви можете побачити це в кінцевому результаті. Надає різного блиску різним ділянкам поверхні. Друк у монотонному порядку гарантує, що перекриття однакове на всій поверхні, тому немає різниці у тому, як воно відбиває світло. Це робить поверхню більш однорідною та гладкою.

Однак, на відміну від [еквівалента для верхніх/нижніх ліній](skin_monotonic.md), цей ефект пригнічений іншим ефектом від прасування. Прасування має настільки низьку швидкість подачі, що зміна подачі від звичайної подачі друку є дуже великою. Це робить прасувальний шар товщим, коли він починає друкуватися, і все одно залишає помітну межу там, де друк було перервано. Монотонний порядок не усуне ці межі. Хоча поверхня може виглядати трохи більш гладкою, на практиці друк ліній прасування в монотонному порядку в основному неефективний, якщо ваш принтер не має дуже точного контролю над швидкістю подачі.

Монотонний порядок трохи збільшить довжину ходів пересування, але цей ефект дуже мінімальний.

Щоб отримати гладку поверхню, подумайте про поєднання цього параметра з налаштуванням [Режим розчісування](../travel/retraction_combing.md), щоб уникати поверхонь, і, можливо, увімкнути [підйом по осі Z](../travel/retraction_hop.md).
