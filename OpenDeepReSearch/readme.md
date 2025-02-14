Recopilación de recursos para implemenar y aplicar cadenas de pensamiento

- Repositorios e info relacionados con OpenDeepReSearch
- https://github.com/open-webui/open-webui/discussions/9321
- https://news.ycombinator.com/item?id=42937701

STORM: Synthesis of Topic Outlines through Retrieval and Multi-perspective Question Asking.
-  

https://github.com/stanford-oval/storm#storm-synthesis-of-topic-outlines-through-retrieval-and-multi-perspective-question-asking

Overview

STORM is a LLM system that writes Wikipedia-like articles from scratch based on Internet search. Co-STORM further enhanced its feature by enabling human to collaborative LLM system to support more aligned and preferred information seeking and knowledge curation.
While the system cannot produce publication-ready articles that often require a significant number of edits, experienced Wikipedia editors have found it helpful in their pre-writing stage.

Open Deep Research
-
https://github.com/dzhng/deep-research?tab=readme-ov-file#open-deep-research

  An AI-powered research assistant that performs iterative, deep research on any topic by combining search engines, web scraping, and large language models.
  
  The goal of this repo is to provide the simplest implementation of a deep research agent - e.g. an agent that can refine its research direction over time and deep dive into a topic. Goal is to keep the repo size at <500 LoC so it is easy to understand and build on top of.
  
  If you like this project, please consider starring it and giving me a follow on X/Twitter. This project is sponsored by Aomni.


Automated-AI-Web-Researcher-Ollama
-
https://github.com/TheBlewish/Automated-AI-Web-Researcher-Ollama#automated-ai-web-researcher-ollama

Description
  Automated-AI-Web-Researcher is an innovative research assistant that leverages locally run large language models through Ollama to conduct thorough, automated online research on any given topic or question. Unlike traditional LLM interactions, this tool actually performs structured research by breaking down queries into focused research areas, systematically investigating each area via web searching and scraping relevant websites, and compiling its findings. The findings are automatically saved into a text document with all the content found and links to the sources. Whenever you want it to stop its research, you can input a command, which will terminate the research. The LLM will then review all of the content it found and provide a comprehensive final summary of your original topic or question. Afterward, you can ask the LLM questions about its research findings.


Daniel Kliewer About
Step-by-Step Guide to Running Open Deep Research with smolagents
-
https://danielkliewer.com/2025/02/05/open-deep-research
This guide walks you through setting up and using the Open Deep Research agent framework, inspired by OpenAI’s Deep Research, leveraging Hugging Face’s smolagents library. Follow these steps to reproduce agentic workflows for complex tasks like the GAIA benchmark.



Open-source DeepResearch – Freeing our search agents
-
https://github.com/huggingface/blog/blob/main/open-deep-research.md#open-source-deepresearch--freeing-our-search-agents
https://news.ycombinator.com/from?site=github.com/huggingface
https://github.com/huggingface/smolagents/tree/main/examples/open_deep_research#open-deep-research
https://github.com/huggingface/open-r1
https://github.com/huggingface/smol-course
https://huggingface.co/docs/autotrain/index



Yesterday, OpenAI released Deep Research, a system that browses the web to summarize content and answer questions based on the summary. The system is impressive and blew our minds when we tried it for the first time.

One of the main results in the blog post is a strong improvement of performances on the General AI Assistants benchmark (GAIA), a benchmark we’ve been playing with recently as well, where they successfully reached near 67% correct answers on 1-shot on average, and 47.6% on especially challenging “level 3” questions that involve multiple steps of reasoning and tool usage (see below for a presentation of GAIA).

DeepResearch is composed of an LLM (which can be selected from the current list of LLMs provided by OpenAI, 4o, o1, o3, etc) and an internal “agentic framework” which guide the LLM to use tools like web search and organize its actions in steps.

While powerful LLMs are now freely available in open-source (see e.g. the recent DeepSeek R1 model), OpenAI didn’t disclose much about the agentic framework underlying Deep Research…

So we decided to embark on a 24-hour mission to reproduce their results and open-source the needed framework along the way!

The clock is ticking, let’s go! 




🤗 smolagents - a smol library to build great agents!
-
https://github.com/albertvillanova/smolagents#---smolagents---a-smol-library-to-build-great-agents
https://huggingface.co/blog/smolagents
https://huggingface.co/docs/smolagents/index

smolagents is a library that enables you to run powerful agents in a few lines of code. It offers:

✨ Simplicity: the logic for agents fits in ~thousand lines of code (see agents.py). We kept abstractions to their minimal shape above raw code!

🧑‍💻 First-class support for Code Agents, i.e. agents that write their actions in code (as opposed to "agents being used to write code"). To make it secure, we support executing in sandboxed environments via E2B.

On top of this CodeAgent class, we still support the standard ToolCallingAgent that writes actions as JSON/text blobs.
🤗 Hub integrations: you can share and load tools to/from the Hub, and more is to come!

🌐 Support for any LLM: it supports models hosted on the Hub loaded in their transformers version or through our inference API, but also supports models from OpenAI, Anthropic and many others via our LiteLLM integration.

Full documentation can be found here.



DeepResearch
-
https://github.com/jina-ai/node-DeepResearch#deepresearch

Keep searching, reading webpages, reasoning until an answer is found (or the token budget is exceeded). Useful for deeply investigating a query.

Unlike OpenAI and Gemini's Deep Research capabilities, we focus solely on delivering accurate answers through our iterative process. We don't optimize for long-form articles – if you need quick, precise answers from deep search, you're in the right place. If you're looking for AI-generated reports like OpenAI/Gemini do, this isn't for you.

Open Deep Research
-
https://github.com/nickscamara/open-deep-research#open-deep-research
https://opendeepresearch.org/
https://x.com/nickscamara_/status/1886459999905521912

An Open-Source clone of Open AI's Deep Research experiment. Instead of using a fine-tuned version of o3, this method uses Firecrawl's extract + search with a reasoning model to deep research the web.

GPT Researcher
-
https://github.com/assafelovic/gpt-researcher#-gpt-researcher

GPT Researcher is an autonomous agent designed for comprehensive web and local research on any given task.

The agent produces detailed, factual, and unbiased research reports with citations. GPT Researcher provides a full suite of customization options to create tailor made and domain specific research agents. Inspired by the recent Plan-and-Solve and RAG papers, GPT Researcher addresses misinformation, speed, determinism, and reliability by offering stable performance and increased speed through parallelized agent work.

Our mission is to empower individuals and organizations with accurate, unbiased, and factual information through AI.

Why GPT Researcher?
Objective conclusions for manual research can take weeks, requiring vast resources and time.
LLMs trained on outdated information can hallucinate, becoming irrelevant for current research tasks.
Current LLMs have token limitations, insufficient for generating long research reports.
Limited web sources in existing services lead to misinformation and shallow results.
Selective web sources can introduce bias into research tasks.

