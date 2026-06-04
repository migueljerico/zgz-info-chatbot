# 🤖 ZGZ Info — Chatbot Municipal de Zaragoza

![Landbot](https://img.shields.io/badge/Landbot-No%20Code-5A45FF?style=for-the-badge&logo=chatbot&logoColor=white)
![GPT](https://img.shields.io/badge/OpenAI-GPT%20PLN-412991?style=for-the-badge&logo=openai&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Completado-4CAF50?style=for-the-badge)
![Tipo](https://img.shields.io/badge/Práctica-No%20Code%20%2F%20IA-FF6B6B?style=for-the-badge)

> **Ejercicio Práctico — Creación de Chatbots con IA**  
> Asistente virtual municipal para el **Ayuntamiento de Zaragoza**

---

## 📋 Descripción del Proyecto

**ZGZ Info** es un chatbot desarrollado en **Landbot** que proporciona información municipal clara, oficial y accesible a la ciudadanía de Zaragoza. Integra un bloque de **IA con GPT** para interpretar preguntas en lenguaje natural, gestionar trasbordos cuando no existe conexión directa y derivar a los recursos oficiales del Ayuntamiento cuando el dato exacto no está disponible.

---

## ⚙️ Funcionalidades

### 🚌 Transporte Público
- Líneas, horarios y frecuencias de **autobús urbano**
- **Tranvía** (Línea 1)
- Bicicleta pública **Bizi** — precios y estaciones
- **Cercanías**
- Gestión de **trasbordos** cuando no hay conexión directa al destino

### 🏛️ Servicios Municipales

| Ámbito | Cobertura |
|---|---|
| **Trámites** | Empadronamiento, tasas, licencias |
| **Cultura y Turismo** | Basílica del Pilar, La Seo, Aljafería, Fiestas del Pilar |
| **Otros servicios** | Deportes, medioambiente, atención social, avisos municipales |

---

## 🧩 Configuración del Agente IA

### System Prompt — Bloque GPT de Landbot

```
Eres "ZGZ Info", asistente virtual del Ayuntamiento de Zaragoza.
Tu función es dar información municipal clara, oficial y útil a la ciudadanía.
```

### Reglas de interacción

| Regla | Descripción |
|---|---|
| ✅ Solo Zaragoza | Reconduces amablemente si la pregunta es ajena a la ciudad |
| ✅ Tono conciso | Cercano, profesional y claro — máx. 4-5 frases por respuesta |
| ✅ Datos reales | Precios Bizi, teléfono 010 y horarios verificados en fuentes oficiales |
| ✅ Saludo inicial | Presenta el asistente y pregunta en qué puede ayudar |
| ❌ No inventa | Nunca genera horarios, precios ni teléfonos sin fuente |
| ❌ Deriva si no sabe | Redirige al **010** o a [zaragoza.es](https://www.zaragoza.es) |

---

## 🔍 Protocolo de pruebas

- Recorrido exhaustivo de todos los caminos y ramas del constructor (builder)
- Verificación de todos los enlaces en entorno de producción
- Validación de datos con fuentes oficiales del Ayuntamiento

---

## 🧰 Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| **Landbot** | Constructor visual de chatbot (no-code) |
| **OpenAI GPT** | Procesamiento de lenguaje natural (PLN) |
| **Flujos condicionales** | Ramificación lógica según intención del usuario |

---

## 👥 Equipo de desarrollo

Proyecto desarrollado en equipo por **Mayelin, Miguel y Francisco** como práctica del programa de formación en Análisis de Datos.

---

## 📚 Contexto formativo

Este ejercicio forma parte del programa de formación en **Análisis de Datos**, dentro del módulo de herramientas no-code e inteligencia artificial conversacional. El objetivo es comprender el diseño de flujos de conversación, la integración de modelos de lenguaje y el despliegue de chatbots sin código orientados a casos de uso reales de la administración pública.

---

<p align="center">
  <sub>Desarrollado por <a href="https://github.com/migueljerico">@migueljerico</a> · 2026</sub>
</p>
