<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->
<!-- Template created for ECO_NIME wiki entries by Johnny Sullivan -->

# Laser Cutting 

<!-- replace 'Template' with short title; this will be page title when published -->

## Summary of Issue

Laser cutting is a popular subtractive digital fabrication technology that has revolutionized the way we produce designs and prototypes. It is an extremely fast and precise method that uses a high-powered laser to cut through a variety of materials such as wood, cardboard, and plastics. This technology has become so accessible that most fab labs/makerspaces have a laser cutter as a standard tool.

**One of the main advantages of laser cutting is its speed**. It can cut intricate designs with high precision at a much faster rate than other traditional methods. Additionally, it can work with a wide range of materials, which makes it a versatile tool for many applications. Laser cutting has become increasingly popular in the DIY community, and its accessibility has made it an affordable option for small businesses and hobbyists alike.

**While laser cutting has its benefits, it is important to note that it does come with some environmental concerns**. The production of the laser cutters themselves can have a high carbon footprint, and the materials used for laser cutting can contribute to waste. However, there are sustainable practices that can be adopted when designing for and using a laser cutter


## Questions Raised

When using a Laser cutting, it is advisable to ask yourself the following questions:

1. Am I using software that risks being obsolete or that is hard and expensive to obtain?
2. Is my design optimized for Laser Cutting so that the amount of wasted material is as little as possible?
3. Am I optimizing the timing of the machine, or can my design be made faster?
4. Are the materials I’m using recyclable and/or sustainable?


## Information and recommendations (TL;DR)

1. Use parametric open-source CAD software to design your objrìects
2. Avoid big engraving works because they take a long time.   
3. Use machines that do not rely on proprietary software and/or support from private producers.
4. In general, the laser cutter burns materials. Try to avoid materials that release toxic fumes, such as MDF or Acrylic (keep an eye on the operator’s health…)


----

## Notes

We can summarise the sustainable strategies presented by saying that if you want to use a laser cutter in a more sustainable way, you need to make sure that your design does not fall into obsolescence’s doom by making your files **open and available for future users** (including your future self), as **fast** as you can, **not waste materials** and use sustainable ones.

#### Open and Available Files

	
A few practical measures can be taken to ensure your project does not become obsolete in a few years.

### Open Source CAD and CAM

Softwares like **FreeCAD** [[1]], **Inkscape** [[2]], and **LibreCAD** [[3]] are completely free, open source and cross-platform, which means that virtually anyone can use them without having to pay any license. This practice breaks a thick barrier and allows you and future users to easily produce spare parts and/or edit your project without starting from scratch, saving time and resources. 
Same principle can be applied to the CAM software that is used to generate the gcode, there are some open source applications [[4]] [[5]] that can be use instead of commercial ones.

### Documentation

Also, it can be a very good idea to organize your files into a well-structured directory where you document the steps that are necessary to rebuild your piece. In this regard, it might be useful to consult the guideline of the **open hardware foundation** [[6]], where they explain in details how this task can be accomplished.

#### Being fast 

When using a laser cutter, it’s quite important that you make sure your pieces are made in the fastest way possible, so that the energy consumed for the production is as low as possible, and the machine is not overstressed and therefore lasts longer

### Low power cuts instead of engraving

The tasks that a laser cutter does are basically two: cutting and engraving. The first one is the fastest as the machine moves to cut a single line, while in the second, the machine acts as a plotter and moves and fires a lot in order to engrave an area.
A good practice that can spare your machine a lot of work can be engraving the contour of a given area and using textures made out of lines instead of engraving a whole area, using the same setting as cutting but using an amount of power that is not enough to cut through the surface. 

### Parts Positioning

Another important aspect is to position your parts correctly, keeping them well close so that the machine doesn’t have to move uselessly and the material wasted is as less as possible. Also, to have a small-sized design, such as a business card, pins, gadgets etc.. for filling the gaps between parts that sometimes are unavoidable can be an idea to avoid material waste for no reason.  

### Test Junctions, Tolerances etc..

If your design involves some mechanical properties that are potentially tricky, such as joints, t-slots, and other components of this kind, make sure you test them by designing specific small-sized parts and/or by cutting a portion of your design before laser-cutting the whole project 

#### Materials

Laser cutters can cut many different materials, and it is more than advisable that users consider the environmental consequences of using them. Materials like MDF [[9]], for instance, are very cheap but based on synthetic adhesives. MDF is not biodegradable and has no carbon offset value, so it is better not to use it.
Also, keep in mind that a lasercutter basically **burns** a material to cut it, and because of this, there are many materials that are not usable with those machines due to the toxic emissions that they provoke when burning (for example PVC, but the list is quite long [[13]]).

Instead, it is advisable to go for cardboard, which is extremely easy to get, carry around, and recycle. Also, when working with wood (very common material for laser cutting), ensure it comes from a sustainable chain, such as FSC [[7]] or PEFC [[8]]-certified wood. 

When working with textiles as well, materials like felt are preferable to synthetic materials such as nylon and neoprene [[10]].

In short, try to do some research when choosing the materials to use in your project, institutions like the European Union [[11]]. and the United Nation [[12]] do provide resources in this regard.


## External Links and References

[[1]] https://www.freecad.org/
[[2]] https://inkscape.org/ 
[[3]] https://librecad.org/ 
[[4]] https://lasergrbl.com/
[[5]] https://github.com/JTechPhotonics/J-Tech-Photonics-Laser-Tool/releases/tag/v1.0-beta_ink0.9
[[6]] https://certification.oshwa.org/basics.html 
[[7]] https://fsc.org/en
[[8]] https://www.pefc.org/ 
[[9]] https://impactful.ninja/how-sustainable-is-mdf-wood/#:~:text=MDF's%20sustainability%20depends%20on%20its,some%20glues%20emit%20toxic%20gases.
[[10]] https://theroundup.org/is-felt-biodegradable-and-eco-friendly/#:~:text=Yes%2C%20natural%20wool%20felt%20can,therefore%20not%20a%20renewable%20resource.
[[11]] https://sdgs.un.org/topics/chemicals-and-waste
[[12]] https://single-market-economy.ec.europa.eu/industry/sustainability_en
[[13]] https://www.troteclaser.com/en-us/learn-support/faqs/unsuitable-materials-laser-processing




## Contributor

* [Nicolò Nerendino (aka "Chi ha ucciso Il Conte?")](https://chihauccisoilconte.eu/)

