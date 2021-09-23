+++
title = "Reproducible Science and Research Tools. and why (and how) should you "
description = "Demo for a Research Software Engineering job position"
outputs = ["Reveal"]


[reveal_hugo]
custom_theme = "warwick-creating-interfaces.scss"
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

{{< slide id="home" template="portadas" background-image="img/what-is-scrum.png"  background-opacity="0.4" background-position="center" background-size="contain" >}}

<div class="borders">

<small>Demo for a Job Interview | 21st January 2021</small>

<h2>An introduction to Research Tools</h2>

An overview to the crucial questions: _what_, _why_, _when_ and _how_.


<div class="authors">
<p>Carlos Cámara Menoyo</p>

<small><a href="https://carloscamara.es/en">https://carloscamara.es/en</a> | <a href="https://twitter.com/drccamara">@drccamara</a></small>

</div>

</div>

{{% note %}}

I have designed this session trying to address your request + showcase some things I've done.
Given the time I'm given this is an introductory session which aims to give an overview of Research tools and learn by example.

{{% /note %}}

---

{{< slide template="highlighted" >}}

## Learning outcomes

1. **Know** what research tools are and why/when are they useful
2. **Identify** types of research tools
3. **Familiarise** with a real case of research tool and its creation process
5. **Familiarise** with some technical concepts (`git`...)
4. **Outline** a possible course of action for developing your research tool

---

{{< slide template="highlighted" id="what">}}

# What?

What is a research software?

---

<!-- {{< slide background="img/research_soft_diagram.png" background-position="80% 60%" background-size="800px">}} -->
{{< slide background-color="#fff" background="img/research_soft_diagram.svg" background-size="800px">}}


{{% note %}}
Something that sits halfway between 

* Research instrument ( microscope )
* Software used in research (Reference manager, Word processors, QAQDAS) (software for general purpose, used by scientists)
* Research tool/software tailored to our needs. Typically does one thing that its crucial for us, and does it well (and in an automated way).

{{% /note %}}


---



{{< slide template="highlighted" id="why">}}

# Why?

Why do we need research tools?

---

Short answer: 

### Research tools make science reproducible

---

{{% section %}}

{{< slide template="bg-dark" background-image="/img/questions/travolta-question-1.gif" background-position="center" background-opacity="0.7" >}}


{{% fragment %}} Why do we want science to be reproducible? {{% /fragment %}}

---



{{< slide background-color="#fff" background-image="https://imgs.xkcd.com/comics/the_difference.png" background-position="85% 60%" background-size="300px">}}


<!-- ![](https://imgs.xkcd.com/comics/the_difference.png) -->

## Philosophical: 

Embedded in science's core values: 
  
* Transparent, 
* Traceable, 
* Useful

{{% note %}}

* others (or ourselves!) should be able to validate/refute it, detect possible errors or limitations, extend it, improve it, adapt it
* ultimately, It should be used for building upon that new knowledge

{{% /note %}}

---

## Practical:

* Reduces time and errors
* Enables **adapting** it to other contexts <small>(same methods, different data; different methods, same data)</small>
* Enables **collaboration**
* Code reuse & sharing **accelerates scientific progress**
* Increasingly required by journals
* Higher **publication impact** (citations, future collaborations, etc)

{{% /section %}}

--- 

### Is it for me?

{{% fragment %}} Definitely! Your research will benefit from it + you do not need to be a coding expert (although it helps + you will become one){{% /fragment %}}

{{% note %}}
There are many different types of research tools, some of which do not require you coding skills

{{% /note %}}



---

{{< slide background="img/research_soft_diagram-spectrum.svg" background-size="70%">}}
