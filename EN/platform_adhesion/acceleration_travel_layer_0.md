Initial Layer Travel Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while travelling across the build plate during the first layer. 

### **Influence**
Printing at high rates of acceleration can cause vibrations of the printer. In particular, these vibrations can make the build plate shake up and down, which can cause the nozzle to hit the build plate and damage the printer. 

The vibrations can also continue on after the travel move and affect extrusion, which is detrimental to the adhesion between the model and the build plate. 

Reducing the acceleration of travel moves during the first layer compared to other layers can prevent these effects. However to save time, the acceleration during travelling in the first layer can still be higher than during the extrusion moves of the first layer, because vibrations are usually only a problem while extruding.

### **Usage**
The acceleration during travels on the first layer can be set to a different rate from the travel moves in the rest of the print or the extrusion moves of the first layer.






