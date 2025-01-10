# Benten Avatar Framework

Open-source personal AI framework that builds your knowledge graph (a personal wiki) and coordinates specialized AI agents to help achieve your goals.

## Overview
The Benten Avatar Framework helps you build and maintain a dynamic knowledge graph through natural conversation with an AI assistant. Starting with Claude 3.5 Sonnet (Anthropic's most advanced AI model), it automatically organizes your thoughts, ideas, and insights into an evolving personal wiki. This forms the foundation for your personal AI ecosystem, designed to grow with you over time.

## 🚧 Project Status
Early development - Core functionality under active development. This MVP focuses on:
- Command-line conversation interface with Claude
- Automated knowledge extraction and wiki creation
- Knowledge graph visualization through Obsidian
- Foundation for future agent extensibility and coordination

## Current Features
- **Natural Conversation**: Chat with Claude through a simple command-line interface
- **Automated Knowledge Management**: Conversations automatically contribute to your personal wiki
- **Dynamic Graph Building**: Auto-generated and linked markdown files
- **Visual Knowledge Map**: Obsidian integration for knowledge graph visualization
- **Extensible Design**: Built to support future integration with additional AI agents and extensions

## Getting Started

### Prerequisites
- Node.js (v22.13.0 or later)
- Anthropic API key
- Obsidian (for visualization)

### Installation
```bash
# Clone the repository
git clone https://github.com/BentenAI/benten-avatar.git
cd BentenAvatar

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your Anthropic API key to .env
```

### Quick Start
```bash
# Start the conversation interface
npm start
```

## Architecture

### MVP Components
1. **Conversation Layer**
   - Claude integration via Anthropic API
   - Context management
   - Basic memory system

2. **Knowledge Processing**
   - Information extraction from conversations
   - Wiki page generation and linking
   - Basic pattern recognition

3. **Graph Management**
   - Markdown file creation and updates
   - Automated linking
   - Obsidian integration

## Development

### Current Focus (MVP)
- Building core conversation infrastructure
- Implementing knowledge extraction
- Setting up wiki management system
- Establishing graph visualization

### Future Development
- Enhanced knowledge processing
- Advanced pattern recognition
- Multi-agent coordination
- Collaborative features
- Personal AI ecosystem expansion

## Contributing
We welcome contributions! This project is in early stages and actively evolving. See our [Contributing Guidelines](CONTRIBUTING.md) for details on:
- Code style
- Development process
- Pull request procedure

## Vision
While the current MVP focuses on knowledge management through conversation with Claude, the Benten Avatar Framework is designed to evolve into a comprehensive personal AI ecosystem. Future developments will expand into:
- Advanced knowledge organization
- Multi-agent task delegation
- Automated workflow management
- Collaborative spaces
- Personal AI ecosystem development

## License
MIT License - See [LICENSE](LICENSE) for details

## Contact
- Ben Parisi - ben@benten.ai
- Project Link: [https://github.com/benten-ai/benten-avatar](https://github.com/benten-ai/benten-avatar)

## Built With
- [LangChain.js](https://js.langchain.com/docs/introduction/) - Agent framework
- [Anthropic API](https://console.anthropic.com/) - Claude integration
- [Obsidian](https://obsidian.md/) - Knowledge graph visualization
