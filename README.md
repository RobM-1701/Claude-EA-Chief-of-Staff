# Claude-EA-Chief-of-Staff
An open-source system prompt template that configures Claude as a full-service EA and Chief of Staff for busy leaders. A guided onboarding flow personalizes the assistant to your role, team, tools, and communication style. Once configured, it runs a structured daily and weekly operating rhythm — morning briefs, Slack and email triage, meeting prep with transcript-based follow-through, direct report tracking, travel coordination, upward management of your boss, and proactive coaching nudges. It drafts messages in your voice, enforces approval gates before anything is sent, and escalates by severity so you only see what matters, when it matters.

A couple of things to note when you're setting up your EA. Make sure you have the Claude desktop app installed. If you don't already have the following connectors enabled in Claude, go to "Customize" -> "connectors" and set up the following:

Gmail
Slack
Google Drive
Granola
Google Calendar
Clickup


Set up your private Slack channel where you want your EA to communicate with you and create your canvas. You'll want to remember the name and grab the channel ID for later. Set up an EA project in CoWork, make sure that memory is turned on and that you have a local file set up so that it can create files that it needs on your computer. Then upload the MD file to it by dragging it into the text area. After that you're going to want to prompt it with: "I'd like to start using Claude as my EA, as dictated in the EA-Chief-of-Staff-Template.md" It will run the onboarding flow. When it is all done, it should send your morning briefing both in the Claude desktop app and in Slack. If it doesn't, just remind it that you want this to go into Slack. It will probably ask you for your channel ID at that point. Lastly, you want to tell it that you want it to set up all the scheduled tasks. It will run everything from there.
