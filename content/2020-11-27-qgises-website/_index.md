+++
title = "QGIS.es website"
description = "Sample lecture for post interview."
outputs = ["Reveal"]


[reveal_hugo]
# theme = "white"
custom_theme = "mapcolabora.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

#[logo]
#src = "/img/mapcolabora-logo-horizontal.png"
#alt = "Mapeado Colaborativo"

[reveal_hugo.templates.bg-dark]
class = "bg-dark"
background = "#000"
data-background-opacity = "0.3"

[reveal_hugo.templates.bibliographical-ref]
class = "bibliographical-ref"

[reveal_hugo.templates.bg-caption]
class = "bg-caption"

[reveal_hugo.templates.home]
class = "portada"

[reveal_hugo.templates.verdes]
class = "verdes"
background = "#4CAF50"
data-background-opacity = "0.3"

+++

{{< slide id="home"  template="home" background-image="img/qgises-screenshot.jpg" background-opacity="0.4" >}}

<div class="borders">

<small>QHF November 2020</small>


<h2><a href="https://qgis.es">QGIS.es</a> Website</h2>
<p> A technical overview</p>
</br>

<p>Carlos Cámara-Menoyo</p>

<small>Mapeado Colaborativo<br>
<a href="https://carloscamara.es">carloscamara.es</a> | <a href="https://twitter.com/carlescamara">@carlescamara</a></small>

</div>

{{% note %}}
You found the speaker notes!
{{% /note %}}

---

<!-- {{< slide background-image="/img/sobre-mi.png" background-size="contained">}} -->

{{< slide template="bg-dark" id="yo" background-image="/img/mapcolabora/grupo-aragontv.jpg" background-position="center" background-opacity="0.6" >}}

## Carlos Cámara Menoyo

[Mapeado Colaborativo](https://mapcolabora.org)'s cofounder and QGIS user. Researching about commodifications between **city, technology and society**.


https://carloscamara.es | <i class="fab fa-twitter"></i>[@carlescamara](https://twitter.com/carlescamara)

<div class=bg-caption>All the coordinators (left to right): Joan Cano, Miguel Sevilla, Héctor Ochoa, Carlos & Alejandro Súarez.</div>


---

{{< slide template="verdes" id="why">}}

## Why?

Why a Static Site Generator (SSG)? Why Hugo?
{{< note >}}

Impulsados por nosotros. Ahora queremos alterar esta lógica y estamos abiertos a propuestas.

{{< /note >}}

---

{{% section %}}

{{< slide  background-image="https://www.nyctechmommy.com/wp-content/uploads/2017/04/Teletubbies-Touchscreen-Tummies-v2.jpg" background-position="center" background-opacity="0.2" background-video-loop="false">}} 

<!-- {{< slide  background-image="https://i.pinimg.com/originals/2a/ca/f3/2acaf3443fe63bc4411e16e4c1e69293.jpg" background-position="center" background-opacity="0.2" background-video-loop="false">}}  -->


## SSG 👍

* **No server needed**:
   * **Cheaper:** hosted on github (but could be in gitlab, too)
   * **Faster** (almost lightning fast!): no queries to database
   * **Not hackable** (from server side)
* No need to maintain a number of html files (verbose and cumbersome)

---

{{< slide template="bg-dark" background-image="/img/gifs/great-powers.gif" background-position="center" background-opacity="0.6" background-video-loop="false">}} 

## SSG 👎

* Requires minimal technical skills:
   * Needs to maintain plain text files (`*.md`, `*.rst`)
   * Not GUI*
   * Git
* Needs extra software (installed locally)* -> parses/serves plain text files into html files
* No interaction (web 1.0!)


{{% /section %}}

---

{{< slide template="verdes">}}

## Infrastructure

---

{{< slide template="bg-dark" background-image="img/github-repo.png" background-position="center" background-opacity="0.6" >}}

## Files

Hosted in a [git(hub) repo](https://github.com/qgises/qgis-es) (no server needed)

---

## Continuous deployment


![img/hugo-netlify.drawio](img/hugo-netlify-02.svg)


---

{{< slide template="bg-dark" background-image="img/netlify-cms-edit.png" background-position="center" background-opacity="0.4" >}}

## Admin UI

[NetlifyCMS](https://www.netlifycms.org/) offers:

* User permissions (github)
* WYSIWYG Editor
* Workflow: GUI for managing PR

---

{{< slide template="bg-dark" background-video="/img/gifs/this-is-the-way.mp4" background-opacity="0.8">}}

{{% fragment %}}# Questions?{{% /fragment %}}

---

{{< slide template="bg-dark" background-image="/img/thanks/thanks-brad-pitt-loop-once.webp" background-opacity="0.8">}}

## Thank you!

https://carloscamara.es | [@carlescamaera](https://twitter.com/carlescamara)

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a></small>



