<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->
<!-- Template created for ECO_NIME wiki entries by Johnny Sullivan -->

# Hardware Optimization and Durability

<!-- replace 'Template' with short title; this will be page title when published -->

## Summary of Issue

**When it comes to designing and building hardware, several crucial aspects concerning sustainability emerge**. Unfortunately, designers often overlook the numerous ways in which hardware efficiency can be improved. 

In this wiki page, we aim to shed light on **a few strategies that can assist members of the NIME community in optimizing the design of their interfaces in a more sustainable manner**. By embracing these practices, we can contribute to a greener and more eco-friendly future. 

**By prioritizing durability, designers can create hardware that is built to last, reducing the need for frequent replacements and minimizing waste**. Through this wiki page, NIME community members can gain valuable insights into sustainable design practices, enabling them to create interfaces that are both efficient and long-lasting, thus contributing to a more sustainable future in the field of hardware development.


## Questions Raised

1. Is my design optimized or does it comprehend non-needed parts and/or maretials?
2. How easily will my interface break?
3. In case of damage or malfunction, how easy is it to fix it? 
4. Is my design easily upgradable and/or updatable?
5. Is my interface optimised so that it consumes the least amount of energy possible?



## Information and recommendations (TL;DR)

1. Use the least amount of parts and materials and  possible, 
2. Try to avoid weak parts in your design
3. Allow users (including your future self) to easily access every part of the device
4. Produce accurate documentation 
5. Try to use programming languages that are diffused and available by a vast number of people
6. Implement functions such as Deep-Sleep or Hibernation Power Mode 



----

## Notes

### Minimizing Materials and Fabrication Techniques

A paramount approach to reducing the environmental footprint of a project is to **employ the least amount of materials** and **adhere to a singular fabrication technique.** In this context, laser cutting emerges as an eco-friendly choice. By leveraging laser cutting as the sole fabrication method, not only does it simplify the manufacturing process, but it also minimizes material waste, energy consumption, and the need for multiple resources. The efficiency and precision of laser cutting align with sustainable values, and its versatility permits the creation of intricate designs with high accuracy. Materials have many mechanical properties that are often not used. For example you can bend wood by cutting patterns with a lasercutter[[2]], or design bendable 3d printed aobjects [[3]]. You can also design snapfits that allows you to skip screws [[4]], and CNC mill Japanese-Joinery inspired object [[5]].   

### Designing for Durability and Transport

Crafting a durable device that can withstand the test of time is fundamental in reducing the environmental impact of electronic projects. By avoiding design elements prone to failure, like sharp corners or fragile junctions, the device's overall lifespan increases. Furthermore, considering the device's portability is vital. Recognizing that the device will likely need to be transported or carried around, incorporating protective features to safeguard delicate components during movement can enhance longevity.

### Promoting Accessibility and Repairability

The ethos of sustainability is inextricably linked with repairability [[1]]. To align with this principle, designing the device with easy access to all parts is pivotal. Whether it's the circuitry or the battery, enabling users, including the creator themselves, to easily disassemble and replace damaged parts fosters a culture of repair rather than replacement. This concept not only extends the device's life but also reduces electronic waste and contributes to a circular economy.

### Comprehensive Documentation for Longevity

Accurate and comprehensive documentation stands as a cornerstone of sustainable design. By providing thorough documentation, troubleshooting becomes more accessible, and the creation of spare parts is streamlined. Precise instructions, clear diagrams, and detailed explanations enable users to understand the device's intricacies, facilitating both its maintenance and adaptation for new projects. This practice encourages a community of users to engage with the design and contribute to its ongoing development. This website [[6]] offers many insight on how to produce good documentation.

### Choosing Universally Supported Programming Languages

To ensure the longevity and versatility of the device, the programming language used should be widely diffused and accessible to a broad user base. Languages like Arduino [[7]] and Micropython [[8]] have gained significant popularity due to their ease of use and comprehensive online resources. This choice allows for easy code modification and improvement without the need to reinvent the programming interface. By leveraging established languages, the device's software can evolve with changing needs, without excessive resource consumption.

### Energy Efficiency through Smart Programming

Incorporating energy-efficient programming practices is crucial for reducing the device's overall power consumption. Functions such as Deep-Sleep [[9]] [[10]] or Hibernation Power Mode play a pivotal role in preventing energy wastage during periods of inactivity. By intelligently managing power states through software, the device can operate optimally while minimizing its environmental impact. This approach aligns with the broader goal of conserving resources and reducing the carbon footprint associated with electronic devices.


## External Links and References

[[1]] https://repair.eu/news/the-french-repair-index-challenges-and-opportunities/
[[2]] https://www.instructables.com/Curved-laser-bent-wood/
[[3]] https://www.mdpi.com/2073-8994/11/11/1398
[[4]] https://www.hubs.com/knowledge-base/how-design-snap-fit-joints-3d-printing/
[[5]] https://www.instructables.com/How-to-Use-the-CNC-Mill-to-Improve-Japanese-Joiner/
[[6]] https://hackmd.io/@Oggo2XIlRZ6wwlsXi_vc8Q/By3DNodtq#Appendix-3-Platforms-for-publishing
[[7]] https://www.arduino.cc/en/software
[[8]] https://micropython.org/
[[9]] https://www.arduino.cc/reference/en/libraries/arduino-low-power/lowpower.deepsleep/
[[10]] https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/system/sleep_modes.html




## Contributor

* [Nicolò Nerendino (aka "Chi ha ucciso Il Conte?")](https://chihauccisoilconte.eu/)

