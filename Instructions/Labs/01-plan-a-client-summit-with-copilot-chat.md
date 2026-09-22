---
lab:
    title: 'Plan a client summit with Copilot Chat'
    description: 'Use Copilot Chat to research trends, brainstorm sessions, visualize an agenda, draft a planning document, and collaborate in Copilot Pages.'
    duration: 30
    level: 100
    islab: true
    status: 'in-development'
    targetDate: '2027-03-01'
---

# Plan a client summit with Copilot Chat

## Scenario

Imagine you're a business operations associate at a mid-sized consulting firm. Your manager has asked you to lead planning for an upcoming Client Innovation Summit. You'll use Copilot Chat to gather insights, generate ideas, visualize the schedule, draft a planning document, summarize it, and collaborate with your colleagues. 

By the end of this exercise, you'll be able to:

- Research industry trends and brainstorm ideas using Copilot Chat.
- Visualize an agenda and generate an image using Copilot Chat.
- Draft a planning document and export it to a file.
- Summarize an uploaded file and draft a follow-up email.
- Collaborate on a shared page using Copilot Pages.

This exercise should take approximately **30** minutes to complete.

> **Tip**: This exercise is about getting comfortable using Copilot Chat, not following steps exactly. If you have a real event or project you'd rather plan, use that instead of the Client Innovation Summit example. You're also encouraged to modify the example prompts or try your own instead of typing them exactly as written.

> **Note**: These tasks are designed specifically to use web-based information in Microsoft Copilot. If you have a Microsoft 365 Copilot license, make sure you manually turn off **Work IQ** when you open Copilot Chat, as it may be enabled by default. Doing so ensures that prompts behave as intended and source information from public web content.

## Before you start

You need:

- A Microsoft 365 tenant account with access to Copilot Chat (credentials provided by your tenant provider for this exercise).
- Access to a virtual machine provided by your tenant provider.

To get started, log into your virtual machine and launch the Microsoft Copilot web app:

1. Log into the virtual machine provided by your tenant provider as the local **Administrator** account with the password `Pa55w.rd`.
   
1. In the Windows taskbar, select **Microsoft Edge**.
   
1. To launch Microsoft Copilot, enter `https://copilot.cloud.microsoft` in the address bar and select **Sign in**.
   
1. On the **Sign-in** screen, enter userx@yourtenant.onmicrosoft.com (provided by your tenant provider) and select **Next**.
   
1. On the **Enter password** screen, enter the password (provided by your tenant provider), then select **Sign in**..
   
1. If prompted to **Stay signed in?**, select the **Don't show this again** checkbox, then select **Yes**.
   
1. Skip any welcome messages if they appear.
   
1. The Microsoft Copilot web app should launch successfully.

You're ready to begin Task 1.

## Task 1: Summarize industry trends for event planning

In this task, you'll explore how Copilot Chat can help you quickly identify key innovation trends from the web that are relevant to your summit. This is the foundation for shaping the event agenda around meaningful topics that resonate with your client audience.

1. Enter this prompt in the prompt box at the bottom of the Copilot Chat:

    ```prompt
    What are the top three innovation trends in [your industry] for 2026 and how can they shape the agenda for a client summit?
    ```

   > **Note**: Replace [your industry] with the industry of your choosing.

1. Select **Send (arrow icon)** on bottom right of the prompt box or select **Enter** on your keyboard. 

1. Review the information provided by Copilot and if needed, refine the prompt.

## Task 2: Brainstorm and draft session ideas

Building on the trends you just researched, use Copilot to brainstorm engaging and relevant session titles and descriptions. This helps you transform raw insights into concrete agenda items that can drive value for event attendees.

1. In the same chat with Copilot, enter this prompt:

    ```prompt
    Based on those trends, suggest 5 engaging session titles and write short descriptions for a client innovation summit.
    ```

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

1. Enter this follow-up prompt:

    ```prompt
    Make the descriptions more compelling by using an energizing and professional tone.
    ```

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

## Task 3: Visualize the agenda timeline and create a logo

Copilot Chat can help you quickly convert text-based ideas into visual content. In this task, you'll generate a timeline for the summit and a logo to reflect the theme of the summit, useful for promotional and summit-related materials to make it more engaging and attractive. 

1. In the same chat with Copilot, enter this prompt:

   ```prompt
   Create an agenda timeline for a 1-day summit focused on [trend] with an introduction, closing, sessions at 9:00 AM, 11:00 AM, 1:30 PM, and 3:00 PM, two mini breaks, and an hour break for lunch in a table format.
   ```

   > **Note**: Replace [trend] with one of the trends listed in Task 1.

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

1. Enter this follow-up prompt:

   ```prompt
   Create a simple and modern logo for this client innovation summit.
   ```

1. Select **Send**, review the image provided by Copilot and if needed, refine the prompt.

## Task 4: Draft a planning document for the summit

Now that you've outlined the structure and ideas for your event, use Copilot Chat to create a planning brief to put into a word document. This document will serve as your anchor for the project, capturing goals, session details, and success metrics in one place.

1. In the same chat with Copilot, enter this prompt:

   ```prompt
   Create a 1-page planning brief for this client innovation summit that includes: goals, audience, session themes, and key planning milestones.
   ```

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

1. Enter this follow-up prompt:

   ```prompt
   Add a section summarizing anticipated outcomes and success metrics for the event.
   ```

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

1. Next, ask Copilot to create a Word document from this information, enter this prompt:

   ```prompt
   Create a Word document of this planning brief.
   ```

1. In the generated document preview, select **Open in Word**.

1. If prompted, sign in using the credentials provided by your tenant provider.
   
1. Review the document in Word for the web.

1. Select the document name in the upper-left corner, enter a new name if needed (for example, **Client Summit Planning Brief**), and then select **Enter**. Word saves the renamed document automatically.

1. Select **File** > **Create a Copy** > **Download a Copy** to save the document to your computer.

1. Navigate back to your Copilot Chat conversation to complete Task 5.

## Task 5: Analyze and generate content from a file

In this task, you'll use the planning brief from Task 4 and have Copilot summarize it and generate an internal communication. This shows how Copilot can save time by turning documents into digestible, action-ready content.

1. Continue in the Copilot Chat conversation. Ensure the **Client Summit Planning Brief** file created in Task 4 is attached, then enter the following prompt:

    ```prompt
    Summarize the key points from this planning brief into only 5 condensed bullet points.
    ```

1. Select **Send** and review the summary generated by Copilot.

1. If needed, refine the prompt and review the updated response.

1. Enter this follow-up prompt:

    ```prompt
    Write a follow-up email to the planning team with these highlights and the next step.
    ```

1. Select **Send**, review the information provided by Copilot and if needed, refine the prompt.

## Task 6: Collaborate using Copilot Pages

Turn the email draft from Task 5 into a collaborative workspace using Copilot Pages. This will let you simulate how multiple team members can refine content in real time.

1. Select More options **(...)** > **Edit in Pages** underneath Copilot's last response in **Task 5** (or any response you prefer) to copy over that information to Copilot Pages.

1. A new Copilot Page will open on the right pane of Copilot Chat, explore the following actions:

    - Give the page a new title at the top of the page.  
    - Type any additional content throughout the page by just clicking into the page.
    - Add an additional Copilot Chat response (previous or new) to the page by selecting More options **(...)** > **Add to page** at the bottom of the response. 
    - Enter **"/"** to insert content blocks, such as a table, or checklist.
    - Use **@** to mention a colleague (or simulate this) and grant them access by selecting **(+)** > **Share with selected** > **Share and notify** in the messages that pops up when adding their name.
    - Optionally, share your page by selecting the **Share** icon at the top right of the page and selecting one of the two options to copy a link.

## Optional Task 7: Review and reflect

In the same chat with Copilot, enter this prompt:

```prompt
Create a checklist of what I learned today using Copilot Chat and how I can apply it to my [role].
```

> **Note**: Replace [role] with your role.

## Summary

In this exercise, you used Copilot Chat to research industry trends, brainstorm session ideas, visualize an agenda timeline, generate a logo, draft and export a planning document, summarize a file into key points, draft a follow-up email, and collaborate on a shared page with Copilot Pages. You practiced navigating between different Copilot experiences and refining prompts to move a project from initial research through to a shareable output.
