---
layout: page
title: Proyecto Escuelas OSM
subtitle: Mapear los establecimientos educativos de Argentina en OpenStreetMap
include_map: false
---

## 🏫 Proyecto Escuelas OSM Argentina

**Actividad principal del mapatón:** Mapear escuelas usando datos oficiales del Ministerio de Educación con verificación automática de duplicados.

---

## 📊 En Números

<div class="estadisticas-proyecto">
  <div class="stat-box">
    <div class="stat-number">64,639</div>
    <div class="stat-label">Escuelas oficiales<br>en Argentina</div>
  </div>

  <div class="stat-box">
    <div class="stat-number">78.8%</div>
    <div class="stat-label">Cobertura actual<br>en OpenStreetMap</div>
  </div>

  <div class="stat-box">
    <div class="stat-number">13,758</div>
    <div class="stat-label">Escuelas faltantes<br>por mapear</div>
  </div>

  <div class="stat-box destacado">
    <div class="stat-number">138</div>
    <div class="stat-label">Tareas preparadas<br>para el encuentro</div>
  </div>
</div>

---

## 🎯 Challenges para el Encuentro

### **Challenge Principal: Escuelas Pergamino**
- **138 tareas** de escuelas en la zona de Pergamino
- **Verificación automática** con enlaces Overpass
- **Enlaces directos** a legajos oficiales del Ministerio
- **Tags específicos:** `sotm_pergamino2026=yes` + `proyecto_escuelas_argentina=yes`

[🗺️ Participar en Challenge Pergamino]({{ site.links.maproulette_pergamino }}){:.btn .btn-success .btn-large}

[📋 Ver Proyecto Completo]({{ site.links.maproulette_project }}){:.btn .btn-outline}

---

## 🛠️ Metodología y Herramientas

### **Workflow para Mappers**

#### 1. Acceder a la Tarea
- Ir al [Challenge Pergamino]({{ site.links.maproulette_pergamino }})
- Seleccionar una tarea disponible
- Leer las instrucciones específicas

#### 2. Verificar Duplicados (OBLIGATORIO)
- **Clic en enlace Overpass** incluido en cada tarea
- Verificación automática en radio de 5km
- Búsqueda por CUE exacto y nombres similares
- Confirmar que NO existe la escuela en OSM

#### 3. Consultar Fuente Oficial
- **Enlace directo** al legajo del Ministerio de Educación
- Verificar nombre oficial, dirección y detalles
- Confirmar coordenadas y ubicación exacta

#### 4. Mapear la Escuela
- Usar editor **JOSM** o **iD** según preferencia
- **Copiar tags** del bloque "COPIAR TAGS" de la tarea
- Posicionar correctamente según fuentes oficiales
- Agregar tags de seguimiento del encuentro

#### 5. Completar la Tarea
- Marcar tarea como completada en MapRoulette
- Comentarios opcionales sobre dificultades encontradas
- Continuar con siguiente tarea

---

## 🏷️ Sistema de Tags

### **Tags Oficiales Incluidos**
```
amenity=school
name=Nombre Oficial de la Escuela
ref:cue=060118000
ref:arg:cue=060118000
official:legajo=https://mapa.educacion.gob.ar/legajo/060118000
overpass:search=https://overpass-turbo.eu/...
source=Ministerio de Educación Argentina
```

### **Tags de Seguimiento del Encuentro**
```
sotm_pergamino2026=yes
proyecto_escuelas_argentina=yes
```

### **Tags Opcionales**
- `education:AR=*` - Nivel educativo específico
- `operator=*` - Sector (público/privado)
- `address:*` - Dirección completa si disponible

---

## 🔍 Verificación Automática

### **Sistema Overpass Integrado**
- **21,026 consultas** preconfiguradas
- **Búsqueda inteligente** por CUE y nombre
- **Detección automática** de establecimientos cercanos
- **Enlaces directos** - Un clic para verificar

### **Criterios de Búsqueda**
- **CUE exacto** en radio de 5km (identificador único)
- **Nombres similares** en radio de 500m
- **Elementos cercanos** con `amenity=school`
- **Variaciones** de nombre y abreviaciones

---

## 🌟 Características Únicas del Proyecto

### **Referencias Oficiales Completas**
- **Legajos ministeriales** - Enlaces directos verificables
- **CUE específico Argentina** - Identificador único nacional
- **Fuente oficial** documentada en cada elemento
- **Trazabilidad completa** desde gobierno a OSM

### **Calidad de Datos Garantizada**
- **Setup completado** - 138 tareas verificadas y listas
- **Duplicados investigados** - Casos críticos pre-resueltos
- **Referencias no contaminantes** - Sin afectar campo website
- **Workflow probado** - Metodología testeada y funcionando

---

## 📈 Impacto Esperado

### **Durante el Encuentro**
- **Participantes del encuentro** × **1.5 horas** de mapatón intensivo
- **Estimación conservadora:** 40-50 escuelas mapeadas
- **Zona Pergamino:** Cobertura educativa significativamente mejorada
- **Experiencia práctica** con datos gubernamentales oficiales

### **Post Encuentro**
- **Metodología consolidada** para futuras provincias
- **Modelo replicable** para otros encuentros regionales
- **Base técnica sólida** para State of the Map Argentina 2027
- **Precedente exitoso** de colaboración comunidad-estado

---

## 💡 Valor Temático: "Comunidad y Estado"

### **Ejemplo Concreto de Colaboración**
- **Datos oficiales:** Ministerio de Educación Nacional
- **Plataforma comunitaria:** OpenStreetMap
- **Metodología híbrida:** Verificación oficial + validación comunitaria
- **Herramientas ciudadanas:** Verificación transparente de datos públicos

### **Impacto Social Directo**
- **Educación accesible:** Escuelas visibles en mapas libres
- **Transparencia gubernamental:** Datos públicos verificables
- **Herramientas ciudadanas:** OSM como infraestructura cívica
- **Capacidades locales:** Comunidad técnica fortalecida

---

## 🚀 Para Participantes del Encuentro

### **Preparación Recomendada**
- **Cuenta OSM** activa y funcional
- **Editor preferido** configurado (JOSM o iD)
- **Experiencia básica** con mapeo de POIs
- **Ganas de aprender** metodologías de verificación oficial

### **Durante el Mapatón**
- **Soporte técnico** disponible (Manuel Retamozo + team)
- **Resolución de dudas** en tiempo real
- **Trabajo colaborativo** presencial/virtual
- **osmlanduseR** para análisis post-mapeo

### **Seguimiento Post-Encuentro**
- **Dashboard** de progreso en wiki OSM
- **Tags de seguimiento** para medir impacto
- **Documentación** de lessons learned
- **Base** para próximos proyectos similares

---

## 🔗 Enlaces y Recursos

<div class="recursos-proyecto">
  <a href="{{ site.links.maproulette_pergamino }}" class="recurso-principal">
    🗺️ Challenge Pergamino (138 tareas)
  </a>

  <a href="{{ site.links.maproulette_project }}" class="recurso-secundario">
    📋 Proyecto Completo MapRoulette
  </a>

  <a href="https://mapa.educacion.gob.ar/" target="_blank" class="recurso-secundario">
    🏛️ Mapa Educativo Oficial
  </a>

  <a href="https://overpass-turbo.eu/" target="_blank" class="recurso-secundario">
    🔍 Overpass Turbo
  </a>
</div>

---

<div class="proyecto-footer">
  <h3>🎖️ Proyecto Listo para SOTM 2026</h3>
  <p>Setup completado, herramientas probadas, metodología consolidada.<br>
  <strong>¡Todo preparado para mapear colaborativamente las 138 escuelas durante el encuentro!</strong></p>
</div>

<style>
.estadisticas-proyecto {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin: 2rem 0;
}

.stat-box {
  background: white;
  padding: 2rem 1rem;
  border-radius: 8px;
  text-align: center;
  border: 2px solid #e9ecef;
  transition: transform 0.3s ease;
}

.stat-box:hover {
  transform: translateY(-4px);
}

.stat-box.destacado {
  border-color: #F4C430;
  background: linear-gradient(135deg, #F4C430, #FFD700);
  color: #2E5C8A;
}

.stat-number {
  font-size: 2.5rem;
  font-weight: 700;
  color: #2E5C8A;
  margin-bottom: 0.5rem;
}

.stat-box.destacado .stat-number {
  color: white;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
}

.stat-label {
  font-size: 0.9rem;
  font-weight: 600;
  line-height: 1.3;
}

.recursos-proyecto {
  display: grid;
  gap: 1rem;
  margin: 2rem 0;
}

.recurso-principal {
  display: block;
  padding: 2rem;
  background: linear-gradient(135deg, #28a745, #20c997);
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-size: 1.2rem;
  font-weight: 700;
  text-align: center;
  transition: transform 0.3s ease;
}

.recurso-principal:hover {
  transform: translateY(-4px);
  color: white;
}

.recurso-secundario {
  display: block;
  padding: 1rem;
  background: white;
  border: 2px solid #2E5C8A;
  color: #2E5C8A;
  text-decoration: none;
  border-radius: 4px;
  font-weight: 600;
  text-align: center;
  transition: all 0.3s ease;
}

.recurso-secundario:hover {
  background: #2E5C8A;
  color: white;
}

.proyecto-footer {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  text-align: center;
  border-left: 4px solid #F4C430;
  margin: 3rem 0;
}

.proyecto-footer h3 {
  color: #2E5C8A;
  margin-bottom: 1rem;
}
</style>
