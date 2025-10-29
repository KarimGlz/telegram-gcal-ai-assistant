# telegram-gcal-ai-assistant  

**Telegram Assistant Bot integrated with Google Calendar.**  
A scheduling assistant that allows any user to log in once deployed. Designed for personal or business use, with the potential to monetize or provide shared access across teams.  

## 🎬 See it in action

![Bot Demo](assets/gif.gif)

## ✨ What can it do?

### 🔐 Secure & Easy Authentication
- **One-time Google login** - Connect your calendar once, and you're all set
- **Smart token management** - Keeps you logged in automatically, refreshing tokens behind the scenes
- **Personal login links** - Every user gets their own secure authentication URL
- **Session recovery** - Detects expired sessions and smoothly guides you through re-authentication

### 🤖 AI-Powered Intelligence
- **Natural language understanding** - Talk to it like you would to a person (powered by Google Gemini)
- **Smart timezone handling** - Automatically extracts and validates your timezone from conversation
- **Conversation memory** - Remembers context from your previous messages for more natural interactions

### 🎙️ Works Your Way
- **Voice or text** - Send voice messages and the bot transcribes them instantly using Gemini 2.5 Flash
- **Automatic detection** - Knows whether you're sending audio or text without you having to specify
- **Real-time processing** - Voice commands are converted to text on the fly

### 📅 Full Calendar Control
**4 specialized tools built specifically for this bot:**
  - ✅ **Create** - Schedule new events with all the details
  - 📖 **Read** - Check what's coming up on your calendar
  - ✏️ **Update** - Modify existing events whenever you need
  - ❌ **Delete** - Remove events that are no longer needed
  
Plus full timezone support and complete CRUD operations for your calendar.

### 🔗 Under the Hood
- **Real-time updates** - Uses Telegram webhooks for instant message delivery
- **Persistent storage** - Saves user data, tokens, and preferences in an integrated database
- **Stay logged in** - No need to authenticate every time you use it
- **Smart user flow** - Automatically recognizes new vs. returning users and guides them accordingly

## 🛠️ Built With

- **n8n** - Workflow automation platform
- **Google Gemini 2.5 Flash** - AI model for language processing and transcription
- **Telegram Bot API** - For seamless chat integration
- **Google Calendar API** - Full calendar access and management
- **OAuth2** - Secure authentication protocol
- **n8n DataTable** - Built-in database for data persistence

## 💡 Ideas for Improvement

Want to make it even better? Here are some suggestions:

- 🔄 **Switch to OpenAI** - For improved reasoning and better performance (especially with complex queries)
- 🔔 **Smart reminders** - Get notified before your events start
- 🌍 **Multi-language support** - Automatically detect and respond in the user's language
- 📊 **Usage analytics** - Track how people are using the bot and gather insights
- 🎨 **Prettier responses** - Use Markdown formatting for more readable Telegram messages

---

## 📩 Get in Touch

This is a personal portfolio project, but I'd love to hear from you if you:
- Found a bug and want to report it
- Have ideas for improvements
- Want to share how you're using it
- Need help with implementation

Feel free to reach out at **karim.glzm@gmail.com**

---

**Made with ❤️ as a learning project**
---

**Bot Asistente de Telegram integrado con Google Calendar.**
 Un asistente agendador que permite a cualquier usuario iniciar sesión una vez desplegado. Diseñado para uso personal o empresarial, con potencial para monetizar o proporcionar acceso compartido entre equipos.

## ✨ ¿Qué puede hacer?

### 🔐 Autenticación Segura y Fácil
- **Inicio de sesión único con Google** - Conecta tu calendario una vez y listo
- **Gestión inteligente de tokens** - Te mantiene conectado automáticamente, renovando tokens en segundo plano
- **Enlaces personalizados** - Cada usuario recibe su propia URL segura de autenticación
- **Recuperación de sesión** - Detecta sesiones expiradas y te guía suavemente en la re-autenticación

### 🤖 Inteligencia Artificial
- **Comprensión de lenguaje natural** - Háblale como le hablarías a una persona (potenciado por Google Gemini)
- **Manejo inteligente de zonas horarias** - Extrae y valida automáticamente tu zona horaria desde la conversación
- **Memoria conversacional** - Recuerda el contexto de tus mensajes anteriores para interacciones más naturales

### 🎙️ Funciona a Tu Manera
- **Voz o texto** - Envía mensajes de voz y el bot los transcribe instantáneamente usando Gemini 2.5 Flash
- **Detección automática** - Sabe si estás enviando audio o texto sin que tengas que especificarlo
- **Procesamiento en tiempo real** - Los comandos de voz se convierten a texto al instante

### 📅 Control Completo del Calendario
**4 herramientas especializadas construidas específicamente para este bot:**
  - ✅ **Crear** - Programa nuevos eventos con todos los detalles
  - 📖 **Leer** - Revisa qué tienes próximamente en tu calendario
  - ✏️ **Actualizar** - Modifica eventos existentes cuando lo necesites
  - ❌ **Eliminar** - Remueve eventos que ya no son necesarios
  
Además, soporte completo de zonas horarias y operaciones CRUD completas para tu calendario.

### 🔗 Bajo el Capó
- **Actualizaciones en tiempo real** - Usa webhooks de Telegram para entrega instantánea de mensajes
- **Almacenamiento persistente** - Guarda datos de usuario, tokens y preferencias en una base de datos integrada
- **Mantente conectado** - No necesitas autenticarte cada vez que lo uses
- **Flujo inteligente de usuario** - Reconoce automáticamente usuarios nuevos vs. recurrentes y los guía en consecuencia

## 🛠️ Construido Con

- **n8n** - Plataforma de automatización de workflows
- **Google Gemini 2.5 Flash** - Modelo de IA para procesamiento de lenguaje y transcripción
- **Telegram Bot API** - Para integración perfecta con el chat
- **Google Calendar API** - Acceso y gestión completa del calendario
- **OAuth2** - Protocolo de autenticación segura
- **n8n DataTable** - Base de datos integrada para persistencia de datos

## 💡 Ideas para Mejorar

¿Quieres hacerlo aún mejor? Aquí hay algunas sugerencias:

- 🔄 **Cambiar a OpenAI** - Para mejor razonamiento y rendimiento mejorado (especialmente con consultas complejas)
- 🔔 **Recordatorios inteligentes** - Recibe notificaciones antes de que empiecen tus eventos
- 🌍 **Soporte multiidioma** - Detectar y responder automáticamente en el idioma del usuario
- 📊 **Analíticas de uso** - Rastrear cómo las personas usan el bot y obtener insights
- 🎨 **Respuestas más bonitas** - Usar formato Markdown para mensajes de Telegram más legibles

---

## 📩 Ponte en Contacto

Este es un proyecto personal de portfolio, pero me encantaría saber de ti si:
- Encontraste un bug y quieres reportarlo
- Tienes ideas para mejoras
- Quieres compartir cómo lo estás usando
- Necesitas ayuda con la implementación

No dudes en contactarme en **karim.glzm@gmail.com**

---

**Hecho con ❤️ como proyecto de aprendizaje**
