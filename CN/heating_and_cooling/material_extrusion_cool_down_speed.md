挤出冷却速度调节器 
====
材料在喷嘴室中加热时，会带走喷嘴的热量。挤出材料速度越快，喷嘴的热量流失越多。如果温度传感器并未完全置于喷嘴末端，则会导致喷嘴在挤出材料时的温度略低于正常温度。此设置描述了在打印时，喷嘴的热量流失速度。

如果启用 [自动控温](../experimental/material_flow_dependent_temperature.md)，打印温度将根据热量流失的速度进行调节。挤出过程中流失的热量，将通过 G 代码的调节进行补偿。

此设置的值取决于喷头设计、打印材料的热容量以及耗材挤出速率。