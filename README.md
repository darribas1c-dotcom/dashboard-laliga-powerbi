# ⚽ Dashboard de Análisis de Rendimiento — LaLiga | Power BI

Análisis del rendimiento individual de jugadores de **LaLiga** con filtrado dinámico por equipo y posición, desarrollado con Power BI como parte del Máster en Ciencia de Datos e Inteligencia Artificial (Universidad Nebrija).

---

## 🗂️ Contenido del dashboard

Panel único con análisis completo de métricas ofensivas y de rendimiento por jugador:

### KPIs y visualizaciones principales

- **Tiros a puerta vs. Goles** — gráfico de barras doble horizontal comparando eficacia de cada jugador (shots total vs. shots on target)
- **Tiempo de juego por jugador** — gráfico de área con minutos acumulados en toda la temporada
- **Goles totales por jugador** — ranking visual de goleadores
- **Scatter plot: Goles vs. Tiros totales** — relación entre volumen de disparo y efectividad real
- **Scatter plot: Goles en 90 min vs. Tiros a puerta** — métrica normalizada por tiempo jugado, más representativa para comparar jugadores con distinta participación
- **Tabla de estadísticas detalladas** — goals, shots total, key passes y duels won por jugador

### Filtros interactivos
- **Por equipo**: Alavés, Athletic Club, Atlético de Madrid, Barcelona, Celta de Vigo, Getafe, Real Madrid
- **Por posición**: BR, CAM, CB, CDM, CF, CM, GK, LB, LM, LW, RB...

---

## 🛠️ Herramientas y técnicas aplicadas

- **Power BI Desktop** — modelado de datos y visualizaciones interactivas
- **DAX** — medidas calculadas para métricas normalizadas (goles/90 min)
- **Segmentadores** — filtrado cruzado por equipo y posición
- Gráficos de dispersión (scatter), barras horizontales, área y tablas dinámicas

---

## 💡 Insights destacados

- **Karim Benzema** lidera en tiros totales (107) y goles, con alta eficiencia en conversión
- **Iago Aspas** destaca en goles (14) y duelos ganados (176), combinando rendimiento ofensivo y físico
- Los scatter plots revelan jugadores con alta tasa de conversión relativa, más allá del volumen bruto de disparos
- **Antoine Griezmann** sobresale en key passes (29) y duelos ganados (103), reflejando un perfil más creativo que goleador puro

---

## 📁 Archivos

| Archivo | Descripción |
|---|---|
| `prueba.pbix` | Archivo Power BI con el dashboard completo |
| `captura_dashboard.png` | Vista general del panel |

---

*Proyecto académico desarrollado durante el Máster Universitario en Ciencia de Datos e IA — Universidad Nebrija (2025-2026)*
