Z 抬升速度
====
### **参数描述**
此参数用于设置喷嘴在 Z 抬升中垂直移动的速度。由于喷嘴 Z 抬升后的水平移动由 [空驶速度](speed_travel.md) 决定，因此不受此设置影响。

![The vertical movement is made at the Z Hop Speed](../images/speed_z_hop.svg)

### **参数影响**
大多数打印机的 Z 轴设计得很坚固但抬升速度较慢。提高 Z 抬升速度非常考验 Z 轴的移动性能，可能会导致 Z 轴电机丢步，最终结果是，喷嘴在结束 Z 抬升后高度可能发生改变。降低 Z 抬升速度可以减少这种情况。

但提高 Z 抬升速度可以让喷嘴更快地远离打印表面，形成的凸点就会更小。

由于 Z 轴加速度较低，Z 抬升速度只能设置得很低。要达到较大的 Z 抬升速度，需要把 Z 抬升高度设置得非常高。