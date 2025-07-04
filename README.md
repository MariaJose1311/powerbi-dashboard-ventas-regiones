# Dashboard de Ventas por Región y Producto (Power BI)

Este proyecto presenta un **dashboard interactivo en Power BI** que analiza las ventas por producto, región, ciudad, año y vendedor. Está basado en los datos extraídos y trabajados originalmente desde un archivo Excel.

## 📊 Características del Dashboard

- Filtros interactivos por **año**, **producto** y **región**
- Visualización de:
  - Total de ventas (€)
  - Unidades vendidas
  - Número de regiones por producto
  - Comparativa entre vendedores
- Tablas y gráficos dinámicos
- Automatización de cálculos de subtotales

## 🧾 Fuentes de Datos

- `Datos_crudo.xlsx`: archivo Excel con los datos originales
- `Calculo.xlsx`: archivo Excel con preprocesado con fórmulas avanzadas y tablas dinámicas.
- `MACRO.xlsx`: archivo Excel con Macro grabada
- `Resumen_ejecutivo_ventas.pbix`: archivo Power BI que importa, transforma y visualiza los datos.

## 📁 Estructura del repositorio

powerbi-dashboard-ventas-regiones/
├── Resumen_ejecutivo_ventas.pbix # Archivo principal de Power BI
├── data/
│ └── Datos_crudos.xlsx # Datos fuente en Excel para creación de Dashboard
│ └── Calculos.xlsx # Excel con calculos
│ └── MACRO.xlsx # Excel con MACRO generada
├── screenshots/
│ └── Dashboard.pdf # Vista previa del dashboard
└── README.md # Descripción del proyecto


## 💡 Cómo usar

1. Clona o descarga este repositorio
2. Abre `Dashboard.pbix` en Power BI Desktop
3. Si es necesario, actualiza la conexión a `Datos_crudo.xlsx` en Power Query (pestaña Transformar Datos > Administrar orígenes)
4. Explora los gráficos y filtros para analizar la información

## 🛠 Tecnologías

- Microsoft Power BI
- Microsoft Excel
  - Funciones como `SUMAR.SI.CONJUNTO`, `BUSCARV`, `CONTAR.UNICOS`
  - Tablas dinámicas y macros

## 📷 Vista previa

![Dashboard Preview](screenshots/Dashhboard.pdf)

## 🧑‍💻 Autor

- Nombre: Maria Jose Suarez
- Contacto: https://www.linkedin.com/in/suarezmariajose/

---

¡Contribuciones y sugerencias son bienvenidas!