较慢层的数量
====
### **参数描述**
打印速度较慢的不只是起始层。此参数配置打印速度较慢的层数。在打印这些层的过程中，打印速度将逐渐提高至正常打印速度。

！【打印速度逐渐提高至 50 毫米/秒】(../images/speed_slowdown_layers.svg)

### **参数影响**
从起始层开始，速度线性加快（或减慢）到正常打印速度。如果要以不同的速度打印壁、表面皮肤、填充等部分，则会分别执行此操作。

### **参数使用**
之所以要通过几层来过渡到正常打印速度，有以下两个原因：
（1）第二层和第三层仍然非常接近打印平台，在它们上面快速移动很容易使打印物从平台松动。
（2）起始层打印速度和正常打印速度之间的流速差异可能很大，需要一段时间才能实现大流速变化。

缓慢过渡可以防止在速度变化很大时挤出不足。
但缓慢过渡也会增加总打印时间。

