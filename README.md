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


### Running the Example

The example is self-contained and can be run independently:

```bash
# Run the Jupyter notebooks
jupyter notebook examples/langgraph-basics/hello_world_agent.ipynb
jupyter notebook examples/langgraph-basics/sequential_graph.ipynb
```

---

## 📖 Example Overview

| Example | Description | Difficulty | Duration |
|---------|-------------|------------|----------|
| **[LangGraph Basics](./examples/langgraph-basics/)** | Introduction to LangGraph with foundational examples | 🟢 Beginner | 30 min |

### 📁 Example Details

#### 🟢 [LangGraph Basics](./examples/langgraph-basics/)

**Example 1: Hello World Agent**
- **File**: `hello_world_agent.ipynb`
- **Description**: Your first steps with LangGraph! Learn how to create a simple agent that processes messages and maintains state.
- **Key Concepts**: StateGraph, TypedDict, basic agent architecture
- **Prerequisites**: None

**Example 2: Sequential Graph**
- **File**: `sequential_graph.ipynb`
- **Description**: Learn how to build sequential pipelines with multiple connected nodes that process data step-by-step.
- **Key Concepts**: Sequential workflows, state management, explicit edges, streaming execution
- **Prerequisites**: Hello World Agent example

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

We recommend following this learning path:

1. **Start Here**: [LangGraph Basics - Hello World](./examples/langgraph-basics/hello_world_agent.ipynb) - Get familiar with the basics of LangGraph
2. **Next Step**: [LangGraph Basics - Sequential Graph](./examples/langgraph-basics/sequential_graph.ipynb) - Learn about sequential workflows and state management
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