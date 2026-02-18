# 📊 Análisis de Desempeño de Tiendas -- Challenge Data Science LATAM

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el desempeño de cuatro
tiendas pertenecientes al Sr. Juan, utilizando técnicas de análisis de
datos para identificar cuál de ellas debería ser vendida
estratégicamente.

El análisis incluye métricas financieras, comerciales, de satisfacción
del cliente y distribución geográfica de ventas.

El proyecto fue desarrollado en Google Colab utilizando principalmente
Pandas para el procesamiento de datos y Matplotlib para la
visualización.

------------------------------------------------------------------------

# 🎯 Objetivo

Determinar, con base en evidencia cuantitativa y visualizaciones, cuál
tienda presenta el desempeño más bajo y debería ser vendida para
optimizar el portafolio del Sr. Juan.

------------------------------------------------------------------------

# 📂 Dataset

Se analizaron cuatro archivos CSV correspondientes a:

-   Tienda 1\
-   Tienda 2\
-   Tienda 3\
-   Tienda 4

Cada dataset incluye información sobre:

-   Producto
-   Categoría del producto
-   Precio
-   Calificación
-   Costo de envío
-   Latitud (lat)
-   Longitud (lon)

------------------------------------------------------------------------

# 📊 Análisis Realizados

## 1️⃣ Ingresos Totales por Tienda

  Tienda     Ingresos Totales
  ---------- ------------------
  Tienda 1   1,150,880,400
  Tienda 2   1,116,343,500
  Tienda 3   1,098,019,600
  Tienda 4   1,038,375,700

📌 **Tienda 4 presenta el menor nivel de facturación.**

------------------------------------------------------------------------

## 2️⃣ Ventas por Categoría

Las categorías con mayor generación de ingresos en todas las tiendas
fueron:

-   Electrónicos
-   Electrodomésticos
-   Muebles

Observaciones clave:

-   Tienda 1 lidera en Electrónicos y Electrodomésticos.
-   Tienda 4 presenta los valores más bajos en Electrodomésticos.
-   Ninguna categoría estratégica es liderada por Tienda 4.

------------------------------------------------------------------------

## 3️⃣ Calificación Promedio de Clientes

  Tienda     Calificación Promedio
  ---------- -----------------------
  Tienda 1   3.98
  Tienda 2   4.04
  Tienda 3   4.05
  Tienda 4   4.00

📌 Tienda 3 presenta la mayor satisfacción.\
📌 Tienda 4 no destaca en experiencia del cliente.

------------------------------------------------------------------------

## 4️⃣ Productos Más y Menos Vendidos

**Productos más vendidos:**

-   Tienda 1: Microondas\
-   Tienda 2: Iniciando en programación\
-   Tienda 3: Kit de bancas\
-   Tienda 4: Cama box

**Productos menos vendidos:**

-   Tienda 1: Auriculares con micrófono\
-   Tienda 2: Juego de mesa\
-   Tienda 3: Bloques de construcción\
-   Tienda 4: Guitarra eléctrica

------------------------------------------------------------------------

## 5️⃣ Costo de Envío Promedio

  Tienda     Costo Promedio
  ---------- ----------------
  Tienda 1   26,018.61
  Tienda 2   25,216.24
  Tienda 3   24,805.68
  Tienda 4   23,459.46

📌 Tienda 4 tiene el costo más bajo, pero esta ventaja no compensa su
menor nivel de ingresos.

------------------------------------------------------------------------

## 6️⃣ Análisis Geográfico (Extra Opcional)

Se utilizaron las coordenadas de latitud y longitud para:

-   Generar gráficos de dispersión.
-   Analizar concentración geográfica de ventas.
-   Identificar patrones regionales.

Hallazgos:

-   Las ventas se concentran en zonas urbanas.
-   No se identificó una ventaja geográfica significativa para Tienda 4.
-   El desempeño geográfico no compensa la diferencia en ingresos
    totales.

------------------------------------------------------------------------

# 🧠 Conclusión Final

Tras integrar todos los indicadores analizados:

📌 **Se recomienda vender la Tienda 4.**

### Justificación:

1.  Es la tienda con menor facturación.
2.  No lidera en categorías estratégicas de alto valor.
3.  No presenta la mayor satisfacción del cliente.
4.  Su ventaja en costo de envío no compensa la brecha financiera.

------------------------------------------------------------------------

# 🛠 Tecnologías Utilizadas

-   Python\
-   Pandas\
-   Matplotlib\
-   Google Colab

------------------------------------------------------------------------

# 🚀 Posibles Mejoras Futuras

-   Análisis de rentabilidad neta.
-   Modelos predictivos de ventas.
-   Segmentación geográfica avanzada.
-   Dashboard interactivo para visualización ejecutiva.
