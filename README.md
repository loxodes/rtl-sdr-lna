** rtl-sdr-lna **
rtl-sdr-lna is an (untested) LNA for the ezcap digital TV USB stick.
This is intended to improve the sensitivity of it for use as a cheap SDR.

See the following websites for more information:

http://sdr.osmocom.org/trac/wiki/rtl-sdr

http://www.reddit.com/r/rtlsdr

The board is intended to take the place of the F connector.  

All work in this repository is under an MIT license.

![rtlsdrlna schematic](http://kl1xf.org/rtlsdr_lna_sch.png)

![rtlsdrlna layout](http://kl1xf.org/rtlsdr_lna_brd.png)


It isn't a good idea to build this as is, I'm still working on optimizing the component values.
The input return loss needs work, and I haven't yet checked stability... 

![rtlsdrlna s2p](http://kl1xf.org/rtl_sdr_lna_s2p.png)
