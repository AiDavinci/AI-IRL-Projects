AI-IRL-Projects

AI Experiments & Research-Level Projects by AiDavinci (AKA Kannan)

🚀 Why This Repo Exists

This repository is a sandbox of AI experiments, prototypes, and full-fledged projects — not just tutorials. The goal: push boundaries. If something breaks, it breaks. If it surprises you, that’s good.

Here you’ll find work in:

Agent systems (browser agents, autonomous bots)

Retrieval-augmented generation and knowledge systems (RAG)

Email automation, outreach, and bot infrastructures

Integrations of AI with real-world tools (APIs, pipelines)

Exploratory projects—because we learn by building

This is not polished production code (though some parts might be). It’s research, hacking, iteration, and continuous failure+improvement.

📂 Repository Structure (Proposed / Existing)

Below is a rough view and what each folder is / should be:

AI-IRL-Projects/


├── ai-browser-agent-bot/       — autonomous browser-based agent experiments  
├── AI-Email-gtm-outreach-bot/   — projects around email outreach automation  
├── rag-projects/                — RAG, retrieval + embedding / knowledge systems  
├── README.md                     — this file  
└── … (future modules)  


Each module should contain:

A short README of its own (what it does, how to run it)

Code (scripts, notebooks, modules)

Dependencies (e.g. requirements.txt or poetry.lock)

Examples, test inputs, output samples

🧰 Requirements & Setup

Language / Runtime: Primarily Python (≥ 3.8)

Dependencies: Each subproject should list requirements (e.g. via requirements.txt)

API Keys / Credentials: Some projects will need credentials (OpenAI key, browser automation tokens, etc.)

Environment Management: Use venv, pipenv, poetry, Docker, or similar

Hardware Needs: Mostly CPU; GPU optional depending on model usage

📌 How to Get Started

Clone the repo

git clone https://github.com/AiDavinci/AI-IRL-Projects.git  
cd AI-IRL-Projects  


Pick a module / folder you want to explore / run

Read that module’s README

Install dependencies

Setup your API keys or credentials

Run example scripts / notebooks

Tinker, break, build

✅ Projects / Highlights

Here are some projects you’ll find (or plan to find) here:

Project	Purpose / Idea
ai-browser-agent-bot	An AI agent that can browse web pages, interact with them, scrape, take actions in a browser environment
AI-Email-gtm-outreach-bot	Automating targeted email outreach, integrating tracking / GTM / campaign logic
rag-projects	Systems combining embeddings, vector databases, and LLMs to do context + knowledge retrieval

You can expand this list as you add modules.

🧩 Contribution & Roadmap

This repo is mostly mine (AiDavinci) experimenting. But if you want to:

See a new kind of AI experiment here? Open an issue / proposal

Found a bug / improvement? Submit a PR

Fork, remix, use code as you like — that’s the point

Planned directions (not guaranteed):

More agent experiments (multi-agent, social, real-world)

Better RAG pipelines, knowledge graphs

Integration with UI / web frontends

Packaging stable modules into libraries

🛠 Best Practices & Style

Keep modules isolated — don’t let one experiment bleed into another

Use version control, commit often

Document assumptions, limitations

Include small test / demo inputs so others can see it run

Use logging, not print, for experiments

Make it reproducible — list seeds, random states, env configs

⚠️ Disclaimer

This is bleeding–edge, experimental work. Things will break. Code is not always “beautiful.” Use at your own risk. Don’t expect enterprise support.
