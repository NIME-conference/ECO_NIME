<!-- Copy this template to add a new topic. Replace text in {brackets} with your content. -->
<!-- Template created for NIME environment entries by Johnny Sullivan -->

# Video conferencing (Zoom alternatives)

## Summary of issue 

With NIME moving to a hybrid format, video conferencing and communication will be essential for the conference. Additionally, the spread of COVID-19 has meant that the already established practice of everyday video conference calls has increased manyfold. While the carbon footprint of video calls is often significantly lower than that of non-local in-person meetings, a number of parameters can be considered in choosing the least polluting technologies and practices. Additionally, there have been a few privacy concerns related to Zoom in the pass [9].

## Questions Raised

1. What is the carbon footprint of a video call? 
2. What parameters determine the footprint of video calls?
3. What are the different alternatives for video calls?
4. How does the footprint of video calls relate to that of travel? 

<!-- ## Information and recommendations (TL;DR) -->

<!-- {a short summary (with list, links, or whatever best format) of information collected on the topic, and recommendations for addressing it.} -->

-----

## Notes

### Carbon footprint of a video call

- The energy efficiency of the internet has been roughly doubling every two years [1].
- Video calls use 250 MB - 1.3 GB of data per participant per hour, depending on the quality [3].
- The most recent reputable peer- reviewed estimate of the energy intensity of the internet found an average of 0.06 kWh per GB for 2015. Assuming that it is still halving every 2 years, it would now be around 0.015 kWh/ GB [3].
- The German grid carbon footprint is (2018) 0.4690 kgCO2e per kWh [5]. Use link [5] to find the footprint of most countries.
- One hour of video conferencing, then, is between 0.0018 and 0.0091 kgCO2e per hour of video conferencing. 

Based on these numbers, a rough calculation of the relationship between virtual and physical attendance for one person from Berlin for NIME 2021 in Shanghai:

> 8 hours a day for four days (8 \* 4 \* 0.0091): 0.292 kg of CO2e. In comparison, a Flight from Berlin to Shanghai: 2.53 tonnes of CO2 

### Video call sustainability parameters

**Self-hosting:** By self-hosting the conference tools for NIME, we can choose a green provider rather than relying on servers beyond our control.

- Jitsi: https://meet.jit.si/. Jitsi offers self-hosting. Environmental statement for 8x8 (the company owning Jitis) here: https://investors.8x8.com/corporate-responsibility/environment-policy/default.aspx
[3] raises ethical concerns regarding excessive enumerations of executives.
- Jami: https://jami.net/# . Recieves a high envorinmental score in [3] but seems to be in its infancy and may not be reliable enough for NIME. Another positive aspect of Savoir-faire Linux, (the company developing Jami) is a general Commitment toward a "sustainable economy based on cooperation and knowledge" [7].
- Kopano Meet: https://meet-app.io/. Open source peer to peer video conferencing with paid options available (paid edition provides access to a hosted turn service). The company Kopano does not provide environmental statements, but Meet is mostly implemented in Golang which provides a small memory footprint.
- Big Blue Button: https://bigbluebutton.org/. Allows for selfhosting, and has features for limiting the need for screensharing (thus limiting bandwidth) by sharing the pdf slides to each participant's computer, rather than having to screen share.

### Considerations for individuals

Use optical fiber wifi rather than cellphone data: I haven't been able to find conclusive research, but [4] suggests that watching a video on the old 3G cellular network consumes 50 times more energy than on a wifi served by optical fiber cables.

Consider turning off your video when conferencing.

Lower the resolution of the video.


## External Links and References

1. Paper: [Electricity Intensity of Internet Data Transmission: Untangling the Estimates](https://onlinelibrary.wiley.com/doi/full/10.1111/jiec.12630)
2. Article: [Comparison of the energy, carbon and time costs of videoconferencing and in-person meetings](https://www.researchgate.net/publication/260438994_Comparison_of_the_energy_carbon_and_time_costs_of_videoconferencing_and_in-person_meetings)
3. Article: [***Ethical consumer UK*** on video conferencing](https://www.ethicalconsumer.org/technology/shopping-guide/video-conferencing?fbclid=IwAR1cfsoJGGcgypD0mktU6q-eNeDbcNR8P8c2cazyYxK5MKhjJpn22AP65lM)
4. Article: [German article on streaming and online data transfer](https://www.deutschlandfunk.de/streaming-und-datenuebertragung-fuer-videokonferenzen-und.697.de.html?dram%3Aarticle_id=483915&fbclid=IwAR3U8XX_dXAGY4g3Di8ncqSctSkiYMtkNZ4oauWV4J1uIrnJ-c-lGSFa0WA)
5. [Carbonfootprint.com - COUNTRY SPECIFIC ELECTRICITY GRID GREENHOUSE GAS EMISSION FACTORS](https://www.carbonfootprint.com/docs/2019_06_emissions_factors_sources_for_2019_electricity.pdf)
6. [Climate Care carbon calculator](https://climatecare.org/calculator/)
7. [Savoir-faire Linux Commitment Statement](https://savoirfairelinux.com/en/commitments)
8. [Zoom makes privacy and security fixes as millions flock to service](https://edition.cnn.com/2020/04/23/tech/zoom-update/index.html)


----

## Contributors

- [Adam Pultz Melbye](mailto:mail@adampultz.com)
- [Raul Masu](mailto:raul@raulmasu.org)
- [Marije Baalman](mailto:sensestage@nescivi.nl)
