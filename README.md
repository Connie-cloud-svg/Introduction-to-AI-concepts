# Introduction-to-AI-concepts

A collaborative guide by [list all team member names].

## Table of Contents
- [Introduction](#introduction)
- [Machine Learning](#machine-learning)
- [Computer Vision](#computer-vision)
- [Large Language Models](#large-language-models)
  
## Introduction.
In itself, Artificial Intelligence (AI) is a branch of computer science dedicated to building machines and software that replicate or simulate human-like intelligence. AI is generally recognized as a system's ability to perceive its environment, reason through problems, and take actions to achieve a specific goal without being explicitly programmed for every single step.Below we shall cover three of it's concepts:

## Machine Learning 
<!-- [Team Member 1 Name] will write this section -->

## Computer Vision
<!-- [Team Member 2 Name] will write this section -->

## Large Language Models


# 1. What a Large Language Model Actually Is

A **Large Language Model (LLM)** is a neural network trained to **predict the next token** in a sequence.

That’s it.

Everything impressive — essays, code, strategy advice, poetry — comes from:

> Learning statistical structure of language at massive scale.

A token is not exactly a word. It can be:

* A word
* Part of a word
* A character
* Punctuation
* Even code symbols

The model predicts:

```
“The capital of France is ___”
```

and assigns probabilities:

* Paris → 92%
* Lyon → 5%
* London → 0.2%
* Banana → 0.0001%

Then it selects one.

Over billions of examples, this becomes intelligence-like behavior.

---

# 2. The Architecture: Transformers

Modern LLMs use the **Transformer architecture**, introduced in 2017 in the paper:

“Attention Is All You Need” by researchers at Google Brain.

Core innovation:

## Self-Attention

Instead of reading text sequentially like old RNNs, transformers:

* Look at all words simultaneously
* Learn which words matter to each other

Example:

> “The dog that chased the cat was fast.”

The model learns:

* “dog” connects to “was fast”
* Not “cat”

That’s attention.

---

# 3. Why They’re Called “Large”

They are large in:

### 1️⃣ Parameters

Billions to trillions of weights.

Examples:

* OpenAI GPT models: 100B+ range
* Meta LLaMA: tens to hundreds of billions
* Google Gemini: large-scale multimodal models

More parameters → more capacity → more emergent abilities.

But bigger ≠ always smarter. Architecture and data matter more than pure size.

---

# 4. Training Process (What Actually Happens)

There are 3 main phases:

---

## Phase 1: Pretraining

Massive internet-scale data:

* Books
* Code
* Articles
* Research papers
* Public data

Objective:
Predict next token.

This creates a **base model**.

---

## Phase 2: Fine-Tuning

The model is trained on curated data:

* Instruction-following examples
* Q&A pairs
* Coding datasets

Now it behaves more useful.

---

## Phase 3: RLHF (Reinforcement Learning from Human Feedback)

Humans rank outputs:

* Good vs bad
* Helpful vs harmful
* Safe vs unsafe

The model learns:
“How humans want answers structured.”

This is how conversational AI becomes aligned.

---

# 5. Core Technical Components

If you're serious about mastering this (which you should be if you're going AI/Quant), understand:

### 🔹 Tokenization

Text → token IDs
Uses algorithms like Byte Pair Encoding (BPE)

### 🔹 Embeddings

Tokens become vectors in high-dimensional space.

Think:

```
King - Man + Woman ≈ Queen
```

Vector arithmetic represents meaning.

### 🔹 Self-Attention Formula

Attention(Q,K,V) = softmax(QKᵀ / √d)V

If you don’t understand that yet — you will when you study linear algebra deeply.

### 🔹 Positional Encoding

Because transformers read in parallel, they must encode word order manually.

---

# 6. Emergent Abilities

As models grow:

* In-context learning emerges
* Reasoning improves
* Zero-shot learning improves
* Chain-of-thought emerges

These weren’t explicitly programmed.

They **emerge** from scale.

That shocked researchers.

---

# 7. Limitations (Don’t Be Delusional About Them)

LLMs:

* Do not “think”
* Do not “understand” like humans
* Do not have memory of reality
* Do not reason symbolically unless trained to simulate it

They:

* Predict patterns extremely well

Common problems:

* Hallucinations
* Overconfidence
* Math weaknesses (though improving)
* Lack of grounded truth unless connected to tools

---

# 8. Retrieval-Augmented Generation (RAG)

Instead of trusting memory:

LLMs can:

1. Search documents
2. Retrieve relevant chunks
3. Use them to generate grounded answers

This is how serious AI systems are built.

Companies don't just deploy raw LLMs.

---

# 9. Multimodal LLMs

Modern systems can process:

* Text
* Images
* Audio
* Code

Example:

* OpenAI GPT multimodal systems
* Google DeepMind Gemini

These are foundation models.

---

# 10. The Business Reality

Here’s where you need strategic clarity:

### Who wins?

* Infrastructure players (GPU makers like NVIDIA)
* Cloud providers
* Model creators
* Application layer founders

### Who loses?

* People who only “use ChatGPT”
* People who don’t build
* Coders who refuse to adapt

---

# 11. How This Connects to You

You want:

* Data science
* AI
* Quant
* Billionaire trajectory

Then you need to understand LLMs at three levels:

### Level 1: User

Prompting, system design, automation.

### Level 2: Engineer

Fine-tuning
RAG
API integration
Inference optimization

### Level 3: Research-Level

* Attention variants
* Scaling laws
* Optimization dynamics
* Alignment theory
* Parameter-efficient fine tuning (LoRA, adapters)

Right now, you should aim for Level 2 within 12–18 months.

---

# 12. Hard Truth

AI is not magic.

It is:

* Linear algebra
* Probability
* Optimization
* Massive compute
* Massive data

If your math is weak, your AI ceiling is low.

No shortcuts.

---




