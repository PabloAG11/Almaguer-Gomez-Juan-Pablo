# Almaguer-Gomez-Juan-Pablo
# Villalpando-Casillas-Luz-Andrea

Tópicos para el Despliegue de Aplicaciones

¨*Presentación:
Comunicación Cliente–Servidor usando Sockets en Python
Este proyecto implementa un sistema básico de comunicación cliente–servidor utilizando el lenguaje de programación Python y el módulo socket, el cual permite el intercambio de información a través de una red local mediante el protocolo TCP/IP.
El sistema está compuesto por dos programas independientes:
Servidor, encargado de escuchar y atender conexiones.
Cliente, encargado de conectarse al servidor y enviar mensajes.
El objetivo principal es demostrar el funcionamiento de una arquitectura cliente–servidor y comprender cómo se establece una comunicación de red a bajo nivel.

*Funcionamiento del Servidor
El servidor se configura para:
Escuchar conexiones en todas las interfaces de red (0.0.0.0).
Utilizar el puerto 8000 para la comunicación.
Aceptar una conexión entrante de un cliente.
Recibir mensajes enviados por el cliente.
Mostrar los mensajes en consola.
Enviar una respuesta confirmando la recepción del mensaje.
El servidor permanece activo hasta que el cliente cierra la conexión.

* Funcionamiento del Cliente
El cliente se configura para:
Conectarse a la dirección IP del servidor.
Utilizar el mismo puerto configurado en el servidor.
Permitir al usuario escribir mensajes desde el teclado.
Enviar los mensajes al servidor.
Recibir y mostrar la respuesta del servidor
El cliente puede finalizar la comunicación escribiendo la palabra “salir”.
