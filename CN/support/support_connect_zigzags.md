连接锯齿形支撑
====
### **参数描述**
如果[支撑图案](support_pattern.md)选择了锯齿形图案，那么启用该设置后，支撑图案的端点会与图案本身相连，从而使支撑更坚固。

### **参数使用**
普通锯齿形图案的端点比较脆弱，对于那些难以挤出，需要空驶移动一定时间后才能达到正常流速的材料尤其如此。此参数通过打印无端点的闭合支撑线来防止这种情况，使得支撑更坚固。另外，支撑底部在端点处容易翘起，若支撑走线没有端点，则支撑和打印平台之间的附着力将得到增强。

如果允许在模型表面上打印支撑，此参数还能大幅增强支撑和模型间的附着力。支撑端点处的额外连接扩大了支撑与模型之间的接触面积。这样，支撑会更加稳定，但也更难移除，并且会留下更多疤痕。