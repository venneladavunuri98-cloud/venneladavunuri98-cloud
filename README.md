# Hi, I'm Vennela 👋

I'm an AI automation engineer at Synergistic AI Solutions in Hyderabad, India. I build AI agents and workflow automations that connect to real business systems, make structured decisions, and hand off to a person when a decision needs one.

Most of my work happens where an LLM meets a business process: classifying and routing requests, answering from a knowledge base, calling APIs, booking appointments by voice and qualifying leads. Around the model I add validation, human approval steps, logging and failure paths, which is what makes a workflow safe to run in a real business.

I'm open to AI automation roles and freelance projects.

## What I build

- AI agents and LLM workflows that classify, route and call tools, with iteration caps and human approval where the stakes are high
- Voice AI agents on Vapi for bookings and support, including multilingual restaurant and healthcare appointment flows
- RAG chatbots that answer from source content and cite it
- Integrations with REST APIs, webhooks, Gmail, Google Sheets, Supabase, and lead and CRM tools such as Apollo and Meta Lead Ads
- Insurance claims intake (FNOL) and healthcare appointment scheduling workflows

## Featured project

### [GuardedReview](https://github.com/venneladavunuri98-cloud/guardedreview): human-in-the-loop AI code review in n8n

AI code review for regulated codebases. The workflow redacts secrets and personal data before the LLM call and checks the model's output in code. A person approves each review in Slack before it is posted, and every decision goes into an insert-only Postgres audit log.

`n8n` · `LLM` · `Slack` · `PostgreSQL` · `AI governance`

Next on my list to publish: an RFP evaluator with citation-checked scoring (LangGraph), voice AI booking agents, and an insurance FNOL intake workflow.

## Tech stack

Automation and AI: n8n · Vapi · OpenAI and other LLM APIs · LangGraph · RAG · prompt engineering

Data and integrations: REST APIs · webhooks · Supabase · PostgreSQL · Google Sheets · Gmail · Apollo · Meta Lead Ads

Languages: Python · JavaScript · SQL

## How I build

Anything consequential passes a code check or a person before it takes effect. When a model returns bad output, the workflow raises an alert and stops there. Every decision is logged, so I can explain later what happened and why.

## Contact

[LinkedIn](https://www.linkedin.com/in/venneladavunuri) · [Portfolio](https://portfolio-vennela3.vercel.app)

I write on LinkedIn about agent reliability, human-in-the-loop design and RAG quality, mostly about what broke in a build and what I changed.
