# clock-distribution
Antikernel Labs clock distribution system

* 1U rackmount
* Two input clocks, one from internal GPSDO and one from external reference
* LMK04806 PLL
* 10x AC coupled LVDS outputs to front panel SMAs (can use single ended or differential)
* 4x output to front panel SFP+ cage for optical clock out (mirrored from clkout0[3:0])
* 1x PLL clock to FPGA for low speed outputs
* 4x LVDS outputs from FPGA
* 1x SFP, 1x SMA reference in for loopback phase correction
