<div align="center">
  <img src="public/icon.png" alt="Second Brain Logo" width="120" />
  <h1>Second Brain 🧠</h1>
  <p><strong>Tu asistente de entrevistas invisible impulsado por IA</strong></p>

  [English](README.md) | [Português](README.pt.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md)
</div>

<br/>

**Second Brain** es un asistente de escritorio 100% gratuito e invisible creado para ayudar a los profesionales de todo el mundo a sobresalir en sus entrevistas de trabajo. Se ejecuta silenciosamente en segundo plano, escuchando la entrevista, y genera sugerencias de respuesta en primera persona basadas en tu propio currículum y en la descripción de la vacante.

Impulsado por la inferencia ultrarrápida de Llama-3 de [Groq](https://groq.com) y por el modelo Whisper-large-v3, todo el proceso — desde la captura de voz hasta la sugerencia inteligente — ocurre en milisegundos.

## ✨ Características

- **Transcripción de Voz en Tiempo Real**: Usa Whisper-v3 a través de la API de Groq para transcribir el habla del entrevistador con extrema precisión y velocidad.
- **Sugerencias con Contexto**: Analiza la conversación actual, tu currículum y la descripción de la vacante para sugerir las mejores respuestas posibles.
- **Soporte Multilingüe**: Interfaz y motor de IA 100% localizados para Inglés, Portugués, Español, Francés e Italiano.
- **Modo Invisible**: Construido con Electron, puede minimizarse para no estorbar mientras te enfocas en tu videollamada.
- **Privacidad Ante Todo**: Tu currículum, la vacante y tus claves API se guardan exclusivamente en el almacenamiento local (`localStorage`) de tu propio ordenador.

## 🚀 Guía Rápida (Descarga)

1. **Descarga el Instalador:**
   Obtén el último `Second Brain Setup .exe` desde nuestra página de [Releases](../../releases).
   
2. **Crea una Groq API Key Gratuita:**
   Ve a [console.groq.com](https://console.groq.com/keys) y genera una clave API gratuita. Es esencial para ejecutar el motor de la IA a alta velocidad.

3. **Instala y Configura:**
   - Abre la aplicación.
   - Pega tu Clave API.
   - Pega tu Currículum y la Descripción de la Vacante.
   - Selecciona tu idioma.
   - Haz clic en **Comenzar Entrevista** y ¡listo!

## 🛠️ Desarrollo (Para Programadores)

Si deseas compilar el código fuente o contribuir:

### Requisitos previos
- Node.js 18+
- npm o yarn

### Instalación

```bash
git clone https://github.com/2brain/second-brain.git
cd second-brain

# Instala las dependencias
npm install

# Inicia el servidor de desarrollo
npm run dev
```

### Compilando para Producción (Instalador)

```bash
# Compilar y generar el instalador de Electron
npm run dist
```
El instalador `.exe` se generará dentro de la carpeta `dist-installers`.

## 🤝 Apoya el Proyecto

Second Brain es open-source y gratuito para la comunidad. Si esta herramienta te ayudó a conseguir un empleo o a destacar en una entrevista, ¡considera invitarnos un café!

<a href="https://www.buymeacoffee.com/2brain" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>

## ❓ FAQ (Preguntas Frecuentes)

**1. ¿Es realmente 100% gratis?**
¡Sí! La aplicación es de código abierto y totalmente gratuita. Solo necesitas crear una cuenta gratuita en Groq para obtener tu clave de API, que actualmente ofrece un plan gratuito extremadamente generoso.

**2. ¿El reclutador puede ver o escuchar la IA?**
No. Second Brain se ejecuta como una ventana independiente en tu pantalla. No inyecta audio en tu micrófono y no comparte tu pantalla. Es completamente invisible para el entrevistador.

**3. ¿Están seguros mis datos? ¿Guardan mi currículum?**
Tu privacidad es nuestra prioridad absoluta. No tenemos base de datos. Tu clave de API, tu currículum y la descripción de la vacante se guardan estrictamente en el `localStorage` de tu propio ordenador. Nada se envía a nuestros servidores (¡porque no tenemos ninguno!).

**4. ¿Por qué la IA tarda en responder?**
La IA espera a que el entrevistador termine un razonamiento completo antes de generar una respuesta. Analiza el contexto en intervalos de 7 segundos para asegurarse de que ha entendido la pregunta completa antes de darte el guion.

**5. ¿Funciona en Mac o Linux?**
Actualmente, las versiones automatizadas (Releases) proporcionan un instalador `.exe` para Windows. Sin embargo, dado que es una aplicación Electron, puedes clonar fácilmente este repositorio y ejecutar `npm run dist` para compilar para macOS o Linux.

---

## 📝 Licencia

Distribuido bajo una Licencia No Comercial. Eres libre de usar y estudiar el software, pero **la venta o distribución comercial está estrictamente prohibida**. Consulta el archivo `LICENSE` para más información.
