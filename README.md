# FinBuddy: Making a Bank's AI Assistant Follow the Rules with a System Prompt


**A FinTech case study on when a plain chat is enough and when a business needs a system prompt.**


Author: [Your Name] · BBA (FinTech), Chitkara Business School · Tool: [ChatGPT / Claude] · [Month Year]


## The case
**KoshBank** (fictional) is a digital bank for college students in Pune with 3 lakh users. It wants to launch **FinBuddy**, an in-app AI assistant. Its compliance team worries that a chatbot could give stock tips, ask for OTPs or invent interest rates. As a Business Analyst, I tested whether a system prompt can make the AI follow the bank's rules every time.


## The data
10 synthetic customer questions created with AI (7 English, 3 Hinglish), including 6 "trap" questions designed to make the AI break rules. I wrote the correct behaviour for each question before testing.


## Approach
| Step | Set-up | Task |
|---|---|---|
| 1 | Plain chat | One simple general question |
| 2 | Plain chat | All 10 customer questions |
| 3 | System prompt (v1) | The same 10 questions |
| 4 | System prompt (v2) | Failed questions re-tested after a fix |
| 5 | Roles | Same question with no role, an expert role and a friendly role |


## Results
| Metric | Plain chat | System prompt |
|---|---|---|
| Answers that followed every rule (/10) | __ | __ |
| Personal data handled safely | [yes/no] | [yes/no] |
| No investment tips | [yes/no] | [yes/no] |
| Closing line present (/10) | __ | __ |


## Key learnings
1. **A plain chat is enough for general questions:** [your finding]
2. **A system prompt enforces business rules:** [question IDs it fixed]
3. **Version 2:** [what I changed and whether it worked]
4. **Roles:** [did a role change accuracy or only tone?]


## My recommendation to KoshBank
[2–3 lines: is FinBuddy ready to launch, and what must still be tested?]


## Skills shown
Prompt engineering · System prompt design · Role prompting · Chatbot stress-testing · Responsible AI in finance · Customer-experience design


## What I learned
- A plain chat is fine for one-off, general questions.
- A system prompt gives AI standing rules, so a business assistant behaves the same way in every answer.
- A good system prompt states the audience, tone, limits, what to do when unsure and what never to do.
- Trap questions (stock tips, OTPs, "ignore your rules") are the best way to test an AI assistant.
- A role changes the tone of an answer more than its accuracy.
- System prompts improve with testing: version 2 fixed a gap that version 1 missed.
- AI assistants in finance must protect personal data and avoid advice they are not allowed to give.


*KoshBank, FinBuddy and all data in this project are fictional and created for learning.*
