+++
title = "Job Interview for Research Fellow"
description = ""
outputs = ["Reveal"]


[reveal_hugo]
custom_theme = "warwich-creating-interfaces.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

[logo]
src = "img/university_of_warwick_logo_white_50_alpha.png"
alt = "University of Warwick"

[reveal_hugo.templates.bg-dark]
class = "bg-dark"
background = "#000"
data-background-opacity = "0.3"

[reveal_hugo.templates.highlighted]
class = "highlighted-slide"
background = "#34767A"
data-background-opacity = "0.3"

[reveal_hugo.templates.bibliographical-ref]
class = "bibliographical-ref"

[reveal_hugo.templates.bg-caption]
class = "bg-caption"

[reveal_hugo.templates.portadas]
class = "portada"

+++

{{< slide id="home" template="portadas" background="https://creatinginterfaces.eifer.kit.edu/wp-content/uploads/2018/06/workshop_EIFER_VisionsWS2.jpg" background-opacity="0.8" >}}

<div class="borders">

<small>Demo for a Job Interview | 21st January 2021</small>

<h2>Research Fellow</h2>

Creating Interfaces Research Project


<div class="authors">
<p>Carlos Cámara Menoyo</p>

<small><a href="https://carloscamara.es/en">https://carloscamara.es/en</a> | <a href="https://twitter.com/drccamara">@drccamara</a></small>

</div>

</div>

---

{{< slide template="highlighted" >}}

## Content

1. About me (reduced)
   1. Crowdsourcing and VGI
   2. Web Development / Data Visualization
2. About the post
   1. Data visualization
   2. Project Management

---

{{< slide template="bg-dark" id="me" background-image="/img/about-me/hackaton-cadaveres-inmobiliarios.jpg" background-position="center" background-opacity="0.7" >}}

<small>Architect. PhD Urban Sociology. Researcher. Activist. Life-long learner.</small>

## Carlos Cámara Menoyo

I pursue a positive impact on people’s lives through the shaping of physical and digital spaces.

{{% fragment %}}I have focused on the topic of **social and spatial inequities** and **collective-action** to find ways in which cities can be more sustainable and egalitarian.{{% /fragment %}}

<small>https://carloscamara.es/en | <i class="fab fa-twitter"></i>[@drccamara](https://twitter.com/drccamara)</small>

{{% note %}}

My name is Carlos Cámara and I have been involved in plenty of diverse jobs, researches and initiatives, and I came to the conclusion that I what all of them had in common the pursue...

(next frag)

In order to do so, I have focused on...

In this talk I will talk about two projects that have two things in common. (NEXT)

{{% /note %}}

---

{{< slide template="bg-dark" background-image="/img/mapcolabora/mapaton.jpg" background-opacity="0.6">}}

## VGI / Crowdsourcing Experience 

* OpenStreetMap Contributor since 2011
* PI at "[Accessible Zaragoza](https://slides.carloscamara.es/2021-01-18-obu-research-seminar/#/4)" Action-Research project
* Founder of [Collaborative Mapping](https://mapcolabora.org) (association to promote..)


{{% note %}}

Mapeado colabora is an associaciation to promote the use of collaborative mapping throuch lectures, workshops and citizen science projects in collaboration with zaragoza's urban living lab.

{{% /note %}}


---

{{< slide id="geek" class="two-cols" background-color="black" background-image="/img/about-me/github-profile.png" background-opacity="0.2" >}}


### Web development & Data Viz

{{% column %}}

* Web developer in 2004 as self-taught, Freelance from 2007
* CMS
  * Wordpress
  * Drupal
* Static Site Generators
  * Jekyll
  * Hugo 
{{% /column %}}

{{% column %}}

* Started in 2015 for my PhD, self-taught
* Used in own research + freelance
  * Visualizatons: Dashboards, reports, slides
* R: 
  * `tidyverse`, `leaflet`, `tmap`, `plotly`, `flexdashboard`, `shiny`

{{% /column %}}


{{% note %}} 

I learnt web development by myself: I lack of formal training, but I am highly motivated.

Looking forward to apply best pracices

* Reproducible research
  * Packages
  * Dependencies (environments or automagic)
  * Documentation
  * CI


{{% /note %}}

---

## Other relevant skills

* Transdisciplinar
  * Qualitative + Quantitative
* Topics
  * Urban studies, dataviz, concern with environment
* Fast learner
* Team person
  * Worked with computer scientists, environmentalists, geographers...
  * I can "translate" different mindsets
* Love to communicate things
  * I try to make complex things easier to understand

---

{{< slide template="highlighted" >}}

## About the post

---

{{< slide template="highlighted" >}}

## 1. Get to know the data & decide right visual


* Data exploration
* Asking the authors (you!)


{{% note %}} 

I have to be honest: I have looked at your website and regretfully I cannot get an idea of what kind of data have you been gathering nor what do you want to present in a website.

The first thing is to get to know the data in order to decide the right visual: present points, lines, polygons, choropleth, flows, heatmaps, cartograms


{{% /note %}}


---

{{% section %}}

{{< slide template="highlighted" >}}

## 2. Choose the right solution

<!-- ---

{{< slide template="bg-dark" background-iframe="embeds/fablabs-europe-map.html"  background-opacity="0.4" >}}

### Leaflet -->


---

{{< slide template="bg-dark" background-image="img/leaflet-map.gif"  background-opacity="0.4" background-position="center" background-size="contain" >}}

### Leaflet


---

{{< slide background-video="/img/mapcolabora/kepler-bizi.mp4" template="bg-dark"  background-position="center" background-size="contain" >}}

### Kepler

---

{{< slide template="bg-dark" background-iframe="/img/zaccesible/mapbox-protanopia-deuteranopia.html"  background-opacity="0.4" >}}

Custom base maps (Mapbox)

---

{{< slide background-image="/img/plotly-gallery-02.png"  background-opacity="0.8" background-position="center" background-size="contain" >}}

---

{{< slide background-image="img/flextable.gif"  background-opacity="0.9" background-position="center" background-size="contain" >}}


{{% /section %}}

---

{{% section %}}

{{< slide template="highlighted" >}}

## 3 Choose the right medium

---

{{< slide background-image="img/pest-embedded-content.png" template="bg-dark"  background-position="center" background-size="contain" >}}

### HTML Widgets in a website

(Either embedded or integrated -`.Rmd`)

---

{{< slide template="bg-dark" background-image="img/leaflet-slides.gif"  background-opacity="0.9" background-position="center" background-size="contain">}}

### Slides


---

{{< slide background-video="img/reports.mp4" background-opacity="0.6" background-position="center" background-size="contain" >}}

### Reports

See example here: https://ccamara.github.io/stats19_exploration/

---

{{< slide template="bg-dark" background-image="img/static-dashboard.gif"  background-opacity="0.9" background-position="center" background-size="contain">}}


### Dashboards (static)

{{% note %}}

Single Rmarkdown file using Flexdashboard

{{% /note %}}

---

{{< slide template="bg-dark" background-image="img/shiny-dashboard.gif"  background-opacity="0.9" background-position="center" background-size="contain">}}

### Dashboards (Dynamic -Shiny App)

---

{{< slide template="bg-dark" background-image="img/shiny-dashboard2.gif"  background-opacity="0.9" background-position="center" background-size="contain">}}

### Standalone shiny app

Online version: https://ccamara.shinyapps.io/labs-interactive-map/

---

{{< slide template="bg-dark" background-image="img/archtlas.png"  background-opacity="0.9" background-position="center" background-size="contain">}}


### Drupal website

---

### Other (not explored)

* Scrollytelling
* [R Markdown websites](https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html)
* ...

{{% /section %}}

---

{{% section %}}

{{< slide template="highlighted" background-image="img/what-is-scrum.png"  background-opacity="0.4" background-position="center" background-size="contain" >}}


## 4. Managing the project

Basically, a simplified version ~~parody~~ of SCRUM


{{% note %}}
Seeing your CV and experience, I am somewhat ashamed to try to summarise that much Scrum, but I hope I make my point clear.
{{% /note %}}

---

### Create user stories / Tasks

* Describe what is to be achieved (balancing detail/brevity)
* Identify verifiable action points
* Links to all required documents (datasets, wireframes, documents...)
* Created by/with the Product Owner

---

{{< slide background-image="img/github-board.png"  background-opacity="0.2" background-position="center" background-size="contain" >}}

### Organize and priorize

* Organize backlog tasks
  * From more urgent to less urgent
* Commit to do some tasks for the week

---

### Communication with the team

* Daily (short) meetings/emails
  * What we did yesterday + what we want to do today (any foreseen problems/needs)  
* Demo at the end of the sprint (weekly, bi-weekly...)

---

### Develop!

Develop the features.
Mark them to be reviewed.

{{% /section %}}

---

{{< slide template="bg-dark" background-video="/img/gifs/this-is-the-way.mp4" background-opacity="0.8">}}

{{% fragment %}}# Questions?{{% /fragment %}}