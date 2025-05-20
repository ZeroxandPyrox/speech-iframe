# 🎤 speech.html – Reconocimiento de Voz para Wix Chatbot

Este proyecto contiene un archivo `speech.html` que habilita reconocimiento de voz usando la API Web Speech en navegadores compatibles (como Google Chrome). Se usa dentro de un sitio Wix mediante un **iframe HTML embebido**, permitiendo a los usuarios dictar su mensaje por voz y enviarlo automáticamente a un chatbot.

## 🚀 ¿Para qué sirve?

Permite a los visitantes de tu página web interactuar con un chatbot mediante comandos de voz, ideal para mejorar la accesibilidad o la experiencia del usuario.

## 🛠 Cómo funciona

- Usa `SpeechRecognition` del navegador (compatible con Chrome).
- Envía el texto reconocido al iframe padre mediante `postMessage`.
- Wix recibe el mensaje y lo introduce automáticamente en un campo de entrada, donde luego se procesa.

## 📦 Contenido

