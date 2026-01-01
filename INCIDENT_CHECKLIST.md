# Incident Response Checklist (Generic)

This checklist outlines a disciplined, repeatable approach to handling operational incidents in Linux-based environments.  
It is intentionally generic and focuses on decision-making rather than technical implementation.

---

## 1. Initial Response
- Remain calm and avoid premature assumptions
- Acknowledge the incident or alert
- Determine whether the issue is ongoing or historical
- Establish a single point of focus for the intervention

---

## 2. Verification
- Confirm the issue using at least two independent signals
- Identify the affected service at a high level
- Distinguish symptoms from potential causes
- Avoid acting solely on incomplete or anecdotal information

---

## 3. Stabilisation
- Prioritise service stability over optimisation
- Apply minimal, reversible actions where possible
- Avoid simultaneous or overlapping changes
- Observe system behaviour after each action

---

## 4. Escalation and Communication
- Escalate only when necessary and with clear context
- Communicate facts, not hypotheses
- Keep messages concise and timestamped
- Avoid unnecessary technical detail during active incidents

---

## 5. Resolution
- Confirm service recovery using the same signals used for detection
- Monitor for recurrence or secondary effects
- Do not introduce new changes immediately after recovery

---

## 6. Post-Incident Actions
- Document what happened, what was observed, and what was done
- Identify procedural improvements
- Update relevant documentation or checklists
- Close the incident only when stability is confirmed

---

> This checklist reflects my general operational discipline and does not reference any specific production system.
