---
title: Sponsors
description: Who supported the MAKinteract lab at KAIST
---

Our research was only possible thanks to the kind support of funding agencies, companies and the Korean government.


<div class="container-fluid">
    <div class="row justify-content-md-center">

        {% for sponsor in site.data.sponsors%}

        <div class="col-lg-3 col-md-3 col-sm-3">
            <div class="service-box sponsor">
                <a class="greyscale" href="{{ sponsor.url }}"><img src="/images/sponsors/{{ sponsor.logo }}"></a>
            </div>
        </div>
        {% endfor %}

    </div>
</div>

---

### Support us!

If you are interested in sponsoring our research, collaborating with us, visiting the lab or discussing about patent transactions and licensing options, please contact us.

<a href="contact.html" class="button button--large">Contact us</a>



