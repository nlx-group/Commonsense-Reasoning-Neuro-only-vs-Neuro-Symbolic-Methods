# Commonsense Reasoning: how do Neuro-Symbolic and Neuro-only approaches compare?

This repository contains the code and some data for the [paper]():

```
Commonsense Reasoning: how do Neuro-Symbolic and Neuro-only approaches compare?
Ruben Branco, António Branco, João Silva and João Rodrigues
to appear at KINN 2021
```

## Abstract

> The representation of knowledge is a perennial task in Artificial Intelligence (AI), and has been an active topic of research since the beginnings of the field.
> Through the years, intensive research and labour has been put into producing resources which encode knowledge regarding different topics, structured in specific formats so as to allow robust, automated reasoning over them.
>
> In Natural Language Processing, deep learning models are commonly given unstructured data, and often struggle to learn the necessary knowledge and abstractions required to represent and understand the underlying mechanisms that govern the target tasks. A popular method to mitigate this issue is to expand the training process to include more tasks and data. Yet, it remains one of the challenges of deep learning.
>
> A promising research topic is to combine the rich knowledge encoded in those structured resources with deep learning methods, affording them with the necessary tools to more effectively learn the complexities of the target tasks.
>
> In this paper we set out to compare a Neuro-Symbolic model with popular Neuro-only models when they are tasked with solving commonsense reasoning problems.
> Commonsense reasoning is an essential part of the human experience.
> It encompasses human values and needs, and by reasoning with it we can organize sensible arguments and decide on effective actions.
>
> The results obtained indicate that there is no clear advantage to either approach, with the Neuro-Symbolic model being competitive amongst the Neuro-only models, but not superior.

## Code

The paper comprises the fine-tuning of different state-of-the-art Transformer models on four different Commonsense Reasoning tasks.

Each models folder (`RoBERTa/`, `GPT-2/`, `T5/` and `BART_AND_COMET/`) contains a scripts folder, which provides an example of how to run the models for each task. All the necessary code and data should be provided in this repository to replicate the experiments.

## Citation

```
@article{branco2021commonsense,
  title={Commonsense Reasoning: how do Neuro-Symbolic and Neuro-only approaches compare?},
  author={Branco, Ruben and Branco, Ant{\'o}nio and Silva, Jo{\~a}o and Rodrigues, Jo{\~a}o},
  year={2021}
}
