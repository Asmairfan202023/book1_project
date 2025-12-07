---
id: 001
title: Create Constitution for AI Textbook
stage: constitution
date: 2025-12-07
surface: agent
model: gemini
feature: none
branch: master
user: user
command: /sp.constitution
labels: ["constitution", "textbook", "AI"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
 - .specify/memory/constitution.md
 - .specify/templates/plan-template.md
tests:
[]
---

## Prompt

/sp.constitution Create a Constitution for my textbook project on **Physical AI and Humanoid Robotics**. The textbook will be 5,000–7,000 words and used in a university-level CS course.

Include the following:

CORE PRINCIPLES
- Accuracy based on primary, verifiable sources
- Clarity for academic readers (CS background)
- Reproducibility with traceable citations
- Rigor using peer-reviewed research

STANDARDS
- All factual claims must be source-verified
- APA citation style
- Minimum 15 sources, at least 50% peer-reviewed
- Writing clarity: Flesch-Kincaid Grade 10–12
- Zero plagiarism tolerance

CONSTRAINTS
- Word count: 5,000–7,000
- PDF format with embedded citations
- Integrate concepts from prior book on AI Agents
- Ensure consistency in terminology and definitions

SUCCESS CRITERIA
- All claims verified and traceable
- At least 50% peer-reviewed sources
- Passes plagiarism and fact-checking review
- Meets all clarity and formatting standards

AGENT TASKS
- Generate `.specify/memory/constitution.md`
- Document all standards, principles, constraints, and success criteria
- Display the final Constitution after creation

End.

## Response snapshot

I have successfully created the project constitution and updated the relevant project templates. The constitution is now available at `.specify/memory/constitution.md`.

## Outcome

- ✅ Impact: Created a new project constitution and updated related templates.
- 🧪 Tests: No tests were run.
- 📁 Files: 
  - `.specify/memory/constitution.md` (created)
  - `.specify/templates/plan-template.md` (modified)
- 🔁 Next prompts: The user can now proceed with other commands like `/sp.plan` or `/sp.spec`.
- 🧠 Reflection: The process of creating the constitution and updating the templates was successful. The agent-native fallback for PHR creation worked as expected.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): PASS
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): n/a
