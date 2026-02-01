# Engagement  
This is a public-safe engagement guide.  

## What to send  
System type: chatbot | RAG | agent  
Access: staging link or transcripts  
Rules: what must always hold  
Docs: if the system should answer from docs  
Failure definition: what matters most  
Fix owner: who applies changes  

---

## MINIMUM REQUIREMENTS:
I start with a bounded baseline only.

Minimum packet:
- System type (chatbot | RAG | agent)
- Access (staging link OR 30 to 50 transcripts)
- Rules/constraints (what must always hold)
- If doc-based: the doc set or a small export
- Fix owner (who applies changes)

If any of the above is missing, I cannot run a fix-oriented loop.

## First step deliverable
First step is always the same:
- 10 to 20 test cases
- failure labels
- one patch recommendation
- retest plan

---

## What you receive  
Repro cases and evidence  
Failure map and severity  
Patch pack (prompt, retrieval, gating)  
Retest proof on the same cases  
Regression set for updates  
