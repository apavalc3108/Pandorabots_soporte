# 🥋 Hapkido IHA Store – Chatbot de atención al cliente en AIML

**Primer proyecto en Pandorabots · Práctica de clase acotada · AIML 2.0**

Tu tienda de artes marciales favorita… pero en versión chatbot.  
Hapkido IHA Store atiende sin cansarse, te saluda, te enseña el catálogo, te informa de precios, horarios y devoluciones, y recuerda tu nombre.  
**Un dependiente virtual que no duerme y no pide vacaciones.**

---

## 🎯 ¿Por qué existe este proyecto?

Este chatbot fue mi **primer contacto real con Pandorabots**.  
Es una **práctica de clase acotada y dirigida por el profesor**, diseñada para:

- Entender la estructura básica de un bot en AIML.
- Aprender a organizar archivos `.aiml` por funcionalidades.
- Familiarizarse con las sustituciones y el procesamiento de lenguaje natural básico.

Es un proyecto breve y directo: no busca ser un producto comercial, sino **una primera piedra sólida** en el desarrollo de chatbots con reglas. Si estás empezando, aquí tienes un ejemplo funcional en minutos.

---

## 🕹️ ¿Qué puede hacer este chatbot?

- **Saludar** y dar la bienvenida.
- **Preguntar y recordar** tu nombre con variables AIML.
- **Mostrar el catálogo** de productos de artes marciales.
- **Informar de precios, materiales, tallas y disponibilidad.**
- **Indicar el horario** de atención al cliente.
- **Explicar la política de devoluciones.**
- **Responder con cortesía** a mensajes como "gracias".
- **No quedarse en blanco**: si no entiende algo, responde con mensajes por defecto.

---

## 🚀 Cómo ejecutarlo en Pandorabots

1. Crea una cuenta en [Pandorabots](https://www.pandorabots.com).
2. Crea un bot nuevo (el plan gratuito es suficiente).
3. Sube todos los archivos de la carpeta `pavonadrianspotter/`.
4. Compila el bot (`Bot → Compile`).
5. Abre el chat de prueba y escribe `Hola` o `Ver productos`.

---

## 🧠 Funcionamiento del chatbot

El sistema utiliza la sintaxis estándar de **AIML 2.0**. Un ejemplo de su lógica interna:

```xml

    HOLA
    Hola, bienvenido a Hapkido IHA Store.

```

---

## 📂 Estructura del proyecto
```
pavonadriansoporte/
│
├── 📂 aiml/
│   ├── saludos.aiml          # Bienvenida y captura del nombre
│   ├── productos.aiml        # Catálogo general
│   ├── producto1.aiml        # Guantes de Boxeo
│   ├── producto2.aiml        # Dobok Hapkido Master
│   ├── producto3.aiml        # Nunchakus
│   ├── horario.aiml          # Horarios de atención
│   ├── devoluciones.aiml     # Políticas de reembolso
│   ├── respuestas.aiml       # Cortesía y confirmaciones
│   ├── defecto.aiml          # Fallback de errores
│   └── udc.aiml              # Ultimate Default Category
│
├── 📂 config/
│   ├── normal.substitution
│   ├── person.substitution
│   └── gender.substitution
│
└── pavonadriansoporte.properties
```
---

## 💬 Demo de conversación

| Usuario | Bot (Hapkido IHA Store) |
|---------|------------------------|
| Hola | Hola, bienvenido. ¿Cuál es tu nombre? |
| Adrián | Encantado Adrián, ¿en qué puedo ayudarte? |
| Ver productos | Tenemos: Dobok Master, Guantes ProFight y Nunchakus. |
| Guantes | Los guantes ProFight cuestan 36€ y son de alta resistencia. |

---

## 🚀 Próximos pasos y mejoras

Para evolucionar este prototipo hacia un producto comercial, se plantean las siguientes líneas de desarrollo:

- 📦 **Módulo E-commerce:** Integración de un sistema de pedidos real y carrito de compra.
- 🗄️ **Persistencia de datos:** Conexión con bases de datos externas (MySQL/MongoDB) para stock en tiempo real.
- 🌐 **Interfaz Web:** Creación de un frontend personalizado con HTML, CSS y JS consumiendo la API de Pandorabots.
- 🌍 **Soporte Multilingüe:** Implementación de traducciones dinámicas para atender a clientes internacionales.

---

## 👨‍💻 Autor

**Adrián Pavón Alcón**  
Desarrollador del proyecto.

Este bot es el resultado de mi primer contacto con la tecnología AIML 2.0, desarrollado como una práctica académica enfocada en la estructuración de lógica conversacional y la gestión de atención al cliente automatizada.
