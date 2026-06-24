# hellosterling.github.io

# Systems & Automation Portfolio

Welcome to my personal portfolio site repository. This project serves as a sandbox for exploring Linux, workflow automation tools, and modern AI-assisted systems integration.

At the same time as exploring these topics, I am also trying to learn to use Vim. Any typos are likely due to my ineptitude at Vim. :P

The live site can be viewed at: [https://hellosterling.github.io](https://hellosterling.github.io)

## 🛠️ Tech Stack & Environment
* **OS Environment:** Linux/EndeavourOS (Lenovo ThinkPad setup) for fun and Mac OS for work
* **Text Editor:** Vim
* **Version Control:** Git & GitHub
* **Automation Stack:** n8n, Google Workspace APIs
* **AI Tooling:** Claude (Anthropic) for code generation and logic prototyping. Gemini when I want to switch it up. Even though I have a background in writing/editing, I'll confess I'm using AI to help with a lot of this content! We also use ChatGPT at work.

## 📂 Project Focus: Client Document Automation Pipeline
The core project documented in this repository is an automated workflow built inside **n8n**. 

* **The Goal:** Prevent duplicate file generation and automate data mapping from a messy, repeating spreadsheet data stream.
* **The Method:** I architected the logic flow and API connections within n8n. Because I am focusing on systems logic rather than raw coding, I leveraged **Claude** to generate the specific data filtering and array-handling mechanics.

## 🚀 How This Site Is Maintained
This entire site is built using raw HTML/CSS and is deployed via **GitHub Pages**. I maintain and update it completely through the terminal using standard Git workflow routines (which I have to look up every single time):

```bash
git add .
git commit -m "Commit message"
git push origin main
