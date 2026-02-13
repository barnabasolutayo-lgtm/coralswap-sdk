# Prompt Basics Project

## Introduction

This project provides a foundational exploration of prompt engineering concepts using ChatGPT and Python. It examines how prompt structure, clarity, and parameter settings influence model responses.

Prompt engineering is an essential skill in working effectively with large language models. Through structured exercises, this project demonstrates how different prompting techniques produce varying outputs.

---

## Project Objectives

The objectives of this project are to:

1. Understand the structure and components of a prompt.
2. Differentiate between zero-shot and few-shot prompting.
3. Develop skills in writing clear and precise prompts.
4. Examine how model parameters (temperature and top-p) affect response quality and creativity.
5. Analyze differences in output clarity, structure, and consistency.

---

## Overview of Concepts

### What is a Prompt?
A prompt is an input instruction or query given to a language model to generate a response.

### Anatomy of a Prompt
Prompts typically consist of:
- **System message** – sets the behavior or role of the model.
- **User message** – contains the instruction or question.
- **Assistant message** – the model’s generated response.

### Zero-Shot vs Few-Shot Prompting
- **Zero-shot prompting:** The model receives only a task instruction without examples.
- **Few-shot prompting:** The model receives task instructions along with examples to guide output format and style.

---

---

## Description of Exercises

### Exercise 0: Environment Setup
This exercise involves installing Python (version 3.9 or higher), verifying installation, and executing a simple "Hello, World!" program to confirm the development environment is correctly configured.

### Exercise 1: Simple Prompt Writing
Students write basic prompts in two formats:
- Direct instruction prompts
- Question-based prompts

Outputs are compared to observe differences in structure, length, and clarity.

### Exercise 2: Instruction Refinement
A vague prompt is progressively refined into clearer, more specific instructions. The outputs are analyzed to evaluate improvements in organization, relevance, and precision. THe responses were the same with the type of prompt made.

### Exercise 3: Parameter Experimentation
The same prompt is tested using different parameter values:
- Low temperature vs high temperature
- Lower vs higher top-p values

The resulting outputs are compared to examine changes in creativity, randomness, determinism, and focus.

---

## Methodology

Each exercise includes:
- The prompt(s) used
- The generated model output(s)
- A brief analytical statement discussing observed differences in clarity, structure, or behavior

---

## Tools and Technologies

- ChatGPT / OpenAI Playground
- Python 3.9+
- OpenAI Python SDK (optional)

---

## Conclusion

This project demonstrates the importance of precise prompt design and parameter configuration when working with language models. Clearer prompts produce more structured and relevant outputs, while parameter adjustments influence response diversity and creativity.

The exercises provide practical experience in understanding how input design directly affects AI-generated responses.
