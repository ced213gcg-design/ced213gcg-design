# Investigation Report

## Case Title
SOC Analyst Lab – Suspicious Traffic Review

## Analyst
Cedrick Green

## Investigation Goal
Review the triggered alert, inspect the available traffic evidence, determine the likely cause of the suspicious activity, and recommend the next defensive action.

---

## Scope
This investigation focuses on:
- suspicious network communication
- traffic patterns
- observable indicators
- possible security implications

---

## Evidence Reviewed
- alert details
- packet or traffic screenshots
- destination behavior
- communication pattern characteristics

---

## Analysis

### 1. Alert Review
The alert suggested unusual or potentially unauthorized network activity. Initial review indicated that the communication pattern was outside expected baseline behavior and required closer examination.

### 2. Traffic Examination
Traffic review focused on the source and destination relationship, the protocol behavior, and whether the communication appeared normal, repetitive, or suspicious. The activity was treated as suspicious until evidence suggested otherwise.

### 3. Risk Consideration
The key risk questions were:
- is the destination trusted?
- is the communication pattern normal for the host?
- does the traffic suggest scanning, staging, or transfer behavior?
- is escalation required?

### 4. Analyst Judgment
Based on the reviewed evidence, the traffic should be treated as suspicious pending environmental validation. Even if the activity is ultimately benign, the alert demonstrates the importance of disciplined triage and documentation.

---

## Conclusion
The alert represents activity that justifies analyst review and structured documentation. The evidence did not support immediate dismissal without validation. This reinforces a defensive workflow of verify first, then classify.

---

## Recommended Actions
- validate destination legitimacy
- compare activity against known baseline behavior
- review additional logs if available
- escalate if repeated or correlated with other suspicious indicators
- document findings for future reference

---

## Severity
**Medium**

Reason:
The activity is suspicious enough to require review, but the evidence currently available does not confirm a critical incident without further context.
