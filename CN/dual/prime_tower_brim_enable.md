装填塔单层粘附
====
### **参数描述**
装填塔单层粘附类似于[打印平台附着类型](../platform_adhesion/adhesion_type.md)中设置的单层粘附，是环绕装填塔底部打印的单层平面结构，可提高装填塔与打印平台间的附着。

若装填塔原先没有粘附，则启用此设置可为装填塔生成单层粘附。若装填塔原先已有粘附，则启用此设置可在已有粘附的基础上额外增加粘附。

装填塔单层粘附可以与普通粘附分开进行设置。

![The adhesion is set to skirt, but there is still a brim around the prime tower](../images/prime_tower_brim_enable.png)

### **参数使用**
启用装填塔单层粘附后，装填塔与打印平台的接触面积将会增大，从而可以更稳定地矗立在打印平台上。因为装填塔的形状一般比较细长，所以如果打印件非常高，装填塔可能会倒塌。虽然启用装填塔单层粘附会导致打印时间增长，材料消耗增多，对打印平台空间的占用也略有增加，但可以有效避免装填塔倒塌的问题。

装填塔单层粘附将使用[单层粘附宽度](../platform_adhesion/brim_width.md)设置中定义的宽度。如果将打印平台附着类型设置为单层粘附，则此设置可以有效地将环绕装填塔的单层粘附宽度加大一倍。

装填塔单层粘附不能与多层粘附并用。