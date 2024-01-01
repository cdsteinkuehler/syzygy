# Rev.A

* SYZYGY template flipped and rotated to align with BeagleV-Fire gerbers

* SYZYGY connector moved to proper location per SYZYGY Pod specification
  (it was off by a small amount)

* Fix minor issues with SYZYGY library parts (eg: SMT parts listed as
  through-hole)

* PCB stackup updated to match OSH Park 4-layer stackup

* Design rules modified for OSH Park, and net classes added for 75 ohm
  single-ended and 100 ohm differential pairs

* Semtech SDI Rx and Tx circuitry added based on Application Information
  in the data sheets and the Arria 10 Reference Design Daughter Card

* Added dual-frequency reference clock (Si513) @ 148.50/148.35 MHz
