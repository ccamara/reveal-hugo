+++
weight = 10
+++

{{< slide id="osm" template="bg-dark" background-image="img/osm-donostia.png" background-opacity="0.6">}}

## OpenStreetMap

AKA "La wikipedia de los mapas"

* **Enfoque colaborativo** (toma + almacenamiento de datos)
* **Compartir datos** (legalmente + técnicamente): retorno social

**OSM es la mayor y más precisa base de datos espacial libre del mundo**

{{% note %}}
More specifically, this principle led us to use OSM.
{{% /note %}}

---

{{< slide template="bg-dark" background-image="img/osm-visible.png" background-opacity="0.8">}}

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">Esto es lo que se ve en https://openstreetmap.org</a>


<!-- ---

{{< section >}}

{{< slide template="bg-dark" background-image="img/osm-visible-standard.png" background-opacity="0.8">}}

## Son muchos mapas

---

{{< slide template="bg-dark" background-image="img/osm-visible-cycle.png" background-opacity="1">}}

---

{{< slide template="bg-dark" background-image="img/osm-visible-transport.png" background-opacity="1">}}

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">¡Incluso hay más mapas fuera de https://openstreetmap.org !</a>

{{< /section >}} -->

---

{{< slide template="bg-dark" background-image="img/osm_maps_slow.gif" background-opacity="0.8">}}

## Son muchos mapas

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">¡Incluso hay más mapas fuera de https://openstreetmap.org !</a>

---

{{< section >}}

{{< slide template="bg-dark" background-image="img/osm-editor.png" background-opacity="0.8">}}

## Base de datos espacial colaborativa

---

## Estructura de datos

* **Componente espacial:** geometría. Hay 2 tipologías básicas
  - nodos / nodes
  - líneas / ways
* **Componente temático**: información asociada a la geometría
  - Par etiquetas y valores (key/value)
```
shop=bakery
name=Panadería Alonso
```

---

{{< slide template="bg-dark" background-image="img/osm-map-features.png" background-opacity="0.9" background-position="top">}}

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">Todas las claves se documentan en la wiki. Un buen punto de partida es https://wiki.openstreetmap.org/wiki/Map_Features</div>

---

{{< slide background-image="img/osm-wiki-keys.png" background-opacity="0.9" background-position="top" background-size="contain">}}

{{< /section >}}

---

{{< slide background-image="img/osm_data.png" background-opacity="0.3" >}}

## Comunidad mundial

* ~5.4 millones de usuarios registrados
  - (~ 100 editando diariamente en España)
* ~ 4.500 millones de nodos totales
  - (20.000 - 30.000 creados cada día en España)
* datos bajos licencia Open Database License (ODbL)

Fuente: [osmstats.neis-one.org](https://osmstats.neis-one.org/)


---

{{< section >}}

## Aplicaciones y servicios

---

{{< slide template="bg-dark" background-image="img/demof4map-donostia.png" background-opacity="0.9" background-position="top">}}

### F4 Maps

---

{{< slide template="bg-dark" background-image="img/ziclabilidad.png" background-opacity="0.6" background-position="top">}}

### uMap

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">Proyecto <a href="https://mapcolabora.org/project/ziclabilidad/">#Ziclabilidad</a> (Héctor Hochoa), usando <a href="http://umap.openstreetmap.fr/">uMap</a></div>


---

{{< slide background-image="img/overpass-turbo-accesibilidad.png" background-opacity="0.8" >}}

## Overpass

Permite hacer consultas a la base de datos de OSM.

<div class="bg-caption">Consulta en <a href="http://overpass-turbo.eu/">Overpass Turbo</a> sobre lugares accesibles en silla de ruedas en Donosti</div>

---

### Otros

* Editores (id, JOSM, Vespucci...)
* Geocoders (Nominatim, Geonames, Photon...)
* Estilos de Mapas personalizados (mapbox, mapzen...)
* Herramientas de QA (osmcha)
* Gamificación

{{< /section >}}
