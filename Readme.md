# 🩺 NoMedic

**NoMedic** es una aplicación desarrollada en **Python** que tiene como objetivo **prevenir la automedicación** y promover el uso responsable de los medicamentos.  
A través de una interfaz simple e intuitiva, ayuda al usuario a identificar posibles riesgos de combinar fármacos y ofrece alternativas naturales y educativas.

---

## 🚀 Características principales

- 🏠 **Pantalla de inicio:**  
  Muestra el nombre del programa y una breve descripción del propósito de NoMedic, junto con un botón **“Comenzar evaluación”**.

- 💬 **Evaluación de síntomas:**  
  El usuario puede seleccionar hasta **4 síntomas** desde una base de datos interna.

- 💊 **Selección de medicamentos:**  
  El usuario indica si ha tomado algún medicamento.  
  - Si **no** tomó medicamentos → se muestran **alternativas naturales y consejos generales**.  
  - Si **sí** tomó medicamentos → puede seleccionar hasta **4 medicamentos**, y el programa evalúa el **riesgo de combinarlos** según la base de datos de interacciones.

- ⚠️ **Evaluación de riesgo:**  
  Analiza los medicamentos seleccionados y muestra un mensaje indicando si su combinación es **segura, moderadamente riesgosa o peligrosa**.

- 🌿 **Alternativas naturales:**  
  Se ofrecen soluciones naturales y hábitos saludables para aliviar los síntomas sin recurrir a la automedicación.

- 📚 **Sección educativa:**  
  Incluye información sobre los riesgos de la automedicación y el uso responsable de medicamentos.

- 👨‍⚕️ **Aviso importante:**  
  NoMedic **nunca reemplaza la opinión de un profesional de la salud**. Siempre se recomienda acudir a un **médico de confianza**.

---

## 🧠 Objetivo

El propósito de **NoMedic** es **concientizar a los usuarios sobre los peligros de la automedicación** y fomentar decisiones informadas respecto al consumo de medicamentos.

---

## 🖥️ Flujo del programa

1. **Pantalla inicial** → Muestra el nombre *NoMedic* y un resumen de su función.  
2. **Botón “Comenzar evaluación”** → Inicia la evaluación.  
3. **Selección de síntomas** → Máximo 4.  
4. **Selección de medicamentos** → Máximo 4 (opcional).  
5. **Evaluación de riesgo** → Muestra el nivel de riesgo según la base de datos.  
6. **Recomendaciones finales** →  
   - Nivel de riesgo (si aplica).  
   - Alternativas naturales.  
   - Recomendación de consultar a un médico.

---

## 🧩 Tecnologías utilizadas

| Tecnología | Uso |
|-------------|------|
| 🐍 **Python** | Lógica principal del programa. |
| 🪟 **Tkinter** | Interfaz gráfica (GUI). |
| 💾 **SQLite** | Base de datos local para almacenar síntomas, medicamentos y sus interacciones. |

---