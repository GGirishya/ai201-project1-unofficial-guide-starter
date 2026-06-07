# Project 1 Planning: The Unofficial Guide

> Write this document before you write any pipeline code.
> Your spec and architecture diagram are what you'll use to direct AI tools (Claude, Copilot, etc.) to generate your implementation — the more specific they are, the more useful the generated code will be.
> Update the Retrieval Approach and Chunking Strategy sections if you change your approach during implementation.
> Update this file before starting any stretch features.

---

## Domain

 The system covers community-driven, unofficial student reviews, grading trends, exam structures, and teaching styles for faculty within the Computer Science Department at Missouri State University (MSU).


     This knowledge is very important especially for CS students trying to balance heavy programming workloads with other coursework, because it is very critical to feel the gaps with the proper channels. The catalog from the official department does not relect what actuallt happens in class.

---

## Documents

<!-- List your specific sources: URLs, subreddit names, forum threads, or file descriptions.
     Aim for at least 10 sources that together cover different subtopics or perspectives within your domain. -->

| # | Source | Type | URL or file path |
|---|--------|------|-----------------|
| 1 | r/missouristate - "Computer Science Students?"| Subreddit Thread| [https://www.reddit.com/r/missouristate/comments/i0qp21/computer_science_students/](https://www.reddit.com/r/missouristate/comments/i0qp21/computer_science_students/)|
| 2 | r/missouristate - "Computer Science at MSU"| Subreddit Thread| [https://www.reddit.com/r/missouristate/comments/jmzz5g/computer_science_at_msu/](https://www.reddit.com/r/missouristate/comments/jmzz5g/computer_science_at_msu/)|
| 3 | r/missouristate - "Will MSU be worth it for me?" (CS review)| Subreddit Thread| |[https://www.reddit.com/r/missouristate/comments/sin703/will_missouri_state_university_be_worth_it_for_me/](https://www.reddit.com/r/missouristate/comments/sin703/will_missouri_state_university_be_worth_it_for_me/)
| 4 | RateMyProfessors - MSU Computer Science Faculty Index| Public Review Site| https://www.ratemyprofessors.com/search/professors/936?q=*&did=11|
| 5 | r/missouristate-Will Missouri State University be worth it for me?|Subreddit Thread | https://www.reddit.com/r/missouristate/comments/sin703/will_missouri_state_university_be_worth_it_for_me/|
| 6 | RateMyProfessors-Jamil saquel |Public Review Site |https://www.ratemyprofessors.com/professor/109481 |
| 7 | RateMyProfessors-Rahul dubey |Public Review Site |https://www.ratemyprofessors.com/professor/3092556 |
| 8 | RateMyProfessors-siming Liu |Public Review Site  |https://www.ratemyprofessors.com/professor/2593599 |
| 9 | RateMyProfessors-Hui Liu |Public Review Site | https://www.ratemyprofessors.com/professor/1071783|
| 10 | RateMyProfessors-Mukulika Ghosh| Public Review Site|https://www.ratemyprofessors.com/professor/2879300 |
---

## Chunking Strategy

<!-- How will you split documents into chunks?
     State your chunk size (in tokens or characters), overlap size, and explain why those
     numbers fit the structure of your documents.
     A review-heavy corpus warrants different chunking than a long FAQ. -->

**Chunk size:**

**Overlap:**

**Reasoning:**

---

## Retrieval Approach

<!-- Which embedding model are you using (e.g., all-MiniLM-L6-v2 via sentence-transformers)?
     How many chunks will you retrieve per query (top-k)?
     If you were deploying this for real users and cost wasn't a constraint, what tradeoffs
     would you weigh in choosing a different embedding model — context length, multilingual
     support, accuracy on domain-specific text, latency? -->

**Embedding model:**

**Top-k:**

**Production tradeoff reflection:**

---

## Evaluation Plan

<!-- List your 5 test questions with their expected correct answers.
     Questions should be specific enough that you can judge whether the system's response
     is right or wrong. "What are good dining halls?" is too vague.
     "What do students say about wait times at [dining hall name] during lunch?" is testable. -->

| # | Question | Expected answer |
|---|----------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

## Anticipated Challenges

<!-- What could go wrong? Name at least two specific risks with reasoning.
     Consider: noisy or inconsistent documents, missing source attribution, off-topic
     retrieval, chunks that split key information across boundaries. -->

1.

2.

---

## Architecture

<!-- Draw a diagram of your pipeline showing the five stages:
     Document Ingestion → Chunking → Embedding + Vector Store → Retrieval → Generation
     Label each stage with the tool or library you're using.
     You can use ASCII art, a Mermaid diagram, or embed a sketch as an image.
     You'll use this diagram as context when prompting AI tools to implement each stage. -->

---

## AI Tool Plan

<!-- For each part of the pipeline below, describe:
     - Which AI tool you plan to use (Claude, Copilot, ChatGPT, etc.)
     - What you'll give it as input (which sections of this planning.md, which requirements)
     - What you expect it to produce
     - How you'll verify the output matches your spec

     "I'll use AI to help me code" is not a plan.
     "I'll give Claude my Chunking Strategy section and ask it to implement chunk_text()
     with my specified chunk size and overlap" is a plan. -->

**Milestone 3 — Ingestion and chunking:**

**Milestone 4 — Embedding and retrieval:**

**Milestone 5 — Generation and interface:**
