# Artificial Intelligence Interview Questions

## Overview

Artificial Intelligence interview questions. 

## General Questions

- What is AI?
- What is Machine Learning(ML)?
- What is Deep Learning?
- How are AI, ML and Deep Learning are related?
- What kind of problems can you solve with AI?
- How would you start solving a real world problem with AI?
- What are some of the ethical AI principles? 
- What are some of the challenges that you run into when solving a problem with AI?
- [What are some of the best practices for scaling?](https://docs.microsoft.com/azure/azure-monitor/autoscale/autoscale-best-practices?WT.mc_id=aiml-10703-ayyonet)

## Azure AI Platform

- [Start free Azure AI](https://azure.microsoft.com/free/ai/?WT.mc_id=aiml-14043-ayyonet)
- [Zero to Hero Azure AI Learning Resources](https://azure.microsoft.com/overview/ai-platform/dev-resources/?WT.mc_id=aiml-14043-ayyonet)
- [Azure AI Machine Learning Documentation](https://docs.microsoft.com/azure/?product=ai-machine-learning&WT.mc_id=aiml-14043-ayyonet)
- [Artificial intelligence for developers](https://azure.microsoft.com/overview/ai-platform/dev-resources/?WT.mc_id=aiml-14043-ayyonet)
- [Azure Machine Learning for Data Scientists](https://azure.microsoft.com/overview/ai-platform/data-scientist-resources/?WT.mc_id=aiml-14043-ayyonet#learning-journey)

### Cognitive Services

Cognitive Services are Azure's pre-trained AI services that are easy to use, whithout the need of AI expertise. 

- Read more about Cognitive Services Overview at [aka.ms/CognitiveServicesOverview](https://azure.microsoft.com/services/cognitive-services/?WT.mc_id=aiml-14043-ayyonet)
- [Azure Cognitive Services Documentation](https://docs.microsoft.com/azure/cognitive-services/?WT.mc_id=aiml-14043-ayyonet)
- [Zero to Hero Azure AI Learning Resources](https://azure.microsoft.com/overview/ai-platform/dev-resources/?WT.mc_id=aiml-14043-ayyonet#learning-journey)
- [How to configure Cloud Services to auto scale?](https://docs.microsoft.com/azure/cloud-services/cloud-services-how-to-scale-portal?WT.mc_id=aiml-10703-ayyonet)

#### Vision

##### Computer Vision

- What are Azure Computer Vision APIs?

The cloud-based Computer Vision API provides developers with access to advanced algorithms for processing images and returning information. By uploading an image or specifying an image URL, Microsoft Computer Vision algorithms can analyze visual content in different ways based on inputs and user choices.

[Computer Vision Documentation](https://docs.microsoft.com/azure/cognitive-services/computer-vision/?WT.mc_id=aiml-14043-ayyonet)


##### Custom Vision

##### Face

##### Form Recognizer

##### Ink Recognizer

##### Video Indexer 

##### Spatial Analysis

- What is Spatial Analysis Services?

Computer Vision spatial analysis is a new feature of Azure Cognitive Services Computer Vision that helps organizations maximize the value of their physical spaces by understanding people's movements and presence within a given area. It allows you to ingest video from CCTV or surveillance cameras, run AI operations to extract insights from the video streams, and generate events to be used by other systems. With input from a camera stream, an AI operation can do things like count the number of people entering a space or measure compliance with face mask and social distancing guidelines.

[Spatial Analysis Documentation](https://docs.microsoft.com/azure/cognitive-services/computer-vision/intro-to-spatial-analysis-public-preview?WT.mc_id=aiml-14043-ayyonet)

- What are some of the characteristics and limitations for Computer Vision Spatial Analysis?

Computer Vision spatial analysis is a building block for creating an end-to-end solution which includes other building blocks. It's not possible to provide universally applicable estimates of accuracy for the actual system you are planning to deploy.

[Source Documentation](https://docs.microsoft.com/legal/cognitive-services/computer-vision/accuracy-and-limitations?context=%2fazure%2fcognitive-services%2fComputer-vision%2fcontext%2fcontext&WT.mc_id=aiml-14043-ayyonet)

- How accurate is spatial analysis?

System accuracy depends on a number of factors, including core model accuracy, camera placement, configuration of regions of interest, how people interact with the system, and how people interpret the system's output. The following sections are designed to help you understand key concepts about accuracy as they apply to using spatial analysis.

[Source Documentation](https://docs.microsoft.com/legal/cognitive-services/computer-vision/accuracy-and-limitations?context=%2fazure%2fcognitive-services%2fComputer-vision%2fcontext%2fcontext&WT.mc_id=aiml-14043-ayyonet#how-accurate-is-spatial-analysis)

#### Speech

##### Speech to Text

##### Text to Speech

- [How do you improve synthesis with Speech Synthesis Markup Language (SSML)?](https://docs.microsoft.com/azure/cognitive-services/speech-service/speech-synthesis-markup?tabs=csharp&WT.mc_id=aiml-14043-ayyonet)

##### Speech Translation

##### Voice Assistants

##### Speaker Recognition

#### Language

##### Text Analytics

- What are the Text Analytics APIs and their use cases?

The Text Analytics API is a cloud-based service that provides advanced natural language processing over raw text, and includes four main functions: sentiment analysis, key phrase extraction, named entity recognition, and language detection.

[Text Analytics API Documentation](https://docs.microsoft.com/azure/cognitive-services/text-analytics/?WT.mc_id=aiml-14043-ayyonet)

- How can you use Text Analytics for health?

Text Analytics for health is a feature of the Text Analytics API service that extracts and labels relevant medical information from unstructured texts such as doctor's notes, discharge summaries, clinical documents, and electronic health records. 

[Source Documentation](https://docs.microsoft.com/azure/cognitive-services/text-analytics/how-tos/text-analytics-for-health?tabs=ner&WT.mc_id=aiml-14043-ayyonet)

- How do you make sure health data is secure and private when using Text Analytics for Health?

  - You can run the [Text Analytics for Health Service in a container](https://docs.microsoft.com/azure/cognitive-services/text-analytics/how-tos/text-analytics-how-to-install-containers?tabs=healthcare&WT.mc_id=aiml-14043-ayyonet) on your own environment and make sure your data never leaves your device.
  - When using the REST endpoints to use the API, Azure has [Privacy](https://azure.microsoft.com/support/legal/cognitive-services-compliance-and-privacy/?WT.mc_id=aiml-14043-ayyonet) and [HIPAA](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html) complience for USA. Check your local 
  - You can check the other [omplience offerings for Cognitive Services in this documentation](https://azure.microsoft.com/resources/microsoft-azure-compliance-offerings/?WT.mc_id=aiml-14043-ayyonet)

##### Q&A Maker & Bots Framework

-[Try Q&A Maker and Bots Framework for free](https://azure.microsoft.com/try/cognitive-services/?unauthorized=1&WT.mc_id=aiml-14043-ayyonet)

- [What is QnA Maker?](https://docs.microsoft.com/azure/cognitive-services/qnamaker/overview/overview?WT.mc_id=aiml-14043-ayyonet)

QnA Maker is a cloud-based API service that lets you create a conversational question-and-answer layer over your existing data. Use it to build a knowledge base by extracting questions and answers from your semi-structured content, including FAQs, manuals, and documents. Answer users’ questions with the best answers from the QnAs in your knowledge base—automatically. Your knowledge base gets smarter, too, as it continually learns from user behavior.

- What is the difference between Azure Bot Service and the Bot Framework SDK and tools?

Azure Bot Service is managed serviced that helps you create and manage conversational application on Azure through a single service. Use Azure Bot Service to create a bot, connect it to your customers on a variety of conversation channels, integrate other Azure services, and learn about how your application is used through analytics.

The Bot Framework SDK provides the most comprehensive experience for delivering bots. It includes a set of open-source SDKs for building conversational experiences, the Bot Framework Emulator for locally testing and debugging your bot, and a set of command-line tools to help you create and manage your bot’s different services more efficiently.

- What's the difference between Bot Framework and QnA Maker Knowledge Base?

[The Bot Framework](https://docs.microsoft.com/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet), along with the Azure Bot Service, provides tools to build, test, deploy, and manage intelligent bots, all in one place. The Bot Framework includes a modular and extensible SDK for building bots, as well as tools, templates, and related AI services. With this framework, developers can create bots that use speech, understand natural language, handle questions and answers, and more. 

You can [create your bot on Azure Portal](https://docs.microsoft.com/azure/bot-service/abs-quickstart?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet) or use [C#](https://docs.microsoft.com/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0&tabs=vs&WT.mc_id=aiml-14043-ayyonet)| [JavaScript](https://docs.microsoft.com/azure/bot-service/javascript/bot-builder-javascript-quickstart?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet) | [Python](https://docs.microsoft.com/azure/bot-service/python/bot-builder-python-quickstart?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet) [bot templates](https://docs.microsoft.com/previous-versions/azure/bot-service/bot-service-concept-templates?view=azure-bot-service-3.0&WT.mc_id=aiml-14043-ayyonet) for local development. See [creating a basic bot](https://docs.microsoft.com/azure/bot-service/bot-builder-tutorial-create-basic-bot?view=azure-bot-service-4.0&tabs=javascript%2Cvc&WT.mc_id=aiml-14043-ayyonet) and [adding QnA maker and redeploy tutorials](https://docs.microsoft.com/azure/bot-service/bot-builder-tutorial-add-qna?view=azure-bot-service-4.0&tabs=csharp&WT.mc_id=aiml-14043-ayyonet).

Some knowledge bots may simply aim to answer frequently asked questions (FAQs). [QnA Maker](https://docs.microsoft.com/azure/cognitive-services/qnamaker/?WT.mc_id=aiml-14043-ayyonet) is a powerful tool that's designed specifically for this use case. QnA Maker has the built-in ability to scrape questions and answers from an existing FAQ site, plus it also allows you to manually configure your own custom list of questions and answers. QnA Maker has natural language processing abilities, enabling it to even provide answers to questions that are worded slightly differently than expected. However, it does not have semantic language understanding abilities. It cannot determine that a puppy is a type of dog, for example.

A very important thing to know about QnA Maker is that it doesn't inherently understand the meaning of the words where as [Language Understanding(LUIS)](https://www.luis.ai/?WT.mc_id=aiml-14043-ayyonet) can analyze a user's message and determine user's intent. Bot using QnA maker is mapping the questions to the answers that are configures in knowledge base. If the answer to a question does not exist in the knowledge base, it finds another question which is similar in structure and might return an answer to a wrong question. 

You can create your QnA pairs and then test and re-train your bot by using the "Inspect" button under the conversation to select an alternative answer for each incorrect answer that is given.

- How to get started building with Bot Service?

Bot Service includes five templates to help you get started with building bots. These templates provide a fully functional bot out of the box to help you get started quickly. When you create a bot, you choose a template and the SDK language for your bot. Find the different template descriptions from [basic to proactive bot templates descriptions here](https://docs.microsoft.com/previous-versions/azure/bot-service/bot-service-concept-templates?view=azure-bot-service-3.0&WT.mc_id=aiml-14043-ayyonet).

- [How can I combine Cognitive Search, QnA Maker and Language Understanding?](https://docs.microsoft.com/azure/bot-service/bot-service-design-pattern-knowledge-base?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet#combining-search-qna-maker-andor-luis)

[The Bot Framework](https://docs.microsoft.com/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet), along with the Azure Bot Service, provides tools to build, test, deploy, and manage intelligent bots, all in one place. The Bot Framework includes a modular and extensible SDK for building bots, as well as tools, templates, and related AI services. With this framework, developers can create bots that use speech, understand natural language, handle questions and answers, and more.

- [Why migrate to the Bot Framework v4?](https://docs.microsoft.com/azure/bot-service/migration/migration-overview?view=azure-bot-service-4.0&tabs=csharp&WT.mc_id=aiml-14043-ayyonet#why-migrate)

- [How much Q&A maker cost?](https://azure.microsoft.com/pricing/details/cognitive-services/qna-maker/?WT.mc_id=aiml-14043-ayyonet)

- [How does Bot Framework work with other AI services?](https://docs.microsoft.com/previous-versions/azure/bot-service/bot-service-concept-intelligence?view=azure-bot-service-3.0&WT.mc_id=aiml-14043-ayyonet)

- [How to cross training your LUIS and QnA Maker models?](https://docs.microsoft.com/azure/bot-service/bot-builder-concept-cross-train?view=azure-bot-service-4.0&WT.mc_id=aiml-14043-ayyonet)

- [What is the Bot Framework Emulator?](https://github.com/microsoft/BotFramework-Emulator?WT.mc_id=aiml-0000-ayyonet)

The Bot Framework Emulator is a desktop application that allows bot developers to test and debug bots built using the Bot Framework SDK. You can use the Bot Framework Emulator to test bots running either locally on your machine or connect to bots running remotely through a tunnel.

- [Where can I find Bot Builder sample code?](https://github.com/Microsoft/BotBuilder-Samples)

#### Decision

- [What is the minimum required data for Metrics Advisor?](https://docs.microsoft.com/azure/cognitive-services/metrics-advisor/how-tos/onboard-your-data?WT.mc_id=aiml-14043-ayyonet)

##### Anomaly Detector

##### Content Moderator

#####  Personalizer


#### Search


