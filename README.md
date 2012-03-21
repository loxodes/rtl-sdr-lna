**rtl-sdr-lna**

rtl-sdr-lna is an (untested) LNA for the ezcap digital TV USB stick.
This is intended to improve the sensitivity of it for use as a cheap SDR.

See the following websites for more information:

http://sdr.osmocom.org/trac/wiki/rtl-sdr

http://www.reddit.com/r/rtlsdr

The board is intended to take the place of the F connector.  

![rtlsdrlna schematic](http://kl1xf.org/rtlsdr_lna_sch.png)

![rtlsdrlna layout](http://kl1xf.org/rtlsdr_lna_brd.png)


It isn't a good idea to build this as is, I'm still working on optimizing the component values.
The input return loss needs work. The amplifier simulates as unconditionally stable. The s2p files for the amplifier are available from the Avago website, and passives from Murata.

![rtlsdrlna s2p](http://kl1xf.org/rtl_sdr_lna_s2p.png)

All layouts and schematics in this repository are under an MIT license.
Feel free to contact me at kleinjt@ieee.org with suggestions, questions, or complaints.
