Series100
=========

Front Panel tools and Enclosure for Electronic Projects

<img src="https://raw2.github.com/StdBx/Series100/master/Sampler.jpg" alt="Example front panel built using StdBx Series100">

StdBx is a group of tools and libraries intended to make it easy to create professional looking control and display panels for your electronics DIY projects.

Series100 is the first design point in the StdBx collection.  The panels fit into an enclosure that is 4.25"w by 2.375"h by 4.00"d.  The enclosure has mounting for the circuit boards and end panels.  The enclosure design is provided in .stl format.  The enclosure can be printed on a 3d printer or ordered from a 3d print service company like Shapeways.  We are also investigating having the enclosure pieces mass-produced so they are cheaply available.

Series100 is designed such that no circuit board needs to be larger than what is supported by the free version of the Eagle CAD PCB design tool.  Although the enclosure can hold multiple boards, you don't have to make more than one if that is all your project needs.

Series100 adds a library and a CAM file to the EagleCAD PCB design software.  As you design your circuit board the front panel is designed along with it.  It is easy to use following these steps.

  1. Design your circuit using Eagle's schematic capture tool.  For displays, buttons, switches, encoders, potentiometers and LEDs choose components from the Series100 library.  Include the Series100 board definition from the library.  
  2. Place the display and control components (along with the other components used in your design) using Eagle's PCB layout tool.  Route the circuit as you normally would.  
  3. Add any text labels you would like to have on the panel.  
  4. Export the panel definition using the CAM file and scripts provided.  
  5. Order your panel from a laser cutting service like Pololu using the exported files.  Panels typically cost about $14.

That's it.  The board and the panel fits accurately and securely in the enclosure.  Together they allow your unique project to look like it just rolled off the manufacturing line.

Here are some of the components in the StdBx Series100 library.

  * Push button, momentary,  round, 7mm & 9mm diameter, multiple colors
  * Push-on / Push-off button, round, 7mm & 9mm diameter, multiple colors
  * Push button, momentary, rectangular, multiple colors
  * Push-on / Push-off button, rectangular, multiple colors
  * Rotary encoder, gray-code with switch, 6mm shaft
  * LEDs, 3mm, 5mm & 10mm dia, clear or diffused, multiple colors
  * 8x1 LCD display
  * 16x2 LCD display
  * 20x4 LCD display
  * 7-segment, 4-dgit display, 0.4" & 0.8"
  * USB mini-B connector
  * Barrel connector (power connector)
  * BNC connector
  * Banana plug recepticle connector
  * Audio jack, 3.5mm
  * Speaker terminals

All components are thru-hole for easy assembly.  All components are specified with vendor part numbers and are readily available.  More and more components will be added to the library as they are verified to work with StdBx Series100.  If you have a need for a specific component you can request it here.

License: All design files are licensed under Creative Commons Universal.  You are welcome to modify the designs or even use them in commercial products.  We ask that you acknowledge that your design is based on StdBx and hope that if you create any additional components or enclosure designs that you contribute them back to the StdBx libraries. So that folks know that what they design from these tools will actually work, all submissions will be validated by StdBx prior to being included (i.e. the library will be moderated by StdBx.)  For the same reason the StdBx name is copyright (c) 2014 C.Schnarel, all rights reserved. (i.e. don't create stuff and call it StdBx if it isn't part of one of the StdBx repositories.)

