# 🌱 Control de Radiación en Invernadero — CAETEC

Sistema de control automatizado a escala para regular la radiación solar incidente sobre cultivos de **jitomate y café**, desarrollado en colaboración con **CAETEC** (Campo Agrícola Experimental del Tecnológico de Monterrey). El sistema controla una membrana de acrílico con tecnología de cristal líquido (PDLC) que cambia de opaca a transparente según el voltaje aplicado, regulando la cantidad de luz que reciben las plantas.

**Equipo:** Tecnológico de Monterrey, en colaboración con CAETEC · Ago–Sep 2023

---

## 📽️ Demo

> https://www.youtube.com/watch?v=9-gIX0Ae0-E


---

## 🧠 ¿Cómo funciona?

El sistema regula la radiación solar mediante control de opacidad de una membrana, en lugar de un sistema mecánico de sombra tradicional (mallas o cortinas):

```
Sensor de luz/radiación
        ↓
Microcontrolador (ESP32 / Arduino)
        ↓
Actuador — Membrana de acrílico PDLC (12V, a escala)
        ↓
Regulación de luz incidente sobre el cultivo
```

**Principio de funcionamiento del actuador:**
- **Sin voltaje aplicado:** la membrana se torna de color **blanco/opaco**, bloqueando el paso de luz — simula una condición de sombra
- **Con 12V aplicados:** la membrana se vuelve **transparente**, permitiendo el paso de luz solar hacia el cultivo

Este principio corresponde a la tecnología de **PDLC (Polymer Dispersed Liquid Crystal)**, comúnmente usada en vidrios inteligentes, adaptada aquí a escala reducida para investigación en agricultura de precisión.

---

## 🎯 Objetivo del proyecto

Diseñar una solución de ingeniería que permitiera **automatizar el control de la cantidad de radiación solar** recibida por cultivos sensibles a la luz —como jitomate y café— con el fin de optimizar las condiciones de crecimiento y explorar alternativas a los sistemas de sombreo mecánico tradicionales (mallas, cortinas).

---

## 🛠️ Tech Stack

| Componente | Tecnología |
|---|---|
| Microcontroladores | ESP32 / Arduino |
| Actuador | Membrana de acrílico PDLC (control por voltaje, 12V a escala) |
| Sensores | Sensor de luz / radiación |
| Cultivos objetivo | Jitomate, café |
| Colaboración | CAETEC — Tecnológico de Monterrey |

---

## 📚 Lo que aprendí

- Control de actuadores no convencionales (membranas de cristal líquido) mediante señales de voltaje desde un microcontrolador
- Integración de sensores ambientales con lógica de control para regular condiciones de cultivo en tiempo real
- Aplicación de electrónica y control a un problema real de agricultura de precisión
- Trabajo colaborativo con un centro de investigación agrícola (CAETEC), traduciendo necesidades del área agronómica a una solución de ingeniería
- Rol de liderazgo en la coordinación del equipo para el diseño e implementación del prototipo

---

## ⚠️ Nota

Este proyecto fue desarrollado como prototipo a escala con fines de investigación y aprendizaje. El código fuente específico de este proyecto no se encuentra disponible actualmente en este repositorio.

---

## 👨‍💻 Autor

**Emmanuel Lechuga Arreola** — [LinkedIn](https://www.linkedin.com/in/emmanuel-lechuga-arreola-7189892bb/) · [GitHub](https://github.com/EmmaLA22)

Proyecto desarrollado en colaboración con **CAETEC — Tecnológico de Monterrey**.
