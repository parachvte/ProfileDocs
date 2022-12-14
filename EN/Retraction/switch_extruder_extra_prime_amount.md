Nozzle Switch Extra Prime Amount
====
### **Description**
This setting allows you to configure the printer to purge a bit of extra material every time when the extruder is switched back. It is intended to restore the pressure on the nozzle after it has been oozing while other extruders have been printing or during an extruder switch.

### **Influence**
While other extruders are printing, this extruder will have been waiting on stand-by. During this time though, it will ooze material. That loss of material can be compensated for by pushing through some extra material. This puts the pressure back in the nozzle chamber. The material that was oozed out will still be hanging under nozzle tip though, so unless a [prime tower](prime_tower_enable.md) or [ooze shield](ooze_shield_enabled.md) is used, it will end up on the side of your print. 

### **Usage**
This setting is configurable per extruder. The configured amount of material is purged before printing with the material.

