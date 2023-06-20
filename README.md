# NLP_code_generation
Final Project for the Natural Language Processing course.

<img width="692" alt="Capture d’écran 2023-06-20 à 03 45 32" src="https://github.com/Shanehoeb/NLP_code_generation/assets/88781950/f98faff7-5b50-4f90-aefd-632260e5db1a">


A lot of recent work on both Large Language Models (LLMs) and generative models for text showed particular improvement on the code generation task and reaffirmed its higher importance. 
Inspired by the paper [Evaluating Large Language models on Code](https://github.com/openai/human-eval) and the performance of the associated model, Codex, we decide to focus on the code generation task and to discuss the convergence between code generation models and "human-style" logic and development concepts in the process of code generation.

First, we reproduce some important results about Large Language models and their ability not only to perform very well on zero-shot, but moreover to improve substantially with fine-tuning on code. Then, we try to explore potential enhancements of the LLM state of the art models by making a step towards more human-like reasoning. We also explore an alternative in the recent breakthrough in generative AI that are diffusion models. Finally, we discuss further models and techniques for aiming at more convergence towards State of the art code generation models and human-like programming logic.

The report is available [here](https://github.com/https://github.com/Shanehoeb/NLP_code_generation/NLP_Project.pdf)

The github is organized in 3 parts :
- A first part : [reproduce-results](https://github.com/Shanehoeb/NLP_code_generation/tree/main/reproduce-results) for reproducing results from LLaMA and CodeGen on the HumanEval benchmark.
- A Second part : [code-T-results](https://github.com/Shanehoeb/NLP_code_generation/tree/main/code-T-results) for exploring Code-T, a concept for human-like reasoning for code generation using generated unit tests.
- A third part : [latent-diffusion-for-language](https://github.com/Shanehoeb/NLP_code_generation/tree/main/latent-diffusion-for-language) for the adaptation of a text latent-diffusion model for training on code.

We hope that you will appreciate our work, we really enjoyed working on this project despite the hard limits in hardware and time !

Best,
Gabriel Fiastre & Shane Hoeberichts
