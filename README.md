# Análisis de embudo de conversión y pruebas A/B en app de e-commerce:

## Descripción
Este proyecto analiza el comportamiento de los usuarios en una aplicación de una empresa dedicada a la venta de productos alimenticios. El objetivo principal es entender el flujo de usuarios a través del embudo de ventas y evaluar el impacto de un cambio en la tipografía de la app mediante un test A/A/B.

## 🎯 Objetivos
- Identificar en qué etapas del embudo de ventas los usuarios abandonan el proceso antes de completar una compra.
- Validar la confiabilidad del test A/A/B mediante la comparación entre grupos de control.
- Determinar si el cambio de tipografía afecta significativamente el comportamiento de los usuarios en la app.

## 🧰 Tecnologías utilizadas

- Python
- Pandas, Numpy
- Matplotlib
- Statsmodels (prueba de proporciones Z)
- Jupyter Notebook

## Metodología
- Análisis del embudo de ventas basado en eventos de usuario.
- Pruebas estadísticas (z-test) para comparar proporciones de usuarios entre grupos experimentales y de control.
- Evaluación de diferencias significativas con un nivel de confianza del 95% (α = 0.05).

## Datos
Los datos incluyen registros de eventos con las siguientes columnas principales:
- `EventName`: Nombre del evento generado por el usuario.
- `DeviceIDHash`: Identificador único del usuario.
- `EventTimestamp`: Marca temporal del evento.
- `ExpId`: Identificador del experimento (246 y 247 = grupos control; 248 = grupo prueba).

## 📌 Resultados
Se concluye que el cambio de tipografía no impacta significativamente el flujo de usuarios a través del embudo de ventas.

---

## 🧠 Autor

David Gustavo Alfonso Torres  
[LinkedIn](https://www.linkedin.com/in/david-alfonso-24a197321/) | [GitHub](https://github.com/DavidAlfonso-19)


