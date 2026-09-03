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

## Scenario

In this exercise, you use Microsoft Copilot to prepare for a project check-in meeting, capture and summarize what happens during the meeting, draft a follow-up email, and centralize the project's decisions in a shared page and notebook.

By the end of this exercise, you'll be able to:

- Use Copilot in Outlook to draft and create a meeting invite.
- Use Copilot in Teams to capture and summarize a live meeting.
- Use Copilot Chat to draft a follow-up grounded in a meeting recap.
- Use Copilot Pages and Notebooks to centralize project decisions and references.

This exercise should take approximately **25** minutes to complete.

> **Tip**: This exercise is about getting comfortable using Copilot across Outlook, Teams, and the Microsoft Copilot app, not following steps exactly. You're encouraged to try your own prompts instead of typing the examples exactly as written. If you'd rather use a real project instead of the LaunchPad example, keep in mind later steps reference the LaunchPad name and details from earlier tasks, so you'll need to adjust the prompts to match.

## Before you start

You need:

- A Microsoft 365 account with a Microsoft 365 Copilot license.
- Access to Outlook, Teams, and Microsoft Copilot, either on the web or through the desktop apps.

## Task 1: Prepare for the meeting in Outlook

You're leading a project check-in for a fictional initiative called LaunchPad, and you need a meeting invite ready to send.

1. Open Outlook and select the Copilot icon to open the Copilot pane.
1. Above the message box, select the **Default mode** dropdown and choose **Allow actions** so Copilot can create the event directly on your calendar.
1. Enter the following prompt, replacing [time] with a specific time at least 5 minutes from now:

    `Draft a Teams meeting invite for a 15-minute LaunchPad project check-in today at [time], with only me as the attendee. Include an agenda covering progress updates, open blockers, and next steps.`

1. Review the meeting details Copilot proposes, then select **Approve** to create the event on your calendar.
1. Check your calendar to confirm the LaunchPad Project Check-In event was created at the time you specified.

## Task 2: Capture a live meeting with Copilot in Teams

Now you'll run the meeting you just scheduled and see how Copilot captures what happens in real time. Because you're completing this exercise on your own, you'll play both the host and the only attendee.

1. Open Teams, find the LaunchPad Project Check-In meeting you scheduled, and select **Join** to start the meeting.
1. Select the **More** (•••) icon in the meeting toolbar and select **Record** (or **Transcribe**, if recording isn't available in your organization).
1. Once the meeting starts, speak a short project update out loud so there's a transcript to work with. For example:

    `This week we finished the login redesign, but we're blocked on the payment integration until the vendor sends updated API documentation. Next step is to follow up with the vendor and target a fix by Friday.`

1. Select the Copilot icon in the meeting toolbar and enter the following prompt:

    `What are the key takeaways so far?`

1. Review Copilot's response, then ask a follow-up question:

    `What blockers were mentioned?`

1. End the meeting.

> **Note**: Copilot requires a saved transcript to provide full meeting insights. If your organization's policy doesn't allow transcription, you can still complete the remaining tasks using the sample update above as reference text.

## Task 3: Review the meeting recap

1. From the Teams calendar, open the meeting you just finished.
1. Open the **Recap** tab in the meeting chat.
1. Select **AI summary** to view the meeting notes and follow-up tasks Copilot generated.

## Task 4: Draft a follow-up with Copilot Chat

With the recap ready, you need to let the wider LaunchPad team know what happened and what's next.

1. Open Microsoft Copilot Chat.
1. Reference your meeting in a prompt by typing a forward slash (`/`) followed by the meeting name, then enter the following prompt:

    `Draft a follow-up email for the LaunchPad team summarizing /LaunchPad Project Check-In. Include the blocker about the payment integration vendor, and list the follow-up tasks with owners and due dates.`

1. Review the draft, then refine it with a follow-up prompt:

    `Convert the follow-up tasks list into a table with columns for task, owner, and due date.`

## Task 5: Build a shared project hub with Copilot Pages

Instead of keeping the project's plan buried in email, you'll turn your follow-up into a shared page the whole team can refer back to.

1. Select the **•••** icon underneath Copilot's last response, then select **Edit in Pages** to copy the follow-up content over to a new Copilot Page.
1. In the page, ask Copilot to expand it into a project hub:

    `Turn this into a collaborative LaunchPad project hub with sections for objectives, key milestones with a timeline, stakeholder roles and responsibilities, and a space for open questions or risks.`

1. Review the generated page, confirming the payment integration blocker appears in the open questions or risks section.
1. Your page saves automatically. To find it again later, select **Library** in the left navigation pane of Microsoft Copilot, then select **Pages**.

## Task 6: Centralize project knowledge with Copilot Notebooks

Finally, you'll bring your meeting recap and project data together in one place so anyone on the team can ask questions about the project's status.

1. In Microsoft Copilot, select **Notebooks** and select **Create first notebook** (or **New notebook** if you've created one before).
1. Name the notebook `LaunchPad Project Notebook`.
1. Under **Add references**, search for your LaunchPad Project Check-In meeting and add it if it appears. Also add the `Quarterly Sales Analysis` workbook from an earlier exercise, if you have it saved to OneDrive.

> **Note**: A meeting may not appear as a searchable reference if it was not recorded. If you don't see it in the search results, try searching for the meeting chat instead and add that as a reference. Otherwise, continue with just the workbook, or add the meeting recap by pasting its content directly into the notebook after it's created.

1. Select **Create**.
1. In the notebook's chat box, enter the following prompt:

    `Summarize the current blockers and next steps for the LaunchPad project based on these references.`

1. Review Copilot's response, grounded in the references you added.
1. Optionally, select **Get audio overview** to generate a short spoken summary of the notebook's contents.

## Summary

In this exercise, you used Copilot across Outlook, Teams, Copilot Chat, Pages, and Notebooks to prepare for a meeting, capture what happened, and centralize follow-up work so your team stays aligned without digging through separate apps. You practiced letting Copilot take direct action on your calendar, capturing and reviewing a live meeting recap, drafting a follow-up grounded in that meeting, and bringing project references together in a shared page and notebook.
