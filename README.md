# Advanced-Mathematics-knowledge-graph
A structured dataset of high-level mathematics knowledge points and their instructional features
High-Level Mathematics Knowledge Graph Dataset and Prompt Templates

This repository contains a structured dataset and associated prompt templates generated from a project titled:
“Construction and Application of a High-Level Mathematics Knowledge Graph Based on Large Language Models (LLMs)”

Project Overview
Traditional higher mathematics education often suffers from fragmentation of concepts and lack of guided learning paths. This project leverages the capabilities of large language models (LLMs) to:

Automatically extract structured knowledge from university-level calculus textbooks

Reorganize content into graph-based knowledge nodes

Support instructional design, student learning, and intelligent feedback systems

Dataset Highlights
Volume: Over 6,000 structured entries
Chapters covered:
Chapter 1: Limits and Continuity
Chapter 2: Derivatives and Differentiation
Chapter 3: Mean Value Theorems and Function Properties

Structure per entry:
Concept: Formal mathematical definition
Usage Notes: Pre-conditions, error-prone cases
Exam Patterns: Common question types and solving models

Examples: Linked textbook problems and reasoning paths
Format: .csv, .json, Markdown snippets (ready for downstream use)
Prompt Design Philosophy

We designed four types of instructionally-oriented prompts to steer LLM output toward teaching-compatible structures:
Concept Extraction: Definitions + Classification

Usage Conditions: Error cases + Applicability
Exam Patterns: Solving models + Judgement strategies
Examples Matching: Problem alignment + Labeling
See prompt_templates.md for detailed examples.
Each prompt is optimized for output stability, format clarity, and semantic alignment with textbook logic.

Evaluation
Metric	Score (out of 5)
Coverage	4.5
Label Accuracy	4.4
Structural Consistency	4.3
Pedagogical Suitability	4.2
Model Stability	4.1
Manual Revision Rate (Inverse)	4.6

Our optimized prompt chain improved average model first-pass accuracy by 15–20%, and reduced manual revision workload significantly.

How to Use
Explore Dataset
Browse data/ directory for CSVs or JSON outputs
Preview samples/ for fully annotated records
LLM Developers
Use prompt templates in prompt_templates.md
Combine with textbook content to generate new instructional graphs
Educators
Integrate dataset with teaching dashboards, graph-based student assistants, or automatic feedback systems
Citation & Acknowledgment
This repository is part of a university research initiative on AI for education. Please cite accordingly if used in academic or product development settings.
Contributing
We welcome improvements, new prompt designs, or evaluation tools. Feel free to fork, submit issues, or open pull requests.

License
MIT License. Educational use encouraged.
