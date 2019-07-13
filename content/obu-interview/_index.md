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
background-image = "img/trama.png"
background-size = "17px"
background-position = "top"
background-repeat = "repeat"
class = "portada"

+++

{{< slide id="home"  template="portadas" background-image="img/tabakalera.jpg">}}

<div class="borders">

<small>Demo for a job position interview</small>

<h2>Introduction to BIM</h2>

<small>15th July 2019</small>


<div class="authors">
<p>Carlos Cámara Menoyo</p>

<small><a href="https://carloscamara.es">carloscamara.es</a> | <a href="https://twitter.com/carlescamara">@carlescamara</a></small>
</div>

</div>

{{% note %}}

Before the counter starts I want to make a disclaimer: Explain assignment and notable differences on study plans between Spain and UK.
I made the following assumptions:
<ul>
<li>First day of first module on BIM.
<ul>
<li>There will be other modules that will provide advanced knowledge</li>
<li>Course content is just a sample. It is likely to be adjusted according to course duration, amongst other issues.</li>
</ul></li>
<li>Students do not have prior knowledge about BIM, but they do on Construction
<ul>
<li>Relatively reduced number of students</li>
</ul></li>
</ul>



{{% /note %}}

---

{{< slide template="pink" >}}

## Session content

1. **Introducing ourselves** (reduced)
2. **Introduction to BIM module** (reduced)
  1. *Why* is this course important for you
  1. *What* are we going to do
  2. *How* are we going to do it
1. **Learning outcomes** (skipped)
2. **Questions**

---

{{< slide template="bg-dark" background-image="/img/about-me/aragon-tv-carlos.jpg" background-opacity="0.4" >}}

## Carlos Cámara Menoyo

**Architect. PhD. Lecturer. Learner**

Life-long learner. Interested in **social aspects** of **design**, **cities** and **technology**, and more particularly how do each one shape the others in a **digital culture**.

https://carloscamara.es | <i class="fab fa-twitter"></i>[@carlescamara](https://twitter.com/carlescamara)

{{% note %}}
Here is where I would introduce myself.
Since we have already had plenty of time disussing about me, I will skip this part.
{{% /note %}}

---

{{< slide template="bg-dark" background-image="img/amor-necro.jpg" background-opacity="0.7" >}}

## About you

Please, introduce yourselves.

{{% note %}}
<p>If we have a reduced number of students, I would ask them for </p>
<ul><li>Names</li>
<li>Prior knowledge/experience on the topic</li>
<li>Motivation</li>
</ul>
{{% /note %}}

---

{{< section >}}
{{< slide template="pink" background-image="img/image-VirtualBuilding.png" background-opacity="0.4" >}}

## About BIM

{{% note %}}

Since we know each other, let's introduce the other agent that will be with us all the course: BIM.

<p>Does anyone...</p>
<ul>
<li>Know what BIM is?</li>
<li>Has some prior knowledge/experience with BIM?</li>
</ul>
{{% /note %}}



---

{{< slide  background-image="img/image-VirtualBuilding.png" background-opacity="0.2" >}}


### **B**uilding **I**nformation **M**odelling
<small>(concept from 1970 and further developed in 1987)</small>

<ul><li>We are actually building a (virtual) building beforehand → simmulation of construction process.</li>
  <ul class="fragment"><li>Everything is connected: a single change, affects all the model (butterfly effect)</li>
  <li>We can extract <i>automated and coherent</i> documentation from it (plans, sections, schedules...)</li>
  <li>We can foresee problems before is too late (always better to fix a line than a wall)</li>
  </ul>
</ul>

{{% note %}}

BIM stands for...

This is an old concept that consists of building a virtual building right from our desk, hence simmulating its construction process.

I know, you might be dissapointed and you might be wondering about what makes BIM so revolutionary?

Ask students: Can you think of any advantage of this revolutionary approach?

{{% /note %}}

---

{{< slide background-iframe="https://www.youtube.com/embed/5Qj9pI5us7o" >}}

---

{{< slide  background-image="img/database-schema-1895779_1280-1080x675.png" background-opacity="0.1" background-size="contain" >}}

### Information is key

* It allows unprecedent possibilities:
  - Project's consistency → error reduction
  * Integrated schedules
  * Coordination between stakeholders
  - Quality Assurance
  - ...
* Everything is possible because of different types of information stored in a relational database within the model.


---

## What is not BIM

* Not a specific software, but a "family" of different softwares (Archicad, Revit, Allplan, Freecad, Vector Works...).
* Not (just) a design tool
* Not (just) a 3D modelling tool

{{< /section >}}

---

{{< slide template="pink" >}}

## About the module

{{% note %}}
Now that we know what BIM is and why is so important, let's see what are we going to do on this module and how are we going to do it.
{{% /note %}}

---

## Module's Goals

1. To get familiar with BIM software
2. To be able to **create** and **extract** information from a BIM model
  1. Drawings (Plans, sections, elevations...)
  2. 3D views
  2. Schedules

---

{{< section >}}

## Module's content

Introduction to BIM

{{% note %}}
In order to achieve those goals, let me introduce the module's content, which is seen as an introduction to BIM.
{{% /note %}}

---

{{< slide  background-video="img/revit-navigation-short.webm" background-opacity="0.2" >}}

### 1. Exploring the BIM model

{{< note >}}

Since everything is stored in a single model, it means that with time, it will become big and complex. As a result, it is of utmost importance to be able to navigate through their different representations to get or create the information we want to.

{{< /note >}}


---

{{< slide background-image="img/archicad.jpg" background-video-loop="true" background-opacity="0.3" >}}

### 2. Constructing

  1. Project setup
  2. Using constructive elements

  {{< note >}}

  The next part of the module consists of creating a model from scratch. In order to do so, we will be using constructing elements. -> not representations as in CAD. This is really important because every object has a bunch of properties, just as in real life + we are not simply drawing but also thinking about how that building would be built.

  {{< /note >}}

---

{{< slide background-image="img/BIM.jpg" background-opacity="0.4" >}}

### 3. Visualizing

---

{{< slide  background-video="img/doors-schedules-short.webm" background-opacity="0.5" >}}

### 4. Scheduling

---

{{< slide template="bg-dark" background-image="img/revizto-markup-in-issue-tracker.png" background-opacity="0.5" >}}


### Out of this module

* MEP (Mechanical, Electrical and plumbing engineering)
* Structural Design
* Analysis (Energy, Life cycle, Structural...)
* Project management
* Collaboration
* Interoperativity with other software

<div class=bg-caption>Revizto Screenshot: real-time issue tracking software for BIM collaboration.</div>

{{% note %}}
Learning BIM is a complex and long process. There are many things that we will not be covering in this module, like...
{{% /note %}}

{{< /section >}}

---
{{< section >}}

{{< slide background-image="img/jury-usj-rotated.jpg" background-opacity="0.3" >}}

## Module's structure

Learning by doing + flipped classroom

---

{{< slide background-image="img/wikihouse.png" background-opacity="0.4" >}}

## Guiding project

* Same project for everyone
* Same project for the whole course
  - Intermediate assignments (milestones)
* Groups of students (grouped by software)
  - Learning from peers
  - Discussion and comparison

---

### Documentation

Wiki-like, collaborative documentation with multimedia content. Made by students.

---

### About my role as a techer

<small>Guide vs Enciclopedia</small>

* I do not know everything
* Even if I did, it is YOU who have to learn
  - you are responsible of your own learning
* I will be guiding you on the process
  - asking Questions
  - answering questions (usually with other questions)
  - pointing to documentation/resources
  - encouraging you
  - ...

{{< /section >}}

---

{{< section >}}

## What this module is not about

---

{{< slide background-image="img/rice-step-by-step.png" background-opacity="0.1" background-size="contain" >}}

### This is not a recipes' module

Looking for the logic behind BIM to solve our problems, not “magical” recipes

---

### This is not a module about how to use specific software
<small>(usually tied to two brands)</small>

- The tools that are used the most differ depending on time and region
- Universities are places to learn, not produce consumers
- I don't get any profit if you buy certain software or not

{{< /section >}}

---

{{< section >}}

## Assessment

---

* Assignments (60%)
* Documentation (30%)
* QA (10%)

{{< /section >}}

---

## What have we learnt?
<small>(today)</small>

* About BIM:
  - BIM definition
  - What BIM is
  - What BIM is not
- About the module:
  - *What / Why / How* are we going to do this course.


---

{{< slide template="pink" >}}

## Questions?
