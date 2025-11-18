## OpenRangefinder 11-17 Update

Redoing the CAD mostly from-the-ground-up again. V0.04 sort of worked but routing the FFC cables was really tedious and messy, trying to model the cables directly this time.

Basic Specs:

* Raspberry Pi CM5 + Waveshare CM5-NANO-B carrier board,
* 4.3" DSI Waveshare (or compat.) screen,
* [IMX585 StarlightEye 1/1.2" sensor: 11.2 x 6.3 mm - 3840 x 2160 - 16:9 sensor](https://github.com/will127534/StarlightEye),
* secondary, offset web-cam for range-finding (WIP!),
* 18650 batteries (initially Anker Nano 5000mAh power bank),
* Waveshare ESP32-S3 AMOLED secondary screen (WIP!).

### Lessons Learned / Changes

* Cables are not that easy to model, but when trying to pack a lot of components into a tight space it is kind of a must.
* Still trying to learn how best model "internals", this time we'll try to co-mode "required empty space" around components along with the component. The idea is to then carve out the main cavities and refine with the "required free spaces".

### CAD Screencaps

The lens shown is a Laowa 6.5mm f/2 lens but the prototype is currently using an 8mm C-mount lens. 

Front/Right View, Transparent Housing

![Front/Right View, Transparent Housing](https://github.com/thingsapart/thingsapart.github.io/blob/main/_res/v5_front_right.jpeg?raw=true)


Back View, Transparent Housing

![Back View, Transparent Housing](https://github.com/thingsapart/thingsapart.github.io/blob/main/_res/v5_back.jpeg?raw=true)


Front View, Transparent Housing

![Front View, Transparent Housing](https://github.com/thingsapart/thingsapart.github.io/blob/main/_res/v5_front.jpeg?raw=true)


left View, Transparent Housing

![Left View, Transparent Housing](https://github.com/thingsapart/thingsapart.github.io/blob/main/_res/v5_left.jpeg?raw=true)


Right View, Transparent Housing

![Right View, Transparent Housing](https://github.com/thingsapart/thingsapart.github.io/blob/main/_res/v5_right.jpeg?raw=true)
