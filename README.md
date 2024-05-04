# Eidolon Chatbot Recipe

This project shows an example of a multi-llm multimedia enabled chatbot. Not all llms support multi-media, 
let allone mid conversation brain-boosts. This can cause issues when swapping out components. Thankfully 
Eidolon's AgentProcessingUnit abstracts away those concepts so you can enable multimedia, json output, and 
function calling on even the smallest llm.

## Core Concepts
1. Customizing the AgentProcessingUnit
2. Running the UI

## Directory Structure

- `resources`: This directory contains additional resources for the project. An example agent is provided for reference.
- `components`: This directory is where any custom code should be placed.

## Running the Server

To run the server in dev mode, use the following command:

```bash
make serve-dev
```

This will start the Eidolon http server without MongoDB along with some other dev tools such as recordings.
