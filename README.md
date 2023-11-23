# node-red-flow-stablecode-completion-alpha-3b-4k #

Node-RED Flows for the StableCode-Completion-Alpha-3B-4K AI model

This repository contains a function node for [Node-RED](https://nodered.org/) which can be used to run the [Stability AI](https://huggingface.co/stabilityai) [StableCode-Completion-Alpha-3B-4K model](https://huggingface.co/stabilityai/stablecode-completion-alpha-3b-4k) within a Node-RED flow. **Inference is done on the CPU** (without requiring any special harware) and still completes within a few seconds on a reasonably powerful computer.

> **Important: in contrast to my other flows for AI models, this one does not use llama.cpp but a similar program called [ggml](https://github.com/ggerganov/ggml)**

![StableCode-Completion-Alpha-3B-4K Text Completion Flow](./StableCode-Completion-Alpha-3B-4K-Completion-Flow.png)

Additionally, this repo also contains a function node to tokenize a prompt - embeddings calculation based on this model is not yet supported.

Having the inference, tokenization and embedding calculation as a self-contained function node gives you the possibility to create your own user interface or even use it as part of an autonomous agent.

> Nota bene: these flows do not contain the actual model. You will have to download your own copy directly from [Huggingface](https://huggingface.co/TheBloke/stablecode-completion-alpha-3b-4k-GGML) (use file [stablecode-completion-alpha-3b-4k.ggmlv1.q8_0.bin](https://huggingface.co/TheBloke/stablecode-completion-alpha-3b-4k-GGML/blob/main/stablecode-completion-alpha-3b-4k.ggmlv1.q8_0.bin)).

> Just a small note: if you like this work and plan to use it, consider "starring" this repository (you will find the "Star" button on the top right of this page), so that I know which of my repositories to take most care of.




## License ##

[MIT License](LICENSE.md)
