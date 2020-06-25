# Hybrid_Cloud_Foundations
Nutanix Hybrid Cloud Training

## Chapter 1: Journey to the Modern Hybrid Cloud

1. What the role of a Hybrid Cloud Engineer is

2. The different models to support various Cloud initiatives

3. The Engineer’s role in Service Level Agreements related to Cloud apps

4. How to choose the optimal Cloud platform for an app, based on business requirements and SLAs

### What does a Hybrid Cloud Engineer do?

A hybrid cloud engineer can design, create, operate, and manage different types of workloads across multiple clouds and infrastructure providers.

The engineer should be able to:

* Consult and plan with business stakeholders
* Successfully execute this plan
* Validate outcomes through their technical skillset
The Hybrid Cloud Engineer helps organizations determine their readiness, and make suggestions if an organization isn't ready yet. One of the most important things to check is if business requirements are clearly defined. This is done through Service Level Agreements, or SLAs, need to be completely documented and enforceable. This is what you're going to use to choose the right infrastructure for every service.

This is followed by ```implementation```.

```Implementation``` involves planning and executing migration. This involves a few things like refactoring applications for the best possible Total Cost of Ownership, or TCO, and Return On Investment, or ROI. Once complete, the technical and organizational infrastructure needs to be continuously monitored to check if performance expectations that were created in the SLAs are met.

### Understanding the Cloud
NIST defines cloud computing as "a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources. For instance: networks, servers, storage, applications, and services that can be rapidly provisioned and released with minimal management effort or service provider interaction."

* With Infrastructure as a Service, or IaaS, you are only managing the workloads and applications that are running on virtual machines and containers.

* With Platform as a Service, or PaaS, you are only responsible for applications and their data.

* Finally, with a Software as a Service, or SaaS, model, every aspect of the infrastructure is provided to you. The only thing that you are required to manage is the data. Everything else is being managed by a provider.

Starting an organization's digital transformation:
1. How do you leave traditional IT behind and become a Cloud consumer?
2. How do you choose between application hosts? Infrastructure as a Service, Platform as a Service, or Software as a Service?
3. How does your choice impact workload design, deployment, management, and costs?
4. Can you leverage multiple models effectively?

### Application Design: The Monolith
When we refer to monolithic, we mean there is one, single source of every component in the stack.

* It is a single application written in a single language.
* It is run in a batch, or is constantly executed on a single instance of infrastructure.
* To address performance issues and bottlenecks, it is necessary to scale up by increasing compute, storage, and memory resources. These resources are always constrained to a monolithic server’s capabilities.
* The infrastructure is also monolithic. It is provided by a single vendor, who potentially also controls the application development tools, database, and operating system layers that are running on their hardware.

### Application Design: Distributed Web Scale
The Internet and open source software lowered application design costs and changed to being distributed over the network. The functionality became a separation of duties from being monolithic.

Three-tier web application includes:

* The web presentation-tier using JavaScript, HTML, and CSS
* The application logic tier using programming languages such as: Java, C++, Python, or Ruby
* A database cluster for persistence.

Micro-service architecture with further separation of tier function allows application architecture to evolve towards network APIs based on the web, called RESTful APIs, or REST APIs.

A customer request comes to a web load balancer.
The web load balancer directs the request to any of the web presentation tier members, in this case Web4, to show a web page which needs to display application logic served through the AppServer Load Balancer from the Application Logic Tier members, in this case from AppServer2. AppServer2, in turn, reads data from the database cluster, in this case: the Database3 instance.

Examples of these web-scale applications with a global reach are Facebook, Netflix, and Gmail.

### The Cloud Differentiator
In the State of the DevOps Report 2019, it was determined that the highest performing teams are 24 times more likely to execute on all five cloud capabilities, when compared to lower performing teams. The cloud, therefore, can be viewed as a differentiator for elite performers as well as a tool in general that drives high performance.

There are first two major aspects of cloud consumption that organizations need to take into consideration: fiscal consumption and workload predictability.

### Cloud Considerations: Workload Predictability

The public cloud is best for elastic workloads. The public cloud allows you to spin up or spin down resources to meet the workload’s demands quickly, easily, and efficiently when a workload is unpredictable.

The private cloud is great for predictable workloads. It is a secure and efficient way to run core workloads, with the agility and sit-back simplicity that IT teams want, and with the control that an organization needs for on-prem workloads.

Distributed workloads across public and private cloud still allows you to control and manage them centrally. The overall management of your deployment is simplified this way.

### Organizational Readiness Fundamentals

Almost every business has a cloud transformation plan. Problems for businesses executing their digital and cloud transformation plans can be caused by their organizational models. Organizational models can refer to how an IT department is structured for example and how technology is actually used. These two models speak to organizational readiness. Organizational readiness refers to how ready a business is to execute their cloud transformation plan successfully.

Why do business think about fiscal consumption and their workload predictability? Usually, those conversations begin when a business is considering making the transition to the cloud.

One of the most important parts of the process is gathering detailed information and knowing the key stakeholders early on. There are different IT domains to learn as well as what they do to deliver business services.

### What is Cloud Readiness?
* A low cloud readiness score means that technology and workforce skills are more traditional. This means the current environment is used exclusively to run legacy, shrink-wrapped applications.

* High cloud readiness means that the technologies and workforce skills that support IT are aligned with what is required to successfully use the full capabilities of the public, private and hybrid cloud. A good example of this scenario is if catalog-based self-service is available to users.

### Cloud Smart, Not Cloud First
Cloud Smart is about rationalizing applications, infrastructure, skills, and people across hybrid clouds and ensuring everything is where it fits best.

You can leverage the essential characteristics of the cloud over various deployment models by looking at the cloud as an experience and a mindset. Since everything is on demand, it doesn’t take ten hours or six months to get a cloud result. Rapid elasticity with service measurements allows these organizations to understand how well they’re managing their on-prem and off-prem resources.

### Legacy IT: The Mainframe
The mainframe is monolithic architecture that first appeared on the computing landscape in the 1940s.

There are several reasons for the mainframe’s continued popularity.

* The enormous resources and computing power that is provides via its monolithic, converged architecture. It is, for example, 18 times faster than an x86 platform.
* It also provides decades of uptime and provides high levels of security.
* It also supports virtualization, which is an increasingly critical element of computing infrastructure today.

Despite its many advantages, the mainframe isn’t the perfect solution for all computing needs.

* Having access to the extensive amount of resources a mainframe provides requires a massive capital investment.
* Mainframes only get more expensive when they need to scale, because their monolithic architectures require massive blocks to expand.
* There’s also the concern of vendor lock-in, due to the use of proprietary hardware and software.
* Finally, operating, managing, and maintaining such a complex piece of computing technology requires highly specialized skills.

### Legacy of IT: Distributed Computing
In the 80s, there was a need for departmental computing, which coincided with advances in memory, storage, software, LAN, and WAN technologies.

Advantages
* The low cost, making the barrier to entry very low. This was a dramatic change from the enormous investments required to stand up a mainframe.
* By design, these systems were also easier to scale, making it much easier to expand an environment to meet growing needs. Most standards were open and because hardware and software were commoditized, businesses had a wealth of choices when making purchases.
* Since these were commoditized systems, niche skills were no longer needed to operate and manage them.

Disadvantages
* Underutilization was the norm, which resulted in low return on investment, and high total cost of ownership.
* Despite being scalable, these systems were not highly available, opening businesses to the risks of downtime and data loss.
* The inherent scalability of the distributed systems also led to sprawl, which made them difficult to secure and manage.
* Finally, because of the sheer number of components involved in different systems, IT organizations experienced sprawl as well, becoming disjointed and siloed.

### Legacy IT: Centralized Storage and 3-tier
Centralized storage, as the name suggests, involves high volume, shareable storage that can be accessed by multiple servers over the network. It provides standalone servers with pools of storage and data protection via multiple network paths, multiple storage processors, and RAID protection at the disk level.

* A Storage Area Network is a dedicated, specialized, high speed network that provides access to block-level storage. A SAN typically consists of hosts, switches, and storage devices, all connected to each other.
* A NAS is a storage device that is connected to a network and allows data to be stored and retrieved from a centralized location. NAS devices use Ethernet to access shared storage devices at the file level.
* Centralized storage works with distributed computing to create the 3-tier infrastructure architecture that is popularly used in datacenters today. In this computing model, servers and storage are separate entities, connected through a storage network.

Advantages
* Centralized storage solved the data availability problem that was caused by distributed computing.
* The ability to add storage separately from computing resources also meant that companies could scale storage to meet the needs of their growing data.
* An added benefit was that application high-availability became easier in distributed environments, because centralized storage facilitated shared disk access for clustering.

Disadvantages
* Storage array and network management became a specialized IT domain, resulting in the need for specialized skills.
* As centralized storage increased in sophistication, it also brought increased complexity via concepts like SAN fabrics, WWPNs, RAID groups,volumes, spindle counts, and so on.
* The flexibility to add storage separately from computing meant that scaling was also uneven – storage was scaled in large blocks, while servers were scaled in smaller increments.
* This resulted in large CapEX commitments when storage was needed. Since storage was purchased in large blocks, it could sometimes take years to fill the available disk space, resulting in very long time to value.

### Legacy IT: x86 Virtualization
* Virtualization uses an abstraction layer and resource scheduler called a hypervisor to run virtual machines on shared hardware resources. Virtual machines, or VMs, can be run at 80% or higher resource utilization without contention, solving one of the major problems of distributed and 3-tier architecture.

* x86 hardware is a good fit for virtualization because, since the mid 2000s, each generation of the x86 processor has added features to improve virtualization performance. The latest generation supports virtualized network, storage, and server infrastructure, with performance that matches dedicated Application Specific Integrated Circuit, or ASIC-based hardware.

Advantages
* The ability to utilize 80% or more of the available infrastructure resources meant that businesses also experienced huge ROI gains with drastically lower TCO.
* An added benefit was that VMs could be moved between hosts without downtime, and operational processes such as cloning, deployment, backup, and recovery of servers and applications were simplified.

Disadvantages
* VM sprawl and the need for high availability resulted in high demands on storage and network resources.
* If VM sprawl goes unmanaged, it can result in more complexity and increased costs.
* Mixed environments – which include both virtualized and non-virtualized workloads – can result in even more management complexity.

### Legacy IT: Hybrid Cloud Readiness

If an organization is using a mainframe to:

* Host a private cloud
* There is modern application development
* A supporting DevOps team
* If it is used for Blockchain, AI, or Big Data integrations
Then cloud readiness is high.

However, if the organization primarily runs monolithic applications with no provision for integrations with modern applications in the private or public cloud, then cloud readiness is low and making the transition will be difficult.

Similarly, with distributed computing and 3-tier infrastructure, cloud readiness is high if there’s:

* Heavy use of virtualization in the organization
* Management of infrastructure and applications is centralized
* App development is modernized
* The public cloud supports and supplements on-prem infrastructure.

However, if the infrastructure is primarily bare-metal servers with legacy, shrink-wrapped applications, or if the IT organization is disjointed, then cloud readiness is low.

### Legacy IT: The Software Defined Datacenter (SDDC)

A SDDC is an integrated abstraction layer that defines a complete datacenter by means of a layer of software that presents the resources of the datacenter as pools of virtual and physical resources and allows their composition into arbitrary user-defined services. 
A modern SDDC deployment is defined by virtualized, software-defined resources that can be scaled up or down as required and can be deployed as needed in a number of distinct ways.

There are three key components to the SDDC:
* Software defined computing
* Software defined networking
* Software defined storage
* There's also often a fourth layer known as the orchestration management layer. "The intelligence that enables the operations team to do the initial configuration in terms of defining the virtual machines, the storage, the network interconnections, and if they need to, support a specific application or set of applications."

SDDC allows for huge gains in productivity through API-addressable management, automation, and orchestration tools with virtual switches, firewalls, load-balancers, and other devices running on the hypervisor.

In 3-Tier SDDC implementations the shared storage may be logically pooled, but the devices are still hardware-based, SAN or NAS, and separated from physical servers by a dedicated network. This means that SAN, NAS and the networks supporting them are typically outside the natural SDDC management plane and must be managed separately.

SAN and NAS also scale in big blocks while the rest of the SDDC scales per server. This can lead to huge blocks of storage resources sitting idle for extended periods of time. It doesn’t make sense economically to have such a large mismatch between the way servers and storage need to scale. And finally, 3 Tier SDDC is only 66% converged by design. This means you’re missing a full one-third of the power of SDDC!

These tools provide a number of benefits, including:

* Consolidated infrastructure and user management
* Automated lifecycle management
* Increased security through network segmentation and traffic inspection
* Automatic scale out of VMs on demand
* Failover and failback
* Configuration management
* Automated updates, health checks
* Chargeback for resource usage

Cloud readiness will be high if there is:

* Catalog-based self-service available to users
* A DevOps initiative
* Micro-serviced-based application architecture is in use
* Containers are being used for some applications.

Cloud readiness will be low if:

* The current SDDC environment is used to run legacy, shrink-wrapped applications exclusively
* The IT staff managing the physical infrastructure is still siloed and segregated based on the 3-tier model

### The Rise of Public Cloud
Advantages
* It is available on-demand.
* When you do need to provision infrastructure it’s all self-service and catalog-based.
* You can provision infrastructure at massive scale.
* Low cost to entry. There’s no hardware cost and you pay-as-you-go for utilization.
* High resilience and availability.

Disadvantages
* Lift and shift. Moving applications and services to the public cloud is a lift-and-shift effort.
* Refactoring apps. Refactoring applications for the cloud requires both skill and a sizable budget.
* Readiness and Management. Organizational readiness and infrastructure management may be significant issues for an organization.
* Expensive for Always-on Apps. The pay-as-you-go model isn't always a good fit for every workload; always-on, heavyweight applications are expensive to run.
* Regulatory requirements. Regulatory requirements can make it difficult to impossible to move forward with a public cloud initiative. Some requirements limit where data can reside, and if you lose control of your cloud or the data stored there, you can incur heavy penalties as a result.

The Public Cloud is excellent for:
* Dev/Test
* Web servers
* One-off Big Data projects
* Training infrastructure
* Cloud-based anti-spam and anti-virus engines
* CRM platforms
* Email

All these workloads are lightweight or they only run for a portion of time.