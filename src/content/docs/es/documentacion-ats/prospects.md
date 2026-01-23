---
title: Prospects
description: Base de datos de talento potencial para búsquedas y análisis de mercado.
---

## Objetivo

Centralizar y organizar la base de datos del talento potencial que aún no ha sido contactado, permitiendo realizar búsquedas avanzadas, análisis de mercado y una transición ordenada hacia candidatos activos dentro del proceso de reclutamiento en el ATS.

## Funcionalidades clave

Este módulo permite:

- **Visualizar y gestionar** una base masiva de perfiles profesionales
- **Analizar la disponibilidad** de talento por skills, experiencia, manejo de idiomas y país
- **Identificar perfiles** con mayor compatibilidad con un job description mediante inteligencia artificial
- **Filtrar, clasificar y priorizar** prospectos antes de iniciar contacto
- **Convertir prospectos** en candidatos una vez se establece comunicación
- **Exportar información** para análisis externo o reportes

---

## Paso a paso

### 1. Acceso al módulo

En la parte superior de la interfaz del menú principal, luego de ingresar con las credenciales, seleccione la pestaña **Prospects**.

### 2. Exploración general

En la parte superior se muestra el **total de prospectos disponibles**.

Se visualizan gráficos con:

- **Top Skills** - Habilidades más comunes en la base de datos
- **Rangos de experiencia** (Junior, Semi, Senior, Senior+)
- **Países** con mayor concentración de talento

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/overview.png" alt="Vista general de prospects con gráficos" style="max-width: 100%; height: auto;" />
</div>

:::note
Estos datos se actualizan dinámicamente según los filtros aplicados.
:::

### 3. Uso de filtros

Desde el **panel izquierdo** es posible optimizar la búsqueda mediante los siguientes filtros:

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/filters-panel.png" alt="Panel de filtros limpio" style="max-width: 100%; height: auto;" />
</div>

#### Filtro por años de experiencia

Permite segmentar candidatos según su nivel de seniority (Junior, Semi-Senior, Senior, Senior+).

#### Filtro por nivel de inglés

En el filtro de **English Level** el botón desplegable presenta diferentes niveles por los cuales puede filtrar (Basic, Intermediate, Advanced, Native).

#### Filtro por habilidades

**Must-have Skills (Habilidades obligatorias):**

Habilidades técnicas o profesionales indispensables que debe tener el prospecto.

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/musthave-skills.png" alt="Filtro de Must-have Skills sin selección" style="max-width: 100%; height: auto;" />
</div>

**Should-have Skills (Habilidades deseables):**

Habilidades adicionales que mejoran el perfil pero no son excluyentes.

Ambos filtros cuentan con un botón **Add/Edit** que permite seleccionar estas habilidades desde un catálogo predefinido.

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/skills-selector.png" alt="Selector de habilidades con opciones" style="max-width: 100%; height: auto;" />
</div>

#### Filtro por país

El panel también incluye búsqueda por **Countries**.

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/countries-filter.png" alt="Botón de filtro por países" style="max-width: 100%; height: auto;" />
</div>

Al seleccionar esta opción, el botón despliega una lista con diferentes países disponibles.

<!-- ![Lista desplegable de países](~/assets/prospects/countries-list.png) -->

#### Búsqueda por palabras clave

En la parte superior de las gráficas se encuentra una **barra de búsqueda general** que facilita la búsqueda mediante palabras clave.

<!-- ![Barra de búsqueda general](~/assets/prospects/search-bar.png) -->

### 4. Revisión de prospectos

Cada **tarjeta de prospecto** muestra la siguiente información:

- Nombre del perfil
- País y zona horaria
- Porcentaje de match con el job description
- Botón **View Profile** - Ver perfil completo
- Botón **LinkedIn** - Acceso directo al perfil de LinkedIn
- Botón **Github** - Acceso directo al perfil de GitHub
- Sección **General Notes** para comentarios internos
- Descripción general de habilidades y experiencia

<div style="display: flex; justify-content: center; margin: 2rem 0;">
  <img src="/images/prospects/card-prospects.png" alt="Ejemplo de tarjeta de prospecto completa" style="max-width: 100%; height: auto;" />
</div>

---

## Tips operativos

- Utiliza primero los **gráficos** para entender el mercado antes de filtrar
- Define bien los **Must-have Skills** para evitar falsos positivos
- Revisa siempre el **porcentaje de match**, pero valida el perfil manualmente
- Usa las **notas** para dejar contexto antes de contactar al prospecto
- Exporta sólo cuando los filtros estén bien definidos para evitar ruido de datos
- Recuerda que los prospectos **no han sido contactados** aún

## Errores a evitar

- Contactar prospectos sin convertirlos correctamente en candidatos
- Usar filtros muy amplios que dificulten la toma de decisiones
- Confundir prospectos con candidatos activos
- No revisar el nivel de inglés antes de avanzar en el proceso
- Exportar grandes volúmenes sin un criterio claro
- No documentar interacciones o decisiones en las notas