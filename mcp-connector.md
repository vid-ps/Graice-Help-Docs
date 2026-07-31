---
description: >-
  The Graice MCP Connector allows AI tools such as Claude AI to securely connect
  to your Graice workspace using the Model Context Protocol (MCP). Once
  connected, Claude can access your authorized Graice
---

# MCP Connector

### Overview

The Graice MCP Connector acts as a secure bridge between any AI Tool (e.g. Claude) and your Graice workspace.

After the connector is configured, Claude can communicate directly with Graice to retrieve information from authorized Rooms and DocRooms without requiring you to switch between applications.

This guide walks you through the complete process of configuring the Graice MCP Connector in Claude AI, authenticating your Graice account, configuring tool permissions, and using the connector to query your Graice knowledge base.

{% hint style="info" %}
INFO: This guide demonstrates how to connect the Graice MCP Connector with **Claude AI**. The same MCP connector can also be used with other AI applications that support the **Model Context Protocol (MCP)**.
{% endhint %}

***

### Prerequisites

Before you begin, ensure that you have the following:

✓ A valid **Claude AI** account.

✓ A valid **Graice** user account.

✓ Access to your Graice workspace containing the required Rooms and DocRooms.

✓ The Graice MCP Connector URL:

```
https://mcp.graice.com/mcp
```

***

### What You'll Learn

By following this guide, you will learn how to:

`✓ Add the Graice MCP Connector to Claude AI.`

`✓ Authenticate your Graice account.`

`✓ Configure permissions for the available MCP tools.`

`✓ Enable the Graice MCP Connector in a Claude chat.`

`✓ Query your Graice knowledge base directly from Claude AI.`

***

### How the Graice MCP Connector Works

The complete setup consists of six simple steps:

→ **Step 1** — Open **Claude Settings**.

→ **Step 2** — Add the **Graice MCP Connector**.

→ **Step 3** — Connect your Graice account.

→ **Step 4** — Configure the required tool permissions.

→ **Step 5** — Enable the Graice MCP Connector in a Claude chat.

→ **Step 6** — Start querying your Graice Rooms and DocRooms from Claude AI.

***

### Connection Workflow

```
Open Claude Settings
        │
        ▼
Add Graice MCP Connector
        │
        ▼
Connect Graice Account
        │
        ▼
Configure Tool Permissions
        │
        ▼
Enable Connector in Claude Chat
        │
        ▼
Start Using Graice MCP
```

***

### Expected Result

After completing this guide:

✓ Claude AI will be securely connected to your Graice workspace.

✓ You can query your authorized Graice Rooms and DocRooms directly from Claude.

✓ Claude will retrieve relevant knowledge through the Graice MCP Connector and generate accurate responses without leaving the chat interface.

> SUCCESS: Once the Graice MCP Connector is enabled, Claude AI becomes a secure interface for interacting with your Graice knowledge base using natural language prompts.

***

## Add the Graice MCP Connector in Claude AI

This section explains how to add the Graice MCP Connector as a custom connector in Claude AI.

***

### Navigation

**Claude AI → User Menu → Settings → Connectors**

***

### Step 1 — Open Claude Settings

Open your **Claude AI** account.

Click your **User Profile** icon in the bottom-left corner to open the account menu, and then select **Settings**.

***

#### Figure 1. Open Claude Settings

> **Description:** Click your user profile icon and select **Settings** to open the Claude settings page.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-1 .png" alt=""><figcaption></figcaption></figure>



***

### Step 2 — Add a Custom Connector

From the **Settings** page, click **Connectors** from the left navigation panel.

Next:

→ Click **Add**.

→ Select **Add custom connector** from the drop-down menu.

This opens the **Add custom connector** dialog.

***

#### Figure 2. Add a Custom Connector

> **Description:** Open the **Connectors** page, click **Add**, and then select **Add custom connector**.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-2.png" alt=""><figcaption></figcaption></figure>



***

### Step 3 — Configure the Graice MCP Connector

In the **Add custom connector** dialog, provide the connector details.

Enter the following information:

✓ **Connector Name**

```
Graice MCP
```

✓ **MCP Server URL**

```
https://mcp.graice.com/mcp
```

After entering the required information, click **Add**.

***

#### Figure 3. Configure the Graice MCP Connector

> **Description:** Enter the connector name and MCP Server URL, then click **Add** to create the Graice MCP Connector.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-3.png" alt=""><figcaption></figcaption></figure>



***

{% hint style="success" %}
BEST\_PRACTICE: Copy and paste the MCP Server URL to avoid typing errors during configuration.
{% endhint %}

***

### Expected Result

After completing these steps:

✓ The Graice MCP Connector is successfully added to your Claude account.

✓ The connector appears in the **Connectors** list.

✓ The connector is ready to be authenticated with your Graice account.

***

> SUCCESS: You have successfully added the Graice MCP Connector to Claude AI. The next step is to authenticate your Graice account and establish the secure connection.

***

## Connect Your Graice Account

After adding the Graice MCP Connector, you must authenticate it with your Graice account before it can access your workspace.

***

### Navigation

**Claude AI → Settings → Connectors → Graice MCP**

***

### Connect to Graice

Open the **Graice MCP** connector from the **Connectors** list.

Initially, the connector displays a message indicating that it is not yet connected to your Graice account.

To establish the connection:

→ Click **Connect**.

→ Complete the Graice authentication process.

→ Grant the required permissions, if prompted.

Once authentication is successful, Claude securely connects to your Graice workspace.

***

#### Figure 4. Connect the Graice MCP Connector

> **Description:** Click **Connect** to authenticate your Graice account and establish a secure connection with the Graice MCP Connector.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-4.png" alt=""><figcaption></figcaption></figure>



***

> INFO: The authentication process is performed securely through Graice. Your login credentials are not stored by Claude AI.

***

### Expected Result

After completing these steps:

✓ The Graice MCP Connector is successfully connected to your Graice account.

✓ Claude AI can securely communicate with your Graice workspace.

✓ The connector is now ready for permission configuration.

***

> SUCCESS: Your Graice account has been successfully connected. You can now configure the permissions that determine how Claude interacts with the available Graice MCP tools.

***

## Configure Tool Permissions

After connecting your Graice account, configure the permissions for each available MCP tool. These permissions determine how Claude AI interacts with your Graice workspace.

***

### Navigation

**Claude AI → Settings → Connectors → Graice MCP**

***

### Configure Tool Permissions

The **Graice MCP** connector displays the list of available tools along with their permission settings.

For each tool, choose one of the following permission options:

✓ **Always Allow**\
Claude can use the tool without requesting approval each time.

✓ **Needs Approval**\
Claude asks for your approval before using the tool.

✓ **Blocked**\
Claude cannot use the tool.

Select the permission level that best suits your security and workflow requirements.

***

#### Figure 5. Configure Tool Permissions

> **Description:** Review the available MCP tools and configure the appropriate permission level for each tool.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-5.png" alt=""><figcaption></figcaption></figure>



***

### Disconnect the Graice MCP Connector

If you no longer want Claude AI to access your Graice workspace, click **Disconnect**.

Disconnecting the connector immediately removes Claude's access to your Graice account. You can reconnect it at any time by completing the authentication process again.

***

> BEST\_PRACTICE: Use **Needs Approval** while evaluating the connector. Once you're comfortable with its behavior, you can switch frequently used tools to **Always Allow** for a smoother experience.

***

### Expected Result

After completing these steps:

✓ The required permissions are configured for each Graice MCP tool.

✓ Claude AI can access only the tools based on the permission levels you selected.

✓ The Graice MCP Connector is fully configured and ready to use.

***

> SUCCESS: The Graice MCP Connector has been successfully configured. You can now enable it in a Claude chat and start interacting with your Graice knowledge base.

***

## Enable the Graice MCP Connector in Claude Chat

After configuring the Graice MCP Connector, you must enable it within your Claude chat before it can access your Graice knowledge base.

***

### Navigation

**Claude AI → New Chat → + → Connectors**

***

### Enable the Graice MCP Connector

Open a **New Chat** in Claude AI.

To enable the connector:

→ Click the **+** icon next to the message box.

→ Select **Connectors**.

→ Turn on the **Graice MCP** connector.

Once enabled, Claude is ready to access your authorized Graice Rooms and DocRooms during the conversation.

***

#### Figure 6. Enable the Graice MCP Connector

> **Description:** Open the **Connectors** menu from a Claude chat and enable the **Graice MCP** connector.

<figure><img src=".gitbook/assets/Graice MCP Connector SS-6.png" alt=""><figcaption></figcaption></figure>



***

> INFO: The Graice MCP Connector must be enabled for each chat where you want Claude to access your Graice knowledge base.

***

### Verify the Connection

After enabling the connector:

✓ The **Graice MCP** connector appears as enabled in the current chat.

✓ Claude can now communicate with your Graice workspace.

✓ You are ready to submit prompts that retrieve information from your authorized Rooms and DocRooms.

***

### Expected Result

After completing these steps:

✓ The Graice MCP Connector is active in your current Claude chat.

✓ Claude is ready to retrieve information from your Graice workspace whenever required.

***

> SUCCESS: The Graice MCP Connector is now enabled for this conversation. You can begin asking questions and retrieve knowledge directly from your Graice workspace.

***

## Using the Graice MCP Connector

After enabling the Graice MCP Connector in your Claude chat, you can begin querying your Graice knowledge base using natural language prompts.

***

### Ask Questions in Claude AI

Simply type your question or request in the Claude chat and submit it.

When the Graice MCP Connector is enabled, Claude communicates with your Graice workspace to retrieve relevant information from your authorized Rooms and DocRooms before generating a response.

***

### Example Prompts

Here are a few examples of questions you can ask:

✓ Summarize the onboarding process for new employees.

✓ Find the leave policy document.

✓ Explain the deployment process for our application.

✓ List the security guidelines for accessing production systems.

✓ Search for the latest API documentation.

***

### How It Works

When you submit a prompt:

→ Claude sends the request through the Graice MCP Connector.

→ Graice searches your authorized Rooms and DocRooms.

→ Relevant information is securely returned to Claude.

→ Claude generates a context-aware response based on the retrieved information.

***

> INFO: Claude can only retrieve information that your Graice account is authorized to access.

***

### Best Practices

✓ Ask clear and specific questions.

✓ Use descriptive keywords to improve search accuracy.

✓ Ensure the required documents are available in your Graice Rooms or DocRooms.

✓ Verify that the Graice MCP Connector is enabled for the current chat.

***

### Expected Result

After completing these steps:

✓ Claude retrieves relevant information from your Graice workspace.

✓ Responses are generated using the knowledge available in your authorized Rooms and DocRooms.

✓ You can continue asking follow-up questions within the same conversation.

***

## Troubleshooting

This section provides solutions to common issues that you may encounter while configuring or using the Graice MCP Connector.

***

### Common Issues

#### Graice MCP Connector is not visible

Possible causes:

✓ The connector was not added successfully.

✓ You are signed in with a different Claude account.

**Solution**

→ Verify that the Graice MCP Connector has been added under **Settings → Connectors**.

→ If necessary, add the connector again using the correct MCP Server URL.

***

#### Unable to Connect to Graice

Possible causes:

✓ Authentication was cancelled.

✓ Invalid Graice credentials.

✓ Temporary network issue.

**Solution**

→ Click **Connect** again and complete the authentication process.

→ Verify that you can successfully sign in to your Graice account.

***

#### Claude Cannot Access Graice Data

Possible causes:

✓ The Graice MCP Connector is disabled for the current chat.

✓ The required tool permissions are restricted.

**Solution**

→ Enable the **Graice MCP** connector from the **Connectors** menu in your current chat.

→ Verify that the required tools are configured with the appropriate permission level.

***

#### No Relevant Information Found

Possible causes:

✓ The requested information is not available in your authorized Rooms or DocRooms.

✓ The search query is too broad or unclear.

**Solution**

→ Use more specific keywords in your prompt.

→ Verify that the required documents exist in your Graice workspace.

***

{% hint style="success" %}
SUCCESS: You have successfully completed the Graice MCP Connector setup. Claude AI is now ready to securely access your authorized Graice knowledge base and assist you with context-aware responses.
{% endhint %}

***

