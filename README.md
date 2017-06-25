# Swagger and Micro-Services #

## Description ##

* Microservice architecture structures applications as a collection of loosely coupled services
* More than 70 percent of companies want to intensify their usage of Micro-services in 2017 according to <a href="./media/leanIX_Microservices-Study.pdf" target="_blank">leanIX study</a>
* Motivations behind micro-services adoption:
  * improvement in IT agility by reducing risk of big-bang releases and/or re-tooling
  * easier development maintainability with simpler code base
  * easier operation with automated CD (continuous deployment) and CI (continuous integration)
  * improved system resilience where failure of a service does not take down the entire system
* Micro-service architecture is not a silver bullet - several drawbacks from real-world experience will be discussed
* Swagger is the world’s largest framework for designing, generating code, and visualizing API's 
* Micro-services is not a language specific pattern, mixing languages and tools is normal 
* Micro-services may use http request/response or a message driven pattern
* Docker containers greatly improve predictability of micro-services deployments
* Public/Private Cloud PaaS (platform as a service) reduce TCO (total cost of ownership) specifically with micro-service architecture

## Audience ##

* Application Architects looking to familiarize themselves with micro-service architecture
* Developers eager to get first hand experience building micro-services 
* Operations looking to automate micro-services deployment and monitoring
* DevOps eager to jump into the modern software delivery mindset

## Course's Objectives ##
* Analyze industry motivation for adopting micro-service architecture
* Draw a comparison between SOA (service-oriented architecture) and Micro-service architecture
* Discover advantages and disadvantages of micro-services
* Get familiar with Swagger tool set
* Build micro-services using different languages
* Implement http and message driven design patter
* Experiment with deployment of micro-services using Docker
* Get familiar with public cloud PaaS DevOps model

## Prerequisites ##
* Laptop with admin/root privileges to install required software
* Recent hands-on programming and/or scripting experience
* Software development, delivery, and operational experience 
* Familiarity with software design and architecture patterns: Desktop, Web, Mobile, and Soa
* Familiarity with git source control system
* Exposure to Linux command line
* Exposure to Public/Private cloud concepts

## Outline ##

### Why Micro-Services and How-to ###
* Software Architecture Patterns
* Life-cycle of an applications
* The more agile architecture the better
* Cross platform and multi-tools reality
* Scalability and spikes in load
* From Monolith to Micro-Services

### RESTFull Web Service ###
* Overview: REST vs. SOAP
* RESTFull Maturity Model
* Building an End-Point
* Testing a Web Service
* Documenting the Deliverable

### Swagger Editor ###
* Why Swagger?
* First API Contract or Implementation?
* Design an End-Point
* Test API Design

### Swagger UI ###
* Installation & Configuration
* Testing RESFull API
* Common Pitfalls

### Swagger Codegen ###
* Code generation overview
* Codegen command line
* Generating code from spec

### Deployment to VM ###
* Overview of options
* Installing dependencies
* Deploying artifacts
* Upgrade strategies

### Operation and Monitoring ###
* Challenges with Micro-services
* Configuration
* Logs aggregation
* Monitoring

### CD/CI Automation ###
* Objectives and Goals
* Building CD
* Designing Unit Tests
* Adding CI

### Message Driven Services ###
* Request/Response vs. Message Driven
* Building a Message Driven Service
* Selecting a back-end

### Running in a Container ###
* Container vs. VM
* Building Docker Image
* Running Docker Container
* Cluster

### Running on PaaS ###
* PaaS vs. Container vs. VM
* Deploying to PaaS
* Automated scalability
* Troubleshooting tools

### Summary ###
* Best Practices
* Anti-patterns
* Lessons learned