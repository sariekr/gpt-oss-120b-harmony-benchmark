# GPT-OSS-120B Harmony Benchmark

An AIMultiple evaluation of self-hosted GPT-OSS-120B using OpenAI's Harmony conversation format. The project examines factual question answering and mathematical reasoning in a vLLM deployment.

> [Read the related AI providers benchmark on AIMultiple](https://aimultiple.com/ai-providers)

## Evaluation scope

The test suite contains 108 questions: 35 article-based knowledge questions and 73 math problems. Prompts are encoded with the Harmony SDK, including a high-reasoning instruction. Generated answers are extracted from the structured response and checked against reference answers.

The evaluation covers:

- Prompt encoding and response parsing.
- Overall accuracy and separate knowledge and math scores.
- Repeat runs of the same self-hosted configuration.

## How this fits the published study

The linked article covers hosted providers and latency measurements alongside the self-hosted evaluation. Each comparison has its own configuration and measurement scope.

Local development runs are omitted from this summary because they differ from the published setup. Refer to the article for the reported results.

## Ownership

The benchmark implementation was developed for AIMultiple and belongs to AIMultiple. This repository contains a documentation summary. Source code and benchmark datasets are not distributed here.
