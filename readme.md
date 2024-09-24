# SMTP Extractor v1.0: Guía Rápida

**SMTP Extractor v1.0** es una herramienta diseñada para automatizar la búsqueda de servidores SMTP vulnerables y la extracción de credenciales sensibles. A continuación, te presentamos una guía paso a paso para usar el software correctamente.

## 1. Instalación de Dependencias
- Asegúrate de tener **Node.js** instalado.
- Navega al directorio del proyecto.
- Ejecuta el comando `npm install` para instalar los paquetes necesarios.

## 2. Selección de un Dork
El software te ofrece **consultas de búsqueda predefinidas** (conocidas como dorks) que permiten encontrar servidores vulnerables con información SMTP sensible.

- Puedes elegir entre las opciones proporcionadas o **ingresar un dork personalizado** según tus necesidades.

## 3. Bypass del servicio reCaptcha
La herramienta está equipada con un módulo que **automatiza las búsquedas en Google** y gestiona los desafíos de reCaptcha, permitiendo una recopilación fluida de información.

## 4. Extracción de URLs
El software **recopila todas las URLs** de los resultados de búsqueda que puedan contener información sensible.

- Se navega de manera inteligente a través de las páginas de resultados para **obtener la mayor cantidad de URLs posibles**.

## 5. Procesamiento de la Información SMTP
Cada URL recopilada se verifica para detectar posibles credenciales SMTP.

- Si se encuentran credenciales válidas, se **extraen y se guardan** en un archivo de texto (`smtp_extracted.txt`).

## 6. Resultados y Finalización
Una vez que se procesan todas las URLs, el software guarda las credenciales SMTP válidas y **te notifica** que el proceso ha finalizado exitosamente.
