# X4-ADDRESS-BYPASS 🚀

> El bot de Telegram más avanzado para análisis de direcciones con IA en 2025

## ✨ Características

- 🤖 **IA Avanzada**: Powered by Google Gemini
- 🎯 **Análisis Preciso**: Determina direcciones más cercanas con alta precisión
- 💫 **UI Moderna**: Interfaz con botones interactivos y menús dinámicos
- ⚡ **Super Rápido**: Respuestas en menos de 2 segundos
- 🔥 **Múltiples Formatos**: Acepta consultas naturales y estructuradas
- 🌐 **Serverless**: Deploy en Vercel con escalado automático

## 🛠️ Configuración Rápida

### 1. Crear Bot de Telegram
```bash
# Habla con @BotFather en Telegram
/newbot
# Nombre: X4-ADDRESS-BYPASS
# Username: x4_address_bypass_bot
# Guarda el token que te da
```

### 2. Obtener API Key de Gemini
```bash
# Ve a: https://makersuite.google.com/app/apikey
# Crear nueva API key
# Guarda la key
```

### 3. Deploy en Vercel
```bash
# Instalar Vercel CLI
npm i -g vercel

# Clonar y configurar
git clone tu-repo
cd x4-address-bypass
npm install

# Configurar variables de entorno
vercel env add BOT_TOKEN
vercel env add GEMINI_API_KEY

# Deploy
vercel --prod
```

### 4. Configurar Webhook
```bash
# Reemplaza con tus datos
curl -X POST "https://api.telegram.org/bot<TU_BOT_TOKEN>/setWebhook?url=https://<TU-VERCEL-URL>/api/x4-address-bypass"
```

## 🎮 Uso del Bot

### Formato Estructurado
```
Dirección base: 8246 NW 66th St, Miami, FL

Opciones:
1. 400 NW 72nd Ave, Miami, FL
2. 9200 NW 36th St, Miami, FL
3. 1601 NW 97th Ave, Miami, FL

¿Cuál está más cerca?
```

### Formato Natural
```
¿Cuál de estas direcciones está más cerca de 8246 NW 66th St Miami: 
- 400 NW 72nd Ave
- 9200 NW 36th St  
- 1601 NW 97th Ave
```

## 🚀 Características Avanzadas

- **Botones Interactivos**: Navegación moderna con inline keyboards
- **Análisis Multi-punto**: Comparación de múltiples ubicaciones
- **Modo Avanzado**: Funciones especiales para power users
- **Feedback System**: Rating y reporte de errores
- **Estadísticas**: Métricas de uso y rendimiento
- **Responsive Design**: Adaptado para móvil y desktop

## 🎯 Comandos Disponibles

- `/start` - Menú principal con interfaz moderna
- `/help` - Guía completa de uso
- `/stats` - Estadísticas del bot
- `/settings` - Configuración personalizada

## 🔧 Variables de Entorno

```env
BOT_TOKEN=tu_telegram_bot_token
GEMINI_API_KEY=tu_gemini_api_key
```

## 📱 Demo

Una vez configurado, tu bot tendrá:

1. **Menú Principal** con botones elegantes
2. **Búsqueda Inteligente** con ejemplos
3. **Resultados Formateados** con análisis detallado
4. **Interfaz Responsive** para cualquier dispositivo
5. **Feedback System** para mejora continua

## 🎨 Personalización

El bot incluye:
- Emojis modernos y consistentes
- Mensajes formateados con Markdown
- Botones contextuales
- Respuestas dinámicas
- Loading states elegantes

## 🚀 Próximas Características

- [ ] Integración con Google Maps API real
- [ ] Análisis de tráfico en tiempo real
- [ ] Exportación de resultados
- [ ] Modo multi-idioma
- [ ] Dashboard web
- [ ] Analytics avanzados

## 📞 Soporte

¿Problemas? ¡Contáctanos!
- GitHub Issues: [Reportar Bug](https://github.com/tu-usuario/x4-address-bypass/issues)
- Telegram: [@tu_username](https://t.me/tu_username)

---

> **X4-ADDRESS-BYPASS** - El futuro del análisis de direcciones está aquí 🔥
