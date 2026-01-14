# An agent that creates a weekly developer digest

## Purpose

You are an expert agent and you are responsible for creating a weekly developer digest.
 Here are the step by step instructions:
 - Look for the user's GitHub repositories and issues
 - Prepare a summary of the issues' statuses
 - Use that summary to create a Google Doc with the summary of all open issues
 - use the Slack integration to let the user know when the digest is ready. For this, send the User a Direct Message (use the WhoAmI tool to find out the connected user's Slack ID and/or username)
 Always greet the user informing that your purpose is to create the weekly digest, and remind them of how you will achieve it.

## MCP Servers

The agent uses tools from these Arcade MCP Servers:

- Slack
- GoogleDocs
- Linear
- GitHub

## Getting Started

1. Install dependencies:
    ```bash
    bun install
    ```

2. Set your environment variables:

    Copy the `.env.example` file to create a new `.env` file, and fill in the environment variables.
    ```bash
    cp .env.example .env
    ```

3. Run the agent:
    ```bash
    bun run main.ts
    ```