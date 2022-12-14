Швидкість на початковому шарі для мілких обʼєктів
====

Контури, коротші за [максимальну довжину мілких обʼєктів](small_feature_max_length.md), можна друкувати зі зниженою швидкістю. За допомогою цього параметра ви можете вказати швидкість, з якою ці контури мають друкуватися на першому шарі, як фактор їх [нормальної швидкості друку](../speed/speed_wall.md). Це можна налаштувати окремо від швидкості друку невеликих елементів на [решті шарів](small_feature_speed_factor.md).

Маленькі контури не мають великої площі, щоб приклеїтися до робочого столу. Особливо під час [друку стінок перед заповненням](../infill/infill_before_walls.md), стінки для невеликих отворів часто є лише крихітними колами, що лежать на робочому столі. Якщо сопло вдариться о них під час руху пізніше, вони можуть відірватися від робочого столу. З цієї причини швидкість друку цих малих контурів має бути зменшена порівняно з іншими контурами. Це дозволяє матеріалу більше витікати та краще з’єднуватися з робочим столом, зменшуючи ймовірність скинути їх із робочого столу.

Зменшення швидкості друку цих маленьких контурів має дуже незначний негативний вплив на швидкість друку. На щастя, оскільки ці контури малі за визначенням і це стосується лише першого шару, загальний доданий час друку незначний.
