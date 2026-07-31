---
description: >-
  Agent Library enables organizations to create, configure, and manage
  intelligent AI Agents for different business roles.
---

# Agent Library

### Overview

Agent Library provides a centralized workspace for creating, configuring, assigning, and managing AI Agents across your organization.

Each Agent can be tailored to support a specific business function by combining:

✓ Persona

✓ AI Model

✓ Knowledge Base

✓ Behavioral Instructions

Once configured, Agents can be assigned to individual users or teams and integrated with DocRooms to deliver contextual, knowledge-grounded responses.

### What You'll Learn

By the end of this guide, you will understand how to:

`✓ How Agent Library works`

`✓ How to enable and configure AI Agents`

`✓ How to assign Agents to users`

`✓ How to connect DocRooms and AI Models`

`✓ How to use Agents in Chat`

### Key Highlights

✓ Create and manage intelligent AI Agents

✓ Enable predefined Graice Agents

✓ Configure Personas, AI Models, and Knowledge Bases

✓ Assign Agents to users or teams

✓ Connect Agents with DocRooms

✓ Support role-based AI automation across departments

{% hint style="info" %}
INFO

Before using Agent Library, ensure that both **Agents** and **Connectors** are enabled from **Admin → Advanced Options**. User Groups must also have the required permissions enabled.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Create Agents based on business functions (such as HR, Finance, Legal, or Marketing) rather than individual users. This makes administration easier and improves scalability.
{% endhint %}

### Agent Library Workflow

The typical workflow for using Agent Library is:

1. Enable Agent Library.
2. Enable predefined Graice Agents.
3. Manage enabled Agents.
4. Assign Agents to users.
5. Configure Agent Properties.
6. Configure Basic Properties and Persona.
7. Configure AI Model and Knowledge Base.
8. Use Agents in Chat.
9. Interact with AI Agents.

**Navigation**

AI Studio → Agent Library

**Screenshot Location**

Agent Library landing page

Overview of the Agent Library workspace showing available Graice Agents and organizational Agent management.

## Enable Agent Library

Before users can create or use AI Agents, Agent Library must be enabled for your organization. This is a one-time administrator configuration that activates the Agent Library feature and grants access to authorized User Groups.

### What You'll Do

By the end of this guide, you will be able to:

✓ Enable Agents and Connectors from Advanced Options.

✓ Grant Agent Library permissions to the required User Groups.

#### Step 1 — Enable Agents and Connectors

Navigate to **Admin → Advanced Options**.

Enable the following features:

✓ Agents

✓ Connectors

{% hint style="info" %}
INFO

Both **Agents** and **Connectors** must be enabled before users can access Agent Library.
{% endhint %}

{% hint style="warning" %}
WARNING

If either setting is disabled, users will not be able to create, access, or use AI Agents.
{% endhint %}

### Figure 1 — Enable Agents and Connectors

<figure><img src=".gitbook/assets/1 - AL-Advanced Option.png" alt=""><figcaption></figcaption></figure>

### Expected Result

Agent Library is enabled for your organization.

***

#### Step 2 — Grant Access to User Groups

Navigate to **Admin → User Groups**.

For each User Group that should use AI Agents, enable the following permissions:

✓ Agent

✓ Allow Connector

{% hint style="info" %}
INFO

Only members of User Groups with both permissions enabled can create, access, and use AI Agents.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Create separate User Groups for **Administrators**, **Power Users**, and **Standard Users** to simplify permission management.
{% endhint %}

### Figure 2 — User Group Permissions

<figure><img src=".gitbook/assets/2 - AL-User Groups.png" alt=""><figcaption></figcaption></figure>

### Expected Result

Eligible users can now access Agent Library based on their assigned User Group permissions.

## Enable Graice Agents

Graice provides a collection of predefined AI Agents designed for common business functions. Enable an Agent to customize its identity and make it available within your organization's Agent Library.

### What You'll Do

By the end of this guide, you will be able to:

✓ Browse the available Graice AI Agents.

✓ Review Agent details before enabling them.

✓ Enable a Graice Agent for customization.

#### Step 3 — Open Agent Library

Navigate to **AI Studio → Agent Library → All Graice Agents**.

The **All Graice Agents** page displays the collection of predefined AI Agents available in Graice. Each Agent card provides key information to help you select the most appropriate AI assistant for your business.

Each Agent includes:

✓ Agent Name

✓ Purpose

✓ Business Role

✓ Enable action

{% hint style="info" %}
INFO

Predefined Graice Agents are ready-to-use templates that accelerate Agent deployment across your organization.
{% endhint %}

{% hint style="success" %}
IMPORTANT

After enabling an Agent, you can customize its **Name**, **Purpose**, **Avatar**, **Persona**, **AI Model**, and **Knowledge Base** before assigning it to users.
{% endhint %}

### Expected Result

You can review all available Graice Agents and identify the one that best fits your business requirements.

***

#### Step 4 — Enable an Agent

Locate the Agent you want to use and click **USE**.

The **Agent Configuration** window opens, allowing you to customize the Agent before it is added to **My Agents**.

{% hint style="success" %}
BEST PRACTICE

Select an Agent based on its intended business role. This minimizes configuration effort and helps users quickly identify the appropriate AI assistant.
{% endhint %}

{% hint style="info" %}
INFO

Enabling an Agent does not automatically assign it to users. User assignment is completed in a later step.
{% endhint %}

### Figure 4.1 — Enable Graice Agent

Agent Configuration window displayed after selecting **USE** for a predefined Graice Agent.

<figure><img src=".gitbook/assets/3 - AL-Agent Library.png" alt=""><figcaption></figcaption></figure>

### Figure 4.2 — Save Graice Agent

Edit the Agent Details and Save it

<figure><img src=".gitbook/assets/4 - AL-Agent Library Edit-Save.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The selected Graice Agent is enabled and ready for customization.

Continue to **Manage Enabled Agents** to review, edit, assign, or remove enabled AI Agents from the **My Agents** workspace.

## Manage Enabled Agents

After enabling a Graice Agent, it is automatically added to the **My Agents** workspace. From here, administrators can review, edit, assign, or remove Agents from a centralized location.

### What You'll Do

By the end of this guide, you will be able to:

✓ Open the My Agents workspace.

✓ Review all enabled AI Agents.

✓ Understand the available management actions.

#### Step 5 — Open My Agents

Navigate to **AI Studio → Agent Library → My Agents**.

The **My Agents** page displays every Agent that has been enabled within your organization. Each Agent card provides quick access to the most common administrative actions.

Each Agent card displays:

✓ Agent Name

✓ Agent Avatar

✓ Purpose

✓ Edit

✓ Assign Admin

✓ Delete

{% hint style="info" %}
INFO

Only enabled Agents appear in the **My Agents** workspace.
{% endhint %}

{% hint style="success" %}
IMPORTANT

If an expected Agent is not listed, verify that it has been enabled from the **All Graice Agents** tab.
{% endhint %}

### Figure 5 — My Agents

<figure><img src=".gitbook/assets/5 - AL-My Agents.png" alt=""><figcaption></figcaption></figure>

### Expected Result

You can view and manage all enabled AI Agents from a centralized workspace.

***

### Available Actions

Use the available actions to manage the lifecycle of an Agent.

#### Edit

Update the Agent configuration, including its Persona, AI Model, Knowledge Base, and other Agent properties.

#### Assign Admin

Assign the Agent to one or more users who should manage or access the Agent.

#### Delete

Remove the Agent from the organization when it is no longer required.

{% hint style="info" %}
BEST PRACTICE

Use clear Agent names, avatars, and purposes so users can quickly identify the correct AI assistant.
{% endhint %}

> WARNING
>
> Deleting an Agent permanently removes it from your organization. Review existing assignments before deleting an Agent.

{% hint style="warning" %}
WARNING

Deleting an Agent permanently removes it from your organization. Review existing assignments before deleting an Agent.
{% endhint %}

### Expected Result

You understand the purpose of each available management action and can manage enabled AI Agents effectively.

## Assign Agents to Users

After configuring an Agent, assign it to the appropriate users so they can access it from the Chat interface. Assignments help ensure users interact with AI Agents that are relevant to their roles and responsibilities.

### What You'll Do

By the end of this guide, you will be able to:

✓ Open the Agent assignment window.

✓ Select one or more users.

✓ Assign the Agent for use in Chat.

#### Step 6 — Open the Assign User Window

Navigate to **AI Studio → Agent Library → My Agents**.

Locate the Agent you want to assign and click the **Assign Admin** icon. This opens the **Add User as Admin** window.

{% hint style="info" %}
INFO

Only users with the required User Group permissions can successfully use an assigned Agent.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Verify that the selected users have access to Agent Library before assigning the Agent.
{% endhint %}

### Expected Result

The user assignment window is ready for selecting users.&#x20;

***

#### Step 7 — Assign User as Admin&#x20;

Select the required user from the dropdown list and click **Done** to save the assignment.

After assignment, the user can:

✓ View the Agent from the **My Agents** menu.

✓ Invoke the Agent using **@** in Chat.

✓ Interact with the Agent based on its configured permissions.

{% hint style="success" %}
BEST PRACTICE

Assign Agents to User Groups based on departments or business functions instead of assigning them individually whenever possible.
{% endhint %}

{% hint style="info" %}
INFO

Assigning an Agent does not change its configuration. Users always interact with the latest saved version of the Agent.
{% endhint %}

### Figure 7 — Set Admin User to an Agent

AI Studio → Agent Library → My Agents → Set User as Admin

Selecting the user and saving the assignment for the selected AI Agent.

<figure><img src=".gitbook/assets/6 - AL-Set Admin.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The selected user can view the Agent on his My Agents List.

## Access Assigned Agents

Users can access all AI Agents assigned to them . The My Agents page provides a centralized view of available Agents, making it easy to select the right assistant for each task.

### What You'll Do

By the end of this guide, you will be able to:

✓ Open the My Agents page.

✓ Review the AI Agents assigned to your account.

✓ Identify the appropriate Agent for your task.

#### Step 8 — Open My Agents

Navigate to **Chat → User Profile → My Agents**.

From the Chat page, click your **User Profile** located in the bottom-left corner and select **My Agents**.

{% hint style="info" %}
INFO

The **My Agents** page displays only the AI Agents assigned to the currently signed-in user.
{% endhint %}

{% hint style="success" %}
IMPORTANT

If you cannot find the **My Agents** option, verify that an administrator has assigned one or more AI Agents to your account.
{% endhint %}

### Figure 8 — My Agents Page

Chat → User Profile → My Agents

The **My Agents** page displaying all AI Agents assigned to the currently signed-in user.

<figure><img src=".gitbook/assets/8 - AL-User My Agent - Settings.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The **My Agents** page opens and displays all AI Agents assigned to your account.

***

## Configure Agent Properties

Configure an Agent to define its identity, behavior, AI capabilities, and knowledge sources. The Agent Configuration page centralizes all settings required to customize how an AI Agent interacts with users.

### What You'll Do

By the end of this guide, you will be able to:

✓ Open the Agent Configuration page.

✓ Access all Agent settings from a single workspace.

✓ Prepare the Agent for advanced configuration.

#### Step 9 — Perform Agent Configuration

Navigate to **AI Studio → Agent Library → My Agents**.

Locate the Agent you want to configure and click the **Edit** icon.

The **Agent Configuration** page opens, where you can manage all Agent settings from a centralized workspace.

{% hint style="info" %}
INFO

The Agent Configuration page centralizes all settings required to customize an AI Agent before it is assigned to users.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Only users with the appropriate administrative permissions can modify Agent configurations.
{% endhint %}

### Expected Result

The Agent Configuration page opens and is ready for customization.

***

### Available Configuration Sections

The configuration page is organized into the following sections:

✓ **Basic Properties** — Update the Agent Name, Avatar, and Purpose.

✓ **Persona** — Define the Agent's behavior, tone, and instructions.

✓ **AI Model** — Select the Large Language Model (LLM) used by the Agent.

✓ **Knowledge Base** — Connect one or more DocRooms to provide contextual responses.

{% hint style="success" %}
BEST PRACTICE

Complete the Agent configuration before assigning it to users. This ensures everyone interacts with a fully configured AI assistant.
{% endhint %}

{% hint style="info" %}
INFO

Changes made to an Agent take effect after the configuration is saved.
{% endhint %}

### Expected Result

You understand the purpose of each configuration section and are ready to customize the selected AI Agent.

## Configure Basic Properties and Persona

Configure the Agent's identity and behavior to ensure it responds consistently and accurately. Basic Properties define how the Agent appears, while the Persona determines how it communicates and interprets user requests.

### What You'll Do

By the end of this guide, you will be able to:

✓ Configure the Agent's basic information.

✓ Select a Persona for the Agent.

✓ Define Agent Instructions to control the Agent's behavior.

#### Step 10 — Configure Basic Properties

Navigate to **AI Studio → Agent Library → My Agents** and click the **Edit** icon for the Agent you want to configure.

Under the **Basic Properties** section, update the following fields to define the Agent's identity:

✓ Agent Name

✓ Agent Avatar or Logo

✓ Purpose

{% hint style="info" %}
INFO

Basic Properties define how the Agent is presented throughout the Graice platform.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Choose a clear Agent Name and Purpose so users can easily identify the appropriate AI Assistant from the Chat interface.
{% endhint %}

### Figure 10 — Configure Basic Properties

AI Studio → Agent Library → My Agents → Settings

Configure the Agent Name, Agent Avatar or Logo, and Purpose for the selected AI Agent.

<figure><img src=".gitbook/assets/9 - AL-User My Agent - Settings Edit.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The Agent's identity is updated and will be displayed consistently throughout the platform.

***

#### Step 11 — Configure Persona

Scroll to the **Persona** section.

Select an existing **Persona** and provide **Agent Instructions** that define how the Agent should respond to user prompts.

Configure the following fields:

✓ Persona

✓ Agent Instructions

Agent Instructions can be used to define the Agent's:

✓ Tone

✓ Response Format

✓ Business Rules

✓ Domain-Specific Behavior

{% hint style="info" %}
INFO

The selected Persona determines the Agent's communication style, while Agent Instructions provide additional guidance for handling user requests.

You can update the Persona and Agent Instructions at any time without recreating the Agent.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Keep Agent Instructions concise, specific, and task-oriented. Well-written instructions produce more accurate and consistent AI responses.
{% endhint %}

### Expected Result

The Agent now has a defined identity, communication style, and behavioral guidelines.

## Configure AI Model and Knowledge Base

Select the AI Model and connect a Knowledge Base to define how the Agent generates responses. These settings enable the Agent to provide accurate, context-aware answers using your organization's documents.

### What You'll Do

By the end of this guide, you will be able to:

✓ Select the appropriate Large Language Model (LLM).

✓ Connect a DocRoom as the Agent's Knowledge Base.

✓ Save the Agent configuration.

#### Step 12 — Select an AI Model

Under the **AI Model** section, choose the Large Language Model (LLM) that best matches your business requirements.

{% hint style="info" %}
INFO

The selected AI Model determines how the Agent processes prompts and generates responses.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Different Agents can use different AI Models. Choose a model based on the Agent's role rather than using the same model for every Agent.
{% endhint %}

### Expected Result

The selected AI Model is configured and will be used to process prompts for this Agent.

***

#### Step 13 — Connect a Knowledge Base

Scroll to the **Knowledge Base** section.

From the **Select Knowledge Base** list, choose the appropriate **DocRoom**.

A connected DocRoom enables the Agent to:

✓ Search organizational documents.

✓ Retrieve relevant information.

✓ Generate knowledge-grounded responses.

{% hint style="info" %}
INFO

A Knowledge Base allows the Agent to answer questions using documents stored in the connected DocRoom.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Connect only the most relevant DocRoom(s) to improve response quality and reduce unrelated answers.
{% endhint %}

### Expected Result

The selected DocRoom is connected and available as the Agent's Knowledge Base.

***

#### Step 14 — Save Configuration

After reviewing all Agent settings, click **Save** to apply the configuration.

{% hint style="info" %}
INFO

Configuration changes take effect after saving.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Existing users automatically interact with the updated Agent configuration after the changes are saved.
{% endhint %}

### Figure 14 — Save Agent Configuration

Save the Agent configuration after selecting the AI Model and connecting the Knowledge Base.

<figure><img src=".gitbook/assets/10 - AL-User My Agent - Settings Edit2.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The Agent is fully configured and ready to be assigned and used in Chat.

## Use Agents in Chat

After an Agent has been configured and assigned, you can invoke it directly within a chat conversation. Use the **@** symbol to quickly select the appropriate AI Agent and receive role-specific responses.

### What You'll Do

By the end of this guide, you will be able to:

✓ Create a new chat thread.

✓ Open the Agent selection menu.

✓ Select an AI Agent for the conversation.

#### Step 15 — Create a New Chat

Navigate to **Chat**.

Click **Create Chat Thread** to start a new conversation.

A new chat thread opens, allowing you to begin interacting with an AI Agent.

{% hint style="info" %}
INFO

A new chat thread provides a dedicated workspace for interacting with an AI Agent.
{% endhint %}

### Expected Result

A new chat thread is created and ready to receive your prompt.

***

#### Step 16 — Open the Agent Menu

In the message input box, type **@** to display the Agent selection menu.

The Agent menu displays:

✓ Available AI Agents

✓ Available LLM Models

{% hint style="info" %}
INFO

The **@** menu allows you to quickly select an AI Agent without leaving the current conversation.
{% endhint %}

{% hint style="success" %}
IMPORTANT

Only AI Agents assigned to your account are displayed in the Agent menu. If an expected Agent is missing, contact your administrator.
{% endhint %}

### Expected Result

The Agent selection menu opens and displays all AI Agents available to your account.

***

#### Step 17 — Select an AI Agent

Choose the required AI Agent from the dropdown list.

The selected Agent is attached to the current conversation and will process all subsequent prompts until another Agent is selected.

{% hint style="info" %}
BEST PRACTICE

Select the Agent whose purpose best matches your task. For example, use an HR Agent for HR policies or a Legal Agent for compliance-related questions.
{% endhint %}

{% hint style="info" %}
INFO

You can switch to another Agent at any time by selecting a different Agent from the **@** menu.
{% endhint %}

### Figure 17 — Select an AI Agent

Selecting an AI Agent from the **@** menu to associate it with the current conversation.

<figure><img src=".gitbook/assets/11 - AL-Chat - Select Agent.png" alt=""><figcaption></figcaption></figure>

### Expected Result

The selected AI Agent is attached to the current chat thread and is ready to generate responses.

## Interact with an AI Agent

After selecting an AI Agent, submit your prompt to receive contextual, role-specific responses. Responses are generated using the Agent's configured Persona, AI Model, Agent Instructions, and connected Knowledge Base.

### What You'll Do

By the end of this guide, you will be able to:

✓ Submit a prompt to the selected AI Agent.

✓ Review the AI-generated response.

✓ Understand how Agent configuration influences responses.

#### Step 18 — Submit Your Prompt

Navigate to an existing chat thread where an AI Agent has already been selected.

Type your question or request in the message input box and click **Send**.

The selected AI Agent processes your prompt using its configured settings.

{% hint style="info" %}
INFO

Every prompt is processed using the selected Agent's Persona, AI Model, Agent Instructions, and connected Knowledge Base.
{% endhint %}

{% hint style="success" %}
IMPORTANT

The selected Agent processes only the prompts submitted after it has been attached to the current conversation.
{% endhint %}

### Figure 18 — Submit a Prompt

Submitting a prompt to the selected AI Agent from the Chat interface.

<figure><img src=".gitbook/assets/12 - AL-Send Prompt.png" alt=""><figcaption></figcaption></figure>

### Expected Result

Your prompt is submitted successfully and is processed by the selected AI Agent.

#### Step 19 — Review the AI Response

After processing your request, the AI Agent generates a response based on its configured AI Model, Persona, Agent Instructions, and connected DocRooms.

Depending on its configuration, an Agent can:

✓ Answer general business questions.

✓ Search connected DocRooms.

✓ Retrieve relevant organizational knowledge.

✓ Generate context-aware responses.

✓ Follow role-specific instructions and business rules.

Review the response to verify that it addresses your request.

{% hint style="info" %}
INFO

Responses are generated using both the Agent's configuration and the information available in the connected Knowledge Base.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Ask clear, specific questions and provide sufficient context to help the Agent generate more accurate and useful responses.
{% endhint %}

### Figure 19 — AI Agent Response

The AI Agent generates a contextual, knowledge-grounded response based on the selected Agent's configuration.

<figure><img src=".gitbook/assets/13 - AL-Result.png" alt=""><figcaption></figcaption></figure>

### Expected Result

You receive an AI-generated response tailored to your request and the Agent's configured Persona, AI Model, Agent Instructions, and Knowledge Base.

### Understanding Response Quality

The quality of an AI Agent's responses depends on multiple configuration settings working together.

Response quality is influenced by:

✓ Selected AI Model

✓ Configured Persona

✓ Agent Instructions

✓ Connected Knowledge Base

✓ Available information within connected DocRooms

{% hint style="info" %}
INFO

Updating any of these configuration settings may change how the Agent responds to future prompts.
{% endhint %}

## Troubleshooting

This section helps you resolve common issues that may occur while configuring, assigning, or using AI Agents. It also includes best practices to help you maintain reliable, accurate, and efficient AI Agent experiences across your organization.

### Common Issues

#### Agent is not visible

If an expected AI Agent is not available in the Agent Library or Chat interface, verify the following:

✓ The Agent has been enabled from **All Graice Agents**.

✓ The Agent has been assigned to the appropriate user.

✓ The user's User Group has the required **Agent** and **Allow Connector** permissions enabled.

{% hint style="info" %}
INFO

Users can only access AI Agents that have been assigned to their account.
{% endhint %}

### Resolution

Confirm the Agent is enabled, assigned to the correct users, and that the required User Group permissions are configured.

***

#### Knowledge Base responses are missing

If the AI Agent is unable to answer questions using organizational documents, verify the following:

✓ The correct DocRoom has been connected.

✓ The required documents exist within the connected DocRoom.

✓ The Agent configuration has been saved after connecting the Knowledge Base.

{% hint style="info" %}
INFO

AI Agents can only retrieve information from the DocRooms connected to their Knowledge Base.
{% endhint %}

### Resolution

Connect the correct DocRoom and ensure it contains the documents required by the AI Agent.

***

#### Unexpected responses

If an AI Agent generates responses that are inaccurate or inconsistent, review the following configuration:

✓ Persona

✓ Agent Instructions

✓ AI Model

✓ Connected Knowledge Base

{% hint style="info" %}
INFO

Response quality depends on the combined configuration of the Persona, AI Model, Agent Instructions, and Knowledge Base.
{% endhint %}

### Resolution

Update the Agent configuration, save the changes, and test the Agent again with representative prompts.

***

