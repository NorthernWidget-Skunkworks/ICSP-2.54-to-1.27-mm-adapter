# ICSP-2.54-to-1.27-mm-adapter
Links a standard 2.54 mm (0.1") ICSP/ISP header termination to a set of half-size 1.27 (0.05") pins.

The top side connects to the cable from the ICSP/ISP device via a set of M pins.

The bottom side connects to the PCB through one of a few possible components (see below).


## Recommended components

* [2x3 0.1" (2.54 mm) pitch M header](https://www.digikey.com/product-detail/en/sullins-connector-solutions/PPTC032LJBN-RC/S5517-ND/775975): attaches directly cable from ICSP
* 2x3 0.05" (1.27 mm) pitch header: connects to device with half-size ICSP header
  * M pins to connect to an unpopulated 2x3 set of through-hole pins. This can be:
    * [Our standard-use 0.05" header](https://www.digikey.com/product-detail/en/sullins-connector-solutions/GRPB032VWVN-RC/S9015E-03-ND/1786453), or
    * [A 90-degree-bed 0.05" header](https://www.digikey.com/product-detail/en/sullins-connector-solutions/GRPB032MWCN-RC/S9017E-03-ND/1786480), which can help to keep the PCB out of the way during programming.
  * [F receptacle (list of possibilities here)](https://www.digikey.com/products/en/connectors-interconnects/rectangular-connectors-headers-receptacles-female-sockets/315?k=&pkeyword=&sv=0&pv69=411897&pv69=411921&sf=1&FV=-8%7C315%2C88%7C249730%2C1790%7C7022%2Cii2%7C2172&quantity=&ColumnSort=0&page=1&stock=1&nstock=1&rohs=1&pageSize=25) to connect to an a populated 2x3 M header


<br>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
