# node-red-flow-stablecode-completion-alpha-3b-4k #

Node-RED Flows for the StableCode-Completion-Alpha-3B-4K AI model

This repository contains a function node for [Node-RED](https://nodered.org/) which can be used to run the [Stability AI](https://huggingface.co/stabilityai) [StableCode-Completion-Alpha-3B-4K model](https://huggingface.co/stabilityai/stablecode-completion-alpha-3b-4k) within a Node-RED flow. **Inference is done on the CPU** (without requiring any special harware) and still completes within a few seconds on a reasonably powerful computer.

> **Important: in contrast to my other flows for AI models, this one does not use llama.cpp but a similar program called [ggml](https://github.com/ggerganov/ggml)**

![StableCode-Completion-Alpha-3B-4K Text Completion Flow](./StableCode-Completion-Alpha-3B-4K-Completion-Flow.png)




## License ##

[MIT License](LICENSE.md)
