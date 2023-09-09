# Taller de Sistemas Operativos, Redes de Cómputo, Sistemas Distribuidos y Manejo de Información
![LOGO FC](https://github.com/ZizuPM/Practica1/blob/main/img_logoFC_2019.png)
# Práctica III: _Configuración de un dominio y certificado de seguridad (HTTPS)_.
![GCP_LOGO](https://github.com/ZizuPM/Practica_1_GPC/blob/main/gcp.png)

## Objetivo:
El objetivo de la práctica es el de configurar un dominio y un certificado de seguridad en la instancia de GCP.

## Prerequisitos

1. Contar con usuario y contraseña de la cuenta GCP, en caso de no contar con ello no se podrá realizar la práctica.
2. Instancia GCP corriendo y con su ip estatica.
3. Práctica 2 realizada
4. Registro en: <https://education.github.com/pack>


# Desarrollo

1.  Se elige un dominio en <https://www.freenom.com> el cual es gratuito [video](https://gitlab.com/ismael.andrade/laboratorio-de-redes/blob/master/lab4/videos/lab4-freenom.mov?expanded=true&viewer=rich)
2.  Se crea un registro A para que se direccione a la IP elástica de AWS [video](https://gitlab.com/ismael.andrade/laboratorio-de-redes/blob/master/lab4/videos/lab4-registro-a.mov?expanded=true&viewer=rich)
3.  Se valida la replicación en todo el mundo del dominio adquirido[video](https://gitlab.com/ismael.andrade/laboratorio-de-redes/blob/master/lab4/videos/lab4-dnscheck.mov?expanded=true&viewer=rich)
4.  Se instala cerbot para certificado de LetsEncrypt.org [video](https://gitlab.com/ismael.andrade/laboratorio-de-redes/blob/master/lab4/videos/lab4-letsencrypt.mov?expanded=true&viewer=rich)
5.  Se configura el certificado en Apache server de AWS [video](https://gitlab.com/ismael.andrade/laboratorio-de-redes/blob/master/lab4/videos/lab4-https.mov?expanded=true&viewer=rich)
6.  Se realiza el análisis de tráfico con wireshark utilizando el formulario, (replicar demo de la práctica 3 y capturar pantallas
7.  Detener instancia EC2 (no elegir la opción de terminar)

[](#evaluaci%C3%B3n)Evaluación
------------------------------

1.  Describir con sus propias palabras ¿Qué es un DNS?
2.  ¿Qué es un registro A y qué elementos fueron necesarios para registrarlo en el DNS de Freenom?
3.  ¿Qué es un registro CNAME y Cuál es la diferencia con el registro A?
4.  ¿Qué es HTTPS ? y ¿Por qué es importante para tu seguridad?
5.  URL creada en la práctica
6.  Pantalla de tráfico **seguro** capturado con wireshark de tu formulario (usar metodo post)

### [](#notas-adicionales)Notas adicionales

1.  El reporte se entrega de manera individual.
2.  Incluir las respuestas del Cuestionario en el reporte.
3.  Se pueden agregar posibles errores, complicaciones, opiniones, críticas de la práctica o del laboratorio, o cualquier comentario relativo a la práctica.
4.  Subir los archivos relacionados con la práctica a Moodle

### [](#errores-comunes)Errores comunes

Algunos alumnos tuvieron problemas con freenom al registrar dominios, estos pasos ayudaron a solucionarlos

Alternativas

1.  Intentar crear el dominio con otro correo diferente al de ciencias, de preferencia con un navegador en modo incógnito, en el campo de nombre colocar uno real
2.  Colocar Datos ficticios pero válidos (pueden poner la dirección de la UNAM y su código postal, telefono de 10 dígitos)
3.  Crear el dominio con una cuenta de 10minutesmail (servicio rápido de correo de 10 minutos de duración)
