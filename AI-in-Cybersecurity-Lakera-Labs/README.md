# AI in Cybersecurity — Lakera Agent Breaker Labs

Internship assignment for **Global Internship Program 2026 — Cyber Secured India**, covering AI red-teaming and prompt injection techniques against the Lakera Agent Breaker platform.

## Objective
Practice offensive AI security testing (prompt injection, system prompt extraction, tool schema extraction, and business logic bypass) against three simulated AI agents.

## Labs Completed

| Lab | Target | Attack Type | Score |
|---|---|---|---|
| Cycling Coach | System prompt extraction | Trust-based instruction disclosure | 100/100 |
| Thingularity | Tool/function name extraction | Reframed disclosure as documentation | 100/100 |
| CorpConnect Messenger | Email sender spoofing (BEC-style) | Delegated authority impersonation | 100/100 |

## Key Learnings
- AI agents can leak system prompts and internal tool schemas when requests are framed as legitimate QA/debug tasks.
- Conversational claims of authority (e.g., "I'm the admin") can bypass identity checks that should be enforced independently of the chat context.
- Output-side guardrails matter more than input filtering — an agent can follow its instructions correctly and still leak them if there's no check on what it's allowed to output.

## Submission
Full write-up with screenshots: `Global_Internship_MudasirZia_2026.pdf`

## Author
**Mudasir Zia** — [GitHub](https://github.com/CyberBros435) | [LinkedIn](https://www.linkedin.com/in/mudasir-zia-a535243b5/)