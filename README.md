# Featured applications

## Adrenal Nodule Clinic Navigator

**Patient education · Document-grounded AI · Accessible web experience**

A collaborative web application that helps people understand adrenal nodules, prepare for testing, and navigate the next steps in their care.

### [Open the application →](https://cs620-uw-surgery.vercel.app/chat)

[Explore the current source code](https://github.com/cs620-UW-Surgery/cs620-UW-Surgery) · [Architecture and developer guide](https://github.com/cs620-UW-Surgery/cs620-UW-Surgery/blob/main/HANDOFF.md)

### What it does

- Answers questions using reference documents, with source citations and a PDF viewer.
- Uses a multi-stage AI pipeline to evaluate safety, interpret questions, and check scope.
- Presents guidance through chat, care checklists, and testing instructions.
- Supports voice input, read-aloud responses, large text, and high-contrast viewing.

### My contributions

- Built the initial full-stack prototype, including the chat interface, dialogue engine, document retrieval, and persistence layer.
- Implemented the initial three-stage agent processing approach.
- Refined question-scope handling and response-card routing.

The current application was developed with a team; the linked repository preserves the full contribution history.

**Stack:** TypeScript · React · Next.js · PostgreSQL · Prisma · OpenAI · Tailwind CSS

**Try it:** Ask “What is an adrenal nodule?” to explore the conversation and cited sources.

*Designed for general education and care navigation.*

## First Ten — work in progress

**Medical distribution · Mexico · Go-to-market research**

I recently worked with a medical distribution company. The specific demands of the industry inspired me to begin developing this application.

First Ten explores how a medical product catalog can guide the choice between **licitaciones**, **direct physician relationships**, and **direct hospital sales**. Public procurement connects suppliers with institutional purchasing; physician relationships help establish clinical fit; hospital conversations address purchasing, technical evaluation, and service needs.

The primary approach depends on the devices being sold. Hospital-scale monitoring may call for procurement and hospital contacts, while procedure-specific products may start with physicians and then the facility's purchasing team. These channels often work in tandem, so the application recommends an approach for each product family.

[Explore the prototype](https://first-ten.casagarciachavez.chatgpt.site) · [Source code](https://github.com/Lattelicious/first-ten) · [Architecture](https://github.com/Lattelicious/first-ten/blob/main/docs/ARCHITECTURE.md) · [Evaluation](https://github.com/Lattelicious/first-ten/blob/main/docs/EVALUATION.md)

Development is ongoing. The current prototype includes catalog intake, route recommendations, reviewed examples, live research, and editable Spanish outreach drafts.
