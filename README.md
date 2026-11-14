# 🌿 AutoFlow

A responsive **team workspace prototype** built with HTML, CSS, and vanilla JavaScript. AutoFlow helps student project teams turn chat messages and meeting decisions into assigned tasks, track submissions, and see which version was accepted.

> **One task, from the original decision to the final review.** AutoFlow demonstrates responsive front-end design, browser-based state management, and an interactive review workflow.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Prototype](https://img.shields.io/badge/Interactive-Prototype-164C39?style=for-the-badge)

---

## 🎯 Key Features

- 📊 **Project Dashboard** — See task owners, due dates, and what’s awaiting review.
- 💬 **Conversation to Task** — Turn a sample chat message into an assigned task that preserves the original context.
- 📝 **Meeting Decisions** — Assign a follow-up directly from the project’s sample meeting notes.
- 👥 **Two Ways to Review Group Work** — Review one shared submission or accept each teammate’s contribution separately.
- 🔁 **Submission and Review** — Request changes, submit a revision, and accept the updated deliverable.
- 🧭 **FlowTrace Timeline** — Follow assignments, submissions, feedback, and acceptance alongside the source decision.
- 📱 **Responsive Layout** — Use the workspace on desktop or mobile.

---

## 🧠 How It Works

**Discuss → Assign → Submit → Review → Accept**

Start in a sample student workspace called **Campus Studio**. When you create a task from a message or meeting note, AutoFlow carries the source text into the task. The task keeps its submission and review history, including any changes requested. For tasks with separate contributions, the parent task is accepted once every required contribution has been accepted.

## 🖥️ Try the Demo

1. Open **Final demo deck** in the **Overview**.
2. Click **Request changes** and enter feedback such as “Add a slide showing the reporting flow.”
3. Click **Submit revision** and enter `Campus Studio demo v2.pdf`.
4. Click **Accept** and look for the accepted revision in **FlowTrace**.

> **Try another path** · Go to **Meeting notes** and create a task for the demo poster’s QR code. Open **Usability evidence** to see how individual contributions are reviewed.

---

## 🛠️ Technologies Used

| Technology | Role |
| --- | --- |
| **HTML5** | Workspace layout, task forms, and review dialogs |
| **CSS3** | Color palette, responsive grids, and mobile layout |
| **Vanilla JavaScript** | Navigation, task creation, review actions, and timeline updates |
| **Browser local storage** | Keeps demo changes between reloads in the same browser |

## 📂 Project Structure

```text
AutoFlow/
├── AutoFlow.html   # Prototype with embedded CSS and JavaScript
└── README.md       # Project overview and demo instructions
```

## ⚙️ Setup Instructions

1. Download the repository from **Code → Download ZIP** on GitHub, or clone it using the URL under **Code**.
2. Open [`AutoFlow.html`](./AutoFlow.html) in a modern browser.
3. Use **Reset demo** to restore the sample workspace whenever you want to start over.

The prototype runs directly in the browser without a package install or build step.

---

## 💡 Why This Project?

Team decisions can get buried in chat, and a task marked “done” can leave teammates guessing which version was approved. AutoFlow explores how a project workspace can keep the original decision, responsibility, and review outcome visible throughout the work.

## 🧪 Prototype Scope

The demo uses sample conversations and meeting notes. Submissions are simulated with filenames or links, and changes stay in the current browser. Accounts, live messaging, and file uploads are outside the current prototype.

## ⭐ Support

If you found AutoFlow useful, consider giving the repository a star on GitHub.
