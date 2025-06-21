# 🧠 WebGPU AI Chat Demo

Este proyecto es una prueba de concepto de un **chat con inteligencia artificial** utilizando tecnologías modernas del navegador como **WebGPU**, **Web Workers** y **Web LLaMA**. Cargamos un modelo de IA de forma local directamente en el navegador, sin necesidad de servidores externos.

## 🚀 Tecnologías utilizadas

- **WebGPU**: Permite utilizar la GPU del dispositivo directamente desde el navegador para acelerar los cálculos.
- **Web Workers**: Implementación de multihilo en JavaScript para mantener la interfaz fluida durante el procesamiento intensivo.
- **Web LLaMA**: Librería que permite ejecutar modelos de lenguaje grandes (LLMs) en el navegador, de forma completamente local.
- **HTML5 + JavaScript**: Interfaz simple, construida con tecnologías web estándar.

## ⚙️ Cómo usarlo

### 🔧 Abrir el archivo HTML

Abre `index.html` en tu navegador (preferentemente [Chrome Canary](https://www.google.com/chrome/canary/) con las flags de WebGPU activadas).

### ⏳ Esperar la carga del modelo

Una vez que la interfaz se carga, espera unos segundos a que se descargue y cargue el modelo localmente. Esto puede tardar dependiendo del hardware del usuario.

### 💬 Comenzar a chatear

Escribe tus consultas en el campo de texto y el modelo responderá directamente desde el navegador, sin conexión a servidores externos.

## 📦 Requisitos

- Navegador con **soporte para WebGPU** (Chrome Canary o Edge con flags activadas).
- Buen hardware para aprovechar la aceleración por GPU.
- Conexión inicial para descargar el modelo (se ejecuta localmente una vez cargado).

## 🔍 Objetivo del proyecto

Este proyecto explora la viabilidad de correr **modelos de lenguaje grandes (LLMs)** completamente en el navegador, **sin enviar datos al servidor**.  
Es ideal para casos donde la **privacidad** es fundamental o donde se desea evitar depender de APIs externas.

## 🧪 Estado del proyecto

- ✅ Prueba funcional  
- 🛠️ Interfaz mínima  
- 📈 En evaluación para mejoras de rendimiento y visual  

## 📸 Demo (opcional)

> *(Aquí puedes agregar una captura de pantalla o un video corto mostrando el funcionamiento del chat.)*

## 📄 Licencia

Este proyecto se publica bajo la licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.

---
