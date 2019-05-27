+++
title = "Accessible Zaragoza"
description = ""
outputs = ["Reveal"]


[reveal_hugo]
# theme = "white"
custom_theme = "usj.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

# custom_theme = "css/usj.css"
# custom_theme_compile = false

[logo]
src = "/img/usj/logo-usj-negro.png"
alt = "Universidad San Jorge Logo"

[reveal_hugo.templates.bg-dark]
class = "bg-dark"
background = "#000"
data-background-opacity = "0.3"

[reveal_hugo.templates.bibliographical-ref]
class = "bibliographical-ref"

[reveal_hugo.templates.bg-caption]
class = "bg-caption"

+++

{{< slide template="bg-dark" id="home"  background-image="img/portada.png" background-opacity="0.8">}}

Past, present and future of

## Accessible Zaragoza study case

Improving handicapped people's autonomy through collaborative mapping



<small>Carlos Cámara | Javier Corzán | Javier Claver | Miguel Sevilla | Ana Ruiz</small>

{{% note %}}
You found the speaker notes!
{{% /note %}}

---

{{% section %}}

## Background (2016)

- 1980 - Present: I am a nerd who loves *technology*, *maps*, *cities* and, particularly, their *social implications*.
* 2016: **AOS Research group**: We had finished *Social Map Risk* (2013-2015) project about *Social inequities and urban morphology*.
* **Private Sponsorship** by Bantierra-Fundación Adecco aimed to promote action research projects regarding disabilities.
  - Replacement: Ángel Comeras (2010-2014) -> Carlos Cámara (2015-2016)

{{% note %}}
Let me start with a confession/disclaimer: I am a nerd. A nerd who loves collaboration, technology, maps, cities and, more specifically their social dimension and how they relate to each other. This is important to understand everything else.

Another important issue is that, on that in 2016, at AOS we had just finished our main research project: Zaragoza's Social Risk Map
Being said that in 2015, I replaced Angel Comeras as main researcher at the Bantierra-Fundación Sponsorship aimed to...

{{% /note %}}

---

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1FEzze9hjnmD4oHz5vfp3mpTFQi7ek9TwzJPMtx1lXtU&font=Default&lang=en&hash_bookmark=true&initial_zoom=2&start_at_slide=3&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

---

### Bantierra-Fundación Adecco sponsorhip (2016)

New people, new approach. New opportunities.

1. Extending the research to **urban scale**
  1. From buildings to cities
2. Focusing on Service-Learning dimension
2. Connecting (unconsciously) with our prior research on (social) **exclusion and urban morphology**.

{{% /section %}}

---

## The problem(s)

People with disabilities cannot be fully autonomous when moving in a city (especially in an unknown city). Two types of exclusion:

* Physical: urban design
* Technological: specialized apps/services

---

{{< slide background-image="img/esquema-colores-mudo.png" background-opacity="0.2" background-size="contain">}}

## Our Goal

<!-- ![](img/esquema-colores.png) -->

The creation of a **pilot**

* Map capable of:
  - Assessing Zaragoza in terms of accessibility
  - Providing routing calculations for disabled people in order to improve their autonomy
- Test a protocol/methodology

---

{{% section %}}
## Our Principle: Open and collaborative project

---

### Political decision:
  - Results should be used and shared by anyone if they are to be of any use
  - Citizenship has to be part of it

---

### Pragmatical decision:
  - Overcome our own limitations (staff, infrastructure)
  - Reduce setup time

{{% /section %}}


---

{{< slide transition="zoom" template="bg-dark" background-image="img/osm-zgz.png" background-opacity="0.8">}}

## OpenStreetMap

The wikipedia of the maps

* **Crowdsorced approach** (data gathering, standardization)
* **Sharing data** (legally + technically): return to society

{{% note %}}
More specifically, this principle led us to use OSM.
{{% /note %}}

---

{{< slide transition="zoom" >}}

## Collaboration with other organisations

* [Mapeado Colaborativo](https://mapcolabora.org) (Zaragoza Activa)
* Association/Activism:
  - Discapacitados Sin Fronteras
  - Mundo Crip
  - Ganchillo Social
- Administration:
  - Civic Centers
