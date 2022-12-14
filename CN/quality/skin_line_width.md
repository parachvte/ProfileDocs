走线宽度（顶部/底部）
====
### **参数描述**
走线宽度（顶部/底部）指打印机所绘制的每条顶部和底部线条的宽度。只要挤出比所需材料更多或更少的量，走线宽度就会与喷嘴尺寸不同。如果挤出更多材料，塑料将流向侧边，使走线更宽。如果挤出更少材料，材料的表面张力往往会将材料拉向喷嘴路径的中线。

![The skin lines are significantly wider than the rest](../images/skin_line_width.png)

### **参数影响**
加宽皮肤线条可缩短打印时间，因为打印对象顶部和底部所需的线条更少。但是，过度提高此设置可能会导致材料挤出量不稳定。由于通过喷嘴的流量无法快速调整，这会导致在打印皮肤时挤出不足，而在打印后续部分时挤出过度。增加皮肤走线宽度也会提高表面出现孔洞的可能性，这将降低打印件的外观质量，并降低打印件的水密性。

### **参数使用**
减少皮肤走线宽度往往能打印出更美观的顶部表面，但会大幅延长打印时间。使用[熨平](../shell/ironing_enabled.md)等不同的技术或仅调整[顶部表面皮肤走线](../experimental/roofing_line_width.md)通常更加有效。
