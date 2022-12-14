Infill Flow
====
### **Description**
This setting adjusts the flow rate for the infill. 


### **Usage**
Adjusting the flow rate during the infill is a stop gap method to fix problems with extrusion rate or strength. The same effect can be achieved by adjusting the [distance between lines](../infill/infill_line_distance.md) and [line width](../resolution/infill_line_width.md) of the infill, but this setting may be more intuitive.

Problems with extrusion rate or strength of the infill are mainly caused by crossings in the infill pattern, or too much of a change in flow rate between the infill and other structures. Rather than adjusting this flow rate, it may be more effective to adjust the [infill pattern](../infill/infill_pattern.md) or the [line width](../resolution/infill_line_width.md). Choose an infill pattern that doesn't cross itself, such as zigzag. If the line width needs to be increased for strength but is limited in the flow rate, it's a good idea to use the [infill multiplier](../infill/infill_multiplier.md) instead of increasing the flow.