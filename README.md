# Eidolon Chatbot Recipe

This project shows an example of a multi-llm multimedia enabled chatbot. Not all LLMs support multimedia, let alone 
mid-conversation brain-boosts. This can cause issues when swapping out components. Thankfully Eidolon's 
AgentProcessingUnit abstracts away those concepts so you can enable multimedia, json output, and function calling on 
even the smallest llm.

## Core Concepts
1. Customizing the AgentProcessingUnit
2. Running the UI

## Directory Structure

- `resources`: This directory contains additional resources for the project. An example agent is provided for reference.
- `components`: This directory is where any custom code should be placed.

## Running the Server

First you need to clone the project and navigate to the project directory:

```bash
git clone https://github.com/eidolon-ai/agent-machine.git
cd agent-machine
```

Then run the server in dev mode, use the following command:

```bash
make serve-dev
```

The first time you run this command, you may be prompted to enter credentials that the machine needs 
to run (ie, OpenAI API Key).

This command will download the dependencies required to run your agent machine and start the Eidolon http server in 
"dev-mode".

If the server starts successfully, you should see the following output:
```
Starting Server...
INFO:     Started server process [34623]
INFO:     Waiting for application startup.
INFO - Building machine 'local_dev'
...
INFO - Server Started in 1.50s
```
