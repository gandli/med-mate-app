# MedMate — Product Requirements Document (PRD)

> Ensuring every pill is truly understood by patients

## 1. Product Overview

### 1.1 Product Positioning
An intelligent medication management tool for patients and their families, solving the core pain point of "doctors prescribed medicine but patients cannot understand, remember, or take it correctly."

### 1.2 One-Sentence Description
Take a photo of your prescription, and AI translates it into plain language, telling you how to take it, when to take it, and what to pay attention to.

### 1.3 Product Form
WeChat Mini Program (priority) + Consider standalone App subsequently

### 1.4 Target Users

| User Role | Typical Profile | Core Needs |
|-----------|----------------|-----------|
| **Primary User: Caregiver** | Children aged 25-45, parents with chronic diseases taking multiple medications | Help parents manage medication, remotely supervise medication intake |
| **Direct User: Patient** | Chronic patients aged 45-75, long-term medication users | Know what each drug does, when to take it |
| **Secondary User: Young patients** | Ages 20-40, occasional doctor visits for prescriptions | Quickly understand medication information, check interactions |

---

## 2. Pain Points • Pleasure Points •痒 Points

### 2.1 😣 Pain Points (fear-driven, problems if unsolved)

| Pain Point | Fear Source | Solution |
|-----------|------------|---------|
| Uncertain if drugs will "fight" | Afraid of poisoning, adverse reactions | Automatic drug interaction detection, instant scanning, red warnings |
| Uncertain about wrong/missed doses | Afraid of worsened condition | Smart reminders + missed dose handling |
| Elderly living alone | Children's guilt and worry | Family collaboration dashboard, real-time status |
| Confused about different schedules | Afraid of wrong dosage/time | Daily medication card, clear visibility |
| Uncertain about China-Western medicine interaction | Afected by efficacy or side effects | Interval reminders, automatic spacing |
| Liver/kidney issues | Afraid of making things worse | Burden evaluation, risk visualization |

### 2.2 😆 Pleasure Points (immediate satisfaction)

| Pleasure Point | Why it's爽 | Solution |
|-----------|----------|---------|
| Confused by medicine → Photo for 3 seconds | From anxiety to control | Prescription photo → AI plain language interpretation |
| Cannot read manual → One sentence | "Oh, this is for heart protection" | One-sentence efficacy + importance tag |
| Many medications → One card | No thinking, just follow schedule | Daily medication schedule, auto-categorized |
| Hospital follow-up | Doctor understands at a glance | PDF medication report |
| Medicine running out | No stress, automatic refill | Inventory countdown + refill list |

### 2.3 🤩痒 Points (ideal self)

|痒 Point | Ideal Self | Solution |
|--------|----------|---------|
| "Be a reliable child" | Care for parents from afar | Family portal: createmed list, view records |
| "Understand my body" | Feel in control | Medication archive, history tracking |
| "Ask but too shy" | Break information asymmetry | AI Q&A |
| "Scientific养生" | Distinguish medicine from health products | Health product identification |
| "Friend recommended" | Professional advisor | Risk check |
| "Chinese formula" | Understand but too shy | Formula interpretation |

---

## 3. Function Planning

### 3.1 Function Priority

| Priority | Module | MVP | Description |
|---------|--------|-----|-------------|
| P0 | Drug recognition | ✅ | Core entry point |
| P0 | "Speak human language" | ✅ | Core differentiation |
| P0 | Daily schedule | ✅ | Core functionality |
| P1 | Reminders | ✅ | Improve compliance |
| P1 | Drug interaction | ✅ | Security |
| P2 | Family collaboration | | Remote care |
| P2 | AI Q&A | | Intelligent |
| P3 | Inventory | | Refill reminders |
| P3 | Follow-up calendar | | Management |
| P3 | Family medicine | | Multi-user |

---

## 4. P0: Drug Recognition Entry

### 4.1 Entry Methods

| Method | Difficulty | Accuracy | Scenario |
|--------|-----------|----------|----------|
| Prescription photo OCR | Medium | High | Hospital printed |
| Barcode scanning | Low | Highest | At-home organization |
| Photo OCR | Medium | Medium-high | Photo recognition |
| Trace code scanning | Low | Highest | Complete information |
| Manual search | Low | — | Fallback |
| Receipt photo | Medium | Medium-high | Batch entry |

### 4.2 MVP Strategy
Priority: **Prescription photo + barcode scanning + manual search**
