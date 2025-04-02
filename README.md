# Multi-Framework AI Agent Generator

A Streamlit-based web application that generates AI agent systems using different frameworks (LangGraph, CrewAI, and AutoGen) based on user prompts.

## Features

- **Multiple Framework Support**: Generate agent systems using:
  - LangGraph (for stateful workflows)
  - CrewAI (for collaborative teams)
  - AutoGen (for conversational agents)

- **LLM Provider Integration**:
  - Google Gemini
  - OpenAI
  - Anthropic (coming soon)

- **Quick Start Templates**: Pre-built templates for common use cases:
  - Customer Support Workflows
  - Document Processing Pipelines
  - Research Teams
  - Marketing Crews
  - Code Review Systems
  - Data Analysis Teams

- **Code Validation**: Built-in validation to ensure generated code follows framework best practices
- **Dependency Management**: Automatic generation of requirements.txt
- **Code Testing**: Basic syntax validation for generated code

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/multi-framework-ai-agent-generator.git
cd multi-framework-ai-agent-generator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run mulitagent-framework.py
```

## Usage

1. Select your preferred framework (LangGraph, CrewAI, or AutoGen)
2. Choose an LLM provider and model
3. Enter your API key
4. Either:
   - Use a Quick Start Template
   - Or describe your agent system in the text area
5. Click "Generate Agent System"
6. Review and download the generated code

## Requirements

- Python 3.8+
- Streamlit
- OpenAI
- Google Generative AI
- LangGraph
- CrewAI
- AutoGen

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 