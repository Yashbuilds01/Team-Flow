# AutoFlow

AutoFlow is a clickable prototype for student project teams. It demonstrates how a chat message or meeting decision can become an assigned task and stay connected to the deliverable through submission, revision, and acceptance.

## Run the prototype

1. Download or clone this repository.
2. Open `AutoFlow.html` in a modern browser.

The prototype runs as a single HTML file. Setup requires no package installation, build command, server, or account.

## Try the demo

1. In **Overview**, select **Final demo deck**.
2. Choose **Request changes** and enter feedback.
3. Choose **Submit revision** and enter a sample filename such as `Campus Studio demo v2.pdf`.
4. Select **Accept**. The **FlowTrace** timeline shows the submission, feedback, revision, and acceptance alongside the source decision.
5. Open **Conversation** or **Meeting notes** to turn a sample message or decision into an assigned task.
6. Open **Usability evidence** to try individual contributions. The parent task is accepted once all required contributions are accepted.

Use **Reset demo** to restore the original sample data.

## What’s included

- A project overview with task counts and review status
- Sample conversations and meeting notes with task creation
- Task owners, due dates, and links back to source context
- Examples of a shared deliverable and individually reviewed contributions
- A FlowTrace timeline for assignments, submissions, feedback, and acceptance

## Tech stack

- **HTML** for the page structure
- **CSS** for the responsive layout and visual design
- **Vanilla JavaScript** for navigation, task creation, and review actions
- **Browser local storage** for demo changes

## Prototype scope

AutoFlow uses sample data and simulates submissions with filenames or links. Changes are stored in the current browser. A full implementation would add real accounts, project permissions, shared data, file uploads, and real-time messaging.
