# 📈 Mejora continua 2026

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1557b0?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Formato](https://img.shields.io/badge/formato-.pbip-555?style=for-the-badge)

> Tablero para seguir las **iniciativas de mejora continua** del año: cuántas hay, en qué estado están, quién es responsable y cuáles tienen impacto económico.

## 📌 Qué responde

- ¿Cuántas mejoras hay registradas y qué porcentaje está **implementado**, **en proceso** o **no iniciado**?
- ¿Cómo evolucionan las implementaciones **mes a mes**?
- ¿Qué sitios, unidades y puestos concentran las mejoras?
- ¿Cuántas iniciativas tienen **impacto económico**?

## 🧱 Modelo

Una tabla `Mejoras`, cargada desde el Excel de seguimiento [`01. MEJORA_CONTINUA_2026 v2.xlsm`](01.%20MEJORA_CONTINUA_2026%20v2.xlsm) a través del parámetro `RutaExcel`.

Columnas: Nro, Mejora, Acción, Fecha de implementación, Sitio, Unidad, Puesto, Status IDOC, Estado, Responsable, Impacto económico, Mes.

## 📐 Medidas

| Medida | Qué mide |
|---|---|
| Mejoras totales | Cantidad de iniciativas |
| Implementadas / En proceso / No iniciadas | Conteo por estado |
| % Implementadas / % En proceso / % No iniciadas | Participación de cada estado |
| Con impacto económico | Iniciativas con ahorro o beneficio informado |
| Texto … / Color Estado | Textos dinámicos y formato condicional |

## ▶️ Cómo abrirlo

1. Abrir `Mejora Continua 2026.pbip` (o el `.pbix`) con Power BI Desktop.
2. En **Transformar datos → Parámetros**, apuntar `RutaExcel` al archivo `.xlsm` del repo.
3. Actualizar.
