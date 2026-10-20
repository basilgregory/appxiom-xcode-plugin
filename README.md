# Appxiom Xcode Plugin

## Overview

The **Appxiom Xcode Plugin** integrates the Appxiom MCP (Model Context Protocol) server with Xcode, enabling developers to connect Appxiom with Xcode's AI-powered development environment.

This repository contains the configuration required to add Appxiom MCP as a plugin in Xcode.

## Prerequisites

- Xcode with support for MCP plugins.
- Access to an Appxiom account for authentication.
- Git installed on your system.

## Installation and Setup

### 1. Launch Xcode

Open Xcode on your Mac.

### 2. Clone the Repository

Open the terminal and run the following command to clone the repository:

```bash
git clone https://github.com/basilgregory/appxiom-xcode-plugin.git
```

### 3. Add the Plugin to Xcode

1. Open **Xcode → Settings**.
2. Navigate to **Intelligence**.
3. Select **Plugins from Agents in Xcode**.
4. Click **Add Plugin**.
5. Select **Add from File**.
6. Navigate to the cloned `appxiom-xcode-plugin` repository and open it.

### 4. Authenticate with Appxiom MCP

Once the plugin is added, an **Appxiom** plugin entry with a **Sign In** button should appear.

1. Click **Sign In**.
2. Complete the Appxiom authentication flow.
3. Authorize the connection to Appxiom MCP if prompted.

### 5. Verify the Connection

1. Start a **new chat** in Xcode.
2. Check whether Appxiom MCP is available to the AI agent.
3. Send a request that uses an Appxiom MCP capability to verify that the integration is working.

If the agent can access and use Appxiom MCP successfully, the integration is complete.

## Troubleshooting

- **Plugin not appearing:** Verify that you selected the cloned repository when adding the plugin.
- **Authentication issues:** Sign in again and ensure your Appxiom account is accessible.
- **MCP connection issues:** Check the authentication status and MCP server configuration, then retry in a new chat.