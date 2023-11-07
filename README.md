# 6th November 2023
1. Computation - A computation is any type of arithmetic or non-arithmetic calculation that is well-defined. Common examples of computations are mathematical equations and computer algorithms.
   
3. Host - A host is a hardware device which has access to network via a user interface, specialised software, network address, protocol stack etc.
   
5. VM - is a digital version of a physical computer. Virtual machine software can run programs and operating systems, store data, connect to networks, and do other computing functions, and requires maintenance such as updates and system monitoring.
   
7. API's (Application Programming Interface) - API is a set of rules and tools which allows different software appliactins to talk to each other and work together. Different programs can interact and share information, making it easier to create complex and interconnected software systems. It helps different software programs communicate and collaborate with each other.
   
   TYPES-
   
   i. Private APIs - allows different parts of a software system to communicate and share information. It is not open to public, only authorised users can use this API. It helps keep sensitive data and functions secure while allowing them to work together smoothly.

   ii. Public APIs - A set of rules and tools provided by a company that allows the developers from outside the organisation to access and interact with their data. All third party developers have access to it.
   
   iv. Composite APIs - It allows developers to access and interact with various services. It acts as a bridge which brings together and coordinates the functions of other APIs.
   
   eg - soap api, **rest api**.

8. Networking - establishment of connections and pathways for transmitting information, both within local networks (such as your home or office network) and over larger-scale networks.
    COMPONENTS
      1. Address
      2. DNS Serevers
      3. Routing
  
9. OSI Model - is a guideline that helps different devices communicate with each other. <BR>
     7 DIFFERENT LAYERS <BR><BR>
           A. **Physical layer**: Actual hardware travel b/w devices. Eg- cables, bits(0s and 1s) <br> <br>
           B. **Data link layer**: Manages how data is sent and received within a local network, like making sure the right data goes to the right device. <BR> <BR>
           C. **Network layer**: Handles how data is routed across different networks, like the internet, and finds the best path for it. <BR> <BR>
           D. **Transport layer**: Takes care of how data is sent and received between devices, making sure everything arrives accurately and in the right order.    <BR> <BR>
           E. **Session layer**: It manages the communication sessions between devices, making sure they start and end properly. <BR> <BR>
           F. **Presentation layer**: Deals with the format of the data, like converting it to a readable form or encrypting it for security. <BR> <BR>
           G. **Application layer**: This is where specific programs and software work. It's where your web browser, email, or other applications exist, allowing you to interact with the network.

10. Kubernetes - is an open-source container orchestration platform developed by Google. It is used for managing and automating application container deployments across multiple machine clusters. It allows you to operate, schedule, monitor, and maintain containerized workloads.

11. CNI (Container Network Interface)- is a framework for dynamically configuring networking resources. It uses a group of libraries and specifications written in Go. The plugin specification defines an interface for configuring the network, provisioning IP addresses, and maintaining connectivity with multiple hosts.

12. NETWROK MODELS USED IN CNI- <br> <br>
      A. Encapsulated network - The model encapsulates a logical Layer 2 network over an existing Layer 3 network topology, which covers multiple Kubernetes nodes. Layer 2 network is isolated so there is no need for routing distribution. <br>
    Eg- Canal, Flannel, and Weave. <br. <br>
      B. Uencapsulated network - This model provides a Layer 3 network for routing packets between containers. There is no isolated Layer 2 network or overhead, but this is at the expense of Kubernetes workers, which must manage any required route distribution. <br>
    Eg- Romana, Calico.

13. Orchestrator - Orchestration is the coordination and management of multiple computer systems, applications and/or services, stringing together multiple tasks in order to execute a larger workflow or process. These processes can consist of multiple tasks that are automated and can involve multiple systems.

14. Hypervisor - A hypervisor aka virtual machine monitor or VMM, is software that creates and runs virtual machines (VMs). A hypervisor allows one host computer to support multiple guest VMs by virtually sharing its resources, such as memory and processing. 

15. Zero touch provisioning - 
16. zero trust security -                                                                        
      
    
  



PORT NUMBER:
FTP: 21 or 20

Port Forwarding



   
   













CDN, (Computation - host, VM, LXC), Storage, Cashing, Properties (scalable - autoscaler, reliability-A2), Isolation - namespace, CNI, VM-DVS, architecture, IAAS, KAAS, Type 1-KVM, type 2, Observabilty,
