# Proyecto Retail - Análisis RFM en Shopify

**Integrantes del Grupo 1 - Retail**  
- Michael Phillips  
- Mauricio García  
- Cristina Prieto  
- Julissa Huebla  

---

## Descripción del Proyecto

Este proyecto tiene como objetivo realizar un análisis de clientes de la plataforma **Shopify** utilizando la metodología **RFM (Recency, Frequency, Monetary)** para segmentar y clasificar clientes, permitiendo identificar perfiles clave para estrategias de marketing y retención.

Se trabajó con diversos datasets de Shopify (clientes, pedidos, productos, vendedores, pagos, geolocalización, etc.) para obtener información valiosa que apoye la toma de decisiones en un negocio de e-commerce.

---

## Tecnologías y Herramientas Utilizadas

- **Entorno de trabajo:** Google Colab  
- **Lenguaje de programación:** Python 3  
- **Librerías principales:**
  | Librería | Uso principal |
  |----------|--------------|
  | `pandas` | Manipulación y análisis de datos |
  | `numpy` | Operaciones numéricas |
  | `matplotlib` | Visualización de datos |
  | `seaborn` | Visualización estadística |


---

## Fuentes de Datos Utilizadas

- **shopify_customers_dataset.csv** – Información de clientes  
- **shopify_orders_dataset.csv** – Información de pedidos  
- **shopify_products_dataset.csv** – Detalles de productos  
- **shopify_sellers_dataset.csv** – Información de vendedores  
- **shopify_order_payments_dataset.csv** – Información de pagos  
- **shopify_category_name_translation.csv** – Traducción de categorías  
- **shopify_geolocation_dataset.csv** – Datos de ubicación de clientes y vendedores  
- **shopify_order_items_dataset.csv** – Detalles de los productos en cada orden  

---

## Metodología Aplicada

1. **Carga y limpieza de datos**  
   - Eliminación de registros con órdenes no entregadas o canceladas.  
   - Conversión de fechas a formato datetime.  
   - Unión de datasets relevantes para un análisis integral.

2. **Cálculo de métricas RFM**  
   - **Recency (R):** Días desde la última compra.  
   - **Frequency (F):** Número de órdenes únicas por cliente.  
   - **Monetary (M):** Monto total gastado por cliente.  

3. **Segmentación de clientes**  
   - Clasificación mediante etiquetas R, F y M usando cuartiles y reglas de negocio.  
   - Creación de segmentos como:  
     - Clientes Potenciales  
     - Clientes Recientes  
     - Clientes Monto Alto  
     - Clientes Alta Frecuencia  
     - Clientes Perdidos  

4. **Exportación de resultados**  
   - Archivo final con clasificación de clientes exportado en formato `.xlsx`.

---

## Estructura de Clasificación RFM

| Segmento | Descripción |
|----------|-------------|
| Clientes TOP | Alto gasto, alta frecuencia y muy recientes |
| Clientes Potenciales | Buen gasto y frecuencia, con posibilidad de mayor conversión |
| Clientes Recientes | Compradores nuevos o de última fecha |
| Clientes Monto Alto | Clientes que gastan mucho pero con baja frecuencia |
| Clientes Alta Frecuencia | Compran seguido pero con gasto moderado |
| Clientes Perdidos | Clientes inactivos por mucho tiempo |

---

## Objetivo General

Realizar un análisis exploratorio y de segmentación para identificar perfiles de clientes y establecer estrategias de retención y reactivación, optimizando así la relación con el cliente en un entorno de **e-commerce**.

---

## Contacto del equipo
Si desea más información sobre el proyecto, puedes contactar a cualquiera de los integrantes del grupo :)

