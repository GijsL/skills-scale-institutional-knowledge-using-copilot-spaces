# OctoAcme Risk Escalation Template

> **Purpose:** Provide a standardized format for escalating risks and blockers. This template addresses gaps identified in [Issue #4](https://github.com/GijsL/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) regarding unclear risk paths.

---

## Escalation Overview

### Escalation Levels

<!-- 
Rationale: Clear escalation paths ensure risks are addressed at the appropriate
level with proper urgency. This aligns with paths defined in octoacme-risks-and-communication.md
-->

| Level | Description | Typical Responders | Escalation Trigger |
|-------|-------------|-------------------|-------------------|
| **Level 1** | Team-level triage | Team members, Tech Lead | Daily standup, team Slack |
| **Level 2** | PM escalation | Project Manager, Product Lead | Blocker unresolved >24hrs, cross-team dependency |
| **Level 3** | Sponsor escalation | Sponsor, Executive | Business-impacting issue, budget/timeline risk |
| **Security** | Security incident | Security on-call, Security Engineer | Any security vulnerability or incident |

---

## Risk Escalation Form

### Risk Identification

| Field | Value |
|-------|-------|
| Date | |
| Reported By | |
| Risk ID (if in register) | |
| Project/Feature | |

### Risk Description

**Summary** (1-2 sentences):


**Detailed Description**:


**Impact if Not Addressed**:


### Risk Assessment

| Criteria | Rating | Notes |
|----------|--------|-------|
| Impact | ☐ High ☐ Medium ☐ Low | |
| Likelihood | ☐ High ☐ Medium ☐ Low | |
| Urgency | ☐ Critical ☐ High ☐ Medium ☐ Low | |

**Affected Stakeholders**:


### Current Status

| Status | Description |
|--------|-------------|
| ☐ Identified | Risk has been identified but not yet triaged |
| ☐ Triaged | Risk has been assessed and assigned |
| ☐ In Mitigation | Active work to address the risk |
| ☐ Escalated | Raised to higher level for resolution |
| ☐ Resolved | Risk has been mitigated or accepted |

### Escalation Request

**Requested Escalation Level:** ☐ Level 1 ☐ Level 2 ☐ Level 3 ☐ Security

**Reason for Escalation**:


**Decision or Support Needed**:


**Proposed Mitigation Options**:
1. 
2. 
3. 

**Recommended Option**:


### Response Timeline

| Urgency | Expected Response | Expected Resolution |
|---------|-------------------|---------------------|
| Critical | Within 1 hour | Within 4 hours |
| High | Within 4 hours | Within 1 business day |
| Medium | Within 1 business day | Within 1 week |
| Low | Within 1 week | As capacity allows |

---

## Escalation Path by Role

<!-- 
Rationale: Role-specific paths ensure team members know who to contact based
on the type of risk. Aligns with interactions defined in octoacme-roles-and-personas.md
-->

### Technical Risks (Code, Architecture, Performance)
1. **Developer** → Tech Lead → PM → Product Lead
2. Involve: Security Engineer (if security-related), DevOps (if infrastructure-related)

### Schedule/Resource Risks
1. **PM** → Product Lead → Sponsor
2. Involve: Stakeholders (for timeline impacts)

### Security Risks
1. **Any role** → Security Engineer → Security on-call
2. Follow security incident runbook
3. Notify PM for coordination

### Quality Risks
1. **QA/Tester** → PM → Product Lead
2. Involve: Developers (for bug resolution)

### User/Customer Risks
1. **Customer Support** → PdM → Product Lead
2. Involve: Developers (for urgent fixes)

### Business/Requirements Risks
1. **Business Analyst** → PdM → Stakeholder → Sponsor
2. Involve: PM (for impact assessment)

---

## Escalation Communication Template

### For Level 1-2 Escalations (Slack/Email)

```
🚨 Risk Escalation: [Brief Summary]

**Risk ID:** [if applicable]
**Project:** [Project Name]
**Urgency:** [Critical/High/Medium/Low]

**Issue:** [1-2 sentence description]

**Impact:** [What happens if not addressed]

**Ask:** [What decision or help is needed]

**Proposed Options:**
1. [Option 1]
2. [Option 2]

**Deadline for Decision:** [Date/Time]

cc: [relevant stakeholders]
```

### For Level 3 Escalations (Meeting Request)

```
Subject: [ESCALATION] [Project Name] - [Brief Summary]

Requesting urgent meeting to discuss:
- Risk: [Brief description]
- Impact: [Business impact]
- Decision needed by: [Date]

Attendees needed: [Sponsor], [Product Lead], [PM]
Proposed time: [Time options]

Background document: [Link to risk details]
```

### For Security Escalations

```
🔒 Security Alert: [Classification]

**Severity:** [Critical/High/Medium/Low]
**Discovered:** [Date/Time]
**Reporter:** [Name]

**Summary:** [What was found]

**Immediate Actions Taken:**
1. [Action]
2. [Action]

**Next Steps:** [What's being done]

**Contact:** Security on-call: [contact info]

DO NOT share details outside security channel.
```

---

## Post-Escalation Follow-Up

### Required Actions
- [ ] Risk register updated with escalation details
- [ ] Decision documented
- [ ] Mitigation plan assigned and tracked
- [ ] Stakeholders notified of outcome
- [ ] Retrospective item created (if systemic issue)

### Documentation
| Field | Value |
|-------|-------|
| Resolution Date | |
| Decision Made | |
| Decision Maker | |
| Outcome | |
| Lessons Learned | |

---

## Related Documentation

- [Risks and Communication](../octoacme-risks-and-communication.md)
- [Roles and Personas](../octoacme-roles-and-personas.md)
- [Execution and Tracking](../octoacme-execution-and-tracking.md)
- [Onboarding Checklist](onboarding-checklist.md)

---

## Change History

| Date | Change | Reference |
|------|--------|-----------|
| Initial | Created risk escalation template | [Issue #4](https://github.com/GijsL/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) |
