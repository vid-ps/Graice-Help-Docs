---
description: >-
  The User Agent Skills provides predefined AI skills for different business
  roles and tasks, with controlled access and configuration.
---

# User agent skills

#### Overview

User Agent Skills provides predefined AI agent skills designed for different business roles, tasks, and use cases.

Each skill represents a unique persona and skill set. These skills can use connected third-party tools (connectors) to provide users with access to external systems and data.

Administrators can control which User Groups can access and operate each skill and can enable, disable, configure, or pause individual skills as required.

#### What You'll Learn

By the end of this guide, you will understand how to:

✓ Enable **Agents** and **Connectors** from Advanced Options.

✓ Configure **Agent** and **Allow Connector** permissions for User Groups.

✓ Access the **User Agent Skills** page.

✓ Review predefined User Agent Skills and their available configuration options.

✓ Assign User Groups to a User Agent Skill.

✓ Allow users belonging to selected User Groups to access and operate a skill.

✓ Activate and configure an assigned User Agent Skill.

✓ Select the appropriate LLM and Knowledge Base for a skill.

✓ Connect and enable the required connectors.

✓ Use the configured User Agent Skill in Chat.

{% hint style="info" %}
INFO

User Agent Skills must be configured and assigned by an administrator before users can access and operate them.
{% endhint %}

***

### Step 1 — Enable Agents and Connectors

Before configuring User Agent Skills, the administrator must enable both **Agents** and **Connectors** from **Advanced Options**.

#### Navigate to Advanced Options

Go to:

**Settings → Admin → Advanced Options**

On the **Advanced options** page, locate the following sections:

✓ **Connectors**

✓ **Agents**

#### Enable Connectors

Under the **Connectors** section, turn ON the **Enable Connectors** toggle.

Connectors allow Graice to integrate with and manage third-party services from a single place.

#### Enable Agents

Under the **Agents** section, turn ON the **Enable Agents** toggle.

Agents provide the AI automation capabilities required to operate User Agent Skills.

#### Figure 1 — Enable Agents and Connectors

<figure><img src=".gitbook/assets/1. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
IMPORTANT

Both **Connectors** and **Agents** must be enabled to use integration and AI automation features.
{% endhint %}

#### Expected Result

The **Agents** and **Connectors** features are enabled and ready for the User Groups Assignment.

***

### Step 2 — Configure User Group Permissions

After enabling Agents and Connectors, configure the required permissions for the User Groups that should be allowed to access and operate User Agent Skills.

#### Navigate to User Groups

Go to:

**Settings → Admin → User Groups**

The **User groups** page displays the available User Groups.

#### Select a User Group

Select the User Group for which you want to configure Agent access.

After selecting the group, its permissions are displayed on the right side.

#### Enable Agent Permission

Under the **Agent** section, turn ON the **Agent** toggle.

This enables Agent capabilities for members of the selected User Group.

#### Enable Allow Connector Permission

Turn ON the **Allow Connector** toggle.

This allows members of the selected User Group to connect and manage third-party services required by the Agent.

#### Figure 2 — Configure User Group Permissions

<figure><img src=".gitbook/assets/2. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
INFO

Enable both **Agent** and **Allow Connector** permissions for User Groups that need to access and operate User Agent Skills with connected tools.
{% endhint %}

{% hint style="warning" %}
WARNING

Users must belong to a User Group with the required Agent permissions before they can access and operate the corresponding User Agent Skills.
{% endhint %}

#### Expected Result

The selected User Group has the required permissions to use Agent capabilities and connected third-party services.

***

### Step 3 — Open User Agent Skills

After enabling the required features and User Group permissions, open the **User Agent Skills** page.

#### Navigate to User Agent Skills

Go to:

**Settings → AI Studio → User Agent Skills**

From the left sidebar, click **User Agent Skills**.

The **User Agent Skills** page opens on the right side.

The **graice Agent Skills** tab is opened by default.

#### graice Agent Skills

The **graice Agent Skills** tab displays all predefined User Agent Skills available in Graice.

Each skill represents a different persona and skill set designed for a specific purpose or business role.

Each skill can also have connected third-party tools, also referred to as **connectors**, that allow the skill to access external systems and data.

#### User Agent Skill Information

Each skill can provide information such as:

✓ **Skill Name**

✓ **Purpose**

✓ **Status**

✓ **Required Tools**

✓ **Optional Tools**

✓ **Configuration Options**

#### Available Actions

Administrators can perform the following actions for each User Agent Skill:

✓ **View Configuration** — View the configuration of the skill.

✓ **Edit Skill** — Edit the skill configuration.

✓ **Assign User Groups** — Assign User Groups that should have access to the skill.

✓ **Pause Skill** — Temporarily make the skill inactive.

#### Enable / Disable Toggle

Each skill includes an **Enable / Disable** toggle.

Use this toggle to control whether the skill can be accessed and operated by users and groups.

✓ **Enabled** — Allows authorized users and groups to access and operate the skill.

✓ **Disabled** — Completely disallows the skill from being accessed and operated.

#### Figure 3 — User Agent Skills Main Page

<figure><img src=".gitbook/assets/3. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
INFO

The **graice Agent Skills** tab is opened by default and displays the predefined User Agent Skills available in Graice.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Review the purpose, available tools, and configuration of a skill before assigning it to User Groups. This helps ensure that users receive skills that are relevant to their business responsibilities.
{% endhint %}

#### Expected Result

The **User Agent Skills** page is open and the predefined skills are displayed.

You can now review and manage individual skills and assign them to the appropriate User Groups.

***

### Step 4 — Assign User Groups to a Skill

To allow users to access and operate a User Agent Skill, the administrator must first enable the skill and then assign the required User Groups.

All users belonging to the selected User Groups will be able to access and operate the assigned skill.

#### Enable the Skill

Locate the User Agent Skill that you want to make available.

Turn ON the skill's **Enable / Disable** toggle.

The skill is now enabled.

#### Open Assign Group

Click the **User Groups** icon for the selected skill.

The **Assign Group** popup opens.

The popup displays the User Groups that can be assigned to the selected skill.

#### Assign User Groups

In the **Assign Group** popup, turn ON the toggle for each User Group that should be allowed to access and operate the selected skill.

All users belonging to an enabled User Group will be able to access and operate the skill.

#### Required Connectors

The Assign Group popup can also display the connectors required by each User Group for the selected skill.

Required connectors must be enabled before the corresponding User Group can be granted access.

{% hint style="warning" %}
WARNING

If a User Group does not have all the required connectors enabled, the group cannot be enabled for access to the selected skill until the required connectors are configured.
{% endhint %}

#### Figure 4 — Assign User Groups

<figure><img src=".gitbook/assets/4. User agent skills-.png" alt=""><figcaption></figcaption></figure>

#### Save the Assignment

After enabling the required User Groups, click **Done**.

The selected User Groups are now assigned to the skill.

{% hint style="success" %}
IMPORTANT

Only users who belong to the enabled User Groups will be able to access and operate the assigned skill.

If a User Group is disabled in the **Assign Group** popup, users from that group cannot use the skill.
{% endhint %}

#### Expected Result

The selected User Groups are assigned to the User Agent Skill.

Users belonging to those groups can now access and operate the skill, subject to the configured permissions and skill availability.

{% hint style="info" %}
INFO

The User Agent Skills available in **My Agent** depend on the skills enabled by the administrator and assigned to the User Groups to which you belong.
{% endhint %}

***

### Step 5 — Go to My Agent

After the administrator enables and assigns a User Agent Skill to your User Group, you can access the assigned skill from your personal **My Agent** section.

#### Open the Graice Main Page

Go to the main **Graice** page.

At the bottom-left corner of the screen, locate your **User Profile** thumbnail.

#### Open the User Profile Menu

Click your **User Profile** thumbnail.

A context menu opens with several account options.

#### Open My Agent

From the context menu, click **My Agent**.

The **My Agent** section opens and displays the agents and User Agent Skills available to your account.

#### Figure 5 — Open My Agent

<figure><img src=".gitbook/assets/5. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
INFO

The **My Agent** section shows the skills that have been enabled by the administrator and assigned to the User Groups to which you belong.
{% endhint %}

#### Expected Result

The **My Agent** page opens and displays the agents and User Agent Skills available to you.

You can now locate the newly assigned skill.

***

### Step 6 — Locate the Skill in the Inactive Section

When you open **My Agent**, you can see the complete list of agents and User Agent Skills available to your account.

Some agents may already be active and available for use, while newly assigned User Agent Skills appear in the **Inactive** section until you start using them.

#### Review the Active Section

At the top of the page, the **Active** section displays the agents and skills that are already available for use.

These are agents and skills that you have already activated or started using.

#### Locate the Inactive Section

Scroll down to the **Inactive** section.

The Inactive section contains newly assigned agents and skills that have not yet been activated for use.

#### Identify the M\&A Tech Analyst Skill

Locate the **M\&A Tech Analyst** skill.

This skill has been newly assigned to the logged-in user and appears in the **Inactive** section.

The skill displays an **Inactive** badge and a **Use** button.

#### Activate the Skill

Click the **Use** button on the **M\&A Tech Analyst** skill.

Once you click **Use**, the skill is moved from the **Inactive** section to the **Active** section.

The skill can then be used in conversations.

#### Figure 6 — Activate the Newly Assigned Skill

<figure><img src=".gitbook/assets/6. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
IMPORTANT

Agents and skills shown in the **Inactive** section are newly assigned but have not yet been activated for use.

Click **Use** to activate the skill and make it available in the **Active** section.
{% endhint %}

{% hint style="info" %}
NOTE

The **M\&A Tech Analyst** skill shown in the screenshot is newly assigned to the logged-in user and therefore appears in the **Inactive** section.
{% endhint %}

#### Expected Result

The **M\&A Tech Analyst** skill is activated and moved to the **Active** section.

***

### Step 7 — Manage the Skill from the Active Section

After clicking **Use**, the **M\&A Tech Analyst** skill is moved to the **Active** section at the top of the **My Agent** page.

The skill now displays an **Active** badge.

#### Active Skill

The **Active** section contains agents and skills that are available for use.

Locate the **M\&A Tech Analyst** skill in this section.

The skill displays an **Active** status badge.

#### Available Actions

The M\&A Tech Analyst skill provides three primary actions at the bottom of the skill card:

✓ **Settings** — Configure the agent/skill.

✓ **Remove** — Remove the agent/skill from the Active section and move it back to the Inactive section.

✓ **Enable / Disable Toggle** — Control whether the agent/skill can be used in Chat.

#### Settings

Click the **Settings** icon to configure the selected agent/skill.

The configuration page allows you to update the skill's properties and behavior.

#### Remove

Click the **Remove** icon to remove the agent/skill from the Active section.

When removed, the agent/skill is moved back to the **Inactive** section.

#### Enable / Disable Toggle

Use the toggle to control whether the agent/skill can be used in Chat.

✓ **Enabled / Blue** — The user can use the agent/skill in Chat.

✓ **Disabled / Grey** — The agent/skill cannot be used in Chat.

{% hint style="warning" %}
IMPORTANT

Removing an agent/skill from the Active section moves it back to the **Inactive** section.

Disabling the toggle prevents the agent/skill from being used in Chat while it remains in the Active section.
{% endhint %}

#### Figure 7 — Manage an Active Skill

<figure><img src=".gitbook/assets/7. User agent skills-.png" alt=""><figcaption></figcaption></figure>

#### Expected Result

The **M\&A Tech Analyst** skill is available in the Active section and can be configured, removed, or enabled/disabled as required.

***

### Step 8 — Configure the Agent / Skill

After activating the skill, configure it according to your requirements.

Click the **Settings** icon on the **M\&A Tech Analyst** skill card.

The skill configuration page opens.

#### Configure the Skill Identity

The configuration page allows you to update the basic identity and behavior of the agent/skill.

You can configure:

✓ **Photo / Logo**

✓ **Agent Name**

✓ **Purpose**

✓ **Persona**

✓ **Instructions**

#### Change Photo / Logo

The **Photo** section allows you to upload a logo or image for the agent/skill.

The screenshot indicates that the supported image formats are:

✓ JPG

✓ PNG

The maximum supported image size shown in the interface is **2 MB**.

#### Update Agent Name

Use the **Agent name** field to change the name of the agent/skill.

Choose a clear and meaningful name so users can easily identify the correct agent in Chat.

#### Define Purpose

The **Purpose** field defines the primary purpose of the agent/skill.

This helps users understand what the agent is designed to do.

#### Configure Persona and Instructions

The **Persona** section defines the core behavior, bio, and personality of the AI agent.

Select the appropriate **Persona** from the available options.

Use the **Instructions** field to provide detailed instructions that define how the AI agent should think, behave, and respond to user queries.

Agent instructions can be used to define:

✓ Response behavior

✓ Communication style

✓ Business rules

✓ Domain-specific behavior

✓ Other instructions required for the agent

#### Save the Changes

After making the required changes, click **Save**.

The updated configuration is applied to the agent/skill.

#### Figure 8 — Configure Basic Properties and Persona

<figure><img src=".gitbook/assets/8. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
BEST PRACTICE

Provide clear and detailed instructions when configuring the agent/skill. Well-defined instructions help the AI agent provide more accurate and consistent responses.
{% endhint %}

{% hint style="info" %}
NOTE

Make sure to click **Save** after making changes to apply the updated configuration to the agent/skill.
{% endhint %}

#### Expected Result

The basic properties, persona, and instructions of the **M\&A Tech Analyst** skill are updated and saved.

***

### Step 9 — Select the LLM Model and Knowledge Base

After configuring the basic properties and persona, select the appropriate AI model and Knowledge Base for the agent/skill.

#### Configure the LLM Model

Locate the **Model** section.

The Model section allows you to select the AI model that the agent will use to respond to user queries and process the configured instructions.

Open the **Model** dropdown and select the appropriate LLM.

The selected model powers the agent's responses.

#### Configure the Knowledge Base

Locate the **Knowledge base** section.

A Knowledge Base gives the agent the ability to access relevant information and use that information when responding to queries and making decisions.

Open the **Select Knowledge Base** dropdown.

Select the appropriate **Knowledge Base / DocRoom** that the agent should use.

For example, the screenshot shows:

**Doc Storage Room**

#### Why the Model and Knowledge Base Matter

The selected LLM and Knowledge Base directly influence the responses generated by the agent.

✓ The **LLM Model** determines the AI model used to process and respond to the user's request.

✓ The **Knowledge Base / DocRoom** provides the agent with relevant information and organizational knowledge.

{% hint style="info" %}
IMPORTANT

Selecting the appropriate **Model** and **Knowledge Base** is important for getting accurate, relevant, and context-aware responses from the agent.
{% endhint %}

#### Save the Changes

After selecting the required Model and Knowledge Base, click **Save**.

#### Figure 9 — Select LLM Model and Knowledge Base

<figure><img src=".gitbook/assets/9. User agent skills-.png" alt=""><figcaption></figcaption></figure>

#### Expected Result

The selected LLM Model and Knowledge Base are configured for the **M\&A Tech Analyst** skill.

***

### Step 10 — Connect and Enable Connectors

The final configuration step is to connect and enable the connectors required by the agent/skill.

Connectors allow the agent to use connected third-party tools and data sources during conversations.

#### Open the Connectors Section

In the agent/skill configuration page, locate the **Connectors** section.

The Connectors section displays the tools and apps available for the agent/skill.

The screenshot shows examples such as:

✓ **Google Sheet**

✓ **Market Data**

#### Enable a Connector

Each connector has an **Enable / Disable** toggle.

Use the toggle to control whether the connector is available to the agent/skill.

✓ **Enabled / Blue** — The connector is enabled and available for the agent/skill during conversations.

✓ **Disabled / Grey** — The connector is disabled and cannot be used by the agent/skill.

#### Connect or Disconnect a Connector

The configuration page also provides a **Connect / Disconnect** option for each connector.

If the connector is connected, the user can enable and use it in the conversation.

If the connector is disconnected, the user cannot use it in the conversation.

#### Connector Workflow

The connector must first be connected before it can be enabled for use.

The workflow is:

**Connect Connector → Enable Connector → Use Connector in Conversation**

#### Save the Configuration

After configuring the required connectors, click **Save** to apply the changes.

#### Figure 10 — Configure Connectors

<figure><img src=".gitbook/assets/10. User agent skills-.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
IMPORTANT

A connector must be **connected** before it can be enabled and used by the agent/skill in a conversation.

If the connector is disconnected, the user cannot use that connector in the conversation.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Connect only the tools and data sources that are relevant to the agent/skill.

This helps the agent provide accurate, context-aware, and efficient responses.
{% endhint %}

#### Expected Result

The required connectors are connected and enabled for the **M\&A Tech Analyst** skill.

The agent/skill is now configured with:

✓ Basic properties

✓ Persona and Instructions

✓ LLM Model

✓ Knowledge Base

✓ Required Connectors

### Use the Configured User Agent Skill

The agent/skill has now been successfully added, enabled, assigned, and configured.

The required connectors are connected and enabled for the **M\&A Tech Analyst** skill.

The agent/skill is now configured with:

✓ Basic properties

✓ Persona and Instructions

✓ LLM Model

✓ Knowledge Base

✓ Required Connectors

{% hint style="info" %}
NEXT STEP

The agent/skill is now successfully added, activated, assigned, and configured.

You can now use the configured **M\&A Tech Analyst** skill in Chat to submit prompts and receive AI-generated responses.
{% endhint %}

#### Step 11 — Select the Agent and Submit Your Prompt

Now move to the main **Graice Chat** screen.

In the text prompt field, select the agent/skill that you have just configured.

Type **@** and select **M\&A Tech Analyst** from the available Agent list.

Then enter the question or request that you want the agent/skill to process.

Click the **Send** icon to submit the prompt.

{% hint style="info" %}
INFO

Make sure **M\&A Tech Analyst** is selected as the active agent/skill before submitting the prompt.

The prompt will be processed using the configuration of the selected agent/skill.
{% endhint %}

#### Figure 11 — Select Agent and Submit Prompt

<figure><img src=".gitbook/assets/11. User agent skills-.png" alt=""><figcaption></figcaption></figure>

Selecting the configured **M\&A Tech Analyst** agent/skill, entering a prompt, and submitting the request.

#### Expected Result

The prompt is successfully submitted to the selected **M\&A Tech Analyst** agent/skill.

The agent begins processing the request using its configured settings.

***

#### Step 12 — Process the Prompt and Generate the Response

Once the prompt is submitted, the selected **M\&A Tech Analyst** agent/skill processes the request.

The agent uses all of its configured parameters and available resources to understand and respond to the prompt.

These include:

✓ Configured Persona

✓ Persona Instructions

✓ Selected LLM Model

✓ Selected Knowledge Base

✓ Connected and enabled Connectors

✓ Other configured agent/skill settings

The agent processes the prompt using these settings and generates a response based on the available information.

{% hint style="info" %}
INFO

The selected agent/skill uses its configured Persona, Instructions, LLM Model, Knowledge Base, and connected tools to process the user's request and generate a contextual response.
{% endhint %}

#### Figure 12 — Agent Processing and Response

<figure><img src=".gitbook/assets/12. User agent skills-.png" alt=""><figcaption></figcaption></figure>

The selected **M\&A Tech Analyst** agent/skill processes the user's prompt using its configured parameters and delivers the generated response in Chat.

#### Expected Result

The AI-generated response is displayed in the Chat interface.

The response is generated using the configured **M\&A Tech Analyst** agent/skill and its:

✓ Persona and Instructions

✓ Selected LLM Model

✓ Knowledge Base

✓ Connected Connectors

✓ Other configured settings

The user can continue the conversation by submitting additional prompts or follow-up questions to the selected agent/skill.

{% hint style="success" %}
SUCCESS

The **User Agent Skills** workflow is now complete.

The agent/skill has been successfully added, enabled, assigned to the required user groups, configured, and used to process a user prompt and generate an AI-powered response.
{% endhint %}
