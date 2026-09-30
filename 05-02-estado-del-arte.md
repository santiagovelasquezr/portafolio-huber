---
layout: default
title: Problema y estado del arte
parent: Proyecto Wearable
nav_order: 2
---

# Planteamiento del problema y estado del arte

Segunda entrega del proyecto.

[Descargar documento completo (PDF)](assets/docs/wearable/problema-estado-del-arte.pdf){: .btn .btn-purple }

---

## 1. Planteamiento del problema

**[D]** = dato verificable · **[I]** = interpretación del equipo

### ¿Qué ocurre?
Personas que pasan la jornada al aire libre respiran de forma continua aire contaminado sin percibir su nivel real de exposición. **[D]** La exposición personal a PM2.5 en una misma vía de la CDMX varió de 16.5 µg/m³ (caminando) a 81.7 µg/m³ (en bicicleta), con picos de 110.9 µg/m³ ligados al tráfico. **[I]** El dato de la estación fija no representa lo que respira cada persona.

### ¿A quién afecta?
- **Usuario primario:** trabajadores de jornada prolongada en exterior (construcción, mantenimiento industrial, vía pública).
- **Usuario secundario:** personas con condiciones respiratorias.

### ¿Qué magnitud tiene?
- **[D]** La OMS atribuye 4.2 millones de muertes prematuras en 2019 a la contaminación exterior.
- **[D]** En México se registraron más de 48 mil muertes prematuras atribuibles en 2019.
- **[D]** Cumplir la guía OMS de PM2.5 en las zonas metropolitanas del Valle de México, Guadalajara y Monterrey evitaría 2,170 muertes y pérdidas por 45 mil millones de pesos.
- **[D]** De enero a agosto de 2023, la CDMX solo tuvo 55 días (≈23 %) con buena calidad del aire.

### ¿Por qué merece atención?
**[I]** El daño es acumulativo e invisible: con la costumbre el cuerpo deja de alertar y el riesgo se normaliza, mientras las recomendaciones oficiales (evitar actividades al aire libre) son inviables para quien trabaja en la calle.

---

## 2. Estado del arte

| Solución | Qué resuelve | Limitaciones |
|---|---|---|
| App AIRE / Índice AIRE Y SALUD (SEDEMA) | Informar el nivel de contaminación y su riesgo | Mide por estación, no por persona; requiere consultar el celular |
| Atmotube PRO 2 | Medir la exposición personal en tiempo real | La información vive en el teléfono; no está pensado para trabajo pesado |
| Flow 2 (Plume Labs) | Conocer la exposición y rutas más limpias | Descontinuado en 2023 |
| Dräger Pac 8000 | Evitar exposiciones agudas a un gas peligroso | Un solo gas; no capta partículas ni exposición crónica |
| LG PuriCare | Filtrar el aire que se respira | Batería de 4–8 h, menor que un turno |
| Cubrebocas N95 / EPP | Reducir la inhalación de partículas | No indica cuándo usarlo; se abandona por calor |

---

## 3. Análisis crítico

- **Medir no es avisar:** las apps y wearables generan datos, pero dependen de que el usuario consulte el celular. Un trabajador con las manos ocupadas y ruido alrededor no lo hace.
- **Agudo vs. crónico:** los detectores industriales alertan bien, pero protegen contra picos de un gas. Los wearables de consumo miden lo crónico, pero con lógica de consumo. Ninguno cubre ambas cosas.
- **Proteger agrega carga:** los purificadores y el EPP suman calor, peso o dependencia de batería.
- **Contradicción:** las fuentes oficiales recomiendan evitar el exterior en días malos, mientras el usuario primario no tiene esa opción.

---

## 4. Necesidades no resueltas

| Necesidad | Oportunidad |
|---|---|
| La exposición acumulada es imperceptible una vez que el cuerpo se acostumbra | ¿Cómo podríamos hacer perceptible la dosis acumulada? |
| La información no llega en el momento ni el formato útil para el trabajo | ¿Cómo podríamos entregarla a quien no puede consultar un teléfono? |
| Las recomendaciones oficiales no son viables para el trabajador en exterior | ¿Cómo podríamos traducir el riesgo en acciones posibles en la jornada? |
| La protección se abandona porque agrega incomodidad | ¿Cómo podríamos lograr que se use solo cuando se necesita? |
| Actuar ante el riesgo depende del respaldo del empleador | ¿Cómo podríamos involucrar a las empresas? |

**Replanteamiento:** el problema se desplaza de la "falta de información" a la **normalización del riesgo y la imposibilidad de actuar** en el contexto laboral.

---

## Referencias

1. OMS (2024). *Ambient (outdoor) air pollution — Fact sheet*. [who.int](https://www.who.int/news-room/fact-sheets/detail/ambient-(outdoor)-air-quality-and-health)
2. WRI México (2023). *Ahogan contaminantes 7 de cada 10 días del año a la CDMX*. [es.wri.org](https://es.wri.org/noticias/ahogan-contaminantes-7-de-cada-10-dias-del-ano-la-cdmx)
3. SEMARNAT. *Informe del Medio Ambiente*, cap. 5 (cita INECC, 2014).
4. Hernández-Paniagua et al. (2018). *Personal Exposure to PM2.5 in the Megacity of Mexico*. Atmosphere, 9(2), 57. [doi.org/10.3390/atmos9020057](https://doi.org/10.3390/atmos9020057)
5. Entrevistas del equipo (2026).
6. SEDEMA. *App Aire_CDMX*.
7. Atmotube. *Atmotube PRO 2*. [atmotube.com](https://atmotube.com/atmotube-pro)
8. Plume Labs. Sitio oficial. [plumelabs.com](https://plumelabs.com/en/)
9. Dräger. *Dräger Pac 8000*. [draeger.com](https://www.draeger.com/en-us_us/Products/Pac-8000)

---

## Siguiente sección
[Cronograma y rol de participación](05-03-cronograma.md)
