# Agentic AI

## Description

This project is an example using the CrewAI framework to automate the process of planning, writing and editing a ML blog article on the topic "Agenctic AIs" using information extracted and synthesized from a [YouTube video](https://www.youtube.com/watch?v=sal78ACtGTc&t=686s). CrewAI orchestrates autonomous AI agents, enabling them to collaborate and execute complex tasks efficiently. It is designed to facilitate the collaboration of role-playing AI agents. In this example, these agents work together to write a comprehensive and compelling article on the topic "Agenctic AIs".

## Features

- Agents -> Content planner, writer and editor
- Tasks -> Plan, write and edit
- Tools -> YouTubeVideoSearchTool()
- Crew -> brings agents, tasks and tools together to perform tasks sequentially or hierarchically as well as define their collaboration process
- Agents are powered by GPT-4 LLM 

## Getting Started

### Prerequisites

- OpenAI API Key - Signup and get an API key from https://platform.openai.com/api-keys
- Paid membership to OpenAI - You will incur charges (< $1.00) to replicate this project

### Installation

- You would have to install crewai, crewai[tools], langchain_community and python-dotenv
- python-dotenv is used to secure the API key
- To install, run `pip install -r requirements.txt`


### Running the script

- Execute `1. Introduction to  Agentic AIs.ipynb`. The notebook will leverage the CrewAI framework to analyze, synthesize, extract information from YouTube video and write the blog article.


### References

- [What's next for AI agentic workflows ft. Andrew Ng](https://www.youtube.com/watch?v=sal78ACtGTc&t=686s)

- https://learn.deeplearning.ai/courses/multi-ai-agent-systems-with-crewai/


![logo](https://github.com/ArunSubramanian456/Agentic_AI/blob/main/YouTubeVideoSearchTool.png?raw=true)