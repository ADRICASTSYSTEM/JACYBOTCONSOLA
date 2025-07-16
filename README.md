<p align="center">
  <img src="https://img.icons8.com/external-flat-juicy-fish/120/000000/external-chatbot-automation-flat-flat-juicy-fish.png" width="100" alt="Chatbot Icon"/>
</p>

<h1 align="center">JACYBOTCONSOLA</h1>

<p align="center">
  🤖 Chatbot de consola desarrollado en Python.  
  <br/>
  Entrenado con datos personalizados, ideal para experimentos de IA y asistentes virtuales.
</p>

---

## 📌 Descripción

**JACYBOTCONSOLA** es un chatbot por línea de comandos creado con Python. Utiliza redes neuronales y procesamiento de lenguaje natural para responder preguntas basadas en un conjunto de datos de entrenamiento (CSV). Es ideal como prototipo educativo o base para aplicaciones más complejas.

---

## 🚀 Funcionalidades

- Chat en tiempo real por consola
- Entrenamiento con archivos `.csv`
- Uso de modelo RNN (`rnn_model.h5`)
- Tokenización y codificación de etiquetas (`tokenizer.pkl`, `label_encoder.pkl`)
- Fácil integración con hardware (Arduino, Serial, etc.)

---

## 📁 Estructura del proyecto

```bash
JACYBOTCONSOLA/
├── chatbot.py
├── datos2.csv
├── entrenadores.csv
├── modelo_entrenado/
│   ├── rnn_model.h5
│   ├── tokenizer.pkl
│   └── label_encoder.pkl
└── requirements.txt
