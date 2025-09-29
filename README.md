# Proyecto-EDA-Python

# 📊 Exploración de Datos de Campañas de Marketing Bancarias

## 📖 Descripción

Este proyecto realiza un análisis exploratorio de datos (EDA) a partir de dos datasets relacionads con campañas de maketing de un banco portugues.\
El objetivo es identificar patrones y factores asociados al éxito de la suscripción de depósitos a plazo, así como explorar características demográficas adicionales de los clientes.

El análisis se divide en tres fases:
  1. **EDA de bank-additional**\
  2. **EDA de customers-details**\
  3. **EDA combinado (merge de ambos datasets)**

------------------------------------------------------------------------

## 🗂 Estructura del Proyecto

    ├── data/                # Datos crudos y procesados
    │   ├── bank-additional.csv
    │   ├── customer-details.xlsx
    ├── notebooks/           # Notebooks con el análisis
    │   └── Proyecto_EDA_Python.ipynb
    ├── README.md            # Informe y conclusiones del proyecto

------------------------------------------------------------------------

## 🛠 Instalación y Requisitos

Este proyecto utiliza **Python 3.8+** y requiere las siguientes librerías:\
  - pandas\
  - numpy\
  - matplotlib\
  - seaborn

Para instalar dependencias:
``` bash
pip install -r requirements.txt
```
------------------------------------------------------------------------

## 📊 Resultados y Conclusiones

- El dataset 'bank-additional' mostró que las variables más relacionadas con el éxito ('y') son la **duración de la llamada** y los **resultados de campañas anteriores**.\
- El dataset 'customers' no presenta por sí solo relaciones fuertes con 'y', pero aporta contexto demográfico y de comportamiento.\
- La unión de ambos datasets permitió enriquecer el análisis, aunque las variables adicionales (ingresos, hijos, visitas web) no resultaron determinantes.\
- En general, **el éxito de las campañas está más influido por factores de interacción (llamadas, historial previo) que por características demográficas**.

------------------------------------------------------------------------

## 🔄 Próximos Pasos

- Profundizar en técnicas de modelado predictivo (ej. regresión logística, árboles de decisión) para estimar la probabilidad de éxito de una campaña.\
- Explorar técnicas de segmentación de clientes para diseñar estratégias de marketing más efectivas.

------------------------------------------------------------------------

## ✒ Autores

- CELIA PALACIOS POVEA





