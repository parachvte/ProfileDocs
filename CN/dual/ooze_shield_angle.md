渗出罩角度
====
### **参数描述**
渗出罩角度是指渗出罩和 Z 轴之间允许存在的最大夹角（非钝角）。此设置限制了渗出罩的倾斜度，使其不会倒塌。

通常情况下，渗出罩非常贴合模型的形状。但是，如果模型的轮廓倾斜度很大，就需要调整渗出罩与模型之间的距离，以确保倾斜角度不会大于渗出罩角度。

![Instead of following the model down the bottom and the top, it doesn't go steeper than the specified angle](../images/ooze_shield.svg)

### **参数影响**
如果将此参数设置为 0°，则渗出罩将完全垂直于打印平台，像圆筒一样围绕在模型周围。角度越小，渗出罩就越稳定。

如果将此参数设置为 90°，则渗出罩将完全贴合模型的轮廓。角度越大，渗出罩就越能有效避免模型表面沾到渗出的材料。