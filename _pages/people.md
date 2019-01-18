---
title: People
subtitle: 'Meet the makers from MAKinteract Lab'

---


{% assign prof = site.data.people[0] %}

<div class="container-fluid">
    <div class="row">
        <div class="col-lg-4 col-md-4 col-sm-4 text-center people">
            <div class="service-box">
                <img src="/images/people/{{ prof.name | append: '_' | append: prof.lastname | append: '.jpg' | downcase  }}"
                    alt="{{prof.name}}" class="rounded-circle">
                <h6>{{prof.name}}<br>{{prof.lastname}}</h6>
                <b>{{prof.position}}</b>
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

---

### For perspective students and collaborators

We look forward to collaborate with new students, researchers, interns, and external collaborators. Specifically, we are currently searching for students with the following interests:

* Physical computing and electronics prototyping
* Software programming
* Digital fabrication, 3D CAD and mechanical analysis
* Analytical skillset and quantitative statistical analysis

Prospective students are expected to have interest in these subjects, as well as demonstrated making skills, and to
have attended courses such as [*Software Prototyping* (ID311) and *Interaction Prototyping*
(ID220)](http://alsoplantsfly.com/#3).

Finally, the lab cannot directly accept candidates, who instead are required to apply through the [KAIST
portal](https://admission.kaist.ac.kr/international/). For
further information about the application process please refer to these pages for the [Master](http://id.kaist.ac.kr/index.php?mid=masterp#) and [Ph.D.](http://id.kaist.ac.kr/index.php?mid=phdp) programs.

Nevertheless, **before** applying you you might want to consider talking with professor Andrea Bianchi.

Feel free to contact us for further questions 

<a href="{{ page.contact }}" class="button button--large">Contact us</a>
