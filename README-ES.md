# ChurnGuardBank-AI 🏦🤖

> **Sistema Inteligente de Engagement Bancario**  
> Orquestación multi-agente con IA para prevención de churn y optimización de ventas cruzadas

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://python.org)
[![LangGraph](https://img.shields.io/badge/LangGraph-Latest-green.svg)](https://github.com/langchain-ai/langgraph)
[![FastAPI](https://img.shields.io/badge/FastAPI-Latest-red.svg)](https://fastapi.tiangolo.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🎯 **Descripción del Proyecto**

ChurnGuardBank-AI es un sistema inteligente de engagement de clientes que combina machine learning con IA conversacional multi-agente para reducir la fuga de clientes y optimizar las oportunidades de ventas cruzadas en entornos bancarios.

### **Características Principales**
- 🤖 Orquestación multi-agente con LangGraph
- 📊 Predicción y análisis de churn en tiempo real
- 💬 Enrutamiento inteligente de conversaciones con clientes
- 📈 Recomendaciones automatizadas de ventas cruzadas
- 🌐 Soporte multicanal (Web, API)

---

## 🚀 **Fases del Proyecto**

### **Fase 1: Exploración de Datos y Fundación ML**
- [ ] Análisis Exploratorio de Datos (EDA) en Jupyter Notebook
- [ ] Desarrollo de modelo de predicción de churn
- [ ] Ingeniería de características y validación del modelo
- [ ] Métricas de rendimiento y generación de insights

### **Fase 2: Agente de Cliente Externo**
- [ ] Agente conversacional para clientes
- [ ] Calificación de leads y onboarding
- [ ] Motor de recomendaciones de productos
- [ ] Estrategias de intervención de churn

### **Fase 3: Agente de Analytics Interno**
- [ ] Agente de analytics para empleados
- [ ] Métricas personalizadas y reportes
- [ ] Consultas de inteligencia de negocio
- [ ] Integración con dashboards

### **Fase 4: API y Capa de Integración**
- [ ] API RESTful con FastAPI
- [ ] Operaciones CRUD para gestión de clientes
- [ ] Integración de endpoints de agentes
- [ ] Autenticación y seguridad

---

## 🏗️ **Arquitectura del Proyecto**

```
ChurnGuardBank-AI/
├── 📁 config/                    # Configuración y environment
├── 📁 data/                      
│   ├── exploration/              # Notebooks de Jupyter para EDA
│   ├── raw/                      # Datasets originales
│   └── processed/                # Datos procesados
├── 📁 src/
│   ├── 📁 core/                  # Controladores de servicios
│   ├── 📁 models/                # Esquemas y modelos compartidos
│   ├── 📁 agents/                # Agentes LangGraph
│   │   ├── orchestrator/         # Agente principal de routing
│   │   ├── retention_agent/      # Prevención de churn
│   │   ├── recommendation_agent/ # Ventas cruzadas
│   │   └── analytics_agent/      # Métricas internas
│   ├── 📁 services/              # Capa de lógica de negocio
│   ├── 📁 tools/                 # Tools y utilidades para agentes
│   └── 📁 api/                   # Routers de FastAPI
├── 📁 tests/                     # Suites de pruebas
├── 📁 docker/                    # Configuraciones de contenedores
├── main.py                       # Punto de entrada de FastAPI
└── requirements.txt              # Dependencias
```

---

## 🛠️ **Stack Tecnológico**

| Componente | Tecnología | Propósito |
|-----------|------------|-----------|
| **Orquestación IA** | LangGraph | Flujo conversacional multi-agente |
| **Framework ML** | scikit-learn | Modelos de predicción de churn |
| **Framework API** | FastAPI | API asíncrona de alto rendimiento |
| **Base de Datos** | SQLite | Almacenamiento local de datos |
| **Análisis de Datos** | Jupyter, Pandas | EDA y experimentación |
| **Modelo de Lenguaje** | OpenAI/LLM Local | Procesamiento de lenguaje natural |

---

## 📋 **Hoja de Ruta de Desarrollo**

### **🔄 Sprint Actual**
- [x] Configuración del proyecto y diseño de arquitectura
- [x] Integración de dataset y exploración inicial
- [ ] Definición de esquema de estado para comunicación entre agentes
- [ ] Agente orquestador con detección híbrida de intención

### **📅 Próximos Hitos**

**Semana 1-2: Fundación**
- Completar EDA e ingeniería de características
- Implementar estructura básica de agentes
- Configurar base de datos y modelos de datos

**Semana 3-4: Desarrollo de Agentes**
- Sistema de orquestación multi-agente
- Flujos de interacción con clientes
- Clasificación de intención y enrutamiento

**Semana 5-6: API e Integración**
- Implementación de FastAPI
- Operaciones CRUD
- Integración de endpoints de agentes

**Semana 7-8: Pruebas y Despliegue**
- Pruebas unitarias e de integración
- Contenerización con Docker
- Documentación y demos

---

## 🚦 **Primeros Pasos**

### **Prerrequisitos**
```bash
Python 3.9+
Git
```

### **Instalación**
```bash
# Clonar el repositorio
git clone https://github.com/[username]/ChurnGuardBank-AI.git
cd ChurnGuardBank-AI

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt
```

### **Inicio Rápido**
```bash
# Iniciar servidor FastAPI
python main.py

# Acceder a documentación de API
# http://localhost:8000/docs
```

---

## 📊 **Estado del Proyecto**

![Progreso del Proyecto](https://progress-bar.dev/15/?title=Progreso%20General)

- **Fase 1**: ![Fase 1](https://progress-bar.dev/60/?title=Exploración%20de%20Datos)
- **Fase 2**: ![Fase 2](https://progress-bar.dev/0/?title=Agente%20Cliente)
- **Fase 3**: ![Fase 3](https://progress-bar.dev/0/?title=Agente%20Analytics)
- **Fase 4**: ![Fase 4](https://progress-bar.dev/0/?title=Capa%20API)

---

## 🎓 **Objetivos de Aprendizaje**

Este proyecto tiene como objetivo demostrar competencias en:

- **Arquitectura de Sistemas IA**: Diseño de sistemas multi-agente escalables
- **MLOps**: Integración de modelos ML en aplicaciones de producción
- **Ingeniería de Software**: Principios SOLID, patrones de diseño, código limpio
- **APIs de Producción**: FastAPI, documentación automática, manejo de errores
- **Ciencia de Datos**: EDA, ingeniería de características, validación de modelos

---

## 🤝 **Contribuciones**

Este es un proyecto de portafolio que demuestra capacidades de ingeniería IA/ML. ¡Feedback y sugerencias son bienvenidos!

---

## 📄 **Licencia**

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

---

## 📞 **Contacto**

**[Tu Nombre]** - Data Scientist & AI Engineer  
📧 [cparraq.98@gmail.com]  
💼 ![Perfil LinkedIn](https://www.linkedin.com/in/ivan-camilo-p-75a73917b/)

---

*Construido con ❤️ y ☕ usando Python, LangGraph, y FastAPI*

---

## 📖 **English Version**

For English documentation, see [README.md](README.md)

---