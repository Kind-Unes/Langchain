# Langchain Crash Course

## Overview
This Jupyter Notebook provides a crash course on using Langchain, a tool for building language model-based chains to generate creative responses, suggestions, and more. It covers key components such as language models (LLMs), prompt templates, chains, agents, and memory.

## Prerequisites
- Python 3.6 or higher
- Required packages (install using `pip install [package_name]`):
  - langchain
  - google-search-results (for Agents)
  - serpapi (for Agents)
  - wikipedia (for Agents)

## Getting Started
1. Clone the repository to your local machine.
2. Install the required packages mentioned in the prerequisites.
3. Open the Jupyter Notebook.

## Usage
1. Obtain API keys for OpenAI and SerpAPI, and replace the placeholders in the code with your actual keys.
2. Run each code cell sequentially to understand and execute different aspects of Langchain.
3. Explore the provided examples, modify inputs, and experiment with different configurations.

## Code Structure
- `secret_key.py`: Placeholder file for storing API keys (replace with your actual keys).
- `langchain.llms`: Contains the OpenAI language model implementation.
- `langchain.prompts`: Defines prompt templates for generating prompts dynamically.
- `langchain.chains`: Implements different types of chains (Simple Sequential, Sequential, Conversation, etc.).
- `langchain.agents`: Introduces agents that use external tools like serpapi and llm-math.

## Examples
1. **Generating Restaurant Names**
   - Use OpenAI to generate creative restaurant names based on a specified cuisine.

2. **Prompt Templates**
   - Dynamically generate prompts using template variables for different cuisines.

3. **Chains**
   - Create chains to generate restaurant names and menu items sequentially.

4. **Agents**
   - Utilize external tools like serpapi and llm-math to perform specific tasks (e.g., search and calculation).

5. **Memory**
   - Explore different memory options, such as ConversationBufferMemory and ConversationBufferWindowMemory.

6. **ConversationChain**
   - Implement a conversation chain that retains context and responds to user queries.

## Contributing
Feel free to contribute to the development of Langchain by opening issues or submitting pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Langchain is based on OpenAI's GPT-3.5 architecture.

