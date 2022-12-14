Initial Layer Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while printing the first layer. The acceleration during the first layer can be set to a different rate than the rest of the print.

### **Influence**
Printing at high rates of acceleration can cause vibrations of the printer. In particular, these vibrations can make the build plate shake up and down, which is detrimental to the adhesion of the print on the build plate. 

Reducing the acceleration for the first layer can reduce vibrations during this critical part of the printing process. It will take more time to print though, and reducing the acceleration rates too much can cause inconsistent extrusion in the corners which is also detrimental to build plate adhesion.

### **Usage**
While the walls, platform adhesion, bottoms, support and infill may all have different rates of acceleration, during the first layer they will be made the same. The initial layer acceleration rate will override the individual structures' acceleration rates. The travel moves may still have a different acceleration rate from the extrusion moves through the [Initial Layer Travel Acceleration](acceleration_travel_layer_0.md) and [Initial Layer Print Acceleration](acceleration_print_layer_0.md) settings. The [Skirt/Brim Acceleration](acceleration_skirt_brim.md) setting overrides the initial layer print acceleration as well.


