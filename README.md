**rtl-sdr-lna**


rtl-sdr-lna is a LNA for the ezcap digital TV USB stick (or other USB tuners).
This is intended to improve the sensitivity of it for use as a cheap SDR.

The amplifier is stable, but the matching could probably be improved.

See the following websites for more information on the rtl-sdr:

http://sdr.osmocom.org/trac/wiki/rtl-sdr

http://www.reddit.com/r/rtlsdr

The board is intended to take the place of the RF connector on the ezcap.  


![rtlsdrlna schematic](https://github.com/loxodes/rtl-sdr-lna/raw/master/rtlsdr_lna_sch.png)

![rtlsdrlna layout](https://github.com/loxodes/rtl-sdr-lna/raw/master/rtlsdr_lna_brd.png)



s2p files for simulation are available from Avago and Murata. I'm using ADS for simulation, qucs would be a free open source alternative.

http://www.avagotech.com/pages/en/rf_microwave/amplifiers/low_noise_amplifiers/mga-62563/

http://ds.murata.co.jp/software/simsurfing/en-us/index.html

The PCB can be ordered from OSH Park for $3.15 here: http://oshpark.com/shared_projects/ExVzBewI

All layouts and schematics in this repository are under an MIT license.
Feel free to contact me at kleinjt@ieee.org with suggestions, questions, or complaints.
