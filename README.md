# 🌐 Traductor · Conectando palabras

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

Una aplicación web de traducción moderna, minimalista y responsiva con estética editorial. Diseñada con un área de trabajo amplia, soporte para voz, atajos de teclado y traducción automática sin necesidad de configuraciones complejas.

---

## ✨ Características

* ⚡ **Traducción Automática:** Detección de escritura con sistema *debounce* (500 ms) para traducir mientras escribís.
* 🌓 **Modo Oscuro / Claro:** Tema oscuro activado por defecto con conmutación fluida en tiempo real.
* 🗣️ **Text-to-Speech (Voz):** Reproducción de audio en idioma nativo para ambos campos, con control de parada (*Stop*) instantáneo.
* 🔄 **Sello de Intercambio (Swap):** Invierte el idioma de origen y destino junto con sus contenidos.
* 📋 **Copiado al Portapapeles:** Copiá la traducción obtenida con un solo clic y retroalimentación visual instantánea.
* ⌨️ **Atajos de Teclado:**
  * `Ctrl + Enter` (o `Cmd + Enter`): Forzar traducción manual.
  * `Alt + S` / `Ctrl + Shift + S`: Intercambiar idiomas (Swap).
* 📏 **Límite de Caracteres:** Indicador visual dinámico con capacidad máxima de 500 caracteres.
* 📱 **Diseño Ultra Responsivo:** Área de texto extendida para lectura cómoda tanto en escritorio como en dispositivos móviles.

---

## 🛠️ Tecnologías Utilizadas

* **Markup:** HTML5 semántico.
* **Estilos & UI:** [Tailwind CSS (Play CDN)](https://tailwindcss.com/) + Google Fonts (*Source Serif 4*, *Inter*, *JetBrains Mono*).
* **Lógica:** JavaScript Vanilla (ES6+).
* **API de Traducción:** [MyMemory Translation API](https://mymemory.translated.net/) (sin necesidad de API Keys).
* **API de Audio:** Web Speech API (`window.speechSynthesis`) nativa del navegador.

---

## 🚀 Uso Rápido

No requiere instalación de dependencias, entornos de Node.js ni procesos de compilación (*build*).

1. **Clonar o descargar el repositorio:**
```bash
git clone [https://github.com/matiasdiaz142/translate-web.git](https://github.com/matiasdiaz142/translate-web.git)
