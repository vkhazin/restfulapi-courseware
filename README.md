# Swagger and Micro-services #

## Description ##

* Microservice architecture structures applications as a collection of loosely coupled services
* More than 70 percent of companies want to intensify their usage of Micro-services in 2017 according to <a href="./media/leanIX_Microservices-Study.pdf" target="_blank"></a>
* Motivations behind micro-services adoption:
  * improvement in IT agility by reducing risk of big-bang releases and/or re-tooling
  * easier development maintainability with simpler code base
  * easier operations automation for CD (continuous deployment) and for CI (continuous integration) due to reduced dependencies
  * improved system resilience where failure of a service does not take down the entire system
* Micro-service architecture is not a silver bullet - several drawbacks from real-world experience will be discussed
* Swagger is the world’s largest framework for designing, generating code, and visualizing API's 
* Micro-services is not a language specific pattern, mixing languages and tools is normal 
* Micro-services may use http request/response or a message driven architecture
* Docker containers greatly improve predictability of micro-services deployments
* Public/Private Cloud PaaS (platform as a service) reduce TCO (total cost of ownership) specifically with micro-service architecture

## Audience ##

* Application Architects looking to familiarize themselves with micro-service architecture
* Developers eager to get first hand experience building micro-services 
* Operations looking to automate micro-services deployment and monitoring
* DevOps eager to jump into the micro-services way of thinking

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
* Recent hands-on experience with Linux bash terminal

* Familiarity with data formats: Json, Csv, Logs, etc.

* Recent administrative and troubleshooting experience on Linux OS

* Scripting and/or programming hands-on recent experience

## Outline ##

### Introduction to InfluxDb ###
* Time series data and database
* InfluxDb Terminology, basic concepts, implementation, setup, and basic operations
* Design Insides and Trade-offs  
* Comparison to Sql
* Schema Design
* Storage Engine
* Enterprise Edition Cluster

### Writing Data ###
* Overview of alternatives
* Creating database
* HTTP API
* CLI (command-line interface)
* Node.Js client library

### Reading Data ###
* Overview of alternatives
* HTTP API
* CLI (command-line interface)
* Node.Js client library

### Schema Design ###
* Recommended Practices
* Discouraged Practices
* Data Granularity
* Multi-purpose Data

### Data Retention ###
* Shard Groups
* Down-sampling
* Continuous Query
* Retention Policy

### Telegraf ###
* Collecting & reporting metrics
* Architecture
* Input Data Formats
* Input plug-ins
* Output Data Formats
* Output plug-ins

### Chronograf ###
* Multi-purpose User Interface
* Infrastructure Monitoring
* Alert Management
* ETL Jobs Monitoring
* Database Management

### Kapacitator ###
* Data Processing Framework
* Steaming data
* Batch data
* Data transformation
* Writing user defined functions
* Integration with external services

### Preparing for Production ###
* Capacity planning
* Hardware requirements
* Cloud hosting
* Docker Container
* Monitoring and troubleshooting
* Backup and Restore


