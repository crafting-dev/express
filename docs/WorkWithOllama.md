# Work with Local Ollama

Activate AI capabilities with local Ollama makes a lot of heavy work possible
while keeping all data local and no cost on tokens.

The guide is not limited to Ollama but other LLM inference engines in a similar way.

## MacOS Guide

As _Crafting Express_ runs inside a docker container,
the default serving endpoint of Ollama can be reached as `http://host.docker.internal:11434`:
- Visit _Settings/AI_ from Crafting web UI;
- From _Models and Providers_ tab, add an _Ollama_ provider with _Base URL_ to be `http://host.docker.internal:11434`;
- Add some models from that provider, assign purposes and adjust the order of models accordingly.

## LLM Service from local Network

Follow [Access Local Network](AccessLAN.md) for details.
