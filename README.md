# Simple portable Arduino Nano HF SWR/POWER meter
Arduino Nano based portable SWR/POWER meter, which can measure SWR and POWER on HF bands from 10-100 mW up to 110W. It is based on popular design with tandem match on binocular toroids and calibrated by using built in power meter from commercial HF transceiver. Could be used to measure power and swr on qrp/qrpp transceiverers and well as on tranceivers operating with qro levels up to approximately 110W.

![alt text](extras/images/tandem.jpg)

Metal box from junk is used as a case with SSD1306 display and two PL connectors, powered from 9V battery.

![alt text](extras/images/meter.jpg)

Two mix 43 or 52 toroids from junk box are used.

![alt text](extras/images/cores.jpg)

Needs re-calibration if re-built with another SWR bridge by adjusting `correctionTable` values in the sketch.

