# InmoBot - Demo Chatbot Inmobiliario

Demo estático de chatbot para inmobiliarias argentinas con respuestas simuladas inteligentes.

## ✨ Características

- **Chat interactivo** con respuestas simuladas inteligentes
- **8 propiedades demo** en zonas de Buenos Aires
- **Búsquedas inteligentes** por zona, precio, ambientes y tipo
- **Sistema de reservas completo** con formularios y confirmación
- **Captura de leads** con datos de contacto
- **Interfaz responsive** con TailwindCSS
- **Flujo completo**: Consulta → Encuentra propiedad → Reserva → Sube comprobante → Confirmación

## 🏠 Propiedades Demo

- Departamentos y casas en Palermo, Recoleta, Puerto Madero, San Telmo, Belgrano, Caballito, Villa Crespo y Núñez
- Precios desde USD 140.000 hasta USD 320.000
- 1 a 4 ambientes
- Superficies de 45m² a 140m²

## 🤖 Funcionalidades del Bot

El bot puede responder sobre:
- Búsquedas por zona, precio y ambientes
- Características de propiedades específicas
- Agendar visitas (simulado)
- Requisitos para alquilar
- Proceso de reserva completo

## 🚀 Deploy en Vercel

### Opción 1: Deploy desde GitHub

1. Sube el proyecto a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) e inicia sesión
3. Click en "New Project"
4. Importa tu repositorio de GitHub
5. Vercel detectará automáticamente que es un sitio estático
6. Click "Deploy"

### Opción 2: Deploy directo

1. Instala Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. En la carpeta del proyecto, ejecuta:
   ```bash
   vercel
   ```

3. Sigue las instrucciones:
   - Link to existing project? → **No**
   - Project name → **inmobot-demo** (o el nombre que prefieras)
   - In which directory is your code located? → **./** (carpeta actual)

4. Vercel detectará automáticamente la configuración y deployará

### Opción 3: Drag & Drop

1. Ve a [vercel.com/new](https://vercel.com/new)
2. Arrastra la carpeta del proyecto al área de "Deploy"
3. Vercel subirá y deployará automáticamente

## 📱 Uso

1. Abre la aplicación en el navegador
2. Inicia conversación con el bot
3. Ejemplos de preguntas:
   - "Busco departamento en Palermo"
   - "Casas hasta 200 mil dólares"
   - "Propiedades de 2 ambientes"
   - "Quiero ver los requisitos para alquilar"

## 🛠️ Tecnologías

- **HTML5** + **React 18** (CDN)
- **TailwindCSS** (CDN)
- **Babel** para JSX (CDN)
- **Sin backend** - Todo estático
- **Pattern matching** para respuestas inteligentes

## 📁 Estructura

```
Demo-ChatBot-Inmobiliaria/
├── index.html          # Aplicación completa
├── README.md           # Documentación
└── Prompt-Chatbot-Inmobiliaria.txt  # Especificaciones originales
```

## 🎯 Casos de Uso

- **Demo para inmobiliarias**: Mostrar capacidades de IA
- **Proof of concept**: Validar idea antes de desarrollo completo
- **Marketing**: Generar leads e interés
- **Presentaciones**: Demo en tiempo real

¡Tu chatbot inmobiliario está listo para mostrar! 🏡🤖