---
title: "Giovannelli Lab - Team"
layout: gridlay
excerpt: "Giovannelli Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**


Jump to [staff](#staff), [graduate students](#graduate-students), [alumni](#alumni),  [undergraduate alumni](#undergraduate-alumni), [high school alumni](#high-school-alumni) [lab visitors](#lab-visitors). Read [more about me here]({{ site.url }}/myself.html).

## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href=" {{ site.url }}/{{ member.bio }}">{{ member.name }}</a></h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Graduate Students

{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.role }}<br>project: {{ member.info }}<br>Co-Advisor: {{ member.collab }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.role }}<br>project: {{ member.info }}<br>Co-Advisor: {{ member.collab }}</i>
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Undergraduate Alumni
<ul style="list-style-type: none">
    <li>Alessandra Palazzi, UNINA, Spring 2020</li>
    <li>Mariacarmen Del Mondo, UNINA, Spring 2020</li>
    <li>Mattia Acunzo, UNINA, Spring 2020</li>
    <li>Simona Piccolo, UNINA, Spring 2020</li>
    <li>Mariavittoria Brandi, UNINA, Spring 2020</li>
    <li>Andrea Campanile, UNINA, Spring 2020</li>
    <li>Lucia Di peso, UNINA, Spring 2020</li>
    <li>Simone De Meo, UNINA, Fall 2019</li>
    <li>Raffaele Nocera, UNINA, Fall 2019</li>
    <li>Antonio Nappo, UNINA, Fall 2019</li>
    <li>Andrea Campanile, UNINA, Fall 2019</li>
    <li>Mariavittoria Brandi, UNINA, Fall 2019</li>
    <li>Nunzia Nappi, UNINA, Fall 2019</li>
    <li>Alessia Masella, UNINA, Summer 2019</li>
    <li>Angelica De Rosa, UNINA, Summer 2019</li>
</ul>

## High School Alumni
<ul style="list-style-type: none">
    <li>Francesca Cafiero, Liceo Statale "Fonseca", Napoli, Summer 2019</li>
    <li>Domenico Mazza, Istituto Istruzione Superiore "Giancarlo Siani", Napoli, summer 2019</li>
</ul>

## Visitors
<ul style="list-style-type: none">
    <li>Costantino Vetriani, visiting professor, Rutgers University, Fall 2019</li>
    <li>Matteo Selci, visiting student, Spring 2019</li>
    <li>Joy Buongiorno, visiting postdoc, Carnegie Institution of Washington (USA), Jan-Feb 2019</li>
</ul>
