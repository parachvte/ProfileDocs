填充走线方向
====
### **参数描述**
填充走线方向通常为 45 度角。在此角度下，使用常见的龙门式笛卡尔打印机时，X 与 Y 电机同时运作，执行头可达到最大加速度。

此参数调节的便是填充走线的角度。设置特定角度，可为模型增加强度，也可为龙门系统增加加速度。

![Lines infill with default angles of 45 and 135 degrees](../images/infill_angles_45_135.png)
![Lines infill with customised angles of 0 and 30 degrees](../images/infill_angles_0_30.png)

### **参数用途**
此参数的数值是一个角度数列，你可以设置多个角度，中间以逗号隔开，数列两边加上中括号(例如[0,60,120])。假如设置 0 度角，则填充走线与 Y 轴平行。根据设置的角度，各层的走线会交替改变方向。
* 打印件在填充走线方向上的强度最高。若想增强打印件在某一水平方向上的强度，可将填充走线设置为该方向。
* 若参数值设置为空，则 Luban 将使用默认参数。
* 默认参数值取决于填充图案：
  * Cross 和 Cross 3D 填充图案的默认角度值为[22]。该值使走线接近对角线。
  * 直线和锯齿形填充图案的默认角度值为[45,135]。该值使走线方向在两条对角线之间逐层变换。
  * 其余所有图案的默认角度值均为[45]。该值使走线接近对角线。
