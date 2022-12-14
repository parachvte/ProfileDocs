空驶避让距离
====
### **参数描述**
在启用 [空驶时避开已打印部分](travel_avoid_other_parts.md)时，此设置决定喷嘴与要避开的部件之间需要保持的间距。

它具体指的是其他部件与空驶移动中心线之间的距离。由于空驶移动没有厚度，建议在此设置中设定一个足够大的值，让喷嘴末端不会碰到其他部件。

### **参数影响**
增加此设置的值可以让喷嘴在已打印部件周围空驶时更不容易碰到这些部件。 

但是由于喷嘴要绕行更多，这也会略微增加空驶移动的距离，进而略微增加打印时间和耗材渗出量。更要紧的是，这个值越大就越难找到能与已打印部件保持一定距离的有效路径。如果找不到有效路径，喷嘴将（可能）回抽并沿直线空驶，即使会碰到其他部件。因此，把此设置的值设定得过大会影响打印件的表面质量。