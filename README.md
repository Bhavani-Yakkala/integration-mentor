# 🚀 Integration Mentor

> AI-powered enterprise integration architect built with Microsoft Foundry.

Integration Mentor is an AI-powered enterprise integration assistant designed to help developers, architects, and integration consultants transform integration requirements into architecture designs, implementation guidance, and technical documentation.


## 🎯 Problem Statement

Enterprise integration projects often require expertise across APIs, middleware, SAP CPI, messaging systems, security, and integration patterns. Designing the right solution can be time-consuming and complex, often requiring significant effort to research best practices and translate requirements into technical solutions.


## 💡 Solution

Integration Mentor acts as a specialized enterprise integration architect that helps users:

* Understand integration concepts
* Design integration architectures
* Explore SAP CPI scenarios
* Recommend integration patterns
* Generate implementation guidance
* Create technical documentation

The goal is to simplify integration design and help users move from requirements to solution faster.


## ✨ Key Features

### Integration Knowledge Assistant

Provides guidance on APIs, SAP CPI, middleware, messaging systems, and event-driven architecture.

### Architecture Design Support

Generates integration architectures and solution recommendations based on business requirements.

### SAP CPI Guidance

Assists with SAP CPI concepts, integration flows, adapters, connectivity options, and implementation considerations.

### API & Middleware Advisory

Provides recommendations for API-led connectivity, middleware selection, integration patterns, and security approaches.

### Documentation Generation

Creates HLDs, LLDs, technical design documents, architecture documents, and integration specifications.

### Conversational Experience

Maintains context to support multi-step integration discussions and solution design.


## 🏗 Solution Architecture

```text
User
  │
  ▼
Flask Web Application
  │
  ▼
Microsoft Foundry Agent
  │
  ▼
Integration Mentor
  │
  ├── Integration Knowledge
  ├── Architecture Design
  ├── SAP CPI Guidance
  ├── Implementation Support
  └── Documentation Generation
```


## 🛠 Technology Stack

### AI Platform

* Microsoft Foundry
* Azure AI Agent Service

### Backend

* Python
* Flask

### Frontend

* HTML5
* CSS3
* JavaScript

### Authentication

* Azure Identity
* Microsoft Entra ID

### Libraries & SDKs

* OpenAI Python SDK
* Azure Identity SDK
* python-dotenv
* Markdown
* Bleach


## 📦 Prerequisites

Before running the project, ensure you have:

* Python 3.10+
* Azure Account
* Microsoft Foundry Project
* Published Integration Mentor Agent
* Git


## ⚙ Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd integration-mentor
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Virtual Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / Mac**

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```


## 🔐 Configuration

Create a `.env` file in the project root:

```env
AGENT_ENDPOINT=<your-foundry-agent-endpoint>
```


## ▶ Running the Application

Start the application:

```bash
python app.py
```

Open your browser:

```text
http://localhost:8000
```


## 📂 Project Structure

```text
integration-mentor/
│
├── app.py
├── agent_client.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    └── index.html
```


## 🎥 Demo Video

[Watch Demo Video](https://www.loom.com/share/54ce04f3e8b146cab9bdeaa7379d09b4)


## 🎯 Sample Use Cases
- Design a Salesforce → SAP S/4HANA integration
- Generate a High-Level Design (HLD) document
- Recommend integration patterns for enterprise systems
- Explore SAP CPI implementation approaches
- Design event-driven architectures using messaging systems
- Generate technical documentation for integration projects


## 🚀 Future Enhancements

* Architecture diagram generation
* SAP CPI iFlow recommendations
* PDF export for generated documents
* Integration pattern comparison engine
* Enterprise knowledge base integration
* Multi-agent collaboration workflows

## 🏆 Built For

**Microsoft Agents League Hackathon 2026**

Integration Mentor demonstrates how Microsoft Foundry can be used to build specialized AI agents that provide architecture guidance, implementation support, and technical documentation for enterprise integration scenarios.


## 📄 License

This project is licensed under the MIT License.
