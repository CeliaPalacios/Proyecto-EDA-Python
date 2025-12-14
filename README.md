# Proyecto-EDA-Python

# 📊 Exploración de Datos de Campañas de Marketing Bancarias

## 📖 Descripción

Este proyecto realiza un análisis exploratorio de datos (EDA) a partir de dos datasets relacionads con campañas de maketing de un banco portugues.\
El objetivo es identificar patrones y factores asociados al éxito de la suscripción de depósitos a plazo, así como explorar características demográficas adicionales de los clientes.

El análisis se divide en tres fases:
  1. **EDA de bank-additional**
  2. **EDA de customers-details**
  3. **EDA combinado (merge de ambos datasets)**

------------------------------------------------------------------------

## 🗂 Estructura del Proyecto

/
├─ data/
│  ├─ raw/
│  │  ├─ bank-additional.csv
│  │  └─ customer-details.xlsx
│  └─ processed/
│     ├─ bank_clean.csv
│     ├─ bank_additional_eda.csv        # (si quieres conservarlo)
│     └─ merged_eda.csv                 # (o renómbralo a bank_customers_final.csv)
├─ notebooks/
│  ├─ 01_proyecto_EDA.ipynb             # (tu Proyecto_EDA_Python renombrado)
│  └─ 02_preparacion_data_merge.ipynb
├─ requirements.txt
└─ README.md


------------------------------------------------------------------------

## Diagrama de flujo

data/raw
   ├─ bank-additional.csv  ──►  01_EDA_bank.ipynb   ──►  data/processed/bank_clean.csv
   └─ customer-details.xlsx ─►  02_EDA_customers.ipynb ─►  data/processed/customers_clean.csv
                                                  ▼
                                   03_EDA_merged.ipynb (merge por id_/ID)
                                                  ▼
                                   data/processed/bank_customers_final.csv


------------------------------------------------------------------------

## 🛠 Instalación y Requisitos

Este proyecto utiliza **Python 3.8+** y requiere las siguientes librerías:
  - pandas
  - numpy
  - matplotlib
  - seaborn

Para instalar dependencias:
``` bash
pip install pandas numpy matplotlib seaborn
```
------------------------------------------------------------------------

## 📊 Resultados y Conclusiones

- El dataset 'bank-additional' mostró que las variables más relacionadas con el éxito ('y') son la **duración de la llamada** y los **resultados de campañas anteriores**.
- El dataset 'customers' no presenta por sí solo relaciones fuertes con 'y', pero aporta contexto demográfico y de comportamiento.
- La unión de ambos datasets permitió enriquecer el análisis, aunque las variables adicionales (ingresos, hijos, visitas web) no resultaron determinantes.
- En general, **el éxito de las campañas está más influido por factores de interacción (llamadas, historial previo) que por características demográficas**.

------------------------------------------------------------------------

## 🔄 Próximos Pasos

- Profundizar en técnicas de modelado predictivo (ej. regresión logística, árboles de decisión) para estimar la probabilidad de éxito de una campaña.
- Explorar técnicas de segmentación de clientes para diseñar estratégias de marketing más efectivas.

------------------------------------------------------------------------

## ✒ Autores

- CELIA PALACIOS POVEA





