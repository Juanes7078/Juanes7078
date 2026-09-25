<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,19,25,32&height=200&section=header&text=Juan%20Esteban%20%7C%20JuanesBy08&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%26%20Systems%20Architect&descAlignY=62&descAlign=50" width="100%" alt="Header Banner" />
</div>

<div align="center">
  <a href="https://github.com/Juanes7078">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1200&color=38BDF8&center=true&vCenter=true&width=650&lines=Software+Engineer+%26+Systems+Architect;High-Concurrency+%26+Distributed+Systems;Cloud+Cost+Optimization+(-85%25+Telemetry);Off-Main-Thread+Computing+(60+FPS+Engines);Multiplatform+PWA+%26+Native+Android+Architect" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Juanes7078&label=Profile%20Views&color=38bdf8&style=flat-square" alt="Profile Views" />
  <a href="mailto:esteban.chaparro0211@gmail.com">
    <img src="https://img.shields.io/badge/Email-esteban.chaparro0211%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/Juanes7078">
    <img src="https://img.shields.io/badge/GitHub-Juanes7078-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com">
    <img src="https://img.shields.io/badge/LinkedIn-Juan_Esteban-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <img src="https://img.shields.io/badge/Location-Boyacá%2C_Colombia-4c1?style=flat-square" alt="Location" />
</div>

---

## 👨‍💻 Perfil Profesional

Ingeniero de software enfocado en la concepción, diseño e implementación de sistemas distribuidos, arquitecturas en la nube de alta disponibilidad y bajo costo operativo (*FinOps*), y experiencias de usuario de alto rendimiento. Especializado en orquestación serverless, optimización extrema del hilo principal (*Off-Main-Thread Computing*) y desarrollo multiplataforma (Web PWA, microservicios y móvil nativo).

### 💡 Principales Logros de Ingeniería:
- **Optimización de Costos en la Nube (-85%):** Rediseño arquitectónico de telemetría IoT mediante desacoplamiento a Realtime Database y algoritmos de *throttling* espaciotemporal (Haversine $\ge 15\text{m}$, tiempo $\ge 8\text{s}$).
- **Rendimiento a 60 FPS Constantes:** Implementación de motores de cálculo asíncronos en Web Workers y decodificación binaria en cliente (`DataView`) para eliminar bloqueos de interfaz (*Zero Frame Drops*).
- **Cero Costo de Renderizado Gráfico ($0 Cloud Compute):** Migración de pipelines pesados de servidor (Puppeteer/Chromium) hacia motores gráficos client-side en Canvas 2D a **300 DPI** reales listos para imprenta.
- **Aislamiento Multitenant & Seguridad:** Diseño de esquemas de datos aislados por inquilino (*shop isolation*), autenticación criptográfica mediante JWT Custom Claims y modelos de control de acceso basados en roles (RBAC).

---

## 🚀 Estudios de Caso Técnico (Engineering Case Studies)

Los siguientes repositorios documentan la arquitectura, diseño de sistemas, diagramas de flujo y soluciones de ingeniería de proyectos reales en producción:

| Proyecto | Tipo de Sistema & Desafío | Tecnologías Clave | Showcase Técnico |
| :--- | :--- | :--- | :---: |
| **🚌 SOLIBUS** | **Plataforma IoT & Transporte Colectivo en Tiempo Real**<br/>Monitoreo de flotas con telemetría GPS continua, motor de ruteo asíncrono a 60 FPS y reducción del 85% en costos de base de datos. | Firebase RTDB / Firestore, Web Workers, Capacitor, Google Maps API, PWA | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/solibus-transit-system) |
| **🎓 ÉDUCATIF** | **Plataforma Web PWA para Gestión Académica & Comunidad**<br/>Arquitectura Serverless Event-Driven (14 Cloud Functions en Node 22), motor de horarios dinámicos, gamificación de rachas y ciberseguridad proactiva. | Node.js 22, Firebase Cloud Functions, Firestore, Tailwind CSS v4, PWA | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/educatif-platform-showcase) |
| **✂️ PAPERCRAFT 3D** | **Visor & Desplegador WebGL de Modelos 3D y Pepakura**<br/>Decodificación binaria en cliente de archivos `.pdo` con `DataView`, renderizado Three.js a 60 FPS, sincronización 3D/2D y Screen Wake Lock API. | React 19, Three.js, WebGL, Zustand 5, PDF.js, Vite 8 | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/papercraft-studio-showcase) |
| **🎵 SPOTIFY CARD GEN** | **Generador Visual Serverless de Alta Resolución**<br/>Motor gráfico Canvas 2D a 300 DPI reales, microservicio serverless de integración Spotify OAuth con auto-renew y cuotas atómicas en Redis KV. | Node.js, Express, Vercel Serverless KV, HTML5 Canvas, Cropper.js, JSZip | [**Ver Estudio Técnico ↗**](https://github.com/Juanes7078/spotify-card-generator-showcase) |
| **🏢 DISTRIFY** | **ERP SaaS Multitenant para Gestión Empresarial**<br/>Plataforma comercial con aislamiento por tenant, pasarela de pagos con webhooks y asistencia empresarial con IA. | NestJS, TypeScript, MongoDB, Vue 3, Pinia, PrimeVue, Mercado Pago | *En preparación* |
| **📸 MEMORIS** | **Aplicación Móvil Android Nativa de Fotografía**<br/>Captura con CameraX, motor personalizado de filtros (`FilterEngine`), base de datos local Room SQLite y arquitectura reactiva MVVM. | Android Nativo, Kotlin, Jetpack Compose, CameraX, Room SQLite, Coroutines | *En preparación* |
| **🍳 FOGÓN POS** | **Punto de Venta & Sistema de Cocina (KDS) en Tiempo Real**<br/>Sincronización instantánea de comandas mesero/cocina, control de stock y balances de caja. | JavaScript Moderno, Firebase Firestore, Chart.js, PWA | *En preparación* |

> 🔒 **Nota sobre Confidencialidad y Propiedad Intelectual:**  
> Por motivos comerciales y derechos de propiedad intelectual, el código fuente completo ejecutable de mis proyectos reside en repositorios privados de desarrollo. Los enlaces anteriores dirigen a **estudios de arquitectura y portafolios técnicos públicos**, donde se exponen diagramas, métricas, mitigaciones de seguridad y decisiones de diseño.

---

## 🛠️ Stack Tecnológico & Especialidades

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,vue,react,nodejs,nestjs,express,kotlin,android,firebase,mongodb,sqlite,redis,tailwind,threejs,vite,docker,git,postman,figma&perline=10" alt="Tech Stack Icons" />
</div>

<br/>

| Dominio | Tecnologías & Herramientas |
| :--- | :--- |
| **Frontend & Web Graphics** | TypeScript • JavaScript (ES6+) • Vue 3 • React 19 • HTML5 Canvas 2D • Three.js (WebGL) • Tailwind CSS • Vite |
| **Backend & Cloud Serverless** | Node.js • NestJS • Express • Firebase Cloud Functions • Vercel Serverless Functions • RESTful APIs • WebSockets |
| **Mobile & Cross-Platform** | Android Nativo (Kotlin & Jetpack Compose) • Capacitor • CameraX • Progressive Web Apps (PWA) • Service Workers |
| **Bases de Datos & Almacenamiento** | Cloud Firestore • Firebase Realtime Database • MongoDB (Mongoose) • SQLite (Room) • Redis (Vercel KV) |
| **Arquitectura & DevOps** | Git & GitHub • RBAC con JWT Custom Claims • Web Workers (*Off-Main-Thread*) • Docker • CI/CD Pipelines |

---

## 📊 Actividad & Métricas en Vivo

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Juanes7078&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Juanes7078&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8" height="150" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Juanes7078&theme=tokyonight&hide_border=true&background=0d1117&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=94a3b8" alt="Streak Stats" />
</div>

---

## 🏛️ Principios de Arquitectura e Ingeniería

- **Separación de Responsabilidades & Clean Architecture:** Desacoplamiento explícito entre reglas de negocio, persistencia e interfaces de presentación.
- **Defensa en Profundidad & Zero-Trust:** Validación exhaustiva en frontend y backend, reglas de seguridad declarativas inmutables en base de datos y sanitización XSS.
- **Rendimiento Orientado a Recursos Limitados:** Soluciones optimizadas para operar con fluidez incluso en dispositivos de gama media y redes móviles con latencia variable.
- **Ingeniería Basada en Métricas (FinOps):** Elección de bases de datos y patrones serverless basada en análisis riguroso de costo por operación vs. costo por ancho de banda.

---

## 📬 Contacto Profesional

¿Interesado en conversar sobre arquitectura de sistemas, oportunidades de ingeniería o proyectos de alto impacto?

- 💼 **LinkedIn:** [linkedin.com/in/tu-perfil](https://linkedin.com) *(Actualiza con tu URL)*
- ✉️ **Correo Directo:** [esteban.chaparro0211@gmail.com](mailto:esteban.chaparro0211@gmail.com)
- 📍 **Ubicación:** Boyacá, Colombia (Disponible para trabajo remoto / híbrido global)

---

<div align="center">
  <sub>Diseñado con dedicación y estándares de alta ingeniería • © 2026 Juan Esteban (JuanesBy08)</sub>
</div>
