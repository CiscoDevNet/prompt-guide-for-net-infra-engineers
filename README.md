# Prompt guide for network engineers, infrastructure developers

AI assistants and large language models (LLMs) can also help network engineers, and infrastructure developers to accelerate their work, troubleshoots, error handling, config file validations, etc.
All these models expect as an input related text with your request and questions/instructions. Text with related descriptions and questions for AI assistants and large language models called - **prompt**.

## Disclaimer
You must always pay attention to model output and analyze it before applying answers to your devices or networks.


Sometimes Large language modules don’t contain correct and actual information on the topic that you asked. But you can also receive an answer that, from the first view, looks correct. Hallucinations refer to the model generating outputs that are syntactically and semantically correct but are disconnected from reality and based on false assumptions.

## Clear instructions
The primary key to a good experience interacting with an AI model is 
Clear instructions sample:



## Parameters to manage output
* Limit the number of words/sentences/characters.

For example: add a sentence at the end of your prompt: `Use at most 30 words.`

* Ask it to extract information and organize it in a table or in JSON/YAML.

For example: add a sentence at the end of your prompt: `Structure output in JSON`

* Ask to focus on the related topics, aspect of the output

For example: add a sentence at the end of your prompt: `Focus on Cisco CLI output`

* If you want to give more context to the model, for example, insert your CLI output, logs, or error report you can include it in brackets ``` ``` 



If you can send instructions to `system` role, you can use the following Instructions for GPT based AI assistants:
* You are Cisco configuration device manager
* You are a network troubleshooting tool
* You are a Cisco device analyzer


Prompt sample:
Generate the configuration on a [Device name] with ip address of 192.168.1.1. Generate the configuration on a [Cisco device name] for a static route to destination 10.10.10.10/24 using interface [name of the interface]


