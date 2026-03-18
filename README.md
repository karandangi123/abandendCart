🚀 AI-Driven Abandoned Cart Recovery (RAG Orchestrator)
The Problem
Standard abandoned cart emails are generic and often ignored.

The Solution
I architected a RAG-based agentic workflow that:

-Ingests cart data via Webhooks.

-Contextualizes the user via Cohere Embeddings and a Supabase Vector Store.

-Reasons using a LangChain Agent to draft a bespoke recovery strategy.

-Automates logging to Google Sheets and high-value alerts to Slack.

🛠 Setup
1. docker-compose up -d

2. Import workflows/abandoned_cart_email.json.

3. Add credentials to .env.
