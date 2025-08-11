# Programa de Entrenamiento – App Generative

Un recorrido práctico para llevar una idea desde cero hasta un despliegue productivo en la nube, integrando inteligencia artificial y siguiendo buenas prácticas de desarrollo moderno.

---

## Requerimientos del Curso

- **Conocimientos previos**:  
  - Fundamentos de programación (Python preferido).  
  - Nociones básicas de HTTP y APIs.  
  - Familiaridad con la línea de comandos GNU/Linux.  

- **Herramientas necesarias**:  
  - Cuenta en **Google Cloud Platform (GCP)** con acceso a Vertex AI.  
  - Cuenta en **GitHub**.  
  - **Git** instalado.  
  - **Docker** y **docker-compose** instalados.  
  - Editor de código (VS Code recomendado).
  - Tener VMWare o maquina virtual con S.O GNU/Linux.

- **Otros**:  
  - Conexión a internet estable.  
  - Claves de API necesarias para integraciones.  

---

## 🗓 Semana 1 – Fundamentos y Control de Versiones

**Objetivo:** Construir una base sólida para desarrollar como un profesional: control de accesos, versionado de código y entornos portables.

1. **Bienvenida y Contexto Tecnológico**  
   - Introducción al curso.  
   - Rol de la IA generativa en el mundo actual.  
   - Ejemplos de uso en la industria.  
   - Cómo encaja en arquitecturas modernas de nube.  

2. **Seguridad y Control de Accesos (IAM en GCP)**  
   - Concepto de IAM.  
   - Diferencias entre usuarios, roles y cuentas de servicio.  
   - Creación y gestión de identidades.  
   - Aplicación de políticas de mínimo privilegio.  
   - Prevención de riesgos de seguridad mediante segmentación de permisos.
   - Implementanción de Terraform en la administración de roles de IAM en GCP.

3. **Control de Versiones con Git & GitHub**  
   - Concepto de control de versiones.  
   - Comandos esenciales (`git add`, `git commit`, `git push`, `git pull`, `branch`, `merge`).  
   - Flujo de trabajo con ramas.  
   - Uso de pull requests.
   - Resolución de conflictos.
   - Buenas prácticas de commit.

4. **Entornos Consistentes con Docker**  
   - Qué es un contenedor y sus ventajas para portabilidad.  
   - Creación de un `Dockerfile` desde cero.  
   - Gestión de imágenes y contenedores.
   - Técnicas de seguridad en las plantillas de Dockerfile.
   - Uso de `docker-compose` para aplicaciones con múltiples servicios.  
   - Ejemplo práctico: app + base de datos. 

---

## 🛠 Semana 2 – Diseño y Desarrollo de APIs

**Objetivo:** Diseñar y construir APIs sólidas, bien estructuradas y listas para integrarse con cualquier servicio.

1. **Fundamentos REST**  
   - Qué es un servicio web.  
   - Diferencias entre REST y SOAP.  
   - Verbos HTTP (`GET`, `POST`, `PUT`, `DELETE`) y su uso.  
   - Códigos de estado y su significado.  
   - Buenas prácticas en nombrado de rutas.  

2. **Arquitectura Web Moderna**  
   - Concepto de arquitectura cliente-servidor.  
   - Separación de responsabilidades entre front-end y back-end.  
   - Capa de controladores, servicios y datos.  
   - Ejemplos de arquitectura escalable.  

3. **Taller Práctico**  
   - Instalación y configuración de Flask/FastAPI.  
   - Creación de rutas y manejo de peticiones.  
   - Uso de parámetros y query strings.  
   - Validación de datos.  
   - Respuestas personalizadas.
   - Manejo correcto de Logs para la observabilidad.
   - Ejemplo: API para un catálogo de productos.  

---

## 🤖 Semana 3 – IA y Automatización CI/CD

**Objetivo:** Integrar IA en tu aplicación y automatizar el flujo de desarrollo y despliegue.

1. **IA con Gemini en Vertex AI**  
   - Presentación de Vertex AI y modelos Gemini.  
   - Instalación y uso del SDK.  
   - Ejemplos de integración en Python.  
   - Manejo de autenticación con claves seguras.  
   - Gestión de errores y excepciones.  

2. **CI/CD para Desarrolladores Ágiles (GitHub Actions)**  
   - Conceptos de integración y entrega continua.  
   - Ventajas para el desarrollo ágil.  
   - Creación de workflows con GitHub Actions.  
   - Configuración de pipelines `.yml`.  
   - Ejecución de pruebas automáticas.  
   - Construcción y despliegue de imágenes Docker.  

---

## 🌐 Semana 4 – Despliegue, Monitoreo y Producción

**Objetivo:** Llevar tu aplicación al mundo real, lista para escalar y ser monitoreada en todo momento.

1. **Herramientas de Despliegue en GCP**  
   - Introducción a Cloud Run y ventajas del modelo serverless.  
   - Configuración de un servicio en Cloud Run.  
   - Uso de Cloud Build para automatizar construcción de imágenes.  
   - Publicación en Container Registry.  
   - GitHub Actions.  

2. **Lanzamiento a Producción**  
   - Proceso paso a paso para desplegar una aplicación.  
   - Integración de Cloud Build con Cloud Run.  
   - Configuración de variables de entorno.  
   - Acceso seguro a través de URL pública.  
   - Estrategias de despliegue sin interrupciones.  

3. **Monitoreo y Observabilidad**  
   - Uso de Cloud Logging para ver registros en tiempo real.  
   - Búsqueda y filtrado de logs.  
   - Creación de paneles en Cloud Monitoring.  
   - Configuración de métricas personalizadas.  
   - Alertas automáticas para fallos y problemas de rendimiento.  

---

✅ **Resultado esperado:** Al final del curso tendrás una aplicación con IA generativa desplegada en la nube, con un pipeline CI/CD automatizado y buenas prácticas de seguridad y monitoreo.
