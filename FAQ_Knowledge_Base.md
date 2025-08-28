---
Title: FAQ Knowledge Base
---

1. Teach AI / Knowledge Base
============================

### Q: What is the "Teach AIˮ section used for?

> A: The Teach AI section allows you to add business-specific
> information to train your AI assistant, making it smarter and more
> aligned with your needs. Check out this video for more information:
> [[https://www.]{.underline}y[outube.com/watch?v=ZNidFNVIXic]{.underline}](https://www.youtube.com/watch?v=ZNidFNVIXic).

### Q: What types of data can I add to teach AI?

> A: You can add various formats, including URLs, DOCX, PDF, TXT, CSV
> (including FAQ files using our template), Shopify store data, Zendesk
> help center content, WordPress knowledge base, and Salesforce apps.
> This diverse data input helps train the AI to better respond to
> customer inquiries.

### Q: How do I set up an AI Agent?

> A: Log in to LiveX AI and click "Add New Agentˮ to initialize your AI.
> You can enhance it by uploading various data sources such as:

-   Website URLs (e.g.,
    [[https://livex.ai]{.underline}](https://livex.ai))

-   PDFs, DOCX, TXT, CSV, ZIP files

-   Shopify stores

-   Zendesk help centers

-   WordPress site

-   YouTube videos and channels

-   Salesforce apps

> Wait for the status to change from "Your agent is learningˮ to "Your
> agent is ready.ˮ

### Q: How do I add new business information?

> A: Click the "Add Business Informationˮ button and input relevant
> URLs, documents, or other supported formats to enhance the AIʼs
> knowledge.

### Q: What happens after I add a data source?

> A: Once you add a source, the system processes the content and
> integrates it into the AIʼs knowledge base. You\'ll see a checkmark
> when the data is successfully processed.

### Q: What does the "Priority Documentˮ checkbox do?

> A: The "Priority Documentˮ checkbox allows you to mark certain
> documents as more important for the AI assistant. When selected, the
> document is placed in the priority\_document\_list inside the agentʼs
> configuration. The AI will reference priority documents first when
> generating responses to user questions before checking other
> documents.

### Q: Can I remove or update the information I added?

> A: Yes, You can:

-   Delete a data source by clicking the trash bin icon.

-   Refresh a data source by clicking the reload icon if updates are
    needed.

### Q: What does the "Publishˮ button do?

> A: Clicking **"**Publish**ˮ** makes your AI assistant active with the
> latest data youʼve provided, ensuring itʼs up to date when interacting
> with users.

### Q: How do I know my AI is ready?

> A: The page will display **"**Your Agent is READY**ˮ** in green text,
> confirming that your AI has successfully processed the provided data
> and is ready for deployment.

### Q: What does it mean when it shows "My agent is learning"?

> A: It indicates that the agent is processing and learning the business
> information you have provided so it can respond accurately and
> consistently in future interactions.

### Q: How can I update the contents in the knowledge base?

> A: Add Website URL and set reprocess frequency such as daily, weekly,
> bi- weekly, or monthly; You can also add other format of documents or
> sources in "Teach AIˮ to update contents in knowledge base.
>
> ![](media/image1.jpg){width="6.530087489063867in"
> height="2.847811679790026in"}

### Q: How often will the knowledge base sync?

> A: If this is a website URL, you can choose from "Dailyˮ, "Weeklyˮ,
> "Bi-weeklyˮ, "Monthlyˮ for Reprocess.

### Q: How to upload multiple URLs?

> A: Upload a csv or excel file by clicking "Add Web List Fileˮ in
> "Teach AIˮ section.

![](media/image2.jpg){width="4.89206583552056in"
height="3.0871872265966753in"}

2. Customize
============

## General
-------

### Q: What is the purpose of the "Customizeˮ section?

> A: The "Customizeˮ section allows you to personalize your AI agentʼs
> name, role, language, mode, chat style, greeting messages, branding,
> and interactive behaviors. You can tailor the agentʼs personality and
> responses to align with your business needs.

### Q: How do I save my customizations?

A: Once youʼve made changes, click the "Saveˮ button in the top-right
corner to apply them. If you want to discard changes, click "Discard.ˮ

## Basic Setting
-------------

### Q: What does the "Agent Nameˮ field do?

A: The "Agent Nameˮ field allows you to specify a custom name for your
AI assistant. This name will be displayed in conversations and
throughout the system where the agent is referenced.

### Q: What does the "Agent Roleˮ setting change?

A: The "Agent Roleˮ setting lets you define the primary function of your
AI assistant. You can select predefined roles such as Customer Service,
Sales, Customer Retention, or Custom, depending on your use case.

### Q: What is the "Agent Descriptionˮ field for?

A: The "Agent Descriptionˮ is a short identifier (less than 3 words)
that describes your AI assistant, such as "Eva Botˮ or "Sales AI.ˮ It is
the display name of your AI assistant.

### Q: Can I set my AI agent to respond in different languages?

A: Yes, the AI agent is designed to respond in multiple languages
automatically, so you don\'t need to manually set it for each
conversation. The "Agent Languageˮ setting also allows you to choose a
default language for interactions, including English, Spanish, German,
Korean, Chinese, Hindi, and Japanese.

## Agent Mode
----------

### Q: What are the options in Agent Mode?

A: There are 6 Agent Mode available: Default, Search Bar, Voice, AvatAI
Only, Side App, Full Screen.


## Appearance
----------

### Q: How do I stop the live chatbot from showing the \"1 messageˮ notification when you first see the bot? And how do I set it so it doesnʼt bounce?

A: Turn on "Disable Attention Animation" in appearance within customize.

![](media/image3.jpg){width="6.195275590551181in"
height="4.481248906386702in"}

### Q: How to handle z-index conflict when putting the AI Agent on my website or mobile app? Why is the chatbot blocked by the webpage component? How do I correctly insert the chatbot and search bar into my website?

A: You can find z-index in "Customize → Appearance". The reason that the
chatbot blocked by the webpage component could be invisible overlay or
element with higher z-index and pointer-events is intercepting clicks.
To correctly insert the chatbot *and* search bar, you can apply the Z
Index value from the customization panel to the widget root and a
slightly higher Search Bar Z Index value to the search/dropdown layer.
The recommended z-index default is 100000 (safe high default), Search
Bar Z Index default is 100010 (must be \> widget root so dropdown sits
above chatbox).

### Q: How do I upload a logo for my AI assistant?

A: You can upload a PNG file (under 10MB in the "Agent Logoˮ section to
brand your assistant with your companyʼs image.

### Q: What is the "Agent Button Iconˮ?

A: The "Agent Button Iconˮ is the small image that appears as your chat
widget. You can upload an image under 1MB for customization.

### Q: What does the "Agent Color Customizerˮ do?

A: This tool allows you to adjust the agentʼs visual theme, selecting
from different styles like Professional, Abundant, Enthusiastic, and
Gradient.

### Q: What are the appearances that I can change for my agent?

These are the elements that you can change with ease within the
Customize tab under Appearance.

-   Logo

-   Agent colour

-   Agent button icon

-   Agent button close icon

-   Agent icon

-   Bottom logo

-   Chatbot button style

    -   Top/Bottom/Left/Right alignment

    -   Center alignment

    -   Show/Hide close button

    -   Enable/disable close chat confirmation

    -   Show/hide refresh button

    -   Show/hide chatbot button

    -   Enable/disable draggable chat

    -   Show/hide header

-   Agent message background colour

-   Font style

-   Font size

For more specific customization such as the size of certain elements

## Messages
--------

### Q: What are "Agent Chat Styles,ˮ and how do they affect my AI?

> A: "Agent Chat Stylesˮ determine the tone and personality of your AI
> assistantʼs responses. Options include:

-   Customer Service: Friendly and helpful support-oriented responses.

-   Sales: Focused on engaging customers and providing sales-related
    information.

-   Professional: Formal and polished interactions.

-   Consultative, Casual, Playful: Adjust the agentʼs conversational
    tone to better fit your audience.


### Q: What are "Agent Welcome Questionsˮ?

A: These are predefined questions that are displayed above your Agent
button when you first visit the site. This message will be displayed by
the agent at the start of a conversation.

### Q: How do I change what happens when the agent cannot answer a question?

A: In the "Action to Take When Agent Cannot Answerˮ section, you can
define a fallback action for when the agent is unsure how to respond.
The default setting prompts users for clarification, but you can modify
this to guide users toward additional support options, such as:

-   Redirecting users to relevant knowledge base articles.

-   Escalating the conversation to a live agent.

-   Collecting user details for follow-up

### Q: What are "Promotion Items,ˮ and how do they work?

> A: "Promotion Itemsˮ let you showcase special offers, discounts, or
> product highlights directly through your AI assistant. You can add new
> promotions via the **"**Add Promotion Item**ˮ** button. You can fill
> out fields like title, body, badge title, badge color, button color,
> and the button url to customize each promotion. You can add up to 5
> promotion items.

### Q: What does "Message Splitˮ do?

> A: Enabling "Message Splitˮ will allow the agent to split longer
> messages into shorter and more readable messages.

## Advanced
--------

### Q: What happens when a user clicks "Get More Helpˮ?

> A: You can configure your AI assistant to gather user data for
> follow-up or provide alternative support options. The settings allow
> you to collect name, email, or phone number and optionally integrate
> with HubSpot.

### Q: What is the "Agent Email Alertˮ used for?

> A: The "Agent Email Alertˮ field allows you to enter an email address
> where notifications will be sent whenever a user reaches out for more
> help.

### Q: What does "Interactive Appointment Schedulingˮ do?

> A: This feature enables your AI agent to provide users with a
> scheduling link so they can book a meeting directly through the chat
> interface.

### Q: What does \"Ticketing Platform\" do?

> A: \"Ticketing Platform\" allows you to configure a customer support
> platform to handle customer support tickets. Customer support
> platforms you can choose from include Zendesk, Intercom, Hubspot,
> Salesforce, and Freshdesk.

### Q: What is "Live Chat Availabilityˮ?

> A: "Live Chat Availabilityˮ allows you to set up when users are
> allowed to start a live chat. You can choose from four platforms:
> Zendesk Web Widget, Zendesk Sunshine Conversation, Intercom, and
> Salesforce. In addition, you can set the days, the time range of when
> you want the live chats to take place, the time zone, along with other
> customization options to tailor the chat experience for both customers
> and agents.

### Q: How does \"Agent Navigation Items\" work?

> A: The \"Agent Navigation Items\" feature allows you to customize the
> initial appearance and interactive options of your AI agent\'s chat
> interface by uploading a json. It allows for flexibility.

### Q: How does "Image Searchˮ work?

> A: Enabling "Image Searchˮ allows you to upload images into the search
> bar.

### Q: How do I receive user feedback

> A: Enable the \"User Feedback\". Enabling \"User Feedback\" will allow
> users to rate the agent\'s responses as either good or bad responses.

### Q: How do I upload suggested questions for users to ask?

> A: In the \"Suggested Questions\" section, you can upload a csv/json
> of the list of suggested questions or manually type out the questions.
> If you decide to upload a csv/json, make sure to follow our provided
> templates.

### Q: What does changing the \"LiveX Global Object Name\" do?

> A: Changing the "LiveX Global Object Nameˮ will change the global
> object name for the LiveX AI Agent. For example, setting "LiveX Global
> Object Nameˮ to "coolˮ will change the default global object name from
> "window.livexChatbotˮ (the default) to "window.coolˮ.

### Q: How do I change the length of the AI Agentʼs response?

> A: In the \"Customize\" section under the \"Advanced\" tab, you will
> find the section called \"Response Length.\" Then, enable \"Response
> Length Control\" and enter in the values for the lengths of short,
> medium and long responses.

###  Q: How does "Containsˮ and "Prefixˮ settings of "Auto Completeˮ work?

> A:

-   Prefix Mode**:** Matches words/phrases that start with the input.

-   Contains Mode: Matches words/phrases that include the input anywhere
    within them

### Q: What if I want to limit which type of devices can access our AI Agent?

> A: In the \"Customize\" section under the \"Advanced\" tab, you will
> find a feature called \"Device Availability\". So far, you can only
> enable or disable the AI Agent on mobile devices. The AI Agent is
> always available on other devices like laptops.

3. Workflow
===========

### Q: What is Workflow in LiveX AI?

> A: Workflow allows you to create automated, step-by-step processes for
> handling customer inquiries that require structured responses instead
> of simple Q&A answers.

### Q: How do I create a new Workflow?

> A: Follow these steps:

1.  Navigate to the Workflow tab in the sidebar.

2.  Click "Add Workflowˮ in the top right corner.

3.  Choose between an empty workflow template or the Customer Support
    template.

4.  Enter a Workflow Name that describes its purpose.

5.  Enable "Generate Buttonsˮ and "Show More Helpˮ if needed.

6.  Provide a Description explaining what the workflow does (You can
    provide multiple descriptions if needed).

7.  Use Optional Fields if needed.

8.  Click "Createˮ to save the workflow.

### Q: What should I name my Workflow?

> A: The Workflow name should be clear and informative. For example:

-   "Order Cancellation Processˮ

-   "Subscription Upgrade Assistance

-   "Refund Request Approvalˮ

### Q: How can I use Workflows to automate responses?

> A: Workflows help guide users through multi-step processes by setting
> up text triggers. For example, a user asking "How do I track my
> order?ˮ could trigger a Workflow that:

-   Asks for their Order ID

-   Fetches tracking information

-   Displays the estimated delivery time

### Q: When should I use a Workflow instead of Q&A?

> A: Use Workflows when:

-   The response requires multiple steps (e.g., troubleshooting, return
    processes).

-   You want to automate actions based on user input.

-   A single Q&A response isnʼt sufficient to guide the user.

### Q: Can I update a Workflow after creating it?

> A: Yes, you can edit workflows to refine steps or add automation based
> on real user interactions.

### Q: How can I apply company policies to workflows?

> A: You can define rules within Workflow to ensure compliance with
> company guidelines

4. Tag Management
=================

### Q: What is Tag Management used for?

> A: Tag Management enables teams to categorize customer interactions
> based on topics such as sales, support, and churn reasons. This helps
> businesses track recurring issues, streamline workflows, and automate
> responses. By analyzing tag trends, companies can identify common
> concerns--- for instance, if 80 out of 100 daily user interactions are
> tagged as "order tracking,ˮ it highlights a frequent issue that may
> require further attention and optimization.

### Q: How are tags used in customer support?

> A: Tags are applied based on chat history to help teams analyze trends
> and identify common topics. For example, if "Order Trackingˮ tags
> appear frequently, it indicates that a large number of users are
> inquiring about order tracking, highlighting a potential area of
> concern or interest.

### Q: What are the "Tag Managementˮ categories?

> A: The Tag Management section is divided into three main categories:

-   General: Used for broad customer interactions, such as greetings and
    other general discussions.

-   Churn: Applied to conversations that triggered churn-related
    workflows, such as discussions about cancellations, pricing
    concerns, or dissatisfaction.

-   Ticket: Controls the tags that can be generated for Zendesk tickets,
    helping categorize and manage support requests effectively.

> Users can create their own subcategories or subtags based on specific
> needs by simply clicking "Add New Itemˮ within any category. This
> allows for a flexible and customizable tagging system to better
> organize and analyze different types of customer interactions.

5. Publish
==========

### Q: What is the Agent Link used for?

> A: The Agent Link is a direct web link to your AI assistant, allowing
> for easy access and sharing with others. It can be used to test and
> showcase different AI capabilities, including interactive demos such
> as Avatai Toggle) for avatar-based interactions.

### Q: How do I use the Agent Link?

> A: Simply click on the link to open your AI agent in a browser. You
> can also copy and share it with your team or customers.

### Q: What is the Agent QR Code?

> A: The Agent QR Code is a scannable code that links directly to your
> AI assistant, making it easy to share access without needing to type
> the URL.

### Q: How do I generate a QR Code for my agent?

> A: Select "Generate QR Codeˮ under the Agent QR Code section. Once
> created, you can download and share it. You can also generate a QR
> code from a custom url.

### Q: What is the Zendesk Sidebar App?

> A: The Zendesk Sidebar App allows you to integrate your AI agent into
> Zendesk for easier access within customer support workflows.

### Q: How do I set up the Zendesk Sidebar App?

> A: You can set up the Zendesk Sidebar App in two ways:
>
> ![](media/image4.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Manually: Copy the AI Agent ID from
> this section and paste it into the Zendesk Sidebar App settings.
>
> ![](media/image5.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Via Zendesk Store: Download the app
> from the Zendesk Store, then set it up using your AI Agent ID.

### Q: How do I integrate the AI Agent into my website?

> A: Copy the provided JavaScript code and paste it into your websiteʼs
> HTML
>
> \<head\> section. This will embed the AI agent onto your site.

### Q: Where can I find a tutorial for website integration?

> A: You can follow this tutorial: [[Website Integration
> Guide]{.underline}](https://www.youtube.com/watch?v=4DS8Ahg3Um8).

### Q: Can I integrate the AI Agent into my WordPress site?

> A: Yes! You can add the AI agent to WordPress using a plugin or by
> embedding JavaScript.

### Q: How do I integrate the AI Agent into WordPress?

> A: To integrate the AI Agent into WordPress, follow these steps:

-   Install the "LiveX AIˮ plugin from the WordPress Plugin Directory.

-   Copy the provided JavaScript code and paste it into the plugin
    settings.

-   Save the changes to activate the agent.

-   More details in this tutorial: [[WordPress Integration
    Guide]{.underline}](https://www.youtube.com/watch?v=-VzNwZH04Dw).

### Q: What is Maintenance Mode?

> A: Maintenance Mode temporarily disables the AI agent, making it
> unavailable for users while updates or changes are being made.

### Q: How do I enable or disable Maintenance Mode?

> A: Toggle the switch under Maintenance Mode. When enabled, users will
> not be able to interact with the AI assistant.

### Q: How do I share my AI agent with users?

> A: The Publish section offers multiple options:
>
> ![](media/image6.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Agent Link: Share a direct link to
> your AI agent. ![](media/image5.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} QR Code: Generate a QR code for easy
> access.
>
> ![](media/image7.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Website/WordPress/Shopify
> Integration: Embed your agent into your website.
>
> ![](media/image8.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Search Bar Integration: Allow users
> to query your agent directly from your site\'s search bar
>
> ![](media/image9.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Zendesk Sidebar App: Integrate with
> Zendesk for customer support.

### Q: How can I test my AI agent before publishing?

> A: Use the Demo options one the right side of any of these section
> Teach AI, Customize, Publish) to preview interactions before making
> it public.

6. Conversations
================

### Q: What is the Conversations section used for?

> A: The Conversations section allows you to track and manage
> interactions between users and the AI agent. You can review past
> conversations, monitor resolution statuses, and analyze user
> inquiries.

### Q: How can I search for or filter specific conversations?

> A: Use the search bar at the top to find conversations by keywords
> from the "Topicˮ column. To filter conversations based on other
> columns (e.g., Status, User, Resolution), hover over the column name,
> click the three-dot menu (⋮), and apply a filter according to your
> needs.

### Q: How do I export conversation data?

> A: To export conversation data, use the Export button located at the
> top right of the Conversations panel. You have two options:

-   Select All Conversations: Click the top-left checkbox to select all
    available conversations, then click Export to download the data.

-   Select Specific Conversations: Manually check individual
    conversations you want to export, then click Export to download only
    those selected.

> Ensure that at least one conversation is selected before clicking
> Export, as the button remains disabled when no conversations are
> selected.

### Q: Can I sort conversations based on resolution status?

> A: Yes, click on the Resolution column to sort conversations by
> whether they are resolved or unresolved.

### Q: What does the Selected filter mean?

> A: The Selected filter shows conversations that match specific
> criteria, such as date range or tags.

### Q: How can I export all conversations or only those within a specific time range?

> A: In ALL mode, clicking Export will download all available
> conversations; in "SELECTED" mode, you can specify a Start and End
> date to filter conversations within that range, then click Export All
> to download the filtered data.

### Q: How to share the conversation as a link?

> A: Click the conversation, click to copy the URL on the right up
> corner.

7. Expert Knowledge
===================

### Q: What is Expert Knowledge used for?

> A: Expert Knowledge is a repository where you can store frequently
> asked questions and their corresponding answers. The AI agent can pull
> from this knowledge base to provide accurate responses to users
> automatically.

### Q: How do I add new knowledge to the Expert Knowledge?

> A: Click the **"**Add New Knowledge**ˮ** button, enter a question and
> its corresponding answer, then save it. The AI will use this
> information to respond to relevant user inquiries.

### Q: Can I edit an existing knowledge entry?

> A: Yes, you can. Simply find the entry you want to update, click on
> it, and modify the question or answer as needed.

### Q: How do I delete a knowledge entry?

> A: Select the checkbox next to the entry you want to remove and click
> the
>
> **"**Delete**ˮ** button.

### Q: What happens when I update an entry?

> A: Once updated, the AI will use the latest version of the answer to
> respond to user queries. Previous versions are not retained unless
> manually saved elsewhere.

### Q: How does the AI use Expert Knowledge?

> A: When a user asks a question, the AI searches the knowledge base for
> a matching or similar entry and provides the stored response.

### Q: How does Expert Knowledge interact with uploaded files in "Teach AIˮ?

> A**:** In LiveX AI, "Expert Knowledgeˮ has a higher priority than
> uploaded documents in "Teach AI.ˮ If there is a conflict between an
> answer in Expert Knowledge and one in an uploaded file, the response
> from Expert Knowledge will be used. This ensures that manually curated
> expert answers take precedence over general document-based responses.

### Q: What if the AI does not find a relevant answer?

> A: If no matching knowledge entry exists, the AI may generate a
> response based on other available data or escalate the query to a
> human agent.

### Q: Can I track how often a knowledge entry is used?

> A: Yes, you can track individual knowledge entries in the Business
> Insight  Top Articles section. This section provides analytics on:
>
> ![](media/image10.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Total Views in Date Range: How many
> times a specific knowledge entry has been accessed.
>
> ![](media/image11.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} SSR in Date Range: The self-service
> resolution rate, indicating how effectively the knowledge entry
> resolved user inquiries.

### Q: What does the "Add Sourceˮ button in the Expert Knowledge section do?

> A: The "Add Sourceˮ button in the Expert Knowledge section allows you
> to attach reference links or documents to a knowledge entry.

### Q: What does the "Exportˮ button do?

> A: The "Exportˮ button allows you to download all stored expert
> knowledge in JSON format. The exported file contains structured data,
> including the question, answer, author, timestamp, and sources. This
> format is useful for backup, data migration, or bulk editing before
> re-importing.

8. Business Voice
=================

### Q: What is the purpose of Business Voice?

> A: Business Voice personalizes how your AI agent communicates,
> ensuring consistency in tone and messaging.

### Q: What is the difference between "Expert Knowledgeˮ and "Business Voiceˮ?

> A: While both serve similar functions in enhancing the chatbotʼs
> responses, their purposes differ:
>
> ![](media/image8.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Expert Knowledge is used to fill in
> missing information, typically for FAQs or technical explanations. For
> example, it can be used to explain an error code for a camera.
>
> ![](media/image4.png){width="5.2083333333333336e-2in"
> height="5.207239720034996e-2in"} Business Voice is designed to control
> how the chatbot responds in specific business-related situations. For
> example, if a user asks about a competitorʼs product, the chatbot can
> be instructed not to provide a direct answer but instead recommend the
> companyʼs own product.

9. My Clients
=============

### Q: What is the "My Clientsˮ section used for?

> A: The My Clients section is used to store and manage user information
> when they request additional assistance. When a user selects "Get More
> Helpˮ in a conversation and submits their required details (such as
> name, email, and phone number), their information is saved under My
> Clients. This section helps agents track and follow up with users who
> have opted for further support.

### Q: What is the difference between "Conversationsˮ and "My Clientsˮ?

> A: Conversations store general chat history between users and the
> agent. These records include all interactions regardless of whether
> the user requests additional assistance. My Clients store user data
> only when a user selects "Get More Helpˮ in a conversation and submits
> their required information (such as name, email, and phone number).
> This section is used to manage users who have explicitly provided
> their details for further support.

10. My Files
============

### Q: What is the "My Filesˮ section used for?

> A: The My Files section allows you to review, download, and manage
> files that are already stored in the system.

### Q: What happens when I delete a file?

> A: Deleting a file permanently removes it from your stored files. Make
> sure you have a backup if you need it later.

### Q: How do I download a file?

> A: Select the file you want and click the **"**Download**ˮ** button to
> save it to your local device.

### Q: What does the "Excludedˮ toggle do?

> A: The Excluded toggle allows you to disable a file from being used by
> the AI, but it will still be stored in the system.

### Q: What types of files appear in "My Filesˮ?

> A: This section stores pre-existing documents, videos, and external
> resources linked to the system. Many files may have been uploaded by
> an admin or automatically added from other integrations.

11. Business Insights
=====================

### Q: What is the Self-Service Rate?

> A: The Self-Service Rate is the percentage of total inquiries that
> were resolved by the AI without human intervention.
>
> ![](media/image12.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Formula: Resolved Tickets / All
> Tickets
>
> ![](media/image13.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} A higher percentage means the AI
> agent is successfully handling more inquiries on its own.

### Q: What does "Cost Savingsˮ mean?

> A: Cost Savings estimates the amount of money saved by resolving
> tickets through AI instead of requiring human customer support.

### Q: What are "All Ticketsˮ?

> A: All Tickets represent the total number of inquiries received within
> a selected time period, including both AI-handled and manually
> resolved tickets.

### Q: What are "Resolved Ticketsˮ?

> A: Resolved Tickets refers to the number of inquiries successfully
> answered and closed by the AI agent without human intervention.

### Q: How does Business Insights track subscription cancellations and pauses?

> A: The Business Insights section provides data on user subscription
> actions, including:
>
> ![](media/image14.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Cancellation: When a user selects
> "Cancel,ˮ their subscription is immediately terminated.
>
> ![](media/image15.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Pause: If a user selects "Pause,ˮ
> their subscription is temporarily suspended for a set period (e.g., 1
> month or 3 months) and automatically resumes afterward.
>
> This data helps analyze user retention patterns and decision trends.
> For internal testing purposes, the agent selector may not be necessary
> in Business Insights.

### Q: Can I export Business Insights reports?

> A: Yes, you can click the Export button to download reports for
> further analysis.

### Q: How can I track my AI agentʼs performance over time?

> A: You can use the time filter options Last 24 Hours, 7 Days, 4
> Weeks, 3 Months, Custom) to analyze trends in AI resolution rates and
> effectiveness.

### Q: What are Cancellation Attempts?

> A: Cancellation Attempts refer to the number of customers who have
> initiated a request to cancel their subscription.

### Q: What is Post-Interaction Deflection?

> A: Post-Interaction Deflection is the number of customers who, after
> interacting with the LiveX AI agent, decided not to proceed with their
> subscription cancellation.

### Q: What is the Deflection Success Rate?

> A: The Deflection Success Rate is the percentage of cancellation
> attempts where the AI agent successfully persuaded the customer to
> keep/pause their subscription.
>
> ![](media/image16.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Formula: Post-Interaction Deflection
> / Cancellation Attempts

### Q: What does "Deflectedˮ mean in Business Insights?

> A: "Deflectedˮ means that after interacting with the AI agent, a
> customer chose not to cancel their subscription.

### Q: What does "Not Deflectedˮ mean?

> A: "Not Deflectedˮ means that despite engaging with the AI agent, the
> customer still proceeded with their decision to cancel/pause their
> subscription.

### Q: What are "Churn Reasonsˮ and how do they help?

> A: Churn Reasons show why customers are canceling their subscriptions.
> Each reason (e.g., "Price too high,ˮ "Product issuesˮ) is predefined
> by the business and tracked along with:
>
> ![](media/image17.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Total % Count: The proportion of
> cancellations attributed to each reason.
>
> ![](media/image18.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Cancel vs. Deflect: The percentage of
> customers who actually canceled vs. those who were successfully
> retained.
>
> ![](media/image19.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} By analyzing these trends, businesses
> can identify pain points and take action, such as offering targeted
> discounts, improving service quality, or addressing product concerns.

### Q: What is the "Deflection Breakdown by Churn Reasonˮ?

> A: This section categorizes deflected and non-deflected customers
> based on their reasons for cancellation, helping businesses analyze
> why customers stay or leave.

### Q: What is "Workflow Analyticsˮ?

> A: Workflow Analytics helps you track and understand how different
> predefined workflows are being used in customer interactions. It shows
> you:
>
> ![](media/image20.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} Which workflows were triggered (e.g.,
> cancellations, pauses, order tracking).
>
> ![](media/image20.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} How often each workflow is used
> (total count).
>
> ![](media/image21.png){width="5.2083333333333336e-2in"
> height="5.206146106736658e-2in"} How many cases were resolved vs.
> unresolved to measure efficiency.
>
> This data helps you analyze trends, optimize processes, and improve
> resolution rates.

### Q: What are "Conversation Tagsˮ?

> Conversation Tags are predefined labels used to categorize customer
> interactions based on their topics. These tags help businesses track
> and analyze common issues, making it easier to understand customer
> needs and optimize support.
>
> For example, a business might create tags such as:

-   "Cancel or Reschedule Appointmentˮ: For customers modifying
    bookings.

-   "Support: How to Useˮ: For general usage questions.

-   "Support: Refund Requestˮ: For refund-related inquiries.

> Tags can be automatically assigned by the AI based on predefined tag
> configurations or manually managed by users. This categorization helps
> businesses measure topic frequency, track resolution success, and
> refine customer support strategies for greater efficiency. The
> \"Resolved\" view of the Conversation Tags shows a count of
> successfully closed conversations, broken down by their assigned
> category tag. This helps you understand which types of issues are
> being solved effectively.

### Q: What is the \"Resolvedˮ and "Unresolvedˮ view of "Conversation Tags\"?

> A: The \"Resolved\" view of the Conversation Tags shows a count of
> successfully closed conversations, broken down by their assigned
> category tag. This helps you understand which types of issues are
> being solved effectively. The \"Unresolved\" view of the Conversation
> Tags shows a count of currently open conversations, broken down by
> their assigned category tag. This helps you prioritize and understand
> what types of issues are still pending.

### Q: What is "Channel Breakdown for Unresolved Chatsˮ?

> A: The "Channel Breakdown for Unresolved Chatsˮ chart helps track the
> reasons behind unresolved customer interactions. It categorizes chats
> into different types based on the nature of the issue, allowing
> businesses to analyze where resolutions were unsuccessful and why.
>
> The specific categories and colors used in the chart may vary
> depending on system configurations, but common breakdowns include:

-   Customer requests for further assistance

-   Unanswered or incomplete responses

> By analyzing these trends, businesses can pinpoint recurring issues,
> refine chatbot performance, and improve overall customer support
> efficiency.

### Q: What is the "Unanswered Questionsˮ section?

> A: The "Unanswered Questionsˮ section helps track customer inquiries
> that the bot or agent could not successfully resolve at the time of
> interaction. This is a great tool for:

-   Observing common customer questions that might not have a proper
    response yet.

-   Understanding gaps in the knowledge base where additional FAQs or
    improved responses are needed.

-   Enhancing chatbot training by identifying recurring issues that can
    be automated in the future.

> By analyzing these unanswered questions, businesses can expand their
> knowledge base, refine responses, and improve both bot and agent
> accuracy over time, leading to better customer support and fewer
> unresolved inquiries.

### Q: What is "Conversation Usageˮ and "Message Usageˮ?

> A: Conversation usage refers to the number of conversations the AI
> agent has handled; message usage represents the number of individual
> replies the agent has sent within those conversations. These metrics
> help businesses understand agent engagement and response volume over
> time.

### Q: What is the "Top Topicsˮ system?

> A: The Top Topics system uses an LLM Large Language Model) to analyze
> up to 2,500 conversation topics, clustering and summarizing them based
> on frequency. This helps businesses identify the most commonly
> discussed topics among users, providing a high-level overview of
> recurring customer concerns.

### Q: What are "Top Articlesˮ?

> A: Top Articles showcase the most viewed knowledge base articles
> within a selected date range. These articles are sourced from both
> uploaded files in the Teach AI section and the Expert Knowledge
> section, helping businesses identify the most frequently accessed
> resources for customer inquiries.

### Q: What does "Total Views in Date Rangeˮ mean?

> A**:** It represents the number of times users have accessed a
> particular article within a given time period.

### Q: What does "SSR in Date Rangeˮ mean?

> A**:** SSR (Self-Service Rate) indicates how many user inquiries were
> successfully resolved through articles and sources in knowledge base
> without needing further interaction.

### Q: What does "URL Engagementˮ show?

> A: The \"URL Engagement\" shows businesses from which links the users
> engage the bot or agent. It also shows the percentage of resolved and
> unresolved conversations from each url. This feature helps businesses
> pinpoint which specific website pages cause the most confusion.

### Q: What does \"URL Link Clicks\" show?

> A: \"URL Link Clicks shows the list of the links that the users
> clicked, sorted by clicks. This can help businesses gauge user
> interests and measure the effectiveness of the bot\'s content and
> self-service resources. You can also export a CSV file of these links.

12. Agentflow
=============

 Q: What is the difference between Show Message and Internal Process?
--------------------------------------------------------------------

> A: Show message instructs the voice agent to say exactly what has been
> typed out in the 'Message to Userʼ box while Internal Process uses the
> content in the 'Prompt to Processʼ box to send a prompt to the voice
> agent LLM to process.

 Q: What does the Use Tool Action do?
------------------------------------

> A: The LiveX AI platform has many tools that your agent workflow can
> use to execute processes such as email verification, specific customer
> support live chat, transferring calls to a human agent, and sending
> SMSʼs.

### Q: How can I test my custom Agentflow before releasing it to customers?

> A: In each individual Agentflow page there is a 'Testʼ tab where users
> can preview how their agent behaves by having a conversation with it.

### Q: What are Conditions and Next Steps?

> A: In each step of your agentflow, different outcomes may arise
> depending on the prompt given to the LLM. Conditions and next steps
> let you define specific criteria for these outcomes and determine how
> the workflow should proceed based on those conditions.

### Q: How many conditions can I add for each step?

> A: You can have as many conditions branching out as you would like for
> every step.

### Q: How do I see the prompt given to the LLM at each step?

> A: There is a "Show Prompt Previewˮ tick box at the top of each step.
> You will be able to see the prompt that will be provided to the LLM
> for each step.

### Q: What is Override Prompt?

> A: Override prompt overrides the entire prompt in the "Step Promptˮ.

### Q: What is "Prompt Body"?

> A: Prompt Body overrides the prompt in the "Prompt Bodyˮ.

### Q: What is "Use Rich Text Editorˮ tick box under Step Details?

> A: This option enables a markdown-friendly editor that lets users
> format text, add links, and insert media. It also supports calling
> tools directly within an Internal Process action using the "/ˮ
> command.

### Q: I want to add an extra step in my workflow, how do I do that?

> A: To add an extra step, open the step where youʼd like to make the
> change. Click the "**unlink"** button next to the Condition you want
> to adjust, then insert your new step. After that, link the new step
> back into the workflow so it connects properly with the previous flow.

### Q: How do I link a step back to itself (i.e. loop a step)?

> A: Next to each condition and next step, youʼll see a blue button.
> Click this button repeatedly until it changes to a loop icon. The loop
> icon indicates that the step is now set to loop back to itself.

### Q: What is "Generate Buttons"?

> A: When Generate Buttons is enabled, the agent will automatically
> create response options and display them as clickable buttons. This
> allows users to quickly select a response instead of typing one
> manually.

### Q: How can I add system prompt/Additional instructions for the LLM?

> A: Follow the below steps:

-   Go to the "configˮ section

-   Expand "Optional fieldsˮ

-   Add your system prompt or any additional instructions for the LLM.

### Q: What are Trigger Questions?

> A: Trigger Questions are specific phrases or questions set in advance
> that will automatically start the agent flow whenever the user
> mentions them, regardless of when they appear during the chat.

13. "Language" Tab
==================

### Q: What is the \"Language\" tab used for? 

**A:** The \"Language\" tab allows you to select a different language
for the LiveX AI platform interface . The available languages are
English, Korean (한국어), Simplified Chinese (中文简体), Traditional
Chinese (中文繁體), and Japanese (日本語).

### Q: Does changing the language in the \"Language\" tab also change the language of my AI agent? 

**A:** No, this tab only changes the language of the user interface. To
change the language of your AI agent, you must go to the \"Customize\"
section and adjust the \"Agent Language\" setting.

14. "Support" Tab
=================

### Q: What is the \"Support\" section used for?

**A:** The \"Support\" section is where you can get help or provide
feedback on the product. It\'s designed to gather descriptions of issues
or feature requests.

### Q: What types of information can I submit through the \"Support\" form?

**A:** You can select a topic, such as a \"Feature Request\" or
"Support", provide a detailed description of an issue, or share your
feedback. You can also upload files to "Support" your request.

### Q: What elements are included in the support form?

**A:** The form includes a dropdown menu for \"Topic,\" a required text
box to \"Provide the Description of the Issue or Share Your Feedback,\"
and a button to \"SELECT FILES TO UPLOAD\".

### Q: What do the \"FINISH\" and \"CANCEL\" buttons do?

**A:** The \"FINISH\" button is used to submit your feedback or issue,
while the \"CANCEL\" button discards it.

15. "Apps" Tab
==============

General
-------

### Q: What is the difference between adding Apps in my account and adding or using Apps for Teach AI?

A: To add your Shopify store, you need to provide the Shopify Store URL
and an Admin Token . You also have the option to include attachments
like PDF and DOCX files.

Shopify
-------

### Q: How do I add my Shopify store? 

A: To add your Shopify store, you need to provide the Shopify Store URL
and an Admin Token . You also have the option to include attachments
like PDF and DOCX files. Follow the instructions from the following
YouTube video:
[[https://youtu.be/8MxurUTCAeQ]{.underline}](https://youtu.be/8MxurUTCAeQ)

### Q: How do I find my Shopify Store URL? 

A: Your default Shopify store URL follows the format
yourstorename.myshopify.com. You can find it by logging in to your
Shopify admin and when you hit 'Settings' from your Admin Dashboard! A
second screen will appear that shows some of your store information
above the menu that appears on the left. This information includes your
store name, and your '.myshopify.com' URL for your store just below it.
Alternatively, you can find it under the Settings → Domains section of
your Shopify dashboard.

### Q: How do I get a Shopify Admin Access Token?

**A:** To get a Shopify Admin Access Token, you need to go to your
Shopify store management dashboard.

1.  On the left sidebar at the bottom, go to **Settings.**

2.  Inside settings, go to \"Apps and Sales channels\".

3.  Choose **Develop apps**.

4.  If this is your first development, click **Allow custom app
    development**. And then, click Allow custom app development again.

5.  Click **Create an app** and give it a name, such as \"livex
    copilot\".

6.  Click **Create app**.

7.  Under the app overview, click **Configure Admin API** **scopes**

8.  Set the following permissions:

    -   read\_analytics

    -   read\_customers

    -   read\_discounts

    -   read\_inventory

    -   read\_metaobjects

    -   read\_orders

    -   read\_product\_listings

    -   read\_products

    -   write\_script\_tags

    -   read\_script\_tags

    -   read\_content

9.  Click on **Save** to save the configuration.

10. Go back to the overview tab.

11. Click **Install app** in the top right corner, then click
    **Install** again on the popup.

12. Under \"API credentials,\" click Reveal token once and copy it.

13. Paste the token into the **Adding New Shopify Store** popup on your
    portal.

### Q: What is the \"Include attachments like pdf and docx\" toggle for? 

**A:** This toggle determines whether the system should include attached
documents like PDFs and DOCX files when integrating with your Shopify
store.

Zendesk
-------

### Q: How do I add my Zendesk Help Center? 

**A:** To add your Zendesk Help Center, you need to provide the
**Zendesk Help Center URL**, an **Agent Email**, and an **API Token** .
You also have the option to include attachments like PDF and DOCX files.
Follow the video for step-by-step instruction:
[[https://youtu.be/s\_7pfjXc8no]{.underline}](https://youtu.be/s_7pfjXc8no)

### Q: How do I find my Zendesk Help Center URL? 

**A:** By default, your Zendesk Help Center URL is a Zendesk subdomain,
such as yourcompany.zendesk.com. It may also be a custom subdomain
you\'ve created, like support.yourcompany.com. The URL will typically
end with /hc.

### Q: What is the \"Agent Email\" field for?

**A:** This field requires the email address of a Zendesk agent.

### Q: What does the \"Include attachments like pdf and docx\" toggle do? 

**A:** This toggle determines whether the system should include attached
documents like PDFs and DOCX files when integrating with your Zendesk
Help Center.

### Q: What does the \"Show in verified source\" toggle do? 

**A:** This toggle allows the Zendesk source to be displayed as a
verified source for the AI agent to use.

### Q: What does the \"Reprocess\" setting do? 

**A:** The \"Reprocess\" setting allows you to choose how often the
knowledge base will sync and update. You can set it to **Monthly** or
leave it **Disabled**. If you choose **Monthly**, you need to have a
paid plan.

### Q: How do I get a Zendesk API Token? 

**A:** To get a Zendesk API Token, you need to go to your Zendesk
dashboard.

1.  In your Zendesk dashboard, go to **Admin Center \> Apps and
    integrations \> APIs \> API tokens**.

2.  Enable \"API token access\".

3.  Click **Add API token**.

4.  Fill in an **API token description** (optional).

5.  Click **Save** to generate the token.

6.  **Copy** the token and paste it somewhere secure, as the full token
    will never be displayed again after you close the window.

7.  Paste the token into the **Add New Zendesk App** popup on your
    portal.

Hubspot
-------

### Q: Is LiveX AI compatible with Hubspot ?

A: Yes, you can add Hubspot integrations to your Livex AI agents.

### Q: How do I add Hubspot to teach my LiveX AI agent?

A: Click "Apps" in the dashboard, Click "Hubspot" and "Add More". Give
your new App a name and use the token from the dashboard in your
Hubspot. Follow the instructions from the following YouTube video:
[[https://youtu.be/1tH4AR38EH0]{.underline}](https://youtu.be/1tH4AR38EH0)

### Q: How do I get Hubspot API Token? 

A: Following the following step to get Hubspot API Token:

1.  HubSpot deprecated API keys; do not create new API keys --- use a
    Private App access token or OAuth instead.

2.  In your HubSpot account go to **Settings → Integrations → Private
    Apps** and click **Create a private app**. Configure the app name
    and the scopes (permissions) it needs.

3.  After creating the private app, HubSpot will show a **Private App
    access token**. Copy it immediately (you will not be able to view it
    again later) and store it securely.

Intercom
--------

### Q: Is LiveX AI compatible with Intercom?

A: Yes, you can add Intercom integrations to your Livex AI agents.

### Q: How do I add Intercom to teach my LiveX AI agent?

A: Click "Apps" in the dashboard, Click "Intercom" and "Add More". Add
Intercom Help Center URL and Access Token, choose frequency for
Reprocess and whether including attachments like pdf and docx, Click
"Add". Follow the instructions from the following YouTube video:
[[https://youtu.be/PoCS5AQbJOM]{.underline}](https://youtu.be/PoCS5AQbJOM)

### Q: Which token shall I choose?

Use corresponding token (development, staging, producing) for the
environment since it controls the webhook endpoint.

### Q: How do I get Intercom API Token? 

A: Following the following step to get Interncom API Token:

1.  Sign in to Intercom and open the **Developer Hub** for your
    workspace.

2.  Create a new app (or open an existing app) in Developer Hub.

3.  In the app settings go to **Configure → Authentication** (or Test &
    Publish → Your Workspaces) to locate the Access Token that Intercom
    provides for that app/workspace. Copy and store it securely.

### Q: What does the reprocess feature do?

A: It will recrawl the knowledge in Interncom to have the latest
information.

Salesforce
----------

### Q: Is LiveX AI compatible with Salesforce?

A: Yes, you can add Salesforce integrations to your Livex AI agents.

### Q: How do I add Salesforce to teach my LiveX AI agent?

A: You can add your Salesforce domain to your LiveX AI agents to train
them on the Salesforce knowledge.

### Q: What does adding the Salesforce App to my account do?

A: You can submit a Salesforce Case or create live chat. You can also
add Salesforce Knowledge to train AI. You can add the Salesforce app to
your account by following the instructions from the following YouTube
video:
[[https://youtu.be/Wm3wfU1AiqY]{.underline}](https://youtu.be/Wm3wfU1AiqY).

### Q: What does including the Salesforce Knowledge Base mean for my agents?

A: The agents will have access to Salesforce Knowledge to answer
queries.

### 

### Q: What are the different components of including the Salesforce Knowledge Base?

A:

1\. Select Knowledge Base Meta Columns (comma separated)

These are the metadata fields you want to pull from Salesforce Knowledge
articles.

2\. Select Knowledge Base Content Columns (comma separated)

These are the textual body fields of the Salesforce Knowledge article
that LiveX should use as the content for RAG/search.

3\. Query Conditions (WHERE clause)

Lets you filter which knowledge articles to sync.

4\. Article URL Prefix

Used to construct a clickable article link in responses. In Salesforce
Knowledge, each article can be accessed via a URL like
https://\<your-instance\>.[[lightning.force.com/articles/Knowledge/]{.underline}](http://lightning.force.com/articles/Knowledge/)\<ArticleNumber\>.
Here you'd supply the prefix part so LiveX can generate full URLs
dynamically. An example is
https://yourcompany.lightning.force.com/articles/Knowledge/.

5\. Image URL Rewrite Mapping

Sometimes Salesforce stores image paths as relative URLs or with
internal domains. This mapping lets you rewrite those image URLs so
they're valid when displayed in LiveX [[AI.]{.underline}](http://ai.an)
An example is that Salesforce stores image as:
/servlet/rtaImage?eid=12345 and you configure the mapping from /servlet/
to
[[https://yourcompany.lightning.force.com/servlet/]{.underline}](https://yourcompany.lightning.force.com/servlet/)
which ensures images in articles render correctly when surfaced through
the AI.

### Q: What does the reprocess feature do?

A: It will recrawl the Salesforce Knowledge to have the latest
knowledge.

Freshdesk
---------

### Q: Is LiveX AI compatible with Freshdesk?

A: Yes, you can add Freshdesk integrations to your LiveX AI agents.

### Q: What features do I get when I integrate Freshdesk into my account?

A: You can submit Freshdesk tickets.

### Q: How do I integrate Freshdesk into my account?

A: Add your Freshdesk domain and API key.

Stripe
------

### Q: Is LiveX AI compatible with Stripe?

**A:** Yes, LiveX AI is fully compatible with Stripe. It offers a direct
integration that enables LiveX AI's AI agent to connect securely with
your Stripe account via the Stripe API.

### Q: How do I integrate Stripe into my LiveX account?

A: Follow the instructions from the following YouTube video:
[[https://youtu.be/ZtDinT\_sjNo]{.underline}](https://youtu.be/ZtDinT_sjNo)

1.  Go to "Apps" tab

2.  Click on Stripe

3.  Click on "Add More"

4.  Enter the account name & Stripe API key

5.  Click add

### Q: What features do I get if I integrate Stripe with LiveX?

A: Integrating **Stripe** with **LiveX AI** equips your AI agents to
handle billing, subscription, and retention tasks directly within
customer conversations.

> **1. Subscription Management**

-   Upgrade, downgrade, pause, resume, or cancel subscriptions in real
    time.

-   Modify plans based on customer requests without manual intervention.

> **2. Promotions and Discounts**

-   Apply coupons or promotion codes during interactions.

-   Offer personalized incentives such as targeted discounts or special
    promotions.

> **3. Retention and Churn Reduction**

-   Present tailored offers to customers considering cancellation.

-   Use incentives to improve trial-to-paid conversion rates and reduce
    churn.

### Q: Where can I find my Stripe API key?

A:

1.  Go to Stripe dashboard

2.  Click on "Developers" in the bottom left

3.  Click on "API keys"

4.  Click on "Create restricted key"

5.  Select API key usage and click on "Continue"

6.  Enter a name for your API key

7.  Configure the permissions field as follows:

    a.  Under "All Core Resources" section: Select Permissions: Read for
        "Customers"

    b.  Under "All Billing Resources" section: Select Permissions: Write
        for "Coupons", "Promotion Codes", "Customer Portal", "Invoices",
        and "Subscription"

8.  Click on "Create Key"

9.  Copy the "Token"

10. Go back to LiveX dashboard and paste the token

Recurly
-------

### Q: Is LiveX AI compatible with Recurly?

A: Yes, LiveX AI is fully compatible with Recurly.

### Q: What features do I get if I integrate Recurly with LiveX?

A: When you combine Recurly's powerful subscription management
capabilities with LiveX's AI-driven customer engagement tools, you
unlock a robust, retention-focused solution. Here's what this
integration can enable:

1\. Seamless Subscription Management

LiveX AI agents can use Recurly's APIs to manage the entire subscriber
lifecycle---such as starting, upgrading, downgrading, pausing, or
canceling subscriptions, and making plan changes---while taking actions
in real time based on conversational context. [[Recurly,
Inc.+1]{.underline}](https://recurly.com/solutions/software-b2b-b2c-saas/?utm_source=chatgpt.com)

2\. Promotional Offers & A/B Pricing Experiments

Recurly allows for flexible pricing models, targeted promotions,
bundles, and discount campaigns that can be adjusted dynamically. LiveX
can leverage these to personalize discount offers or re-engage
subscribers during interactions.

### Q: How do I integrate Recurly into my LiveX account?

A: Follow the instructions from the following YouTube
video:[[https://youtu.be/ZtDinT\_sjNo]{.underline}](https://youtu.be/ZtDinT_sjNo)

1.  Go to "Apps" tab

2.  Click on Recurly

3.  Click on "Add More"

4.  Enter the account name & Stripe API key

5.  Click add

### Q: Where can I find my Recurly API key?

A:

1.  Go to your Recurly dashboard

2.  Go to "Integrations" on the left sidebar

3.  Click on "API Credentials"

4.  Click on "Add Private API Key"

5.  Enter a name for your API key

6.  Click on "Save Changes"

7.  Click on the view icon and copy the token

8.  Go back to LiveX dashboard and paste the token

Twilio
------

### Q: Is LiveX AI compatible with Twilio?

A: Yes. LiveX AI is fully compatible with Twilio.

### Q: What features do I get if I integrate Twilio with LiveX?

A: You can config the twilio app to be used by the voice agent

1.  Go to the liveX customization tab

2.  Go to the AGNET MODE tab on the right

3.  Select the Chatbot Mode to Voice

4.  In the Voice configuration section

5.  In the second place you can find the Twilio phone configuration

6.  Select the Twilio APP you added in the first drop down menu

7.  Select the phone number in the second drop down menu

### Q: How do I integrate Twilio into my LiveX account?

A: Follow the instructions from the following YouTube video:
[[https://youtu.be/ZtDinT\_sjNo]{.underline}](https://youtu.be/ZtDinT_sjNo)

1.  Go to liveX homepage

2.  Go to "Apps" tab

3.  Click on twilio

4.  Click on "Add More"

5.  Enter the account name & account SID & auth token

6.  You can Click into the question mark tab for video instruction,

7.  Click Add

### Q: Where can I find my Twilio account SID?

A:

1.  Login to Twilio

2.  Go to the Account info

3.  Find the Account SID

### Q: Where can I find my Twilio auth token?

A:

1.  Login to Twilio

2.  Go to the Account info

3.  Find the Auth token

### Q: Where can I select the Twilio enabled phone numbers?

A:

1.  Login to Twilio

2.  Go to the Account info

3.  Select the enabled phone numbers from the drop down menu

Gmail
-----

### Q: Is LiveX AI compatible with Gmail?

A: Yes. LiveX AI is compatible with Gmail. You can add Gmail as an
integration under the Apps tab. This allows your AI agent to process and
respond to emails directly, alongside other integrated platforms.

### Q: How do I add my Gmail account to LiveX AI?

A:

-   Go to the **Apps** tab in your LiveX AI dashboard.

-   Select **Gmail**.

### Q: What does Gmail integration allow my AI agent to do?

A: Once connected, Gmail integration enables your AI agent to:

-   Send automated email responses.

-   Read and process incoming messages.

-   Categorize messages with **Tag Management**.

-   Trigger **Workflows** based on email content.

-   Escalate to a human agent when necessary.

-   Include file attachments (PDF, DOCX) in responses if enabled.

### Q: How do I refresh or remove my Gmail integration?

A:

-   **Refresh**: Go to **Apps → Gmail → Refresh** to re-authenticate if
    permissions or tokens expire.

-   **Remove**: Select **Remove Integration** to disconnect Gmail. Your
    configuration is preserved for later re-use.

### Q: How do I test Gmail integration before going live?

A: After setup, use the **AgentFlow** in your LiveX AI dashboard.
Customise/create a flow and send a test email to the connected Gmail
account and verify that the AI agent responds as expected. Adjust
workflows or content if results are incomplete.

### Q: What happens if the Gmail connection fails?

A:

-   Re-authenticate the Gmail account in **Apps → Gmail**.

-   If problems persist, use the **Support** tab to report the issue and
    attach error details or screenshots.

### Q: Can I integrate multiple Gmail accounts?

A: Yes. Repeat the integration process for each Gmail account. Each will
appear separately under **Apps → Gmail** and can be assigned to
different AI agents.

### \*\*Q: How secure is Gmail integration with LiveX AI?

A: Gmail integration uses Google OAuth for authentication. LiveX AI does
not store Gmail login credentials. All email data is encrypted both in
transit and at rest.

### \*\*Q: Can I limit what the AI agent can access in Gmail?

A: Yes. During OAuth setup, you can restrict the permissions you grant
(e.g., read-only vs. read and send). For tighter control, you can also
create a dedicated Gmail account with scoped permissions for use by
LiveX AI.

### Q: Can Gmail workflows be customized?

A: Yes. In the **Workflow** section you can:

-   Trigger responses based on email subject or body.

-   Route specific types of messages (e.g., invoices, VIP senders) to a
    human agent.

### Q: How long does Gmail setup take?

A: Gmail integration typically takes a few minutes, depending on account
size and number of messages processed.

### \*\*Q: Can Gmail sync frequency be controlled?

A: Yes. Use the **Reprocess** setting in the Apps tab to define how
often Gmail content is refreshed. Depending on your plan, options may
include Monthly or Disabled.

### \*\*Q: What is the "Include attachments" toggle for Gmail?

A: It controls whether Gmail attachments (PDFs, DOCX) are included when
the system processes messages. Enabling it ensures attachments are
referenced in agent replies when relevant.

### \*\*Q: Can Gmail integration be paused without removing it?

A: Yes. Use the **Excluded toggle** in **My Files** to temporarily stop
Gmail content from being used by the AI while keeping it stored in the
system.

### \*\*Q: Can Gmail be combined with other integrations?

A: Yes. Gmail can be connected alongside Zendesk, Salesforce, Freshdesk,
and other systems. This allows Gmail activity to sync into your wider
support and CRM ecosystem.

16. "My Account" Tab
====================

### Q: How can I see or edit my personal information?

A: You can view and edit your personal information under the "My
Account" tab in the navigation bar.

### Q: How can I see the quota usage of my account?

A: You can view your account quota under the "My Account" tab in the
navigation bar.

### Q: I ran out of account quota/message credits/members/agents/documents, what should I do?

A: You can increase your quota under the "My Account" tab in the
navigation bar.

17. "My Team" Tab
=================

### Q: How can I add/delete my team members into my LiveX AI account?

A: You can add or delete members by going to the "My Team" tab in the
navigation bar.

### Q: How can I change the role of my team members to Admin/Member?

A: You can change the role status of your team members under the "My
Team" tab in the navigation bar. Click on the member whose status you
would like to change.

18. Others
==========

### Q: How long does it take for the agent to be ready?

A: It usually takes a few minutes, depending on the data size and number
of sources.

### Q: How can I improve my AI agentʼs accuracy?

A: You can enhance accuracy by adding:

-   Expert Knowledge: Upload industry-specific information for accurate
    responses.

-   Business Voice: Customize how your agent communicates with
    customers.

-   Agent Customization: Adjust chat style, language, greetings, and
    appearance.

-   Tag Management: tags help categorize user interactions, making it
    easier to identify trends and automate responses. For example, if 80
    out of 100 daily user engagements are tagged as "order tracking,ˮ it
    signals a recurring issue that needs attention.

### Q: How do I monitor my agentʼs performance?

A: Track key metrics like:

-   Self-Service Rate: Percentage of resolved tickets without human
    support.

-   Cost Savings: Money saved by automating support.

-   Resolved Tickets: Number of inquiries successfully handled.

Tech Support
============

> [[https://docs.livex.ai/reference]{.underline}/[javascript-sdk]{.underline}](https://docs.livex.ai/reference/javascript-sdk)
>
> Ask the support team from LiveX for access password or any other
> question.
