+++
title = "An introduction to Research Tools"
description = "A guided overview to its creation process"
outputs = ["Reveal"]


[reveal_hugo]
custom_theme = "warwick-cim.scss"
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
background = "#666"
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

<small>Demo for a Job Interview | 24th September 2021</small>

<h2>An introduction to Research Tools</h2>

A guided overview to its creation process


<div class="authors">
<p>Carlos Cámara Menoyo</p>

<small><a href="https://carloscamara.es/en">https://carloscamara.es/en</a> | <a href="https://twitter.com/drccamara">@drccamara</a></small>

</div>

</div>

{{% note %}}

I have designed this session as an introduction to research tools.

Also, since it is my understanding that CIM students may have very different programming knowledge,

It has two parts: 
1. an introductory part where no prior knowledge is required 
2. 2nd part aimed to learn by example which provides a more technical overview. 

Due to time constraints I won't be able to further develop it, but each topic could be developed in one or more sessions. 

I hope it has the right balance of skillsets.

{{% /note %}}

---

{{< slide template="highlighted" >}}

## Learning outcomes

At the end of this session you will...

1. **Know** what research tools are and why/when are they useful
2. **Identify** types of research tools
3. **Familiarise** with a real case of research tool and its creation process
5. **Familiarise** with some technical concepts (`git`...)
4. **Outline** a possible course of action for developing your research tool

{{% note %}}

At the end of this session you will...

{{% /note %}}

---

{{< slide template="highlighted" id="what">}}

# What?

What is a research tool?

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

{{< slide template="bg-dark" background-image="/img/questions/travolta-question.gif" background-position="center" background-opacity="0.7" >}}


Why do we want science to be reproducible?

---



{{< slide background-color="#fff" background-image="https://imgs.xkcd.com/comics/the_difference.png" background-position="85% 60%" background-size="500px">}}


<!-- ![](https://imgs.xkcd.com/comics/the_difference.png) -->

## Philosophical: 

Embedded in science's core values: 
  
* Transparent
* Traceable 
* Replicable
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

<small>I'm a student of Digital Media and Culture, not an experienced researcher in Urban Analytics...</small>

### Is it for me?

{{% fragment %}} Definitely! It doesn't depend on: 

* Your research expertise/level
    * Student <-> Senior researcher
* Your background or field of knowledge
    * Digital media, Urban analytics...
* Your coding skills (but you'll learn by doign)

**Either way, your research will benefit from it.**

{{% /fragment %}}



{{% note %}}
At this point, you may be wondering if this is something useful for a student of digital media and culture or is something for more experienced researchers in urban analyitcs.

{{% /note %}}

---

{{< slide background="img/research_soft_diagram-spectrum.svg" background-size="70%">}}
