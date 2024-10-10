# System Integrator Partner - AI Solution Accelerator Repository

This is a central hub for solution accelerators for Microsoft SI partners to use for building customer solutions for AI Design Wins


## Solution Accelerators

### Chat with your data
Users can chat with their own data by combining Azure Cognitive Search and Large Language Models (LLMs) to create a conversational search experience. It enables increased user efficiency by minimizing endpoints required to access internal company knowledgebases.
- [Solution Accelerator](https://github.com/Azure-Samples/chat-with-your-data-solution-accelerator)

### Build your own copilot
Users can see in action how to create their own copilots using Azure OpenAI Service, Azure AI Search, and Microsoft Fabric. The repository includes reusable architecture, code snippets, and deployment scripts to help accelerate AI projects.

#### Client Advisor
This copilot helps client advisors to save time and prepare relevant discussion topics for scheduled meetings. It provides an overview of daily client meetings with seamless navigation between viewing client profiles and chatting with structured data. Altogether, these features streamline meeting preparation for the advisors and result in more productive conversations with clients.
- [Solution Accelerator](https://github.com/microsoft/Build-your-own-copilot-Solution-Accelerator?tab=readme-ov-file#client-advsior)
  
#### Researcher
This copilot helps the researchers find relevant articles and grants available for their research topic easily using a conversational assistant. Researcher can generate different sections of a grant application with a simple button click, then they can refine the prompts and regenerate individual sections to add more details as needed. Finally, the generated grant application can be exported as a PDF or a Microsoft Word document for further processing.
- [Solution Accelerator](https://github.com/microsoft/Build-your-own-copilot-Solution-Accelerator?tab=readme-ov-file#research-assistant)

#### Document Generation
This copilot is a powerful tool that helps you create your own AI assistant(s). The accelerator can be used by any customer looking for reusable architecture and code snippets to build an AI assistant(s) with their own enterprise data. It leverages Azure Open AI Service and Azure AI Search, to identify relevant documents, summarize unstructured information, and generate Word document templates using your own data.
- [Solution Accelerator](https://github.com/microsoft/Generic-Build-your-own-copilot-Solution-Accelerator)  

### Conversation knowledge mining
Users can maximize their contact center efficiency and customer satisfaction by utilizing AI driven knowledge mining enabled by Fabric, Azure Speech Service and Azure OpenAI Service. Gain valuable post-conversation insights to inform actions, improve product offerings, optimize operational efficiency and improve customer experience.
- [Solution Accelerator](https://github.com/microsoft/Customer-Service-Conversational-Insights-with-Azure-OpenAI-Services)  


### Build your own copilot End to End Solution Accelerator
  - Production Ready Reference Solution for how to build your own copilot using Azure services including: Azure Cosmos DB for NoSQL, Azure OpenAI Service, Azure Kubernetes Service or Azure Container Apps. Uses Semantic Kernel plugins for OpenAI, Cosmos DB connectors, and semantic cache. Built in C#.
    - AKS or ACA, Container Registry, Managed Identity, Key Vault, Log Analytics, Azure Monitor
    - [Solution Accelerator](https://github.com/Azure/buildyourowncopilot)
    - [Hackathon Workshop - coming soon]()


## Sample Applications

### Build a copilot App in C# and Azure Cosmos DB for NoSQL
  - This sample application shows how to build a Generative-AI application using Azure Cosmos DB for NoSQL using its new vector search capabilities and Azure OpenAI Service and Semantic Kernel. The sample provides practical guidance on many concepts you will need to design and build these types of applications.
    - Azure App Service, C#, Native SDK, Semantic Kernel
    - [Sample App](https://github.com/AzureCosmosDB/cosmosdb-nosql-copilot)
    - [Hands on Lab](https://github.com/AzureCosmosDB/cosmosdb-nosql-copilot/tree/start)

### Build a copilot App in Python with Azure Cosmos DB for NoSQL
  - This sample demonstrates how to build a RAG Pattern application using a subset of the Movie Lens dataset. This sample will leverage the Python SDK for Azure Cosmos DB for NoSQL to perform vector search for RAG, store and retrieve chat history, and store the vectors of the chat history to use as a semantic cache. Azure OpenAI to generate embeddings and LLM completions.
    - Jupypter Notebook, Python, Azure Cosmos DB for NoSQL
    - [Sample App](https://github.com/microsoft/AzureDataRetrievalAugmentedGenerationSamples/blob/main/Python/CosmosDB-NoSQL_VectorSearch/CosmosDB-NoSQL-Quickstart-RAG-Chatbot.ipynb)
   
### Build a Graph RAG application 
  - Cosmos AI Graph: An AI-Powered Graph and Knowledge Graph Solution with Azure Cosmos DB. Combine the power of baseline (vetor search) with the contextual and relationship data captured in  a knowledge graph to bring you RAG apps to the next level with Azure Cosmos DB.
  - Python, Azure Cosmos DB for NoSQL or Azure Cosmos DB for MongoDB (vCore)
  - [Sample App](https://github.com/azurecosmosdb/cosmosaigraph)

  
## Other content

  - TBD


