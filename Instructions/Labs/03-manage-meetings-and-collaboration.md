---
lab:
    title: 'Manage meetings and collaboration with Microsoft Copilot'
    description: 'Use Copilot in Outlook and Teams, Copilot Chat, Copilot Pages, and Copilot Notebooks to prepare for a meeting, capture what happened, and centralize follow-up work.'
    duration: 25
    level: 100
    islab: true
    status: 'in-development'
    targetDate: '2027-03-01'
---

# Manage meetings and collaboration with Microsoft Copilot

In this exercise, you use Microsoft Copilot to prepare for a project check-in meeting, capture and summarize what happens during the meeting, draft a follow-up email, and centralize the project's decisions in a shared page and notebook.

This exercise should take approximately **25** minutes to complete.

## Before you start

You need:

- A Microsoft 365 account with a Microsoft 365 Copilot license.
- Access to Outlook, Teams, and Microsoft Copilot, either on the web or through the desktop apps.

## Prepare for the meeting in Outlook

You're leading a project check-in for a fictional initiative called LaunchPad, and you need a meeting invite ready to send.

1. Open Outlook and create a new event.
1. Select the Copilot icon in the event toolbar.
1. Enter the following prompt:

    `Draft a meeting invite for a 15-minute LaunchPad project check-in. Include an agenda covering progress updates, open blockers, and next steps.`

1. Review the draft agenda and title Copilot generates, then adjust the details as needed.
1. Set the meeting time to start in a few minutes so you can run it yourself in the next task, then save the invite.

## Capture a live meeting with Copilot in Teams

Now you'll run the meeting you just scheduled and see how Copilot captures what happens in real time. Because you're completing this exercise on your own, you'll play both the host and the only attendee.

1. Open Teams and start the LaunchPad check-in meeting you scheduled, or select **Meet now** to start an instant meeting.
1. Open **Meeting options** and turn on transcription for the meeting.
1. Once the meeting starts, speak a short project update out loud so there's a transcript to work with. For example:

    `This week we finished the login redesign, but we're blocked on the payment integration until the vendor sends updated API documentation. Next step is to follow up with the vendor and target a fix by Friday.`

1. Select the Copilot icon in the meeting toolbar and enter the following prompt:

    `What are the key takeaways so far?`

1. Review Copilot's response, then ask a follow-up question:

    `What blockers were mentioned?`

1. End the meeting.

> [!NOTE]
> Copilot requires a saved transcript to provide full meeting insights. If your organization's policy doesn't allow transcription, you can still complete the remaining tasks using the sample update above as reference text.

## Review the meeting recap

1. From the Teams calendar, open the meeting you just finished.
1. Open the **Recap** tab in the meeting chat.
1. Select **Copilot** to view the summarized content, including topics discussed and any action items.
1. Export the summary to Word if you'd like to keep a copy.

## Draft a follow-up with Copilot Chat

With the recap ready, you need to let the wider LaunchPad team know what happened and what's next.

1. Open Microsoft Copilot Chat.
1. Enter the following prompt:

    `Draft a follow-up email for the LaunchPad team summarizing today's check-in. Include the blocker about the payment integration vendor and the next step to follow up by Friday.`

1. Review the draft, then refine it with a follow-up prompt:

    `List the action items separately with owners and a due date.`

## Build a shared project hub with Copilot Pages

Instead of keeping the project's plan buried in email, you'll create a shared page the whole team can refer back to.

1. In Microsoft Copilot, select **Pages** and create a new page.
1. Prompt Copilot:

    `Create a collaborative LaunchPad project hub with sections for objectives, key milestones with a timeline, stakeholder roles and responsibilities, and a space for open questions or risks.`

1. Review the generated page, then add the payment integration blocker to the open questions or risks section.
1. Save the page so it's accessible to your team from the **Pages** tab in Microsoft Copilot, Teams, and Outlook.

## Centralize project knowledge with Copilot Notebooks

Finally, you'll bring your meeting recap and project data together in one place so anyone on the team can ask questions about the project's status.

1. In Microsoft Copilot, select **Notebooks** and select **Create first notebook** (or **New notebook** if you've created one before).
1. Name the notebook `LaunchPad Project Notebook`.
1. Under **Add references**, add your meeting recap and the `Quarterly Sales Analysis` workbook from an earlier exercise, if you have it saved to OneDrive.
1. In the notebook's chat box, enter the following prompt:

    `Summarize the current blockers and next steps for the LaunchPad project based on these references.`

1. Review Copilot's response, grounded in the references you added.
1. Optionally, select **Get audio overview** to generate a short spoken summary of the notebook's contents.

You've used Copilot across Outlook, Teams, Copilot Chat, Pages, and Notebooks to prepare for a meeting, capture what happened, and centralize follow-up work so your team stays aligned without digging through separate apps.
