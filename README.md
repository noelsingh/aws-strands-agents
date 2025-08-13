# AWS Strands Agents SDK Tutorial

A comprehensive Jupyter notebook tutorial for building production-ready AI agents using AWS Strands Agents SDK.

## 🚀 Overview

This repository contains a hands-on tutorial that demonstrates how to use AWS Strands framework to build AI agents capable of:
- Leveraging multiple AI models (Bedrock, OpenAI, etc.)
- Executing tools and taking actions
- Coordinating multiple agents in workflows
- Providing enterprise-grade observability

## 📚 What You'll Learn

1. **Basic Setup** - Installing and configuring the Strands SDK
2. **Creating Agents** - Building your first AI agent
3. **Observability** - Debug logging and monitoring agent execution
4. **Model Flexibility** - Switching between different AI models
5. **Custom Tools** - Creating and integrating custom tools
6. **Built-in Tools** - Using pre-built tools like calculator and Python REPL
7. **Multi-Agent Systems** - Building graphs for complex agent workflows
8. **Human-in-the-Loop** - Implementing approval workflows for critical actions

## 🛠️ Prerequisites

- Python 3.10+
- AWS Account with Bedrock access
- Basic understanding of AI/ML concepts

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/aws-strands-agents-tutorial.git
cd aws-strands-agents-tutorial

# Install required packages
pip install -U strands-agents strands-agents-tools

# For Jupyter notebook support
pip install jupyter
```

## 🏃 Quick Start

1. Open the notebook:
```bash
jupyter notebook strands.ipynb
```

2. Follow the tutorial step-by-step, starting with basic agent creation and progressing to advanced multi-agent systems.

## 📖 Tutorial Contents

### Part 1: Basic Agent Creation
Learn how to create and interact with a simple agent using default settings.

### Part 2: Debug and Observability
Enable debug logging to understand agent execution flow and decision-making.

### Part 3: Model Configuration
Configure different AI models including Claude 3 Haiku with custom inference parameters.

### Part 4: Custom Tools
Build custom tools that agents can use to perform specific tasks.

### Part 5: Built-in Tools
Leverage pre-built tools for common operations like calculations and code execution.

### Part 6: Multi-Agent Graphs
Create sophisticated workflows with multiple specialized agents working together.

### Part 7: Human-in-the-Loop
Implement approval mechanisms for sensitive operations.

## 🔑 Key Features Demonstrated

- **Model Agnostic**: Switch between AWS Bedrock models seamlessly
- **Tool Integration**: Both custom and built-in tools
- **Production Ready**: Enterprise-grade logging and observability
- **Flexible Orchestration**: Single agents or complex multi-agent graphs
- **Safety First**: Human approval workflows for critical actions

## 📝 Example Use Cases

- **Code Generation Pipeline**: Agents that generate and execute code
- **Data Processing**: Agents with calculator and analytical tools
- **Approval Workflows**: File operations with human confirmation
- **Multi-step Tasks**: Coordinated agent teams for complex workflows

## 🤝 Contributing

Feel free to open issues or submit pull requests if you find bugs or have suggestions for improvements.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🔗 Resources

- [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/)
- [Strands Agents SDK Documentation](https://github.com/aws/strands-agents)

## ⚠️ Important Notes

- Ensure you have proper AWS credentials configured
- Some examples use `BYPASS_TOOL_CONSENT` for demo purposes - use cautiously in production
- The human-in-the-loop example is best run as a Python script rather than in Jupyter

## 🙏 Acknowledgments

Built with AWS Strands Agents SDK - AWS's framework for production AI agents.
