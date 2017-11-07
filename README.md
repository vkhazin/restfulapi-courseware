# Micro-Services #

## Description ##

* RESTful API is an application program interface that uses HTTP/S requests to GET, PUT, POST and DELETE data
* RESTful API is based on representational state transfer technology, an architectural style and approach to communications used in web services
* REST Web services systems are used to access and manipulate textual representations of Web resources
* RESTful web services are uniform and interoperable contrasted to language or platform specific API's
* RESTful web service are often enough associated with Micro-Services architecture
* RESTful architecture aims at breaking down monolithic application to series of individually deployed and loosely coupled components
* New challenges arise with adoption of RESTful and Micro-services: automation of deployment and monitoring
* RESTful services are odd to be designed deploy-able on-premises and on-the-cloud location-transparently
* Docker containers greatly improve predictability of service deployment and portability between on-premises and on-the-cloud hosting options
* Public/Private Cloud PaaS (platform as a service) and FaaS (function as a service) are aiming to further reduce total cost of ownership

## Audience ##

* Application Architects looking to familiarize themselves with RESTful architecture trade-offs compared to a Soa and to monolithic application architecture
* Developers eager to get first hand experience building RESTful services 
* Operations looking to automate web services deployment and monitoring
* DevOps eager to jump into the modern software delivery mindset

## Course's Objectives ##
* Analyze industry motivation for adopting RESTful architecture
* Draw a comparison between Soa (service-oriented architecture) and RESTful architecture
* Discover advantages and disadvantages of RESTful services
* Build RESTful services using different approaches
* Experiment with deployment of services using Docker
* Get familiar with public cloud PaaS/FaaS DevOps model

## Prerequisites ##
* Laptop with admin/root privileges to install required software
* Recent hands-on programming and/or scripting experience
* Software development, delivery, and operational experience 
* Familiarity with software design and architecture patterns: Desktop, Web, Mobile, and Soa
* Familiarity with git source control system
* Exposure to Linux command line
* Exposure to Public/Private cloud concepts

## Outline ##

### Why RESTful Services ###
* Software Architecture Patterns
* Life-cycle of an applications
* The more agile architecture the better
* Cross platform and multi-tools reality
* Scalability and spikes in load
* Compare Soa to RESTful
* Compare Monolith to Micro-Services

### RESTFull Web Service ###
* Overview: REST vs. SOAP
* RESTFull Maturity Model
* Building an End-Point
* Testing a Web Service
* Documenting the Deliverable to streamline adoption

### Deployment to VM ###
* Overview of options
* Installing dependencies
* Deploying artifacts
* Versioning and Upgrade strategies

### Operation and Monitoring ###
* Challenges with RESTful services
* Configuration
* Logs aggregation
* Monitoring

### CD/CI Automation ###
* Objectives and Goals
* Building CD
* Designing Unit Tests
* Adding CI

### Swagger ###
* Why Swagger?
* First API Contract or Implementation?
* Design an End-Point
* Test API Design

### Running in a Container ###
* Container vs. VM
* Building Docker Image
* Running Docker Container
* Cluster

### Running on PaaS & FaaS ###
* PaaS vs. Container vs. VM
* Deploying to PaaS
* Deploying to FaaS
* Automated scalability
* Troubleshooting tools

### Summary ###
* Best Practices
* Anti-patterns
* Lessons learned