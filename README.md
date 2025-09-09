# ChurnGuardBank-AI 🏦🤖

> **Intelligent Banking Customer Engagement System**  
> Multi-agent AI orchestration for churn prevention and cross-selling optimization

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![LangGraph](https://img.shields.io/badge/LangGraph-Latest-green.svg)](https://github.com/langchain-ai/langgraph)
[![FastAPI](https://img.shields.io/badge/FastAPI-Latest-red.svg)](https://fastapi.tiangolo.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🎯 **Project Overview**

ChurnGuardBank-AI is an intelligent customer engagement system that combines machine learning with multi-agent conversational AI to reduce customer churn and optimize cross-selling opportunities in banking environments.

### **Key Features**
- 🤖 Multi-agent orchestration with LangGraph
- 📊 Real-time churn prediction and analysis
- 💬 Intelligent customer conversation routing
- 📈 Automated cross-selling recommendations
- 🌐 Multi-channel customer support (Web, API)

---

## 🚀 **Project Phases**

### **Phase 1: Data Exploration & ML Foundation**
- [ ] Exploratory Data Analysis (EDA) in Jupyter Notebook
- [ ] Churn prediction model development
- [ ] Feature engineering and model validation
- [ ] Performance metrics and insights generation

### **Phase 2: External Customer Agent**
- [ ] Customer-facing conversational agent
- [ ] Lead qualification and onboarding
- [ ] Product recommendation engine
- [ ] Churn intervention strategies

### **Phase 3: Internal Analytics Agent**
- [ ] Employee-facing analytics agent
- [ ] Custom metrics and reporting
- [ ] Business intelligence queries
- [ ] Dashboard data integration

### **Phase 4: API & Integration Layer**
- [ ] RESTful API with FastAPI
- [ ] CRUD operations for customer management
- [ ] Agent endpoint integration
- [ ] Authentication and security

---

## 🏗️ **Project Architecture**

```
ChurnGuardBank-AI/
├── 📁 config/                    # Configuration & environment
├── 📁 data/                      
│   ├── exploration/              # Jupyter notebooks for EDA
│   ├── raw/                      # Original datasets
│   └── processed/                # Cleaned data
├── 📁 src/
│   ├── 📁 core/                  # Controllers of services
│   ├── 📁 models/                # Shared schemas and models
│   ├── 📁 agents/                # LangGraph agents
│   │   ├── orchestrator/         # Main routing agent
│   │   ├── retention_agent/      # Churn prevention
│   │   ├── recommendation_agent/ # Cross-selling
│   │   └── analytics_agent/      # Internal metrics
│   ├── 📁 services/              # Business logic layer
│   ├── 📁 tools/                 # Agent tools and utilities
│   └── 📁 api/                   # FastAPI routers
├── 📁 tests/                     # Test suites
├── 📁 docker/                    # Container configurations
├── main.py                       # FastAPI application entry
└── requirements.txt              # Dependencies
```

---

## 🛠️ **Technology Stack**

| Component | Technology | Purpose |
|-----------|------------|---------|
| **AI Orchestration** | LangGraph | Multi-agent conversation flow |
| **ML Framework** | scikit-learn | Churn prediction models |
| **API Framework** | FastAPI | High-performance async API |
| **Database** | SQLite | Local data storage |
| **Data Analysis** | Jupyter, Pandas | EDA and experimentation |
| **Language Model** | OpenAI/Local LLM | Natural language processing |

---

## 📋 **Development Roadmap**

### **🔄 Current Sprint**
- [x] Project setup and architecture design
- [x] Dataset integration and initial exploration
- [ ] State schema definition for agent communication
- [ ] Orchestrator agent with hybrid intent detection

### **📅 Upcoming Milestones**

**Week 1-2: Foundation**
- Complete EDA and feature engineering
- Implement basic agent structure
- Setup database and data models

**Week 3-4: Agent Development**
- Multi-agent orchestration system
- Customer interaction flows
- Intent classification and routing

**Week 5-6: API & Integration**
- FastAPI implementation
- CRUD operations
- Agent endpoint integration

**Week 7-8: Testing & Deployment**
- Unit and integration testing
- Docker containerization
- Documentation and demos

---

## 🚦 **Getting Started**

### **Prerequisites**
```bash
Python 3.9+
Git
```

### **Installation**
```bash
# Clone the repository
git clone https://github.com/[username]/ChurnGuardBank-AI.git
cd ChurnGuardBank-AI

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### **Quick Start**
```bash
# Start the FastAPI server
python main.py

# Access API documentation
# http://localhost:8000/docs
```

---

## 📊 **Project Status**

![Project Progress](https://progress-bar.dev/15/?title=Overall%20Progress)

- **Phase 1**: ![Phase 1](https://progress-bar.dev/60/?title=Data%20Exploration)
- **Phase 2**: ![Phase 2](https://progress-bar.dev/0/?title=Customer%20Agent)
- **Phase 3**: ![Phase 3](https://progress-bar.dev/0/?title=Analytics%20Agent)
- **Phase 4**: ![Phase 4](https://progress-bar.dev/0/?title=API%20Layer)

---

## 🤝 **Contributing**

This is a portfolio project showcasing AI/ML engineering capabilities. Feedback and suggestions are welcome!

---

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 **Contact**

**Ivan P.** - Data Scientist & AI Engineer  
📧 [cparraq.98@gmail.com]  
💼 [LinkedIn](https://www.linkedin.com/in/ivan-camilo-p-75a73917b/)

---

*Built with ❤️ and ☕ using Python, LangGraph, and FastAPI*

---

## 📖 **Versión en Español**

Para la documentación en español, consulta [README-ES.md](README-ES.md)

---