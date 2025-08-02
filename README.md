# 🎵 De las Series de Fourier a la Identificación de Música con FFT

> 📌 Un recorrido desde la teoría matemática pura hasta una aplicación funcional para el reconocimiento automático de música usando Python, FFT y fingerprinting digital.

---

## 📖 Descripción del Proyecto

Este proyecto nació como parte de la asignatura **Análisis Matemático III** de la carrera de **Ingeniería en Sistemas**, y tiene como objetivo mostrar cómo una idea matemática —las **series de Fourier**— puede transformarse en una herramienta computacional poderosa como la **Transformada Rápida de Fourier (FFT)** para resolver problemas complejos del mundo real.

Nos enfocamos en un caso práctico ampliamente conocido:
> 🎧 ¿Cómo puede una aplicación como **Shazam** identificar una canción con solo unos segundos de audio?

---

## 🎯 Objetivos

- Comprender la **intuición matemática** detrás de las Series y Transformadas de Fourier.
- Aplicar la **Transformada Rápida de Fourier (FFT)** a señales de audio reales.
- Construir un sistema básico de **identificación musical** mediante análisis espectral y huellas digitales (audio fingerprints).
- Explorar herramientas y librerías modernas para procesamiento digital de señales (DSP).

---

## 🧰 Tecnologías y Librerías Usadas

- **Python 3.10+**
- [`librosa`](https://librosa.org/) – análisis musical y espectrogramas
- [`pydub`](https://github.com/jiaaro/pydub) – manipulación de archivos de audio
- [`chromaprint`](https://acoustid.org/chromaprint) – generación de fingerprints
- [`mutagen`](https://mutagen.readthedocs.io/) – lectura de metadatos de archivos MP3
- [`matplotlib`](https://matplotlib.org/) – visualización de espectros y señales
- [`acoustid`](https://acoustid.org/) – API pública de reconocimiento musical (opcional)
- [`yt-dlp`](https://github.com/yt-dlp/yt-dlp) – descarga de audios desde YouTube (para pruebas)

---

## 📁 Estructura del Proyecto

