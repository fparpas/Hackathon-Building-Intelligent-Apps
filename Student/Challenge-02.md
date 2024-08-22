# Build intelligent applications with Semantic Kernel (C# or Python)

[< Previous Challenge](./Challenge-01.md) - **[Home](../README.md)** - [Next Challenge >](./Challenge-03.md) - 

## Introduction

Semantic Kernel is a lightweight, open-source development kit that lets you easily build AI agents and integrate the latest AI models into your C#, Python, or Java codebase. It serves as an efficient middleware that enables rapid delivery of enterprise-grade solutions. It achieves this by allowing you to define plugins that can be chained together in just a few lines of code.

It combines prompts with existing APIs to perform actions. By describing your existing code to AI models, they’ll be called to address requests. When a request is made the model calls a function, and Semantic Kernel is the middleware translating the model's request to a function call and passes the results back to the model.

This hands-on session will guide you through the process of developing your first intelligent app with Semantic Kernel
## Description

In just a few steps, you can build your first AI agent with Semantic Kernel in either Python, .NET, or Java. 
You should complete the following steps in the [reference guide](https://learn.microsoft.com/en-us/semantic-kernel/get-started/quick-start-guide?pivots=programming-language-csharp):

- Install the necessary packages
- Create a back-and-forth conversation with an AI
- Give an AI agent the ability to run your code
- Watch the AI create plans on the fly

After completing the above you should create a [plugin to retrieve data from external source](https://learn.microsoft.com/en-us/semantic-kernel/concepts/plugins/using-data-retrieval-functions-for-rag) such us Azure AI Search and generate grounded responses with semantic search.
## Success Criteria

- Ensure that your application is running and your able to debug the application
- Set a break point in one of the plugins and hit the break point with a user prompt
- Create a plugin to retrieve data from external source (Azure AI Search) and generate grounded responses.

## Learning Resources
- [Introduction to Semantic Kernel | Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/overview/)
- [Plugins in Semantic Kernel | Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/concepts/plugins/?pivots=programming-language-csharp)
- [What are Planners in Semantic Kernel | Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/concepts/planning?pivots=programming-language-csharp)
- [In-depth Semantic Kernel Demos | Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/get-started/detailed-samples?pivots=programming-language-csharp)
- [Semantic Kernel GitHub](https://github.com/microsoft/semantic-kernel)
