+++
weight = 10
+++

{{< slide id="osm" template="bg-dark" background-image="/img/osm/osm-bcn-2019-10.png" background-position="top" background-opacity="0.6">}}

## OpenStreetMap

AKA "La wikipedia de los mapas"

* **Enfoque colaborativo** (toma + almacenamiento de datos)
* **Compartir datos** (legalmente + técnicamente): retorno social

**OSM es la mayor y más precisa base de datos espacial libre del mundo**

{{% note %}}
More specifically, this principle led us to use OSM.
{{% /note %}}

---

{{< slide template="bg-dark" background-image="/img/osm/osm-bcn-visible.png" background-position="top" background-opacity="0.8">}}

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">Esto es lo que se ve en https://openstreetmap.org</a>


---

{{< slide template="bg-dark" background-image="/img/osm/osm_maps_slow.gif" background-opacity="0.8">}}

Aunque en realidad...

## Son muchos mapas

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 10px 0">¡Incluso hay más mapas fuera de https://openstreetmap.org !</a>

---

{{% section %}}

{{< slide template="bg-dark" background-position="top" background-image="/img/osm/osm-editor.png" background-opacity="0.8">}}

## Base de datos espacial colaborativa

---

## Estructura de datos

* **Componente espacial:** geometría. Hay 2 tipologías básicas
  - nodos / nodes
  - líneas / ways
* **Componente temático**: información asociada a la geometría
  - Par etiquetas y valores (key/value)
```
amenity=community_centre
name=Centre Albareda
```

---

{{< slide template="bg-dark" background-image="/img/osm/osm-map-features.png" background-opacity="0.9" background-position="top">}}

<div style="position:fixed; bottom:0; background-color:rgba(0, 0, 0,.8); font-size:75%; padding:0 20px">Todas las claves se documentan en la wiki. Un buen punto de partida es https://wiki.openstreetmap.org/wiki/Map_Features</div>

---

{{< slide background-image="/img/osm/osm-wiki-keys.png" background-opacity="0.9" background-position="top" background-size="contain">}}

{{% /section %}}

---

{{< slide background-image="/img/osm/osm_data.png" background-opacity="0.3" >}}

## Comunidad mundial

* ~5.4 millones de usuarios registrados
  - (~ 100 editando diariamente en España)
* ~ 4.500 millones de nodos totales
  - (20.000 - 30.000 creados cada día en España)
* datos bajos licencia Open Database License (ODbL)

Fuente: [osmstats.neis-one.org](https://osmstats.neis-one.org/)


---

{{% section %}}

<!-- {{< slide background-image="img/josm.png" background-opacity="0.6" background-position="top">}} -->

## Aplicaciones y servicios

<ul class="gallery" data-iterations="0" data-interval="2.5" data-mode="full-screen">
  <li><img src="/img/osm/josm.png" alt="Editor avanzado JOSM" style="opacity:0.2;"></li>
  <li><img src="/img/osm/demof4map-bcn.png" alt="Edificios 3D con F4 Maps" style="opacity:0.2;"></li>
  <li><img src="/img/osm/overpass-turbo-accesibilidad.png" alt="Consultas a la BD a partir de la API overpass" style="opacity:0.2;"></li>
  <li><img src="/img/osm/streetcomplete-02.png" alt="Aplicaciones móviles (StreetComplete)" style="opacity:0.2;"></li>

</ul>
