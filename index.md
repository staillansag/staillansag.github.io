---
layout: page
title: Stéphane Tailland @ Software AG
description: Collection of useful information items and links
---

Find here some useful information items and links regarding Software AG and its products.
This page focuses on products related to APIs, Applicative Integration and Microservices.

### Integration microservices

Over the last few years, webMethods has undergone a transformation to become an integration microservice platform.  
You still get the power of the good old webMethods ESB platform: connectivity to virtually anything, standardized low-code integrations, high performance, to name a few.  
But you can now implement and deploy your integration in lightweight and distributed containers, while applying the DevOps practices.  
You get a platform to easily expose synchronous and asynchronous APIs.

The lightweight container version of the webMethods ESB is called Microservice Runtime (or MSR.)  
The MSR is available in [Docker Hub](https://hub.docker.com/r/softwareag/webmethods-microservicesruntime), it embeds a trial license of 90 days.  
Talking about licensing, the transaction model allows you to deploy as many MSR as you want, in the environment of your choice. The underlying infrastructure does not matter, we just count the number of transactions that are executed by the runtimes.

You can also download a [full IDE in the Tech Forum.](https://tech.forums.softwareag.com/t/webmethods-service-designer-download/235227)  
With the MSR you still implement your integrations using the Service Designer and you do it with a local instance of the MSR.  
You manage your generated code in Git, with feature branching and pull requests (if you want.)  
You then build a Docker image and push it to a container registry.  
You can deploy the resulting image in a simple Docker host, in Container as a Service platforms or in Kubernetes (or OpenShift.)  
You can use the traditional automated test tools (like Postman / Newman.)  
And of course you can orchestrate all these activities using the CI/CD tool of your choice (Jenkins, Github actions, Azure Pipelines, ...)

Other useful links:
-   [Customer Management microservice showcase](https://github.com/staillansag/msr-customer-management-v2)
-   [Building an integration microservice from A to Z with webMethods and Kubernetes](https://tech.forums.softwareag.com/t/building-an-integration-microservice-from-a-to-z-with-webmethods-and-kubernetes/267171/1)
-   [webMethods Product Deep Dive: Microservices Runtime and Containers IUG 2022](https://tech.forums.softwareag.com/t/webmethods-product-deep-dive-microservices-runtime-and-containers-iug-2022/267502)

### Serverless and hybrid integrations

webMethods underwent another major transformation in the last few years: you can now run your integrations in the Cloud, in a platform fully managed by Software AG.  
The result is webMethods.io: an integration Platform as a Service (iPaaS) which focuses on agility.

While integrations on the on-premise version of webMethods require specific technical knowledge, the iPaaS approach is to make these integrations accessible to as many people as possible.  
The powerful but sometimes complex Service Designer can be replaced by a streamlined development environment based on the web browser.
The traditional flow services are complemented with a workflow engine that follows a nocode model.  
A new population of citizen integrators can now create and maintain integrations: Business Analysts, Human Resource specialists, Business Application managers, etc. As a rule of thumb, people who can manage Business process will be comfortable using the iPaaS' workflow engine.

You can try the iPaaS by [creating an account in our Sign Up page.](https://signup.softwareag.cloud/#/advanced)  
The iPaaS comprises several products: Integration, B2B, MFT, API management (API Gateway and Developer Portal) & Cloud Container. You can try each product and if you want you can convert your webMethods.io Integration trial into a free forever subscription with 1000 monthly transactions.

Other useful links:
-   [Youtube tutorials](https://www.youtube.com/playlist?list=PL3HwmrSYjxiOSBXu9OqiOmcresQDCk9Xg)

### API Management

