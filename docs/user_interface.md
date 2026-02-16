# User Interface

## Welcome to the University of Arizona GenAI Platform!

On the left-hand side of the UI, you will see an expandable menu that lets you start a new chat, access previous chats, complete searches, create folders, and add notes. 

<img width="700" height="350" alt="orai" src="../assets/ui.webp" /> 

<br>
<br>

## Model Choice
At the top of the chatbot interface, you can select and expand a dropdown menu to choose the model you want to use. For example, here we are using Claude Haiku 4.5 from Anthropic. Next to the drop-down is a plus symbol that lets you add more models and chat with them all simultaneously, allowing you to compare their outputs.

<img width="500" height="250" alt="orai" src="../assets/model_choice.webp" />


## Current Available Models

??? Tip "Anthropic Claude Haiku 4.5"
    Works with: Text and images

    Best for: Most student needs and general campus use across departments

    Claude Haiku is one of the best AI models available through AWS Bedrock. It provides intelligent, quick responses perfect for academic and administrative tasks. It can handle long documents and conversations (up to 200,000 words) and offers strong analytical capabilities.

    Ideal campus applications:

    * Homework and assignment assistance (check with your instructor about course AI policies)
    * Essay writing and research support
    * Study assistance and tutoring
    * Course material development
    * Student advising and support services
    * Administrative automation
    * Image analysis (charts, diagrams, handwritten work)

??? Tip "Google Gemma 3 12B IT"
    Works with: Text and images

    Best for: Multilingual applications and extended conversations

    Gemma excels at maintaining long conversations (128,000 words), works with multiple languages, and handles both text and images efficiently while delivering solid performance.

    Ideal campus applications:

    * International student services
    * Extended tutoring sessions
    * Multi-language document processing
    * High-volume projects
    * Departmental chatbots
    * Multilingual research support


??? Tip "OpenAI - GPT OSS 120B"
    Works with: Text only (no images)

    Best for: Complex analytical tasks requiring advanced reasoning

    This model delivers GPT-4-level performance with greater flexibility for customization. It handles long conversations well (128,000 words) and excels at reasoning and using tools, though it cannot process images.

    Ideal campus applications:

    * Complex analytical projects
    * Advanced reasoning tasks
    * Tool integration workflows
    * Custom AI applications
    * Research requiring GPT-4 level capability
    * Text-only document analysis

??? Tip "Meta - LLAMA 4 Maverick 17B Instruct"

    Works with: Text and images

    Best for: Analyzing very long documents or comprehensive research materials

    Llama's standout feature is its ability to handle extremely long documents (up to 1 million words—roughly 3-4 novels). It supports multiple languages and is particularly strong at coding and technical reasoning.

    Ideal campus applications:

    * Dissertation and thesis analysis
    * Large-scale literature reviews
    * Processing entire course readers or textbooks
    * Comprehensive document summarization
    * Multi-chapter book analysis
    * Long-form research synthesis

??? Tip "Amazon - Nova Pro"

    Works with: Text and images

    Best for: Teams prioritizing AWS integration and enterprise support

    As Amazon's own model, Nova Pro offers excellent integration with other AWS services used on campus. It balances good performance and handles very long contexts (300,000 words). Supports many languages.

    Ideal campus applications:

    * Question answering systems
    * Content generation and summarization
    * Knowledge base integration
    * Projects already using AWS infrastructure
    * RAG (Retrieval-Augmented Generation) applications
    * Multi-language content workflows

<br>
<br>

## Create Folders
To help with organization, you can create folders and move chats to them; These folders can be named and have a set System Prompt. A system prompt is a foundational instruction set given to a large language model (LLM) that defines its role, behavior, tone, constraints, and capabilities for a specific use case or application. The system prompt will be applied to all of the chats in the folder.

<img width="700" height="350" alt="orai" src="../assets/create_folder.webp" /> 

Once your folder is created, it will be visible in the side panel. You can drag existing conversations into the folder and start new ones.

<img width="700" height="350" alt="orai" src="../assets/create_folder2.webp" /> 

<br>
<br>

## Upload Files

<img width="30" height="30" alt="orai" src="../assets/more.png" />
<img width="120" height="40" alt="orai" src="../assets/upload_files.png" />



<br>
<br>

## Capture
<img width="30" height="30" alt="orai" src="../assets/more.png" />
<img width="120" height="40" alt="orai" src="../assets/capture.png" />

This feature lets you take a screen capture of your desktop, a browser tab, or an open window. The capture will be uploaded to the chat. 

<br>
<br>

## Attach Webpage

<img width="30" height="30" alt="orai" src="../assets/more.png" />
<img width="140" height="50" alt="orai" src="../assets/attach_webpage.png" />

<br>
<br>

## Attach Knowledge

<img width="30" height="30" alt="orai" src="../assets/more.png" />
<img width="150" height="60" alt="orai" src="../assets/attach_knowledge.png" />

<br>
<br>

## Reference Chats

<img width="30" height="30" alt="orai" src="../assets/more.png" />
<img width="150" height="60" alt="orai" src="../assets/reference_charts.png" />

This option lets you reference previous chats while you chat in a current session. 

<br>
<br>

## Web Search 
<img width="30" height="30" alt="orai" src="../assets/integrations.png" />
<img width="250" height="70" alt="orai" src="../assets/web_search.png" />

Enabling web search allows the LLMs to search the internet and bring you back results. With the web search tool disabled, LLM responses are limited to its training.  
<br>
<br>

## Code Interpreter

<img width="30" height="30" alt="orai" src="../assets/integrations.png" />
<img width="250" height="70" alt="orai" src="../assets/code_interpreter.png" />

Enabling the code interpreter allows you execute code directly in the chat. 
