🧠 Vercel AI SDK Deep Research
This project is an AI-powered autonomous research agent that combines the Vercel AI SDK with Exa for real-time web search and information synthesis.

It works by:

Generating intelligent search queries based on a user prompt.

Scraping and extracting relevant content from the web using Exa’s API.

Evaluating and filtering the results for relevance with the help of GPT-4o.

Iteratively generating follow-up questions to deepen the research.

Producing a detailed, organized research report in Markdown format.

✨ Features
Autonomous multi-step web research.

Dynamic query generation and refinement.

Relevance evaluation of search results.

Insight extraction with learning summaries and follow-up questions.

Final report generation powered by LLMs.

🏗️ Tech Stack
Vercel AI SDK (@ai-sdk/openai)

Exa API for live web search

TypeScript + Node.js

OpenAI GPT-4o

Zod for schema validation

File output in Markdown (report.md)

📄 Example Use Case
“What do you need to be a D1 shotput athlete?”

The agent searches the web, synthesizes the information, generates structured learnings, and delivers a detailed report including relevant links, insights, and further questions for deep exploration.
