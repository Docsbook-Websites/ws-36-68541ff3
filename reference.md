---
title: NotedAI Reference Guide for Meeting Documentation
description: Learn to use NotedAI's features for efficient meeting notes and action item tracking.
---

# NotedAI Reference Guide

This reference guide provides a comprehensive overview of the commands and parameters available in NotedAI, organized by category. Use this guide to enhance your meeting documentation process.

## Meeting Commands

| Parameter/Command        | Type         | Description                                           | Example                        |
|--------------------------|--------------|-------------------------------------------------------|--------------------------------|
| `createMeeting`          | Command      | Initiates a new meeting session.                      | `createMeeting("Team Sync")`  |
| `addParticipant`         | Command      | Adds a participant to the current meeting.            | `addParticipant("Alice")`     |
| `startRecording`         | Command      | Begins recording the meeting for note-taking.         | `startRecording()`             |
| `stopRecording`          | Command      | Stops the current recording session.                  | `stopRecording()`              |

## Note Management

| Parameter/Command        | Type         | Description                                           | Example                        |
|--------------------------|--------------|-------------------------------------------------------|--------------------------------|
| `summarizeNotes`         | Command      | Generates a summary of the recorded meeting notes.    | `summarizeNotes()`            |
| `tagNote`                | Command      | Tags a specific note for easy retrieval.              | `tagNote("Action Item")`      |
| `editNote`               | Command      | Edits a specific note within the meeting notes.       | `editNote(1, "Update budget")`|
| `deleteNote`             | Command      | Deletes a specified note from the meeting notes.      | `deleteNote(2)`               |

## Action Item Tracking

| Parameter/Command        | Type         | Description                                           | Example                        |
|--------------------------|--------------|-------------------------------------------------------|--------------------------------|
| `addActionItem`          | Command      | Adds an action item to the meeting notes.             | `addActionItem("Follow up with Bob")` |
| `markActionItemComplete` | Command      | Marks a specific action item as completed.            | `markActionItemComplete(1)`   |
| `listActionItems`        | Command      | Lists all action items from the meeting notes.        | `listActionItems()`            |

## Integration Commands

| Parameter/Command        | Type         | Description                                           | Example                        |
|--------------------------|--------------|-------------------------------------------------------|--------------------------------|
| `integrateCalendar`      | Command      | Integrates your calendar for scheduling meetings.     | `integrateCalendar("Google")` |
| `syncWithSlack`          | Command      | Syncs meeting notes with your Slack channel.          | `syncWithSlack("team-updates")` |
| `exportNotes`            | Command      | Exports the meeting notes to a specified format.      | `exportNotes("PDF")`          |

## Conclusion

Utilize this reference guide to maximize your use of NotedAI for efficient meeting documentation. Each command and parameter is designed to streamline your workflow, allowing you to focus on what matters most—growing your business.