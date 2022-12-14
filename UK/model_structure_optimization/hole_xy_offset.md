Горизонтальне розширення отвору
====

Це міра компенсації ефекту друку, коли твори, як правило, стають меншими, ніж заплановано. За допомогою цього параметра ви можете збільшити розмір отворів у вашій деталі.

![Отвори було збільшено, але решта форми не змінилася](../images/hole_xy_offset.png)

Через в’язкість матеріалу під час друку кривої пластик має тенденцію тягнутися соплом уздовж кривої. Це робить криву трохи меншою, ніж заплановано, оскільки матеріал втягується всередину кривої. Зазвичай це не дуже помітно, але під час друку елементів, які мають бути дуже точними, або під час друку елементів із дуже маленькими вертикальними отворами, це стає руйнівним для точності вашого друку. Гвинти більше не підходять, деталі більше не ковзають одна в одну акуратно і так далі.

Цей параметр компенсує це, зробивши всі отвори трохи більшими. На відміну від [Горизонтального розширення](xy_offset.md), це впливає лише на закриті отвори. Якщо з одного боку (горизонтально, на тому самому шарі) є навіть невеликий отвір, то ця частина не вважатиметься отвором і на неї не вплине цей параметр.

Додатне значення збільшить отвори. Від’ємне значення зменшить отвори. У поєднанні з горизонтальним розширенням спочатку розширюються отвори перед застосуванням звичайного горизонтального розширення. Це може спричинити повне зникнення тонких частин до того, як вони будуть розширені за допомогою звичайного горизонтального розширення.
