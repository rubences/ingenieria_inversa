# 1. SCAPY
Scapy es una completa herramienta interactiva de manipulación de paquetes escrita en Python por Philippe Biondi. Realiza principalmente dos funciones: enviar paquetes y recibir respuestas.

Puede falsificar o decodificar paquetes de una variedad de protocolos, enviarlos, recibir respuestas, emparejar solicitudes con respuestas y devolver una lista de parejas de paquetes y una lista de paquetes no emparejados. Puede manejar fácilmente las tareas más comunes como el escaneo de la red, el descubrimiento de la red, el rastreo, los ataques, el sondeo, etc.

El objetivo de Scapy es hacer que la manipulación de paquetes sea fácil proporcionando un conjunto de funcionalidades que salvan la distancia entre la programación de red de bajo nivel y los protocolos de alto nivel. Es una gran herramienta para iniciarse en la manipulación de paquetes. No es difícil de usar, pero tiene una empinada curva de aprendizaje.

Instalación y ayuda: https://scapy.readthedocs.io/en/latest/

pip install scapy


# 2. REQUESTS
Requests es una librería HTTP de Python que se utiliza para enviar peticiones HTTP/HTTPS fácilmente. La librería requests es una herramienta increíblemente útil y versátil para escribir scripts en Python que requieran interacción con servicios web.

Ofrece una interfaz conveniente para enviar solicitudes HTTP y manejar las respuestas. La librería se puede utilizar para cualquier cosa, desde el envío de solicitudes simples a la obtención de datos complejos de las API a los sitios web de raspado (scraping).

Algunas de las características de la librería requests son Keep-alive (mantenimiento de conexiones), dominios y URLs, sesiones con persistencia de cookies, verificación SSL, y mucho más.
La librería Requests sirve como una herramienta fundamental para el hacking, ya que la mayoría de las actividades de hacking requieren la comunicación con servidores remotos y la obtención de recursos a través de Internet. Si no estás familiarizado con la librería Requests, la página de documentación es un buen lugar para empezar. Para instalar requests, ejecuta este comando en tu terminal: https://docs.python-requests.org/en/latest/

pip install requests

# 3. IMPACKET
Impacket es una colección de clases de Python para trabajar con protocolos de red. Actualmente, la librería se centra en proporcionar soporte para la programación de sockets de bajo nivel, TCP/IP, y múltiples protocolos de alto nivel. Es una librería de Python que facilita a los programadores la creación y decodificación de paquetes de red.

Impacket es utilizado por muchos hackers y probadores de penetración para elaborar ataques de intrusión personalizados basados en la red, como el ataque de intermediario (MitM) y el secuestro de sesiones. Originalmente fue diseñado como una herramienta interna para ayudar en las pruebas, pero ha crecido hasta convertirse en una poderosa herramienta de hacker que puede ser utilizada contra las redes.

El objetivo de Impacket es facilitar la programación de redes a los programadores de Python y proporcionar un marco para implementar protocolos personalizados. Por ejemplo, Impacket puede utilizarse para implementar versiones personalizadas de la pila TCP/IP para una plataforma determinada. Para instalar IMpacket, secureauth.com/labs/open-source-tools/impacket/ ejecuta:

pip install impacket

# 4. PWNTOOLS
pwntools es un marco de trabajo CTF (Capture-the-Flag) y una librería de desarrollo de exploits escrita en Python. Está diseñada para facilitar la creación rápida de prototipos y el desarrollo.

pwntools proporciona una serie de herramientas útiles para las pruebas de penetración, la automatización de la ingeniería inversa, la creación de exploits, programas de fuzzing, y más.

También permite a los usuarios crear rápidamente exploits para desafíos en competiciones CTF. Esta librería funciona mejor con las versiones de 64 bits de Ubuntu LTS y tiene muchos módulos que permiten un rápido desarrollo de exploits y flexibilidad a la hora de escribir código de rogue.
Encuentra la documentación de pwntools: https://docs.pwntools.com/en/latest/

pip install pwntools

# 5. CRYPTOGRAPHY
Cryptography es un paquete que proporciona recetas criptográficas a los desarrolladores de Python. Esto incluye encriptación, hashing, generación de números aleatorios, firmas, así como cifrados por bloque y de flujo.

Proporciona una API de alto nivel para algoritmos criptográficos fuertes como las firmas digitales y bloques de construcción criptográficos de bajo nivel diseñados con el rendimiento en mente. El hacking ético hace uso de esta funcionalidad para cifrar y descifrar información sensible compartida en Internet.

La guía de desarrollo será esta https://cryptography.io/en/latest/

pip install cryptography

# 6. PYTHON-NMAP
Python-nmap es una librería de Python que ayuda a utilizar el escáner de puertos Nmap. Nmap es una herramienta de administración de redes y auditoría de seguridad. Normalmente se utiliza para descubrir hosts y servicios disponibles en una red, aunque también puede utilizarse para examinar un único host.

La librería python-nmap sirve como una wrapper de Python para la herramienta Nmap permitiendo acceder, usar y manipular fácilmente las características y funcionalidades de Nmap. La librería no sustituye a la herramienta Nmap, sino que sólo proporciona una interfaz para interactuar con Nmap.

Ofrece un rico conjunto de características para el escaneo de puertos, el descubrimiento de hosts y TCP/IP fingerprinting. Esta librería es una herramienta perfecta para hackers y administradores de sistemas que quieran automatizar las tareas de escaneo de la red y los informes.

Para instalar python-nmap, ejecuta:

pip install python-nmap

Para más información acerca de esta librería, consulta la documentación. https://xael.org/pages/python-nmap-en.html

# 7. FAKER
Faker es un paquete de Python que genera datos falsos. Puede generar cualquier cosa, desde nombres, números de teléfono y direcciones hasta textos falsos, documentos XML, etc. Faker es muy fácil de usar. Sólo tienes que llamar a faker.name() y obtendrás un nombre aleatorio, faker.address() y obtendrás una dirección falsa.

Viene con muchas otras funciones para generar datos falsos. Hay varias razones por las que puedes querer usar Faker. Tal vez necesites rellenar una base de datos con información falsa para un prototipo 

Puedes instalar la librería faker ejecutando este comando:

pip install Faker
Puedes consultar la documentación para obtener más directrices. https://faker.readthedocs.io/en/master/

# 8. PYCRYPTO

PyCrypto es una colección de algoritmos y protocolos criptográficos. Es una librería de Python que proporciona una serie de herramientas para la criptografía y la seguridad. PyCrypto es una librería de código abierto que proporciona una serie de herramientas para la criptografía y la seguridad.

PyCrypto es una librería de código abierto que proporciona una serie de herramientas para la criptografía y la seguridad. La librería proporciona una serie de algoritmos criptográficos y protocolos, incluyendo cifrados, firmas digitales, cifrados de flujo, cifrados de bloque, cifrados de clave pública, y más.

pip install pycrypto

Documentación de PyCrypto: https://www.dlitz.net/software/pycrypto/

