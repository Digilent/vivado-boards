# Vivado Board Files for Digilent FPGA Boards

This repository contains the files used by Vivado IP Integrator to support Digilent system boards. They include board interfaces, preset configurations for the IP that can connect to those interfaces, and the constraints required to connect the pins of those interfaces to physical FPGA pins. Memory Interface Generator (MIG) project files are also included for non-Zynq boards which can be used to configure the Xilinx MIG IP for use with Microblaze systems.

The `old` folder is for use with Vivado versions 2014.4 and below. The `new` folder covers Vivado 2015.x and above.

Installation instructions for the `new` files can be found in [Section 3](https://reference.digilentinc.com/vivado/installing-vivado/start#installing_digilent_board_files) of the *Installing Vivado, Xilinx SDK, and Digilent Board Files* guide on the Digilent Wiki.

Installation instructions for the `old` files can be found in the [Installing Vivado Board Files for Digilent Boards (Legacy)](https://reference.digilentinc.com/vivado:boardfiles) guide on the Digilent Wiki.

## Notes

* Boards with ChipKit/Arduino headers have the pin locations of CK_IO10 and CK_SS swapped in order to support connection to the [Multi-Touch Display Shield](https://reference.digilentinc.com/reference/add-ons/mtdshield/start). This is not an ideal solution, and may be revised in future. See [Issue 5](https://github.com/Digilent/vivado-boards/issues/5) for more information.