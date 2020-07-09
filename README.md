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

### Hyperconverged Infrastructure (HCI)
Hyperconverged Infrastructure (HCI) converges the entire datacenter stack, including compute, storage, networking, and virtualization. Some key points to remember about HCI are:

* Software running on each server node distributes all operating functions across a cluster. This allows incremental scaling, so that a cluster can be grown one node at a time; performance increases as the environment grows.
* The software also creates clusters and pools local storage, eliminating the need for SAN or NAS infrastructure​.
* The removal of the physical storage fully unleashes the power of the SDDC.
* The use of solid state drives (SSDs), combined with data locality, provides excellent cluster performance without bottlenecks.

Note that unlike its 3-tier incarnation – which was only 66% converged – HCI is fully converged.

SSDs and HCI
The key points to remember about SSDs and HCI are:

* SSDs improve performance of the storage tier if they are * bottlenecking on read-write performance at the disk level.
* To leverage the extreme advances in performance, the controllers and network need to be able to handle the vast I/O capabilities of SSDs.
* Data locality is a key component of HCI; not having to transit the network provides better utilization of an SSDs capabilities.

HCI and Private Cloud
Out of the box, HCI isn’t a true private cloud. To have a fully operational private cloud, you also need to have:

* Unified management support
* One-click upgrades
* Customizable security
* Built-in data services for file, block, and object storage
* Sophisticated backup and disaster recovery solutions
* Tools for automation and self-service; and cost governance

Hybrid Cloud Readiness
Your cloud readiness will be high if:

* A Private Cloud is deployed on the HCI
* There is catalog-based self-service available to users
* There is a DevOps initiative and micro-service-based application architecture is in use
* Containers are being used for some applications,
* The use of the Public Cloud is being considered to supplement the infrastructure where appropriate
* In contrast, you can have an HCI deployment but still have low cloud readiness if:

* An HCI deployment is being used exclusively to run legacy, shrink-wrapped applications
* Automation and orchestration tools are not being leveraged
* There is no supplemental use of Public Cloud

### Hybrid Cloud: Hybrid Cloud: When To Use It And When Not To

Remember, hybrid cloud is not a good fit when:

* A business has non-portable applications
* Security and regulatory compliance requirements do not allow public cloud exposure
* Delegation of management responsibilities to a service provider is not allowed
* The Public Cloud is too expensive

For businesses born in the public cloud, a hybrid cloud does not make sense without the ability to invest in private, on-premises infrastructure, a supporting operations team, and ongoing skill growth.

Examples of where the hybrid cloud is a good fit are:

* Workloads with constantly changing populations
* Large scale workload management
* Short-lived ephemeral workloads
* Dev/Test
* Training infrastructure
* Anti-spam and anti-virus engines
* CRM platforms
* E-mail
* Web servers
* One-off big data projects

### Cloud Smart Examples

A Data Processing Firm
This data processing firm had strict governance requirements that their customer data remain on-premises, so they had a private cloud hosting their data lake of customer data. However, they wanted to burst compute capacity for large end-of-the-month, quarterly, and annual reporting. So, they provided a virtual private network between their public and private clouds.

This allowed them to spin up and scale out analytics with high memory and GPU-accelerated public cloud infrastructure, save the results back on-prem, and then shut-down the analytics workloads. Because of the shared data, their analytics is a hybrid cloud application, even though the workload mainly runs in the public cloud.

A Retail Outlet Business
This retail outlet business with many remote locations had local services (file and print sharing) in each store, but it used private networks to its private cloud datacenter for virtual desktops. This is how the IT organization has slowly modernized its infrastructure at the edge and in the datacenter.

A new initiative for a data lake with analytics kicked off and a team with skillsets favoring the public cloud got their project up and running quickly. The organization is running with both public and private infrastructure. None of the applications or data are shared though, so each cloud is a silo, and it is not a hybrid cloud model.

An E-Commerce Company
This e-commerce company has a large inventory and customer database that they keep on-prem. They backup this database to the public cloud, but this is hybrid cloud storage use. If you’re wondering why, it’s because they operate the database application on-prem, and back-up the database itself to the public cloud. So, true to the hybrid model, there’s some sharing going on here.

Their developers use multiple public cloud compute for rapid and short-lived test workloads. This means they’re using multiple public clouds in a cloud-smart manner, but no data or applications are shared. This makes each public cloud a silo and it is not hybrid cloud use. Finally, they operate their web tier by load balancing across on-prem web servers and public cloud web servers, which is a hybrid cloud web tier.

What do these examples demonstrate?
Ultimately, to be truly hybrid is to not have silos. But it’s also possible – as the e-commerce company illustrated – to be cloud-smart and not hybrid. Workloads that were the right fit for the public cloud were on the public cloud, and those that needed to be shared between on-prem and public were.

What matters is the best fit. Where a workload belongs is where it should be, based entirely on what’s best for the business.

### Gathering and Analyzing Business Requirements
Throughout this lesson, we’ve talked a lot about best fit—and insuring a good fit requires talking to your stakeholders. This will give you a 360-degree view of the workloads and services you need to support.

When you’re having that discussion, it’s important to structure the conversation around 8 major requirements:

* Application portability
* Compliance and security
* Cost, including TCO and ROI
* Scalability
* Resilience and availability
* Performance
* Manageability
* Data protection and recoverability
* Let’s look at each of these requirements in a little more detail.

Deeper Dive: Application Portability

Application portability describes how easily an application can be moved between different kinds of infrastructure.

* Applications that are designed with portability in mind (e.g., containerized applications) do not require major refactoring in order to move from private to public cloud providers.
* In contrast, monolithic applications require an expensive “lift and shift” process in order to move between different platforms or even to change hypervisors.
* Another approach is to employ a data-centric strategy, where you share data between services running on multiple cloud platforms without porting applications between them. This avoids "lift and shift" campaigns and leverages applications designed to take advantage of native infrastructure and toolsets.

Deeper Dive: Compliance and Security

Companies are subject to many regulations regarding security and data-handling—and these regulations can have a significant impact on how you utilize the cloud. These are some of the main regulations that it’s important to be familiar with:

* GDPR: The General Data Protection Regulation (GDPR) protects EU citizens from data breaches and misuse. It applies to all companies with data for EU citizens, even if those companies are not located in the EU.

* HIPAA: The Health Insurance Portability and Accountability Act (HIPAA) regulates the data security of healthcare patients. Companies that handle healthcare data (e.g., hospitals, clinics and insurance companies) are required to comply with HIPAA regulations.

* Sarbanes-Oxley Act (SOX): The Sarbanes-Oxley Act (SOX) requires U.S. company boards, management, and accounting firms to follow best practices and maintain financial records for seven years. The intent is to prevent incidents like the Enron scandal.

* FISMA: The Federal Information Security Management Act of 2002 (FISMA) treats information security as a matter of national security. All federal agencies are required to develop compliant data protection methods.

* PCI-DSS: The Payment Card Industry Data Security Standard (PCI-DSS) regulations reduce fraud by protecting customer credit card information. PCI-DSS compliance is required for all companies handling credit card information.

* GPG13: The Protective Monitoring for HMG ICT Systems regulation (GPG13) is a U.K. general data-protection regulation for business processes. It is compulsory for businesses managing high-impact data.

Deeper Dive: Cost (TCO and ROI)

When comparing the public cloud with on-prem hybrid cloud infrastructure, it's important to consider the Total Cost of Ownership (TCO) and Return on Investment (ROI).

* Because public cloud infrastructure is rented (not owned), it has no upfront capital cost—and can thus seem better than investing in on-prem hybrid cloud infrastructure.
* However, the public cloud requires significantly more operating expenditure; thus, despite the higher up-front costs, the hybrid cloud can have significantly better long-term TCO and ROI.

Deeper Dive: Scalability

The need to scale an application or the resources supporting an application up/out can be driven by:

* An increasing number of users
* Increased demand from existing users
* A growing data set
* Increased computational complexity

In addition, many workloads are cyclical, requiring the ability to scale up/out during periods of high demand and pull back during periods of low demand. Monolithic applications require different scale up/out strategies than modular or micro-service-based applications. If application design and other requirements permit, it is possible to have individual application components or application tiers running on Private and Public Cloud simultaneously.

When you need to decide on a scaling strategy, it’s important to consider:

1. The application architecture. Is it legacy-monolithic, multi-tier, modular, or micro-services based?
2. What the the triggers points for scaling up or scaling out are?
3. Seasonality and complete demand cycles

Deeper Dive: Resilience and Availability

Applications need to be designed for resiliency, meaning that they can suffer a failure or degradation in one or more components and still provide service.

* Applications must take the infrastructure providing resources into account.
* Many organizations implement software across multi-tier, multiple technology infrastructures, which can make designing for resilience more complicated.
* Resilience can be provided at any or every layer of the stack.

Resilience goes hand-in-hand with availability, but availability requirements need to be clearly defined.

* For example, hardware or operating system availability does not necessarily translate to application availability.
* It’s common to underestimate the cost and complexity of providing availability, as well as overstate availability requirements.
* Understanding what’s required is critical to determining the right infrastructure for a given workload or service.

Deeper Dive: Performance

Performance has many dimensions and dependencies, and this portion of the stakeholder conversation will likely result in a large variety of requirements. You’re likely to hear about application response times, storage performance, CPU and memory requirements for workloads, and so on.

When rolling in performance data, it’s important to be mindful of the breadth and complexity of this particular requirement. For example, application response time can be influenced by network architecture, CPU type, storage architecture, or memory type. In a multi-tenant environment, CPU saturation, storage contention, or memory oversubscription can degrade performance.

Deploying multi-tiered applications requires careful planning, especially if the infrastructure is hybrid. In the case of multi-tiered applications, performance will only be as good as the least performant tier.

Deeper Dive: Manageability

Infrastructure and application manageability is greatly influenced by tool integrations and the availability of automation for routine and repetitive tasks.

Lack of manageability can drastically increase OPEX and degrade performance of a Private Cloud. It is especially detrimental in Hybrid Cloud deployments when tasks such as updates, troubleshooting, and scaling are delayed or fail outright.

It’s also important to consider the relative complexity of a workload from the perspective of manageability. Does it need to be on-prem because every aspect needs to be managed, or can a provider be trusted to manage a part of it?

When gathering requirements and planning your strategy, remember that a well-designed management plan show allow for SLAs to be met and monitored, in order to verify performance.

Deeper Dive: Data Protection and Recoverability

Every application or service will have specific requirements for data protection and recoverability. At a minimum, you should determine and document the requirements for each application and service in terms of:

* The Recovery Time Objective (RTO), which refers to how long an application can be down without causing damage to the business
* The Recovery Point Objective (RPO), which refers to how much data can be lost before damage to the business occurs.

100% uptime (RTO) with no lost data (RPO) requires an investment in continuous data replication and mirrored infrastructure, but not every application or service will require this level of protection. When 100% uptime requirements or zero data loss requirements do exist, cloud-based options for backup and recovery can provide low-cost alternatives.

### Turning Business Requirements into SLAs
Once you have the answers to all of your questions, you’ll have the framework and requirements of your solution. You will also have successfully mapped out the attributes of your required solution to specific business needs.

Taking these attributes and turning them into SLAs will provide a performance framework that can be monitored, managed, and enforced. These attributes and SLAs will also help with vendor evaluation. You’ll have a checklist you can use to determine whether a solution provider can meet your needs and at what cost.

If modifications are needed to any aspect of the requirements, you can perform a cost-benefit analysis, determine the impact, and move forward with whatever is best for the business.

### Lesson Recap
In this lesson, we covered:

* What the role of a Hybrid Cloud Engineer is
* The different models to support various Cloud initiatives
* The Engineer’s role in Service Level Agreements related to Cloud apps
* How to choose the optimal Cloud platform for an app, based on business requirements and SLAs

## Chapter 2: Introduction to Nutanix Hyperconverged Infrastructure

1. The what and why of Nutanix HCI
2. The components of a cluster
3. The software components of a Nutanix cluster
4. How to work with the Prism interface

### Why Nutanix HCI?
Quick Review of the Legacy Infrastructure

There are a few reasons legacy infrastructure is not well suited to meet the increasing requirements of enterprise applications or the fast pace of modern business:

* The silos created by traditional infrastructure have become a barrier to change and progress, adding complexity to every step of the IT process from ordering to deployment to management.
* New business initiatives require cooperation from multiple teams. They also need organizations to predict IT infrastructure 3 to 5 years in advance. For context, this is pretty hard to get right.
* Vendor lock-in and rising licensing costs are significantly increasing budgets.

HCI addresses these pain points by combining standard datacenter hardware using locally attached storage resources with intelligent software to create flexible building blocks. These flexible building blocks can replace legacy infrastructure with separate servers, storage networks, and storage arrays.

Benefits of the Nutanix HCI

Nutanix provides the public cloud benefits that organizations want with the control that they need on-prem. There are six major benefits to Nutanix HCI specifically:

* Full-cloud: It’s a full-cloud stack that integrates all compute, storage, virtualization, and networking resources to run any application.

* One-click simplicity: This entire stack is managed via a single pane of glass that streamlines IT lifecycle management and makes hybrid and multi-cloud management easy .

* Deployed in minutes: The applications themselves can be deployed in minutes, instead of weeks or months. This is true for new infrastructure as well.

* Automation application management: Application management can also be automated, along with other common IT tasks. Application owners and developers can also be given on-demand IT services.

* Lower cloud costs: You can also reduce your datacenter TCO by up to 60%. This will help optimize your public cloud spend with lower cloud costs.

* True hybrid cloud: This refers to the ability for you to combine both public and private cloud operations with unified management.

### What is Nutanix HCI?

Nutanix HCI is fully software-defined, which is required from a true HCI solution. This means that the intelligence of the solution comes from the software, which runs on a variety of hardware platforms.

There are two key components to the software:

1. Acropolis: The data plane
2. Prism: The management plane

This software can be run on a number of different servers, from manufacturers such as Dell, Lenovo, HPE, Cisco, IBM, Inspur, and so on. In general, the hardware platforms themselves are structured as nodes, blocks, and clusters.

### Hardware Components: Nodes, Blocks, and Clusters

A node is an x86 server with compute and storage resources. A single Nutanix cluster can have an unlimited number of nodes. Different hardware platforms are available to address varying workload needs for compute and storage.

Each node in the cluster:
* Runs a standard hypervisor
* Contains processors, memory, and local storage such as SSDs and hard disks.
* A Nutanix Controller VM that enables the pooling of local storage from all nodes in the cluster.

All nodes in a Nutanix cluster converge to deliver a unified pool of tiered storage and present resources to VMs for seamless access. A global data system architecture integrates each new node into the cluster, allowing you to scale the solution to meet the needs of your infrastructure.

A block is a chassis that holds one to four nodes, and contains power, cooling, and the backplane for the nodes. The number of nodes and drives depends on the hardware chosen for the solution.

A cluster is a collection of multiple blocks. It refers to the physical servers, logically associated with one another, that deliver a unified pool of infrastructure resources. It can handle the failure of a single node when specific cluster conditions are met. In the case where multiple nodes in a block fail, guest VMs can continue to run because cluster configuration data has been replicated on other blocks.

A Sample Block
This graphic shows a 4-node block in which each node takes up one node position identified as A, B, C, or D. In this block chassis example, the node ports are accessible from the rear of the chassis and the storage is at the front. A Nutanix block is a rack-mountable enclosure that contains one to four Nutanix nodes. It can handle the failure of a single node when specific cluster conditions are met. In the case where multiple nodes in a block fail, guest VMs can continue to run because cluster configuration data has been replicated on other blocks.

Sample Cluster
What you see here is a visualization of a cluster, with both its physical and logical components highlighted. This particular example contains three nodes, each of which has a controller VM, locally attached storage, and has guest VMs running. All of the locally attached storage is presented as a single pool to the guest VMs, via the Controller VM.

### Software Components: Acropolis

Acropolis is a distributed data plane for either VMs or container-based applications that runs across a cluster of nodes delivering enterprise storage and virtualization services. Acropolis is also the foundation of an HCI solution that transforms HCI into a Hybrid Cloud OS.

Here are the main components:

* The Distributed Storage Fabric (DSF)
* The Acropolis Hypervisor (AHV)
* Scale-out storage services
* Advanced virtual networking

Let's take a look at each of these below!

Acropolis: Distributed Storage Fabric

Here is a representation of the Distributed Storage Fabric (DSF). The DSF simplifies storage and data management for virtual environments, by pooling flash and hard disk drive storage across a Nutanix cluster and exporting it as a data store to the virtualization layer as Small Computer Systems Interface (iSCSI), Network File System (NFS), and Server Message Block (SMB) which are all different ways of data sharing.

DSF offer capabilities:

* Snapshots
* Compression
* Cloning
* Data locality
* Deduplication
* Erasure coding
* Tiering
* Replication

Acropolis: AHV

Acropolis Hypervisor (or AHV) is a comprehensive virtualization solution that’s included as part of the Nutanix solution, bundled with Acropolis.

AHV is the virtualization layer in the illustration example. It enables a variety of key capabilities including:

* Backup
* Disaster recovery
* Host and VM high availability
* Dynamic scheduling

Acropolis: Scale-out Storage Services

Nutanix allows you leverage scale-out, fully software-defined storage services via Nutanix Files, Nutanix Volumes, and Nutanix Objects.

* Nutanix Files file services provides access to Microsoft Windows via SMB 2.1 and to Linux and Unix via the NFS v4 protocol. It also scales and load balances multiple nodes in the cluster, growing capacity and performance as needed.
* Nutanix Volumes block services provides iSCSI access to applications that require direct access to block storage. This can be non-virtualized systems, or virtual machines with specific requirements. Volumes uses the DSF to scale I/O across the entire cluster and can load balance and accelerate specified Volume Groups.
* Nutanix Buckets object storage services is a software-defined object storage solution that non-disruptively scales out while lowering overall costs. It supports an industry-standard S3-compatible REST API to handle petabytes of unstructured data.

Acropolis: Virtual Networking

Nutanix Flow:

* Delivers advanced networking and security services, providing visibility into the virtual network, application-centric protection from network threats and automation of common networking operations.
* Allows organizations to deploy software-defined virtual networking without having to install and manage additional products that have separate management and independent software maintenance requirements.
* Provides detailed visualization of communications between VMs, making it simple and straight-forward to set the right policies for the environment.
* Micro-segmentation provides granular control and governance of all traffic into and out of a VM, or groups of VMs. It ensures that only permitted traffic between application tiers or other logical boundaries is allowed and protects against advanced threats propagating within the virtual environment.
* Provides API-based notifications enabling third-party network devices to observe VM lifecycle events, such as the instantiation of a new VM into the Nutanix environment.

### Software Components: Prism
This is Prism, the single dashboard from which you can manage your entire Nutanix solution.

Prism is a distributed management plane that uses advanced data analytics and heuristics to simplify and streamline common workflows, eliminating the need for separate management solutions for servers, storage networks, storage, and virtualization. It provides a unified management interface that can generate actionable insights for optimizing virtualization, provides infrastructure management and everyday operations.

In Prism, Nutanix administrators can easily manage and operate their end-to-end virtual environments.

Just as Acropolis creates a data plane that spans the entire cluster for performance and resiliency, Prism creates the same resiliency for management and operational intelligence.

The information in Prism focuses on common operational tasks grouped into four areas:

* Infrastructure management
* Operational insight
* Capacity planning
* Performance monitoring

Prism is a single interface that eliminates the need for separate management solutions for servers, storage networks, storage, and virtualization. It generates actionable insights for optimizing virtualization, provides infrastructure management and everyday operations.

### Prism - Infrastructure Management: Cluster Management
Four Common Operational Areas
1. Infrastructure Management
2. Operational Insight
3. Capacity Planning
4. Performance Monitoring


Infrastructure management refers to cluster management, upgrades, storage management, virtual machine management, networking, data protection, entity management, user management, localization, and a handful of other key features.

Cluster management refers the overall view of your entire cluster that you see on the Prism home screen.

The Home dashboard is a summary overview of your Nutanix cluster:

* A count of blocks and hosts with model numbers
* A summary of storage
* VMs
* Hardware
* Cluster-wide controller IOPS
* Latency
* CPU usage
* Memory usage
* Alerts and events

Infrastructure Management
There are a lot of different dashboard available to you here depending on what type of information you'll need. We'll go through some of these dashboards during the course, but here's an opportunity to see what the options are. The Home drop down menu has a number of dashboards you can explore, each tailored around providing details on a specific area of your cluster.

### Prism - Infrastructure Management: Storage Management
Storage Dashboard: Overview
The Storage dashboard view shows you an overview of the storage environment, important performance charts, data reduction metrics, capacity summaries, and important alerts and warnings. If an administrator needs more details about certain storage services, then they can use the table view.

This screen provides three views that offer insight into the storage constructs within a cluster:

* Volume groups
* Containers
* Storage pools

The table view displays the configuration settings for each container, capacity metrics, and several performance charts.

The different views of the Storage dashboard are fundamentally the same, each view allows you to interact with and drill down into various components in different ways. The table view puts the storage containers, volume groups, and storage pools front and center. It provides a number of details at a glance about each of these components:

* Controller IOPS, total capacity, free and used capacity, status of various space optimization features, and more.
* Usage and performance summaries, as well as storage alerts and events.

The information you need from the Storage dashboard will determine which view you'll use and interact with.

From the Storage dashboard, you can also create new Storage Containers and new Volume Groups by filling in details in a simple form based on your requirements.

### Prism - Infrastructure Management: Virtual Machine Management
VM Dashboard: Table View
The VM Dashboard provides the same kind of overview summary that the cluster and storage management views offer.

* The VM summary delivers VM counts as well as VM power status.
* Highlighted CPU and memory usage statistics focus on provisioned amounts versus reserved amounts.
* You can also see the top VM consumers for IOPS, latency, memory usage, and CPU usage, enabling you to identify which VMs are using the most resources and detect any outliers.

VM Dashboard: Table View
Following the user experience in the other sections, the VM-focused view in Prism also offers a table-based layout for VM management. Similar to the detailed host data in the cluster view, the VM-based view provides a greater number of VM-focused data points.

This VM-focused view allows organizations to easily compare the CPU and memory settings configured versus the actual amounts of CPU and memory used. You can also access storage metrics for read versus write IOPS, combined IOPS, storage bandwidth, and latency. Prism tracks each of these data points on a per-VM basis to give a quick overview and locate potential issues faster.

### Prism - Infrastructure Management: Data Protection
While there are many other dashboards in Prism, the last one we’ll talk about in this section is the Data Protection dashboard. The data protection overview summarizes the number of remote sites and protection domains, giving you a quick look into the cluster’s data protection. Charts report replication data transfer bandwidth, as well as a list of the top remote sites by bandwidth consumption. This report lets an organization easily understand the bandwidth that replication is consuming, whether something is operating abnormally, and which sites use the most resources. Administrators also gain awareness of ongoing replication, pending replication, and successful replication tasks, so they can recognize if any tasks are being held up or simply verify that replication is completing successfully.

Data Protection Dashboard: Table View
The data protection table view summarizes the configuration, performance, and status of the protection domains that provide backup and disaster protection in your cluster. From this view you can see how many resources each protection domain consumes, what is contained within a protection domain, when taking a snapshot was last successful, and if there are any pending jobs. When you select a specific protection domain or remote site, a greater amount of data becomes available through additional charts and tables. These entity-specific data points provide extensive details on the contents, schedules, alerts, and metrics for each item.

Creating Protection Domains and Remote Sites
Again, creating protection domains and remote sites involves filling a form with details, after which both entities will be created for you. A protection domain is a set of policies that govern the local backup and remote replication functions for one or more VMs. A schedule attached to each protection domain controls the rate at which snapshots are taken and how long they are retained. This architecture allows you to create protection domains that can protect either a single VM or groups of VMs. The flexibility to use multiple protection domains within a cluster means that you can create different policies to protect diverse applications and groups of VMs, and control replication to different sites and clusters.

### Prism - Managing a Nutanix Cluster: Operational Insights
The second of the four key areas in which Prism helps organizations manage their Nutanix clusters is operational insights. Operational insights focus on providing administrators with alerts, metrics, and the ability to analyze data. As with infrastructure management, this also involves a number of different dashboard and Prism capabilities, including:

* Alerts and user-created alerts
* Alert-driven root cause analysis
* Analytics
* Analysis
* Network visualization

Operational Insights: Alerts Dashboard

Alerts Dashboard: Alerts View
Alerts in Prism provide administrators with information about informational, warning, and critical alerts. The Alerts dashboard has two views – Alerts and Events. The Alerts view presents all notifications and events in an easy-to-consume table format. The table presents each alert with a color-coded severity level, a description of the alert, a timestamp, which entities the alert involves, and cause and resolution guidance.

Alerts Dashboard: Events View
The Event view displays a list of event messages. Event messages describe cluster actions such as adding a storage pool or taking a snapshot. This view is read-only and you do not need to take any action like acknowledging or resolving generated events.

### Prism Operational Insights: Analysis Dashboard
The Analysis dashboard stacks multiple charts and lines them up in time sync.

Above the stack of charts, Prism adds all alerts and events, represented with colors and counts. This visual layout lets an administrator click on a chart at any point in time, placing a vertical line stretched through all charts for easy correlation. By focusing on a specific point and syncing all metrics, administrators can reduce the effort it takes to identify possible root causes. The rightmost column of the screen provides a summary of any alerts and events, so you don’t need to leave the analysis page.

The analysis view allows you to fully customize the number and size of the analytical charts you see and to add charts to your screen or remove them as needed. You can export each chart to a .csv or .json file.

### Prism Capacity Planning: Capacity Runway
Capacity planning is available as part of Prism and focuses on consumption from three resource buckets:

* Storage capacity
* CPU
* Memory

Capacity results are illustrated as a chart that shows the historical consumption for the capacity metric along with the estimated capacity runway. The capacity runway is the number of days remaining before the resource item is fully consumed. The Capacity Runway view provides overall and detailed runway information for each cluster managed by Prism Central. Clicking any of the clusters listed in the row will allow you to view more detailed information.

In this case, for example, we can see the total runway, and we can click to view:

* Specific storage
* CPU
* Memory details

On the Storage Runway view for DEMO-AHV, as seen here, we can view runway details either by usage or by storage container. On the CPU and memory pages, we can view details either as an overall view or by host.

Finally, hovering over the any point in the chart will show you projected capacity and runway information for that point in time. For example, as we’re seeing here, live usage has gone up from 1.07 TiB to 5 TiB, and Snapshot Usage has increased from 124.06 GiB to 282 GiB.

### Prism Capacity Planning: Scenarios
The other major capability of Prism’s Capacity Planning is scenario creation. Scenarios allow you to create projections and estimates of resource utilization over a period of time, if you were to add new workloads, or both.

Creating a Scenario
Creating a new scenario presents you with a number of different options. Here, we’re trying to create a scenario to determine resource utilization in 9 months, if no new workloads are added. As you can see, based on current utilization data, Prism projects that we’ll run out of storage well before that time.

In this case, clicking the Recommend button gives us suggestions for which nodes we could add, how many we should add, and what their configuration should be for us to meet our runway needs. This particular feature can be a powerful tool in understand what your current and future capacity needs are, and can empower you to make informed, incremental purchasing decisions.

### Prism Performance Monitoring: Dynamic Monitoring
We’ve already briefly touched upon this in the Operational Insights section, specifically when we discussed the Analysis dashboard. The Analysis dashboard is a key part of Prism’s performance monitoring capabilities, because it provides you with a single, holistic view of cluster data and allows you to drill down into details as required. However, what we haven’t yet discussed is how performance monitoring works in Prism.

Prism offers Dynamic Monitoring, using VM behavioral learning. The system learns the behavior of each VM and establishes a dynamic threshold as a performance baseline for each resource assigned to that VM. Each of the resource charts represents the baseline as a blue shaded range. If a given data point for a VM strays outside the baseline range (higher or lower), the system detects an anomaly and generates an alert. The anomaly is noted on the performance charts for easy reference and follow-up.

If the data point’s anomalous results persist over time, the system learns the VM’s new behavior and adjusts the baseline for that resource. With behavioral learning, performance reporting delivered via Prism helps organizations better understand their workloads and have early knowledge of issues that traditional static threshold monitoring would not otherwise discover.

### Prism Performance Monitoring: Creating Charts
In addition to the default charts that Prism presents you with, you can also create custom charts to monitor specific elements of your cluster. You can create two types of charts: metric or entity.

A metric chart monitors the performance of a single metric on one or more entities. For example, you can create a single chart that monitors the content cache hits for multiple hosts within a cluster.

An entity chart monitors the performance of one or more metrics for a single entity. For example, you can create a single metric chart that monitors a particular host, for metrics such as Disk I/O Bandwidth for Reads, Disk I/O Bandwidth for Writes, and Disk IOPS.

### Prism Performance Monitoring: Alert Emails
By default, Alert email notifications are enabled. This feature sends alert messages automatically to Nutanix customer support through customer-opened ports 80 or 8443. To receive email notification alerts, you need to ensure that nos-alerts and nos-asup recipients are added to the accepted domain of your SMTP server.

You can also customize your Alert emails. To aid in your cluster monitoring efforts, you can schedule the frequency of these Alert emails, the recipients, and the conditions under which an email will be sent.

You can also edit the contents of the email itself.

### Lesson Recap
* The hardware and software components of HCI
* Acropolis: AHV, DSF, Virtual Networking, Storage Services
* Prism: Infrastructure Management, Operational Insights, Capacity 
* Planning, and Performance Monitoring

## Chapter 3: Hybrid Cloud Security

Security today is more complicated than it’s ever been. There are more workloads than the industry has ever had to deal with before. As a result of virtualization, these workloads are often sitting on a single hardware platform.

With traditional infrastructure, stacks are composed of products from multiple vendors, each with a narrow and limited view of security. Validating and maintaining a security baseline through continuous software upgrades, is time-consuming and often involves error-prone manual processes that take away from innovation and productivity.

Traditional security solutions such as firewalls are often blind to the internal communication between virtual machines and applications. Once cybercriminals infiltrate the network, they can take up residence and move laterally without being detected. The inherent complexity of this infrastructure has led to increased risks.

### Security Standards

Since there’s always that risk of someone getting in, a lot of organizations find themselves in a risky place. More often than not, they deal with large volumes of sensitive data around with a high standard of security must be maintained. In order to ensure there are standards organizations can hold themselves to, a number of widely accepted and enforced definitions have been developed.

There are five major government standards for security that IT needs to take into consideration. They are TAA Compliance, NSA Suite B, 508 Compliance, FIPS Compliance, and Common Criteria.

TAA Compliance
The Trade Agreements Act refers to a law requiring the U.S. government purchase only “U.S.-made or designated country end products.” Companies and contractors are considered TAA-compliant if they follow TAA guidelines.

End products are “articles, materials and supplies to be acquired for public use," according to the text of the law. Designated countries include Free Trade Agreement countries, countries that have signed the World Trade Organization Agreement on Government Procurement, Caribbean basin countries and some "least-developed" countries.

China, Taiwan, India, Thailand and Malaysia are not considered designated countries in the TAA. However, U.S. contractors can use supplies from these countries and other non-designated countries, as long as they substantially transform them into different final products that meet the criteria. Contractors and companies that do not comply with TAA rules may face lawsuits or have trouble obtaining government contracts.

NSA Suite B
NSA Suite B is a set of commercially available encryption algorithms, published by the US’s National Security Agency, for use in commercial applications as well as some types of classified information.

Suite B specifies a mode of operation in which only a specific set of secure cryptographic algorithms should be used. Suite B specifies the encryption algorithm, the key exchange algorithm, the digital signature algorithm, and the hashing algorithms.

508 Compliance
In 1998, the United States Congress amended the Rehabilitation Act to require Federal agencies to make their electronic and information technology accessible to people with disabilities.

Section 508 was enacted to eliminate barriers in information technology, to make available new opportunities for people with disabilities, and to encourage development of technologies that will help achieve these goals. The law applies to all Federal agencies when they develop, procure, maintain, or use electronic and information technology.

508 Compliance, involves ensuring accessibility in technology. While it’s popularly and more commonly known in the context of website accessibility, 508 Compliance is a key part of systems and platform development as well. Although it isn’t technically a security standard, it’s here because – just like security – 508 compliance needs to be built into a product from the ground up.

It needs to be considered in UI design, navigation, menus and interactions, labelling, and so much more.

FIPS Compliance
FIPS 140-2 stands for Federal Information Processing Standard 140-2 and, like the other standards listed here, is US-government specific. The standard itself is used to approve cryptography modules and is required when working in any capacity with the United States government. FIPS 140-2 is derived from the Federal Information Security Management Act of 2002 (FISMA) and the Federal Information Security Modernization Act of 2014.

The Federal Information Security Management Act of 2002 is a United States federal law that recognized the importance of information security to the economic and national security interests of the United States. The act requires each federal agency to develop, document, and implement an agency-wide program to provide information security for the information and information systems that support the agency. This also includes information and system that were provided or managed by another agency, contractor, or other sources.

FISMA was superseded by the Federal Information Security Modernization Act of 2014, which removed some elements from FISMA and amended other aspects for changes in cybersecurity and oversight.

Common Criteria
The Common Criteria for Information Technology Security Evaluation, also called Common Criteria, is an international standard for computer security. It allows the users of a system to specify their functional and functional assurance requirements for a specific product. Technology vendors can then, based on these requirements, evaluate their products against these requirements to confirm compliance.

Common Criteria provides assurance that the process of specification, implementation and evaluation of a computer security product has been conducted in a rigorous, and standard manner at a level that corresponds with its target use environment. Once this process is completed successfully, a vendor achieves Common Criteria certification.

There are two major components to Common Criteria. The first, is a Protection Profile, which is a document that specifies the requirements for a class of security devices, such as firewalls. This document is what vendors evaluate their products against to determine Common Criteria Compliance.

The second component is the Evaluation Assurance Level, which – as the name suggests – refers to the evaluation itself. More specifically, it is a numerical rating that described the rigor and depth of an evaluation.

### How Secure Are Your Clouds?
Leveraging the public cloud doesn’t mean you give up all control over security. There are still measures that you can implement, but they only go so far. In practice, you’ll find that you can control and secure about 80% of a public cloud’s capabilities. While that is a considerable amount of control, it does still mean that roughly 20% is left to the cloud provider and their security measures. Most public cloud providers do an excellent job of securing that 20%, but that doesn’t mean breaches are an impossibility.

On the other hand, with the private cloud, you have full control over your security. That means you can potentially be more secure than the public cloud but, simply having an on-prem setup doesn’t bolster security by itself. That is one of the reasons that these security standards are so important. They represent a benchmark against which you can measure your own security profile, determine what areas of your environment are well set up and which ones are in need of some tightening. Your on-prem cloud is only as secure as the products you use to build your technology stack. This is why security needs to be built into those products from the ground up.

### Securing Clouds from the Ground Up

Toggle Sidebar
Securing Clouds from the Ground Up
Securing Clouds from the Ground Up

Why are the standards we just talked about are so important?

Each of these standards represents a set of considerations for the way a product is conceptualized, designed, programmed, and tested - and ultimately determines who it can be sold to. These considerations aren’t things that can be bolted on at the last minute.

For a system – any system – to be as protected as it can be, security needs to be built in from the ground up. This is why compliance is something you consider even before you start development. When you’re gathering requirements, determining functionality, and figuring out the sort of product that you’re going to build, you need to consider how security will affect decisions you make during development.

Because of this, it’s important to understand the security development life cycle.

### Security Development Life Cycle
This is a high-level overview of the Security Development Life Cycle. It is a process with different phases that contain security activities that sits inside of the classic people-process-technology triangle. The SecDL forms the process portion.

It includes both the central security team that governs the process and updates it, as well as the product or development teams that perform security activities. The technology portion consists of tools that assist in finding vulnerabilities in source code or discovering vulnerabilities in a running instance of the product or application.

The SecDL is methodology-neutral. Security activities fit within any product development methodology, whether waterfall, or DevOps. Methodology differences show up in the cadence of security activities.

The SecDL was developed during the time of waterfall, so it is usually portrayed as a linear process that begins with requirements and ends with the release. When the SDL is extended to agile, some security activities get integrated into the normal sprint schedule, while others are pursued out-of-band. With DevOps, activities are embedded into the build pipeline using automation, while additional activities happen outside the pipeline.

### SecDL: Analyze
The first phase is essentially requirements gathering. In this phase, the goal is to defined the security best practices that will be integrated into a product. These practices may come from industry standards or be based on responses to problems that have occurred in the past. Requirements exist to define the functional security requirements implemented in the product, and include all the activities of the SDL. They are used as an enforcement point to ensure that all pieces are properly considered.

Requirements may take the classic form, stating that the product or application must, can, or should, do something. An example might be that the product must enforce a minimum password length of eight characters. In the agile world, requirements are expressed as user stories. These stories contain the same information as do the requirements, but security functionality is written from the user's perspective.

### SecDL: Design
The design phase of the SDL consists of activities that ideally occur before code is written. Secure design is about quantifying an architecture, for a single feature or the entire product, and then searching for problems.

The key to identifying problems is threat modeling. Threat modeling is the process of thinking through how a feature or system will be attacked, and then mitigating those future attacks in the design before writing the code. If you’ve seen the 2002 film Minority Report, that’s kind of the function that threat modeling serves – it’s about preventing crimes before they happen.

A solid threat model understands a feature's, or product's, attack surface. It then defines the most likely attacks that will occur across those interfaces. A threat model is only as good as the mitigations it contains to fix the problems. It is crucial to identifying security issues early in the process.

### SecDL: Implement
The next phase is implementation, which involves actually writing secure code. The SecDL contains a few things programmers must do to ensure that their code has the best chance of being secure. The process involves a mixture of standards and automated tools.

On the standards front, a solid SecDL defines a secure coding guide, that defines what is expected and provides guidance for when developers hit a specific issue and need insight. Implementation tools include Static Application Security Testing, or SAST, and Dynamic Application Security Testing, or DAST, software.

SAST is like a spell-checker for code, identifying potential vulnerabilities in the source code. SAST runs against a nightly build or may be integrated into your IDE. It may find and open new bugs in the bug management system nightly or prompt the developer to pause while coding to fix a problem in real time.

DAST checks the application's runtime instantiation. It spiders through an application to find all possible interfaces and then attempts to exploit common vulnerabilities in the application. These tools are primarily used on web interfaces.

### SecDL: Test
Formal test activities include security functional test plans, vulnerability scanning, and penetration testing. Vulnerability scanning uses industry-standard tools to determine if any system-level vulnerabilities exist with the application or product.

Penetration testing involves testers attempting to work around the security protections in a given application and exploit them. Penetration testing also stretches the product and exposes it to testing scenarios that automated tools cannot replicate. Because penetration testing is resource-intensive, it is usually not performed for every release.

### SecDL: Update
The findings from tests are updated as necessary and the product itself is then prepared for release.

Release occurs when all the security activities are confirmed against the final build and the software is sent to customers or made available for download. After the software is released, an interface is typically provided for external customers and security researchers to report security problems in products.

Part of this response interface should ideally include a product security-incident response team that focuses on triaging and communicating product vulnerabilities, both individual bugs and those that will require industry-wide collaboration such as Heartbleed, Bashbug, etc.

Finally, there are other security activities are also important to the success of a SecDL, including security champions, bug bounties, and education and training.

### SecDL and Nutanix
Our security development life cycle integrates security into every step of product development, rather than applying it as an afterthought. It is a foundational part of product design. The pervasive culture and processes built around security harden the Hybrid Cloud OS and eliminate zero-day vulnerabilities.

For example, research and development teams work together to fully understand all the code in the product, whether it is produced in-house or inherited from dependencies. We schedule product updates to handle known common vulnerabilities and exposures, or CVEs, for minor release cycles, and backport all dependencies to their latest release versions in major release cycles. This approach significantly reduces zero-day risks without slowing down product evolution.

Efficient one-click operations and self-healing security models enable automation to maintain security in an always-on hyperconverged solution. Finally, Nutanix also delivers validated joint solutions with security-focused vendors.

### Security in the Hybrid Cloud
As a result of the Nutanix approach to SecDL, and with the way we built security into our products from the ground up, you’ll find that the Hybrid Cloud has a number of security features available out of the box.

While there’s more to Nutanix security than the five points you’re seeing here, these are the major topics we’re going to talk about in this lesson. Broadly, we’re going to cover two-factor authentication, cluster lockdown, key management and administration, STIG implementation, data-at-rest encryption, and role-based access control.

### Two-Factor Authentication
Several different types of authentication exist, including one way, two way, and two-factor.

One way authentication involves simply authenticating to the server. Two-way involves the server also authenticating the client.

Two-factor authentication is a subset of multi-factor authentication, which involves presenting two or more pieces of evidence to an authentication mechanism. These pieces of evidence are typically combinations of three things: something the user knows, something the user has, and something the user is.

A good example of this is typically bank transactions. Very often, when performing an online transaction, you’ll also be asked to confirm the transaction by entering a time-limited password sent to your mobile phone via text message, or to your email account. In this case, entering your card or account details represent knowledge as the first factor, and the password comes from something you have or own – in this example, your phone or email account.

Two-factor authentication simply involves two pieces of information. In the case of Nutanix’s implementation, it involves a username and password combination, and a client certificate. For two-factor authentication, Nutanix administrators can use either local accounts, or Active Directory.

### Cluster Lockdown
Cluster lockdown is the ability to disable password-based CVM access and/or only allow key based access.

However, you can add your public SSH-key via Prism and still login via SSH by using your ssh key. This adds a layer of non-repudiation to the connection, since the key used to access the emergency account on the shell is logged. This adds a layer of cryptographic exchange to the connection instead of just a source IP.

All CVMs have a set of ssh-keys that are generated at installation, so all CVMs in a cluster can still communicate with each other using keys,and you can ssh between them using keys once you gain access.

### Key Management and Administration
Nutanix nodes are authenticated by a key management server, or KMS. SEDs generate new encryption keys, which are uploaded to the KMS. In the event of power failure or a reboot, keys are retrieved from the KMS and used to unlock the SEDs. These security keys can also be instantly reprogrammed. And finally, Crypto Erase can be used to instantly erase all data on an SED while generating a new key.

### Security Technical Implementation Guides
Security Technical Implementation Guides, or STIGs, are the configuration standards for DoD Information Assurance, or IA, and IA-enabled devices/systems. STIGs specify how a computing device must be configured to maximize security.

A STIG describes how to minimize network-based attacks and prevent system access when the attacker is interfacing with the system, either physically at the machine or over a network. STIGs also describe maintenance processes such as software updates and vulnerability patching. Advanced STIGs cover the design of a corporate network, covering the configurations of routers, firewalls, domain name servers, and switches.

Once deployed, STIGs lock down IT environments and reduce security vulnerabilities in infrastructure. Traditionally, using STIGs to secure an environment is a manual process that is highly time-consuming and error prone. Because of this, only the most security-conscious IT shops follow the required process. Nutanix has created custom STIGs that are based on the guidelines outlined by The Defense Information Systems Agency, or DISA, to keep the Hybrid Cloud Platform within compliance and reduce attack surfaces.

### Data-at-Rest Encryption
Data-at-Rest Encryption secures data while at rest using self-encrypting drives and key-based access management. For customers who require enhanced data security, Nutanix provides a software-only encryption option for data-at-rest security which does not require self-encrypting drives.

With Nutanix’s Data-at-Rest Encryption implementation data is encrypted on all drives at all times, data is inaccessible in the event of drive or node theft, data on a drive can be securely destroyed, protection can be enabled or disabled at any time, and no performance penalty is incurred despite encrypting all data.

### Role-Based Access Control
The last security capacity that we’re going to discuss in this lesson is role-based access control. Prism supports role-based access control that you can configure to provide customized access permissions to users based on their assigned roles. The roles dashboard allows you to view information about all defined roles and the users and groups assigned to those roles.

Prism includes a set of predefined roles. You can also define additional custom roles. Configuring authentication confers default user permissions that vary depending on the type of authentication like full permissions from a directory service, or no permissions from an identity provider. You can configure role maps to customize these user permissions. Finally, you can refine access permissions even further by assigning roles to individual users or groups that apply to a specified set of entities.

### Lesson Recap
* Introduced you to security
* Went over security standards
* Discussed the Security Development Life Cycle
* Discussed how to secure the Hybrid Cloud

## Chapter 4: Networking
### Lesson Overview
* Introduction to Physical and Virtual Networking
* Components of AHV Networking
* Working with VLANs

What is Networking?
Networking is the practice in which nodes transport and exchange data over a shared medium.

It is commonly associated with the design, construction, and use of a network. Networking also includes the management, maintenance, and operation of the network’s physical infrastructure. It also involves all the associated software and policies.

In this lesson we’re going to be focusing on two specific topics – physical networking and virtual networking.

### Introduction to Networking: Physical Networking
Physical networking is about the network topology – the devices, their location, and the physical cables that connect those devices to each other. The network is a key component in ensuring high performance and availability, and successful deployments combine the right physical switches with the right physical designs.

A Nutanix environment should use datacenter switches designed for transmitting large amounts of server and storage traffic at low latency.

Datacenter switches have the following characteristics:

* Line rate: Ensures that all ports can simultaneously achieve advertised throughput.
* Low latency: Minimizes port-to-port latency, measured in microseconds or nanoseconds.
* Large per-port buffers: Handle speed mismatch from uplinks without dropping frames.
* Nonblocking, with low or no oversubscription: Reduces chance of drops during peak traffic periods.
* 10 Gbps or faster links for Nutanix CVM traffic: Only use 1 Gbps links either for additional user VM traffic or when 10 Gbps connections are not available, such as in a ROBO deployment. Limit Nutanix clusters using 1 Gbps links to eight nodes.

Once you’ve found the right switch, that’s one big decision dealt with. The other is which networking design to use. And whether you’re designing a new network or transitioning an older network into cloud-scale architecture, it is important to know the differences and characteristics of two prominent network topologies: Core-Aggregation-Access networking, which is also called 3-Tier networking, and Leaf-Spine architecture.

### Physical Networking Topology: Core-Aggregation-Access (3-Tier)
This architecture contains three layers: Core, Aggregation, and Access.

The core layer provides fast transport between distribution layer switches. The core layer provides routing services to other parts of the data center, as well as to services outside of the data center such as the Internet, geographically separated data centers and other remote locations. The network core delivers routing services, making complex routing decisions for optimized networking traffic, advertises routes, stores network configurations, and provides a gateway for all networks to communicate internally and externally.

The aggregation layer has redundant connections to access layer switches and connects to the core layer.

The access layer is where host devices are connected to the network. It plays a vital role in meeting server requirements such as NIC teaming, clustering, and broadcast containment.

In the Core-Aggregation-Access networking model, devices are connected to each other within a layer, as well as across layers for redundancy. This model scales somewhat well, but it is subject to bottlenecks if uplinks between layers are oversubscribed. This can come from latency incurred as traffic flows through each layer and from blocking redundant links. Also, the cost per port is fairly high. The hardware and logic contained within core switches made them cost-prohibitive to scale.

### Using 3-Tier in a Nutanix Deployment
The core-aggregation-access (or three-tier) design is a modular layout that allows you to upgrade and scale layers independently.

However, there’s one important best practice that you need to consider and that’s the three-switch-hop rule.

Nutanix nodes send storage replication traffic to each other in a distributed fashion over the top-of-rack network. One Nutanix node can therefore send replication traffic to any other Nutanix node in the cluster. The network should provide low and predictable latency for this traffic. So, it’s important to ensure that there are no more than three switches between any two Nutanix nodes in the same cluster.

Essentially, when using Core-Aggregation-Access, you need to ensure that all nodes in a Nutanix cluster share the same aggregation layer to meet the three-switch-hop rule.

Scaling the three-tier network design may require adding another aggregation and access layer to the core. In this case, there would be more than three switch hops between the two access layers. To continue to align with the three-switch-hop rule, ensure that you add Nutanix nodes in separate aggregation and access layers to separate clusters. In the example you’re seeing here, Cluster 1 connects to one aggregation layer and Cluster 2 connects to another.

However, since there are many ways to connect switches in the core-aggregation-access design, your deployment may look a little different from this one.

### Physical Networking Topology: Leaf-Spine
The leaf-spine network design is popular in new datacenter deployments because it’s easy to deploy and easy to scale after deployment. A leaf-spine topology requires at least two spine switches and two leaf switches. Every leaf connects to every spine using uplink ports. There are no connections between the spine switches or between the leaf switches in the conventional leaf-spine design. This architecture maintains consistent performance without any reduction in throughput.

Spine switches contain the routing, switching, and network services required for core network functions. Leaf switches exclusively provide high port density for network communications and extend the network configuration of the core out to the endpoints. Leaf-Spine switching focuses on east-west traffic, capitalizing on the fact that a majority of network communication now relies upon communication within the LAN to other adjacent servers and services. Spine leaf provides a high-bandwidth, low latency alternative to 3-tiered architecture, as any given network node is simply one hop away from any adjacent node through the leaf switches.

Spine and leaf architecture provides consolidated management and scale-out networking in a simplified network design. Scaling the architecture normally involves adding a single leaf, enabling the new switch in the fabric, and then cabling the endpoints as needed.

### Leaf Spine: Using Leaf-Spine in a Nutanix Deployment
Nutanix recommends a leaf-spine network architecture to ensure true linear scaling. Other best practices include using uplinks that are a higher speed than the edge ports to reduce uplink oversubscription. To increase uplink capacity, add spine switches or uplink ports as needed.

### Introduction to Networking: Virtual Networking
To understand virtual networking, we need to first take a quick step back and understand network virtualization. And although they sound similar – and that’s because they’re related – they do mean slightly different things.

Network virtualization involves combining hardware and software network resources, along with network functionality, into a single, software-based administrative entity. The elements that can be combined include switches, network adapters, firewalls, load balancers, virtual LANs, and so on. The outcomes of this – the single, software-based entity – is a virtual network.

And virtual networking, to put it very simply, facilitates communication between virtual machines. It’s based on physical networking principles, but its functions are software-driven. For example, a virtual switch contains the same packet forwarding logic that a physical switch does, but as software.

There are four major components that we need to talk about: virtual switches, bridges, ports, and bonds.

This virtual switch controls and directs communication between the existing physical network and virtual parts of the network, like virtual machines. A virtual network adapter allows VMs to connect to a network, and allows the VMs on a LAN to connect to a larger network as well.

### Virtual Networking: Virtual Switches
As we discussed earlier, virtual switches allow communication between virtual machines. More specifically, they intelligently direct communication on a network by checking data packets before sending them along to their destination.

Using virtual switches simplifies the complexity that comes with configuring and managing a network. This is because virtual switches help reduce the number of switches that need to be managed after factoring in the size of the network, data packets, and architecture. Because they’re entirely software-based, it’s easier to roll out new functionality for virtual switches as compared to physical, hardware-based ones.

Nutanix AHV uses Open vSwitch, or OVS, to manage the network across all nodes in the Nutanix cluster. OVS is an open source software switch implemented in the Linux kernel and designed to work in a multi-server virtualization environment. By default, OVS behaves like a layer-2 learning switch that maintains a MAC address table. The hypervisor host and VMs connect to virtual ports on the switch.

OVS supports many popular switch features, including VLAN tagging, Link Aggregation Control Protocol (LACP), port mirroring, and quality of service (QoS), to name a few. Each AHV node maintains an OVS instance, and all OVS instances combine to form a single logical switch. Constructs called bridges manage the switch instances residing on the AHV hosts.

Let's break down some of these virtual networking components that make up Nutanix AHV.

### Virtual Networking: Bridges
Bridges act as virtual switches that manage network traffic between physical and virtual network interfaces.

The default AHV configuration includes an OVS bridge called br0 and a native Linux bridge called virbr0. The virbr0 Linux bridge carries management and storage communication between the CVM and AHV host. All other storage, host, and VM network traffic flows through the br0 OVS bridge. The AHV host, VMs, and physical interfaces use ports for connectivity to the bridge. Next, let's discuss ports.