# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Octopus v2: On-device language model for super agent

  - **[Link](https://arxiv.org/abs/2404.01744)**
  - **Objective**: Fine-tuning of a small Large Language Model for the purpose of function-calling by employing a new training strategy where the model gets trained on new functional tokens, e.g. <oc_i>, that allows token efficient classification and parameter extraction of a user command. 
  - **Methods**: functional tokens, supervised fine-tuning, full fine-tuning, LoRA
  - **Outcomes**: Small models can with the right fine-tuning strategy (fine-tuning template) and functional token technology achieve similar performance to zero-shot prompted models like GPT-4 in function-calling.
  - **Relation to the Project**: Main source that was tried to be replicated in large parts.

- **Source 2**: ORPO: Monolithic Preference Optimization without Reference Model

  - **[Link](https://arxiv.org/abs/2403.07691)**
  - **Objective**: New preference optimization method that employs a combined loss function that seemingly outperforms previous approaches. Can be used instead of SFT and DPO.
  - **Methods**: preference optimization, new loss function
  - **Outcomes**: ORPO is a promising alternative to SFT + DPO
  - **Relation to the Project**: Preference optimization technique that was tested during the experiments instead of SFT and DPO.

- **Source 3**: Octopus v3: Technical Report for On-device Sub-billion Multimodal AI Agent

  - **[Link](https://arxiv.org/abs/2404.11459)**
  - **Objective**: Next iteration of the Octopus v2 model with multimodal capabilities and sub-billion parameter base model.
  - **Methods**: functional tokens
  - **Outcomes**: Small function-calling models can be further downscaled to sub-billion parameter models while maintaining a similar/same level of accuracy.
  - **Relation to the Project**: The choice of the model is not restricted to 2B+ models like Gemma-2B.
