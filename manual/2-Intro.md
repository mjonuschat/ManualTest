# Introduction

### STL File Key

#### The STL naming convention used for Micron is below:


| Primary Color                                               | Accent Color                                                                                                       | Quantity Required                                                                                           |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| Example                                                     | Example                                                                                                            | Example                                                                                                     |
| z_drive_main_a_x2.stl                                       | \[a\]\_z_drive_baseplate_a_x2.stl                                                                                  | \[a\]\_z_drive_baseplate_a_x2.stl                                                                           |
| These files will have nothing at the start of the filename. | These files will have ‘’\[a\]’’ to the front to mention that they are intended to be printed with an accent color. | If a file ends with ‘’\_x#’’, that is telling you the quantity of that part required to build this system.. |

### PRINT GUIDELINES

| **FDM MATERIAL** | **LAYER HEIGHT** | **EXTRUSION WIDTH** | **INFILL PERCENTAGE** |
| ---------------- | ---------------- | ------------------- | -------------------- |
| Micron was designed for ABS. Use other plastics at your own discretion. | Recommended: 0.2mm | Recommended: Forced 0.4mm | Recommended: 40% |


| **INFILL TYPE** | **WALL COUNT** | **SOLID TOP/BOTTOM LAYERS** | **SUPPORTS REQUIRED** |
| -------------- | ------------- | -------------------------- | -------------------- |
| Grid, Gyroid, Honeycomb, Triangle, Cubic, Adaptive Cubic | Recommended: 4 | Recommended: 5 | If the part needs supports, they are built into the model. |



