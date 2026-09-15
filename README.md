# 📱 Proyecto Urban Lunch - Pruebas de Aplicaciones Móviles

## 📌 Título del Proyecto
**Pruebas Funcionales y de Calidad QA en Aplicación Móvil Urban Lunch | Bootcamp Tripleten (2026)**

---

## 📝 Descripción General del Proyecto
Este proyecto está centrado en la ejecución del ciclo completo de pruebas QA para la aplicación móvil de delivery de comida **Urban Lunch**. El trabajo abarca desde el análisis exhaustivo de requisitos y la creación de listas de comprobación (checklists), hasta la ejecución de pruebas funcionales, pruebas de UI/UX, verificación de APIs backend y pruebas de regresión. Se identificaron y reportaron defectos de diseño y funcionalidad con el objetivo de asegurar una experiencia fluida, estable y libre de errores antes de su lanzamiento.

---

## 🎯 Objetivos
* 📌 **Garantizar la Calidad del Software:** Verificar que la aplicación móvil cumpla estrictamente con las especificaciones y requisitos del negocio.
* 📌 **Validar el Flujo de Compra:** Comprobar la experiencia completa del usuario desde la selección de puntos de recogida hasta el seguimiento y entrega del pedido.
* 📌 **Identificar y Documentar Defectos:** Detectar bugs visuales, lógicos y de integración, reportándolos detalladamente en JIRA.
* 📌 **Verificar Endpoints y Backend:** Realizar pruebas de API en las integraciones móviles para validar el correcto procesamiento de la información.

---

## 📐 Alcance de las Pruebas
La auditoría de calidad cubre los módulos principales del flujo operativo de **Urban Lunch**:

* 📍 **Puntos de Recogida:** Selección y geolocalización de las sedes o puntos de entrega.
* 🍽️ **Elección de Platillos:** Navegación por el menú, personalización de platillos, selección de cantidades y adición al carrito.
* 💳 **Confirmación del Pedido:** Validación del resumen de compra, métodos de pago y datos del usuario.
* 🛵 **Envío y Seguimiento:** Evaluación del estado del pedido en tiempo real, pantalla de rastreo y notificación de recogida.
* 📐 **Validación de Formularios y Campos:** Pruebas de valores límite (BVA) y clases de equivalencia (EP) en los campos de entrada de datos.

---

## 🧪 Estrategia de Pruebas
La estrategia aplicada incluye actividades manuales y de análisis técnico:

1. 📑 **Análisis de Requisitos y Diseño de Checklist:** Revisión detallada de las historias de usuario para estructurar listas de comprobación y casos de prueba.
2. 📱 **Ejecución de Pruebas Manuales y UI:** Instalación y emulación de la app en **Android Studio** para testear componentes interactivos e interfaces.
3. 🔗 **Validación de APIs (Backend):** Inspección de peticiones HTTP en **Postman** para confirmar que la respuesta del servidor coincida con la UI.
4. 🐞 **Gestión de Defectos:** Documentación completa de los hallazgos en **JIRA**, clasificando severidad y prioridad con los pasos para reproducir el fallo.
5. 🔄 **Pruebas de Regresión:** Re-verificación de la aplicación tras la corrección de errores para asegurar la estabilidad global.

---

## 🔬 Tipos de Pruebas
* 📱 **Pruebas de Aplicaciones Móviles (Mobile Testing):** Evaluación del comportamiento en dispositivos emulados bajo entorno Android.
* 🧪 **Pruebas Funcionales:** Comprobación del correcto funcionamiento de cada elemento y pantalla de la app.
* 🎨 **Pruebas de Interfaz de Usuario (UI/UX Testing):** Identificación de inconsistencias de diseño, alineación y navegabilidad.
* 🔗 **Pruebas de API y Endpoints:** Verificación de las solicitudes HTTP enviadas y recibidas durante la gestión del pedido.
* ⚠️ **Pruebas de Clases de Equivalencia y Valores Límite:** Validación de límites permitidos en formularios y selección de productos.
* 🔄 **Pruebas de Regresión:** Confirmación de la estabilidad del sistema tras los ciclos de corrección de bugs.

---

## 🛠️ Herramientas y Tecnologías
* 📱 **Emulador Móvil:** Android Studio
* 🔗 **Verificación de APIs:** Postman
* 🐞 **Gestión de Defectos y Tareas:** JIRA
* 📊 **Diseño de Casos de Prueba y Checklists:** Google Sheets / Microsoft Excel

---

## 📋 Casos de Prueba
Se diseñaron e implementaron más de **50 casos de prueba** para verificar los módulos clave:

| ID Caso | Módulo / Funcionalidad | Herramienta | Resultado Esperado |
| :--- | :--- | :--- | :--- |
| **TC-MOB-01** | Selección del punto de recogida | Android Studio | La app permite ubicar y seleccionar una sede disponible correctamente. |
| **TC-MOB-02** | Adición y personalización de platillos | Android Studio | El platillo se agrega al carrito con sus ingredientes y opciones seleccionadas. |
| **TC-MOB-03** | Aplicación de límites en la cantidad de platillos | Android Studio / Sheets | El campo no permite números negativos ni exceder el máximo permitido. |
| **TC-MOB-04** | Confirmación y procesamiento del pedido | Android Studio | El pedido se procesa y se genera el resumen de pago de forma precisa. |
| **TC-MOB-05** | Pantalla de seguimiento y rastreo | Android Studio | La pantalla refleja el estado del envío y los tiempos de recogida en tiempo real. |
| **TC-MOB-06** | Validación de respuesta API en el pedido | Postman | El servidor responde con código `200 OK` y el payload con los datos correctos. |

---

## 🐛 Reporte de Defectos
Durante las sesiones de prueba se detectaron e ingresaron más de **50 reportes de error en JIRA**:

* 🚨 **Errores Lógicos en Funcionalidades:** Inconsistencias al agregar múltiples productos o actualizar la cantidad en el carrito.
* ⚠️ **Defectos de UI / Diseño:** Problemas de alineación de texto, botones desproporcionados y solapamiento de elementos visuales en pantalla.
* 📝 **Errores en Campos de Texto:** Aceptación de datos inválidos en formularios de dirección y datos de contacto.

---

## 📊 Resultados y Métricas
* 🧪 **Casos de Prueba Diseñados:** +50 casos de prueba ejecutados y documentados.
* 🐞 **Reportes de Incidencias:** +50 bugs registrados en JIRA con prioridad y severidad categorizadas.
* 📋 **Listas de Comprobación:** Checklists detalladas creadas para cubrir todos los flujos de la app.
* ✅ **Impacto del Proyecto:** Calidad del software optimizada, permitiendo la entrega de una versión móvil estable, funcional y lista para producción.

---

## 📂 Evidencias
* 📊 **Casos de Prueba y Checklists del Proyecto:** [Ver Documentación en Google Sheets](https://docs.google.com/spreadsheets/d/1E-i89E5WQJcPMDyH1eCDPE6ALmv8bU6H/edit?usp=sharing&ouid=117662769631159222767&rtpof=true&sd=true)

---

## 📁 Estructura del Repositorio
```text
urban-lunch-mobile-testing/
├── test-cases/
│   ├── checklist_urban_lunch.xlsx # Lista de comprobación de la app móvil
│   └── test_cases_suite.xlsx     # Casos de prueba detallados (BVA y EP)
├── bug-reports/
│   └── jira_bugs_export.csv      # Exportación de reporte de defectos en JIRA
├── docs/
│   └── requirements_analysis.pdf # Documento de análisis de requisitos
└── README.md                     # Documentación general del proyecto
```

---

## 💡 Principales Aprendizajes
* 📱 **Pruebas de Aplicaciones Móviles:** Dominio del flujo de instalación, emulación y pruebas de interfaz en dispositivos Android mediante Android Studio.
* 📊 **Técnicas de Diseño de Pruebas:** Aplicación práctica de Clases de Equivalencia (EP) y Análisis de Valores Límite (BVA) en un entorno mobile.
* 🐞 **Gestión Profesional de Incidencias:** Redacción detallada de reportes de error en JIRA incluyendo pasos para reproducir, resultados esperados y adjuntos.
* 🔗 **Validación Integrada Backend-Frontend:** Uso de Postman para contrastar la respuesta de las APIs con el comportamiento visual de la app.

---

## 🚀 Mejoras Futuras
* 🤖 **Automatización Móvil:** Implementar scripts de prueba automatizados utilizando Appium y Python.
* 🌐 **Pruebas Cross-Platform:** Ampliar el alcance de las pruebas para verificar la aplicación en dispositivos con iOS.
* ⚡ **Pruebas de Rendimiento Móvil:** Evaluar el consumo de batería, memoria RAM y comportamiento ante conexiones lentas (3G/4G/5G).
