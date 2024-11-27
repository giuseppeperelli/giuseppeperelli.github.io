---
layout: about_alt
title: MuSa Jazz
permalink: /musajazz/
subtitle:

nav: true
nav_order: 8

profile:
  align: right
  logo:
  image: Piano_vertical.jpg
  address: >
    <p><i class="material-icons">photo</i>Ph Credits: <a href="https://www.antonellapagani.it/portfolio-p">Antonella Pagani</a></p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

> A problem is just a chance for you to do your best
> (Duke Ellington)

Besides my research and teaching activities, I am a huge passionate about [jazz](https://en.wikipedia.org/wiki/Jazz).
In October 2023, I joined [MuSa Jazz Orchestra](https://www.sapienzacrea.uniroma1.it/strutture/musa-jazz) as a *Pianist*.


##### MuSa - Musica Sapienza

MuSa is the acronym for Musica Sapienza, a project born in 2006 to promote solidarity and culture through music. Its members include students, teachers and technical-administrative staff of this University, who thanks to MuSa can combine their commitment to study or work with their passion for music.

It offers the chance to amateurs and professional musicians within the Sapienza community to join different orchestral or choral ensembles.

MuSa performs in its own musical season ("I venerdì di Musa") and organizes musical parties for the University community on the occasion of Christmas, Carnival and institutional or celebratory events. It can also be requested to provide a musical setting for inaugural or convivial moments of conferences or other events organized by Departments or external institutions.
More inforomation and contact available to the [official page of the project](https://www.sapienzacrea.uniroma1.it/strutture).

##### MuSa Jazz Orchestra

Founded in 2006 and directed by M. Silverio Cortesi until 2023, MuSa Jazz is the orchestral ensemble dedicated to all areas of Jazz.

Currently under the direction of [M. Roberto Spadoni](https://www.robertospadoni.com/), its main activity revolves around the Big Band ensemble, made by around 30 members, including a brass section, a woodwinds section, rythmic section and the support of singers and vocalists.
Beside this, within the Big Band, a number of small ensembles - from duo to septet - can perform in most intimate situations.

Stay in touch with MuSa Jazz Orchestra activities by following us on [Facebook](https://www.facebook.com/profile.php?id=100063580660807) and [Instagram](https://www.instagram.com/musa_jazz_orchestra)!



## Events

#### 2025

**08/05/2025** - TBA

**13/03/2025** - TBA

**12/01/2025** - [Happy New Jazz Year! - Accademia Nazionale dei Lincei](http://www.villafarnesina.it/wp-content/uploads/2024/10/MuSa_2024.jpg)


------------

#### 2024

**18/12/2024** - TBA

**07/12/2024** - TBA

**05/12/2024** - [Honorary Doctorate to Alberto Angela](https://news.uniroma1.it/node/11805)

**18/06/2024** - [Classica al Tramonto](https://www.sapienzacrea.uniroma1.it/node/5858#:~:text=Tempo%20di%20musica%20e%20di,di%20Sapienza%20Universit%C3%A0%20di%20Roma.) - [YouTube Live](https://www.youtube.com/live/j01LP3yl5EQ) - [Radio 3 Broadcast](https://www.raiplaysound.it/audio/2024/11/Radio3-Suite---Il-Cartellone-del-12112024-ebb4c38a-0f55-4314-93a4-2e0181d06ebc.html)

**02/05/2024** - [International Jazz Day 2024](https://news.uniroma1.it/02052024_1830)

**23/04/2024** - [Sapienza, 721° Anniversario dalla Fondazione](https://news.uniroma1.it/23042024_1130#:~:text=Sapienza%2C%20721%C2%B0%20anniversario%20dalla%20fondazione%20dello%20Studium%20Urbis,-Facebook%20Twitter%20instagram&text=Sar%C3%A0%20una%20giornata%20importante%20quella,VIII%20(20%20aprile%201303).) - [YouTube Live](https://www.youtube.com/watch?v=LYoBUfrygbk)

**21/04/2024** - [Jazz Idea Festival](https://conservatoriosantacecilia.it/evento/jazz-idea-2024-festival/)

**14/04/2024** - [Accademia dei Lincei](https://www.instagram.com/p/C5N2avPqEGz/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==)

**08/02/2024** - [MuSa in Maschera](https://www.sapienzacrea.uniroma1.it/node/5858#:~:text=Tempo%20di%20musica%20e%20di,di%20Sapienza%20Universit%C3%A0%20di%20Roma.)

------------

#### 2023

**10/12/2023** - [Accademia dei Lincei](https://www.instagram.com/p/C0i3QJKtlIa/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==)

**25/11/2023** - [Musei in Musica](https://www.uniroma1.it/it/notizia/musei-musica-2023#:~:text=Sabato%2025%20novembre%202023%20torna,organizzativo%20di%20Z%C3%A8tema%20progetto%20cultura.)


{::nomarkdown}
<h2 class="mb-4">Photo gallery</h2>
<!-- <hr class="my-4"> -->
{% for gallery in site.data.gallery %}
    <h3 id="musa">{{ gallery.name }}</h3>
    <div id="carousel-{{ gallery.folder }}" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        {% assign counter = 0 %}
        {% for image in site.static_files %}
            {% assign path = 'images/gallery/' | append: gallery.folder %}
            {% if image.path contains path %}
                {% if counter == 0 %}
                    <li data-target="#carousel-{{ gallery.folder }}" data-slide-to="{{ counter }}"></li>
                {% else %}
                    <li data-target="#carousel-{{ gallery.folder }}" data-slide-to="{{ counter }}"></li>
                {% endif %}
                {% assign counter = counter | plus: 1 %}
            {% endif %}
        {% endfor %}
    </ol>
    <div class="carousel-inner">
        {% assign counter = 0 %}
        {% for image in site.static_files %}
            {% assign path = 'images/gallery/' | append: gallery.folder %}
            {% if image.path contains path %}
                {% if counter == 0 %}
                <div class="carousel-item active">
                    <img src="{{ site.baseurl }}{{ image.path }}" class="d-block w-100" alt="...">
                </div>
                {% else %}
                    <div class="carousel-item">
                    <img src="{{ site.baseurl }}{{ image.path }}" class="d-block w-100" alt="...">
                </div>
                {% endif %}
                {% assign counter = counter | plus: 1 %}
            {% endif %}
        {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#carousel-{{ gallery.folder }}" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carousel-{{ gallery.folder }}" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
    </div>
    <div align=center>
        <br>
        <h3>Photo Credits: {{gallery.credits}}</h3>
    </div>
    <hr class="my-4">
{% endfor %}
{:/}
