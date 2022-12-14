最大回抽计数
====
### **参数描述**
耗材是通过进料器齿轮的推动挤出的。回抽材料经常导致进料器齿轮磨损耗材，进而导致齿轮无法继续推动耗材挤出。此参数通过限制一定耗材长度内的回抽次数来避免对材料的磨损。

此参数指在[最小挤出距离范围](retraction_extrusion_window.md)内耗材的回抽次数。最小挤出距离范围指的是一段特定的耗材长度，在此长度内，回抽次数不能超过最大回抽计数；超过规定范围的回抽将不会执行，只会空跑。

![Visualisation of retractions during a certain length of filament](../images/retraction_count_max.svg)

举个例子，当最小挤出距离范围设置为 3mm，最大回抽计数设置为 10，那么，在 3mm 的耗材长度内，回抽次数不能超过 10 次。

### **参数用途**
减小最大回抽计数可以减少材料磨损，适用于 PVA 这些柔性材料。然而，由于此参数取消了一些关键位置的回抽，所以也会增加拉丝的情况。