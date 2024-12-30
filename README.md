# AgenticAI
This repo is solely for study purpose of AgenticAI
AGENTIC AI - Notes by Bharath

Important points:
Started in Mid 2024 also called AI Agent, Multi AI Agents
More than GenAI
The diff between GenAI and agentic AI is:


GenAi -> create content -> LLM Model
Query ->(prompt) -> LLm -> Output {Generating content}
Also called prompt finetuning

RAG - > Retrieve relevant content that is upto date by giving access to an llm to an external source where data is stored in vectors like ChromeDB(Langchain is used)

Agentic AI -> Autonomous AI Systems / Agents (perform their own tasks)
They have a goal to achieve
All the AI systems work independently to achieve the goal
LangGraph (Agentic AI framework), langflow, Phidata
Solve Complex workflow
Can finetune themselves to perform much more better

Summary
Genai when access to external source makes workflow complex, in agentic AI goal is based on business outcome


Example:

Custom Bot -> Agentic AI -> interacts with many things

Query: Hey i have 1000$ Buy some stocks and sell it in 5 days that can give 50% profit.
Query: Compare tesla and nvdia stock and suggest best one to purchase


Here each workflow is a separate task and each task is handled by an AI separately. These all work together simultaneously  to achieve the goal and then give the output.

Open source framework 
AutoGen(Microsoft) -> https://github.com/microsoft/autogen
LangFlow(No code tool for Agentic AI) -> Dragdrop -> End code will we given -> Later can be deployed - > https://www.langflow.org/
LangGraph(More complex) -> https://www.langchain.com/langgraph
PhiData - > https://www.phidata.com/
CrewAI -> https://www.crewai.com







The Influence of AI in 2025: Trends you should not miss
Agentic AI
AI Infrastructure -> Gpus as PAAS, Inference compute engine(Fast responses)
Large Models (LLm, LVM) -> Billion to Trillion parameters
AI Edge Devices for Gen AI -> Jetson Nano oron
Small Models(Phi3) -> OpenSource less para for fine tuning
Security AI -> Regulations
Lot of Open Source Models

Prerequisites
Python
LangChain 

Reference Links:
What is Agentic AI? Important For GEN AI In 2025
Agentic AI Is The Future- GEN AI Trends In 2025
Building Agentic AI Free Course For Everyone
Detailed Prerequisites To Start Learning Agentic AI With Free Videos And Materials

Phidata Docs

Docs url: https://docs.phidata.com/
Models: https://docs.phidata.com/models
Agents: https://docs.phidata.com/agents
Knowledge(External source or domain specific): https://docs.phidata.comj/knowledge
Storage:https://docs.phidata.com/storage (Formats)
VectorDbs: https://docs.phidata.com/vectordb 
Chunking: https://docs.phidata.com/chunking 
Embeddings: https://docs.phidata.com/embeddings 
Tools: https://docs.phidata.com/tools 

Building your first Agentic AI
Using phidata we can use any llm and turn it into agentic ai
We can easily integrate an open source llm to solve complex workflows

Playground used -> Google Colab

Suppose i ask “hey can you summarise and recommend the nvidia stock”, then the chatbot will contact the agents -> the first agent will be ai agent that will do all things or interactions to get details of the stock, second will get the info from news or web search(new info) -> combine all the data and then send it llm to summarize to output the result. 





















Financial agent
Source -> Building Your First Agentic AI- Financial Agent With Phidata
Code - > AgenticAI.ipynb
Example input text: Summarize analyst recommendations and share the latest news for NVDA
Corresponding output screenshot








Building Multi Agentic AI RAG using Vector Database 

Here we will use Agentic AI where they will start communicating with vector databases to ask for a query and retrieve the appropriate response. Here the vector databases are external.

Source: 2-Building Multi Agentic AI RAG With Vector Database

