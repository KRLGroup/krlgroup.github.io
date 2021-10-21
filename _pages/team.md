---
title: "KRL Research Group - Team"
layout: gridlay
excerpt: "KRL Research Group: Team members"
sitemap: false
permalink: /team/
---
<h2 class="sapienza-text">Group Members</h2>

 **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**

<h3 class="sapienza-text">Faculty</h3>
{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-5 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="photo {{member.name}}" class="responsive" style="float: right" />
  <h4 class="person-name">{{ member.name }}</h4>
  <i>
    {{ member.info }}
  </i>
    <i>
    {{ member.info }}
  </i>
  <br/>
  {% if member.webpage %}
  <a href="{{member.webpage}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/home.png" alt="Home page {{member.name}}" class="icons" />
  </a>
  {% endif %} 
  {% if member.email %}
  <a href="mailto:{{member.email}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/email.png" alt="Email {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.github %}
  <a href="https://github.com/{{member.github}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/github.png" alt="Githun {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.twitter %}
  <a href="https://twitter.com/{{member.twitter}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/twitter.png" alt="Twitter {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.linkedin %}
  <a href="https://www.linkedin.com/in/{{member.linkedin}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/linkedin.png" alt="Linkedin {{member.name}}" class="icons" />
  </a>
  {% endif %}
  <br>
  {% if member.bio %}
  <b>Bio: </b>{{member.bio }}
  {% endif %}
 </div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

<div class="row"></div>
<h3 class="sapienza-text">PhD Students</h3>

{% assign number_printed = 0 %}
{% for member in site.data.phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}
{% if even_odd == 0 %}
<div class="col-sm-5 clearfix">
{% endif %}
{% if even_odd == 1 %}
<div class="col-sm-5 clearfix">
{% endif %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="photo {{member.name}}" class="responsive" style="float: right" />
  <h4 class="person-name">{{ member.name }}</h4>
  <i>
    {{ member.info }}
  </i>
  <br/>
  {% if member.webpage %}
  <a href="{{member.webpage}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/home.png" alt="Home page {{member.name}}" class="icons" />
  </a>
  {% endif %} 
  {% if member.email %}
  <a href="mailto:{{member.email}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/email.png" alt="Email {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.github %}
  <a href="https://github.com/{{member.github}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/github.png" alt="Githun {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.twitter %}
  <a href="https://twitter.com/{{member.twitter}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/twitter.png" alt="Twitter {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.linkedin %}
  <a href="https://www.linkedin.com/in/{{member.linkedin}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/linkedin.png" alt="Linkedin {{member.name}}" class="icons" />
  </a>
  {% endif %}
  <br>
  {% if member.bio %}
  <b>Bio: </b>{{member.bio }}
  {% endif %}
</div>
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

<div class="row"></div>
<h3 class="sapienza-text">Master Students</h3>

{% assign number_printed = 0 %}
{% for member in site.data.msc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="photo {{member.name}}" class="responsive" style="float: left" />
  <h4 class="person-name">{{ member.name }}</h4>
  <i>
    {{ member.info }}
  </i>
  <br>
  {% if member.bio %}
  <b>Bio: </b>{{member.bio }}
  {% endif %}
  {% if member.webpage %}
  <a href="{{member.webpage}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/home.png" alt="Home page {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.email %}
  <a href="mailto:{{member.email}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/email.png" alt="Email {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.github %}
  <a href="https://github.com/{{member.github}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/github.png" alt="Githun {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.twitter %}
  <a href="https://twitter.com/{{member.twitter}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/twitter.png" alt="Twitter {{member.name}}" class="icons" />
  </a>
  {% endif %}
  {% if member.linkedin %}
  <a href="https://www.linkedin.com/in/{{member.linkedin}}">
  <img src="{{ site.url }}{{ site.baseurl }}/images/icons/linkedin.png" alt="Linkedin {{member.name}}" class="icons" />
  </a>
  {% endif %}
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


<div>
<br/>
<h3 class="person-name">Past students</h3>
<br/>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<!--

## Master Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4 class="person-name">{{ member.name }}</h4>
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

<!---
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
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
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

<!--- ## Former visitors, BSc/ MSc students 

 
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>

## Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration.-->
