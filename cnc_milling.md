<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->
<!-- Template created for ECO_NIME wiki entries by Johnny Sullivan -->

# CNC Milling

<!-- replace 'Template' with short title; this will be page title when published -->

## Summary of Issue

In this page of the Eco Nime WIKI, we will describe sustainable practices within the field of CNC Milling  

**CNC milling is a highly versatile digital fabrication technique that is commonly used in the manufacturing industry and can also be found in most makerspaces and fablabs**. The term CNC stands for Computer Numerical Control, which means that the milling machine is operated by a computer program that controls the movement of the milling tool. This allows for highly accurate and precise milling operations to be performed, making it a popular choice for a wide range of applications.

**One of the key advantages of CNC milling is its ability to work with a vast array of materials**. Whether it is wood, metal, or FR4 for circuit prototyping, CNC milling is a highly effective technique for subtractive manufacturing. The ability to work with such a wide range of materials has made CNC milling a popular choice for a variety of industries, including aerospace, automotive, and medical device manufacturing.

Despite its widespread use, CNC milling does have its drawbacks in terms of sustainability. However, there are a number of sustainable practices that can be adopted to reduce the environmental impact of CNC milling. These include designing parts for maximum material efficiency, minimizing waste by nesting parts in a single sheet of material, and using recycled or reclaimed materials wherever possible.



## Questions Raised

1. Am I using software that risks being obsolete or that is hard and expensive to obtain?
2. Can other users (or my future self) easily understand and eventually fix my piece?
3. Is my design optimized for CNC milling so that the amount of wasted material is as little as possible?
4. Are the materials I’m using recyclable and/or sustainable?



## Information and recommendations (TL;DR)

1. Use Open Source CAD and CAM software.
2. Produce accurate documentation of your milling process   
3. Use materials that are certified as sustainable and/or recycled ones
4. Make sure you position your paths as close as possible to reduce material waste



----

## Notes

We can summarize the content of this wiki page by claiming  that to reduce the impact of a CNC Milling work you need to make good **documentation** and adopt **open source workflows**, **Use sustainable materials** and **optimize the production** of you CNC milled pieces.

#### Documentation and Open Source Workflows

### Clear Documentation and Open Source Workflow

A very useful strategy to prevent the obsolescence of CNC milling-based projects that we make is to provide future users with accurate documentation so that, in case of need, it will be possible to understand how our circuit is designed.

Using open-source software such as FreeCAD[[1]] or LibreCAD [2]] can be a viable solution to ensure that people in the future will be able to redesign or reproduce our product without having to spend big amounts of money or, worse, having to get a no-longer-available version of a CAD software.

The same goes for CAM software. The Path Workbench that is part of FreeCAD [[3]], BlenderCAM [[4]], and FlatCAM [[7]] allows you to create freely the g-codes that are needed to operate the machine.    

### Well document your project

Also, making a repository where you upload CAD files and indications on how you milled your piece (speed, bit used etc…)is very advisable. Open Hardware Foundation [[6]] offers precious guidelines to achieve this important goal.


###Materials

CNC milling machines can work with many different materials, and it is more than advisable that users consider the environmental consequences of using them. Materials like MDF, for instance, are very cheap but based on synthetic adhesives. MDF is not biodegradable and has no carbon offset value, so it is better not to use it [10]].

Instead, it is advisable to go for wood (very common material for laser cutting), ensure it comes from a sustainable chain, such as FSC [[8]] or PEFC-certified [[9]] wood, Also, materials like paraffine [[11]] (often used to mill molds) are meltable and usable several times, so, make sure you collect the leftovers and reuse them.

Milling machines do not burn materials like laser cutters. Therefore, many materials are not usable with laser cutters, but  are perfect for CNC milling machines (PVC sheets, to cite one [[12]]). Junkyards and basements can represent a very interesting source of CNC milling-compatible materials. Before buying new materials, look around and see if you can recycle something around you.  

In short, do some research when choosing the materials to use in your project.

###Parts positioning

Another important aspect is to position your parts correctly, keeping them close so that the machine doesn’t have to move uselessly and the wasted material is as less as possible. Also, to have a small-sized design, such as a business card, pins, gadgets etc.. to fill the gaps between parts that sometimes are unavoidable can be an idea to avoid material waste for no reason.  

###Test junction, tolerances etc..

Keep in mind that due to the way a CNC milling machine works, some adjustments need to be done when crafting mechanical parts (for example, you might need to add a “Dogbone”[[13]] in your machinery job)
If your design involves some mechanical properties that are potentially tricky, such as joints, t-slots, and other components of this kind, make sure you test them by designing specific small-sized parts and/or by cutting a portion of your design before milling the whole project. 




## External Links and References

[[1]] https://www.freecad.org/
[[2]] https://librecad.org/ 
[[3]] https://wiki.freecad.org/Path_Workbench
[[4]] https://github.com/vilemduha/blendercam
[[6]] https://certification.oshwa.org/basics.html 
[[7]] https://bitbucket.org/jpcgt/flatcam/src/master/
[[8]] https://fsc.org/en
[[9]] https://www.pefc.org/ 
[[10]] https://impactful.ninja/how-sustainable-is-mdf-wood/#:~:text=MDF's%20sustainability%20depends%20on%20its,some%20glues%20emit%20toxic%20gases.
[[11]] https://www.cnczone.com/forums/glass-plastic-and-stone/23207-machinable-wax.html
[[12]] https://plasticsheetsshop.co.uk/pvc-sheets/processing/milling/
[[13]] https://www.bricsys.com/en-eu/blog/everything-you-need-to-know-about-dogbone-fillets



## Contributor

* [Nicolò Nerendino (aka "Chi ha ucciso Il Conte?")](https://chihauccisoilconte.eu/)

