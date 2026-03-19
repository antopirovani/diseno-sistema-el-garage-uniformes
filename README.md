# Diseño e Integración del Sistema de Información
### El Garage Uniformes

> Trabajo Práctico Integrador · Materia: Diseño de Sistemas  
> Universidad Gastón Dachary · 2025  
> Grupo N°1 — Los Diseñadores del Tablón · 8 integrantes  

---

## Descripción

Este trabajo consistió en el diseño completo del sistema de información para
El Garage Uniformes, una empresa dedicada a la fabricación y venta de uniformes
escolares. El punto de partida fue el relevamiento y las necesidades definidas
en el TPI de Análisis de Sistemas del mismo año (realizado por otro grupo),
y el trabajo avanzó a través de todas las etapas del diseño: selección de
solución, diseño general y diseño detallado.

---

## Fases del proyecto

**Fase de selección**  
Se especificaron y evaluaron 5 soluciones alternativas:

| Alt. | Descripción |
|------|-------------|
| A1 | Sistema cliente-servidor web local con API y base de datos on-premise |
| A2 | Sistema web y móvil en la nube con arquitectura serverless |
| A3 ✅ | Implementación de ERP (Odoo) en modalidad PaaS — Odoo.sh |
| A4 | Aplicación mobile nativa Android con API en la nube |
| A5 | Aplicación de escritorio instalada en puestos locales |

Cada alternativa fue evaluada mediante análisis cualitativo (viabilidad operativa,
técnica, temporal y económica) y análisis cuantitativo con estimación de costos
de desarrollo, hardware, software, capacitación e instalación.
La solución seleccionada por el usuario fue la Alternativa 3: Odoo en Odoo.sh.

**Fase de diseño general**  
- Correspondencia entre las entidades del análisis previo y el modelo de datos
  de Odoo, verificada atributo por atributo usando PgAdmin y el repositorio
  oficial de Odoo en GitHub.
- Construcción del DER y el DFD de la solución a especificar.
- Distribución en Unidades de Diseño (manual e informatizada) y asignación
  de tecnologías.
- Modelo de procesadores y modelo de tareas.

**Fase de diseño detallado**  
- Diseño físico de la base de datos en PostgreSQL 18.1: tablas, atributos,
  claves e integridad referencial.
- Diagramas de estructura mejorados con ELPs y diccionarios de datos.
- Diseño de interfaces: árbol de navegabilidad, entradas y salidas.

---

## Tecnologías/herramientas planteadas para el diseño

- ERP: Odoo 18 (módulos de Ventas, Inventario y Manufactura)
- Plataforma: Odoo.sh (PaaS)
- Base de datos: PostgreSQL 18.1
- Herramientas: PgAdmin, repositorio de Odoo en GitHub
- Artefactos: DER, DFD, Diagramas de Estructura, ELPs, Diccionarios de Datos

## Link al trabajo completo
- https://drive.google.com/file/d/1A8v1EeloBkUTVL0ITxJgNc0-AFfq9NP-/view?usp=sharing
  
---

> *Proyecto académico — Universidad Gastón Dachary, Posadas, Misiones, 2025.*
