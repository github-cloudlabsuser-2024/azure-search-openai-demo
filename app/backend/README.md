# Backend Documentation

The backend of this application is built using Quart, a Python framework for asynchronous web applications. It communicates with the frontend using the AI Chat HTTP Protocol.

## Key Dependencies

The backend relies on several key Python libraries and Azure services:

- Quart for the web framework
- Azure Cognitive Services for speech synthesis
- Azure Search for document search capabilities
- Azure Storage for blob and data lake storage
- OpenAI for AI capabilities

## Key Files

The main file in the backend is [`app.py`](../../../../c:/Users/azureuser/azure-search-openai-demo/app/backend/app.py). This file imports the necessary libraries and sets up the application routes.

## Routes

The application has several routes defined in `app.py`, including:

- `/` (the index route)
- `/redirect` (used for login redirects)
- `/favicon.ico` (serves the favicon)
- `/assets/<path:path>` (serves static assets)
- `/content/<path>` (serves content)

## Configuration

The backend is configured through a series of environment variables, which are imported from the `config` module.

## Running the Backend

The backend can be started by running the `start.ps1` script in the root directory of the application. This script sets up the necessary environment, installs dependencies, and starts the backend server.

## Customizing the Backend

For more details on customizing the backend, refer to the [customization guide](../../../../c:/Users/azureuser/azure-search-openai-demo/docs/customization.md#customizing-the-backend).