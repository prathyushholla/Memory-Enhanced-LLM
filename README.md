# llm-memories

This repository contains a project that integrates various memory modules with a language model (LLM) to improve conversation continuity, context retention, and information recall. The project is designed to showcase different memory types, including buffer memory, summary memory, and combination memory modules, enhancing the user interaction experience with large language models.

## Project Overview

In dialogue systems, maintaining context over multiple turns is crucial for natural interaction. This project adds memory capabilities to an LLM using LangChain, with memory modules like:

- **Conversation Buffer Memory:** Retains recent conversation turns for immediate context.
- **Conversation Summary Memory:** Summarizes conversations to maintain context over longer dialogues.
- **Conversation Summary Buffer Memory:** Combines buffer and summary memory for optimal context preservation.

## Features

- **Modular Memory Integration:** Easily switch between memory types to experiment with how each affects the conversation flow.
- **Extended Context Retention:** Summarized and buffered memories provide extended and immediate recall, creating richer dialogues.
- **Customizable Memory Parameters:** Configure memory lengths and summary depth to adjust retention based on use cases.


# Memory Modules Demonstrated
- **ConversationBufferMemory**
- **ConversationSummaryMemory**
- **ConversationSummaryBufferMemory**
- **ConversationBufferWindowMemory**
- **ConversationKGMemory**
- **ConversationEntityMemory**
