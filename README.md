# Multi-Framework AI Agent Generator

A powerful tool for generating AI agents using different frameworks including LangGraph, CrewAI, and AutoGen. This application provides a user-friendly interface to create and test AI agents with various LLM providers.

## Features

- Support for multiple AI frameworks:
  - LangGraph: For stateful workflows and complex decision trees
  - CrewAI: For collaborative agent teams with specialized roles
  - AutoGen: For conversational agents and chat-based systems
- Multiple LLM provider support:
- Interactive Streamlit interface
- Code validation and testing
- Quick-start templates for common use cases

##Output
1. ![1743625241990](https://github.com/user-attachments/assets/32aa7b0e-36be-480e-b5d9-2329b4274474)
2. ![1743625242186](https://github.com/user-attachments/assets/f09ea662-0527-4955-a304-1b0569da8146)
3.![1743625242710](https://github.com/user-attachments/assets/edce0b6a-6e48-477a-8626-6b2df564c306)
4.![1743625242343](https://github.com/user-attachments/assets/34ad2b31-dccf-4977-996c-b9760e08cc0a)

## Prerequisites

- Python 3.8 or higher
- API keys for your chosen LLM provider(s)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/shadsidd/multi-framework-ai-agent-generator.git
cd multi-framework-ai-agent-generator
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
streamlit run mulitagent-framework.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

1. Select your preferred framework (LangGraph, CrewAI, or AutoGen)
2. Choose an LLM provider and model
3. Enter your API key
4. Either:
   - Use a Quick Start Template
   - Or describe your agent system in the text area
5. Click "Generate Agent System"
6. Review and download the generated code

## Requirements

## Supported Frameworks

### LangGraph
- Best for stateful workflows and complex decision trees
- Uses StateGraph for workflow management
- Includes proper state management and error handling

### CrewAI
- Ideal for collaborative agent teams
- Supports role-based task delegation
- Includes built-in collaboration mechanisms

### AutoGen
- Perfect for conversational agents
- Supports multiple agent types
- Includes chat-based workflows

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
