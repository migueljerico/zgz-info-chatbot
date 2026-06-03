# Documentación del Chatbot ZGZ Info

## Contexto y Rol

Este documento detalla el chatbot **ZGZ Info**, un asistente virtual desarrollado en la plataforma Landbot para el Ayuntamiento de Zaragoza. Su propósito principal es ofrecer información rápida y accesible sobre los servicios de transporte público de la ciudad, actuando como un punto de contacto inicial para los ciudadanos que buscan datos sobre autobuses, tranvías, bicicletas y cercanías.

## Consulta/Tarea

La tarea consiste en documentar de manera profesional y exhaustiva las características, funcionalidades y el flujo de interacción del chatbot ZGZ Info, para su publicación en un repositorio de GitHub. El objetivo es proporcionar una visión clara de su operación y capacidades.

## Especificaciones

El chatbot ha sido diseñado para:

*   **Asistencia en Transporte Público:** Proporcionar detalles sobre líneas, horarios, frecuencias y métodos de pago (tarjeta bus).
*   **Interacción Guiada:** Ofrecer opciones predefinidas para facilitar la navegación del usuario.
*   **Procesamiento de Lenguaje Natural (PLN) Básico:** Interpretar preguntas de texto libre para ofrecer respuestas más específicas, como se observó al preguntar por el horario de una línea de autobús específica.
*   **Clarificación de Consultas:** Solicitar información adicional al usuario para refinar la búsqueda y ofrecer datos precisos.

## Detalles Técnicos y de Implementación

### Equipo de Desarrollo

El chatbot fue desarrollado por el equipo compuesto por Mayelin, Miguel y Francisco.

### Prompt de Sistema (Landbot - Bloque AI / GPT)

El prompt utilizado para configurar el comportamiento del chatbot es el siguiente:

> Eres "ZGZ Info", asistente virtual del Ayuntamiento de Zaragoza. Tu función es dar información municipal clara, oficial y útil a la ciudadanía.

### Ámbitos de Información Cubiertos

El chatbot está diseñado para proporcionar información dentro de los siguientes ámbitos:

*   **Trámites:** Empadronamiento, tasas, licencias.
*   **Transporte:** Autobús urbano, tranvía, Bizi (bicicleta pública).
*   **Cultura y Turismo:** Basílica del Pilar, La Seo, Aljafería, fiestas del Pilar.
*   **Otros:** Deportes, medioambiente, atención social y avisos municipales.

### Reglas de Interacción del Chatbot

Para asegurar una interacción efectiva y precisa, el chatbot sigue las siguientes reglas:

*   Responde solo sobre Zaragoza. Si se pregunta sobre otra ciudad o tema ajeno, reconduce amablemente la conversación.
*   Mantiene un tono cercano, profesional y conciso, con respuestas de un máximo de 4-5 frases.
*   Si no dispone del dato exacto, lo indica y deriva al 010 (atención ciudadana) o a zaragoza.es.
*   Evita inventar horarios, precios o teléfonos; en caso de duda, recomienda verificar la información en la web oficial.
*   Saluda al inicio de la conversación y pregunta en qué puede ayudar.

### Protocolo de Pruebas

El proceso de pruebas incluyó:

*   Un recorrido exhaustivo de todos los caminos y ramas del constructor (builder).
*   La inclusión de datos 100% reales para garantizar la credibilidad institucional (ej. Precio Bizi, teléfono 010).
*   Verificación de enlaces reales comprobados en entorno de producción.

### Ejemplo de Despliegue

El chatbot se integra con la red de autobús urbano, tranvía (línea 1) y bicicleta pública Bizi. Permite la consulta de horarios en tuzsa.es o en la aplicación Zaragoza Móvil.

## Criterios de Calidad

La documentación debe ser:

*   **Profesional:** Redactada con un tono formal y técnico adecuado para un entorno corporativo.
*   **Clara y Estructurada:** Fácil de entender, con secciones bien definidas y un flujo lógico.
*   **Completa:** Cubrir todos los aspectos relevantes del chatbot, desde su propósito hasta su interacción.
*   **Formato Markdown:** Utilizar la sintaxis Markdown para asegurar la compatibilidad y legibilidad en GitHub.

## Cómo se presentará la respuesta

La respuesta se presentará como un archivo `README.md` en un repositorio de GitHub. Este archivo contendrá la documentación completa del chatbot, incluyendo una descripción detallada de su funcionamiento, ejemplos de interacción y las capacidades de IA observadas.

## Verificación

La verificación se realizará mediante la revisión del archivo `README.md` en el repositorio de GitHub, asegurando que cumple con todos los criterios de calidad y especificaciones establecidas.
