[Home](./index.html)

## Device Management

Massively distributed systems are challenging to update while maintaining consistency among the included devices. They pose additional challenges compared to traditional architectures, such as handling systems that are always on, handling a large number of devices, and moving from centralised to edge architectures. It can not be assumed that all devices are available for updating at the same time, and in many cases it is not feasible to shut down the system for updating. This can make it difficult to deploy updates in a consistent and timely manner, which might be crucial when facing security vulnerabilities. Additionally, the updating procedure itself must not open up for new vulnerabilities.

So, at the heart of this part of the project is the requirement to securely distribute and install updated code in remote devices, and to be able to do so in a timely manner that doesn't require the system to be shut down.

As part of our research we have implemented a prototype update mechanism that addresses the issues stated above. We use this mechanism in a demonstrator that we have developed in collaboration with the municipality of Helsingborg.


### Automatic updates
This video describes the automatic update mechanism implemented in Palcom.

<!-- Automatic Updates -->
{% include youtubePlayer.html id="AU63XRrFu4M" %}


### EDOC 2020 Demo video
This demo video was shown at the EDOC 2020 Conference and won the Best Demo award. It showcases our update mechanism using one of the demonstrator scenarios of the project that we have developed together with the municipality of Helsingborg.

<!-- EDOC 2020 Demo video -->
{% include youtubePlayer.html id="TVLZfQT-IRo" %}


### REBLS 2023 video
This video presents ComPOS, a composition language used for composing IoT systems with weak connectivity, presented at the 10th ACM SIGPLAN International Workshop on Reactive and Event-Based Languages and Systems (REBLS), 2023.

{% include youtubePlayer.html id="Z4SRR1iA3jE" %}

### People involved in this part of the project

* Alfred Åkesson
* [Mattias Nordahl](https://portal.research.lu.se/en/persons/mattias-nordahl)
* [Görel Hedin](https://portal.research.lu.se/en/persons/görel-hedin)
* [Boris Magnusson](https://portal.research.lu.se/en/persons/boris-magnusson)
