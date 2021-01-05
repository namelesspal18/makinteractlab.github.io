---
title: VirtualWire
subtitle: 'Supporting Rapid Prototyping with Instant Reconfigurations of Wires in Breadboarded Circuits'
year: 2021
featured_image: /images/projects/virtualwire.jpg # width must be 1600px
# pdf_file: Lee_VirtualWire_TEI21.pdf # put file in the directory FILESii
# doi_link: https://doi.org/
featured: true
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/vWRRjfUocuw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- DO NOT CHANGE MANUALLY -->

# {{page.title}}: {{page.subtitle}} ({{page.year}})

Assembling circuits is a challenging and time consuming activity for novice makers, frequently resulting in incorrect placements of wires and components into breadboards. This results in errors that are difficult to identify and debug, and delays that hinder creating, exploring or reconfiguring circuit layouts. This paper presents VirtualWire, a tool that allows users to rapidly design and modify circuits in software and have these changes instantiated in real-time as electrical connections on a physical breadboard. To achieve this, VirtualWire dynamically translates circuit design files into physical connections inside a hardware switching matrix, which handles wiring across breadboard rows and to/from an embedded Arduino. The user can interactively test, tune, and share different circuit layouts \changed{for an Arduino shield}, and once satisfied, can fabricate the circuit on a permanent substrate. Quantitative and qualitative user studies demonstrate that VirtualWire significantly reduces the time taken for (by 37%), and the number of errors made during (by 53%) circuit assembly, while also supporting users in creating readable, space-efficient and flexible layouts. 

### References

Woojin Lee, Ramkrishna Prasad, Seungwoo Je, Yoonji Kim, Ian Oakley, Daniel Ashbrook , Andrea Bianchi. **VirtualWire: Supporting Rapid Prototyping with Instant Reconfigurations of Wires in Breadboarded Circuits**. To appear in _TEI 2021_.

<!-- DO NOT CHANGE MANUALLY -->

<a href="{{ site.url }}/files/{{ page.year }}/{{ page.pdf_file }}" target="_blank">paper</a>&nbsp;&nbsp;&nbsp;
<a href="{{ page.doi_link }}" target="_blank">doi</a>

---

<a href="/index.html" class="button button--large">Back to projects</a>
