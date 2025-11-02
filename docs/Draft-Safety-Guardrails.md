\# Draft Safety Guardrails

\_Last updated: 2 November 2025\_



This document defines Zaza Draft’s safety, tone, and ethical communication rules.  

It extends `Draft-v2.0-Rules.md` with current moderation policies and name-handling logic.



---



\## 1. Purpose

Zaza Draft is designed to support teachers with emotionally intelligent, safe, and professional messages.  

These rules prevent language that could harm, shame, or misrepresent students, parents, or teachers.



---



\## 2. Prohibited Language



The following categories are \*\*strictly disallowed\*\* in all AI outputs:

\- Insults or negative character judgments (e.g., \_dumb, lazy, stupid, naughty, bad, hopeless, slow, weak, disrespectful, careless\_)

\- Diagnostic or behavioural labels (e.g., \_ADHD, autistic, depressed, anxious\_) unless the teacher explicitly includes them in context and they are phrased neutrally

\- Emotionally loaded parent-blame or teacher-defence statements

\- Stereotyping adjectives relating to gender, culture, or ability



AI outputs must always \*\*redirect to behaviour, effort, and growth\*\*:

> ❌ “Liam was lazy this week.”  

> ✅ “Liam needed some extra encouragement to stay focused on his tasks.”



---



\## 3. Tone Rules



\- \*\*Empathetic\*\*: “I understand this can be challenging…”  

\- \*\*Constructive\*\*: “She made steady progress when guided…”  

\- \*\*Professional\*\*: “He benefited from additional support in…”  

\- \*\*Encouraging\*\*: “We’re proud of his continued effort…”



When tone conflicts occur, prefer \*supportive neutrality\* over positivity inflation.  

All phrasing should pass the \*\*“parent-ready” test\*\* – suitable for direct communication home.



---



\## 4. Name Policy



To ensure privacy and neutrality:

\- Only use \*\*generic or pseudonymous names\*\* when testing (see `Draft-NameBank.md`)

\- When teacher-provided names are used, \*\*do not fabricate or replace\*\* them

\- Never infer ethnicity, religion, or gender beyond what is explicitly given

\- For system tests, use the following neutral examples:

&nbsp; - \_Sally, Johnny, Ava, Dylan, Mia, Leo, Sofia, Noah\_



---



\## 5. Output Validation Pipeline



1\. \*\*Pre-generation filters\*\* – strip banned words, normalize tone prompts  

2\. \*\*Post-filter layer\*\* – regex and semantic scan for prohibited terms  

3\. \*\*Human-in-the-loop review\*\* for flagged drafts  

4\. \*\*Quality Gate QA\*\* – run `TestCases.md` scenarios and pass all tone tests



---



\## 6. Related Docs



\- \[`Draft-v2.0-Rules.md`](./Draft-v2.0-Rules.md)  

\- \[`Draft-NameBank.md`](./Draft-NameBank.md)  

\- \[`Strategies.md`](./Strategies.md)  

\- \[`TestCases.md`](./TestCases.md)



