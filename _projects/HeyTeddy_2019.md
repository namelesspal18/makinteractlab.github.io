---
title: HeyTeddy
subtitle: "Conversational Test-Driven Development for Physical Computing"
year: 2019
featured_image: /images/projects/heyteddy.jpg # width must be 1600px	
pdf_file: Kim_HeyTeddy_IMWUT19.pdf # put file in the directory FILES
doi_link: https://doi.org/10.1145/3369838
featured: true
---

<!-- 
<div class="gallery" data-columns="1">
	<img src="/images/projects/example.jpg">
	<img src="/images/projects/example.jpg">
	<img src="/images/projects/example.jpg">
</div>
 -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/GUtUtIBBJ74" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- DO NOT CHANGE MANUALLY -->
# {{page.title}}: {{page.subtitle}} ({{page.year}})
Physical computing is a complex activity that consists of different but tightly coupled tasks: programming and assembling hardware for circuits. Prior work clearly shows that this coupling is the main source of mistakes that unfruitfully take a large portion of novices' debugging time. While past work presented systems that simplify prototyping or introduce novel debugging functionalities, these tools either limit what users can accomplish or are too complex for beginners. In this paper, we propose a general-purpose prototyping tool based on conversation. HeyTeddy guides users during hardware assembly by providing additional information on requests or by interactively presenting the assembly steps to build a circuit. Furthermore, the user can program and execute code in real-time on their Arduino platform without having to write any code, but instead by using commands triggered by voice or text via chat. Finally, the system also presents a set of test capabilities for enhancing debugging with custom and proactive unit tests. We codesigned the system with 10 users over 6 months and tested it with realistic physical computing tasks. With the result of two user studies, we show that conversational programming is feasible and that voice is a suitable alternative for programming simple logic and encouraging exploration. We also demonstrate that conversational programming with unit tests is effective in reducing development time and overall debugging problems while increasing users' confidence. Finally, we highlight limitations and future avenues of research.


### References

Yoonji Kim, Youngkyung Choi, Daye Kang, Minkyeong Lee, Tek-Jin Nam, and Andrea Bianchi. 2019. HeyTeddy: Conversational Test-Driven Development for Physical Computing. Proc. ACM Interact. Mob. Wearable Ubiquitous Technol. 3, 4, Article 139 (December 2019), 21 pages. DOI: https://doi.org/10.1145/3369838

<!-- DO NOT CHANGE MANUALLY -->
<a href="{{ site.url }}/files/{{ page.year }}/{{ page.pdf_file }}" target="_blank">paper</a>&nbsp;&nbsp;&nbsp;
<a href="{{ page.doi_link }}" target="_blank">doi</a>

### Source code and material
[GitHub](https://github.com/makinteractlab/heyteddy)

--- 

<a href="/index.html" class="button button--large">Back to projects</a>