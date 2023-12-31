# [Recurso Original](https://cs.fyi/guide/how-does-internet-work) (Version - Febrero 16, 2023)
# ¿Cómo funciona el internet?

Como desarrollador, es importante tener un sólido entendimiento de qué es internet y cómo funciona. Es la base sobre la cual se construyen la mayoría de las aplicaciones de software modernas. Para desarrollar aplicaciones y servicios efectivos, seguros y escalables, necesitas comprender bien cómo funciona internet y cómo aprovechar su potencia y conectividad.

En este artículo, cubriremos los conceptos básicos de internet, incluyendo qué es y cómo funciona, algunos conceptos y terminología básicos, así como algunos protocolos comunes que se utilizan para construir aplicaciones y servicios en internet.

* Introducción a Internet
* Cómo funciona Internet: Una visión general
* Conceptos básicos y terminología
* El papel de los protocolos en Internet
* Comprensión de las direcciones IP y los nombres de dominio
* Introducción a HTTP y HTTPS
* Construcción de aplicaciones con TCP/IP
* Seguridad en la comunicación por internet con SSL/TLS
* El futuro: Tendencias y tecnologías emergentes
* Conclusión

Tenemos mucho que cubrir, ¡así que empecemos!

## Introducción a Internet
Antes de aprender qué es Internet, necesitamos entender qué es una red. Una red es un grupo de computadoras u otros dispositivos que están conectados entre sí. Por ejemplo, en tu hogar puedes tener una red de computadoras y dispositivos. Tu amigo que vive al lado puede tener una red similar de dispositivos. Su vecino puede tener una red similar de dispositivos. Todas estas redes, cuando están conectadas entre sí, forman internet.

> Internet es una red de redes.

Internet fue desarrollada a finales de la década de 1960 por el Departamento de Defensa de los Estados Unidos como un medio para crear una red de comunicación descentralizada que pudiera resistir un ataque nuclear. Con el tiempo, ha evolucionado hasta convertirse en una red compleja y sofisticada que abarca todo el mundo.

Hoy en día, Internet es una parte esencial de la vida moderna, utilizada por miles de millones de personas en todo el mundo para acceder a información, comunicarse con amigos y familiares, realizar negocios y mucho más. Como desarrollador, es esencial tener un sólido entendimiento de cómo funciona Internet y de las diversas tecnologías y protocolos que lo sustentan.

## Cómo funciona Internet: Una visión general
A un nivel elevado, Internet funciona conectando dispositivos y sistemas informáticos mediante un conjunto de protocolos estandarizados. Estos protocolos definen cómo se intercambia la información entre dispositivos y aseguran que los datos se transmitan de manera confiable y segura.

El núcleo de Internet es una red global de routers interconectados, que son responsables de dirigir el tráfico entre diferentes dispositivos y sistemas. Cuando envías datos por Internet, estos se dividen en pequeños paquetes que se envían desde tu dispositivo a un router. El router examina el paquete y lo envía al siguiente router en la ruta hacia su destino. Este proceso continúa hasta que el paquete llega a su destino final.

Para asegurar que los paquetes se envíen y reciban correctamente, Internet utiliza una variedad de protocolos, incluyendo el Protocolo de Internet (IP) y el Protocolo de Control de Transmisión (TCP). IP se encarga de dirigir los paquetes a su destino correcto, mientras que TCP asegura que los paquetes se transmitan de manera confiable y en el orden correcto.

Además de estos protocolos centrales, existen una amplia gama de otras tecnologías y protocolos que se utilizan para habilitar la comunicación y el intercambio de datos a través de Internet, incluyendo el Sistema de Nombres de Dominio (DNS), el Protocolo de Transferencia de Hipertexto (HTTP) y el protocolo de Capa de Conexión Segura/Seguridad de la Capa de Transporte (SSL/TLS). Como desarrollador, es importante tener un sólido entendimiento de cómo estas diferentes tecnologías y protocolos trabajan juntos para habilitar la comunicación y el intercambio de datos a través de Internet.

## Conceptos básicos y terminología
Para entender Internet, es importante estar familiarizado con algunos conceptos y términos básicos. Aquí tienes algunos términos clave y conceptos para tener en cuenta:

* **Paquete**: Una pequeña unidad de datos que se transmite por Internet.
* **Router**: Un dispositivo que dirige paquetes de datos entre diferentes redes.
* **Dirección IP**: Un identificador único asignado a cada dispositivo en una red, utilizado para dirigir datos al destino correcto.
* **Nombre de Dominio**: Un nombre legible por humanos que se utiliza para identificar un sitio web, como google.com.
* **DNS**: El Sistema de Nombres de Dominio se encarga de traducir nombres de dominio en direcciones IP.
* **HTTP**: El Protocolo de Transferencia de Hipertexto se utiliza para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web).
* **HTTPS**: Una versión encriptada de HTTP que se utiliza para proporcionar comunicación segura entre un cliente y un servidor.
* **SSL/TLS**: Los protocolos de Capa de Conexión Segura y Seguridad de la Capa de Transporte se utilizan para proporcionar comunicación segura por Internet.

Comprender estos conceptos y términos básicos es esencial para trabajar con Internet y desarrollar aplicaciones y servicios basados en la red.

## El papel de los protocolos en Internet
Los protocolos juegan un papel crítico al facilitar la comunicación y el intercambio de datos a través de Internet. Un protocolo es un conjunto de reglas y normas que definen cómo se intercambia la información entre dispositivos y sistemas.

Existen muchos protocolos diferentes utilizados en la comunicación por Internet, incluyendo el Protocolo de Internet (IP), el Protocolo de Control de Transmisión (TCP), el Protocolo de Datagramas de Usuario (UDP), el Sistema de Nombres de Dominio (DNS) y muchos otros.

IP se encarga de dirigir paquetes de datos a su destino correcto, mientras que TCP y UDP aseguran que los paquetes se transmitan de manera confiable y eficiente. DNS se utiliza para traducir nombres de dominio en direcciones IP, y HTTP se utiliza para transferir datos entre clientes y servidores.

Uno de los principales beneficios de utilizar protocolos estandarizados es que permiten que dispositivos y sistemas de diferentes fabricantes y proveedores se comuniquen entre sí de manera fluida. Por ejemplo, un navegador web desarrollado por una empresa puede comunicarse con un servidor web desarrollado por otra empresa, siempre y cuando ambos se adhieran al protocolo HTTP.

Como desarrollador, es importante entender los diversos protocolos utilizados en la comunicación por Internet y cómo trabajan juntos para permitir la transferencia de datos e información a través de la red.

## Comprensión de las direcciones IP y los nombres de dominio
Las direcciones IP y los nombres de dominio son conceptos importantes para entender al trabajar con Internet.

Una dirección IP es un identificador único asignado a cada dispositivo en una red. Se utiliza para dirigir datos al destino correcto, asegurando que la información se envíe al destinatario previsto. Las direcciones IP suelen representarse como una serie de cuatro números separados por puntos, como "192.168.1.1".

Por otro lado, los nombres de dominio son nombres legibles por humanos utilizados para identificar sitios web y otros recursos en Internet. Típicamente, están compuestos por dos o más partes separadas por puntos. Por ejemplo, "google.com" es un nombre de dominio. Los nombres de dominio se traducen a direcciones IP mediante el Sistema de Nombres de Dominio (DNS).

DNS es una parte crítica de la infraestructura de Internet y es responsable de traducir nombres de dominio en direcciones IP. Cuando ingresas un nombre de dominio en tu navegador web, tu computadora envía una consulta DNS a un servidor DNS, que devuelve la dirección IP correspondiente. Luego, tu computadora utiliza esa dirección IP para conectarse al sitio web u otro recurso que hayas solicitado.

## Introducción a HTTP y HTTPS
HTTP (Protocolo de Transferencia de Hipertexto) y HTTPS (HTTP Seguro) son dos de los protocolos más comúnmente utilizados en aplicaciones y servicios basados en Internet.

HTTP es el protocolo utilizado para transferir datos entre un cliente (como un navegador web) y un servidor (como un sitio web). Cuando visitas un sitio web, tu navegador web envía una solicitud HTTP al servidor, solicitando la página web u otro recurso que hayas pedido. El servidor luego envía una respuesta HTTP al cliente, que contiene los datos solicitados.

HTTPS es una versión más segura de HTTP que cifra los datos transmitidos entre el cliente y el servidor mediante cifrado SSL/TLS (Capa de Conexión Segura/Seguridad de la Capa de Transporte). Esto proporciona una capa adicional de seguridad, ayudando a proteger información sensible como credenciales de inicio de sesión, información de pago y otros datos personales.

Cuando visitas un sitio web que utiliza HTTPS, tu navegador web mostrará un ícono de candado en la barra de direcciones, indicando que la conexión es segura. También es posible que veas las letras "https" al principio de la dirección del sitio web en lugar de "http".

## Construcción de aplicaciones con TCP/IP
TCP/IP (Protocolo de Control de Transmisión/Protocolo de Internet) es el protocolo de comunicación subyacente utilizado por la mayoría de las aplicaciones y servicios basados en Internet. Proporciona una entrega de datos confiable, ordenada y verificada contra errores entre aplicaciones que se ejecutan en dispositivos diferentes.

Al construir aplicaciones con TCP/IP, hay algunos conceptos clave para entender:

* **Puertos**: Los puertos se utilizan para identificar la aplicación o servicio en ejecución en un dispositivo. A cada aplicación o servicio se le asigna un número de puerto único, lo que permite enviar datos al destino correcto.
* **Sockets**: Un socket es una combinación de una dirección IP y un número de puerto, que representa un punto final específico para la comunicación. Los sockets se utilizan para establecer conexiones entre dispositivos y transferir datos entre aplicaciones.
* **Conexiones**: Una conexión se establece entre dos sockets cuando dos dispositivos desean comunicarse entre sí. Durante el proceso de establecimiento de la conexión, los dispositivos negocian varios parámetros, como el tamaño máximo del segmento y el tamaño de la ventana, que determinan cómo se transmitirán los datos sobre la conexión.
* **Transferencia de datos**: Una vez que se establece una conexión, los datos pueden transferirse entre las aplicaciones que se ejecutan en cada dispositivo. Los datos se transmiten típicamente en segmentos, y cada segmento contiene un número de secuencia y otros metadatos para garantizar una entrega confiable.

Al construir aplicaciones con TCP/IP, es necesario asegurarse de que la aplicación esté diseñada para funcionar con los puertos, sockets y conexiones apropiados. También es importante estar familiarizado con los diversos protocolos y estándares que se utilizan comúnmente con TCP/IP, como HTTP, FTP (Protocolo de Transferencia de Archivos) y SMTP (Protocolo Simple de Transferencia de Correo). Comprender estos conceptos y protocolos es esencial para construir aplicaciones y servicios efectivos, escalables y seguros basados en Internet.

## Seguridad en la comunicación por internet con SSL/TLS
Como discutimos anteriormente, SSL/TLS es un protocolo utilizado para cifrar datos que se transmiten por Internet. Se utiliza comúnmente para proporcionar conexiones seguras para aplicaciones como navegadores web, clientes de correo electrónico y programas de transferencia de archivos.

Cuando se utiliza SSL/TLS para asegurar la comunicación por Internet, hay algunos conceptos clave que entender:

* **Certificados**: Los certificados SSL/TLS se utilizan para establecer confianza entre el cliente y el servidor. Contienen información sobre la identidad del servidor y están firmados por una entidad de confianza (una Autoridad de Certificación) para verificar su autenticidad.

* **Handshake**: Durante el proceso de saludo de SSL/TLS, el cliente y el servidor intercambian información para negociar el algoritmo de cifrado y otros parámetros para la conexión segura.

* **Cifrado**: Una vez que se establece la conexión segura, los datos se cifran mediante el algoritmo acordado y se pueden transmitir de manera segura entre el cliente y el servidor.

Al construir aplicaciones y servicios basados en Internet, es importante entender cómo funciona SSL/TLS y asegurarse de que tu aplicación esté diseñada para utilizar SSL/TLS al transmitir datos sensibles como credenciales de inicio de sesión, información de pago y otros datos personales. También deberás asegurarte de obtener y mantener certificados SSL/TLS válidos para tus servidores, y seguir las mejores prácticas para configurar y asegurar tus conexiones SSL/TLS. Al hacerlo, puedes contribuir a proteger los datos de tus usuarios y garantizar la integridad y confidencialidad de la comunicación de tu aplicación por Internet.

## El futuro: Tendencias y tecnologías emergentes
La internet está en constante evolución, y continuamente surgen nuevas tecnologías y tendencias. Como desarrollador, es importante mantenerse actualizado con los últimos avances para construir aplicaciones y servicios innovadores y efectivos.

Aquí hay algunas de las tendencias y tecnologías emergentes que están dando forma al futuro de Internet:

* **5G**: 5G es la última generación de tecnología de redes móviles, que ofrece velocidades más rápidas, menor latencia y mayor capacidad que las generaciones anteriores. Se espera que permita nuevos casos de uso y aplicaciones, como vehículos autónomos y cirugías remotas.

* **Internet de las cosas (IoT)**: IoT se refiere a la red de dispositivos físicos, vehículos, electrodomésticos y otros objetos que están conectados a Internet y pueden intercambiar datos. A medida que IoT continúa creciendo, se espera que revolucione industrias como la salud, el transporte y la manufactura.

* **Inteligencia Artificial (IA)**: Tecnologías de IA como el aprendizaje automático y el procesamiento del lenguaje natural ya se están utilizando para impulsar una amplia gama de aplicaciones y servicios, desde asistentes de voz hasta detección de fraudes. A medida que la IA avanza, se espera que permita nuevos casos de uso y transforme industrias como la salud, las finanzas y la educación.

* **Blockchain**: Blockchain es una tecnología de libro de contabilidad distribuido que permite transacciones seguras y descentralizadas. Se está utilizando para alimentar una amplia variedad de aplicaciones, desde criptomonedas hasta la gestión de la cadena de suministro.

* **Edge computing**: La computación en el borde se refiere al procesamiento y almacenamiento de datos en el borde de la red, en lugar de en centros de datos centralizados. Se espera que permita nuevos casos de uso y aplicaciones, como análisis en tiempo real y aplicaciones de baja latencia.

Manteniéndote al día con estas y otras tendencias y tecnologías emergentes, puedes asegurarte de que tus aplicaciones y servicios estén diseñados para aprovechar las últimas capacidades y ofrecer la mejor experiencia posible para tus usuarios.

## Conclusión
Y así llegamos al final de este artículo. Hemos cubierto mucho terreno, así que tomémonos un momento para revisar lo que hemos aprendido:

* Internet es una red global de computadoras interconectadas que utiliza un conjunto estándar de protocolos de comunicación para intercambiar datos.
* Internet funciona conectando dispositivos y sistemas informáticos mediante protocolos estandarizados, como IP y TCP.
* El núcleo de Internet es una red global de routers interconectados que dirigen el tráfico entre diferentes dispositivos y sistemas.
* Conceptos y terminología básicos con los que necesitas familiarizarte incluyen paquetes, routers, direcciones IP, nombres de dominio, DNS, HTTP, HTTPS y SSL/TLS.
* Los protocolos juegan un papel crítico al facilitar la comunicación y el intercambio de datos por Internet, permitiendo que dispositivos y sistemas de diferentes fabricantes y proveedores se comuniquen sin problemas.

Espero que hayas encontrado útil este artículo. Si tienes alguna pregunta o comentario, no dudes en dejarlos abajo. ¡Gracias por leer!