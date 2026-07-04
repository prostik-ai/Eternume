# Eternume
Project "Eternum"
Development of a personal AI assistant with a unique personality and long-term memory.

Objective
Creation of a software agent capable of maintaining meaningful dialogue, preserving conversation context, and demonstrating individual character traits defined by the user.

Technology Stack

· Programming language: Python 3.12.
· Graphical interface: PyQt6 (full-screen window, custom styles, message bubbles).
· Reasoning engine: connection to LLM via OpenRouter API (openrouter/auto model).
· Memory: local JSON file storage of dialogue history (echo_memory.json).
· Personality core: embedded system prompt (SOUL) defining the assistant's character, biography, and communication style.
· Additional features: threads for asynchronous requests, network error handling with retries.

Functionality

· Interactive chat with visual separation of user and assistant messages.
· Full dialogue history preservation (no length limit).
· Personalization: the assistant has a name (Echo), a defined origin story, and an emotional response spectrum.
· Resilience to unstable connections (retries, non-strict SSL context).

Current Status
Working prototype. The program runs on a local machine, interacts with the LLM via the internet, and retains memory between sessions.

Future Prospects
Integration of voice input/output, a 3D avatar, and additional data sources to expand contextual awareness is planned.
