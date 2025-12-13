# Configuración de Formspree para PQRS

## ✅ Formulario PQRS Configurado

El formulario PQRS está configurado para funcionar con **Formspree**, un servicio gratuito que permite recibir envíos de formularios en sitios estáticos.

### 📧 Email de destino

- **Correo**: oscar_jsv@outlook.com
- Los envíos del formulario llegarán a este email

### 🔑 Endpoint de Formspree

- **Form ID**: `xwpkkkyk`
- **URL**: `https://formspree.io/f/xwpkkkyk`

### ⚙️ Configuración actual

El formulario incluye:

- ✅ Nombre completo
- ✅ Email (con `_replyto` para poder responder directamente)
- ✅ Teléfono (opcional)
- ✅ Tipo de solicitud (Petición, Queja, Reclamo, Sugerencia)
- ✅ Mensaje
- ✅ Protección anti-spam (`_gotcha` field)
- ✅ Asunto personalizado: "Nueva solicitud PQRS - AGUARIO"

### 📝 Primer uso

**IMPORTANTE**: La primera vez que alguien envíe el formulario, Formspree enviará un email de confirmación a oscar_jsv@outlook.com. Debes hacer clic en el enlace de confirmación para activar el formulario.

### 🚀 Compatible con GitHub Pages

Este formulario funciona perfectamente en:

- ✅ GitHub Pages
- ✅ Netlify
- ✅ Vercel
- ✅ Cualquier hosting de sitios estáticos

### 📊 Límites del plan gratuito

- **50 envíos/mes** gratis
- Si necesitas más, puedes actualizar a un plan pago en formspree.io

### 🔄 Cambiar el email de destino

Si necesitas cambiar el email más adelante:

1. Ve a [formspree.io](https://formspree.io)
2. Crea una cuenta con el nuevo email
3. Crea un nuevo formulario
4. Reemplaza el `action` en `pqrs.html` con el nuevo endpoint

### 📱 Notificaciones

Cada vez que alguien envíe el formulario, recibirás un email con:

- Nombre del remitente
- Email (podrás responder directamente)
- Teléfono
- Tipo de solicitud
- Mensaje completo

---

**El sitio sigue siendo 100% estático y compatible con GitHub Pages** 🎉
