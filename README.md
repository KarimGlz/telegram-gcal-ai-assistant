# telegram-gcal-ai-assistant  

**Telegram Assistant Bot integrated with Google Calendar.**  
A scheduling assistant that allows any user to log in once deployed. Designed for personal or business use, with the potential to monetize or provide shared access across teams.  

---

## 📩 Contact  
For support, implementation guidance, or feature suggestions, please reach out at karim.glzm@gmail.com

---

**Bot Asistente de Telegram integrado con Google Calendar.**
 Un asistente agendador que permite a cualquier usuario iniciar sesión una vez desplegado. Diseñado para uso personal o empresarial, con potencial para monetizar o proporcionar acceso compartido entre equipos.

## ✨ Características

### 🔐 Autenticación y Seguridad
- **OAuth2 con Google Calendar** - Implementación completa de flujo OAuth2
- **Gestión automática de tokens** - Refresh automático de access tokens al expirar
- **URLs únicas por usuario** - Cada usuario recibe una URL personalizada única para autenticación
- **Manejo de sesiones** - Detección automática de sesiones expiradas y re-autenticación

### 🤖 Inteligencia Artificial
- **Agente AI con Google Gemini** - Procesamiento de lenguaje natural para entender comandos
- **LLM Chain para validación** - Extracción y validación inteligente de zonas horarias
- **Memoria conversacional** - El agente recuerda el contexto de conversaciones anteriores

### 🎙️ Procesamiento Multimodal
- **Transcripción de audio** - Envía comandos por voz usando Google Gemini 2.5 Flash
- **Detección automática** - Identifica si el mensaje es texto o audio automáticamente
- **Conversión instantánea** - Audio convertido a texto en tiempo real

### 📅 Gestión de Google Calendar
- **Herramientas personalizadas** - 4 herramientas especializadas creadas específicamente para este bot:
  - ✅ **Create Event Tool** - Crear eventos con detalles completos
  - 📖 **Get Event Tool** - Consultar eventos existentes
  - ✏️ **Update Event Tool** - Modificar eventos programados
  - ❌ **Delete Event Tool** - Eliminar eventos del calendario
- **Manejo de zonas horarias** - Soporte completo para diferentes zonas horarias por usuario
- **Acceso completo a tu calendario** - Operaciones CRUD completas

### 🔗 Webhooks y Base de Datos
- **Telegram Webhook** - Recepción en tiempo real de mensajes del usuario
- **Base de datos integrada** - Almacenamiento de usuarios, tokens y zonas horarias
- **Persistencia de sesión** - Los usuarios no necesitan autenticarse en cada uso

### 🌐 Flujo de Usuario Optimizado
- **Registro único** - Solo se requiere autenticación una vez
- **Validación inteligente** - Verificación automática de nuevos usuarios vs. usuarios existentes
- **Mensajes informativos** - Guía clara en cada paso del proceso
- **Recuperación de errores** - Manejo elegante de tokens expirados o errores de autenticación

 ---
## 📩 Contacto
Para soporte, orientación de implementación o sugerencias de funcionalidades, por favor comuníquese a karim.glzm@gmail.com
 
