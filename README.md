# Taller de Sistemas Operativos, Redes de Cómputo, Sistemas Distribuidos y Manejo de Información
![LOGO FC](https://github.com/ZizuPM/Practica1/blob/main/img_logoFC_2019.png)
# Práctica III: _Configuración de un dominio y certificado de seguridad (HTTPS)_.
![GCP_LOGO](https://github.com/ZizuPM/Practica_1_GPC/blob/main/gcp.png)

## Objetivo:
El objetivo de la práctica es el de configurar un dominio y un certificado de seguridad en la instancia de GCP.

## Prerequisitos

1. Contar con usuario y contraseña de la cuenta GCP, en caso de no contar con ello no se podrá realizar la práctica.
2. Instancia GCP corriendo y con su ip estatica.
3. Práctica 2 realizada.
4. Registro en: <https://education.github.com/pack>.


# Desarrollo

1.  Se elige un dominio en <https://get.tech/github-student-developer-pack> el cual es gratuito.
2.  Se crea un registro A para que se direccione a la IP estatica de GCP.
3.  Se valida la replicación en todo el mundo del dominio adquirido.
4.  Se instala cerbot para certificado de LetsEncrypt.org.
5.  Se configura el certificado en Apache server de GCP.
6.  Se realiza el análisis de tráfico con Wireshark utilizando el formulario (replicar demo de la práctica 3 y capturar pantallas).
7.  Detener instancia GCP.

## Guia para su desarrollo
Se ha desarrollado una guia para familiarizarse con el entorno de Google Cloud y pueden llevar a acabo la practica: <https://docs.google.com/document/d/1itxSHdvyXPbGODIbd84nFmYdofqtQfy_zq4gYjbdAIE/edit?usp=sharing>

NOTA: La guia solo sirve como material de apoyo, mas no contiene en su totalidad los pasos para llevar acabo la practica.

# Evaluación

1.  Describir con sus propias palabras ¿Qué es un DNS?
2.  ¿Qué es un registro A y qué elementos fueron necesarios para registrarlo en el DNS de CloudFlare?
3.  ¿Qué es un registro CNAME y Cuál es la diferencia con el registro A?
4.  ¿Qué es HTTPS ? y ¿Por qué es importante para tu seguridad?
5.  URL creada en la práctica.
6.  Pantalla de tráfico **seguro** capturado con Wireshark de tu formulario (usar metodo post).

# Notas adicionales

1.  El reporte se entrega de manera individual.
2.  Incluir las respuestas del Cuestionario en el reporte.
3.  Se pueden agregar posibles errores, complicaciones, opiniones, críticas de la práctica o del laboratorio, o cualquier comentario relativo a la práctica.
4.  Subir los archivos relacionados con la práctica a Moodle.
