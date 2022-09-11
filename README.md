# Troyano-Simple-VB6-PoC
Prueba de concepto de un troyano simple desarrollado en Visual Basic 6.0

▶ **Vídeo PoC**: https://youtu.be/HuanrTRfKQI

Usando una conexión directa cliente/servidor con el componente Winsock Control a un equipo víctima podemos:
- Apagar
- Reiniciar
- Enviar mensajes
- Registrar pulsaciones de teclado (Keylogger)

Por defecto el puerto de escucha para el servidor es el 4455. 

Para cambiarlo modificamos el fichero Server.frm, línea 35, *Sock1.LocalPort = "4455"*.

![troyano-simple-vb6-poc](https://github.com/adrianlois/Troyano-Simple-VB6-PoC/blob/main/screenshots/troyano-simple-vb6-poc.png)
