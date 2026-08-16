# 📅 Ftracker - Calendario Familiar, Hábitos y Gastos 2026 - 2027

Aplicación web móvil-first con experiencia nativa tipo iOS para la gestión del calendario familiar, seguimiento de hábitos y control de gastos.

## 🚀 Características

- **📱 Navegación Nativa estilo iPhone (iOS Tab Bar)**:
  - Barra inferior con efecto *frosted glass* (blur) y soporte de área segura (`safe-area-inset-bottom`).
  - **3 Pestañas Principales**:
    1. **Calendario (Home)**: Vista mensual interactiva, detalle de actividades, retos del día y módulo de gastos.
    2. **Analítica**: Cuadro de mando integral con métricas KPI, balance de retos (éxito %, desglose dieta/ejercicio, niveles) y balance de gastos (total acumulado, promedio diario, desglose porcentual por categorías y top mayores gastos). Selector de periodo *Mes Actual* vs *Histórico*.
    3. **Config**: Panel de ajustes centralizado con exportación e importación de copias de seguridad JSON, contadores de datos almacenados y zona de reinicio.
- **👆 Gestos Táctiles (Swipe / Deslizamiento)**:
  - Transición fluida deslizando con el dedo (swipe horizontal de izquierda a derecha y viceversa) entre las 3 pestañas principales.
  - Swipe horizontal sobre el calendario para cambiar rápidamente entre meses.
- **🎯 Retos Diarios Gamificados**:
  - Dieta Cumplida y Ejercicio Realizado.
  - Métricas en tiempo real de éxitos vs. días transcurridos del mes.
  - Barras de progreso dinámicas e insignias por niveles (Leyenda, Pro, En Marcha).
- **💳 Módulo de Gastos**:
  - Categorías: Supermercado, Restaurante, Gasolina, Ropa, Regalos y Otro.
  - Detalle o concepto opcional e importe en Euros (€).
  - Gasto acumulado del mes y lista interactiva por día seleccionado con eliminación rápida.
- **🔔 Integración con Google Calendar**: Botón directo para crear recordatorios en Google Calendar.
- **💾 Copias de Seguridad (JSON)**: Exportación e importación completa de todas las actividades, retos y gastos con persistencia automática en `localStorage`.

