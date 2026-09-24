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

## First Ten

**Medical distribution · Mexico · Evidence-backed GTM**

An independent application that turns a medical product catalog into a recommended commercial route: public procurement, physician conversations, or hospital purchasing. It keeps clinical interest, purchasing authority, and procurement eligibility separate.

[Explore First Ten](https://first-ten.casagarciachavez.chatgpt.site) · [Source code](https://github.com/Lattelicious/first-ten) · [Architecture and evaluation](https://github.com/Lattelicious/first-ten/blob/main/docs/EVALUATION.md)

Try the reviewed patient-monitoring and procedure-supply examples, compare recommendations, inspect evidence, and edit Spanish outreach drafts. Historical procurement examples are labeled. Live research is currently paused; the interactive showcase and reviewed examples are available.
