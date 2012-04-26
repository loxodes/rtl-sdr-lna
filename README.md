**rtl-sdr-lna**


rtl-sdr-lna is a LNA for the ezcap digital TV USB stick (or other USB tuners).
This is intended to improve the sensitivity of it for use as a cheap SDR.
It isn't a good idea to build this as is, I'm still working on optimizing the component values.
The amplifier simulates as unconditionally stable.


See the following websites for more information on the rtl-sdr:

http://sdr.osmocom.org/trac/wiki/rtl-sdr

http://www.reddit.com/r/rtlsdr

The board is intended to take the place of the RF connector on the ezcap.  


![rtlsdrlna schematic](http://kl1xf.org/rtlsdr_lna_sch.png)

![rtlsdrlna layout](http://kl1xf.org/rtlsdr_lna_brd.png)

The noise figure measurements came out better than expected, I'm probably measuring incorrectly.

![rtlsdrlna s2p](http://kl1xf.org/rtlsdrlna_nf_gain.png)

![rtlsdrlna s2p](http://kl1xf.org/rtl_sdr_lna_s2p.png)


s2p files for simulation are available from Avago and Murata. I'm using ADS for simulation, qucs would be a free open source alternative.

http://www.avagotech.com/pages/en/rf_microwave/amplifiers/low_noise_amplifiers/mga-62563/

http://ds.murata.co.jp/software/simsurfing/en-us/index.html


All layouts and schematics in this repository are under an MIT license.
Feel free to contact me at kleinjt@ieee.org with suggestions, questions, or complaints.
