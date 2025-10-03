AI-IRL-Projects
AI Experiments & Research-Level Projects by AiDavinci (Aka - Kannan)

🚀 Why This Repo Exists

This repository is a sandbox of AI experiments, prototypes, and full-fledged projects — not just tutorials. The goal: push boundaries. If something breaks, it breaks. If it surprises you, that’s good.

Here you’ll find work in:

1. Agent systems (browser agents, autonomous bots)
 
2. Retrieval-augmented generation and knowledge systems (RAG)

3. Email automation, outreach, and bot infrastructures

4. Integrations of AI with real-world tools (APIs, pipelines)

5. Exploratory projects—because we learn by building

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

1. A short README of its own (what it does, how to run it)

2. Code (scripts, notebooks, modules)

3. Dependencies (e.g. requirements.txt or poetry.lock)

4. Examples, test inputs, output samples


🧰 Requirements & Setup

1. Language / Runtime: Primarily Python (≥ 3.8)

2. Dependencies: Each subproject should list requirements (e.g. via requirements.txt)

3. API Keys / Credentials: Some projects will need credentials (OpenAI key, browser automation tokens, etc.)

4. Environment Management: Use venv, pipenv, poetry, Docker, or similar

5. Hardware Needs: Mostly CPU; GPU optional depending on model usage


📌 How to Get Started

Clone the repo
git clone https://github.com/AiDavinci/AI-IRL-Projects.git  
cd AI-IRL-Projects  


1. Pick a module / folder you want to explore / run

2. Read that module’s README

3. Install dependencies

4. Setup your API keys or credentials

5. Run example scripts / notebooks

6. Tinker, break, build

   

✅ Projects / Highlights

Here are some projects you’ll find (or plan to find) here:

Project	Purpose / Idea
1. ai-browser-agent-bot	An AI agent that can browse web pages, interact with them, scrape, take actions in a browser environment
2. AI-Email-gtm-outreach-bot	Automating targeted email outreach, integrating tracking / GTM / campaign logic
3. rag-projects	Systems combining embeddings, vector databases, and LLMs to do context + knowledge retrieval

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
