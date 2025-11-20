# Dashboard Power BI – Análisis de Ventas Internacionales
## Este repositorio contiene un dashboard desarrollado en Power BI Desktop para el análisis de ventas de una empresa con operaciones multinacionales y un portafolio amplio de productos. El proyecto integra modelado de datos, transformación mediante Power Query y medidas DAX optimizadas para visualizar indicadores clave de rendimiento (KPIs) y segmentaciones comerciales.
## Arquitectura del Proyecto

### 1. Origen y Transformación de Datos
- Procesamiento de datos mediante **Power Query Editor**.
- Limpieza, normalización y tipificación de columnas.
- Creación de tablas de dimensiones y hechos bajo un enfoque **Star Schema**.

### 2. Modelado de Datos
- Implementación de relaciones 1:* entre tablas de hechos y dimensiones.
- Optimización del modelo para favorecer el rendimiento y la compresión.
- Uso de columnas calculadas para clasificación de productos y métricas temporales.

---

## Funcionalidades del Dashboard
- **KPIs globales**: ventas totales, conteo de clientes y países.
- **Top 7 productos por ingresos**, con ordenamiento dinámico.
- **Tendencia anual de ventas** mediante line chart con análisis comparativo.
- **Mapa geográfico** para distribución de ventas por país (Bing Maps).
- **Segmentación por método de entrega (online/local)** mediante barras apiladas.
- **Filtros de usuario**:
  - Dimensión País
  - Categoría de Producto

---

## Herramientas
- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX (Data Analysis Expressions)**
- **Modelado Tabular**
- **Bing Maps Integration**
- Opcional: Excel/CSV como fuente de datos
