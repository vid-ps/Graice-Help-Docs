---
description: >-
  The Graice MCP Connector lets OpenAI, Claude and other MCP-compatible AI tools
  securely connect to your Graice workspace and access authorized resources
  using the Model Context Protocol (MCP).
---

# MCP Connectors

### Overview&#x20;

The Graice MCP Connector acts as a secure bridge between your Graice workspace and AI tools such as Claude, OpenAI, and other MCP-compatible applications.

Once configured, your AI tool can securely communicate with Graice to retrieve information from authorized Rooms and DocRooms without requiring you to switch between applications.

This guide walks you through the complete process of configuring the Graice MCP Connector, authenticating your Graice account, managing tool permissions, and using the connector to access and query your Graice knowledge base.

{% hint style="info" %}
This guide demonstrates how to connect the Graice MCP Connector with Claude, OpenAI and other AI applications that support the Model Context Protocol (MCP).
{% endhint %}

### What You'll Learn

By following this guide, you will learn how to:

`✓ Add the Graice MCP Connector to OpenAI OR Claude.`

`✓ Authenticate your Graice account.`

`✓ Configure permissions for the available MCP tools.`

`✓ Enable/Select the Graice MCP Connector in a ChatGPT/Claude chat.`

`✓ Query your Graice knowledge base directly from OpenAI/Claude.`

***

### Graice MCP Connectors

{% tabs %}
{% tab title="OpenAI" icon="openai" %}
## Prerequisites for OpenAI (ChatGPT)

Before connecting the **Graice MCP Connector** to **OpenAI (ChatGPT)**, ensure that you have the following:

✅ An active **OpenAI (ChatGPT)** account.

✅ A valid **Graice** account with access to your organization's Knowledge Base and Docrooms.

✅ Permission to create and configure **Custom MCP Connectors** in ChatGPT.

✅ A stable internet connection.

✅ The Graice MCP Server URL:

```
https://mcp.graice.com/mcp
```

{% hint style="info" %}
**INFO**

You must enable **Developer mode** in ChatGPT before you can add and configure a Custom MCP Connector.
{% endhint %}

***

## Step 1: Enable Developer Mode

Before creating the Graice MCP Connector, you must enable **Developer mode** in your ChatGPT account.

#### Follow these steps:

* ➜ Open **OpenAI (ChatGPT)**.
* ➜ Open the **Settings** window.
* ➜ Select **Security and login** from the left navigation menu.
* ➜ Scroll down to the **Developer mode** section.
* ➜ Turn on the **Developer mode** toggle.

Once enabled, ChatGPT allows you to add and configure **Custom MCP Connectors**.

{% hint style="success" %}
**SUCCESS**

Developer mode is now enabled and your ChatGPT account is ready to add the Graice MCP Connector.
{% endhint %}

***

### Figure 1: Enable Developer Mode

> **Figure 1** illustrates how to enable **Developer mode** from the **Security and login** settings page in OpenAI (ChatGPT).

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-1 .png" alt=""><figcaption></figcaption></figure>

## Step 2: Open the Plugins Page

Once **Developer mode** is enabled, you can create and configure the **Graice MCP Connector** from the Plugins page.

#### Follow these steps:

➜ Close the **Settings** window.

➜ From the left sidebar, click **Plugins**.

➜ The **Plugins** page opens and displays all available plugins.

➜ Click the **➕ (Add)** icon in the top-right corner.

➜ This opens the **New Plugin** window where you can add a new MCP connector.

{% hint style="info" %}
**INFO**

The **➕ (Add)** button is used to create a new custom plugin or MCP connector for your ChatGPT account.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

You are now ready to configure the Graice MCP Connector.
{% endhint %}

***

### Figure 2: Open the Plugins Page

> **Figure 2** shows how to open the **Plugins** page and start creating a new plugin by clicking the **➕ (Add)** button.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-2 .png" alt=""><figcaption></figcaption></figure>

## Step 3: Configure the Graice MCP Plugin

After clicking the **➕ (Add)** button, the **New Plugin** window opens. Here, you can configure the Graice MCP Connector before connecting it to your ChatGPT account.

#### Configure the plugin

➜ **Name**\
Enter a name for the connector, for example:

```
Graice MCP
```

➜ **Description (Optional)**\
Provide a short description to help identify the connector.

➜ **Connection URL**\
Enter the Graice MCP Server URL:

```
https://mcp.graice.com/mcp
```

➜ **Authentication**\
Select the required authentication method. The connector uses **OAuth** for secure authorization.

➜ **Additional Settings**\
Configure any optional settings if required for your environment.

➜ **Create the Connector**\
After verifying all the information, click **Create** to begin connecting the Graice MCP Connector.

{% hint style="info" %}
**INFO**

The **Connection URL** is the endpoint through which ChatGPT securely communicates with your Graice workspace.
{% endhint %}

{% hint style="warning" %}
**IMPORTANT**

Ensure that the MCP Server URL is entered exactly as shown below.

```
https://mcp.graice.com/mcp
```

An incorrect URL will prevent the connector from being created successfully.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

The Graice MCP Connector configuration is complete. ChatGPT will now begin the authorization process.
{% endhint %}

***

### Figure 3: Configure the Graice MCP Plugin

> **Figure 3** shows the **New Plugin** window where you configure the Graice MCP Connector, specify the MCP Server URL, select the authentication method, and create the connector.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-3 .png" alt=""><figcaption></figcaption></figure>

## Step 4: Authorize the Graice MCP Connector

After clicking **Create**, ChatGPT displays the **Add Graice MCP to ChatGPT** authorization window.

This step securely links your **Graice account** with **OpenAI (ChatGPT)** so the connector can access your authorized Graice Knowledge Base.

#### Complete the authorization

➜ Review the authorization message displayed in the popup.

➜ Click **Sign in with Graice MCP**.

➜ A new Graice sign-in page opens in your browser.

➜ Continue with the Graice authentication process.

{% hint style="info" %}
**INFO**

The authorization process uses **OAuth authentication**, allowing ChatGPT to securely connect to your Graice account without exposing your login credentials.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

Always verify that the authorization window is for **Graice MCP** before proceeding with sign-in.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

After clicking **Sign in with Graice MCP**, you will be redirected to the Graice sign-in page to authenticate your account.
{% endhint %}

***

### Figure 4: Authorize the Graice MCP Connector

> **Figure 4** shows the authorization popup that appears after creating the connector. Click **Sign in with Graice MCP** to continue the authentication process.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-4 .png" alt=""><figcaption></figcaption></figure>

## Step 5: Sign in to Your Graice Account

After clicking **Sign in with Graice MCP**, the Graice authentication page opens.

Sign in using your Graice account credentials to authorize ChatGPT to securely access your Graice workspace.

#### Sign in to Graice

You can authenticate using either of the following methods:

➜ **Corporate Email Login**\
Sign in using your organization's corporate email account, if configured.

➜ **Username & Password**\
Enter your Graice username and password.

➜ Click **Sign In** to complete the authentication process.

Once your credentials are successfully verified, Graice securely authorizes the MCP Connector and redirects you back to ChatGPT.

{% hint style="info" %}
**INFO**

Graice supports multiple authentication methods depending on your organization's login configuration.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

Use your organization's official Graice account to ensure you can access the correct Rooms, Docrooms, and Knowledge Base resources.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

Your Graice account has been successfully authenticated. The Graice MCP Connector is now authorized to securely access your permitted Graice resources.
{% endhint %}

***

### Figure 5: Sign in to Graice

> **Figure 5** shows the Graice authentication page where you can sign in using your corporate email or your Graice username and password.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-5 .png" alt=""><figcaption></figcaption></figure>

## Step 6: Verify the Connected Graice MCP Plugin

After successful authentication, ChatGPT completes the connection and displays the **Graice MCP** plugin details.

This confirms that the Graice MCP Connector has been successfully linked to your ChatGPT account and is ready to use.

#### Review the Connector Details

The Graice MCP Plugin page displays important information about the connected plugin, including:

➜ **Plugin Status**\
Confirms that the Graice MCP Plugin is successfully connected.

➜ **Connected Account**\
Displays the Graice account that is currently authorized to use the connector.

➜ **Plugin Permissions**\
Shows the permissions granted to the plugin for accessing your Graice workspace.

➜ **Developer Information**\
Displays the plugin developer and related information.

➜ **MCP Server Information**\
Shows the configured Graice MCP Server URL and other connection details.

Review these details to ensure the connector has been configured correctly.

{% hint style="info" %}
**INFO**

The displayed account and connection details help you verify that the correct Graice account has been connected to ChatGPT.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

Before using the connector, verify that the displayed Graice account, permissions, and MCP Server URL are correct. This helps ensure ChatGPT retrieves information from the intended Graice workspace.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

The Graice MCP Plugin is successfully connected and ready to retrieve information from your authorized Graice Knowledge Base.
{% endhint %}

***

### Figure 6: Connected Graice MCP Plugin

> **Figure 6** shows the Graice MCP Plugin after a successful connection, including the connected account, granted permissions, and MCP Server information.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-6 .png" alt=""><figcaption></figcaption></figure>

## Step 7: View the Installed Graice MCP Plugin

Once the Graice MCP Plugin has been successfully connected, it appears in your **Plugins** page along with your other installed plugins.

From here, you can quickly access the plugin, review its details, and manage its configuration.

#### View the Installed Plugin

To locate the Graice MCP Plugin:

➜ Open the **Plugins** page from the left navigation panel.

➜ Locate the **Graice MCP** plugin in the list of installed plugins.

➜ Click the **Graice MCP** plugin to open its details page.

The plugin details page provides additional information about the connector, including its configuration, permissions, and management options.

{% hint style="info" %}
**INFO**

The **Plugins** page displays all MCP plugins and custom connectors that are installed in your ChatGPT account.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

Assign a clear and meaningful name, such as **Graice MCP**, so the connector can be easily identified when multiple plugins are installed.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

The Graice MCP Plugin is now installed and available in your ChatGPT account. You can open the plugin at any time to review its details or manage its configuration.
{% endhint %}

***

### Figure 7: View the Installed Graice MCP Plugin

> **Figure 7** shows the **Plugins** page where the installed **Graice MCP** plugin is listed. Click the plugin to view its details and configuration.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-7 .png" alt=""><figcaption></figcaption></figure>

## Step 8: Manage the Graice MCP Plugin

The **Graice MCP** plugin provides additional management options that allow you to review or modify the connector configuration whenever required.

You can access these options directly from the plugin details page.

#### Manage the Plugin

To manage the Graice MCP Plugin:

➜ Open the **Graice MCP** plugin details page.

➜ Click the **⋮ (More Options)** menu in the upper-right corner.

➜ Select **Manage** from the context menu.

The **Manage** option allows you to review and update the plugin configuration whenever necessary.

#### You can manage the following

➜ Review the plugin configuration.

➜ Update the connector settings.

➜ Modify authentication or connection details.

➜ Review plugin permissions.

➜ Reconfigure the plugin if your environment or connection settings change.

{% hint style="info" %}
**INFO**

The **Manage** option opens the plugin configuration page where you can review or update the Graice MCP Connector settings without creating a new plugin.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

If the Graice MCP Server URL, authentication settings, or connection configuration changes, use the **Manage** option to update the existing plugin instead of creating another connector.
{% endhint %}

{% hint style="success" %}
**SUCCESS**

You can now manage and maintain the Graice MCP Plugin whenever required, ensuring that your ChatGPT account always uses the latest connector configuration.
{% endhint %}

***

### Figure 8: Manage the Graice MCP Plugin

> **Figure 8** shows the **Graice MCP** plugin details page. Open the **⋮ (More Options)** menu and select **Manage** to review or update the connector configuration.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-8 .png" alt=""><figcaption></figcaption></figure>

## Step 9: Use the Graice MCP Plugin in ChatGPT

After the Graice MCP Plugin has been successfully configured, you can begin using it directly within your ChatGPT conversations.

Simply select the Graice MCP Plugin, enter your prompt, and ChatGPT will securely retrieve relevant information from your Graice Knowledge Base before generating a response.

***

### Use the Graice MCP Plugin

Open a **New Chat** in your ChatGPT account.

To use the Graice MCP Plugin:

➜ Type **@** in the chat input box.

➜ Select the **Graice MCP** plugin from the list of available plugins.

➜ Enter your prompt or question.

➜ Click **Send** or press **Enter**.

ChatGPT automatically communicates with the Graice MCP Connector to retrieve relevant information from your authorized Graice Rooms and Docrooms.

The retrieved information is then used to generate an accurate, context-aware response within the same conversation.

***

### Example Prompts

You can ask questions such as:

➜ Show me the list of available Rooms.

➜ Summarize the Employee Handbook.

➜ Find the Leave Policy document.

➜ Search for API documentation.

➜ Explain the deployment process.

➜ List all available Docrooms.

➜ Retrieve information about the Sales Knowledge Base.

***

### How It Works

When you submit a prompt:

➜ ChatGPT sends your request to the **Graice MCP Plugin**.

➜ The plugin securely connects to your Graice workspace.

➜ Graice searches your authorized Rooms and Docrooms.

➜ Relevant knowledge is returned to ChatGPT.

➜ ChatGPT generates a precise, context-aware response based on the retrieved information.

{% hint style="info" %}
**INFO**

The Graice MCP Plugin can only access the Rooms, Docrooms, and Knowledge Base content that your Graice account is authorized to access.
{% endhint %}

{% hint style="info" %}
**BEST PRACTICE**

Write clear and specific prompts to receive more accurate and relevant responses from your Graice Knowledge Base.
{% endhint %}

***

### Figure 9: Use the Graice MCP Plugin in ChatGPT

> **Figure 9** shows how to select the **Graice MCP** plugin using **@**, submit a prompt, and receive a response from your Graice Knowledge Base.

<figure><img src=".gitbook/assets/Graice MCP Connector - OpenAI - SS-9  (1).png" alt=""><figcaption></figcaption></figure>

***

### Expected Result

After completing all the steps in this guide:

✅ The Graice MCP Plugin is successfully connected to your ChatGPT account.

✅ ChatGPT can securely communicate with your Graice workspace.

✅ You can retrieve information from your authorized Graice Docrooms. .

✅ Responses are generated using the knowledge available in your Graice Knowledge Base.

{% hint style="success" %}
**SUCCESS**

You have successfully connected and configured the **Graice MCP Plugin** with **OpenAI (ChatGPT)**. You can now use ChatGPT to securely access your Graice Knowledge Base and receive accurate, context-aware responses directly within your conversations.
{% endhint %}

***
{% endtab %}

{% tab title="Claude" icon="claude" %}
### Prerequisites for Claude

Before you begin, ensure that you have the following:

✅ A valid **Claude** account.

✅ A valid **Graice** user account.

✅ Access to your Graice workspace containing the required Rooms and DocRooms.

✅ The Graice MCP Connector URL:

```
https://mcp.graice.com/mcp
```

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

### Expected Result

After completing this guide:

✓ Claude AI will be securely connected to your Graice workspace.

✓ You can query your authorized Graice Rooms and DocRooms directly from Claude.

✓ Claude will retrieve relevant knowledge through the Graice MCP Connector and generate accurate responses without leaving the chat interface.

{% hint style="success" %}
SUCCESS: Once the Graice MCP Connector is enabled, Claude AI becomes a secure interface for interacting with your Graice knowledge base using natural language prompts.
{% endhint %}

***

## Add the Graice MCP Connector in Claude

This section explains how to add the Graice MCP Connector as a custom connector in Claude AI.

***

### Step 1 — Open Claude Settings

Open your **Claude** account.

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
{% endtab %}
{% endtabs %}



