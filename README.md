<div align="center">

# ◈ GenActa

### `From Generation to Action.`

**A living atlas of Generative AI, Large Language Models, RAG, AI Agents, Agentic Systems, Multi-Agent Intelligence, and Production AI Engineering.**

<br>

![Generative AI](https://img.shields.io/badge/Generative_AI-111111?style=for-the-badge\&logo=openai\&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-5B21B6?style=for-the-badge\&logo=probot\&logoColor=white)
![Python](https://img.shields.io/badge/Python-AI_Engineering-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Learning](https://img.shields.io/badge/Status-Learning_%E2%86%92_Building-00A67E?style=for-the-badge)

<br>

```text
                         ┌───────────────────┐
                         │       GOAL        │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │      REASON       │
                         └─────────┬─────────┘
                                   │
                  ┌────────────────┴────────────────┐
                  │                                 │
                  ▼                                 ▼
        ┌───────────────────┐             ┌───────────────────┐
        │     GENERATE      │             │       PLAN        │
        │                   │             │                   │
        │ Text • Code       │             │ Decide • Adapt    │
        │ Image • Audio     │             │ Decompose • Route │
        └─────────┬─────────┘             └─────────┬─────────┘
                  │                                 │
                  └────────────────┬────────────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │       ACT         │
                         │                   │
                         │ Tools • APIs      │
                         │ Search • Systems  │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │      OBSERVE      │
                         └─────────┬─────────┘
                                   │
                                   └──────────────↺
```

### `GENERATE → REASON → PLAN → ACT → OBSERVE → ADAPT`

<br>

> **Generative AI taught machines to create.**
> **Agentic AI gives them the machinery to pursue goals.**

<br>

`LLMs` · `Transformers` · `RAG` · `Agents` · `Tools` · `Memory` · `MCP` · `Multi-Agent Systems`

</div>

---

# 1. 🧬 Welcome to GenActa

**GenActa** is my evolving AI engineering knowledge base for studying two closely connected frontiers of modern Artificial Intelligence:

### ✦ Generative AI

Systems capable of producing new content — text, code, images, audio, video, and multimodal outputs.

### ✦ Agentic AI

Systems designed to reason about goals, formulate plans, use tools, interact with environments, maintain context, and execute multi-step workflows with varying degrees of autonomy.

GenActa explores the progression from:

```text
MODEL
  │
  ▼
GENERATION
  │
  ▼
RETRIEVAL
  │
  ▼
REASONING
  │
  ▼
TOOLS
  │
  ▼
MEMORY
  │
  ▼
AGENTS
  │
  ▼
MULTI-AGENT SYSTEMS
  │
  ▼
AGENTIC APPLICATIONS
```

This repository is not intended to become a collection of copied definitions.

The objective is to develop a working understanding of:

* 🧠 how modern AI models work
* ✨ how machines generate content
* 🔤 how Large Language Models process language
* 🎯 how prompting influences model behaviour
* 📚 how RAG connects models with external knowledge
* 🧩 how embeddings and vector databases work
* 🛠️ how models interact with tools and APIs
* 🧠 how agents use memory and context
* 🗺️ how agents plan multi-step tasks
* 🤖 how autonomous AI agents operate
* 🤝 how multiple agents collaborate
* 🔌 how protocols such as MCP connect AI with external systems
* 🔐 how agentic systems are secured
* 📊 how AI systems are evaluated and observed
* 🚀 how AI applications move from experiments to production

The learning philosophy behind GenActa is:

> **Understand the model. Build the system. Give it tools. Observe its decisions. Engineer its behaviour.**

---

# 2. 🧩 Modules

> **Click any module to expand the learning map.**

---

## ✨ PART I — GENERATIVE AI

<details>
<summary><b>🧠 Module 01 — AI & Generative AI Foundations</b></summary>

<br>

### Topics

* Artificial Intelligence Fundamentals
* Machine Learning Fundamentals
* Deep Learning Fundamentals
* Introduction to Generative AI
* Generative vs Discriminative Models
* Neural Networks
* Representation Learning
* Probability & Statistical Foundations
* Latent Representations
* AI Model Training
* Inference
* AI Model Lifecycle

### Key Questions

* What makes a model generative?
* How does Generative AI differ from traditional predictive AI?
* How do machines learn representations from data?
* What happens during training?
* What happens during inference?

### Mental Model

```text
DATA
 │
 ▼
LEARNING
 │
 ▼
REPRESENTATION
 │
 ▼
MODEL
 │
 ▼
GENERATION
```

📁 Suggested directory:

```text
01-genai-foundations/
```

</details>

<details>
<summary><b>🧠 Module 02 — Neural Networks & Deep Learning</b></summary>

<br>

### Topics

* Artificial Neural Networks
* Perceptrons
* Activation Functions
* Feedforward Networks
* Backpropagation
* Loss Functions
* Gradient Descent
* RNNs
* LSTMs
* GRUs
* Deep Learning Architectures
* Training & Optimization

### Evolution

```text
Perceptron
    │
    ▼
Neural Network
    │
    ▼
Deep Neural Network
    │
    ├── CNN
    ├── RNN
    ├── LSTM / GRU
    │
    ▼
Transformer
```

📁 Suggested directory:

```text
02-deep-learning/
```

</details>

<details>
<summary><b>🔤 Module 03 — NLP Foundations</b></summary>

<br>

### Topics

* Natural Language Processing
* Text Preprocessing
* Tokenization
* Bag of Words
* TF-IDF
* Word Embeddings
* Word2Vec
* GloVe
* Contextual Embeddings
* Sequence Modelling
* BERT
* GPT
* Hugging Face Models

### Evolution

```text
Words
  │
  ▼
Tokens
  │
  ▼
Embeddings
  │
  ▼
Context
  │
  ▼
Language Representation
```

📁 Suggested directory:

```text
03-nlp-foundations/
```

</details>

<details>
<summary><b>⚡ Module 04 — Transformers & Attention</b></summary>

<br>

### Topics

* Transformer Architecture
* Attention
* Self-Attention
* Query, Key & Value
* Multi-Head Attention
* Positional Encoding
* Encoder Architecture
* Decoder Architecture
* Encoder-Decoder Models
* Causal Attention
* Transformer Training
* Transformer Inference

### Core Idea

```text
Input Tokens
     │
     ▼
Embeddings
     │
     ▼
Self-Attention
     │
     ▼
Feed Forward Network
     │
     ▼
Transformer Layers
     │
     ▼
Output Representation
```

### Key Question

> How can every token dynamically decide which other tokens matter?

📁 Suggested directory:

```text
04-transformers-attention/
```

</details>

<details>
<summary><b>🧠 Module 05 — Large Language Models</b></summary>

<br>

### Topics

* Large Language Models
* GPT-style Models
* BERT
* T5
* Llama
* Mistral
* Gemma
* Tokens & Tokenizers
* Context Windows
* Model Parameters
* Pretraining
* Inference
* Temperature
* Top-k
* Top-p
* Scaling Laws
* Model Capabilities & Limitations

### LLM Pipeline

```text
PROMPT
  │
  ▼
TOKENIZATION
  │
  ▼
TRANSFORMER
  │
  ▼
PROBABILITY DISTRIBUTION
  │
  ▼
NEXT TOKEN
  │
  └──────────────↺
```

📁 Suggested directory:

```text
05-large-language-models/
```

</details>

<details>
<summary><b>🎯 Module 06 — Prompt Engineering</b></summary>

<br>

### Topics

* Prompt Engineering Fundamentals
* System Prompts
* Zero-Shot Prompting
* One-Shot Prompting
* Few-Shot Prompting
* Role Prompting
* Contextual Prompting
* Structured Outputs
* Chain-of-Thought Concepts
* Self-Consistency
* ReAct
* Tree of Thoughts
* Retrieval-Augmented Prompting
* Prompt Templates
* Prompt Guardrails

### Prompt Anatomy

```text
┌─────────────────────┐
│ ROLE                │
├─────────────────────┤
│ CONTEXT             │
├─────────────────────┤
│ TASK                │
├─────────────────────┤
│ CONSTRAINTS         │
├─────────────────────┤
│ OUTPUT FORMAT       │
└─────────────────────┘
          │
          ▼
         LLM
```

📁 Suggested directory:

```text
06-prompt-engineering/
```

</details>

<details>
<summary><b>🎨 Module 07 — Generative Model Architectures</b></summary>

<br>

### Topics

* Autoencoders
* Variational Autoencoders
* Latent Space
* Generative Adversarial Networks
* GAN Architecture
* Generator vs Discriminator
* Diffusion Models
* Denoising
* Stable Diffusion
* Text-to-Image Generation
* Multimodal Generation

### Architecture Families

```text
Generative AI
     │
     ├── Autoregressive Models
     │
     ├── Autoencoders / VAEs
     │
     ├── GANs
     │
     └── Diffusion Models
```

📁 Suggested directory:

```text
07-generative-architectures/
```

</details>

<details>
<summary><b>📚 Module 08 — Embeddings, Vector Search & RAG</b></summary>

<br>

### Topics

* Embeddings
* Semantic Similarity
* Vector Representations
* Vector Search
* Vector Databases
* FAISS
* ChromaDB
* Qdrant
* Pinecone
* Retrieval-Augmented Generation
* Chunking
* Retrieval
* Reranking
* Context Injection
* Hybrid Search
* Multimodal RAG
* RAG Evaluation

### RAG Architecture

```text
                  KNOWLEDGE BASE
                        │
                        ▼
                    DOCUMENTS
                        │
                        ▼
                     CHUNKS
                        │
                        ▼
                   EMBEDDINGS
                        │
                        ▼
                 VECTOR DATABASE
                        │
                        │ Retrieve
                        ▼
USER ──► QUERY ──► RETRIEVER
                        │
                        ▼
                     CONTEXT
                        │
                        ▼
                       LLM
                        │
                        ▼
                     ANSWER
```

📁 Suggested directory:

```text
08-rag-vector-search/
```

</details>

<details>
<summary><b>🔧 Module 09 — Fine-Tuning & Model Adaptation</b></summary>

<br>

### Topics

* Transfer Learning
* Fine-Tuning
* Supervised Fine-Tuning
* Parameter-Efficient Fine-Tuning
* PEFT
* LoRA
* QLoRA
* Quantization
* RLHF
* Preference Optimization
* DPO
* Model Distillation
* Fine-Tuning vs RAG
* Evaluation after Fine-Tuning

### Decision Question

```text
Need external knowledge?
        │
       YES
        │
        ▼
       RAG

Need behavioural specialization?
        │
       YES
        │
        ▼
   FINE-TUNING
```

📁 Suggested directory:

```text
09-fine-tuning/
```

</details>

<details>
<summary><b>🖼️ Module 10 — Multimodal Generative AI</b></summary>

<br>

### Topics

* Multimodal AI
* Vision-Language Models
* Text Generation
* Image Generation
* Audio Generation
* Video Generation
* Image Understanding
* Speech Models
* Multimodal Embeddings
* Multimodal RAG

### Concept

```text
       TEXT ─────┐
                 │
       IMAGE ────┤
                 │
       AUDIO ────┼──► MULTIMODAL MODEL ──► RESPONSE
                 │
       VIDEO ────┤
                 │
       DATA ─────┘
```

📁 Suggested directory:

```text
10-multimodal-ai/
```

</details>

---

## 🤖 PART II — AGENTIC AI

<details>
<summary><b>🤖 Module 11 — Introduction to AI Agents & Agentic AI</b></summary>

<br>

### Topics

* What is an AI Agent?
* What is Agentic AI?
* Traditional AI vs Generative AI vs Agentic AI
* Autonomous Systems
* Goal-Oriented Behaviour
* Environment Interaction
* Perception
* Decision Making
* Action Execution
* Feedback Loops
* Agent Lifecycle

### The Transition

```text
TRADITIONAL AI
Predicts
   │
   ▼
GENERATIVE AI
Creates
   │
   ▼
AI AGENTS
Reason + Use Tools
   │
   ▼
AGENTIC AI
Pursues Goals + Acts
```

### Core Mental Model

```text
GOAL
 │
 ▼
PERCEIVE
 │
 ▼
REASON
 │
 ▼
PLAN
 │
 ▼
ACT
 │
 ▼
OBSERVE
 │
 └────────────► REASON
```

📁 Suggested directory:

```text
11-agentic-ai-foundations/
```

</details>

<details>
<summary><b>🧭 Module 12 — Agent Architecture & Reasoning</b></summary>

<br>

### Topics

* Agent Architecture
* Reasoning Loops
* Planning
* Task Decomposition
* ReAct
* Reflection
* Self-Correction
* Decision Making
* State Management
* Goal Decomposition
* Planning Strategies
* Agent Execution Loops
* Human-in-the-Loop Systems

### Agent Loop

```text
            ┌──────────────┐
            │     GOAL     │
            └──────┬───────┘
                   ▼
            ┌──────────────┐
            │    REASON    │
            └──────┬───────┘
                   ▼
            ┌──────────────┐
            │     PLAN     │
            └──────┬───────┘
                   ▼
            ┌──────────────┐
            │     ACT      │
            └──────┬───────┘
                   ▼
            ┌──────────────┐
            │   OBSERVE    │
            └──────┬───────┘
                   │
                   └──────────↺
```

📁 Suggested directory:

```text
12-agent-architecture/
```

</details>

<details>
<summary><b>🛠️ Module 13 — Tool Use & Function Calling</b></summary>

<br>

### Topics

* Tool Calling
* Function Calling
* API Integration
* Search Tools
* Database Tools
* Code Execution
* External Services
* Tool Selection
* Tool Routing
* Structured Tool Inputs
* Tool Results
* Error Handling
* Tool Permissions

### Mental Model

```text
              ┌─────────┐
              │   LLM   │
              └────┬────┘
                   │
             Select Tool
                   │
       ┌───────────┼───────────┐
       ▼           ▼           ▼
     SEARCH       API       DATABASE
       │           │           │
       └───────────┼───────────┘
                   ▼
                RESULT
                   │
                   ▼
                  LLM
```

### Core Question

> How does an LLM move from **describing an action** to **executing an action through a controlled interface**?

📁 Suggested directory:

```text
13-agent-tools/
```

</details>

<details>
<summary><b>🧠 Module 14 — Memory & Context Engineering</b></summary>

<br>

### Topics

* Agent Memory
* Short-Term Memory
* Long-Term Memory
* Episodic Memory
* Semantic Memory
* Working Memory
* Conversation History
* Context Windows
* Context Engineering
* Memory Retrieval
* Vector-Based Memory
* State Persistence
* Memory Summarization

### Agent Memory Model

```text
                AGENT
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
     WORKING    EPISODIC   SEMANTIC
     MEMORY     MEMORY     MEMORY
        │         │         │
        └─────────┼─────────┘
                  ▼
               CONTEXT
```

📁 Suggested directory:

```text
14-agent-memory/
```

</details>

<details>
<summary><b>📚 Module 15 — Agentic RAG</b></summary>

<br>

### Topics

* Traditional RAG
* Agentic RAG
* Dynamic Retrieval
* Query Planning
* Query Rewriting
* Multi-Step Retrieval
* Retrieval Tools
* Source Selection
* Reranking
* Self-Corrective Retrieval
* Knowledge Agents
* RAG with Agents

### Traditional RAG

```text
Query → Retrieve → Generate
```

### Agentic RAG

```text
                   ┌────────────┐
                   │   QUERY    │
                   └─────┬──────┘
                         ▼
                   ┌────────────┐
                   │   AGENT    │
                   └─────┬──────┘
                         │
                 Decide what is needed
                         │
            ┌────────────┼────────────┐
            ▼            ▼            ▼
         SEARCH      VECTOR DB     DATABASE
            │            │            │
            └────────────┼────────────┘
                         ▼
                      REASON
                         │
                 Enough evidence?
                    /         \
                  NO           YES
                  │             │
                  └──↺          ▼
                             ANSWER
```

📁 Suggested directory:

```text
15-agentic-rag/
```

</details>

<details>
<summary><b>🔌 Module 16 — Model Context Protocol (MCP)</b></summary>

<br>

### Topics

* Model Context Protocol
* MCP Architecture
* MCP Hosts
* MCP Clients
* MCP Servers
* Tools
* Resources
* Prompts
* External Data Sources
* Tool Discovery
* AI-System Integration
* Security Considerations

### Conceptual Architecture

```text
                 AI APPLICATION
                       │
                       ▼
                  MCP CLIENT
                       │
            ┌──────────┼──────────┐
            ▼          ▼          ▼
        MCP SERVER  MCP SERVER  MCP SERVER
            │          │          │
            ▼          ▼          ▼
          FILES      DATABASE     TOOLS
```

### Goal

Understand how AI applications can interact with external capabilities through **standardized interfaces rather than one-off integrations**.

📁 Suggested directory:

```text
16-model-context-protocol/
```

</details>

<details>
<summary><b>🤝 Module 17 — Multi-Agent Systems</b></summary>

<br>

### Topics

* Multi-Agent Systems
* Agent Collaboration
* Agent Delegation
* Agent Roles
* Supervisor Agents
* Worker Agents
* Agent-to-Agent Communication
* Shared Memory
* Task Routing
* Agent Coordination
* Sequential Workflows
* Parallel Workflows
* Hierarchical Agents
* Collaborative Problem Solving

### Multi-Agent Pattern

```text
                       USER GOAL
                           │
                           ▼
                    ┌─────────────┐
                    │ SUPERVISOR  │
                    │    AGENT    │
                    └──────┬──────┘
                           │
              ┌────────────┼────────────┐
              │            │            │
              ▼            ▼            ▼
         RESEARCHER     ANALYST      BUILDER
              │            │            │
              └────────────┼────────────┘
                           ▼
                      SYNTHESIZER
                           │
                           ▼
                        RESULT
```

📁 Suggested directory:

```text
17-multi-agent-systems/
```

</details>

<details>
<summary><b>🕸️ Module 18 — Agent Frameworks & Orchestration</b></summary>

<br>

### Topics

* LangChain
* LangGraph
* LlamaIndex
* CrewAI
* Agent Workflows
* Graph-Based Agents
* Stateful Agents
* Agent Orchestration
* Agent Routing
* Workflow Design
* Custom Tools
* Human Approval Steps

### Framework Thinking

```text
MODEL
  │
  ├── PROMPTS
  │
  ├── MEMORY
  │
  ├── TOOLS
  │
  ├── RETRIEVAL
  │
  └── STATE
        │
        ▼
   ORCHESTRATION
        │
        ▼
      AGENT
```

### Goal

Understand the architectural ideas behind agent frameworks rather than becoming dependent on a single library.

📁 Suggested directory:

```text
18-agent-frameworks/
```

</details>

<details>
<summary><b>⚙️ Module 19 — Agentic Workflows & Automation</b></summary>

<br>

### Topics

* AI Workflow Automation
* Event-Driven Agents
* n8n
* Workflow Orchestration
* Trigger-Based Agents
* Email Agents
* Research Agents
* Data Agents
* Coding Agents
* Document Processing Agents
* Approval Workflows
* Human-in-the-Loop Automation

### Evolution

```text
MANUAL TASK
     │
     ▼
SCRIPT
     │
     ▼
AUTOMATED WORKFLOW
     │
     ▼
LLM WORKFLOW
     │
     ▼
AI AGENT
     │
     ▼
AGENTIC SYSTEM
```

📁 Suggested directory:

```text
19-agentic-automation/
```

</details>

---

## ⚙️ PART III — ENGINEERING INTELLIGENT SYSTEMS

<details>
<summary><b>📏 Module 20 — Evaluation, Observability & Testing</b></summary>

<br>

### Topics

* LLM Evaluation
* Agent Evaluation
* RAG Evaluation
* Retrieval Quality
* Hallucination Evaluation
* Tool-Use Evaluation
* Agent Trajectories
* Prompt Testing
* Regression Testing
* Latency
* Cost
* Reliability
* Tracing
* Logging
* Observability

### Production Question

```text
Did it answer correctly?
        │
Did it retrieve correctly?
        │
Did it choose the correct tool?
        │
Did it follow the intended path?
        │
How long did it take?
        │
How much did it cost?
        │
Can we reproduce the failure?
```

📁 Suggested directory:

```text
20-ai-evaluation-observability/
```

</details>

<details>
<summary><b>🛡️ Module 21 — AI Safety, Security & Responsible AI</b></summary>

<br>

### Topics

* Responsible AI
* AI Bias
* Hallucinations
* Deepfakes
* Prompt Injection
* Indirect Prompt Injection
* Jailbreaking Concepts
* Data Leakage
* Tool Abuse
* Excessive Agency
* Permission Boundaries
* Human Oversight
* AI Guardrails
* Agent Security
* Model Security
* Secure Tool Execution

### Security Boundary

```text
USER
 │
 ▼
INPUT VALIDATION
 │
 ▼
MODEL / AGENT
 │
 ▼
POLICY + PERMISSIONS
 │
 ▼
TOOLS
 │
 ▼
EXTERNAL SYSTEMS
```

### Principle

> An agent should have **only the information, permissions, tools, and autonomy required to complete its task**.

📁 Suggested directory:

```text
21-ai-safety-security/
```

</details>

<details>
<summary><b>🚀 Module 22 — Deployment & Production AI</b></summary>

<br>

### Topics

* AI Application Deployment
* Model Serving
* APIs
* FastAPI
* Streamlit
* Gradio
* Docker
* Kubernetes
* GPU Inference
* vLLM
* Scaling
* Caching
* Rate Limiting
* Monitoring
* Cost Optimization
* Production RAG
* Production Agents

### Evolution

```text
NOTEBOOK
   │
   ▼
PROTOTYPE
   │
   ▼
API
   │
   ▼
CONTAINER
   │
   ▼
DEPLOYMENT
   │
   ▼
OBSERVABILITY
   │
   ▼
SCALING
   │
   ▼
PRODUCTION AI
```

📁 Suggested directory:

```text
22-production-ai/
```

</details>

<details>
<summary><b>🧪 Module 23 — Generative AI Projects</b></summary>

<br>

### Project Ideas

* [ ] AI Text Generator
* [ ] Document Summarizer
* [ ] PDF Question-Answering System
* [ ] Semantic Search Engine
* [ ] RAG Chatbot
* [ ] Multimodal Document Assistant
* [ ] Code Explanation Assistant
* [ ] Research Paper Assistant
* [ ] Knowledge-Base Chatbot
* [ ] Fine-Tuned Domain Assistant
* [ ] Image Generation Application
* [ ] Local LLM Application

### Project Philosophy

```text
CONCEPT
   │
   ▼
PROTOTYPE
   │
   ▼
EVALUATE
   │
   ▼
IMPROVE
   │
   ▼
DEPLOY
```

📁 Suggested directory:

```text
23-generative-ai-projects/
```

</details>

<details>
<summary><b>🤖 Module 24 — Agentic AI Projects</b></summary>

<br>

### Project Ideas

* [ ] Web Research Agent
* [ ] AI Study Agent
* [ ] Autonomous Research Assistant
* [ ] Email Classification Agent
* [ ] Document Analysis Agent
* [ ] SQL Database Agent
* [ ] Coding Agent
* [ ] Agentic RAG Assistant
* [ ] Personal Knowledge Agent
* [ ] Multi-Agent Research Team
* [ ] Supervisor + Worker Agent System
* [ ] AI Workflow Automation System
* [ ] MCP-Powered Agent
* [ ] Human-in-the-Loop Approval Agent

### Agentic Project Pattern

```text
                   USER GOAL
                       │
                       ▼
                    AGENT
                       │
                ┌──────┴──────┐
                │             │
                ▼             ▼
             MEMORY         PLANNER
                              │
                    ┌─────────┼─────────┐
                    ▼         ▼         ▼
                  SEARCH     API      DATABASE
                    │         │         │
                    └─────────┼─────────┘
                              ▼
                           OBSERVE
                              │
                              ▼
                           REASON
                              │
                       Goal complete?
                        /          \
                      NO            YES
                      │              │
                      └──────↺       ▼
                                  RESULT
```

📁 Suggested directory:

```text
24-agentic-ai-projects/
```

</details>

---

# 3. ⚡ The GenActa Spectrum

The central idea behind this repository is that modern AI systems can be understood as a progression of capabilities.

```text
┌──────────────────────────────────────────────────────────────┐
│                     THE GenActa SPECTRUM                     │
└──────────────────────────────────────────────────────────────┘

      PREDICT
         │
         ▼
      GENERATE
         │
         ▼
      RETRIEVE
         │
         ▼
       REASON
         │
         ▼
        PLAN
         │
         ▼
     USE TOOLS
         │
         ▼
        ACT
         │
         ▼
      OBSERVE
         │
         ▼
       ADAPT
         │
         ▼
    COLLABORATE
```

### Generative AI asks:

> **What should I create?**

### Agentic AI adds:

> **What should I do next to accomplish the goal?**

That distinction forms the backbone of GenActa.

---

# 4. 🧠 The Anatomy of an Intelligent Agent

A useful agent is more than an LLM wrapped inside a loop.

```text
                    ┌──────────────────────┐
                    │         GOAL         │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       PLANNING       │
                    └──────────┬───────────┘
                               │
               ┌───────────────┼───────────────┐
               │               │               │
               ▼               ▼               ▼
          ┌─────────┐     ┌─────────┐     ┌─────────┐
          │ MEMORY  │     │   LLM   │     │  STATE  │
          └────┬────┘     └────┬────┘     └────┬────┘
               │               │               │
               └───────────────┼───────────────┘
                               │
                               ▼
                       ┌──────────────┐
                       │ TOOL ROUTER  │
                       └──────┬───────┘
                              │
              ┌───────────────┼───────────────┐
              ▼               ▼               ▼
            SEARCH           APIs          DATABASE
              │               │               │
              └───────────────┼───────────────┘
                              │
                              ▼
                         OBSERVATION
                              │
                              ▼
                           REFLECT
                              │
                              └───────────↺
```

A production-grade agent therefore involves several engineering problems:

* model selection
* prompt design
* context engineering
* memory
* planning
* retrieval
* tool integration
* permissions
* state management
* error recovery
* evaluation
* observability
* security
* human oversight

---

# 5. 🔬 GenActa Labs

Theory becomes useful when the system actually runs.

Each major topic can eventually include experiments following:

```text
LEARN
  │
  ▼
BUILD
  │
  ▼
TEST
  │
  ▼
BREAK
  │
  ▼
OBSERVE
  │
  ▼
DEBUG
  │
  ▼
EVALUATE
  │
  ▼
IMPROVE
```

### 🧪 Lab 01 — Prompt Laboratory

Experiment with:

* zero-shot prompting
* few-shot prompting
* structured outputs
* role prompting
* contextual prompting
* prompt constraints

---

### 🧪 Lab 02 — Build RAG From Scratch

```text
Documents
    │
    ▼
Chunking
    │
    ▼
Embeddings
    │
    ▼
Vector DB
    │
    ▼
Retrieval
    │
    ▼
LLM
```

---

### 🧪 Lab 03 — Give an LLM Tools

```text
User
 │
 ▼
LLM
 │
 ├──── Search
 ├──── Calculator
 ├──── API
 └──── Database
```

Study how the model decides **whether and when to call a tool**.

---

### 🧪 Lab 04 — Build a Stateful Agent

Add:

```text
LLM
 +
TOOLS
 +
MEMORY
 +
STATE
 +
PLANNING
```

---

### 🧪 Lab 05 — Build Agentic RAG

Move beyond:

```text
Retrieve → Generate
```

toward:

```text
Plan
 ↓
Search
 ↓
Evaluate Evidence
 ↓
Search Again
 ↓
Synthesize
```

---

### 🧪 Lab 06 — Build a Multi-Agent System

```text
              SUPERVISOR
             /     |     \
            /      |      \
     RESEARCH   ANALYSIS   WRITER
            \      |      /
             \     |     /
                RESULT
```

---

### 🧪 Lab 07 — Production Agent

Add:

* structured logging
* traces
* retries
* timeouts
* tool permissions
* evaluation
* cost tracking
* failure handling
* human approval
* guardrails

---

# 6. 💡 GenActa Repository Ideas

### 🧠 `Concept in 60 Seconds`

Every important topic gets a compressed explanation.

```text
RAG

What:
Retrieval-Augmented Generation.

Why:
LLMs cannot reliably contain every piece of current
or private knowledge.

How:
Retrieve relevant external information and provide
it to the model as context before generation.

Mental Model:
SEARCH → CONTEXT → GENERATE
```

---

### ⚔️ `AI Battles`

Compare concepts that are frequently confused.

```text
RAG                 ⚔️ Fine-Tuning
AI Agent            ⚔️ Chatbot
Workflow            ⚔️ Agent
Generative AI       ⚔️ Agentic AI
Vector DB           ⚔️ Traditional DB
Embedding           ⚔️ Token
Prompt Engineering  ⚔️ Context Engineering
Tool Calling        ⚔️ MCP
Single Agent        ⚔️ Multi-Agent System
Memory              ⚔️ Context
```

---

### 🔬 `Under the Hood`

Investigate what abstractions hide.

Examples:

* What happens when an LLM receives a prompt?
* How does tokenization actually work?
* How does self-attention connect tokens?
* What happens during vector retrieval?
* How does an agent decide to call a tool?
* How is agent state persisted?
* What happens when an agent's tool fails?
* How do multiple agents exchange information?

---

### 💥 `What Happens If...?`

Failure-oriented learning.

```text
What happens if retrieval returns irrelevant documents?

What happens if the LLM hallucinates a tool argument?

What happens if an agent enters an infinite loop?

What happens if a tool times out?

What happens if memory contains incorrect information?

What happens if retrieved content contains prompt injection?

What happens if two agents disagree?

What happens if the model exceeds its context window?

What happens if an autonomous agent receives excessive permissions?
```

---

### 🩺 `Agent Clinic`

Start with a poorly designed agent:

```text
USER
 │
 ▼
LLM
 │
 ▼
ALL TOOLS + FULL PERMISSIONS
```

Diagnose the problems:

```text
❌ Excessive permissions
❌ No tool boundaries
❌ No validation
❌ No observability
❌ No human approval
❌ No retry policy
❌ No cost controls
❌ No execution limits
```

Then redesign it:

```text
USER
 │
 ▼
VALIDATION
 │
 ▼
AGENT
 │
 ▼
POLICY LAYER
 │
 ▼
TOOL ROUTER
 │
 ├── Read Tool
 ├── Search Tool
 └── Approved Write Tool
        │
        ▼
     OBSERVE
```

---

### 🧠 `Agent Autopsy`

For interesting agent runs, record:

```text
GOAL
 │
 ▼
What did the agent know?
 │
 ▼
What plan did it create?
 │
 ▼
Which tools did it select?
 │
 ▼
What observations did it receive?
 │
 ▼
Where did it make a bad decision?
 │
 ▼
How can the system be improved?
```

This shifts learning from **"the agent worked"** to **"why did the agent behave this way?"**

---

### 📊 `Model / Agent Scorecards`

Evaluate experiments across:

```text
Accuracy
Reliability
Latency
Cost
Retrieval Quality
Tool Selection
Task Completion
Safety
```

---

### 🏆 `GenActa Boss Battles`

Open-ended engineering challenges with no prescribed implementation.

#### Boss Battle — Autonomous Research System

> Build an AI system capable of receiving a research question, planning the investigation, searching multiple sources, extracting evidence, identifying contradictions, and producing a cited report.

Possible architecture:

```text
                    RESEARCH QUESTION
                           │
                           ▼
                     SUPERVISOR
                           │
                 ┌─────────┴─────────┐
                 ▼                   ▼
            PLANNER              RESEARCHER
                                     │
                              ┌──────┴──────┐
                              ▼             ▼
                            WEB          DOCUMENTS
                              │             │
                              └──────┬──────┘
                                     ▼
                                  ANALYST
                                     │
                                     ▼
                                  WRITER
                                     │
                                     ▼
                              FINAL REPORT
```

The objective is not merely to make the architecture run.

The objective is to explain **why every component exists**.

---

# 7. 🗂️ Suggested Repository Architecture

```text
GenActa/
│
├── README.md
│
├── 01-genai-foundations/
├── 02-deep-learning/
├── 03-nlp-foundations/
├── 04-transformers-attention/
├── 05-large-language-models/
├── 06-prompt-engineering/
├── 07-generative-architectures/
├── 08-rag-vector-search/
├── 09-fine-tuning/
├── 10-multimodal-ai/
│
├── 11-agentic-ai-foundations/
├── 12-agent-architecture/
├── 13-agent-tools/
├── 14-agent-memory/
├── 15-agentic-rag/
├── 16-model-context-protocol/
├── 17-multi-agent-systems/
├── 18-agent-frameworks/
├── 19-agentic-automation/
│
├── 20-ai-evaluation-observability/
├── 21-ai-safety-security/
├── 22-production-ai/
├── 23-generative-ai-projects/
├── 24-agentic-ai-projects/
│
├── papers/
├── experiments/
├── diagrams/
├── datasets/
├── notebooks/
├── cheatsheets/
└── resources/
```

---

# 8. 🧭 Learning Philosophy

GenActa follows one rule:

> **Do not stop at "How do I use it?"**

Keep asking:

```text
What is it?
     │
     ▼
Why does it exist?
     │
     ▼
How does it work?
     │
     ▼
What abstraction does it hide?
     │
     ▼
Where does it fail?
     │
     ▼
How do I evaluate it?
     │
     ▼
How do I engineer it reliably?
```

For Generative AI:

```text
Don't only call the model.

Understand the model.
```

For Agentic AI:

```text
Don't only build the agent.

Understand why it acts.
```

---

# 9. 🎯 Learning Roadmap

```text
                     AI FOUNDATIONS
                           │
                           ▼
                    DEEP LEARNING
                           │
                           ▼
                       NLP
                           │
                           ▼
                    TRANSFORMERS
                           │
                           ▼
                         LLMs
                           │
             ┌─────────────┴─────────────┐
             ▼                           ▼
     PROMPT ENGINEERING            EMBEDDINGS
                                         │
                                         ▼
                                        RAG
                                         │
                         ┌───────────────┴───────────────┐
                         ▼                               ▼
                   FINE-TUNING                       TOOLS
                                                         │
                                                         ▼
                                                      AGENTS
                                                         │
                                         ┌───────────────┼───────────────┐
                                         ▼               ▼               ▼
                                      MEMORY          PLANNING           MCP
                                         │               │               │
                                         └───────────────┼───────────────┘
                                                         ▼
                                                  AGENTIC RAG
                                                         │
                                                         ▼
                                                MULTI-AGENT SYSTEMS
                                                         │
                                                         ▼
                                                   EVALUATION
                                                         │
                                                         ▼
                                                     SECURITY
                                                         │
                                                         ▼
                                                   DEPLOYMENT
                                                         │
                                                         ▼
                                                 PRODUCTION AI
```

---

# 10. 📚 Learning References

GenActa documents my own notes, experiments, implementations, diagrams, comparisons, and understanding developed while studying modern AI engineering.

Primary learning references include:

* **GeeksforGeeks — Generative AI Tutorial**
* **GeeksforGeeks — Agentic AI Tutorial**
* Research papers
* Official framework documentation
* Model documentation and technical reports
* AI engineering experiments
* Open-source implementations

> External resources serve as learning references. The purpose of GenActa is to document my own understanding, experiments, implementations, and engineering observations.

---

# 11. ⚠️ Responsible AI Engineering

Powerful AI systems require more than powerful models.

When building Generative and Agentic AI systems:

* Never expose API keys or credentials.
* Treat model output as untrusted input.
* Validate structured model outputs before execution.
* Restrict tool permissions.
* Apply least privilege to agents.
* Treat retrieved external content as potentially hostile.
* Design for prompt-injection risks.
* Add execution limits to autonomous loops.
* Monitor tool calls and agent trajectories.
* Require human approval for consequential actions where appropriate.
* Evaluate hallucinations and retrieval quality.
* Protect private and sensitive data.
* Track latency and model/API cost.
* Design explicit failure and recovery paths.

```text
CAPABILITY
    +
AUTONOMY
    +
TOOLS
    +
PERMISSIONS
    =
RESPONSIBILITY
```

---

# 12. 🤝 Contributions & Discussions

GenActa is primarily a personal AI engineering knowledge base, but corrections, architecture discussions, research suggestions, experiments, and improvements are welcome.

If you find:

* an incorrect technical explanation,
* an outdated AI concept,
* a better architecture,
* an interesting paper,
* an agent failure worth studying,
* a security concern,
* or an experiment worth running,

feel free to open an **Issue** or **Pull Request**.

---

<div align="center">

# ◈ GenActa

### AI evolved from answering:

### `What should I generate?`

### to reasoning about:

### `What should I do next?`

<br>

```text
GENERATE  →  REASON  →  PLAN  →  ACT  →  OBSERVE  →  ADAPT
```

<br>

**Generative AI × Agentic AI × AI Engineering**

<br>

`Transformers` • `LLMs` • `RAG` • `Agents` • `MCP` • `Multi-Agent Systems`

---

### ⭐ Explore. Build. Evaluate. Engineer Intelligence.

**From models that create to systems that act.**

</div>
