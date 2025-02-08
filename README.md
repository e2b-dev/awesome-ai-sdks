
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


<img src="/assets/visual.png" width="100%" alt="SDKs Repo Visual" />

Welcome to our list of [AI agents](https://github.com/e2b-dev/awesome-ai-agents) SDKs. A database of SDKs, frameworks, libraries, and tools for creating, monitoring, debugging and deploying autonomous [AI agents](https://github.com/e2b-dev/awesome-ai-agents)

The list is done according to our best knowledge, although definitely not comprehensive.
Discussion and feedback appreciated! :heart:

## Have anything to add?
You have something to add or improve about our list? Do it via pull request.

## Who's behind this?
This list is made by the team behind [e2b](https://github.com/e2b-dev/e2b). E2b is building an operation system of AI agents - that is, a set of tools, environments, SDKs and APIs. E2b is agnostic to your tech stack and aims to work with any tooling for building AI agents.

## Join the community
- Follow us on [Twitter](https://twitter.com/e2b_dev)
- [Join Twitter community](https://twitter.com/i/communities/1670204079619055616) for AI agents
- [Join our Discord](https://discord.gg/U7KEcGErtQ)
- Want to discuss anything about AI agents? [Schedule a call with us](https://calendly.com/tereza-tizkova/30min)

Feel free to reach out to us at [hello@e2b.dev](mailto:hello@e2b.dev).
Check out also our database of [AI agents](https://github.com/e2b-dev/awesome-ai-agents).


## [E2B](https://www.e2b.dev/)
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


## [AgentOps](https://www.agentops.ai/)
AgentOps create tools to make agents actually work, e.g., graphs, monitoring, and replay analytics.

<details>

<!-- ### Description -->

### Links
- [Web](https://www.agentops.ai/)


</details>


## [Chidori](https://github.com/ThousandBirdsInc/chidori)
Chidori is a reactive runtime for building AI agents. It provides a framework for building AI agents that are reactive, observable, and robust. It supports building agents with Node.js, Python, and Rust.
It is currently in alpha, and is not yet ready for production use.

<details>

<!-- ### Description -->

### Links
- [Web](https://docs.thousandbirds.ai/)
- [GitHub](https://github.com/ThousandBirdsInc/chidori)
- [Discord](https://discord.com/invite/CJwKsPSgew)

</details>

## [Fixie]()

Fixie is a platform for conversational AI that enables to build agents in any language. They have their own [agent protocol](https://docs.fixie.ai/agent-protocol/).

<details>

<!-- ### Description -->

### Links
- [Web](https://docs.fixie.ai/agents/)



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

## [Llama-github](https://github.com/JetXu-LLM/llama-github)
Llama-github is a python library that helps you retrieve the most relevant code snippets, issues, and repository information from GitHub based on your queries, transforming them into valuable knowledge context. It empowers LLM Chatbots, AI Agents, and Auto-dev Agents to solve complex coding tasks. Whether you're a developer looking for quick solutions or an engineer implementing advanced Auto Dev AI Agents, llama-github makes it easy and efficient.

<details>
Here's a simple example of how to use llama-github:

```
pip install llama-github
```

```python
from llama_github import GithubRAG

# Initialize GithubRAG with your credentials
github_rag = GithubRAG(
    github_access_token="your_github_access_token", 
    openai_api_key="your_openai_api_key", # Optional in Simple Mode
    jina_api_key="your_jina_api_key" # Optional - unless you want high concurrency production deployment (s.jina.ai API will be used in llama-github)
)

# Retrieve context for a coding question (simple_mode is default set to False)
query = "How to create a NumPy array in Python?"
context = github_rag.retrieve_context(
    query, # In professional mode, one query will take nearly 1 min to generate final contexts. You could set log level to INFO to monitor the retrieval progress
    # simple_mode = True
)

print(context)
```

### Links
- [GitHub](https://github.com/JetXu-LLM/llama-github)
</details>

## [Langchain](https://www.langchain.com/)
LangChain is a framework designed to simplify the creation of applications using large language models.

<details>

<!-- ### Description -->


### Links
- [Web](https://www.langchain.com/)
- [GitHub](https://github.com/langchain-ai/langchain)



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

## [SID](https://www.sid.ai/)

SID is a YC S23 company that makes data infrastructure for AI easy by letting AI devs connect to all of their customer's data with a single button and API.

<details>

<!-- ### Description -->


### Links
- [Web](https://www.sid.ai/)
- [Twitter](https://twitter.com/try_sid)



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

An open source library for building AI-powered user interfaces.

<details>

<!-- ### Description -->


### Links
- [Web](https://sdk.vercel.ai/docs)
- [GitHub](https://github.com/vercel-labs/ai)


</details>


