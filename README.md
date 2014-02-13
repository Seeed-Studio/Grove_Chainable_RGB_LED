ChainableLED
---------------

[![ChainableLED](http://www.seeedstudio.com/wiki/images/thumb/9/94/Chanbalelednb1.jpg/300px-Chanbalelednb1.jpg)](http://www.seeedstudio.com/depot/twig-chainable-rgb-led-p-850.html?cPath=156_157)

Arduino library compatible with Grove Chainable LED and the P9813 chip. It allows controlling a chain of LEDS individually. 
Supports both RGB and HSB color spaces for setting the color of each individual LED.



### Usage:

####Installation

1. Grab the latest version from the download section of GitHub.
(https://github.com/pjpmarques/ChainableLED/downloads)

2. Unzip it to your Arduino "libraries" directory. 

3. It should be ready to use. Examples are included.


####Library Interface

```c++
    class ChainableLED {
      public:
        ChainableLED(byte clk_pin, byte data_pin, byte number_of_leds);

        void setColorRGB(byte led, byte red, byte green, byte blue);
        void setColorHSB(byte led, float hue, float saturation, float brightness);
    }
```

For more information, please refer to [author's wiki page](https://github.com/pjpmarques/ChainableLED/wiki) or [seeedstudio's wiki page](http://www.seeedstudio.com/wiki/Grove_-_Chainable_RGB_LED).

----

This software is written by pjp.marques@gmail.com.

Contributing to this software is warmly welcomed. You can do this basically by<br>
[forking](https://help.github.com/articles/fork-a-repo), committing modifications and then [pulling requests](https://help.github.com/articles/using-pull-requests) (follow the links above<br>
for operating guide). Adding change log and your contact into file header is encouraged.<br>
Thanks for your contribution.

Seeed Studio is an open hardware facilitation company based in Shenzhen, China. <br>
Benefiting from local manufacture power and convenient global logistic system, <br>
we integrate resources to serve new era of innovation. Seeed also works with <br>
global distributors and partners to push open hardware movement.<br>


[![Analytics](https://ga-beacon.appspot.com/UA-46589105-3/Grove_Chainable_RGB_LED)](https://github.com/igrigorik/ga-beacon)


