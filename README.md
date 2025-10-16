# 🤖 LLM-Based Automations Course

<div align="center">
  <img src="./ak-logo.png" alt="Arionkoder Logo" width="200"/>
  
  **Building Intelligent Automations with LangGraph and Large Language Models**
  
  [![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://python.org)
  [![LangGraph](https://img.shields.io/badge/LangGraph-0.6.10-green.svg)](https://langchain-ai.github.io/langgraph/)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
</div>

---

## 📚 About This Course

Welcome to the **LLM-Based Automations Course**! This quick tutorial will guide you through building automations for different types of business challenges using Large Language Models (LLMs) and LangGraph.

### What You'll Learn

- 🎯 **LangGraph Fundamentals**: Understanding state graphs, nodes, and workflows
- 🔄 **Agent Architecture**: Building intelligent agents that can reason and act
- 🛠️ **Local LLM Integration**: Working with local language models
- 🌐 **API Integration**: Connecting to external LLM services
- 📊 **State Management**: Handling state transitions in your automations

---

## 👥 Authors

* [José Ignacio Orlando, PhD](https://www.linkedin.com/in/jos%C3%A9-ignacio-orlando-560b8040/?originalSubdomain=ar) - Director of R&D at Arionkoder, Associate Researcher at CONICET
* [Damián Calderón](https://www.linkedin.com/in/damiancalderon/) - AI Product Manager at Arionkoder


---

## 🚀 Quick Start

### Prerequisites

- Python 3.10 or higher
- pip (Python package manager)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/arionkoder/llm-based-automations-course.git
   cd llm-based-automations-course
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables** (if needed)
   ```bash
   cp examples/llm-openai-api/.env_example .env
   # Edit .env with your API keys
   ```

### Running the Examples

Each example is self-contained and can be run independently:

```bash
# For Jupyter notebook examples
jupyter notebook examples/langgraph-hello-world/hello_world_agent.ipynb

# For Python script examples
python examples/example_name/script.py
```

---

## 📖 Table of Contents

| Example | Description | Difficulty | Duration |
|---------|-------------|------------|----------|
| **[LangGraph Hello World](./examples/langgraph-hello-world/)** | Introduction to LangGraph with a simple agent | 🟢 Beginner | 15 min |
| **[Local LLM Integration](./examples/llm-local/)** | Working with local language models | 🟡 Intermediate | 30 min |
| **[OpenAI API Integration](./examples/llm-openai-api/)** | Connecting to external LLM services | 🟡 Intermediate | 25 min |

### 📁 Example Details

#### 🟢 [LangGraph Hello World](./examples/langgraph-hello-world/)
- **File**: `hello_world_agent.ipynb`
- **Description**: Your first steps with LangGraph! Learn how to create a simple agent that processes messages and maintains state.
- **Key Concepts**: StateGraph, TypedDict, basic agent architecture
- **Prerequisites**: None

#### 🟡 [Local LLM Integration](./examples/llm-local/)
- **Description**: Explore how to run language models locally on your machine for privacy and cost efficiency.
- **Key Concepts**: Local model setup, resource management, offline processing
- **Prerequisites**: Basic understanding of LangGraph

#### 🟡 [OpenAI API Integration](./examples/llm-openai-api/)
- **Description**: Learn to integrate with external LLM services like OpenAI's API for powerful cloud-based processing.
- **Key Concepts**: API integration, authentication, error handling
- **Prerequisites**: OpenAI API key, basic understanding of LangGraph

---

## 🛠️ Dependencies

This course uses the following main libraries:

- **LangGraph** (0.6.10): Core framework for building LLM applications
- **LangChain Core** (0.3.79): Essential components for LLM workflows
- **Pydantic** (2.12.2): Data validation and settings management
- **Jupyter**: Interactive notebook environment

For a complete list of dependencies, see [requirements.txt](./requirements.txt).

---

## 📚 Learning Path

We recommend following the examples in this order:

1. **Start Here**: [LangGraph Hello World](./examples/langgraph-hello-world/) - Get familiar with the basics
2. **Choose Your Path**: 
   - [Local LLM](./examples/llm-local/) - If you prefer privacy and offline processing
   - [OpenAI API](./examples/llm-openai-api/) - If you want powerful cloud-based models
3. **Experiment**: Modify the examples, add your own features, and build something unique!

---

## 🤝 Contributing

We welcome contributions! If you find a bug or have an idea for improvement:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact & Support

<div align="center">

### 🏢 **Arionkoder**
*Co-crafting transformational AI solutions*

🌐 **Website**: [arionkoder.com](https://arionkoder.com)  
📧 **Email**: hello@arionkoder.com  
💼 **LinkedIn**: [Arionkoder](https://linkedin.com/company/arionkoder)

---

### 👨‍🏫 **Course Instructors**

**José Ignacio Orlando**  
📧 ignacioo@arionkoder.com  
💼 [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-ignacio-orlando-560b8040/?originalSubdomain=ar)

**Damián Calderón**  
📧 damian.calderon@arionkoder.com  
💼 [LinkedIn](https://www.linkedin.com/in/damiancalderon/)


---

*Have questions or feedback? Feel free to add issues to our repository! 🚀*

</div>