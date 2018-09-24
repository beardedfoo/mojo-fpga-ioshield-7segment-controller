# mojo-ioshield-7segment-controller
A controller module for the Mojo v3 FPGA IO Shield 7-segment display implemented in Lucid HDL.

In order to use this you must have the Mojo FPGA IO Shield inserted into the Mojo FPGA. Before compiling add the IO Shield UCF contraints file in the Mojo IDE using the Project->Add Component menu.

To use this as a library download the `ioshield_seven_segment_controller.luc` file and add it to your project. To see the demo create a new project and add `ioshield_seven_segment_controller.luc` and `mojo_top.luc` to the project, overwriting the previous `mojo_top.luc` file.
