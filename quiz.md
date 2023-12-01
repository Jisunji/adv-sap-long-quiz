## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA). 
The service-oriented architecture (SOA) is a development approach that reuses or combines different components of a system, called services, for complicated activities to 
design business applications.


2. List and discuss the characteristics of SOA. 
a) Standardized Servie Contracts means that the services must comply with a set of guidlines. 
b) Loose coupling simply means that each service should have as little dependency with one another as possible.
c) Abstraction means that the users should only know the functions of the service, while hiding the implementation and the "how it works" of the service itself. 
d) Reusability simply means that the service can be used and modified for other functions when necessary. 
e) Autonomy means that the service is able to execute its function even without relying on other services. 
f) Statelessness means that the service processes requests using only the information given in that current request, and not any previous ones. 
g) Discoverability is self explanatory. The service should be able to be discovered through a registry. 
h) Composability simply means that the service can be used in conjunction with other services to create business applications and execute complex procces. 
i) Interoperability means that the service can communicatie with other services using standardized protocols.


3. Define Microservices. 
Microservices are similar to SOA in a way that it aims to make software and systems that are reusable, modular, and flexible, albeit in a smaller scale. It is a 
development approach that natively utilizes cloud computing services.


4. List and discuss the benefits of using Microservices. 
a) Independently Deployable - microservices ensures that services can be deployed quickly as it is divided into small, digestible groups essentially. It is also independent of other services which means teams can work on one specific service without it affecting the entire system. 
b) Righ tool for the job - this basically means that software/systems developed with this approach can be optimized for specific functions. 
c) Precise Scaling - due to services being independent of one another, scaling one service does not require scaling the entire project. This saves resources and time as only those that need to be scaled are scaled.


5. List and discuss the similarities and differences of SOA and Microservices. 
Similarities

Both architectural approaches are used to create software applications. Both place a strong emphasis on using services as the essential components of applications. 
Both encourage strong cohesiveness and loose coupling between services. For communication, both rely on common protocols and data formats. 
Both aim to enhance software programs' adaptability, scalability, and maintainability.

Differences

Microservices are more narrowly focused on a single capability, whereas SOA services, despite being larger and coarser grained, can manage multiple business functions. 
With fewer dependencies on other services, microservices exhibit greater coherence and loose coupling. 
Unlike SOA services, which communicate via an Enterprise Service Bus (ESB), they engage directly through APIs. 
SOA services are usually deployed as a single monolithic application, while microservices are independently deployed as separate services. 
SOA services are usually managed centrally, while microservices are managed independently by their respective teams.


6. Define Web Services.
The simplest definition for a web service is that it is a software is offered through the internet. It follows certain standards and protocols which allow it to act as a mediator
between applications when they need to communicate with eachother over commputer networks


7. List and discuss the benefits of using Web Services.
a) Exposing the Existing Function on the network
This means that applications can use the functionality of another program through the use of webservices. 

b) Interoperability
Interoperabiliy means that through web services, applications can communicate with one another regardless of their programming language nor the operating system in which they
are transmitting from. 
 
c) Standardized Protocol
Standardized protocols means that different entities use the same protocols in communicating with other programs. This ties in with interoperability, as it ensures smooth
communication between various languages, OSs, enterprises, etc. It also ensures that services must achieve a certain degree of quality that meets the industry standard.

d) Low Cost Communication
Web services use protocols that are common and cheap to use, which means that developers do not need to invest in expensive solutions to run and use the functionalities of a 
web service.


8. List and discuss the characteristics of Web Services.
a) XML - Based - XML is used by web services to transfer and represent data, which makes it compatible with a wide range of platforms, operating systems, and networks. 
The XML base improves interoperability by facilitating smooth communication between apps regardless of the underlying technologies.

b) Loosely Coupled - Loose coupling is encouraged by web services, allowing modifications to the service interface without impairing the client's ability to interact. 
This adaptability promotes adaptability and ease of maintenance by ensuring that changes made on one end do not require instant updates on the other.

c) Coarse-Grain - Web services, especially when applied to business logic, prioritize a coarse-grained approach over disclosing specific methods. This design approach supports 
the requirement for extensive and substantial services, enabling the efficient application of business logic inside an organizational structure.

d) Synchronous or Asynchronous - The flexibility of both synchronous and asynchronous activities is provided by web services. Asynchronous operations allow clients to perform 
other tasks before getting results later, whereas synchronous commands require instant client-side blocking until service completion.

e) Supports Remote Procedure Calls (RPCs) - Web services allow clients to call methods, functions, and procedures on distant objects via an XML-based interface. 
By exposing input and output features, these remote methods guarantee interoperability and efficient communication amongst distant components.

f) Supports Document Exchange - Web services utilize the general representation of XML to enable transparent content exchange. This capacity provides smooth integration 
with business procedures by extending from basic data, like addresses, to complex documents, like books.


9. List and discuss the distinct roles in Web Services Architecture.
a) Provider - A web service is created by the provider and made available to client applications that need its features. It is this organization's responsibility to ensure 
that potential users can access the service.

b) Requestor - The entity attempting to establish a connection with a web service is known as the requestor, or client application. It could be an application designed to 
access particular features provided by the web service, written in other programming languages like Java or.Net.

c) Broker - The broker acts as a middleman, making the UDDI system accessible. This approach improves the efficiency of service location for requestors by allowing client 
programs to find the location and specifics of the desired web service.

10. List and discuss the Web Services Components.
a) SOAP, or Simple Object Access Protocol, is a protocol used in online services to exchange structured data while using XML as its messaging format. Regardless of the 
platforms or programming languages that various applications are developed on, SOAP offers a standardized means of communication between them.

b) WSDL or Web Services Description Language is an XML-based language that is used to define the features that a web service offers. WSDL serves as a 
contract between the client and the service provider. It makes it possible for clients to comprehend how to use the online service.

c) UDDI or Universal Description, Discovery, and Integration is a directory service that enables companies to sign up and find online resources.
It offers a centralized registry where users can publish and retrieve web service-related data.
