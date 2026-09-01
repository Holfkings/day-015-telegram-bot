# 🤖 TelegramBot - Bot de Telegram con Python

Bot de Telegram desarrollado en Python con funcionalidades de respuesta automática, comandos personalizados y manejo de mensajes. Ideal para automatizar tareas y proporcionar información instantánea a través de Telegram.

## ✨ Características

- **Comandos personalizados**: Responde a /start, /help, /info y más
- **Respuestas automáticas**: Procesa mensajes de texto y comandos
- **Manejo de errores**: Gestión robusta de excepciones
- **Configuración flexible**: Variables de entorno para tokens y opciones
- **Fácil despliegue**: Listo para ejecutar localmente o en la nube
- **Código modular**: Estructura escalable para añadir nuevos comandos

## 🚀 Instrucciones de uso

```bash
# Clonar el repositorio
git clone https://github.com/Holfkings/day-015-telegram-bot.git
cd day-015-telegram-bot

# Instalar dependencias
pip install python-telegram-bot

# Configurar token (crea un archivo .env con TELEGRAM_TOKEN=tu_token)
# Obtén tu token desde @BotFather en Telegram

# Ejecutar el bot
python bot.py
```

## 📁 Estructura de archivos

```
├── bot.py           # Lógica principal del bot
├── requirements.txt # Dependencias del proyecto
├── .env.example     # Ejemplo de configuración
└── README.md        # Esta documentación
```

## 🛠️ Stack técnico

- **Python 3.8+**: Lenguaje principal
- **python-telegram-bot**: Librería para la API de Telegram
- **dotenv**: Gestión de variables de entorno

---

Reto #100DíasEnGitHub por @Holfkings
