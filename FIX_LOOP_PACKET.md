# Fix Loop Packet (Template)  
Author: Alyssa Solen | Origin  
Classification: TIER-0 SAFE (no private materials)  

## 0) Scope
System type: (chatbot | RAG | agent | copilot)  
Domain: (support | HR | real estate | internal ops | other)  
What is being tested (one sentence):  
Out of scope (one sentence):  

## 1) Inputs Provided (what you hand me)
Access method: (staging link | transcripts | screenshots)  
Docs/KB provided: (yes/no, description)  
Rules/constraints provided: (yes/no, description)  
Who applies fixes: (me | their team | unknown)  

## 2) Success Criteria (what "fixed" means)  
Primary failure to eliminate:  
Secondary failures to reduce:  
Rules that must always hold:  

## 3) Test Set
Number of cases:  
How cases were selected: (top intents | risky edge cases | both)  

### Test Cases (table)
ID | User Input | Expected Behavior | Evidence Source (doc/constraint) | Observed Output | Pass/Fail | Failure Type  
---|-----------|-------------------|----------------------------------|----------------|----------|------------  
T01|           |                   |                                  |                |          |  
T02|           |                   |                                  |                |          |  
T03|           |                   |                                  |                |          |  

Failure Types allowed:  
- retrieval_miss  
- hallucination  
- constraint_violation  
- uncertainty_fail  

## 4) Findings Summary  
Total cases:  
Pass:  
Fail:  
Failures by type:  
- retrieval_miss:  
- hallucination:  
- constraint_violation:  
- uncertainty_fail:  

Top 3 failures (short):  
1)  
2)  
3)  

## 5) Patch Pack (what I hand back to fix it)  
### Patch A: Prompt / Instruction Patch  
What to change:  
Copy/paste patch text:  

### Patch B: Retrieval / Knowledge Patch (if applicable)  
What to change:  
Config suggestions (plain language):  

### Patch C: Tool Gating / Safety Patch (if applicable)   
What to change:  

## 6) Retest Proof  
Retest date:  
Same test set rerun: (yes/no)  
Before: __ fails / __ total  
After:  __ fails / __ total  
What improved:  
What still fails:  

## 7) Regression Plan   
What to rerun after any update:  
Frequency: (every model update | weekly | monthly)  
Owner: (who runs it)  
