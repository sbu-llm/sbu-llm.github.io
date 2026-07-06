---
layout: page
title: Syllabus
permalink: /Syllabus/
---

#Expert Systems (Engineering for Large Language Models)

**Level:** Undergraduate  
**Prerequisites:** Python Programming, Basic Machine Learning Concepts  
**Instructors:** Dr. _, _ 

---

## Course Objectives

This course is designed to introduce undergraduate students to the evolution of artificial intelligence—from symbolic approaches to foundation models and generative/agentic systems. Students will begin by understanding the trajectory of AI development and the differences between traditional AI and generative AI, then progress to foundational topics such as vectorization, vector databases, and subsequently delve into large language models, retrieval-augmented generation and its variants, memory, reasoning, and finally fine-tuning and practical implementation of agentic AI systems.

The curriculum is structured to take students from basic concepts to the cutting-edge technologies of today, addressing the growing industry demand for skilled professionals in LLM-based systems. With a comprehensive and practical perspective, this course aims to bridge the gap between theoretical AI foundations and real-world industry requirements.

**Forward-Looking Perspective:** Beyond teaching current technologies, this course prepares students to face future AI developments. Through deep understanding of fundamental principles and underlying architectures, students will be able to quickly grasp and adopt emerging technologies as they appear.

**Industry Relevance and Market Needs:** The syllabus has been designed based on current market demands. Topics such as RAG, intelligent agents, efficient fine-tuning, and system evaluation rank among the most sought-after skills in today's job market.

---

## Learning Outcomes

By the end of this course, students will be able to:

1. Understand the concept of LLMs and their limitations
2. Explain Text Vectorization, Embeddings, and Vector Databases
3. Articulate the concepts of Semantic Space and Cosine Similarity
4. Compare the structure and types of RAG systems
5. Recognize Memory concepts in agentic systems at various levels
6. Distinguish between AI Agent, Agentic AI, and Generative AI
7. Identify and conceptually apply Fine-tuning methods such as LoRA, QLoRA, and newer approaches
8. Describe the Transformer architecture and Self-Attention mechanism

---

## Course Syllabus

### Part 1: Evolution and Foundations of Artificial Intelligence (1 session)

**Objective:** Understanding the historical trajectory and differences between AI paradigms.

#### Evolution of Artificial Intelligence
- Symbolic AI and Fuzzy Logic
- Expert Systems
- Machine Learning
- Deep Learning
- Foundation Models
- Generative AI
- Agentic AI

#### Differences Between Traditional and Generative AI

#### Operational Applications of Generative AI
- Text Generation
- Image Generation
- Code Generation
- Video & Audio Generation
- Multimodal Systems

---

### Part 2: Infrastructure and Foundations of Language Models

**Objective:** Deep understanding of how machines comprehend language and manage vector data.

#### Why Do Machines Need Numbers?
- Text Vectorization & Embeddings
  - Classical Methods: Bag of Words, TF-IDF, One-hot encoding, n-grams
  - Word Embeddings: Word2Vec, GloVe, FastText
  - Transformer Architecture (In-depth Review)
  - Contextual Embeddings: ELMo, BERT
  - Modern Tokenization Techniques: BPE, WordPiece, SentencePiece

#### Vector Databases
- Concept of Semantic Space and Cosine Similarity
- Differences Between RDBMS and Vector Databases
- Approximate Nearest Neighbor Search Algorithms
- Hands-on Introduction to ChromaDB

#### LLM Challenges and Limitations
- Hallucinations and Their Causes
- Context Window Limitations
- Knowledge Cutoff and Lack of Real-time Awareness
- Bias
- Security Issues (Prompt Injection)
- Lack of Grounding and Real-world Connection
- Cost and Latency in Deployment
- Reasoning Failures in Multi-step Problems

---

### Part 3: Reasoning

**Objective:** Moving beyond simple prompting to reasoning engineering in LLMs.

#### Advanced Prompt Engineering and Reasoning
- Zero-shot, Few-shot Prompting
- Chain of Thought (CoT): Forcing Step-by-Step Thinking
- Tree of Thoughts (ToT) and Graph of Thoughts (GoT)
- Self-Consistency and ReAct (Reasoning + Acting)

---

### Part 4: External Knowledge and Information Retrieval

**Objective:** Overcoming hallucination and LLM limitations by connecting to external data and structured knowledge.

#### Fundamentals and Types of RAG (Retrieval-Augmented Generation)
- Chunking
- CAG (Cache-Augmented Generation)
- KAG (Knowledge-Augmented Generation)

#### RAG System Evaluation and Optimization
- Evaluation Metrics: Faithfulness, Answer Relevancy, Context Relevancy
- Retrieval Stage Optimization:
  - Reranking
  - HyDE (Hypothetical Document Embeddings)
  - Multi-Query Retrieval

---

### Part 5: Fine-tuning and Model Optimization

**Objective:** Personalizing foundation models for specific domains and tasks with minimal cost.

#### Fine-Tuning Fundamentals
- Full Fine-Tuning vs. Parameter-Efficient Fine-Tuning (PEFT)
- LoRA and Its Derivatives

#### Training Tools and Frameworks
- Working with Hugging Face

---

### Part 6: Agentic AI

**Objective:** Transforming LLMs from "text generators" to "autonomous agents" capable of planning and using tools.

#### Definitions and Conceptual Distinctions
- Generative AI
- AI Agent
- Agentic AI

#### AI Agent Architecture

#### Multi-Agent Systems (MAS)
- Why Multi-Agent? (Task Division, Specialization, Hallucination Reduction)
- Communication Patterns: Sequential, Hierarchical, Debate/Collaboration

#### Memory Systems in Agents
- Short-term / Working Memory
- Long-term Memory
- Episodic, Semantic, and Procedural Memory

---

## Assessment

| Assessment Component | Grade | Description |
|----------------------|-------|-------------|
| Attendance & Active Participation | 2 point | Regular class attendance and participation in scientific discussions and Q&A |
| Practical Assignments | 6 points | 4 to 6 practical exercises including implementation of RAG systems, intelligent agents, fine-tuning, and working with vector databases |
| Final Project with Report | 9 points | Comprehensive end-of-term project |
| Final Examination | 3 points | Comprehensive final exam covering theoretical and analytical concepts |

---

*Total: 20 points*



## **Seeking Assistance**

Here are the available help resources, organized by the urgency of your issue:

### **Messaging**
Our course will utilize a Telegram group (link to be provided in class) as the primary communication platform for announcements and discussions. This is an ideal space for asking questions that can be answered by anyone. It's best to use this resource for non-urgent inquiries.

### **Talk with the Instructor**
For any issues at all, please reach out to the instructor:

- Speak with me before class  
- Raise your hand or speak up during class

## **Required Tools and Accounts**

To successfully participate in this course, students are expected to prepare the following tools and accounts prior to the practical sessions:

- **Python**: [Install](https://www.python.org/downloads/) the latest stable version of Python.
- **GitHub Account**: Create a [GitHub](https://github.com/) account.


 
## **Collaboration Policy**

You are encouraged to discuss the content of this course with anyone you like; however, it is essential to **maintain academic integrity** in your work. All homework assignments, projects, and exams must be completed independently, meaning you are not permitted to copy any part of another student’s solution, collaborate with others on your assignments, or use solutions from unauthorized sources, including the Internet. **Therefore, the solution you submit for each assignment must be solely your own, reflecting your understanding and effort.**


## **Related Courses**

- [UC Berkeley](https://cs186berkeley.net/)

## **A note on self care.** 
Please take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress. 
