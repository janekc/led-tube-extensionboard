# led-tube
PCB design for a portable, battery powered, tube shaped partylight.

It should run with 4 x 18650 lithium battery cells, that can be recharged through USB Power Delivery 3.0 with up to 18W. This would be achived using the IP5328P IC reference desing to handle charging and discharging of the 4 parallel cells.

The IP5328P can output uo to 5v 3.1A which, according to [Quins' real world LED Power consumption sheet](https://quinled.info/2020/03/12/digital-led-power-usage/), would be enough to power around 70 WS2812b 5050 RGB LEDs.

<img width="955" alt="Idea to use VOUT1 to power LEDs and ESP32 with IP5328P" src="https://github.com/janekc/led-tube/assets/32040630/7f33bd0d-97d9-422a-acac-64fe3aaba133">


#### Extra Parts that you will need to buy if you want to build your own tube

- [Acrylic PLEXIGLASS Tubes 50/44mm](https://hbholzmaus.de/epages/Store7_Shop34800.sf/de_DE/?ObjectPath=/Shops/Shop34800/Categories/Rohre/%22Rohre%20satiniert%22)

- [QuinLED-ESP32-ABE Ethernet ESP32 Board](https://quinled.info/quinled-esp32/)

- [18650 lithium batteries](https://www.akkushop.de/de/3400mah-panasonic-18650-li-ion-akku-mit-eigener-schutzschaltung-ca.-69-x-1861mm-beachten/)



#### Projects that have been used as Inspiration

- https://github.com/YC-Lammy/IP5328P-powerbank_design

- https://hackaday.io/project/177748-modular-18650-power-bank

- https://www.flux.ai/jecstronic/powerbank-board

- https://github.com/janekc/diodeplate

- https://github.com/mstuij/QuinLED-ESP32-Breakout

- https://quinled.info/quinled-esp32-kicad-files/



#### Useful datasheets

- http://www.injoinic.com/wwwroot/uploads/files/20200221/ec29931791194a51119ee1d6a4a21efb.pdf



#### Links (not related directly)

- https://github.com/kkr0kk/PowerBank-DIY

- https://kicadrookie.blogspot.com/2022/07/kicad-projects-powerbank-pcb-IP5328P%20.html

- https://www.lcsc.com/search?q=IP5328P

- https://www.reddit.com/r/batteries/comments/onzm58/how_to_get_12v_for_a_amplifier_with_a_ip5328p/

- https://www.ti.com/lit/ug/tiduey1a/tiduey1a.pdf?ts=1696105000442

- https://hackaday.io/project/184947-pi-cm4-carrier-io-board

- https://www.aliexpress.com/item/33057941535.html?aff_fcid=06bf9dcd74484ab2a2f4b222b06f5361-1696411999482-09499-_AgWfRQ&aff_fsk=_AgWfRQ&aff_platform=shareComponent-detail&aff_trace_key=06bf9dcd74484ab2a2f4b222b06f5361-1696411999482-09499-_AgWfRQ&afSmartRedirect=y
