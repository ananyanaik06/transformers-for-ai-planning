# Transformers for AI Planning

A curated collection of research paper summaries, critical analyses, and reading notes on AI Planning, Transformer-based Planning, Learned Heuristics, and Large Language Models (LLMs) for planning.

## Motivation

Modern AI planning is increasingly influenced by advances in deep learning and transformer architectures. This repository serves as my personal research notebook for understanding the intersection of:

* Classical AI Planning
* Automated Planning Systems
* Learned Heuristics
* Transformer-Based Planning
* Neuro-Symbolic Planning
* Large Language Models for Planning

The goal is to move beyond reading papers and develop a deeper understanding of the ideas, assumptions, strengths, limitations, and future directions of planning research.

---

## Papers Covered

| # | Paper                                                                                    | Main Topic                         |
| - | ---------------------------------------------------------------------------------------- | ---------------------------------- |
| 1 | Beyond A Better Planning with Transformers                                               | Transformer-based Planning         |
| 2 | Dualformer: Controllable Fast and Slow Planning                                          | Fast & Slow Planning Architectures |
| 3 | Large Language Models Still Can't Plan (2022)                                            | LLM Planning Evaluation            |
| 4 | Learning Domain-Independent Heuristics for Classical Planning with Graph Neural Networks | Learned Heuristics                 |
| 5 | Symmetry-Aware Transformer Training for Automated Planning                               | Generalization & Inductive Biases  |

---

## Reading Note Format

Each paper is summarized using the following structure:

* One-Line Summary
* Problem Statement
* Core Idea
* Key Concepts
* Methodology
* Results
* Strengths
* Weaknesses
* Personal Insights
* Connections to Other Work

The focus is on understanding the reasoning behind each paper rather than simply reproducing the abstract.

---

## Key Research Themes

### Classical Planning

* STRIPS
* PDDL
* State-Space Search
* Heuristic Search

### Learning for Planning

* Learned Heuristics
* Graph Neural Networks
* Representation Learning

### Transformer-Based Planning

* Sequence Modeling
* Planning as Prediction
* Fast and Slow Planning

### LLM Planning

* Reasoning About Actions and Change
* Plan Generation
* Replanning
* Tool-Augmented Planning
* Neuro-Symbolic Systems

---

## Current Takeaways

Some recurring ideas that appear across multiple papers:

* Planning is more than pattern matching.
* State-space search remains difficult for purely neural models.
* Learned heuristics can significantly improve search efficiency.
* Transformer models can capture planning patterns but may struggle with explicit search.
* Combining symbolic planning with neural models is often more effective than using either alone.

---

## Repository Structure

```text
transformers-for-ai-planning/
│
├── README.md
│
├── papers/
│   ├── 01-beyond-a-better-planning-with-transformers.md
│   ├── 02-dualformer.md
│   ├── 03-large-language-models-still-cant-plan.md
│   ├── 04-learning-domain-independent-heuristics.md
│   └── 05-symmetry-aware-transformer-training.md
│
└── pdfs/
    ├── paper PDFs
```

---


---

## Disclaimer

These notes are intended for learning and research purposes. They reflect my understanding of the papers and may contain interpretations, critiques, and personal observations beyond the authors' original claims.
