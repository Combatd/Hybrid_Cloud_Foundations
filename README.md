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