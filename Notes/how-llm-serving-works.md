#### [How LLM Serving Works: An Introduction to vLLM and SGLang](https://www.youtube.com/watch?v=vM3kzJIPvvw)
* Llama3.1 8B - 8 billion parameters in BF16 (2 bytes each): 16 GB of weights
* [H100](https://github.com/muarshad01/Kernel-Engg/blob/main/H100.md)

***

* 10:00
  
* VRAM - 80 GB and 16 GB is for weights.
* SRAM - 30 MB
* VRAM to SRAM data transfer speed: 3.35 TB/s
* Computation speed: 989 TFLOPs/s
* KV Cache per token: 128 KB
* KV Cache per 2,500 token chat: ~320 MB
* Left for KV Cache after weights: 54 GB

***

* 20:00

***

