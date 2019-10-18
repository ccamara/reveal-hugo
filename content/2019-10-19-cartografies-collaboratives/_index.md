+++
title = "Mapas al servicio de la ciudadanía"
description = "Mapeado colaborativo pone la información geográfica al servicio de la ciudadanía. En esta charla explicaré algunos proyectos colaborativos que hemos desarrollado."
outputs = ["Reveal"]


[reveal_hugo]
custom_theme = "mapcolabora.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

[logo]
src = "/img/mapcolabora-logo-horizontal.png"
alt = "Mapeado Colaborativo"

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

{{< slide id="home"  template="home" background-image="img/background-zgz.png">}}

<div class="borders">

<small>II Jornades Cartografies Col·laboratives<br>
19 d'octubre de 2019. Centre Cultural Albareda. Barcelona.</small>

<p>Mapeado Colaborativo:</p>
<h2>Mapas por y para la ciudadanía</h2>

<p>Carlos Cámara Menoyo</p>

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

Cofundador de [Mapeado Colaborativo](https://mapcolabora.org). Investigo sobre las comodificaciones entre **ciudad, tecnología y sociedad**.

Centrado en las desigualdades sociales y espaciales, y en cómo las ciudades pueden ser más sostenibles e igulaitarias y, por tanto, mejorar las condiciones de vida de sus habitantes.

https://carloscamara.es | <i class="fab fa-twitter"></i>[@carlescamara](https://twitter.com/carlescamara)

<div class=bg-caption>El resto de coordinadores (de izquierda a derecha): Joan Cano, Miguel Sevilla, Héctor Ochoa, Carlos y Alejandro Súarez.</div>

---

{{< slide template="bg-dark" id="mapcolabora" background-image="/img/mapcolabora/02-grupo-zac.jpg" background-opacity="0.6">}}

## Sobre Mapeado Colaborativo

Ponemos conocimientos, herramientas y mapas, al servicio de la ciudadanía.
Favorecemos la elaboración de información geográfica voluntaria.

<div class=bg-caption>Una sesión quincenal en ZAC Las Armas.</div>

{{< note >}}
Trabajamos en la construcción y elaboración de información geográfica participativa o voluntaria, para **construir mapas útiles a la ciudadanía**: que se puedan usar como herramientas para una mejor _toma de decisiones_, para _compartir experiencias_ , _visbilizar aspectos concretos_ y ayudar a configurar el modo con el que observamos la realidad.
{{< /note >}}
