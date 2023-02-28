# awesome-RLHF-language-models

Curated list of resources for Reinforcement Learning from Human Feedback and Language Models.

Reinforcement learning from human feedback (RLHF) has gained popularity with ChatGPT with combines language models with RLHF.

# Language models

The paper [Transformer models: an introduction and catalog](https://arxiv.org/pdf/2302.07730.pdf) contains a very comprehensive of the existing language models.

# Reinforcement Learning methods

* [Proximal Policy Optimization](https://en.wikipedia.org/wiki/Proximal_Policy_Optimization)

# Commercial products

* [Anthropic](https://www.anthropic.com/)
* [OpenAI ChatGPT]
  * ChatGPT (https://openai.com/blog/chatgpt/)
  * InstructGPT (https://openai.com/research/instruction-following)
* [Google bard](https://blog.google/technology/ai/bard-google-ai-search-updates/)

# Courses

* [Reinforcement Learning from Human Feedback: From Zero to chatGPT](https://www.youtube.com/watch?v=2MBJOuVq380)
* [CS224n: NLP w/ Deep Learning course at Stanford](http://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture11-prompting-rlhf.pdf)
* [Stanford CS234: Reinforcement Learning | Winter 2019](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u)
* [Hugging Face Deep Reinforcement Learning Course](https://huggingface.co/deep-rl-course/unit0/introduction)

# Papers

*2020*
* [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/pdf/1909.08593.pdf)

*2022*
* [Fine-tuning language models to find agreement among humans with diverse preferences](https://arxiv.org/pdf/2211.15006.pdf)

*2023*
* [It's chatgpt a general-purpose natural language processing task solver?](https://arxiv.org/pdf/2302.06476.pdf)

# Code

## Reference implementations

* https://github.com/openai/lm-human-preferences - The first code released to perform RLHF on LMs from OpenAI

## Open source projects which can produce models

* https://github.com/LAION-AI/Open-Assistant
* [EluetherAI](http://www.eleuther.ai/)
* [Carper.ai](https://carper.ai/)

## RLFH open source libraries

* https://github.com/allenai/RL4LMs - provide easily customizable building blocks for training language models including implementations of on-policy algorithms, reward functions, metrics, datasets and LM based actor-critic policies
* https://github.com/lvwerra/trl -  train transformer language models with Proximal Policy Optimization (PPO). The library is built on top of the transformers library by hugs Hugging Face.

# Datasets

* https://huggingface.co/datasets/Anthropic/hh-rlhf - Human preference data about helpfulness and harmlessness

