# Hi, I'm Vennela 👋

I'm an AI automation engineer at Synergistic AI Solutions in Hyderabad, India. I build AI agents and workflow automations that connect to real business systems, make structured decisions, and hand off to a person when a decision needs one.

Most of my work happens where an LLM meets a business process: classifying and routing requests, answering from a knowledge base, calling APIs, booking appointments by voice and qualifying leads. Around the model I add validation, human approval steps, logging and failure paths, which is what makes a workflow safe to run in a real business.

I'm open to AI automation roles and freelance projects.

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**RFP Intelligence Platform**](https://github.com/venneladavunuri98-cloud/RFP-Intelligence-Platform) | Turns a tender PDF into a scored go/no-go draft. Every scored fact points to a page and an exact quote that Python verifies, and a person makes the final call. 83–93% requirement recall on 3 public Indian government RFPs, with 165 tests. | LangGraph · Gemini · pgvector · FastAPI · Streamlit · n8n |
| [**AI Outbound Sales Caller**](https://github.com/venneladavunuri98-cloud/ai-outbound-sales-caller) | A lead row becomes a researched, grounded phone pitch. The do-not-call list, calling hours and retries are enforced in code, and a meeting is booked only when the transcript quotes the agreed time and email. | n8n · OpenAI · OmniDimension · Google Workspace |
| [**AI Lead Finder**](https://github.com/venneladavunuri98-cloud/ai-lead-finder) | One form in, a ranked list of sales-ready leads out. It searches Apollo, skips dead sites, detects buying signals, finds the decision maker, has an LLM analyse each company and computes a 0–100 score in code. | n8n · Apollo API · OpenAI · Google Sheets |
| [**Restaurant Voice Ordering Agent**](https://github.com/venneladavunuri98-cloud/restaurant-voice-ordering-agent) | A phone agent that answers only from live menu data, captures allergy notes word for word, logs every tool call, and hands each confirmed order to staff. | n8n · PostgreSQL · voice AI |
| [**Prior Authorization Approval**](https://github.com/venneladavunuri98-cloud/prior-authorization-approval) | A physician's one-click approval becomes a payer submission. Links are single-use, patient data is decrypted only at submission, eligibility is checked first, and denials get an AI-drafted appeal. | n8n · Supabase · Availity · OpenAI |
| [**GuardedReview**](https://github.com/venneladavunuri98-cloud/guardedreview) | AI code review for regulated codebases: secrets and personal data are redacted before the LLM call, a person approves each review in Slack, and decisions go to an insert-only audit log. | n8n · LLM · Slack · PostgreSQL |

More workflows, including a RAG support chatbot, a hospital voice appointment assistant and insurance quote and renewal automations, are in [**n8n-ai-workflows**](https://github.com/venneladavunuri98-cloud/n8n-ai-workflows).

## What I build

- AI agents and LLM workflows that classify, route and call tools, with iteration caps and human approval where the stakes are high
- Voice AI agents (Vapi, OmniDimension) for ordering, bookings, support and outbound sales calls
- RAG chatbots that answer from source content and cite it
- Integrations with REST APIs, webhooks, Gmail, Google Sheets, Supabase, and lead and CRM tools such as Apollo and Meta Lead Ads
- Healthcare and insurance workflows: appointment scheduling, prior authorization, quotes, renewals and claims intake

## Tech stack

Automation and AI: n8n · Vapi · OpenAI, Gemini and other LLM APIs · LangGraph · RAG · prompt engineering

Data and integrations: REST APIs · webhooks · Supabase · PostgreSQL · pgvector · Google Sheets · Gmail · Apollo · Meta Lead Ads

Languages and frameworks: Python · FastAPI · JavaScript · SQL

## How I build

Anything consequential passes a code check or a person before it takes effect. When a model returns bad output, the workflow raises an alert and stops there. Every decision is logged, so I can explain later what happened and why.

Every public workflow here is sanitized before it's pushed: no API keys, credential IDs or real customer data.

## Contact

[LinkedIn](https://www.linkedin.com/in/venneladavunuri) · [Portfolio](https://portfolio-vennela3.vercel.app)

I write on LinkedIn about agent reliability, human-in-the-loop design and RAG quality, mostly about what broke in a build and what I changed.
