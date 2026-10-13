---
layout: default
title: Encuentro OSM Argentina 2026
include_map: true
---

<div class="hero-section">
  {% include hero-flyer-elements.html %}
  <div class="event-badge">
    <h1>Encuentro OSM Argentina 2026</h1>
    <h2>{{ site.event.date_short }}</h2>
    <p>{{ site.event.location }}</p>
    <p class="hero-subtitle">Datos abiertos, territorio y comunidad</p>
    <div class="hero-actions">
      <a href="{{ '/flyer' | relative_url }}" style="color: rgba(255,255,255,0.7); text-decoration: none; font-size: 0.9rem;">Ver flyer completo</a>
    </div>
  </div>
</div>

## 🎯 Sobre el Encuentro

Un **espacio de intercambio entre pares** generado desde y para la comunidad de OpenStreetMap Argentina. Este encuentro busca compartir experiencias, proyectos, herramientas y metodologías vinculadas con la cartografía libre, los datos geográficos abiertos y el uso de información colaborativa para comprender y gestionar el territorio.

### 📍 Información del Evento

- **📅 Fecha:** {{ site.event.date_formatted }}
- **📍 Sede:** [{{ site.event.location }}]({{ '/venue' | relative_url }})
- **👥 Modalidad:** Híbrida (presencial + virtual)
- **🕘 Horario:** {{ site.event.time }}

<div class="countdown-container">
  <div class="countdown-title">⏰ Faltan para el encuentro</div>
  <div id="countdown-timer" class="countdown-timer">
    <div class="countdown-unit">
      <span class="countdown-number" id="days">--</span>
      <span class="countdown-label">Días</span>
    </div>
    <div class="countdown-unit">
      <span class="countdown-number" id="hours">--</span>
      <span class="countdown-label">Horas</span>
    </div>
    <div class="countdown-unit">
      <span class="countdown-number" id="minutes">--</span>
      <span class="countdown-label">Min</span>
    </div>
    <div class="countdown-unit">
      <span class="countdown-number" id="seconds">--</span>
      <span class="countdown-label">Seg</span>
    </div>
  </div>
</div>

### 👨‍💼 Coordinador: {{ site.chairman.name }}

**{{ site.chairman.experience }}** especializado en {{ site.chairman.specialty }}. [Ver perfil OSM]({{ site.chairman.osm_profile }})

---

## 🗓️ Programa del Encuentro

La jornada combina **charlas** sobre experiencias de uso de OpenStreetMap, **talleres** prácticos (desde los primeros pasos en OSM hasta el uso de datos en QGIS) y un **mapatón** de escuelas de Pergamino.

[Ver programa completo]({{ '/programa' | relative_url }}){:.btn .btn-outline}

---

## 🌎 OpenStreetMap y Pergamino

Pergamino cuenta con una experiencia de trabajo sostenida en materia de **información geográfica abierta y colaborativa**.

Desde la Municipalidad de Pergamino, y particularmente desde la Infraestructura de Datos Espaciales (IDE Pergamino), se viene desarrollando una política de producción, actualización y contribución de información geográfica en OpenStreetMap.

Esta experiencia permite fortalecer el vínculo entre los datos abiertos y la gestión territorial, al mismo tiempo que contribuye a que la información geográfica producida y mejorada quede disponible para ciudadanos, organizaciones, instituciones y empresas.

El encuentro será una oportunidad para compartir esta experiencia, conocer otros proyectos desarrollados por la comunidad y explorar nuevas formas de colaboración entre **OpenStreetMap, las instituciones públicas y la sociedad**.

---

## 💡 ¿Qué vamos a compartir?

Durante la jornada se abordarán experiencias y proyectos relacionados con:

- 🗺️ **OpenStreetMap y cartografía colaborativa**
- 📊 **Datos geográficos abiertos**
- 🏛️ **Información geográfica para la gestión pública**
- 🌎 **Experiencias de colaboración entre comunidad y Estado**
- 🛠️ **Herramientas y metodologías de mapeo**
- 📍 **Análisis y conocimiento del territorio**
- 🤝 **Nuevas iniciativas de participación y colaboración**

---

## 🔗 Enlaces y Comunidad

<div class="enlaces-oficiales">
  {% if site.links.osm_calendar %}
  <a href="{{ site.links.osm_calendar }}" class="enlace-oficial">
    📅 OSM Calendar
  </a>
  {% endif %}

  {% if site.links.wiki %}
  <a href="{{ site.links.wiki }}" class="enlace-oficial">
    📚 Wiki OSM
  </a>
  {% endif %}
</div>

### 💬 Únete a la comunidad

- **[Telegram @osm_ar]({{ site.social.telegram }})** - Canal principal de OSM Argentina
- **[Instagram @OpenStreetMapAR]({{ site.social.instagram }})** - Fotos y actualizaciones
- **[Web oficial]({{ site.social.website }})** - openstreetmap.org.ar

---

## 📍 Ubicación

<div id="mapa-encuentro" style="height: 400px; margin: 2rem 0;"></div>

**{{ site.event.location }}** - {{ site.event.address }}

[Ver información completa de la sede]({{ '/venue' | relative_url }}){:.btn .btn-outline}

---

## 🎯 Participar

### Para Participantes Presenciales

1. **Confirmar asistencia** mediante el formulario de inscripción.
2. **Preparar herramientas:** JOSM o iD editor, si vas a participar de actividades de mapeo.
3. **Cuenta OSM:** Se recomienda contar con un usuario activo de OpenStreetMap.

### Para Participantes Virtuales

1. **Conexión híbrida** disponible durante la jornada.
2. **Participación online** en las actividades que se habiliten.
3. **Chat comunitario** para coordinación e intercambio durante el evento.

<div class="cta-buttons">
  {% if site.links.inscripcion_oficial %}
  <a href="{{ site.links.inscripcion_oficial }}" target="_blank" class="btn btn-success btn-large">Inscribirse Ahora</a>
  {% endif %}

  {% if site.links.osm_calendar %}
  <a href="{{ site.links.osm_calendar }}" target="_blank" class="btn btn-outline btn-large">OSM Calendar</a>
  {% endif %}
</div>

---

<div class="footer-evento">
  <p><strong>Organizan:</strong> Dirección de Sistemas de Información Geográfica (DSIG) e IDE Pergamino · Municipalidad de Pergamino</p>
  <p><strong>Coordinador:</strong> {{ site.chairman.name }}</p>
  <p><strong>Anfitriona:</strong> Hub de Innovación · Municipalidad de Pergamino</p>
</div>
