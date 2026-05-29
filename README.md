# Phishing Email Detection & Awareness Report

## Overview
This repository contains a phishing email analysis and awareness
report produced for the internship project task 2.

Three phishing email samples were analyzed to identify common
attack indicators, classify risk levels, and produce practical
awareness guidelines for employees and organizations.

---

## Target
Fabricated phishing email samples representing real-world
attack patterns:
- Sample 1: Fake bank security alert (Brand Impersonation)
- Sample 2: Fake IT password reset (Workplace Phishing)
- Sample 3: Fake DHL package delivery (Delivery Scam)

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Google Apps Header Analyzer | Email header inspection |
| MXToolbox Email Header Analyzer | SPF / DKIM / DMARC analysis |
| Chrome DevTools | Manual URL and domain inspection |
| Manual Analysis | Language, sender, and link review |

---

## Scope
Each email sample was examined for:
- Sender domain authenticity
- Reply-To address mismatches
- SPF / DKIM / DMARC authentication results
- URL and link inspection
- Urgency and fear-based language patterns
- Generic vs. personalized greetings
- Suspicious attachments

Each sample was then classified as:
Safe / Suspicious / Phishing

---

## Key Findings

- All 3 samples confirmed as PHISHING
- 18 total indicators identified
- 10 High Risk / 2 Medium Risk indicators
- SPF, DKIM, and DMARC failed on all 3 samples
- Most common tactic: fake sender domain + urgency language

## Author
**Anay Nayak**
