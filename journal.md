---
title: "Canteliever Printer"
author: "LandonBayer"
description: "Designing and building a custom cantelievered mini 3D printer"
created_at: "2025-07-20"
---
Total time spent:  hours

## **7/20/2025 Log 1: Project Goals and initial BOM**

To start this off, I decided upon a couple design goals for this project. The main reason I'm doing this is just to see if I can and because the [canteliever style](https://www.youtube.com/shorts/Ux0-xS0A1uI) is very interesting. Taking advantage of this style, here are my goals:

- Small 120 x 120mm build volume to make the printer easy to fit in to any space
- No extrusion, use the rails as the frame
- Make it a "corner" so it can sit cleanly in a corner of a wall and be completely functional
- XY at the top, moving Z 
- Affordable, reasonably high quality, reasonably fast (I'm coming from an Ender 3 so not expecting much)

As usual, I made my [Onshape document](https://cad.onshape.com/documents/23b4e50d6c05fcb813eea4aa/w/7fe1f2bc9a8fa9069679c050/e/448736e2902a950e6c5dd058?renderMode=0&uiState=687e405897e37c02a58bec0e) and a starter [BOM](https://docs.google.com/spreadsheets/d/1wA5AeRHLFUGY_Gqp5uV-WRdiVc_ecCNHqM5kMq4zwS4/edit?usp=sharing) to see if this is possible. I'm using a fellow [Hack Club contributors BOM](https://docs.google.com/spreadsheets/d/1phz7-RffRIvpMKJ_e924fQqCT83ikvXl2FwaxxTpVO4/edit?usp=sharing) as a starting point, since I've never built a printer before. Also, since I'm still waiting for approval on my other project, I haven't made an Aliexpress account and see all the welcome deal prices, so I'm currently marking them as full price but expecting the project to be much cheaper. Even then, I have most components selected and am still under $300 for the printer, which is pretty impressive to me.

I began by putting together the BOM as best I could, finding some 3D models for my linear rails, motors, and controller, and started a rough model which I will continue later. This was mostly about getting that BOM together to figure out how much I need to do and how much it'll cost.

![roughmodel][rough]

[rough]: Journal-Pictures/roughlayout3dp.png

Time spent: 2.5 hours

## **7/21/2025 Log 2: Refining CAD**

Today I really tried to get the CAD into a better spot and figure out how everything will go together. I decided to expand the base to fit the full 200mm rails in between the Z axis ones sticking up, which should also make packaging for electronics easier later on. I'm still satisfied with the size, as it'll work out to be pretty much exactly 220x220, which is the size of the bed on my old 3D printer (which is significantly larger). I began adding holes and slots for the motor tensioning and lead screw attachment. It does pain me in a sense to use the leadscrews as structural members since I loose some travel, but it is much cheaper than using extrusion and may even be stronger. It still needs much refinement, but it's a start that I can pick up on tomorrow. Regardless, here's a picture of the working design:

![lessroughlayout][lessrough]

[lessrough]: Journal-Pictures/lessroughlayout3dp.png

Time spent: 1.5 hours