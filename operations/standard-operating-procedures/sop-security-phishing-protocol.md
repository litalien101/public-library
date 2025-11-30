# SOP-Security-Phishing-Protocol

**Version:** v1.0  
**Effective Date:** 2025-11-30  
**Audience:** Moderators, Conduct Officers, Technical Teams  
**Linked Annex:** Annex E.1 — Security Protocols  
**Status:** Binding  

---

## 1. Purpose
Protect Guardian Override systems and contributors from phishing, credential theft, and security breaches.

---

## 2. Scope
Applies to moderators, Conduct Officers, and technical teams.

---

## 3. Responsibilities
- **Moderators:** Report suspicious activity, initiate account restrictions, and escalate cases.  
- **Conduct Officers:** Review escalated cases, enforce restrictions, and coordinate with governance.  
- **Technical Teams:** Perform scans, maintain detection systems, and ensure evidence is securely stored.  
- **Governance Team:** Review systemic risks and oversee quarterly/annual audits.  

---

## 4. Procedure

### Detection
- [ ] Automated scans + moderator reports for suspicious links, credential requests, exploit code.

### Immediate Action
- [ ] Restrict contributor account within 24h.  
- [ ] Escalate to Conduct Officers.  
- [ ] Notify governance if systemic risk detected.

### Classification
- [ ] Minor: accidental insecure link → advisory.  
- [ ] Moderate: repeated insecure practices → restriction.  
- [ ] Critical: phishing, exploit code, credential theft → suspension + law enforcement referral.

### Documentation
- [ ] Case logged in MEI Appendix E.1.  
- [ ] Evidence stored encrypted.

### Audit
- [ ] Annual penetration testing.  
- [ ] Quarterly security incident reports.

---

### Workflow Diagram
```mermaid
flowchart TD
    A[Detection] --> B[Immediate Action]
    B --> C{Classification}
    C -->|Minor| D[Advisory Notice]
    C -->|Moderate| E[Restriction]
    C -->|Critical| F[Suspension + Law Enforcement]
    F --> G[Documentation]
    E --> G
    D --> G
    G --> H[Audit & Reports]
