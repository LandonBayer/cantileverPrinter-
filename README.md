# Cant-Be-Done - The cantilevered 3D Printer

I have never designed a 3D printer before, so naturally when I randomly saw a [Youtube short](https://www.youtube.com/shorts/Ux0-xS0A1uI) portraying an experimental cantilever-style 3D printer, I knew I had to take a shot at it. This printer is absolutely tiny, with a tiny 120 by 120mm build plate and about 220 by 220 base external dimensions. I did this both as a fun challenge, to make it easier to fit in small spaces, and so even the large base and top components can be printed on a standard 220 by 220 printer by anyone. 

Features:
- Small size, easy creation
- NO extrusion, only linear rails and 3D prints to reduce cost
- SKR Mini E3 V3 mainboard with Octoprint on a Raspberry Pi Zero 2 W
- cantilevered style makes for a cool viewable experience
- Can (somewhat) easily fit in to corners
- No external space required (like a bedslinger would)
- Bowden Protoextruder to minimize cost but maximize performance
- E3D V6 hotend for its tiny size and simple nature
- Blower fan for part cooling
- BLTouch probe for leveling Z
- All belted axis - no more leadscrew backlash!
- Standardized belt clamping/motor offsets from rails
- Easy tensioning with slots for motor mounting

![f][f]

[f]: Journal-Pictures/cantelieverfinal3dp.png

[Onshape](https://cad.onshape.com/documents/23b4e50d6c05fcb813eea4aa/w/7fe1f2bc9a8fa9069679c050/e/04335c3d0e682b47a7a284cf?renderMode=0&uiState=688a17f1cdfd5c77b0c78253)

[BOM](https://docs.google.com/spreadsheets/d/1wA5AeRHLFUGY_Gqp5uV-WRdiVc_ecCNHqM5kMq4zwS4/edit?usp=sharing)

Very rough wiring diagram:

![wire][wire]

[wire]: Journal-Pictures/cantelieverfinal3dpwiring.png

| ITEM | PRICE | QUANTITY | TOTAL PRICE | SOURCE | Ordered | Owned | LINK |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mainboard SKR Mini E3 V3 | 48.65 | 1 | 48.65 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256803334065221.html |
| BlTouch clone | 7.57 | 1 | 7.57 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256803153352100.html |
| Aluminum bed | 18.95 | 1 | 18.95 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256803443772403.html |
| Magnetic bed + PEI | 9.93 | 1 | 9.93 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256805924671351.html |
| Silicon bed heater | 10.36 | 1 | 10.36 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256806496223222.html |
| MGN9H 150mm linear rails | 9.6 | 4 | 38.4 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/2255800576028509.html |
| MGN9H 250mm linear rails | 9.86 | 3 | 29.58 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/2255800576028509.html |
| Extruder + Motor | 44.37 | 1 | 44.37 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256808501961686.html |
| Hotend (V6) | 10.99 | 1 | 10.99 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256803006376690.html |
| Stepper motors (need at least 4) | 39.95 | 1 | 39.95 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256808837281579.html |
| 4M-9MM-2GT belt | 18.36 | 1 | 18.36 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/2251832766081359.html |
| Pulley for steppers (5 pack, 20t 10mm 5mm bore) | 3.42 | 1 | 3.42 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256801747103853.html |
| Idler pulley | 1.16 | 4 | 4.64 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/2251832631013486.html |
| 300W Power supply | 19.42 | 1 | 19.42 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256808542915771.html |
| 4010 Blower (part cooling) | 1.96 | 1 | 1.96 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/3256803185681643.html |
| Raspberry Pi Zero 2 W (for octoprint) | 14.99 | 1 | 14.99 | Other | FALSE | FALSE | https://www.microcenter.com/product/643085/raspberry-pi-zero-2-w-arm-cortex-a53-quad-core-processor-512mb-lpddr2-ram |
| M5 25mm dowels (for idlers) | 5.79 | 1 | 5.79 | Aliexpress | FALSE | FALSE | https://www.aliexpress.us/item/2255800287548941.html |
|  |  | Necessary total: | 327.33 |  |  |  |  |
|  |  | With tax: | 347.788125 |
