
# Welcome to Xyna
***This page is under construction, you'll find information about Xyna itself and your first steps with Xyna here in a short term***
## First Steps
[Tutorials](https://github.com/Xyna-Factory/xyna/wiki/Tutorials)
[Installation](https://github.com/Xyna-Factory/xyna/wiki/Installation)

[Where to go next](https://github.com/Xyna-Factory/xyna/wiki)


## What is Xyna

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://user-images.githubusercontent.com/107180330/173100035-d6b447d7-841d-4001-9254-01d3ad7be334.svg"
      width="200"
    />
    <img
      alt="Xyna logo"
      src="https://user-images.githubusercontent.com/107180330/173533108-f8fe97bd-c984-401b-b7ab-0e283ea053e4.svg"
      width="200"
    />
  </picture>
</div>

Xyna Factory is an automation platform for graphically modeled workflows with a focus on network- / resource-related processes in carrier, provider and large enterprise networks. Invented and originally developed for large, demanding projects at Tier-1 service providers, Xyna was designed and implemented from the beginning with a large-scale and carrier-grade claim. Xyna is a generic platform from which various domain-specific applications can be derived: order management, service provisioning, self-service automation, network abstraction & activation, DHCP & ACS clusters, network intelligence & monitoring platforms – and much more.

* **Workflow Automation:** graphic development environment for modeling + automation of technical processes
* **Deep Modelling Paradigm:** modeling instead of programming – graphic processes are executable workflows, no media breaks
* **Ready-2-Use Fullstack Application Framework:** frontend + API framework + backend in a standardized CI/CD Pipeline
* **Microservice mashup:** flexible and DevOps-accessible service network with standardized APIs
* **Container-ready & Cloud-enabled:** operation in standardized, virtualized infrastructures / stacks
* **High-performance Operations:** support of scalable cluster configurations for highly available and/or high-performance systems

Xyna is a platform to focus on the essentials. And the essence is always modeling – because a model is a description of the desired implementation, in which only the important things appear.
The dynamic aspects of an application are the most interesting and important. Procedures and processes. The Xyna Modeller visualizes the graphical process model (Workflow) and also the graphical data model (XMOM).

A major difference to other graphical notations like BPMN or UML: we want the identity of model and implementation. The models are executable in Xyna. The Xyna Process Modeller is an IDE for generating supervised (Java) code. With deployment into Xyna Server, compilation and execution in the Xyna Workflow Engine. Accessible and lifecycle controlled via DevOps methods.

Xyna Applications are self-contained deployment items including workspaces, workflows and data types. Different versions can be deployed at the same time, enabling application changes without downtime. A solution usually consists of a set of different Xyna Applications: productized standard modules (e.g. for network services or device-specific activation adapters) as well as custom modules (e.g. individual service configurations or provisioning processes) Xyna Factory Manager provides definition, build process and deployment of Xyna Applications in a graphical frontend + control over all running and installed applications.

A typical Xyna application is a server application that carries business logic. Depending on the business case, the degree of automation can be adjusted, with integration of manual steps, self-service, SLS/LLS access, etc. Xyna systems usually have (many) interfaces to partner systems, are embedded in large system landscapes with dependencies to parallel processes, subjected to a continuous lifecycle with continuous changes. Therefore, Xyna can serve a variety of interfaces: from “traditional” legacy interfaces (like email, SOAP or MQ) up to contemporary implementations like RESTful OpenAPI catalogues or YANG-defined Netconf commandos. Xyna’s fullstack application framework supports various configurations up to multi-layered N-tier architectures with separated proxy elements, firewalled layers, and x/y-dimensioned scalability  for mission-critical applications.

DISCLAIMER: Xyna is a free & open platform. No commercial terms, no locked-in effects,  no dependencies, no barriers to entry. And like any software, Xyna contains bugs. We appreciate any feedback and contributions here on GitHub. In its current maturity stage Xyna is well suited for application development. But for production systems, we generally recommend to implement further security measures through suitable network technology, firewalls, WAFs, etc. #CIP #kaizen #FailHarder.
