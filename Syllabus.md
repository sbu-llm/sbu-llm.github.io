---
layout: page
title: Syllabus
permalink: /Syllabus/
---

#  Expert Systems (Engineering for Large Language Models)

**Level:** Undergraduate

**Prerequisites:** Python Programming, Basic Machine Learning Concepts

**Instructors:** Dr. Saeed Reza Kheradpisheh, Milad Vazan

---

## Course Overview

This course is a comprehensive and advanced program in the field of **Generative AI** and **Agentic AI**, covering everything from fundamental principles to advanced architectures and practical implementation. Students will become familiar with foundational concepts of neural networks, the Transformer architecture, Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) systems, fine-tuning techniques, and the design of intelligent AI Agents.

The curriculum is designed to take students from basic concepts to the cutting-edge technologies of today, addressing the growing industry demand for skilled professionals in systems based on large language models. With a comprehensive and practical perspective, this course aims to bridge the gap between the theoretical foundations of artificial intelligence and the practical needs of the industry.

---

## Course Objectives

### 🔭 Forward-Looking Perspective
- Familiarity with modern architectures such as Mamba, MoE, and reasoning models that shape the next generation of AI systems.
- Examination of research trends in agent memory, multi-agent systems, and inference scalability.
- Ability to analyze and predict future developments in autonomous intelligent agents and human-machine interaction.

### 🏭 Industry Relevance and Job Market Needs
- Training on widely-used industry tools and frameworks: Hugging Face, ChromaDB, FastAPI, and MCP and A2A standards.
- Implementation of real-world projects including a complete RAG system, conversational agents, and deployable multi-agent systems.
- Familiarity with operational optimizations such as cost reduction and speed enhancement.

### 🎓 Academic and Research Relevance
- In-depth study of foundational and latest research papers in areas like Attention, RAG, Agentic Memory, and Reasoning.
- Final projects that can potentially lead to scientific publications or open-source contributions.

---

## Learning Outcomes

By the end of the course, students will be able to:

### 📚 Knowledge
- Explain the Transformer architecture, Attention mechanisms, and tokenization and embedding methods effectively.
- Correctly distinguish between generative, agent-based, and traditional AI models.
- Analyze key challenges such as hallucination, context window limitations, and data bias.

### 🧠 Analytical Skills
- Design, implement, and evaluate a complete RAG system from scratch using appropriate metrics.
- Compare different retrieval methods and select the best option for a given scenario.
- Fine-tune language models using efficient techniques (like LoRA) and measure their impact.

### 🛠️ Practical Skills
- Work with tools such as Hugging Face Transformers, ChromaDB, LangChain, and FastAPI.
- Design and implement intelligent agents with tool calling capabilities and long-term memory.
- Implement multi-agent systems with specialized roles (e.g., Researcher, Writer, Reviewer) and manage their coordination.

### 🔬 Critical and Research Thinking
- Evaluate the strengths and weaknesses of various compression, knowledge distillation, and evaluation methods.
- Predict agent failure scenarios and propose recovery strategies.
- Present their findings in a final project with scientific documentation and operational code.

---

## Course Syllabus

| Part | Topic | Sessions |
|:----:|:------|:--------:|
| 1 | Evolution and Fundamentals of AI | 2 |
| 2 | Infrastructure and Foundations of Language Models | 6 |
| 3 | Advanced Prompt Engineering and Reasoning | 1 |
| 4 | External Knowledge and RAG | 5 |
| 5 | Fine-tuning and Optimization | 2 |
| 6 | Agentic AI | 6 |
| 7 | Supplementary Topics, Evaluation, and Deployment | 3 |
| - | **Final Project** | - |

---

## Assessment

| Assessment Component | Grade | Description |
|:---------------------|:-----:|:------------|
| Attendance and Active Participation | 2 | Regular attendance and active participation in scientific discussions, Q&A, and group discussions |
| Practical Assignments | 6 | 4 to 6 practical exercises |
| Final Project with Report | 9 | Comprehensive end-of-term project including design, implementation, evaluation, and thorough documentation |
| Final Exam | 3 | Comprehensive exam covering theoretical concepts, analytical questions, and practical problems |
| **Total** | **20** | |

---

## Communication and Help Channels

To resolve ambiguities and seek guidance, please use the following resources in order of priority:

1. **Messenger** — The class Telegram group serves as the main platform for communication, announcements, and scientific discussions. This space is highly suitable for asking questions whose answers would also benefit other students.

2. **Instructor Consultation** — For personal, urgent, or complex matters:
   - Before class starts – a short opportunity to ask questions
   - During class – by raising your hand or asking at an appropriate time
   - Email – send your questions to the instructor's email address

---

## Collaboration Policy

Discussion and dialogue about the course content with anyone is free and highly encouraged. However, adherence to academic ethics is mandatory in all assignments, projects, and exams.

### ✅ Permitted
- Discussing concepts, algorithms, and general ideas with classmates
- Using reputable educational resources (books, articles, official documentation)
- Studying sample code to better understand concepts
- Using AI as a supplementary learning aid

### ❌ Not Permitted
- Copying solutions, in whole or in part, from other students
- Collaborating on writing code or solving specific assignment problems
- Using pre-made solutions from the internet without citing the source
- Submitting identical or highly similar answers from multiple students
- Using AI to generate complete assignment or project solutions

---

## Detailed Teaching Schedule

### Part 1: Evolution and Fundamentals of AI (2 Sessions)

<details>
<summary><b>Session 1: The Evolution of AI and Foundational Concepts</b> (Instructor: Dr.)</summary>

- General course introduction and prerequisites
- Review of history: from Symbolic AI and expert systems to machine learning and deep learning
- The emergence of Foundation Models and their differences from traditional models
- Key differences: Generative AI vs. traditional AI
- Operational applications of Generative AI: text, image, code, video, audio generation, and multimodal systems
- Introduction to Language Models
</details>

<details>
<summary><b>Session 2: Comprehensive Review of Neural Networks (Pre-requisite)</b> (Instructor: Dr.)</summary>

- Architecture: from Simple Perceptron to Multi-Layer Perceptron (MLP)
- Activation Functions: Sigmoid, Tanh, ReLU, Leaky ReLU, GELU
- Loss Functions: MSE, MAE, Cross-Entropy, Binary Cross-Entropy
- Weight Update Algorithm: Gradient Descent and its variants (SGD, Adam, RMSprop)
- Concept of Backpropagation and the chain rule for differentiation
- Hyperparameter Tuning: Learning Rate, Batch Size, Epoch
</details>

---

### Part 2: Infrastructure and Foundations of Language Models (6 Sessions)

<details>
<summary><b>Session 3: Tokenization and Embedding</b></summary>

- Why do machines need numbers? Converting text to numbers, importance of numerical representation
- Classical Vectorization Methods: Bag of Words (BoW), TF-IDF, One-hot encoding, n-grams
- Concept of Embedding: Mapping words to vector space, dimensionality reduction and preserving meaning
- Word2Vec and GloVe: CBOW and Skip-gram, differences and applications
- Modern Tokenization Methods: BPE, WordPiece, SentencePiece, Special Tokens
- Tokenization Best Practices and Implementation with Hugging Face
- Concept of Distance in Vector Space: Cosine Similarity, Euclidean Distance
</details>

<details>
<summary><b>Session 4: Transformer Architecture (Part 1 - Attention)</b></summary>

- Problems with older sequential models (RNN, LSTM)
- Self-Attention and Multi-Head Attention mechanisms
- Mathematics behind Q, K, V (Query, Key, Value)
- Attention Pathologies: Attention Sink, Attention Dilution, Other Attention Phenomena
</details>

<details>
<summary><b>Session 5: Transformer Architecture (Part 2 - Complete Structure)</b></summary>

- Positional Encoding: Sinusoidal, Learned, Relative
- Original Encoder-Decoder Transformer
- Decoder-Only vs. Encoder-Decoder: BERT (Encoder), GPT (Decoder), T5 and BART (Encoder-Decoder)
- Visualizing Attention for Explainability
</details>

<details>
<summary><b>Session 6: Prediction Heads and Modern Embeddings</b> (Instructor: Dr.)</summary>

- Prediction Heads: Language Modeling Head, Conditional Generation Head, Value Head
- Limitations of Static Embeddings
- Contextual Embeddings: ELMo, BERT as an Embedding, Extracting Embeddings from BERT
</details>

<details>
<summary><b>Session 7: Vector Databases + ChromaDB</b></summary>

- Why are RDBMSs inefficient for vector data?
- Concept of Semantic Space
- Approximate Nearest Neighbor (ANN) Search Algorithms: LSH, IVF, HNSW
- Practical Part: ChromaDB (Installation, Collections, Storing Embeddings, Similarity Queries)
- Comparison of Vector Databases
</details>

<details>
<summary><b>Session 8: LLM Challenges and Limitations</b> (Instructor: Dr.)</summary>

- Hallucination: Types, Detection Methods, Roots
- Context Window Limitation: Token limits, Solutions (Sliding Window, Positional Interpolation)
- Knowledge Cutoff
- Data Biases
- Security Issues
- Lack of Grounding
- Failure in Multi-Step Reasoning
</details>

---

### Part 3: Reasoning (1 Session)

<details>
<summary><b>Session 9: Advanced Prompt Engineering</b></summary>

- **Basic Concepts:** Importance of prompt writing, In-Context Learning, Zero-shot, Few-shot, Instruction-Following, Structured Output, Best Practices
- **Chain of Thought (CoT):** Concept, Zero-shot CoT, Few-shot CoT, Numerical and logical examples
- **Tree and Graph of Thoughts:** Limitations of CoT, ToT, GoT
- **New Techniques:** Self-Ask, Plan-and-Solve
</details>

---

### Part 4: External Knowledge and RAG (5 Sessions)

<details>
<summary><b>Session 10: Fundamentals of RAG</b> (Instructor: Dr.)</summary>

- Why RAG? Parametric vs. Non-Parametric Knowledge, When to Use RAG vs. Fine-Tuning vs. Long Context
- General RAG Architecture: Full Pipeline, Indexing, Retrieval, Generation
- Introduction to RAG Types
- Concept of Chunking: Fixed-Size with Overlap, Semantic, Document-Structure-Aware, Parent-Child, Empirical Guidelines
</details>

<details>
<summary><b>Session 11: Advanced Retrieval Methods</b></summary>

- Sparse Retrieval: BM25, TF-IDF
- Dense Retrieval: DPR
- Hybrid Retrieval with Reciprocal Rank Fusion
- Learned Sparse Retrieval: SPLADE, SPLADEv2
- ColBERT: Late Interaction
- CAG (Cache-Augmented Generation)
- KAG (Knowledge-Augmented Generation)
</details>

<details>
<summary><b>Session 12: Retrieval Optimization</b></summary>

- Query Transformation: Rewriting, Expansion, Multi-Query Retrieval
- Re-Ranking with Cross-Encoders
- Contextual Compression
- Self-RAG (Reflection and self-correction)
- CRAG (Corrective RAG)
- Adaptive RAG
- Graph RAG
- RAG-Fusion
</details>

<details>
<summary><b>Session 13: Evaluation of RAG Systems and LLMs</b></summary>

- Evaluation Scheme Design
- Data Collection: Human Annotation Pipelines, Inter-Annotator Agreement, Guideline Design
- Synthetic Data Generation: LLM-as-Judge, Self-Instruct, Evol-Instruct, Constitutional AI, Distillation
- Metrics: BLEU, ROUGE, BERTScore, METEOR, Perplexity, Pass@k, Exact Match, F1
- RAG Evaluation
</details>

<details>
<summary><b>Session 14: RAG Practical Workshop (Complete Project)</b></summary>

- Implementation of a Complete RAG System: Domain selection, Data collection, Preprocessing, Chunking
- Parameter Optimization: Chunk Size, Overlap, Top-K, Embedding Model Selection
- Adding Chat History: Multi-turn conversations, Maintaining history
- System Deployment: API with FastAPI, Simple user interface
- Production Considerations: Latency Optimization, Incremental Indexing, Versioning
</details>

---

### Part 5: Fine-tuning and Optimization (2 Sessions)

<details>
<summary><b>Session 15: Fine-tuning Fundamentals and LoRA</b></summary>

- **Fundamentals:** SFT Objective, Data Quality (LIMA Principle), Training Configuration, Efficient Training Solutions, Best Practices
- **LoRA (Low-Rank Adaptation)**
- **LoRA Variants**
- **Other PEFT Approaches**
</details>

<details>
<summary><b>Session 16: Knowledge Distillation and Model Compression</b></summary>

- Knowledge Distillation: Teacher-Student architecture, Types, Practical implementation
- Comprehensive Comparison of Compression Methods: Quantization, Pruning (Structured vs. Unstructured)
- When to use each method?
- Model Compression in Practice
</details>

---

### Part 6: Agentic AI (6 Sessions)

<details>
<summary><b>Session 17: Definitions and Key Distinctions</b></summary>

- Introduction to Agentic AI: Generative AI vs. AI Agent vs. Agentic AI
- General Architecture of an Agent: Planning, Memory, Tool Use
- **Agent Harness:** What Is an Agent Harness? Context Window Management (Context Budget, Allocation, Compression, Sliding Window, Recursive Decomposition, Token Counting)
- **Prompt Architecture:** System Prompt Design, Dynamic Prompt Assembly, Few-Shot Management, Tool Descriptions
- Introduction to the MCP Standard: Motivation, Architecture Overview, Core Primitives
</details>

<details>
<summary><b>Session 18: Agent Architecture and Tool Calling</b></summary>

- **Tool Calling / Function Calling:** Concept
- **Tool Integration:** Connecting Tool Calling to Reasoning Loop, Tool Definition Schemas, Selection, Output Processing, Sandboxing
- Using MCP for Tool Calling: Building MCP Server/Client, Connecting to Multiple Servers
- Comparison of implementations in frameworks
</details>

<details>
<summary><b>Session 19: Agent Design Patterns</b></summary>

- **Workflow Patterns:** Prompt Chaining, Routing, Parallelization, Orchestrator-Workers, Evaluator-Optimizer
- **Autonomous Agent Patterns:** ReAct, Planning Agents, Reflection and Self-Critique, Tool-Use Patterns
- **Orchestration Patterns:** ReAct Loop, Plan-and-Execute, Multi-Agent Orchestration, Human-in-the-Loop, Workflow Graphs
- **State Management:** Conversation, Task, Agent, Persistent State
- **Error Handling and Recovery:** Retry Strategies, Loop Detection, Graceful Failure, Observability
</details>

<details>
<summary><b>Session 20: Multi-Agent Systems - Part 1</b></summary>

- Why Multiple Agents?
- **Multi-Agent Architectures:** Centralized, Decentralized, Hierarchical, Swarm
- **Coordination Mechanisms:** Shared State, Message Passing, Planning and Decomposition, Voting and Consensus, Market-Based, Stigmergy
- **Communication Protocols:** Structured Message Formats, Performative Types, Context Sharing
- **Agent-to-Agent Communication (A2A):** Motivation, Google A2A Protocol, Communication Patterns, Agent Discovery and Routing
</details>

<details>
<summary><b>Session 21: Practical Multi-Agent Implementation</b></summary>

- Implementing a Multi-Agent Scenario: Researcher, Writer, Editor
- Implementing a Debate Scenario: Pro, Con, Judge
- **Role Design and Specialization:** Defining Roles, Capability vs. Role-Based Assignment, Dynamic Reassignment, Persona Design
- **Multi-Agent Patterns for LLMs:** Debate, Reflection, Division of Labor, Pipeline, Ensemble, Teacher-Student, Red Team
</details>

<details>
<summary><b>Session 22: Memory in Agentic Systems</b></summary>

- Why Agents Need Memory
- **Taxonomy of Memory Types:** Working, Episodic, Semantic, Procedural
- **Memory Architectures:** RAG-Based, Summarization-Based, Graph-Based, Key-Value, MemGPT
- **Memory Operations:** Write, Read/Retrieve, Update, Reflect
- **Memory for Multi-Turn Conversations:** User Modeling, Session Continuity, Personalization
- **Memory for Multi-Agent Systems:** Shared Memory Pools, Blackboard Architecture, Consensus and Conflict
- **Recent Advances:** CoALA, Mem0, Sleep-Time Compute, A-MEM
</details>

---

### Part 7: Supplementary and Advanced Topics (3 Sessions)

<details>
<summary><b>Session 23: Advanced Architectures and New Models</b></summary>

- **Architectures Beyond Transformer:** Mamba (SSM), RWKV, Hybrid Models
- **Mixture of Experts (MoE):** Architecture, Load Balancing, Noisy Top-K Gating, Notable MoE Models
- **Diversity in LLM Training:** Sampling, Training Data, Diversity-Promoting Methods
- **Text Generation Decoding Methods:** Greedy, Beam Search, Diverse Beam Search, Top-k, Top-p, Min-p, Temperature, Contrastive, Repetition Penalties, Constrained
- **Advanced Reasoning Models:**
  - DeepSeek-R1: Two-Stage Training, Reward Design, GRPO, Distillation
  - OpenAI o1/o3: CoT RL, Process vs. Outcome Reward Models, Inference-Time Compute Scaling
  - QwQ/Qwen: Multi-Stage RL, Rejection Sampling, Tool-Integrated Reasoning
- **Scaling Laws for Reasoning:** Training vs. Test-Time Compute Tradeoff, Optimal Token Budget Allocation
</details>

<details>
<summary><b>Session 24: Evaluation and Testing of Agentic Systems</b></summary>

- **Metrics for Agentic Tasks:** Task Success Rate, Trajectory Efficiency, Tool-Use Accuracy, Multi-Step Reasoning Accuracy, SWE-bench, WebArena
- **LLM-as-Judge:** Setup, Prompt Templates, Position Bias Mitigation, Multi-Judge Panels, Agreement Metrics, G-Eval
- **Evaluation Pitfalls:** Benchmark Contamination, Overfitting, Goodhart's Law
- **Agent Testing:** Unit Testing Tools, Integration Testing, Regression Testing, Behavioral Testing, Cost and Latency Testing
</details>

<details>
<summary><b>Session 25: Safety, Privacy, and Responsible Deployment</b></summary>

- **LLM Safety:** Threat Taxonomy, Safety Training Pipeline, Key Mechanisms, Helpfulness–Safety Tradeoff, Evaluation
- **Security in Multi-Agent Systems:** Identity Verification, Message Integrity, Authorization, Audit Trails
- **MCP Security Model:** Trust Hierarchy, User Consent, Input Validation, Credential Management, Sandboxing
- **Production Deployment Patterns:** Async Execution, Multi-Tenant Isolation, Cost Optimization, Auto-Scaling
- **Observability and Debugging:** Tracing, Failure Categorization, Replay and Debugging Workflows
- **Scaling and Production Concerns:** Latency Optimization, Cost Management, Rate Limiting, Evaluation in Production
</details>

---

### Final Project

<details>
<summary><b>Session 26: Final Project Presentation</b></summary>

- Presentation of final projects by students
- Project review and critique by the instructor and other students
</details>

---

## References and Resources

There is no single designated textbook for this course. Instead, educational content is compiled from a combination of reputable and up-to-date sources, including specialized books, scientific articles, and technical documentation.

However, a highly valuable and comprehensive resource that can serve as a primary reference and practical guide for many parts of this course is:

> **Title:** *The Hitchhiker's Guide to Agentic AI: From Foundations to Systems*  
> **Author:** Haggai Roitman  
> **Year:** 2026  
> **Access:** arXiv:2606.24937

This recently published book is a complete and practical reference for building agentic AI systems.



## **A note on self care.** 
Please take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress. 
