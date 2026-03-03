<p align="center">
  <img src="assets/banner.png" alt="JobFit Agent banner" width="100%" />
</p>

<div align="center">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
</div>

> **Autores:** Roberto De Gouveia y Jaquelin Da Costa  
> **Fecha:** Julio 2025  
> **Versión:** 1.6

---

## 📋 Descripción del Proyecto

Este proyecto implementa un **sistema avanzado de clasificación de flores** que combina información visual (imágenes) y metadatos (tipo de empaque, peso y país de origen) usando **redes neuronales multimodales**. Utiliza transfer learning con MobileNetV2 y técnicas modernas de procesamiento de datos y visualización, logrando resultados precisos y robustos.

---

## 🎯 Objetivos

- **Clasificación Multimodal:** Fusionar imágenes y metadatos para mejorar la precisión.
- **Análisis Exploratorio Completo:** Detectar problemas y comprender los datos.
- **Evaluación Exhaustiva:** Medir el rendimiento desde varias perspectivas.
- **Interfaz Interactiva:** Permitir predicciones en tiempo real con widgets.

---

## 🏗️ Arquitectura

- **Módulo de Imágenes:** MobileNetV2 preentrenado + capas densas.
- **Módulo de Metadatos:**
  - Embeddings para variables categóricas (tipo de empaque, país).
  - MLP para variable numérica (peso).
- **Fusión:** Concatenación de características.
- **Clasificación Final:** Capas densas + softmax.
- **Interfaz:** Widgets interactivos para subir imágenes y configurar metadatos.

---

## 📊 Dataset

- **Fuente:** [TensorFlow Flowers](https://www.tensorflow.org/datasets/catalog/tf_flowers) (5 clases).
- **División:** 80% entrenamiento, 20% validación.
- **Metadatos:** Simulados (empaque, peso, país).

---

## 🚀 Instrucciones de Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Skorpion02/flowers_classifier_advanced.git
   cd flowers_classifier_advanced
   ```

2. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```
   _Principales librerías: TensorFlow 2.15+, pandas, numpy, scikit-learn, matplotlib, seaborn, ipywidgets, imagehash, Pillow._

3. **Ejecuta el notebook o script:**
   - En Google Colab o Jupyter, ejecuta las celdas en orden.
   - En terminal:
     ```bash
     python flowers_classifier_advanced.py
     ```

4. **Sigue la interfaz interactiva:**  
   Al final, usa la interfaz para subir imágenes y predecir la clase junto con los metadatos configurables.

---

## 📈 Ejemplo de Resultados

- **Precisión en Validación:** ~84.9%
- **F1-Score Macro:** ~0.85
---

## 💡 Principales Características

- **Transfer learning** con MobileNetV2.
- **Data augmentation** para robustez.
- **Procesamiento multimodal**: imágenes + metadatos (embeddings + normalización).
- **Métricas avanzadas**: accuracy, F1, matriz de confusión, análisis de confianza.
- **Detección de duplicados** y análisis EDA visual.
- **Interfaz interactiva** con widgets (subida de imágenes, sliders, dropdowns).
- **Permutación de metadatos**: análisis de importancia de cada campo no visual.

---

## 🖥️ Tecnologías Utilizadas

| Área              | Herramientas         |
|-------------------|---------------------|
| Deep Learning     | TensorFlow, Keras   |
| Computer Vision   | MobileNetV2, PIL    |
| Ciencia de Datos  | pandas, numpy       |
| Evaluación        | scikit-learn        |
| Visualización     | matplotlib, seaborn |
| Interfaz          | ipywidgets, Jupyter |

---

## 🚧 Mejoras Futuras

- Desplegar como **API REST** o demo web.
- Integrar nuevos metadatos (temporada, variedad).
- Probar arquitecturas de fusión más sofisticadas (attention, ensembles).
- Soporte para nuevos datasets reales de flores.

---

## 📚 Créditos

- Basado en [TensorFlow Flowers Dataset](https://www.tensorflow.org/datasets/catalog/tf_flowers).
- Inspirado por mejores prácticas de deep learning multimodal.

---

## 📝 Cita

Si usas este código, por favor cita el repositorio y a los autores:

> De Gouveia, R. & Da Costa, J. (2025). Clasificador de Flores Multimodal.  
> https://github.com/Skorpion02/flowers_classifier_advanced

---
## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

## 🤝 Contribuciones

¡Contribuciones, issues y sugerencias son bienvenidas!  
No dudes en abrir un issue o un pull request.

---

## 📬 Contacto

Para dudas o sugerencias, abre un issue o contacta a través de [Skorpion02](https://github.com/Skorpion02).

---

⭐️ **Si te gustó este proyecto, ¡déjale una estrella!**

---

<div align="center">
  <b>¡Combina lo mejor del Deep Learning Visual y la Ciencia de Datos para clasificar flores como nunca antes!</b>
</div>

<div align="center">
  <b>Hecho con ❤️ por Skorpion02</b>
</div>
