+++
title = "Crowdsourcing ciudadano para visualizar y comprender la ciudad"
description = ""
outputs = ["Reveal"]


[reveal_hugo]
custom_theme = "obu.scss"
custom_theme_compile = true
plugins = ["plugin/gallery/gallery.plugin.js"]

#[logo]
#src = "/img/warwick/university_of_warwick_logo_white_50_alpha.png"
#alt = "University of Warwick"

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

<small>Segundo Congreso Internacional Filosofía y Ciudad<br>
Imaginar, (Con)Vivir y habitar<br>
5-7 de octubre de 2022</small>

<h3>Crowdsourcing ciudadano para visualizar y comprender la ciudad</h3>

<p>Dr. Carlos Cámara Menoyo</p>

<small><a href="https://warwick.ac.uk/fac/cross_fac/cim/">Centre for Interdisciplinary Methodologies</a>, University of Warwick<br>
<a href="https://carloscamara.es">https://carloscamara.es</a> | <a href="https://twitter.com/carlescamara">@carlescamara</a></small>

</div>

{{% note %}}
You found the speaker notes!
{{% /note %}}

---

{{< slide template="bg-dark" id="yo" background-image="/img/about-me/hackaton-cadaveres-inmobiliarios.jpg" background-position="center" background-opacity="0.7" >}}

## Carlos Cámara Menoyo

Investigo sobre las comodificaciones entre **ciudad, tecnología y sociedad**. 

Trabajo con análisis y visualización de datos.

Interesado en cómo las ciudades pueden ser más sostenibles, vivibles e igulaitarias.

<small>https://carloscamara.es | <i class="fab fa-twitter"></i>[@carlescamara](https://twitter.com/carlescamara)</small>

---

## Preámbulo: Ciudades y datos

Consenso:
- Papel de las ciudades
- Datos son necesarios para comprenderlas y para evaluar las medidas.
- Muchas iniciativas
  - Smart cities
  - Digital twins

Está bien porque ponen la ciudad en el centro
Limitaciones:
Estas aproximaciones suelen responder a XXX  ser positivistas, 
Entienden que las ciudades son todas iguales, tiene los mismos problemas y las soluciones.

Quiero plantear una aproximación que, si bien también tiene ciertas similudes, como la toma de datos, en su esencia es radicalmente opuesta: el crowdsorcing ciudadano.


Mi charla se centrará en un tipo de visualizaciones 

---



## Contenido

Charla sobre crowdsorcing ciudadano

- Crowdsorcing
- 2+1 casos de estudio
  - Zaragoza Accesible
  - Eskola Bideak
  - Walkability (AI + un inicio de crowdsorcing)
- Lecciones desde la práctica: otenciales y delimitaciones

---

{{% section %}}

## Preámbulo

Dejad que empieze con una provocación

---

{{< slide template="bg-dark" background-image="https://unhabitat.org/sites/default/files/styles/featured_image_header_xl_focal/public/2022/04/51720665047_5407e85933_k.jpg?h=a1e1a043&itok=1CHQ3TNw" background-position="center" background-opacity="0.5" >}}

> En la actualidad, **más de la mitad de la población mundial (un 54%, o 4.000 millones de personas) vive en ciudades.** [...] Para  **2030, se calcula que la cifra de personas que vivan en ciudades alcance los 5.000 millones** y para **2050** se prevé que lo hagan **dos tercios de la humanidad.**
>
> -- Naciones Unidas, 2013


{{< frag c="Ciudades" >}} {{< frag c="| Datos" >}}

{{% note %}}
Dejad que empieze con una provocación, con esta frase tan manida que odio y que estoy seguro de que todos hemos leído, oído o incluso dicho en algún momento de nuestras vidas:

La destaco porque, con toda la problemática que tiene, tiene dos de los tres ingredientes de los que quiero hablar hoy:

- Ciudades. NEXT Son importantes
- No lo digo yo, no lo dicen unos activistas. Lo dice Naciones Unidas. Lo dicen los datos.

{{% /note %}}

---

## Ciudades


---

{{< slide template="bg-dark" id="datos" background-image="img/data-new-oil.jpg" background-position="center" background-opacity="0.7" >}}


## Datos

---

{{< slide template="bg-dark" background-image="https://urbanbigdata.github.io/01-lecture-intro/images/data_new_oil.png" background-position="center" background-opacity="0.7" >}}

---

{{< slide template="bg-dark" background-image="https://www.geodan.com/media/1565/screenshot-21.png" background-position="center" background-size="contain" background-opacity="0.7" >}}
<!--Fuente: https://www.geodan.com/knowledge-and-innovation/managing-urban-processes-intelligently-with-the-amsterdam-smart-city-dashboard/-->

## Datos y ciudades

{{% /section %}}

---

## Crowdsorcing

Ciudadanía implicada. 
Muchas maneras de entenderlo

- No son meros sensores de datos (extractivismo) -> Ciudadanía implicada en la toma de datos, pero también en el diseño y la toma de decisiones
- Para mi, lo importante es el conocimiento local, y la capacidad de mobilización ciudadana

Ligarlo con el paper de Joao: Modes of engagement : reframing ‘sensing’ and data generation in citizen science for empowering relationships

