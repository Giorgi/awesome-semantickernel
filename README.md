# awesome-semantickernel
 Awesome list of tools and projects with the awesome semantic kernel framework

 > Curated list of tools and projects using semantic kernel.

Semantic kernel is an amazing framework to get LLM projects done in a matter of no time and the ecosystem is growing fast. Here is an attempt to keep track of the initiatives around semantic kernel.

Contributions welcome. Add links through pull requests or create an issue to start a discussion. Please read the [contribution guidelines](contributing.md) before contributing.

## Table of Contents

- [Awesome semantickernel ](#-awesome-semantickernel--)
  - [Table of Contents](#table-of-contents)
  - [Semantickernel Framework](#semantickernel-framework)
  - [Plugins](#plugins)
  - [Open Source Projects](#open-source-projects)
  - [Learn](#learn)
    - [Notebooks](#notebooks)
    - [Videos](#videos)
    - [Articles](#articles)
  - [Alternatives](#alternatives)
  - [Complement to this list](#complement-to-this-list)

## Semantickernel Framework
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): the original  ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social) 
- [Concepts](https://learn.microsoft.com/en-us/semantic-kernel/overview/): Semantic Kernel concepts doc 
- [Discord discussion](https://aka.ms/SKDiscord)
- [Semantic Kernel Blog](https://devblogs.microsoft.com/semantic-kernel/): The Official Semantic Kernel blog 
- [Semantic Kernel starter](https://github.com/microsoft/semantic-kernel-starters): Starter Projects for Semantic Kernel
- [VisualStudio Code Tool](https://marketplace.visualstudio.com/items?itemName=ms-semantic-kernel.semantic-kernel): Visual Code Studio Semantic Kernel Extension

## Plugins
Plugins are at the heart of unlocking more potential with your [Semantic Kernel](https://github.com/microsoft/semantic-kernel) applications. They allow you to connect to external data sources and give large language models tools to be able to interact with native functions and API services.

If you want to try out your plugins and you do not have a ChatGPT plus subscription or are off the waitlist, you can test this directly **for free** using the Semantic Kernel!

See [this tutorial doc](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/chatgpt-plugins) or watch the [video](https://youtu.be/W_xF8PcdT78) for how to get set up.

**Why:** Microsoft is standardizing around the [plugin architecture](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/plugins?tabs=Csharp) for all of its internal AI copilots
and encourage developers to use them for their own applications. This hackathon serves to jumpstart a larger plugin ecosystem that is valuable to the broader community.

**How:** Follow the getting started guides for creating a plugin
- **C#** - [(Video)](https://youtu.be/T7XLn11rpYI) | [(Repo) Semantic Kernel ChatGPT plugin starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-csharp-chatgpt-plugin)
- **Python** - [(Video)](https://youtu.be/_4HZCdd3OxI) | [(Repo) Semantic Kernel Python Flask (and plugin) Starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-python-flask)

## Open Source Projects
- [Conversational Speaker](https://github.com/microsoft/conversational-speaker): uses a Raspberry Pi (or desktop) to enable spoken conversation with OpenAI large language models. This implementation listens to speech, processes the conversation through the OpenAI service, and responds back.
- [SolidWorks-Copilot](https://github.com/weianweigan/SolidWorks-Copilot) : Your SolidWorks Copoilt based on LLM(ChatGPT) and semantical kernel
- [Email-Copilot](https://github.com/jogendrasinghgurjar/email-copilot): Email-copilot for Outlook aims to revolutionize email management by leveraging natural language processing to streamline drafting, responding, and organizing emails
- [SS.SemanticKernel.Extensions](https://github.com/chenrensong/SS.SemanticKernel.Extensions):  This extension enables you to generate text embeddings with a semantic-based kernel function.
- [A port of the Python example that answers questions about 2022 Winter Olympics](https://github.com/afederici75/SKWinterOlympics)
- [Fantasy Copilot](https://github.com/Richasy/FantasyCopilot): Fantasy Copilot integrates Open AI and Azure's AI services, dedicated to building a personal assistant tool with a large language model as the core and high scalability 
- [sk-ingest](https://github.com/craigomatic/sk-ingest): Small library to make it easier to BYO data for use with Semantic Kernel and LLMs 
- [sk-classifier](https://github.com/craigomatic/sk-classifier): This small sample project shows how to perform basic classification on a series on prompts, against a pre-defined series of classifications using Semantic Kernel
- [Using Semantic Kernel to Summarize Youtube Videos](https://github.com/RogerBarreto/sk-youtube-summarizer)
- [semantic-kernel-LLamaSharp](https://github.com/xbotter/semantic-kernel-LLamaSharp) use LLamaSharp to implement the Completion and Embedding interfaces of the semantic kernel
- [semantic-kernel-ERNIE-Bot](https://github.com/custouch/semantic-kernel-ERNIE-Bot): Semantic Kernel 集成文心千帆
- [Elsa.SemanticKernel](https://github.com/rysweet/Elsa.SemanticKernel): SemanticKernel Activity Provider for Elsa Workflows
- [Write a blog using Semantic Kernel](https://github.com/devedium/WriteABlog) 


## Learn

### Notebooks
- [A collection of C# notebooks to get you started with Semantic Kernel quickly](https://github.com/johnmaeda/SK-Recipes)
- [Intelligent app workshop](https://github.com/Azure/intelligent-app-workshop): This is an envisioning workshop, based on Microsoft's Copilot stack, to rethink user experience, architecture, and app development by leveraging the intelligence of foundation models
- [Project Miyagi - Financial coach](https://github.com/Azure-Samples/miyagi): showcasing AI-first application architectures and generative AI capabilities with nascent design patterns to embed intelligence. A Hyper-personalized agent powered by SoTA foundation models and event-driven architecture
- [Tutorial: ChatGPT + Enterprise data with Semantic Kernel, OpenAI and Azure Cognitive Search](https://github.com/Azure-Samples/semantic-kernel-rag-chat)
- [Learn Azure OpenAI Service with .NET](https://github.com/kinfey/dotNETOAIBooks): This is a Azure OpenAI book for .NET Developer
- [MSFabricCopilotWorkshop](https://github.com/kinfey/MSFabricCopilotWorkshop) : Building Microsoft Fabric Copilot App Workshop
- [Semantic Kernel OpenAPI Skill Sample Project](https://github.com/mbenachour/semantic-kernel-course) This is a sample project to demonstrate the Semantic Kernel OpenAPI skill. It consists of a clothing API, which is a Swagger API, and a Copilot chat app.

### Videos

### Articles


## Complement to this list

- [Open LLMs](https://github.com/eugeneyan/open-llms): A list of open LLMs available for commercial use ![GitHub Repo stars](https://img.shields.io/github/stars/eugeneyan/open-llms?style=social)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM): Awesome-LLM: a curated list of Large Language Model resources. ![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/Awesome-LLM?style=social)
- [LLaMA Cult and More](https://github.com/shm007g/LLaMA-Cult-and-More): Keeping Track of Affordable LLMs, 🦙 Cult and More ![GitHub Repo stars](https://img.shields.io/github/stars/shm007g/LLaMA-Cult-and-More?style=social)