# Guia-N.7
Sockets y Mensajeria Cliente/Servidor

## Preguntas Orientadoras
1. ¿Cuáles fueron los aprendizajes obtenidos al realizar esta guía?, liste como mínimo 3 aprendizajes y relaciónelos con su futuro quehacer profesional.
- Entender el funcionamiento del socket además de la mensajería entre servidor cliente.
- Entender el funcionamiento de hilos para el proceso de sockets.
- Entender como conectarlo por medio de formulario.
2. ¿Dónde presento mayor dificultad resolviendo la guía? y ¿cómo lo resolvieron? ¿cuáles fueron las estrategias de solución?
- Se presento mayor dificultad y se sigue presentando al momento de agregar el socket al proyecto, puesto que el proyecto se maneja con JSP y el Socket es mayormente dado para aplicativos y forms, igual se sigue indagando en documentación y videos para poder sacar adelante el proyecto y poder implementarlo de buena manera.
## Actividad de Trabajo Autónomo
1.	 What is distributed computing?
- Refers to a system where multiple computers work together to perform a task, instead of relying on a single machine, distributed computing systems share tasks across different networked computers that may be located in different physical locations, in Java, it allows applications to distribute their workload across multiple servers or devices, improving scalability, performance, and resilience, it is commonly implemented using technologies such as RMI, web services, and sockets that facilitate communication across different parts of a distributed system.
2.	What are Sockets used for?
- Are communication endpoints between two machines over a network, in Java, they allow programs to connect and exchange data over the networks, when a client wants to communicate with a server, it creates a socket that connects to a corresponding socket on the server, sockets support connection-oriented protocols like TCP that ensure reliable communication and connectionless protocols like UDP that are faster but do not guarantee data delivery or order.
3.	What is the difference between UDP and TCP?
- TCP: is a connection-oriented protocol that provides reliable, ordered, and error-checked delivery of data between applications, it establishes a connection before data transfer, ensuring all packets arrive in the correct sequence, it is commonly used in applications that require accuracy, such as web browsing and email.
- UDP: is a connectionless protocol that focuses on speed rather than reliability, it does not establish a connection or guarantee packet delivery, making it faster but less reliable, it is often used in real-time applications where speed is essential, such as video streaming and online gaming.
4.	What are RMI and JNDI? And how are they related to Sockets?
- RMI: allows a Java application to invoke methods on an object located remotely on another Java Virtual Machine, it abstracts the details of network communication so developers can invoke methods on remote objects as if they were local, it uses sockets, generally TCP, to establish communication between the client and server JVMs.
- JNDI: is a Java API that allows applications to look up and access resources and services in a networked environment, such as databases or messaging services, it is often used for discovering remote objects or services and integrating them into Java applications, especially in distributed and enterprise settings, although JNDI does not directly use sockets, the resources it locates, like RMI objects, may use sockets for communication.
5.	What is a Web Service?
- It is a standardized way for applications to communicate over a network, typically using HTTP, it allows different software applications to exchange data and services, regardless of their underlying technologies or programming languages, web services can be SOAP-based or RESTful:
- SOAP: follows a strict protocol for exchanging structured data using XML, suitable for complex enterprise-level transactions.

- RESTful: are simpler and rely on HTTP methods like GET, POST, PUT, and DELETE, often using JSON for lightweight data interchange, web services are a key technology in distributed computing, allowing Java applications to integrate with other systems over the internet, unlike Java sockets, which are low-level and specific to Java programs, web services are language-independent and follow open standards.

Link Video Explicativo Youtube:	https://youtu.be/fPQSRB-hKmQ
