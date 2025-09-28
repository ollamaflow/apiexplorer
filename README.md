# Ollama API Explorer

<img src="assets/logo.png" alt="OllamaFlow Logo" width="192" height="192">

A simple web-based API testing tool for [OllamaFlow](https://ollamaflow.com) - a powerful inference load balancer and API gateway for LLM deployments.

## Overview

Ollama API Explorer provides an intuitive interface for testing and validating APIs in scaled inference architectures. Whether you're exploring API endpoints, debugging requests, or validating your OllamaFlow deployment, this tool offers a streamlined way to interact with your LLM services.

## Features

- **Multi-Format Support**: Test both Ollama and OpenAI API formats
- **Real-time Testing**: Send requests directly to your OllamaFlow instance
- **Collapsible Settings**: Clean, organized interface that gets out of your way
- **Streaming Support**: Test streaming and non-streaming completions
- **Request Validation**: JSON syntax validation and error handling
- **Response Inspection**: View response body, headers, and status information

## Use Cases

- **API Exploration**: Discover and test different endpoints and request formats
- **Load Testing**: Validate your scaled inference architecture under various conditions
- **Development**: Debug API requests and responses during development
- **Integration Testing**: Ensure your OllamaFlow deployment handles requests correctly
- **Demo and Training**: Showcase LLM capabilities to stakeholders

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Configure the Base URL to point to your OllamaFlow instance
4. Select your desired request format (Ollama or OpenAI)
5. Choose a request type and model
6. Send your first request!

## Configuration

The tool automatically updates the Base URL when you change request types, but you can override this to test specific endpoints. This flexibility allows you to:

- Test embedding endpoints with chat requests (intentionally)
- Explore custom API paths
- Debug endpoint routing issues

## About OllamaFlow

[OllamaFlow](https://ollamaflow.com) is a high-performance inference load balancer and API gateway designed for production LLM deployments. It provides:

- Load balancing across multiple inference servers
- API format translation (Ollama ↔ OpenAI)
- Request queuing and rate limiting
- Health monitoring and failover
- Centralized logging and metrics

For more information, visit:
- **Website**: [https://ollamaflow.com](https://ollamaflow.com)
- **GitHub**: [https://github.com/ollamaflow/ollamaflow](https://github.com/ollamaflow/ollamaflow)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.