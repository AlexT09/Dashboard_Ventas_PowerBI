# 📊 Dashboard de Ventas y Rentabilidad – Superstore (Power BI)

## 🚀 Descripción
Dashboard interactivo en Power BI construido sobre el dataset público **Sample Superstore**, orientado a identificar qué productos, regiones, categorías y segmentos de cliente generan más valor — y cuáles están destruyendo rentabilidad pese a vender bien.

---

## 🎯 Objetivo
Responder la pregunta de negocio central del dataset: **¿en qué productos, regiones y segmentos debería enfocarse (o dejar de invertir) la empresa?**

---

## 🛠️ Tecnologías utilizadas
- Power BI Desktop
- Power Query
- DAX
- Excel / CSV

---

## 📈 Métricas clave (KPIs)
- Total Sales — **$2,297,200.86**
- Total Profit — **$286,397.02**
- Profit Margin — **12.47%**
- Total Orders — **5,009**
- Avg Ticket — **$458.61**

---

## 📊 Estructura del Dashboard

### 📌 1. Resumen ejecutivo
- KPIs principales (Sales, Profit, Margin, Orders)
- Evolución mensual de Sales vs Profit (2014-2017)
- Ventas y ganancia por Category
- Ranking de ventas por Region

### 📌 2. Productos y rentabilidad
- Top 10 / Bottom 10 Sub-Category por Profit
- Matriz Category × Sub-Category (Sales, Profit)
- Scatter Discount vs Sales (relación inversa no lineal)

### 📌 3. Clientes y segmentos
- Ventas por Segment
- Ventas por Ship Mode
- Ticket promedio por segmento

---

## 💡 Insights principales
- **Technology** es la categoría más rentable ($145,455 de Profit) pese a no ser la de mayor volumen de pedidos.
- **Tables, Bookcases y Supplies dan pérdida neta** (Profit negativo: -$17,725 / -$3,473 / -$1,189) aunque generan ventas — candidatas a revisar descuentos o descontinuar.
- **West** es la región más rentable ($108,418 de Profit); **Central** es la más débil.
- **Consumer** es el segmento que más factura y más rentabilidad genera en términos absolutos.
- El descuento muestra una relación inversa con las ventas — a mayor descuento, menor rentabilidad neta, especialmente en Furniture.

---

## 📁 Estructura del repositorio
```
superstore-dashboard/
├── data/
│   └── Sample - Superstore.csv
├── screenshots/
│   ├── dashboard_resumen.png
│   ├── dashboard_productos.png
│   └── dashboard_segmentos.png
├── Superstore_Dashboard.pbix
└── README.md
```
