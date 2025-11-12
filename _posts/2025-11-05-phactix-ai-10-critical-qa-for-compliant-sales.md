---
layout: post
title: "Phactix AI: 10 Critical Q&A for Compliant Pharma Sales"
author: Phactix AI Team
date: 2025-11-05 14:45:00 +0100
categories: [compliance, pharma, AI, sales enablement]
tags: [FDA, MSL, off-label, HIPAA, Jekyll, iPadOS]
image: /assets/images/Phactix_compliance_qa.png
---

# Phactix AI: 10 Critical Q&A for Compliant Pharma Sales

Our AI-driven platform, **Phactix**, is engineered to turn a major compliance risk—the unsolicited off-label question—into a win-win situation for both pharmaceutical companies and healthcare professionals (HCPs).

Here is a Q&A breakdown of how Phactix works within the strict US regulatory environment, focusing on FDA rules, hospital policies, and technical feasibility.

---

## **Compliance and Regulatory Questions**

### 1. **How does Phactix ensure compliance when an off-label question is asked?**

Phactix uses its local AI to instantly **identify** the off-label question as it's spoken. It then automatically triggers a mandatory compliance workflow:
1.  It flags the rep's iPad, providing compliant "bridge language" (e.g., "I can't answer, but our Medical Team can").
2.  It creates a locked, **Verbatim Transcription** of the question.
3.  It automatically populates and submits an **Unsolicited Request for Information (URI)** form to the Medical Science Liaison (MSL) team.
*The sales rep's only job is to acknowledge and escalate; they never answer.*

### 2. **Is recording a conversation legal in US hospitals? What about consent?**

Legality depends on state wiretapping laws ("One-Party" vs. "All-Party" consent) and, more critically, on the **hospital's internal policy**. Phactix requires the highest standard: **Explicit, All-Party Consent**.

The platform is designed to:
* Require **documented consent** from the doctor *before* transcription starts.
* The visibility of the **iPad's privacy indicator** provides clear, continuous visual confirmation that the transcription feature is active.

### 3. **How does Phactix avoid violating HIPAA by capturing audio?**

Phactix follows a **Consent-First, Audio-Minimal** approach:
* The AI performs **live, on-device transcription** on the iPad's Neural Engine.
* The raw audio file is **immediately discarded** from the device's temporary memory.
* Only the **encrypted text transcript** (the compliance record) is transferred to the secure Medical Affairs server. This minimizes PHI risk by eliminating storage and transit of sensitive audio.

### 4. **What is the final, auditable record Phactix provides to satisfy the FDA?**

Phactix generates a single, machine-readable JSON object (our **PSCM: Phactix Simple Compliance Model**) for every request. This record contains key audit-proof fields:
* The **Verbatim** Off-Label Question.
* The **System Timestamp** (Proving Contemporaneous documentation).
* The **Sales Rep's Confirmation** that they did *not* answer.
* Traceable links proving the Medical Affairs team provided a scientifically sourced response.

### 5. **How does Phactix maintain the required separation between Sales and Medical Affairs?**

The platform creates a **digital firewall**:
* The Sales Rep initiates the URI in their system (Commercial).
* The record is immediately transferred to the MSL's system (Medical Affairs).
* The Sales Rep is **prohibited** from seeing the final scientific response, and the MSL has no access to the rep's sales data.

---

## **Technical and Operational Questions**

### 6. **Why is the iPad the recommended device for running Phactix?**

The **Apple M-series or A-series chips** in modern iPads include a powerful, dedicated **Neural Engine**. This hardware is essential for:
* **High-Speed, On-Device Transcription:** Necessary to run the AI model locally without relying on internet speed.
* **Privacy:** Ensures the raw audio never leaves the company-issued device.

### 7. **Can Phactix run simultaneously with the e-detailer presentation software?**

**Yes.** Phactix utilizes **iPadOS Split View Multitasking**. The rep can run their presentation in the main window while the Phactix transcription log runs in a smaller, secure side panel. This allows for real-time compliance logging without interrupting the sales discussion.

### 8. **What is the primary benefit for the Doctor/Hospital?**

The primary benefit is **Speed, Accuracy, and Compliance Assurance**.
* The doctor's complex scientific question is captured **verbatim** and escalated instantly without error.
* They receive a **fast, accurate, and unbiased scientific response** from the MSL team, enabling better patient care decisions.

### 9. **What is the primary benefit for the Sales Rep?**

The rep's primary win is **Risk Reduction and Time Savings**.
* The AI instantly guides the rep into compliant behavior, eliminating the **fear of non-compliance** (a major sales hurdle).
* The platform automatically completes the lengthy URI paperwork, **saving 10-20 minutes of administrative work** per request.

### 10. **Is Phactix considered a "Safe Harbor" for off-label discussions?**

Phactix is not a "law," but an **enforcement discretion tool**. It is designed to perfectly execute the compliance steps outlined in the FDA Guidance, "Responding to Unsolicited Requests." By following the documented process and creating a perfect audit trail, Phactix ensures the company's actions fall within the FDA's established bounds for responding to unsolicited scientific inquiries.

---