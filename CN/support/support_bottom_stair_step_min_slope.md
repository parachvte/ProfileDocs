支撑阶梯最小坡度角
====
### **参数描述**
若模型上放置支撑的部位坡度角小于支撑阶梯最小坡度角，则支撑底部将不会生成阶梯结构。

![Stair stepping disabled until the slope is 10°](../images/support_bottom_stair_step_min_slope_10.png)
![Stair stepping disabled until the slope is 30°](../images/support_bottom_stair_step_min_slope_30.png)

### **参数影响**
调大此参数的值后，Luban 在坡度角较低的表面上生成的支撑就不会带有阶梯结构。这样的话，支撑会更稳固，但也更难移除，还会在表面上留下更多疤痕。调小此参数的值可以让支撑更容易移除，它所接触的表面也会更美观。但在某些情况下，这会让支撑与模型接触部位之间的跨度变得很大，甚至可能让部分支撑与模型表面完全不接触。

### **参数使用**
要想让模型表面更加美观，最好谨慎设置一个较低的角度，比如 5° 或 10° 左右。如果支撑下方的模型表面坡度角较低但并非完全平坦，那么最好通过分层视图预览一下支撑结构，如果发现支撑看上去很不稳固，则需要把支撑阶梯最小坡度角调高一点。