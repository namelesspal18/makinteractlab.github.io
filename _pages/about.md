---
title: The Lab
---

**MAKinteract** (**MAK**E + **interact**ion) is a research lab in the department of [Industrial
Design](http://id.kaist.ac.kr) at [KAIST](http://www.kaist.edu/html/en/index.html) working at the intersection of design and engineering, in the field of Human-Computer Interaction (**HCI**).

Through user-centered design, fabrication, iterative prototyping and users studies we make new **tangible** and
**wearable** systems and toolkits for helping designers inventing yet unseen interactions.

---

### Meet the makers

{% assign prof = site.data.people[0] %}

<div class="container-fluid">
    <div class="row">
        <div class="col-lg-4 col-md-4 col-sm-4 text-center people">
            <div class="service-box">
                <img src="/images/people/{{ prof.name | append: '_' | append: prof.lastname | append: '.jpg' | downcase  }}"
                    alt="{{prof.name}}" class="rounded-circle">
                <h5>{{prof.name}}<br>{{prof.lastname}}</h5>
                <b>{{prof.position}}<br>Director</b>
                <div class="icons">
                    {% if prof.homepage %}<a href="{{prof.homepage}}"><i class="fas fa-home" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.github %}
                    <a href="http://github.com/{{prof.github}}"><i class="fab fa-github" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.linkedin %}
                    <a href="https://www.linkedin.com/in/{{prof.linkedin}}"><i class="fab fa-linkedin-in" aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.facebook %}
                    <a href=""><i class="fab fa-facebook" aria-hidden="true"></i></a>
                    {%endif%}
                    {% if prof.scholar %}
                    <a href="https://scholar.google.co.kr/citations?user={{prof.scholar}}"><i class="fas fa-graduation-cap"
                            aria-hidden="true"></i></a>
                    {% endif %}
                    {% if prof.email %}
                    <a href="mailto:{{prof.email}}" target="_blank"><i class="fas fa-envelope"></i></a>
                    {% endif %}

                </div>
            </div>
        </div>


        <!-- OTHER MEMBERS -->
        {% include people_grid.html %}
    </div>
</div>

<div class="img-container">
    <img src="/images/demo/test.jpg" alt="The Lab" style="width:100%;">
    <h5 class="text-overlay">Few hours before the CHI deadline...</h5>
</div>

<!-- ![](/images/people/group.jpg) -->


### Collaborators

Our research was possible also thanks to numerous collaborators: 
[Ian Oakley](http://interactions.unist.ac.kr) (UNIST), 
[Daniel Ashbrook](http://danielashbrook.com) (University of Copenhagen), 
[Xing-Dong Yang](https://www.cs.dartmouth.edu/~xingdong/) (Dartmouth College), 
[Liwei Chan](https://scholar.google.co.uk/citations?user=yF0Cw1EAAAAJ&hl=en) (National Chiao Tung University), 
[Pedro Lopes](http://plopes.org) (University of Chicago), 
[Aaron Quigley](https://sachi.cs.st-andrews.ac.uk/people/faculty/aaron-quigley/) and [Hui-Shyong](https://hsyeo.com) (University of St Andrews), 
[Hamed Alavi](http://hamedalavi.com) and [Himanshu Verma](http://human-ist.unifr.ch/people-and-team/himanshu-verma) (University of Fribourg),
[Youngjun Cho](https://uclic.ucl.ac.uk) (UCL), 
[Hyeon-Jeong](Suk http://color.kaist.ac.kr) (KAIST Design), 
[Geehyuk Lee](http://hcil.kaist.ac.kr/?page_id=349) (KAIST School of Computing), 
[Hyoungshick Kim](https://seclab.skku.edu) (SKKU).


---

### For perspective students and collaborators

We look forward to collaborate with new students, researchers, interns, and external collaborators. Specifically, we
are currently searching for students with the following interests:

* Physical computing and electronics prototyping
* Software programming
* Digital fabrication, 3D CAD and mechanical analysis
* Analytical skillset and quantitative statistical analysis

Prospective students are expected to have interest in these subjects, as well as demonstrated making skills, and to
have attended courses such as [*Software Prototyping* (ID311) and *Interaction Prototyping*
(ID220)](http://alsoplantsfly.com/#3).

Finally, the lab cannot directly accept candidates, who instead are required to apply through the [KAIST
admission site](https://admission.kaist.ac.kr/international/). For
further information about the application process please refer to these pages for the
[Master](http://id.kaist.ac.kr/index.php?mid=masterp#), [Ph.D.](http://id.kaist.ac.kr/index.php?mid=phdp), and Master+Ph.D combined programs.

Nevertheless, **before** applying you you might want to consider talking with professor Andrea Bianchi.

Feel free to contact us for further questions

<a href="contact.html" class="button button--large">Contact us</a>