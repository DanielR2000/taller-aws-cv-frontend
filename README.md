# ☁️ AWS Serverless CV - Práctica Final

Este repositorio contiene el código fuente y la documentación gráfica del despliegue de un currículum web estático en la nube de AWS. Es el proyecto final desarrollado para el taller de microservicios y nube de la Universidad Politécnica de Madrid y Next Digital.

## 🏗️ Arquitectura del Proyecto

El proyecto implementa una arquitectura *serverless* segura y de alta disponibilidad:

1. **Amazon S3:** Almacenamiento seguro de los activos estáticos (HTML y CSS) con el acceso público bloqueado por defecto.
2. **Amazon CloudFront:** Red de Entrega de Contenido (CDN) configurada con OAC (Origin Access Control) para servir la web a nivel global con baja latencia y forzando la redirección a HTTPS.
3. **Amazon Cognito (Opcional implementado):** Gestión de identidades mediante Hosted UI para proteger el acceso al currículum real, requiriendo autenticación previa en la página de inicio.

## 📁 Estructura del repositorio

* `index.html`: Landing page pública con el botón de inicio de sesión.
* `cv.html`: Página protegida que contiene el currículum.
* `style.css`: Hoja de estilos compartida.
* `entregable_aws.pdf`: Documento con las capturas de pantalla de la infraestructura desplegada y funcionando.

## 🚀 Tecnologías utilizadas

* **Frontend:** HTML5, CSS3.
* **AWS Cloud:** S3, CloudFront, Cognito, IAM.

---
*Desarrollado por Daniel Reinosa Corps - 2026*