Друкувати заповнення, а потім стінки
====

Якщо цей параметр увімкнено, під час друку чергового шару буде надруковано заповнення і тільки потім стінки.

![Налаштування вимкнено, тому спочатку друкуються стінки](../images/infill_before_walls_disabled.gif)
![Налаштування ввімкнено, тому спочатку друкується заповнення](../images/infill_before_walls_enabled.gif)

Цей параметр є компромісом між точністю та міцністю:

* Якщо стінки надруковані перед заповненням, стінки не матимуть до чого прикріпитися, що призведе до їхнього провисання. Однак стінки спочатку затвердіють і не будуть відштовхуватися заповнювачем, що запобігає просвічуванню заповнення крізь стінки.
* Якщо заповнення надруковано перед стінами, стінки будуть відштовхуватися в місці, де заповнення прикріплено до стінок, що робить стінки менш точними та може призвести до того, що заповнення просвічуватиме скрізь поверхню моделі, створюючи візерунок, видимий назовні. Однак заповнення краще утримуватиме стінки на місці під час друку.
