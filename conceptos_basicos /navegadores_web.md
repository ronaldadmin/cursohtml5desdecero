# Navegadores

Un navegador es un programa (complejo) que cambio y transforma el código que recibe desde un servidor<sup>1</sup> en algo entendible para un humano (una página web, imágenes, etc).

Entre algunas de las responsabilidades que debe garantizar un navegador se encuentran:

* **Integridad**: para transmitir páginas web se utiliza una forma de comunicación llamada HTTP (o protocolo [HTTP](http://www.w3.org/Protocols/)). Este protocolo es el lenguaje común entre el servidor y el navegador web. 

* **Seguridad**: dado que los navegadores reciben código escrito normalmente por otras personas, el navegador implementa algunas reglas de seguridad. Estas reglas se definen a diferentes niveles: durante la conexión entre las máquinas y el envío ([HTTPS](https://en.wikipedia.org/wiki/HTTPS)), al ejecutarse en el navegador ([CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)), etc.

* **Optimización**: al mismo tiempo que reciben la información, los navegadores integran mecanismos para acelerar la carga y mejorar la experiencia del usuario, por ejemplo acelerar el tiempo de carga utilizando una memoria de almacenamiento temporal (memoria caché), o comprimiendo los mensajes durante las comunicaciones.

Aunque existen multitud de [navegadores](https://es.wikipedia.org/wiki/Navegador_web#Ejemplos_de_navegadores_web), nosotros usaremos Google Chrome durante todo el curso.

Aquí te dejo además una gráfica que muestra la cuota de uso de los navegadores más populares:

![](../images/quota_navegadores.png)<br>
Fuente: [StatCounter](http://gs.statcounter.com/#browser-ww-monthly-201411-201601-bar)

---
Aclaraciones:

1. Normalmente a través de un servidor web HTTP
