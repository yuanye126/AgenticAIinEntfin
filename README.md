# CryptoVCBot

A sophisticated multi-agent cryptocurrency venture capital analysis bot built with LangGraph. CryptoVCBot helps crypto VCs make informed investment decisions by analyzing startups across multiple dimensions using specialized AI agents.

## 🚀 Features

### Multi-Agent Architecture
- **Consultant Agent**: Supervisor that coordinates analysis and makes final investment recommendations
- **Whitepaper Agent**: Analyzes technical documentation and tokenomics using RAG
- **Market Agent**: Evaluates market trends and competitive positioning using CoinGecko and Tavily APIs
- **GitHub Agent**: Assesses code quality and development activity
- **OnChain Agent**: Analyzes blockchain data and token metrics using Etherscan
- **Social Agent**: Evaluates social media presence and community engagement
- **Website Agent**: Reviews website quality and user experience

### Advanced Capabilities
- **RAG System**: Vector database for whitepaper analysis and knowledge retrieval
- **Reflection Loops**: Each agent iterates up to 3 times to improve analysis quality
- **Conditional Agent Routing**: Only runs agents when relevant data is provided
- **LangGraph Workflow**: Orchestrates complex multi-agent coordination
- **Multi-LLM Support**: Choose between OpenAI, Anthropic Claude, or DeepSeek
- **Memory Management**: Working memory and long-term analysis storage
- **LangSmith Integration**: Tracing and visualization of agent workflows


