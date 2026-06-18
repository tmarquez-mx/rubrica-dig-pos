<div align="center">

# 🎓 Rúbrica digital · Admisión a posgrado

### De horas de deliberación en papel a una decisión colegiada, transparente y sin imprimir.

[![Estado](https://img.shields.io/badge/estado-demo_funcional-C8102E)](#)
[![Hecho con](https://img.shields.io/badge/hecho_con-vibecoding-1A1A1A)](https://techiholic.netlify.app/)
[![Datos](https://img.shields.io/badge/datos-ficticios-6b7280)](#privacidad-y-datos)
[![Ciencia abierta](https://img.shields.io/badge/ciencia-abierta-10b981)](https://globaldiamantoa.org/manifiesto/)

</div>

---

## ✨ En una frase

Una aplicación que acompaña a las comisiones de profesores mientras entrevistan y evalúan a quienes aspiran a un posgrado: califican con criterios ponderados, ven el puntaje y la recomendación al instante, y llegan a la junta del colegio con un reporte listo, en lugar de un fajo de rúbricas en papel.

> A diferencia de otros artefactos del laboratorio, de orientación más conceptual, esta herramienta nació de un problema práctico: **ordenar y agilizar la deliberación de admisión**.

---

## 📊 Impacto

<div align="center">

| | |
|---:|:---|
| **≈ 60 %** | menos tiempo de deliberación de las comisiones |
| **0** | hojas impresas en todo el proceso |
| **2** | roles diferenciados (coordinación y profesorado) |
| **6** | líneas de investigación atendidas |

</div>

---

## 🧩 Qué hace

- **Rúbrica ponderada por programa.** Siete criterios con pesos distintos para Maestría y Doctorado; el puntaje total se recalcula al instante.
- **Dos roles con permisos propios.** La coordinación ve todo y genera reportes; cada profesor o profesora ve solo su línea de investigación.
- **Seis formas de ver la lista.** Cronológica, académica, administrativa, por línea, por dictamen y por asignación de beca.
- **Reporte visual completo.** Tablero de indicadores, gráficos por criterio, por línea y por dictamen, comparativa de perfiles y tabla analítica.
- **Comparación de candidaturas.** Selecciona varias y contrástalas en un gráfico de radar.
- **Exportación.** Descarga de resultados en CSV (compatible con Excel) e impresión a PDF.
- **Control del periodo de edición.** La coordinación abre o cierra la captura para el profesorado.

---

## 🌟 Dos detalles que marcan la diferencia

> **🏅 Límite automático de becas SECITHI.** El sistema ordena por puntaje y asigna las seis becas por programa de forma automática, enviando al resto a una lista de espera calculada al momento. Lo que antes era una hoja de cálculo aparte y propensa a errores, aquí es instantáneo.

> **🤖 Lectura cualitativa con IA.** En la versión real, un agente de inteligencia artificial sintetiza los comentarios de las comisiones y las tendencias del grupo en un informe redactado, listo para la junta del colegio. *(En esta demo pública el texto se omite por no incluir claves de servicios externos.)*

---

## 🚀 Demostración

La demo de este repositorio funciona con **datos ficticios** y puede abrirse directamente en el navegador o desplegarse como sitio estático.

```
1. Abre index.html en el navegador, o publícalo en GitHub Pages / Netlify.
2. Entra como "Coordinadora" para ver el reporte completo,
   o como "Profesor(a)" para ver el flujo de una sola línea.
3. Explora las vistas, califica, compara y exporta el CSV.
```

> ⚠️ La versión original empleada en procesos reales **no se publica**, porque maneja datos personales de las personas postulantes. Esta demo existe solo para ilustrar el funcionamiento de la herramienta.

---

## 🔒 Privacidad y datos

La aplicación funciona enteramente en el navegador: no envía información a ningún servidor ni la almacena fuera del equipo de quien la usa. Todos los datos de esta demostración son inventados y no corresponden a personas reales.

---

## 🛠️ Tecnología

| Demo pública | Versión real |
|:---|:---|
| HTML + CSS + JavaScript (un archivo) | React + TypeScript + Vite |
| Gráficos con Chart.js | Gráficos con Recharts |
| Datos ficticios en memoria | Firebase (Auth + Firestore) |
| Análisis de IA simulado | Agente de IA (Gemini) |

Desarrollada con asistencia de IA (*vibecoding*) como parte de un flujo de trabajo de humanidades digitales.

---

## 📄 Estado y licencia

Versión de demostración. Define aquí la licencia con la que deseas compartir el código (por ejemplo, MIT o CC BY).

---

<div align="center">

**Teresa Márquez** · Departamento de Ciencias Sociales y Políticas
Universidad Iberoamericana Ciudad de México

Parte del espacio de imaginación sociotécnica · [**Techiholic Labs**](https://techiholic.netlify.app/)

</div>
