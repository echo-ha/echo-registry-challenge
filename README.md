# 🚀 Full Stack Engineer Technical Assignment: Registry UI Challenge

Welcome to the "Registry UI Challenge!"  
Your mission: create a simplified UI experience similar to DockerHub. You'll explore DockerHub's public APIs on your own and use them to build a polished, functional web app.  

---

## 🎯 Objective

Build a small but complete frontend application that consumes DockerHub's public APIs and allows browsing/searching repositories and tags.

👉 **Note:** We don't provide the API specification. Part of the challenge is to figure out how to access and use DockerHub's APIs yourself.

---

## 📋 Your Tasks

1. Discover and use DockerHub's APIs to:  
   - Search repositories by keyword.  
   - Display repository details (tags, last updated, size).  
   - Show tag lists for a repository.  

2. Implement the following two pages (your own design):

### 🔍 A. Explore Repositories

- A search bar at the top to search for repositories by keyword.  
- A showcase of 10 popular image repositories displayed as cards or any other format you find appropriate (no need for filters).  
- Each repository entry should include at least: logo, repository name, description, and owner.  
- Clicking a repository should take the user to the Repository Details page.  

🔗 **Reference:** [DockerHub Explore](https://hub.docker.com/search?sort=pull_count&order=desc)  

### 📄 B. Repository Details

- Show repository title, description, owner, and last updated.  
- Display a list of tags for the repository, each with:  
  - Tag name  
  - Last updated  
  - Size  
  - A "Copy Command" button (to copy `docker pull <repo>:<tag>`)  

🔗 **Reference:** [Example Repository – Fluent Bit](https://hub.docker.com/r/fluent/fluent-bit)  

---

## 🧠 Product Thinking

We expect you to treat this as a real product: think about what a user would need beyond the list above, and tell us what you added and why.  

---

## 📦 Deliverables

1. **A working web app:**  
   - Clean structure (components, API layer, etc.)  
   - Instructions to run locally (README).  

2. **A short summary document that includes:**  
   - APIs you used and how you discovered them.  
   - Key design decisions.  
   - Product decisions: what you added or left out from a user's point of view, and why.  
   - Challenges or lessons learned.  
   - What you'd improve with more time.  

You'll walk us through your work in your technical interview.

---

## 💡 Reminders

- Part of the assignment is API exploration – show us how you approach discovering and integrating external APIs.  
- Prioritize clarity, maintainability, and a nice-looking UI.  
- Handle UX gracefully (loading states, errors, empty results).
- Focus on quality of reasoning over volume.
- Don't make this production-grade; you can do things that don't scale.
- AI tools are welcome. Tell us what you used them for and where they helped or hurt.
- If you hit a wall, write down what you tried and move on.

---

## 🚢 Submission

- Create a fork of this repository and give access to your fork
- Once you notify that you are done, no more commits!

---

## ❓ Questions

Have fun! For any question or clarification, reach out without a second thought 🙂

**Echo Team**
