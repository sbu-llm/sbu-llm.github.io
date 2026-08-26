---
layout: page
title: Project
permalink: /project/
---

## Final Project

**Semester:** Fall 2026-2027

**Grade Value:** 9 points

---

## Project Topic Selection Guide

Students may choose one of the topics listed in this document and define their project accordingly. Students may also propose a new topic; in this case, the instructor will determine the appropriate level.

### Project Leveling Based on Team Size

| Project Level | Team Size | Description |
|:-------------:|:---------:|:------------|
| Level 1 | 1 person | Individual projects |
| Level 2 | 2 persons | Two-person projects |
| Level 3 | 3 persons | Three-person projects |

**Important Notes:**
- A student with a one-person team is permitted to undertake Level 2 and Level 3 projects.
- However, multi-person teams **cannot** choose lower-level projects (e.g., Level 1 with two people).

---

## Final Reminders

- Topic selection must be announced to the instructors by **October 23, 2026**.
- The final report must include: design, implementation, evaluation, complete documentation, and expected outputs.
- Projects must be presented in the final session.
- Multi-person teams are required to ensure that **all members actively and effectively participate** in all stages of the project (design, implementation, evaluation, documentation, and presentation).
- At the end of the semester, each team member must submit a **separate individual performance report** specifying exactly which parts they were responsible for.
- Each topic from the provided list (or proposed by students), regardless of level (1, 2, or 3) and regardless of team size, can be selected by a **maximum of 2 teams**.

**Strong Recommendation:** Clear division of labor and use of project management tools (such as GitHub Projects) to track tasks and progress is highly recommended to avoid any ambiguity or disputes.

---

## Topic List

### Level 1

- [Topic 1: Autonomous Agent System with "Doubt" and "Reconsideration" Capabilities](#topic-1-autonomous-agent-system-with-doubt-and-reconsideration-capabilities)
- [Topic 2: Digital Twin with Deep Persona Modeling](#topic-2-digital-twin-with-deep-persona-modeling)
- [Topic 3: Automated Scientific Literature Browser](#topic-3-automated-scientific-literature-browser)

### Level 2

- [Topic 1: Industrial Data Analysis System with Intelligent Agents](#topic-1-industrial-data-analysis-system-with-intelligent-agents)
- [Topic 2: Intelligent Agent for Knowledge Extraction from Scientific Papers and Knowledge Graph Construction](#topic-2-intelligent-agent-for-knowledge-extraction-from-scientific-papers-and-knowledge-graph-construction)
- [Topic 3: Customer Support Conversation Analysis Agent](#topic-3-customer-support-conversation-analysis-agent)
- [Topic 4: Multi-Agent Simulation of Fictional Societies](#topic-4-multi-agent-simulation-of-fictional-societies)

### Level 3

- [Topic 1: Automated Scientific Paper Writing Agent with Research and Citation](#topic-1-automated-scientific-paper-writing-agent-with-research-and-citation)

---

## Level 1 Topics

### Topic 1: Autonomous Agent System with "Doubt" and "Reconsideration" Capabilities

**Core Challenge:**

Current systems are either overconfident (hallucination) or lack confidence entirely. You need to design a system that:
- Detects when it has made a mistake (without needing external feedback)
- Can reconsider its reasoning path
- Admits mistakes and takes a new path
- Changes its opinion if new evidence is found

**Suggested Capabilities:**

1. **Logical Doubt Module:**
   - After each answer, an internal critic evaluates the response from 3 different angles:
     - Contradiction (with previous answers)
     - Misalignment with basic knowledge
     - Reasoning weakness (gaps in the logical chain)
   - If the Critic scores below 70%, the Agent enters reconsideration mode.

2. **Reconsideration Mode:**
   - Agent completely forgets the previous answer (Reset Context)
   - Uses a completely different method (e.g., if previously CoT, now uses ToT)
   - Compares the new answer with the previous one and selects the best

3. **Error Memory:**
   - Stores all mistakes with details:
     - What was the question?
     - What mistake was made?
     - What was the cause? (insufficient data, faulty reasoning, bias)
   - When facing similar questions, warns: "I've made mistakes on this topic before, let's be more careful"

4. **Dynamic Confidence Metric:**
   - Each answer has a confidence score (0 to 100)
   - If score is below 50, start response with phrases like "I'm not sure, but..."
   - If score is above 90, respond with full confidence

5. **Devil's Advocate Simulation:**
   - Create an adversary agent that always tries to refute the answer
   - The main agent must be able to defend against criticism or change its opinion
   - This process helps the agent discover its blind spots

**Expected Output:**
- A system that, on 50 challenging questions, says "I'm not sure" in 20% of cases (instead of hallucinating)
- Complete logs of the doubt and reconsideration process for each question
- Comparative chart: system accuracy with and without the doubt module
- Analytical report on error patterns in the system (what types of questions cause more mistakes?)

---

### Topic 2: Digital Twin with Deep Persona Modeling

**Core Challenge:**

Build a digital twin of a real or fictional character that not only has their knowledge but also simulates their thinking style, tone, biases, and even personality evolution over time.

**Suggested Capabilities:**

1. **Persona Extraction from Text:**
   - Extract personality from a dataset (e.g., letters, interviews, books):
     - Linguistic style: sentence length, specific words, grammatical structure
     - Worldview: attitudes toward life, politics, science
     - Biases: cognitive biases (e.g., optimism, pessimism, conservatism)
     - Knowledge: what they know and what they don't know

2. **Persona-Consistent Response Generation:**
   - Each response must be consistent with the persona
   - If it deviates from the persona, a Critic detects and corrects it

3. **Persona Evolution Over Time:**
   - Persona is not static! It should evolve based on new experiences
   - For example, if the character encounters new ideas, they might change their opinion
   - Implement an opinion change mechanism

4. **Counterfactual Simulation Mode:**
   - "What would this character do if placed in situation X?"
   - Simulate character decisions in various scenarios

5. **Emotional Memory:**
   - Each event has an emotional weight (positive/negative)
   - High-emotional-weight events are retained longer in memory
   - This makes the character behave more human-like

6. **Cognitive Dissonance Detection:**
   - If the character has two conflicting beliefs, the system detects and shows the conflict
   - The character attempts to resolve the conflict (change belief or justify)

**Expected Output:**
- A digital twin of a historical figure (e.g., Albert Einstein or Socrates) or a fictional character
- A 30-question interview with this character
- Comparison of character responses at the beginning and end of interaction (persona evolution)
- Psychological analysis of the generated persona
- Report: How can this technique be used to simulate customers in marketing?

---

### Topic 3: Automated Scientific Literature Browser

**Core Challenge:**

Students and researchers spend significant time searching, screening, and reading papers for literature reviews. You need to build a multi-agent system that:
- Takes a research question in natural language
- Generates appropriate search queries for arXiv
- Retrieves and scores papers for relevance
- Extracts methodology, findings, and future work sections from relevant papers
- Produces a synthesized report on common themes and research gaps

**Proposed Architecture (6 Agents):**

- **Query Construction Agent:** Converts the research question into multiple arXiv search queries
- **Search Agent:** Executes queries and collects results
- **Screening Agent:** Scores each paper for relevance to the research question
- **Knowledge Collection Agent:** Downloads relevant papers and extracts full text
- **Analysis Agent:** Extracts methodology, findings, and future work from each paper
- **Synthesis Agent:** Identifies common themes and research gaps, writes the final report

**Output:** A comprehensive report including paper summaries, main themes, and suggestions for future research

---

## Level 2 Topics

### Topic 1: Industrial Data Analysis System with Intelligent Agents

*Inspired by research: Agentic Data Analysis for Intelligent Manufacturing*

**Core Challenge:**

Data analysis in manufacturing industries requires technical experts who are expensive and scarce. Non-technical users (production managers, quality controllers) need to be able to ask questions from data and get answers. You need to build a system that:
- Allows non-technical users to ask questions from industrial data using natural language
- Analyzes data and generates charts
- Interprets results and explains them in simple language
- Operates with high accuracy and interpretability
- Works for 2 different industrial datasets

**Suggested Capabilities:**

1. **Lightweight Agentic Framework:**
   - Use LangGraph for agent orchestration
   - Agents should be modular to allow adding new tools

2. **Specialized Agents:**
   - **Query Understanding Agent:** Converts user question to data operations
   - **Search Agent:** Finds relevant data
   - **Analysis Agent:** Performs statistical analysis and computations
   - **Visualization Agent:** Generates appropriate charts
   - **Interpretation Agent:** Explains results in simple language

3. **Evaluation with Industrial Datasets:**
   - Use 2 manufacturing datasets (e.g., production line data and quality control data)
   - Design a standard set of questions
   - Compare system accuracy with direct prompting (without agents)

4. **Explainability:**
   - Each answer must be accompanied by analysis steps
   - User should see what calculations the system performed and why it reached that conclusion

5. **Integration with Existing Tools:**
   - System must work with Pandas, Matplotlib, and Seaborn
   - Accept CSV or Excel data as input

**Expected Output:**
- An industrial data analysis system with 5 specialized agents
- Execution on 2 industrial datasets with 50 standard questions
- Report: How much better does the agent-based system perform compared to direct prompting?
- Practical examples of questions and answers

---

### Topic 2: Intelligent Agent for Knowledge Extraction from Scientific Papers and Knowledge Graph Construction

**Core Challenge:**

Scientific papers contain valuable information (concepts, relationships between concepts, methods, findings), but manual extraction and organization is nearly impossible. You need to build an agent that:
- Takes a scientific paper as input
- Extracts key concepts
- Detects relationships between concepts (e.g., "X causes Y", "X is a method for Y")
- Constructs a knowledge graph from the paper
- Visualizes the graph

**Suggested Capabilities:**

1. **Concept Extraction Agent:**
   - Using NER (Named Entity Recognition) and key phrase extraction techniques, find main concepts
   - Categorize concepts into "Topic," "Method," "Finding," "Challenge"

2. **Relation Extraction Agent:**
   - For each pair of concepts, detect the relationship type:
     - Causes: X causes Y
     - Part-Of: X is part of Y
     - Method-For: X is a method for Y
     - Improves: X improves Y
     - Challenges: X is a challenge for Y
   - Use few-shot learning with standard relationship examples

3. **Graph Builder Agent:**
   - Store concepts as nodes and relationships as edges
   - Build the graph with NetworkX or Neo4j
   - Visualize the graph

4. **Graph Summarizer Agent:**
   - Produce a textual summary of the graph:
     - Main concepts
     - Most important relationships
     - Conceptual clusters (which concepts are related?)

5. **Paper Comparison Mode:**
   - User can compare two papers
   - System builds two knowledge graphs and identifies similarities/differences

**Expected Output:**
- A knowledge graph extraction system for scientific papers (with LangChain and multiple Agents)
- Execution on 20 papers from different fields (e.g., medicine, computer science, physics)
- 10 visual knowledge graphs with complete analysis

---

### Topic 3: Customer Support Conversation Analysis Agent

**Core Challenge:**

Companies have massive volumes of customer support conversations that manual analysis cannot handle. You need to build a multi-agent system that:
- Takes conversations (chat text or call transcripts) as input
- Summarizes each conversation
- Detects overall sentiment (positive/neutral/negative)
- Extracts key topics discussed
- Generates an analytical dashboard of conversation patterns

**Proposed Architecture (4 Agents):**

- **Summarizer Agent:** Summarizes each conversation into 3-5 key sentences
- **Sentiment Agent:** Detects overall tone (positive/neutral/negative)
- **Topic Extraction Agent:** Identifies 2-3 main topics discussed
- **Combiner Agent:** Aggregates all agent outputs into a cohesive JSON structure

**Output:** A JSON file containing summaries, sentiment, and topics for each conversation + a Streamlit dashboard

---

### Topic 4: Multi-Agent Simulation of Fictional Societies

*Inspired by research: BookWorld*

**Core Challenge:**

A system that turns a novel or story into a living world. Characters behave as independent agents, interact with each other, and create new stories that remain faithful to the original world. But beyond simple simulation, the system must:
- Extract characters with deep persona from the book
- Identify and simulate relationships between characters
- Respect the geography and constraints of the story world
- Generate new and creative stories in the same world
- Allow the user to enter the story as a new character

**Suggested Capabilities:**

1. **World Extraction:**
   - From a novel (e.g., Harry Potter, Tolkien, or Persian stories), extract:
     - Characters: traits, goals, relationships
     - World rules: magic, technology, physical constraints
     - Geography: locations, distances, paths
     - History: important events before the story

2. **Dynamic Persona:**
   - Each character should evolve based on new experiences
   - Changes must be consistent with the original character

3. **Society Simulation:**
   - Characters interact with each other (conversation, cooperation, conflict)
   - Each character has a daily schedule
   - Random events (e.g., wars, disasters) affect society

4. **New Story Generation:**
   - User provides an initial spark (e.g., "What if Harry Potter went to a different school?")
   - System generates a complete story with the same characters and rules
   - Story must be unpredictable yet logical

5. **Counterfactual Mode:**
   - "What if character X made a different decision at event Y?"
   - System simulates alternative story branches

6. **User Interaction:**
   - User can enter the world as a new character
   - User decisions affect the story's progression
   - Main characters react to the user (based on their persona)

7. **Source Fidelity:**
   - Design an evaluator that compares each output with the original book
   - Calculate a fidelity score (0 to 100)
   - If fidelity is below 80%, reject the output

**Expected Output:**
- A simulated world from a famous novel (suggestions: Harry Potter, Lord of the Rings, or Shahnameh)
- At least 5 new stories generated in the same world (with new events)
- Analytical report on character evolution across new stories
- Comparison with traditional methods (story generation with a regular LLM)

---

## Level 3 Topics

### Topic 1: Automated Scientific Paper Writing Agent with Research and Citation

**Core Challenge:**

Writing a scientific paper requires research, literature review, and accurate citation. You need to build an agent that:
- Takes a scientific topic as input
- Finds relevant papers from Google Scholar or arXiv
- Writes a summary of each paper
- Produces a paper draft with standard structure (Introduction, Methodology, Results, Discussion, Conclusion)
- Adds accurate citations (in APA or IEEE format)

**Suggested Capabilities:**

1. **Search Agent:**
   - Uses Serper API (Google Search) or arXiv API to find relevant papers
   - Extracts title, abstract, authors, and publication year
   - Ranks papers based on recency and citation count

2. **Study Agent:**
   - Writes a summary of each paper (200-300 words) emphasizing: research question, method, findings
   - Extracts keywords and important concepts
   - Identifies research gaps

3. **Writer Agent:**
   - Writes the paper based on summaries and standard structure
   - Each section must be supported by sources
   - Scientific language and appropriate tone (formal, precise, objective)

4. **Editor Agent:**
   - Reviews the paper for scientific accuracy, coherence, and grammar
   - Provides improvement suggestions
   - Verifies citations (are all sources present in the references?)

5. **Final Output:**
   - A LaTeX or Word file with the complete paper
   - Reference list
   - A 200-word executive summary

**Expected Output:**
- A scientific paper writing agent with 4 sub-agents (Search, Study, Writer, Editor)
- Generation of 5 papers in different fields (e.g., machine learning, medicine, economics, social sciences)
- Report: In which domains does the system perform better?


