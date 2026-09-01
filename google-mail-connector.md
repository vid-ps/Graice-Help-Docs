---
description: >-
  The Google Mail Connector allows users to connect their Gmail account with
  Graice, enabling AI Agents and Skills to access and retrieve supported Gmail
  information.
---

# Google Mail Connector

**Overview**

The **Google Mail Connector** allows Graice to connect with a user's Google Mail account.

Once the connector is enabled, assigned to the appropriate User Groups, and connected to a user's Google Account, it can be made available to authorized AI Agents and Skills.

The connected Agent or Skill can then use the Google Mail Connector to access Gmail information and perform supported email-related actions based on the permissions granted during the connection process.

The Google Mail Connector can be used as part of Graice's broader **Connectors** feature, which allows third-party services and tools to be connected with the Graice platform.

**What You'll Learn**

By the end of this guide, you will understand how to:

✓ Enable the **Google Mail Connector**.

✓ Assign the Google Mail Connector to one or more User Groups.

✓ Allow users in assigned User Groups to access the connector.

✓ Open the personal **Connectors** page.

✓ Connect the Google Mail Connector to a Google Account.

✓ Review the requested access permissions.

✓ Confirm that the Google Mail Connector is successfully connected.

✓ Enable the connector for one or more AI Agents or Skills.

✓ Use an AI Agent or Skill to retrieve information from the connected Google Mail account.

✓ Submit different Gmail-related prompts to retrieve email information.

{% hint style="info" %}
INFO

The Google Mail Connector must first be enabled and assigned to the appropriate User Groups before authorized users can connect it to their Google Account.
{% endhint %}

***

#### Step 1 — Enable the Google Mail Connector

Before users can connect their Google Mail accounts, an administrator must enable the **Google Mail Connector** from the Connectors page.

**Navigate to Connectors**

Go to:

**Settings → AI Studio → Connectors**

The **Connectors** page displays the available third-party services that can be connected to Graice.

These connectors are organized into different categories, such as:

✓ File Storage

✓ Documents

✓ Communication

✓ Other available service categories

**Locate Google Mail**

Scroll to the **Communication** section.

Locate **Google Mail** in the list of available connectors.

**Enable Google Mail**

Turn ON the toggle beside the **Google Mail** connector.

When the toggle is turned ON, the Google Mail Connector is enabled and becomes available for further configuration.

{% hint style="info" %}
INFO

Enabling the Google Mail Connector makes it available to be assigned to the required User Groups.
{% endhint %}

#### Figure 1 — Enable the Google Mail Connector

Navigate to the **Connectors** page, locate **Google Mail** under the **Communication** section, and turn ON the toggle.

<figure><img src=".gitbook/assets/1. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The **Google Mail Connector** is enabled and ready to be assigned to one or more User Groups.

***

#### Step 2 — Assign the Google Mail Connector to User Groups

After enabling the Google Mail Connector, assign it to the User Groups that should be allowed to access it.

**Open Assign Group**

Locate the **Assign Group** icon beside the **Google Mail** connector.

Click the **Assign Group** icon.

The **Assign Group** popup opens.

**Select the Required User Groups**

The popup displays the available User Groups.

Each User Group has a toggle that can be used to control whether that group has access to the Google Mail Connector.

Turn ON the toggle for each User Group that should be assigned access to the connector.

For example, you can assign the connector to:

✓ Super Admin

✓ Owner

✓ Member

✓ Other available User Groups

You can enable one or more User Groups based on your organization's access requirements.

**Save the Group Assignment**

After selecting the required User Groups, click **Done** to save the group assignments.

The selected User Groups are now authorized to access the Google Mail Connector.

{% hint style="info" %}
INFO

Only users belonging to the User Groups assigned to the Google Mail Connector can access and use the connector.
{% endhint %}

{% hint style="success" %}
BEST PRACTICE

Assign the Google Mail Connector only to the User Groups that require access to Gmail functionality. This helps maintain appropriate access control across the organization.
{% endhint %}

#### Figure 2 — Assign the Google Mail Connector to User Groups

Click the **Assign Group** icon, turn ON the required User Group toggles, and click **Done** to save the assignments.

<figure><img src=".gitbook/assets/2. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The Google Mail Connector is successfully assigned to the selected User Groups.

Users who belong to these assigned User Groups can proceed with connecting the Google Mail Connector to their own Google Account.

{% hint style="success" %}
SUCCESS

The Google Mail Connector is now enabled and assigned to the required User Groups.

Authorized users can proceed to the next step and connect the Google Mail Connector to their Google Account.
{% endhint %}

#### Step 3 — Open Your Personal Connectors

After the Google Mail Connector has been enabled and assigned to the appropriate User Groups, the user must connect the connector to their personal Google Account.

**Navigate to My Profile**

From the **Main Chat** page, click your user profile image located in the bottom-left corner.

From the available menu, click:

**My Profile**

The **My Profile** page opens.

**Open Connectors**

Under **My Profile**, click:

**Connectors**

The **Connectors** page displays the third-party connectors that are available to the logged-in user.

These are the connectors that have been assigned to the user's User Group.

**Locate Google Mail**

Locate the **Google Mail** connector under the **Communication** section.

Click the **Connect** button beside the Google Mail Connector.

This starts the process of connecting the Google Mail Connector to your Google Account.

{% hint style="info" %}
INFO

The connectors displayed on the personal Connectors page are based on the access permissions assigned to the logged-in user.
{% endhint %}

#### Figure 3 — Open and Connect Google Mail

Go to **My Profile → Connectors**, locate **Google Mail**, and click **Connect**.

<figure><img src=".gitbook/assets/3. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The Google Account connection process starts.

The user is redirected to the Google sign-in or account selection page.

***

#### Step 4 — Select Your Google Account

After clicking **Connect**, Graice starts the process of connecting the Google Mail Connector to your Google Account.

Google displays the available account options.

**Select a Google Account**

If you are already signed in to one or more Google Accounts, the available accounts are displayed on the screen.

Click the Google Account that you want to connect to the Google Mail Connector.

The selected Google Account will be used to connect Gmail with Graice.

{% hint style="info" %}
INFO

If you are not already signed in to a Google Account, Google may ask you to sign in before continuing.
{% endhint %}

**Continue With the Selected Account**

After selecting your Google Account, the Google authorization process continues.

The next screen displays information about the access that Graice requires.

#### Figure 4 — Select Your Google Account

Select the Google Account that you want to use for connecting the Google Mail Connector.

<figure><img src=".gitbook/assets/4. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The selected Google Account is used for the connection process.

The Google access and authorization information is displayed for review.

***

#### Step 5 — Review Access Information and Continue

After selecting your Google Account, Google displays the access information requested by Graice.

Review the information carefully before continuing.

**Review the Requested Access**

The authorization page displays the Google services and permissions that Graice requires to use the Google Mail Connector.

Graice may have access to the following Gmail services:

✓ **View your email messages and settings**

✓ **Send email on your behalf**

✓ **Read, compose and send emails from your Gmail account**

These permissions allow the Google Mail Connector to perform supported Gmail-related actions through authorized Graice Agents and Skills.

**Review Privacy Information**

Before continuing, you can also review the available:

✓ **Privacy Policy**

✓ **Terms of Service**

Review this information to understand how Graice processes and protects your data.

**Continue the Connection**

After reviewing the requested access information, click:

**Continue**

The Google Mail Connector is then authorized to connect with Graice using the selected Google Account.

{% hint style="warning" %}
IMPORTANT

Review the requested permissions carefully before clicking **Continue**.
{% endhint %}

#### Figure 5 — Review Access Information

Review the requested Gmail access permissions, Privacy Policy, and Terms of Service. Then click **Continue** to proceed.

<figure><img src=".gitbook/assets/5. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The Google authorization process is completed.

The Google Mail Connector is connected to Graice using the selected Google Account.

***

#### Step 6 — Confirm the Google Mail Connector Is Connected

After completing the authorization process, you are returned to the **Connectors** page.

The Google Mail Connector now shows that it is successfully connected.

**Verify the Connection**

Locate the **Google Mail** connector under the **Communication** section.

The **Connect** button is replaced with a **Disconnect** button.

The **Disconnect** button indicates that the Google Mail Connector is successfully connected to your Google Account.

**Disconnect When Required**

You can click **Disconnect** at any time if you want to disconnect the Google Mail Connector from Graice.

{% hint style="info" %}
INFO

Disconnecting the connector removes the connection between the Google Mail Connector and the connected Google Account.
{% endhint %}

**Use the Connector With Agents and Skills**

Once the Google Mail Connector is connected, it can be made available to your authorized AI Agents or Skills.

The connector must be enabled from the configuration settings of the specific Agent or Skill that needs to use it.

{% hint style="success" %}
SUCCESS

The Google Mail Connector is successfully connected and is ready to be enabled for use with one or more AI Agents or Skills.
{% endhint %}

#### Figure 6 — Google Mail Connector Connected

The **Disconnect** button confirms that the Google Mail Connector is successfully connected.

You can also disconnect the connector at any time or use it with your authorized Agents or Skills.

<figure><img src=".gitbook/assets/6. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The Google Mail Connector is successfully connected to the user's Google Account and is ready to be configured for use with one or more AI Agents or Skills.

***

#### Step 7 — Enable Google Mail Connector for an Agent or Skill

After successfully connecting the Google Mail Connector to your Google Account, you must enable it for the specific Agent or Skill that needs to use Gmail functionality.

**Open the Agent or Skill Configuration**

Go to the settings or configuration page of the Agent or Skill that you want to use with the Google Mail Connector.

The Agent configuration page displays various settings and options that can be customized.

**Locate the Connectors Section**

Locate the **Connectors** section in the Agent or Skill configuration.

The list displays the available connectors for the selected Agent or Skill.

Locate the **Google Mail** connector.

Since the connector is already connected to your Google Account, it is available for use.

**Enable the Google Mail Connector**

Turn ON the toggle beside the **Google Mail** connector.

This makes the Google Mail Connector accessible to the selected Agent or Skill.

The Agent or Skill can now use the connected Google Mail account when processing supported prompts.

**Use the Connector With Multiple Agents or Skills**

The Google Mail Connector can be enabled for one or more Agents or Skills.

To use the same connector with another Agent or Skill:

✓ Open the configuration page of the required Agent or Skill.

✓ Go to the **Connectors** section.

✓ Locate the **Google Mail** connector.

✓ Turn ON the connector toggle.

{% hint style="info" %}
INFO

The Google Mail Connector must be enabled separately for each Agent or Skill that needs access to Gmail functionality.
{% endhint %}

**Save the Configuration**

After enabling the Google Mail Connector, click the **Save** button.

This saves the changes made to the Agent or Skill configuration.

{% hint style="info" %}
IMPORTANT

Make sure to click **Save** after enabling the Google Mail Connector. The configuration changes must be saved before the Agent or Skill can use the connector.
{% endhint %}

#### Figure 7 — Enable Google Mail for an Agent or Skill

Locate the **Google Mail** connector in the Connectors section, turn ON the toggle, and click **Save**.

<figure><img src=".gitbook/assets/7. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The Google Mail Connector is enabled for the selected Agent or Skill.

The configured Agent or Skill is now ready to access the connected Google Mail account when processing supported prompts.

***

#### Step 8 — Send a Prompt to the Agent

The Agent is now configured and ready to use the Google Mail Connector.

You can now move to the main Chat page and send a Gmail-related prompt.

**Open the Main Chat Page**

Navigate to the main Chat page in Graice.

Go to the prompt field at the bottom of the Chat page.

**Select the Agent**

Type **@** in the prompt field.

Select the Agent that has been configured with the Google Mail Connector.

For example:

**@Ava**

Once the Agent is selected, you can enter your prompt.

**Enter a Gmail-Related Prompt**

Enter a prompt requesting information from the connected Google Mail account.

For example, you can ask the Agent to fetch unread emails from your Gmail account.

The Agent processes the request using the connected Google Mail Connector.

**Send the Prompt**

After entering the prompt, click the **Send** icon.

The prompt is then submitted to the selected Agent.

#### Figure 8 — Send a Prompt to the Agent

Select the configured Agent, enter a Gmail-related prompt, and click the **Send** icon.

<figure><img src=".gitbook/assets/8. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The selected Agent receives the prompt and begins processing the request using the configured Google Mail Connector.

***

#### Step 9 — Retrieve Gmail Information

After you submit the prompt, the selected Agent or Skill processes your request.

The Agent uses the Google Mail Connector to access the connected Google Mail account and retrieve the requested information.

For example, if the prompt requests unread emails, the Agent can retrieve and display the available unread emails from the connected Google Mail account.

The response is displayed directly in the Chat conversation.

{% hint style="info" %}
INFO

The information returned by the Agent depends on the prompt you provide and the Gmail information available through the connected Google Mail account.
{% endhint %}

**Try Other Gmail Prompts**

You can also ask the Agent to retrieve different types of Gmail information.

For example:

✓ **Fetch my 10 latest Gmail emails with sender, subject, date**

✓ **Fetch all unread Gmail emails from the last 7 days with sender, subject**

✓ **Fetch all Gmail emails from \[sender] from the last 30 days with date, subject**

Replace **\[sender]** with the name or email address of the sender you want to search for.

{% hint style="info" %}
BEST PRACTICE

Use clear and specific prompts when requesting Gmail information. Including details such as the sender, date range, or type of email can help you retrieve more relevant results.
{% endhint %}

#### Figure 9 — View the Gmail Response

The Agent processes the prompt using the Google Mail Connector and displays the requested Gmail information in the Chat conversation.

<figure><img src=".gitbook/assets/9. Google_Mail_Connector.png" alt=""><figcaption></figcaption></figure>

**Expected Result**

The configured Agent or Skill successfully uses the Google Mail Connector to retrieve information from the connected Google Mail account and provide the response in the Chat conversation.

***

### Google Mail Connector Workflow Complete

The Google Mail Connector has now been successfully configured and used with an AI Agent or Skill.

The complete workflow includes:

✓ Enable the **Google Mail Connector** from **Settings → AI Studio → Connectors**.

✓ Assign the connector to the required **User Groups**.

✓ Open **My Profile → Connectors**.

✓ Connect the Google Mail Connector to the user's Google Account.

✓ Review the requested Google Mail permissions.

✓ Confirm that the connector is successfully connected.

✓ Enable the connector for the required Agent or Skill.

✓ Save the Agent or Skill configuration.

✓ Select the configured Agent from the main Chat page.

✓ Enter and send a Gmail-related prompt.

✓ View the Gmail information returned by the Agent.

{% hint style="success" %}
SUCCESS

The Google Mail Connector is now successfully connected to Graice and can be used by configured Agents or Skills to access supported Gmail information from the connected Google Account.
{% endhint %}
