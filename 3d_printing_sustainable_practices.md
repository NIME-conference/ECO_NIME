<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->
<!-- Template created for ECO_NIME wiki entries by Johnny Sullivan -->

# 3D Printing: Sustainable Practices 

<!-- replace 'Template' with short title; this will be page title when published -->

## Summary of Issue

This section of the wiki will focus on sustainable practices within the field of 3D printing. The goal is to provide guidance and recommendations on minimizing this technology's environmental impact while benefiting from its many advantages.

3D printing is a digital fabrication technique that has revolutionized the manufacturing industry. It allows the production of complex geometries quickly and efficiently, and it has enabled the creation of customized products that were previously impossible or very expensive to produce. In particular, 3D printing has been proven to be a valuable tool in the development of Tangible User Interfaces (TUIs), which are interactive systems that allow users to interact with digital content through physical objects.

Several types of 3D printers are available on the market, but the most common one is the Fused Filament Fabrication (FFF) printer. FFF printers heat and extrude thermoplastic material in thin layers to create a 3D object. However, printing can consume a significant amount of energy and often involve using non-recyclable materials, which can have negative environmental impacts.
Here you will find some useful information on reducing the environmental impact of your 3D printing-related projects.


## Questions Raised

When using a 3D printer, it is advisable to ask yourself the following questions:

1. Am I using software that risks being obsolete or that is hard and/or expensive to obtain?
2. Is my design optimized for 3d printing so that the support materials needed are as little as possible?
3. Is the specific 3D printing technique that I’m using sustainable?
4. Are the materials I’m using recyclable and/or sustainable?
5. Is my object positioned correctly on the building plate?

## Information and recommendations (TL;DR)

1. Use Open Source CAM software like Slic3r or Cura
2. Use machines that do not rely on proprietary software and/or support from private producers. An example of those machines are Prusa 3D printers or Creality printers, those companies do base their products on rep rap technology that (although it is obviously sold commecrialy) are open source and available for everyone.  
3. Use materials that are certified as sustainable. Companies like Reflow, prusament and Closed Loop Plastics bae their business in selling filament for 3d printing obtained recycling materials.
4. If you have that option, choose FFF 3d printing technique. SLA and other technologies produce outcomes that are basically nonrecyclable as they use thermosetting polymers. 
5. When making your G-code, make sure you position your part correctly so that the production does not involve the use of excessive support materials. .
6. Buy and use recycled PLA filament.
7. Recycle waste PLA into new filament as a DIY project. An advanced but achievable project.

----

## Notes

In addition to its ubiquitous use in 3D printing, PLA (Polylactic acid) is used in food packaging. Its a bioplastic, derived from renewable, plant-based materials such as corn starch. A common misconception is that as PLA is a bioplastic, it will naturally decompose; making it an environmentally-friendly choice of material. PLA is biodegradable but unfortunately, will break down exceptionally slowly without the intervention of industrial processes. The rate of decomposition is dependent on the environment the PLA is placed in. Analysts suggest that a PLA bottle could take anywhere from 100 to 1000 years to fully decompose in landfill. Conversely, when placed in an industrial composting facility (an anaerobic digestor), PLA can decompose within three months [[2]]. Filamentive estimated that globally, eight thousand tons of 3D printing material would enter landfill in 2019 [[8]].

Is it possible to send waste PLA, resulting from print errors, discarded support structures and old prototypes, to an industrial composting facility? Municipal waste collection programs are likely to vary geographically. In the UK, domestic compostable waste collection is commonplace, intended for food scraps. However, PLA would be seen as contamination if mixed with this. Furthermore, falling into the catch-all, Recycling Grade 7 (the higher the number, the harder to recycle) PLA cannot be recycled by municipal waste programs [[3]]. Placing large quantities of PLA into domestic recycling would contaminate the recycling stream [[4]].

So where does this leave us? By attending to the familiar three R's (Reduce, Reuse & Recycle), our environmental impact can be reduced in the use of PLA.

### REDUCE
	
There are a few practical measures that can be taken to reduce the amount of PLA filament we use. 

#### Infill density and wall thickness

A reasonably easy adjustment is to reduce the infill density and wall thickness of a 3D print. This will, however, affect the strength of the printed object, and therefore its ability to withstand an applied load. Where strength is integral to a design, it may still be feasible to reduce the infill and wall thickness on test prints (when checking tolerances, for example).
	
#### Tolerances

It may not be necessary to print an object in its entirety to check mechanical tolerances. For example, the tolerance of a screw hole can be scrutinised in isolation, using just a small amount of filament.
	
#### Support structures

Consider the orientation and design of models to reduce the number of support structures required. All3DP has an [excellent article][.3] on this topic. As a general rule of thumb, models that overhang by 45 degrees or more will require support structures, albeit printer dependent. Reducing layer thickness can help improve your printers ability to print overhangs. While reorientating a model on the print bed may eliminate the need for specific support structures, other techniques such as chamfering can be employed to reduce overhang angles.
	
Dual extruder 3D printers can make use of water-soluble PVA filament for support structures. However, there are some concerns that the growing use of water-soluble polymers by consumers and by industry could have a detrimental environmental impact [[5]].

#### Storage

Waste can be reduced by ensuring your filament is stored in a clean, moisture-free environment. A dusty spool of PLA is likely to cause failed prints. Once PLA has absorbed moisture, it becomes brittle, and print quality decreases. [All3DP suggest a range of storage solutions][.4], including in-situ storage for loaded filament. Furthermore, filament dust can be removed using a [clip-on filter][.5].
	
#### Spools

Filament typically comes, loaded on a plastic spool intended to be discarded once the filament is spent. Consider buying filament on a more easily recycled metal/cardboard spool. In the UK, [Filamentive][.6] is a good source of such filament: 
	
### REUSE/RECYCLE

There are ways (albeit somewhat experimental), in which makers can recycle and reuse waste PLA.

#### Reuse

Some creative approaches to repurposing waste filament can be found online. Of interest to guitarists might be these [plectrums][.7] cut from PLA. Another example is the [Plastic Smoothie][.8]. The filament is cut into small pieces using a food processor, melted into a sheet in a small oven then used as raw material for a laser cutter. Another interesting experiment was conducted during a study by Dew and Rosner [[6]].  Waste filament was reheated to use as a fixative for printed objects, and also moulded into new items.

#### Create New Filament

[Filabot][.9] manufactures a system for extruding (and re-spooling) waste filament. This began as an open-source project (the Filabot Wee). The current Filabot machines are sophisticated but costly, perhaps only within the means of larger maker spaces. Alternatively, [open-source projects][.11] exist and [DIY guides][.10] are available, explaining how to create extruding machines.

#### Buy Recycled Filament

It is possible to purchase filament made from recycled PLA. Again, Filamentive is a good source. However, bear in mind that, to retain strength, such filament is likely to be a mix of recycled PLA and virgin material. Filamentive PLA contains 55% recycled material.

## External Links and References

[[1]] https://www.filamentive.com/how-sustainable-is-pla/  
[[2]] https://www.scientificamerican.com/article/environmental-impact-of-corn-based-plastics/  
[[3]] https://all3dp.com/2/3d-printer-recycled-plastic-tips-for-your-waste-plastic/  
[[4]] https://www.theguardian.com/environment/2008/apr/26/waste.pollution  
[[5]] https://www.sciencedirect.com/science/article/pii/S0301479718310016  
[[6]] https://dl.acm.org/doi/10.1145/3322276.3322320  
[[7]] https://all3dp.com/2/is-pla-recyclable/  
[[8]] https://www.filamentive.com/the-3d-printing-waste-problem/  


[.3]: https://all3dp.com/1/3d-printing-support-structures/ "All3DP Support Structures"
[.4]: https://all3dp.com/2/filament-spool-8-ways-to-safely-store-your-filament/ "All3DP Filament Storage"
[.5]: https://www.thingiverse.com/thing:190118 "Filament Dust Filter"
[.6]: https://www.filamentive.com/ "Filamentive"
[.7]: https://hackaday.com/2019/12/08/from-fail-to-wail-guitar-picks-made-from-3d-printed-waste/ "Waste Plectrums"
[.8]: https://all3dp.com/weekend-project-laser-cutting-3d-printed-trash/ "Plastic Smoothie"
[.9]: https://www.filabot.com/ "Filabot"
[.10]: https://www.instructables.com/Build-your-own-3d-printing-filament-factory-Filame/ "Filame"
[.11]: https://reprap.org/wiki/RepRapable_Recyclebot:_Open_source_3-D_printable_extruder_for_converting_plastic_to_3-D_printing_filament

[1]: https://www.filamentive.com/how-sustainable-is-pla/  
[2]: https://www.scientificamerican.com/article/environmental-impact-of-corn-based-plastics/  
[3]: https://all3dp.com/2/3d-printer-recycled-plastic-tips-for-your-waste-plastic/  
[4]: https://www.theguardian.com/environment/2008/apr/26/waste.pollution  
[5]: https://www.sciencedirect.com/science/article/pii/S0301479718310016  
[6]: https://dl.acm.org/doi/10.1145/3322276.3322320  
[7]: https://all3dp.com/2/is-pla-recyclable/  
[8]: https://www.filamentive.com/the-3d-printing-waste-problem/

## Contributor

* [Alex Lucas](mailto:alucas02@qub.ac.uk)

