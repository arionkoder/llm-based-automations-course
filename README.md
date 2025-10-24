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


### Running the Examples

The examples are self-contained and can be run independently:

```bash
# Run the LangGraph basics notebooks
jupyter notebook examples/langgraph-basics/hello_world_agent.ipynb
jupyter notebook examples/langgraph-basics/sequential_graph.ipynb
jupyter notebook examples/langgraph-basics/conditional_graph.ipynb
jupyter notebook examples/langgraph-basics/looping_graph.ipynb

# Run the LLM OpenAI API notebook
jupyter notebook examples/llm-openai-api/basic_bot_no_memory.ipynb

# Run the LLM Local notebook (requires Ollama setup)
jupyter notebook examples/llm-local/basic_bot_no_memory.ipynb

# Run the LLM-Based Workflows notebook (requires OpenAI API key)
jupyter notebook examples/llm-based-workflows/invoice_processor.ipynb
```

---

## 📖 Example Overview

| Example | Description | Difficulty | Duration |
|---------|-------------|------------|----------|
| **[LangGraph Basics](./examples/langgraph-basics/)** | Introduction to LangGraph with foundational examples | 🟢 Beginner | 45 min |
| **[LLM OpenAI API](./examples/llm-openai-api/)** | Integration with OpenAI's language models | 🟡 Intermediate | 30 min |
| **[LLM Local](./examples/llm-local/)** | Running local language models with Ollama | 🟡 Intermediate | 30 min |
| **[LLM-Based Workflows](./examples/llm-based-workflows/)** | Real-world document processing with LangGraph and LLMs | 🔴 Advanced | 60 min |

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

**Example 3: Conditional Graph**
- **File**: `conditional_graph.ipynb`
- **Description**: Discover how to create conditional branching logic in LangGraph with decision-making nodes that route execution based on state conditions.
- **Key Concepts**: Conditional edges, routing logic, branching workflows, decision nodes, business logic modeling
- **Prerequisites**: Sequential Graph example

**Example 4: Looping Graph**
- **File**: `looping_graph.ipynb`
- **Description**: Learn how to implement loops in LangGraph, allowing nodes to repeat until specific conditions are met. Perfect for iterative processes and retry mechanisms.
- **Key Concepts**: Looping edges, iterative workflows, conditional loops, retry patterns, state persistence across iterations
- **Prerequisites**: Conditional Graph example

#### 🟡 [LLM OpenAI API](./examples/llm-openai-api/)

**Example 1: Basic Bot (No Memory)**
- **File**: `basic_bot_no_memory.ipynb`
- **Description**: Your first real AI agent! Learn how to integrate OpenAI's language models with LangGraph to create a conversational agent.
- **Key Concepts**: LLM integration, OpenAI API, ChatOpenAI, message handling, environment setup, API key management
- **Prerequisites**: LangGraph Basics examples

#### 🟡 [LLM Local](./examples/llm-local/)

**Example 1: Basic Bot (No Memory) - Local**
- **File**: `basic_bot_no_memory.ipynb`
- **Description**: Run AI agents locally! Learn how to integrate local language models using Ollama with LangGraph to create a conversational agent that runs on your own hardware.
- **Key Concepts**: Local LLM integration, Ollama setup, ChatOpenAI with local endpoints, GPU utilization, cost reduction, offline AI capabilities
- **Prerequisites**: LangGraph Basics examples, Ollama installation

#### 🔴 [LLM-Based Workflows](./examples/llm-based-workflows/)

**Example 1: Invoice Processing Pipeline**
- **File**: `invoice_processor.ipynb`
- **Description**: Build a complete document processing workflow! Learn how to create an automated system that extracts data from PDF invoices using LLMs and LangGraph orchestration. This real-world example demonstrates advanced workflow patterns for business automation.
- **Key Concepts**: PDF text extraction, LLM-based data parsing, structured data extraction, Pydantic models, batch processing, document automation, business workflow orchestration
- **Prerequisites**: LangGraph Basics examples, OpenAI API key, PDF processing libraries
- **Sample Data**: Includes 10 sample PDF invoices and CSV output format

---

## 🛠️ Dependencies

This course uses the following main libraries:

- **LangGraph** (0.6.10): Core framework for building LLM applications
- **LangChain Core** (1.0.0): Essential components for LLM workflows
- **LangChain OpenAI** (1.0.0): OpenAI integration for LangChain
- **Pydantic** (2.12.2): Data validation and settings management
- **PDF Plumber** (0.11.7): PDF text extraction and processing
- **Python-dotenv** (1.1.1): Environment variable management
- **Jupyter**: Interactive notebook environment

For a complete list of dependencies, see [requirements.txt](./requirements.txt).

---

## 📚 Learning Path

We recommend following this learning path:

1. **Start Here**: [LangGraph Basics - Hello World](./examples/langgraph-basics/hello_world_agent.ipynb) - Get familiar with the basics of LangGraph
2. **Next Step**: [LangGraph Basics - Sequential Graph](./examples/langgraph-basics/sequential_graph.ipynb) - Learn about sequential workflows and state management
3. **Advanced**: [LangGraph Basics - Conditional Graph](./examples/langgraph-basics/conditional_graph.ipynb) - Master conditional branching and decision-making logic
4. **Loops**: [LangGraph Basics - Looping Graph](./examples/langgraph-basics/looping_graph.ipynb) - Understand iterative processes and retry mechanisms
5. **AI Integration**: [LLM OpenAI API - Basic Bot](./examples/llm-openai-api/basic_bot_no_memory.ipynb) - Create your first AI-powered agent with OpenAI
6. **Local AI**: [LLM Local - Basic Bot](./examples/llm-local/basic_bot_no_memory.ipynb) - Run AI agents locally with Ollama
7. **Real-World Application**: [LLM-Based Workflows - Invoice Processing](./examples/llm-based-workflows/invoice_processor.ipynb) - Build a complete document processing pipeline
8. **Experiment**: Modify the examples, add your own features, and build something unique!

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