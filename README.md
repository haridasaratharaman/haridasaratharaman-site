haridasaratharaman.com

Personal website of Hari Dasaratharaman, a product leader for AI and enterprise platforms.

Live site: https://haridasaratharaman.com

What's here

The home page covers my background, focus areas (agentic AI, AI quality, platforms at scale), and experience at Genesys, OpenText, Oracle, Amazon, and Vodafone.

It also introduces a project in progress: an AI conversation auditor. You paste any AI chatbot conversation and choose what to check, such as abusive language, personal data, prompt injection, off-policy promises, or hallucination. An agent then picks the right model for each check, runs the checks as tools on an MCP server, and returns a ship, review, or block verdict with evidence, cost, and latency.

How it's built
A single static index.html with inline CSS, so there's no build step or framework.
Hosted on Vercel, which redeploys automatically on every push to main.
Domain registered with Porkbun.
Supports light and dark mode, and is responsive down to mobile.
Structure
index.html   Home page
README.md    This file

The auditor will be added at /auditor with its own backend, guardrails, and evaluation scripts.

Roadmap
 Home page
 AI conversation auditor: evaluation core and rubric
 Model comparison across judge models
 Guardrails for input, output, and policy
 MCP server for the evaluation tools
 Agentic workflow that plans and routes checks
 Observability: traces, cost, latency, and a dashboard
Contact
LinkedIn: https://www.linkedin.com/in/hdasaratharaman
Email: dhariharan23@gmail.com

Views and projects here are my own and use no employer data.
