GlobalFoundries 180um MCU I/O libraries
=======================================

This repository contains the "I/O cells" implementation as part of
`Google's open source PDK for GlobalFoundries 180nm MCU process node <https://github.com/google/gf180mcu-pdk>`_.

Pad Information
===============

The table below summarizes the available I/O and related pad cells from
the I/O cell reference table for quick reference.

.. list-table:: GF180MCU FD IO pad reference
   :header-rows: 1

   * - Cell
     - Width (um)
     - Height (um)
     - Area (um^2)
     - Pin Count
     - Functionality
     - Pins
   * - asig_5p0
     - 75.0
     - 350.0
     - 26250.0
     - 5
     - 5V WR analogue signal pad with double diode protection (DC current carrying capability 10mA)
     - ASIG5V, DVDD, DVSS, VDD, VSS
   * - bi_24t
     - 75.0
     - 350.0
     - 26250.0
     - 13
     - 5V WR bidirectional pad with 24mA drive strength tri-state output buffer, fast/slow slew rate control, pull-up/down and selectable CMOS/Schmitt input
     - PAD, A, CS, IE, OE, PD, PU, SL, Y, DVDD, DVSS, VDD, VSS
   * - bi_t
     - 75.0
     - 350.0
     - 26250.0
     - 15
     - 5V WR bidirectional pad with programmable drive strength of 4mA, 8mA, 12mA and 16mA tri-state output buffer, fast/slow slew rate control, pull-up/down and selectable CMOS/Schmitt input
     - PAD, A, CS, IE, OE, PD, PDRV0, PDRV1, PU, SL, Y, DVDD, DVSS, VDD, VSS
   * - brk2
     - 2.0
     - 350.0
     - 700.0
     - 1
     - 2um Breaker with VSS
     - VSS
   * - brk5
     - 5.0
     - 350.0
     - 1750.0
     - 1
     - 5um Breaker with VSS
     - VSS
   * - cor
     - 355.0
     - 355.0
     - 126025.0
     - 4
     - Corner cell
     - DVDD, DVSS, VDD, VSS
   * - dvdd
     - 75.0
     - 350.0
     - 26250.0
     - 3
     - Power supply cell (DC current carrying capability 60mA)
     - DVDD, DVSS, VSS
   * - dvss
     - 75.0
     - 350.0
     - 26250.0
     - 3
     - Ground cell (DC current carrying capability 60mA)
     - DVSS, DVDD, VDD
   * - fill1
     - 1.0
     - 350.0
     - 350.0
     - 4
     - 1um filler
     - DVDD, DVSS, VDD, VSS
   * - fill10
     - 10.0
     - 350.0
     - 3500.0
     - 4
     - 10um filler
     - DVDD, DVSS, VDD, VSS
   * - fill5
     - 5.0
     - 350.0
     - 1750.0
     - 4
     - 5um filler
     - DVDD, DVSS, VDD, VSS
   * - fillnc
     - 0.1
     - 350.0
     - 35.0
     - 4
     - Filler for gap width less than 1um
     - DVDD, DVSS, VDD, VSS
   * - in_c
     - 75.0
     - 350.0
     - 26250.0
     - 8
     - 5V WR CMOS input only pad with pull-up/down
     - PAD, PD, PU, Y, DVDD, DVSS, VDD, VSS
   * - in_s
     - 75.0
     - 350.0
     - 26250.0
     - 8
     - 5V WR Schmitt Trigger input only pad with pull-up/down
     - PAD, PD, PU, Y, DVDD, DVSS, VDD, VSS

License
=======

The GF180MCU PDK is released under the `Apache 2.0 license <https://github.com/google/skywater-pdk/blob/master/LICENSE>`_.

The copyright details (which should also be found at the top of every file) are;

::

   Copyright 2022 GlobalFoundries PDK Authors

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
