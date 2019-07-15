---
languages:
- json
products:
- azure
page_type: sample
description: "Resource Manager templates to get started with Azure API Management and Service Fabric, together, in Azure."
---

# Service Fabric + Azure API Management

This repo contains Resource Manager templates to get started with Azure API Management and Service Fabric, together, in Azure. 

Cloud applications typically need a front-end gateway to provide a single point of ingress for users, devices, or other applications. In Service Fabric, a gateway can be any stateless service such as an [ASP.NET Core application](https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-communication-aspnetcore), or another service designed for traffic ingress, such as [Event Hubs](https://docs.microsoft.com/azure/event-hubs/), [IoT Hub](https://docs.microsoft.com/azure/iot-hub/), or [Azure API Management](https://docs.microsoft.com/azure/api-management/).

The Resource Manager templates in this repo deploy API Management and a Service Fabric cluster into a shared Virtual Network, allowing API Management to communicate directly with Service Fabric so it can perform service discovery, service partition resolution, and forward traffic directly to any backend service in Service Fabric. 

# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
