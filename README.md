# Order-to-Cash (O2C) — Complete Sales Cycle in SAP SD
## Capstone Project | KIIT SAP BTP Developer Program 2027

**Student:** Swarnim Kumar  
**Roll Number:** 2329159  
**Batch/Program:** SAP BTP Developer Program | 2027  

---

## Project Overview

This project demonstrates a complete end-to-end Order-to-Cash (O2C) cycle implemented in SAP SD (Sales and Distribution) for a fictitious company — **Vertex Enterprises Ltd.**

The O2C process covers every step from customer inquiry to cash collection, with integration to SAP MM and SAP FI.

---

## O2C Process Flow

| Step | Process | T-Code | Document |
|------|---------|--------|----------|
| 1 | Customer Inquiry | VA11 | IN-0000042 |
| 2 | Quotation | VA21 | QT-0000018 |
| 3 | Sales Order | VA01 | SO-0000321 |
| 4 | Outbound Delivery | VL01N | DEL-0000289 |
| 5 | Post Goods Issue | VL02N | Stock -100 units |
| 6 | Billing / Invoice | VF01 | INV-0000156 |
| 7 | Payment Clearing | F-28 | Receivable cleared |

---

## Company Structure — Vertex Enterprises Ltd.

- **Company Code:** VEL1
- **Sales Organization:** 1000
- **Distribution Channel:** 10 (Direct Sales)
- **Division:** 00 (Cross-Division)
- **Plant:** P001
- **Storage Location:** SL01

---

## Folder Structure

```
Swarnim_Kumar_O2C_SAP_Project/
├── README.md                          ← This file
├── documentation/
│   └── O2C_Process_Steps_Detailed.md ← Full step-by-step documentation
├── screenshots/
│   └── screenshots_guide.md          ← Screenshots reference guide
└── process_steps/
    └── SAP_Configuration_Steps.md    ← SAP configuration and master data
```

---

## Submission
- **PDF Report:** O2C_SAP_Project_Swarnim_Kumar.pdf (submitted separately)
- **Deadline:** April 21, 2026 | 11:59 PM
