## ***Assignment in Advanced Systems Integration & Architecture***
###1. **Define Service Oriented Architecture(SOA).**

	-It is an approach to building sftware that uses reusable components called services to perform specific tasks like checking customer's credit, etc... These services consist of both code and data integrations necessary for executing specific business functions. SOA aims to create a flexble and interoperable system by breaking down applications into smaller, reusable pieces that can be easily combinied and adapted for various applications and purposes.

### **2. List and discuss the characteristics of SOA.**

	1. Standardized Service Contracts - Services define their purpose and capabilities thru formal, sandardize contracts. This ensures clarity in communication and interaction between services.
	2.Loose Coupling - Services minimizes dependencies on each other and promotes flexibility. There's a constant effort to reduce interdependence between service contracts, implmentations and consumers.
	3.Abstraction - Services that hides the internal logic from the outside world. This helps prevent unnecessary information proliferation and maintains loosely-coupled relationships.
	4.Service Reusability - Logic is organized into sercvices with the goal of maximizing reuse. This promotes efficiecy by adding redundant development efforts.
	5. Autonomy - Services have control over the logic they encapsulate. Autonomy ensures that services can carry out their functions independently of external influences.
	6.Statelessness - Services that are designed to be stateless, meaning they don't retain information about previous interactions and this enhances scalability, supports agnostic logic and improves service reuse.
	7. Discoverability - Services can be discovered, usually thru a service registry. This makes it easier for other services or consumers to find and interact with available services.
	8.Composability - This services, break down complex problems into smaller, resuable components. 
This encourages efficiency when it comes to assembly of services to address vatious applications and business needs.
	9.Interoperability - This servic use standards that allows a mutiple subscribers to access and use the service. This ensures compatibility and seamless integration across different platforms.

### **3. Define Microservices.**

	Microservices are a modern way of building software where we can create an application using small, independent pieces called services. These services work together and can be updated, scaled and managed independently. They communicate with each other through well-defined methods like REST APIs or messaging. Nicroservices make it easier to update code, use different technologies wothout affecting the entire application. When combined, they're like building blocks that can create a flexible, agile and cost-effective system especially useful for handling various workloads efficiently.

### **4. List and discuss the benefits of using Microservices.**

	Microservices brings flexibility, speed, comprehensive, tool customization, efficient scaling and cloud benefits to our software development. here are the list of benefits of using Microservices:

	1.Independently Deployable - Microservices enable the independent deploymenr of small, individual services, addressing the challenge of deployments for minor updates.	
	2. Right Tools for the Tasks - Microservices lets you use different technologies for different tasks, this makes it easier and cheaper to adapt to new technologies.
	3.Efficient Scaling - It lets you scale only the parts of your application that needs it. This saves resources compared to scaling the whole application.
	4.Cloud Benefits - Microservices works well with cloud services, offering flexibility and cost savings. We pay for what we use and each part can use the best tools for the job.
	
### **5. List and discuss the similarities and differences of SOA and Microservices.**

	-SOA is an enterprise-focused with a common communication mechanism, while Microservices are application-focused emphasizing independent communication and specialization. These are some similarities and differences of SOA and Microservices:

Similarities:
	1.Loose Coupling - SOA and Microservices aim for loose coupling, meaning that individual components are independent and can evolve without affecting others.
	2. Reusability - Both architectures promote the reuse of components. SOA focuses on reusing serivces across the enterprise while Microservices encourage reuse within specific application.
	3.Interoperability - Both architectures emphasize the use of tandards for communication allowing services to work together.
	4.Independently Scalable - Both SOA and Microservices enable independent scaling of service, allowing resources to be allocated where needed.

Differences:
	1.Scope - SOA is designed for an enterprise-wide approach ensuring standardization across all services, while Microservices are application-specific, focusing on breaking down application into smaller pieces to be independently managed.
	2.Communication - SOA often relies on a common communication mechanism known as Enterprise Service Bus (ESB) while Microservices use independent communication protocols for each service.
	3.Service Granularity - SOA can vary from small, specialized services to enterprise-wide services. Microservices are highly specialized, design to perform specific functions very well.
	4.Speed and Duplication - SOA, with its emphasis on sharing a common architcture, can operate more slowly while Microservices priortize speed by minimizing sharing and favoring duplication where needed.

### **6. Define Web Services.**
	A web service is like a computer program that talks to other programs on the internet. It's a kind of software that follows specific rules for sending messages. These programs are independent, can be moved around, and can do different tasks. They can be described, shared, found and used over the internet to build things. Web services use a set of agreed-upon rules to exchange infrmation between different prgrams or systems. It's like a different languages talking to each other on the internet.

### **7. List and discuss the benefits of using Web Services.**
	**1.Exposing Existing Functionality:** Web services let your computer programs share what they can do over the internet. This means that other programs can use the things your program can do.

	**2.Interoperability:** Web services allow different programs to talk to each other and share information. For example, a program made with VB or .NET can communicate with a program made with Java. This makes programs work together even if they are made with different technologies.
	
	**3.Standardized Protocol:** Web services use a set of aggreed-upon rules for communication. These rules are the same for everyone, making it easier for different programs to understand each other. This standardization helps in offering a variety of choices, reducing costs and improving the quality.

	**4. Low-Cost Communication:** Web services use a standard protocol called **SOAP** over HTTP. This means they can use the regular internet for communication, which is usually cheaper. This is more cost-effective compared to other methods like **EDI/B2B**. Additionally, web services can work with other reliable methods like FTP for communication.

### **8. List and discuss the characteristics of Web Services.**
	
	**1.XML-Based:** Web services use XML for both representing and transporting data. This makes them independent of specific networks, OS or platforms. It also enhances interoperability allowing different systems to work together seamlessly.

	**2.Loosely Coupled:** Users of a web service are not directly tied to it. The web service's interface can change without affecting the client's ability to use it. This is different from tightly coupled systems where changes in one part require updates in the other.

	**3.Coarse-Grained:** Web services define wervices at a higher, more general level. This contrasts with the fine-grained approach of some technologies, where each method is a distinct service. Coarse-Grained services in web technology access the right amount of business logic for effective operations.

	**4.Ability to be Synchronous or Asynchronous:** Web services can work in sync or async modes. Sycnchronous operations mean the client waits for the service to finish before moving on while Asysnchronous operations allow the client to continue with other tasks or retrieve results later.

	**5.Supports Remote Procedure Calls (RPCs)** Clients can use web services to call procedures, functions and methods on remote objects through an XML-based protocol. The web service must handle the input and output parameters of these remote procedures.

	**6.Supports Document Exchange** Web services can exchange not only data but also complex documents using XML. These documents can range from simple things like addresses to more intricate items like entire books or business documents. This capability supports transparent document exchange for business integration.

### **9. List and discuss the distinct roles in Web Services Architecture.**

	**1.Provider** Is the one who creates and offers the web service. They develop the functionality or data that the web provides and make it available for client applications to use.

	**2.Requestor** Also known as the client application is the entity that needs to interact with a web service. It can be developed in various programming languages like .NET or Java.

	**3.Broker:** The broker serves as an intermediary in the **Web Service Architecture**. It provides access to the **UDDI (Universal Description, Discovey, and Integration)**, allowing client applications to discover and locate the web service they need. The **UDDI** serves as a directory or registry that stores information about available web services.

	**4.Publish** The provider informs the broker (service registry) about the web service they've created. This is done through the broker's publish interface. By using this interface, the provider makes the detail of teh web service available to potential clients.

	**5.Find:** The requestor consults the broker to discover information about available web services. Using the broker's capabilities, typically facilitated through UDDI, the requestor looks for published web services that match its requirements.

	**6.Bind:** With the information obtained from the broker about the web service, the requestor is now ready to bind or invoke the web service. Binding is essentially the process of initiating communication with the web service to access its functionality or retrieve the desird data.

### **10. List and discuss the Web Services Components.**

	**1.SOAP (Simple Object Access Protocol)** SOAP is an XML-based protocol used for communication between computers. It defines how to encode an HTTP heade and an XML file to facilitate communication between applications. SOAP is a platform and language independent allowing to run on any operating system.

	**2.WSDL (Web Services Description Language)** WSDL is an XML-based language used to describe and how to access them. It provides a standard way of documenting the functionalities of a web service and the process of accessing them.

	**3.UDDI (Universal Description, Discovery and Integration):** UDDI is an XML-based standard for describing, publishing and finding web services. UDDI is an open framework that is platform-independent and works in conjuntion with SOAP and WSDL as ont of the foundational standards of web services.

