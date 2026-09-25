# Hola, soy Juan Esteban (JuanesBy08) 👋
### Software Engineer & Systems Architect
*Especializado en diseño de sistemas escalables, alta concurrencia, arquitecturas serverless y desarrollo multiplataforma.*

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan_Esteban-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Juanes7078-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Juanes7078)
[![Email](https://img.shields.io/badge/Email-esteban.chaparro0211%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:esteban.chaparro0211@gmail.com)
[![Architecture](https://img.shields.io/badge/Focus-High_Concurrency_%26_Systems_Design-blue?style=flat-square)](#-arquitectura--principios-de-ingeniería)

---

## 👨‍💻 Perfil Profesional

Ingeniero de software enfocado en la concepción, diseño e implementación de sistemas robustos, arquitecturas en la nube de bajo costo operativo y experiencias de usuario de alto rendimiento. Con experiencia liderando proyectos desde la formulación del modelo de datos y la orquestación serverless hasta el empaquetado móvil y la optimización extrema del hilo principal (*Off-Main-Thread Computing*).

### 💡 Principales Logros de Ingeniería:
- **Optimización de Costos en la Nube (-85%):** Rediseño arquitectónico de telemetría IoT mediante desacoplamiento a Realtime Database y algoritmos de *throttling* espaciotemporal (Haversine).
- **Rendimiento a 60 FPS Constantes:** Implementación de motores de cálculo asíncronos en Web Workers para eliminar el bloqueo del hilo de interfaz (*Zero Frame Drops*).
- **Aislamiento Multitenant & Seguridad:** Diseño de esquemas de datos aislados por inquilino (*shop isolation*), autenticación criptográfica mediante JWT Custom Claims y modelos de acceso basados en roles (RBAC).

---

## 🚀 Proyectos Destacados (Engineering Case Studies)

A continuación se presentan los estudios de caso técnico de sistemas diseñados y construidos para resolver desafíos reales de escalabilidad y negocio:

| Proyecto | Tipo de Sistema & Desafío | Tecnologías Clave | Showcase Técnico |
| :--- | :--- | :--- | :---: |
| **🚌 SOLIBUS** | **Plataforma IoT & Transporte Colectivo en Tiempo Real**<br/>Monitoreo de flotas urbanas con telemetría GPS continua, motor de ruteo asíncrono a 60 FPS y reducción del 85% en costos de base de datos. | Firebase RTDB / Firestore, Web Workers, Capacitor, Google Maps API, PWA | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/solibus-transit-system) |
| **🎓 ÉDUCATIF** | **Plataforma Web PWA para Gestión Académica & Comunidad**<br/>Arquitectura Serverless Event-Driven (14 Cloud Functions en Node 22), motor de horarios dinámicos, gamificación de rachas y ciberseguridad proactiva (anti-bot y detección de IP). | Node.js 22, Firebase Cloud Functions, Firestore, Tailwind CSS v4, PWA | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/educatif-platform-showcase) |
| **✂️ PAPERCRAFT 3D** | **Visor & Desplegador WebGL de Modelos 3D y Pepakura**<br/>Decodificación binaria en cliente de archivos `.pdo` con `DataView`, renderizado Three.js a 60 FPS, sincronización espacial 3D/2D y Screen Wake Lock API. | React 19, Three.js, WebGL, Zustand 5, PDF.js, Vite 8 | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/papercraft-studio-showcase) |
| **🏢 DISTRIFY** | **ERP SaaS Multitenant para Gestión Empresarial**<br/>Plataforma comercial completa (ventas, stock, compras, caja y reportes) con aislamiento por tenant, pasarela de pagos y asistencia con IA. | NestJS, TypeScript, MongoDB, Vue 3, Pinia, PrimeVue, Mercado Pago | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/distrify-erp-showcase) |
| **📸 MEMORIS** | **Aplicación Móvil Android Nativa de Fotografía**<br/>Captura con CameraX, motor personalizado de filtros en tiempo real (`FilterEngine`), base de datos local Room SQLite y arquitectura reactiva MVVM. | Android Nativo, Kotlin, Jetpack Compose, CameraX, Room SQLite, Coroutines | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/memoris-camera-showcase) |
| **🎵 SPOTIFY CARD GEN** | **Generador Visual Serverless de Alta Resolución**<br/>Microservicio en la nube para renderizado gráfico sobre Canvas, manipulación vectorial, rate-limiting con Redis serverless y compresión ZIP. | Node.js, Express, Vercel Serverless KV, HTML5 Canvas, Cropper.js, JSZip | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/spotify-card-generator-showcase) |
| **🍳 FOGÓN POS** | **Punto de Venta & Sistema de Cocina (KDS) en Tiempo Real**<br/>Sincronización instantánea de comandas entre meseros y cocina, control reactivo de inventario y balances financieros para restaurantes. | JavaScript Moderno, Firebase Firestore, Chart.js, Progressive Web App | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/fogon-restaurant-pos-showcase) |

> 🔒 **Nota sobre el Código Fuente y Confidencialidad:**  
> Debido a acuerdos operativos, valor de negocio y derechos de propiedad intelectual, el código fuente completo ejecutable de mis proyectos comerciales se aloja en repositorios privados de desarrollo.  
> Los enlaces anteriores dirigen a **estudios de arquitectura y portafolios técnicos públicos**, donde documento a profundidad las decisiones técnicas, diagramas de flujo, mitigaciones de seguridad y métricas cuantitativas logradas.

---

## 🛠️ Stack Tecnológico & Especialidades

```
┌────────────────────────────────────────────────────────────────────────┐
│  CAPA DE CLIENTE & FRONTEND                                            │
│  JavaScript (ES6+) • TypeScript • Vue 3 • HTML5 Semántico • CSS3       │
│  Tailwind CSS • Progressive Web Apps (PWA) • Service & Web Workers     │
├────────────────────────────────────────────────────────────────────────┤
│  ARQUITECTURA BACKEND & CLOUD                                          │
│  Node.js • NestJS • Express • Firebase Cloud Functions (Serverless)   │
│  RESTful APIs • WebSockets • Vercel Serverless Functions • Cron Jobs   │
├────────────────────────────────────────────────────────────────────────┤
│  DESARROLLO MÓVIL                                                      │
│  Android Nativo (Kotlin & Jetpack Compose) • Capacitor (Cross-Platform)│
│  CameraX • MVVM con StateFlow & Corrutinas                            │
├────────────────────────────────────────────────────────────────────────┤
│  BASES DE DATOS & ALMACENAMIENTO                                       │
│  Cloud Firestore • Firebase Realtime Database • MongoDB (Mongoose)     │
│  SQLite (Room Database) • Vercel KV (Redis) • Cloud Storage            │
├────────────────────────────────────────────────────────────────────────┤
│  SEGURIDAD, DEVOPS & CALIDAD                                           │
│  Git & GitHub • RBAC con Custom Claims JWT • Content Security Policy   │
│  Pruebas Unitarias (node:test) • Terser Minification • CI/CD Pipelines│
└────────────────────────────────────────────────────────────────────────┘
```

---

## 🏛️ Arquitectura & Principios de Ingeniería

En cada desarrollo aplico estándares rigurosos de ingeniería de software:
- **Clean Architecture & Separación de Intereses:** Fronteras claras entre lógica de negocio, persistencia e interfaces de usuario.
- **Defensa en Profundidad:** Validación estricta en el cliente, sanitización contra ataques XSS y reglas declarativas inmutables en base de datos.
- **Rendimiento Orientado a Recursos Limitados:** Diseños optimizados para operar con baja huella de memoria y ancho de banda restringido en redes móviles reales.
- **Decisiones Basadas en Métricas:** Elección de motores de datos evaluando costos por operación vs. costos por transferencia.

---

## 📬 Contacto y Redes Profesionales

¿Interesado en conversar sobre arquitectura de software, oportunidades de ingeniería o proyectos de alto impacto?

- 💼 **LinkedIn:** [linkedin.com/in/tu-perfil](https://linkedin.com) *(Actualiza con tu URL)*
- ✉️ **Correo Directo:** [esteban.chaparro0211@gmail.com](mailto:esteban.chaparro0211@gmail.com)
- 📍 **Ubicación:** Boyacá, Colombia (Disponible para trabajo remoto / híbrido)

---

<div align="center">
  <sub>Diseñado con dedicación y estándares de alta ingeniería • © 2026 Juan Esteban (JuanesBy08)</sub>
</div>
