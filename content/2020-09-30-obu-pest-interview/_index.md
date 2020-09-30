+++
title = "Oxford Brookes"
description = "Sample lecture for post interview."
outputs = ["Reveal"]


[reveal_hugo]
# theme = "white"
custom_theme = "obu.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

[logo]
src = "img/obu-logo.png"
alt = "Oxford Brookes University Logo"

[reveal_hugo.templates.bg-dark]
class = "bg-dark"
background = "#000"
data-background-opacity = "0.3"

[reveal_hugo.templates.pink]
class = "pink"
background = "#d10373"
data-background-opacity = "0.3"

[reveal_hugo.templates.bibliographical-ref]
class = "bibliographical-ref"

[reveal_hugo.templates.bg-caption]
class = "bg-caption"

[reveal_hugo.templates.portadas]
class = "portada"


+++

<!-- {{< slide id="home"  template="portadas" background="img/gemma-evans-dqCaaAD-wYw-unsplash.jpg" background-opacity="0.4" >}} -->

{{< slide id="home" template="portadas" background="img/IMG_20200915_145534.jpg" background-opacity="0.6" >}}

<div class="borders">

<small>Demo for a job position interview</small>

<h2>PEST Research Assistant</h2>

<small>30th September 2020</small>

<div class="authors">
<p>Carlos Cámara Menoyo</p>

<small><a href="https://carloscamara.es/en">https://carloscamara.es/en</a> | <a href="https://twitter.com/drccamara">@drccamara</a></small>

</div>

</div>


{{% note %}}
After an excellent background on the need for studying the relationship/impacts between COVID and active travel, I was asked to do a brief introduction demonstrating how could I 

Disclaimer:

* I am new to UK, so I am not 
* Sorry if my proposals are too basic/obvious or too bold: I have only worked on this presentation for an evening, and I've seen you have been working on this topic (or related ones) for years.

{{% /note %}}

---

## PEST's Goals

Increase understanding of place-based policy and activity in relation to active travel in the aftermath of the Covid-19 pandemic

{{% fragment %}} <small> Assess how they support equitable and sustainable transport for most vulnerable colectives/areas </small> {{% /fragment %}}

{{% fragment %}} <small> <p>Assess Active Travel's role in the transition to climate neutrality and healthier and more equitable ecosystems</p> </small> {{% /fragment %}}

{{% note %}}
 by investigating the response of English local planning and highway authorities to the UK government’s Emergency Active Travel Fund (EATF) and Cycling and Walking strategy.
{{% /note %}}

---

{{< slide template="pink" >}}

## Indicators

<ul>
<li class="fragment" data-fragment-index="1">Types:</li>
<ul class="fragment" data-fragment-index="1">
<li>Quantitative (open data repositories, datasets...)</li>
<li>Qualitative (interviews, study cases)</li>
</ul>
<li class="fragment" data-fragment-index="2">Scale:</li>
<ul class="fragment" data-fragment-index="2">
<li>Macro (Country/County)</li>
<li>Local (city)</li>
<li>Micro (cases -eg. George Street)</li>
</ul>
</ul>

---

{{< slide class="big-table" >}}

Indicators' matrix (a draft proposal)

| Scale                   | Analysis units       | Indicator                                                                            | Sources                                                                                                                       |
| ----------------------- | -------------------- | ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| Macro (Country, county) | Legislation          | Number of laws, regulations, measures...                                             | Open Data, Interviews, Desk Research                                                                                          |
|                         |                      | Budget                                                                               |                                                                                                                               |
|                         |                      | Location                                                                             |                                                                                                                               |
|                         | Sales/users          | Number of vehicles/sales per type                                                    |                                                                                                                               |
| Local (City)            | Active travel habits | Routes by type of transport, demographics and time (month, weekday, hours), avg km.. | Strava Metro <small>(free, starting 27/09/2020, [blog post](https://blog.strava.com/the-new-human-powered-era-20951))</small> |
|                         | Highways’ network    | Number of Km by type (pedestrian, bike lanes...)                                     | OpenStreetMap, Open Data Repos                                                                                                |
| Micro (Cases)           | Study case           | Geography (Location)                                                                 | Interviews, Case Study                                                                                                        |
|                         |                      | Stakeholders (Promoter, beneficiaries...)                                            |                                                                                                                               |
|                         |                      | Description                                                                          |                                                                                                                               |
|                         |                      | Impacts (Number of Km...)                                                            |                                                                                                                               |

{{% note %}}
With those indicators, we can create indicators' matrices like the proposed one
{{% /note %}}

---

{{% section %}}

{{< slide background-video="img/dashboard.mp4" background-position="top">}}

## Dashboards / Apps


---

{{< slide background="img/strava-metro.png" background-position="top">}}

### Maps (1)

---

{{< slide background-video="/img/mapcolabora/kepler-bizi.mp4" template="bg-dark" >}}

### Maps (2)

---

### Tables

![](img/tables.png)

{{% /section %}}

---

{{< slide template="pink" >}}

## Data Gathering

---

{{% section %}}

### Stakeholders & Experts

{{% note %}}

I assume this will be the main source of information and is one of the strenghts of the project.

I admit that since I am new to UK, I didn't know any of the stakeholders you've mentioned  (Sustrans, Cycling UK and Living Streets) other than an initial exploration to their websites

{{% /note %}}

---

<ul class="gallery" data-iterations="1" data-interval="2.5" data-mode="full-screen">
  <li><img src="img/sustrans.jpg" alt="Sustrans" style="opacity:0.2;"></li>
  <li><img src="img/cycling-uk.jpg" alt="Cycling UK" style="opacity:0.2;"></li>
  <li><img src="img/living-streets.png" alt="Living Streets" style="opacity:0.2;"></li>
  <li><img src="/img/zaccesible/IMG_20161203_102252.jpg" alt="Accessible Zaragoza: Working with NGOs, Disabled collectives, City Council, Students (Photo: Carlos Cámara)" style="opacity:0.2;"></li>
  <li><img src="img/solasgune-class.jpg" alt="Children interacting with Dashboard on a Walk to school project (Photo: Julian Maguna, Solasgune)" style="opacity:0.2;"></li>

</ul>

{{% note %}}

{{% /note %}}

{{% /section %}}

---

{{< slide  background-image="/img/zaccesible/ruta-ciencia-1.png" background-opacity="0.2" >}}

### Interviews

* Experience in:
  * PhD (key agents in urban commons)
  * MSc (key agents in drupal community)
* Types:
  * Structured/semi-structured
* Tasks:
  * Outline Design 
  * Recording
  * Transcription

---

{{< slide background="/img/R_logo.svg" background-position="80% 60%" background-size="400px">}}

### Datasets

1. Automated downloads <small>(Open Data repositories, stakeholders, Strava Metro...)</small>
   1. Querying APIs
   2. Web scrapping
2. Data munging
   1. Data cleaning
   2. Data calculation
   3. ...
3. Data visualization

---

{{< slide  background-image="/img/zaccesible/tabla-toma de datos.png" background-position="top" background-opacity="0.3" >}}

### Fieldwork

---

{{< slide template="pink" >}}

## Project's structure

---

{{< slide  background-image="img/project-template.png" background-size="1000px" >}}

---

### Datasets

* Rows: observations
* Columns: attributes
  * `id`: unique -> join with other datasets
* Open formats (preferred): compatibility

---

### Control version

* Track files' history
* Sharing with others
* Backup! 😱

---

{{< slide template="pink" >}}

## Results' Dissemination


---

{{< slide background-video="img/dashboard.mp4" background-position="top" background-opacity="0.3">}}

### Dashboards

1. [COVID-19 Dashboard](https://ccamara.github.io/covid_spain/)
2. Walk to school

---

{{< slide background-image="img/medium-post.png" background-position="top" background-opacity="0.3">}}

### Websites

1. My personal website (https://carloscamara.es/en)
2. Guest blog posts ([Medium](https://towardsdatascience.com/considerations-on-the-importance-of-data-and-science-in-data-science-b19f5155fd9c))

---

{{< slide background-video="img/reports.mp4" background-opacity="0.6"  >}}

### (Interactive) reports

1. [STATS19 data exploration](https://ccamara.github.io/stats19_exploration/)

---

{{< slide background="/img/podcast-scalae.png" background-position="top" background-opacity="0.6">}}

### Podcasts

1. Technician:
   1. Scalae (Recording, audio editing, publishing)
2. Guest:
   1. [Arquicafe Stepien y Barno](https://www.youtube.com/watch?time_continue=1252&v=MTtfXY67Xgs&feature=emb_title)
   2. [COVID and participation](#)

<!-- ---

{{< slide background-image="/img/mapcolabora/aragon-abierto.png" background-position="top" background-opacity="0.6" template="bg-dark">}}


### Media (newspapers, TV) -->

---

{{< slide background-image="/img/mapcolabora/aragon-abierto2.png" background-position="top" background-opacity="0.6" template="bg-dark">}}


### Media (newspapers, TV)

---

{{< slide background-image="/img/about-me/talk-cartografies-collaboratives.jpg" background-position="top" background-opacity="0.6" template="bg-dark">}}

### Talks

---

{{< slide background="/img/about-me/google-scholar.png" background-position="top" background-opacity="0.3">}}

### Papers  🎓
  
* [ORCID profile](http://orcid.org/0000-0002-9378-0549)
* [Research Gate](https://www.researchgate.net/profile/Carlos_Camara_Menoyo)
* [Google Scholar](https://scholar.google.es/citations?user=zuCP2PAAAAAJ&hl=ca)

---

{{< slide template="pink" >}}

## Thank you!

{{% fragment %}}Questions? / Comments? {{% /fragment %}}