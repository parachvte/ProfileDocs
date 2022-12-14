Seam Corner Preference
====
### **Description**
With this setting you can control how the seams will be positioned relative to corners in your model.

Generally there are two options for where the seam can be placed: hidden in an inside corner, or exposed in an outside corner. Hiding the seam in an inside corner is generally preferable since the seam will hardly be visible there. But it is also possible to put it on an outside corner so that you can cut off the seam with a knife or sand it smooth with some sand paper, if some post-processing can be done on the part.

### **Usage**
The following options are available for this setting:
* **None:** There is no preference for corners at all. The seam will be chosen to match the requirements for [Z Seam Alignment](z_seam_type.md) best.
* **Hide Seam:** This will prefer to hide the seam in an inside corner. If Z Seam Alignment is set to "Sharpest Corner", the very innermost corner is always chosen. If Z Seam Alignment is set to "Shortest", it will choose an inside corner near the position at which the nozzle finishes the previous layer.
* **Expose Seam:** This will prefer to expose the seam on an outside corner. If Z Seam Alignment is set to "Sharpest Corner", the very sharpest outer corner is always chosen. If it's set to "Shortest", it will choose an outside corner near the position at which the nozzle finishes the previous layer.
* **Hide or Expose Seam:** This will place a seam on a sharp corner, be it an inside corner or outside, as long as it's not on a flat wall.
* **Smart Hiding:** This will place the seam on a sharp corner just like "Hide or Expose Seam", but inside corners will be more preferable than outside corners if any inside corners are available in the contour. If there are no inside corners, it will choose an outside corner.