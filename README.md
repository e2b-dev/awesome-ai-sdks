<!--- 
TBD Add to visual:
Langroid
--->


<h1 align="center">
	:gift: Awesome SDKs For AI Agents
	<p align="center">
		<a href="https://discord.gg/U7KEcGErtQ" target="_blank">
			<img src="https://img.shields.io/static/v1?label=Join&message=%20discord!&color=mediumslateblue">
		</a>
		<a href="https://twitter.com/e2b_dev" target="_blank">
			<img src="https://img.shields.io/twitter/follow/e2b.svg?logo=twitter">
		</a>
	</p>
</h1>

<h3 align="center">
  Try out E2B's <a href="https://e2b.dev/docs?ref=awesome-sdks">sandbox runtime </a> for agents, copilots, and AI apps
</h3>
<h5 align="center">👉 <a href="https://forms.gle/UXQFCogLYrPFvfoUA">Submit new product here</a></h5>


<img src="/assets/visual.png" width="100%" alt="SDKs Repo Visual" />

Welcome to our list of [AI agents](https://github.com/e2b-dev/awesome-ai-agents) SDKs. A database of SDKs, frameworks, libraries, and tools for creating, monitoring, debugging and deploying autonomous [AI agents](https://github.com/e2b-dev/awesome-ai-agents).

The list is done according to our best knowledge, although definitely not comprehensive.
Discussion and feedback are appreciated! :heart:

## Have anything to add?
Do you have something to add or improve about our list? Do it via pull request.

 :star: For any new project, please also include a suggestion for a category in the visual, where it fits the most, or suggest a new category.  :star:


# :mag_right: Monitoring, Observability, Analytics

## [AgentOps](https://www.agentops.ai/)
AgentOps creates tools to make agents actually work, e.g., graphs, monitoring, and replay analytics.

<details>

<!-- ### Description -->

### Links
- [Web](https://www.agentops.ai/)

</details>


## [Context](https://context.ai/)
Context is the product analytics platform for chat interfaces

<details>

<!-- ### Description -->

### Links
- [Web](https://context.ai/)
- [Twitter](https://twitter.com/getcontextai)

</details>


## [Helicone](https://www.helicone.ai/)
An open-source observability platform for GPT-3. Allows to track usage, costs, and latency with one line of code.


<details>

<!-- ### Description -->


### Links
- [Web](https://www.helicone.ai/)
- [GitHub](https://github.com/Helicone/helicone)
- [Linkedin](https://www.linkedin.com/company/helicone/)


</details>



## [Langfuse](https://langfuse.com/)
Langfuse is an open-source analytics for LLM apps. The analytics is currently in a closed alph

<details>

<!-- ### Description -->


### Links
- [Web](https://langfuse.com/)
- [GitHub](https://github.com/langfuse/langfuse)



</details>

## [LangSmith](https://smith.langchain.com/)
A unified platform for debugging, testing, evaluating, and monitoring LLM applications. LangSmith is now in closed beta. 


<details>

<!-- ### Description -->


### Links
- [Web](https://smith.langchain.com/)



</details>


# 🌻: Frontend & UI


## [AgentLabs](https://www.agentlabs.dev/)
A dynamic AI Automation Platform for Interoperability & AI Agent Management


<details>

<!-- ### Description -->

### Links
- [Web](https://www.agentlabs.dev/)
- [GitHub](https://github.com/agentlabs-inc/agentlabs)
- [X ](https://twitter.com/agentlabs_)

### Guides and examples
- [Building a Code Interpreter with AgentLabs and E2B](https://docs.agentlabs.dev/recipes/code-interpreter)

</details>



# :circus_tent: Orchestration


## [AGiXT](https://github.com/Josh-XT/AGiXT)
A dynamic AI Automation Platform for Interoperability & AI Agent Management


<details>

<!-- ### Description -->

### Links
- [GitHub](https://github.com/Josh-XT/AGiXT)
- [Twitter](https://twitter.com/Josh_XT)
- [Discord](https://discord.com/invite/d3TkHRZcjD)

</details>


# :construction: Frameworks for Building Agents

## [Agents](https://github.com/aiwaves-cn/agents)

**Agents** is an open-source library/framework for building autonomous language agents.

<details>

### Description
-   **Long-short Term Memory**: Language agents in the library are equipped with both long-term memory implemented via VectorDB + Semantic Search and short-term memory (working memory) maintained and updated by an LLM.
-   **Tool Usage**: Language agents in the library can use any external tools via  [function-calling](https://platform.openai.com/docs/guides/gpt/function-calling)  and developers can add customized tools/APIs  [here](https://github.com/aiwaves-cn/agents/blob/master/src/agents/Component/ToolComponent.py).
-   **Web Navigation**: Language agents in the library can use search engines to navigate the web and get useful information.
-   **Multi-agent Communication**: In addition to single language agents, the library supports building multi-agent systems in which language agents can communicate with other language agents and the environment. Different from most existing frameworks for multi-agent systems that use pre-defined rules to control the order for agents' action,  **Agents**  includes a  _controller_  function that dynamically decides which agent will perform the next action using an LLM by considering the previous actions, the environment, and the target of the current states. This makes multi-agent communication more flexible.
-   **Human-Agent interaction**: In addition to letting language agents communicate with each other in an environment, our framework seamlessly supports human users to play the role of the agent by himself/herself and input his/her own actions, and interact with other language agents in the environment.
-   **Symbolic Control**: Different from existing frameworks for language agents that only use a simple task description to control the entire multi-agent system over the whole task completion process,  **Agents**  allows users to use an  **SOP (Standard Operation Process)**  that defines subgoals/subtasks for the overall task to customize fine-grained workflows for the language agents.

### Links
- [Paper](https://arxiv.org/pdf/2309.07870.pdf)
- [GitHub](https://github.com/aiwaves-cn/agents)
- [Documentation](https://agents-readthedocsio.readthedocs.io/en/latest/index.html)
- [Tweet](https://twitter.com/wangchunshu/status/1702512370785100133)
</details>


## [Axilla](https://www.axilla.io/)
Axilla is a comprehensive end-to-end open-source LLM framework for TypeScript. It provides a family of modular libraries, which can be incrementally adopted, and together form an end-to-end opinionated framework for AI development.
Axilla targets enterprises and allows them to develop AI applications. They provide a toolkit to orchestrate, monitor, and continuously improve AI applications in production.


<details>

<!-- ### Description -->

### Links
- [GitHub](https://github.com/axilla-io/ax)
- [Twitter](https://twitter.com/axilla_io)
- [YCombinator](https://www.ycombinator.com/companies/axilla)

</details>


## [AutoGen](https://github.com/microsoft/autogen)
AutoGen is a framework by [Microsoft](https://microsoft.github.io/autogen/docs/Use-Cases/agent_chat/) that enables development of LLM applications using multiple agents that can converse with each other to solve task


<details>

### Description
-  AutoGen agents are customizable, conversable, and seamlessly allow human participation
-  They can operate in various modes that employ combinations of LLMs, human inputs, and tools
-  AutoGen's design offers multiple advantages:
	- it gracefully navigates the strong but imperfect generation and reasoning abilities of these LLMs
  	- it leverages human understanding and intelligence, while providing valuable automation through conversations between agents
     	- it simplifies and unifies the implementation of complex LLM workflows as automated agent chats

### Links
- [Blog post](https://www.microsoft.com/en-us/research/blog/autogen-enabling-next-generation-large-language-model-applications/)
- [Paper](https://arxiv.org/abs/2308.08155)
- [GitHub](https://github.com/microsoft/autogen)
- [Discord](https://discord.gg/pAbnFJrkgZ)

### Guides and examples
- [A guide to code-executing agents with AutoGen](https://e2b.dev/blog/microsoft-s-autogen)
</details>


## [BondAI](https://github.com/krohling/bondai)
BondAI is an open-source framework tailored for integrating and customizing Conversational AI Agents.


<details>

<!-- ### Description -->

### Links
- [GitHub](https://github.com/krohling/bondai)
- [Docs](https://bondai.dev/docs/intro)
- [Discord](https://discord.com/invite/docusaurus)

<!-- ### Guides and examples -->

  
</details>

## [ChatDev](https://github.com/OpenBMB/ChatDev)
ChatDev is a framework for building communicative agents for software development

<details>

### Description
- ChatDev is a cutting-edge AI NPC gaming research platform that seamlessly blends numerous advanced model interfaces, allowing for intricate manipulation of NPC interactions within meticulously crafted simulated social settings.
- ChatDev stands as a virtual software company that operates through various intelligent agents holding different roles, including Chief Executive Officer, Chief Product Officer, Chief Technology Officer, programmer, reviewer, tester, art designer .

### Links
- [GitHub](https://github.com/OpenBMB/ChatDev)
- [Web](https://chatdev.toscl.com/)

<!-- ### Guides and examples -->

  
</details>



## [Chidori](https://github.com/ThousandBirdsInc/chidori)
Chidori is a reactive runtime for building AI agents. It provides a framework for building AI agents that are reactive, observable, and robust. It supports building agents with Node.js, Python, and Rust.
It is currently in alpha and is not yet ready for production use.

<details>

<!-- ### Description -->

### Links
- [Web](https://docs.thousandbirds.ai/)
- [GitHub](https://github.com/ThousandBirdsInc/chidori)
- [Discord](https://discord.com/invite/CJwKsPSgew)

</details>

## [Fixie](https://www.fixie.ai/)

Fixie is a platform for conversational AI that enables to build agents in any language. They have their own [agent protocol](https://docs.fixie.ai/agent-protocol/).

<details>

<!-- ### Description -->

### Links
- [Web](https://docs.fixie.ai/agents/)



</details>

## [GenWorlds](https://genworlds.com/)

GenWorlds is an event-based communication framework enabling developers to seamlessly blend deterministic and non-deterministic processes in building interactive multi-agent systems.

<details>

<!-- ### Description -->

### Main Advantage

Flexibility in Process Management: GenWorlds excels in letting developers choose how to balance deterministic (predictable) and non-deterministic (AI-driven) processes. This is crucial for tailoring system reliability and intelligence to specific needs.

### Key Features

- **Customizable Systems:** GenWorlds emphasizes flexibility, allowing users to tailor systems according to their specific needs.
- **Intuitive Abstraction Layer:** Offers a basic interface with primitives to build agents, objects, and worlds without predefined constraints, supporting both deterministic and non-deterministic processes.
- **Pre-Built Elements for Rapid Development:** Comes equipped with a variety of ready-made agents, objects, and worlds, speeding up the setup process while still allowing extensive customization.
- **Smooth Deployment Mechanisms:** GenWorlds is built around a FastAPI web-socket server, facilitating easy dockerization and deployment, and providing versatile connectivity options suitable for various web systems.

### Links

- [Quickstart](https://genworlds.com/docs/get-started/quickstart)
- [GitHub](https://github.com/yeagerai/genworlds)
- [Discord](https://discord.gg/22eCYpb3w2)
- [Twitter](https://twitter.com/yeagerai)

</details>

## [Haystack by Deepset](https://haystack.deepset.ai/)

Haystack is an open-source LLM framework for building production-ready applications.

<details>

<!-- ### Description -->

### Links
- [Web](https://haystack.deepset.ai/)
- [GitHub](https://github.com/deepset-ai/haystack)



</details>



## [Hugging Face Agents](https://huggingface.co/docs/transformers/main_classes/agent)
A platform for deploying LLM agents with tools. They provide three types of agents: HfAgent uses inference endpoints for open-source models, LocalAgent uses a model of your choice locally and OpenAiAgent uses OpenAI closed models.

<details>

<!-- )### Description -->

### Links
- [Web](https://huggingface.co/docs/transformers/main_classes/agent)



</details>



## [Langchain](https://www.langchain.com/)
LangChain is a framework designed to simplify the creation of applications using large language models.

<details>

<!-- ### Description -->


### Links
- [Web](https://www.langchain.com/)
- [GitHub](https://github.com/langchain-ai/langchain)



</details>

## [Langroid](https://github.com/langroid/langroid)

Multi-Agent framework for building LLM Applications.

<details>

### Description


`Langroid` is an intuitive, lightweight, extensible and principled
Python framework to easily build LLM-powered applications.
You set up Agents, equip them with optional components (LLM,
vector-store and methods), assign them tasks, and have them
collaboratively solve a problem by exchanging messages.
This Multi-Agent paradigm is inspired by the
[Actor Framework](https://en.wikipedia.org/wiki/Actor_model)
(but you do not need to know anything about this!).

`Langroid` is a fresh take on LLM app-development, where considerable thought has gone
into simplifying the developer experience; it does not use `Langchain`.

- Works with most commercial/remote and open/local LLMs.
- Set up Multi-agent, multi-LLM system: use stronger LLMs for agents requiring strong reasoning and instruction-following, and delegate simpler tasks to weaker/local LLMs. 
- Supports OpenAI function-calling as well as native equivalent called `ToolMessage`, which works with LLMs that 
  do not have built-in function-calling. Simply specify structure as a (nested) Pydantic object.
- Batteries-included: vector-databases for RAG (Retrieval-Augmented Generation), caching, logging/observability.
- Specialized agents available: `DocChatAgent`, `SQLChatAgent`, `TableChatAgent` (for tabular data, e.g. csv/dataframes).
- `DocChatAgent` handles text, PDF, Docx files/URLS, and has state-of-the art techniques 
   for retrieval combining lexical and semantic search.
- Documentation: https://langroid.github.io/langroid/
</details>



## [Rift by Morph](https://github.com/morph-labs/rift)
Rift is an AI-native language server for AI agents. It's an open-source VS Code extension that allows merging the output of code generation agents.

<details>

<!-- ### Description -->


### Links
- [Web](https://morph.so/)
- [GitHub](https://github.com/morph-labs/rift)
- [Twitter](https://twitter.com/morph_labs)
- [Discord](https://discord.com/invite/wa5sgWMfqv)


</details>


## [Steamship](https://www.steamship.com/)
Steamship is a platform that allows to build, scale, and monitor AI agents with serverless cloud hosting, vector search, webhooks, callbacks, and more.
<details>

<!-- ### Description -->
- 

### Links
- [Web](https://www.steamship.com/)
- [GitHub](https://github.com/steamship-core)
- [Twitter](https://twitter.com/GetSteamship)
- [Discord](https://discord.com/invite/dR5fHvxSNg)



</details>

## [Vercel AI SDK](https://sdk.vercel.ai/docs)

An open-source library for building AI-powered user interfaces.

<details>

<!-- ### Description -->


### Links
- [Web](https://sdk.vercel.ai/docs)
- [GitHub](https://github.com/vercel-labs/ai)

</details>

## [WunderGraph Agent SDK](https://docs.wundergraph.com/docs/openai)

An open-source library that helps you to integrate OpenAI into your existing API infrastructure. You can use it to validate user input, enhance existing APIs with AI capabilities, and build APIs on top of AI Agents.
<details>

### Links
- [Web](https://wundergraph.com/)
- [GitHub](https://github.com/wundergraph/wundergraph)
- [Founders Twitter](https://twitter.com/jensneuse_de)
- [Founders Twitter](https://twitter.com/StefanTMD)
- [Company Twitter](https://twitter.com/wundergraphcom)
  
</details>


# :cloud: Cloud and Sandbox runtime


## [E2b](https://www.e2b.dev/)
E2b is an operating system for AI agents, that is, a set of tools, APIs, and cloud environments for  agents.


<details>

<!-- ### Description -->


### Links
- [Web](https://www.e2b.dev/)
- [GitHub](https://github.com/e2b-dev)
    - [e2b Dashboard](https://github.com/e2b-dev/e2b)
    - [The Agent Protocol](https://github.com/e2b-dev/agent-protocol)
    - [ChatGPT Pluhin](https://github.com/e2b-dev/chatgpt-plugin)
- [Twitter](https://twitter.com/e2b_dev)
    - [Vasek Mlejnsky](https://twitter.com/mlejva) (CEO, founder)
    - [Tomas Valenta](https://twitter.com/co_valenta) (CEO, founder)
    - [Tereza Tizkova](https://twitter.com/tereza_tizkova) (Growth & Community)
    - [Jakub Novak](https://twitter.com/_jcube) (Software Engineer)
- [Discord](https://discord.com/invite/U7KEcGErtQ)

</details>


# :chart_with_upwards_trend: Data Integration, memory management

## [AgentMemory](https://github.com/autonomousresearchgroup/agentmemory)

Easy-to-use agent memory, powered by chromadb and postgres

<details>

<!-- ### Description -->


### Links
- [GitHub](https://github.com/autonomousresearchgroup/agentmemory)


</details>

## [Cadea](https://www.cadea.ai/)
Cadea is a platform that helps you create, manage, and monitor chatbots that can answer questions about your internal documents

<details>

### Description
- Cadea allows you to deploy AI tools in your organization with strict security protocols, encryption, and monitoring
- Still in waitlist version



### Links
- [Web](https://www.cadea.ai/)
- [Linkedin](https://www.linkedin.com/company/cadea/about/)
- [X ](https://twitter.com/cadea_ai)


</details>



## [LlamaIndex](https://www.llamaindex.ai/)
LlamaIndex (formerly GPT Index) is a data framework for LLM applications to ingest, structure, and access private or domain-specific data. 


<details>

<!-- ### Description -->


### Links
- [Twitter](https://twitter.com/llama_index)
- [Discord](https://discord.com/invite/eN6D2HQ4aX)
- [Docs](https://gpt-index.readthedocs.io/en/latest/)
- [Linkedin](https://www.linkedin.com/company/llamaindex/)


</details>


## [MemGPT](https://memgpt.ai/)
MemGPT is teaching LLMs memory management for unbounded context 

<details>

### Description
- MemGPT manages a virtual context (inspired by virtual memory in operating systems) to create unbounded LLM context
- MemGPT allows to create perpetual chatbots 🤖 with self-editing memory


### Links
- [Web](https://memgpt.ai/)
- [Paper](https://arxiv.org/abs/2310.08560)
- [GitHub](https://github.com/cpacker/MemGPT)
- [Discord](https://discord.com/invite/9GEQrxmVyE)

</details>

## [PromethAI](https://github.com/topoteretes/PromethAI-Memory)

About
Memory management for the AI Applications and AI Agents

<details>

<!-- ### Description -->


### Links
- [GitHub](https://github.com/topoteretes/PromethAI-Memory)
- [Notion](https://topoteretes.notion.site/Going-beyond-Langchain-Weaviate-and-towards-a-production-ready-modern-data-platform-7351d77a1eba40aab4394c24bef3a278)

</details>


## [SID](https://www.sid.ai/)

SID is a YC S23 company that creates personal data infrastructure for AI


<details>


### Description
- SID makes data infrastructure for AI easy by letting AI devs connect to all of their customers' data with a single button and API
- It is a fully-hosted retrieval pipeline that makes it easy to connect services like Google Mail, Notion, GDrive, or fully custom data. In one afternoon, you can connect to any data source you'd like and instantly scale to millions of users.


### Links
- [Web](https://www.sid.ai/)
- [Twitter](https://twitter.com/try_sid)

</details>


## [Turbopuffer](https://turbopuffer.com/)

A truly serverless vector database


<details>


### Description
- Cheap. $1/month per million vectors. That's 10-70x cheaper than other vector databases. $4 per million queries.
- Serverless. Pay only for what you use. Don't worry about manual scaling.
Reasonably
- Fast. ~100ms latency on 1m vectors. Much faster soon.


### Links
- [Web](https://turbopuffer.com/)

</details>


## [Vectara](https://vectara.com/)
Vectara is a cloud-native, API-driven LLM-powered search app platform 



<details>


### Description
- Purpose of Vectara is to serve the world’s largest sites and applications at blazing fast speeds

### Links
- [Web](https://vectara.com/)
- [Discord](https://discord.com/invite/GFb8gMz6UH)
- [X ](https://twitter.com/vectara)
- [Linkedin](https://www.linkedin.com/company/vectara/)

</details>





<br/><br/>


# Who's behind this?

<img src="/assets/footer.png" width="100%" alt="SDKs Repo Visual" />


This list is made by the team behind [E2B](https://github.com/e2b-dev/e2b?ref=awesome-sdks). E2b is building a Sandbox Runtime for LLM apps and agents  - that is, a set of custom sandboxed cloud environments for AI-powered apps and agentic workflows. Get started [here](https://e2b.dev/docs?ref=awesome-sdks).

## Join the community
- Follow us on [X ](https://twitter.com/e2b_dev)
- [Join our Discord](https://discord.gg/U7KEcGErtQ)

Feel free to reach out to us at [hello@e2b.dev](mailto:hello@e2b.dev).
Check out also our database of [AI agents](https://github.com/e2b-dev/awesome-ai-agents).





