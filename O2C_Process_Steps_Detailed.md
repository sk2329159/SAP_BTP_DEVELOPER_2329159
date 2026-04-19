# O2C End-to-End Process — Detailed Steps
## Student: Swarnim Kumar | Roll No: 2329159

---

## Step 1: Inquiry (VA11)
- Inquiry Type: IN | Customer: CUST-001 | Material: MAT-1001 | Qty: 100 EA
- Output: IN-0000042

## Step 2: Quotation (VA21)
- Reference: IN-0000042 | Type: QT | Valid: 18.04.2026 – 30.04.2026
- Net Value: INR 4,94,000 (5,200 x 100 – 5%)
- Output: QT-0000018

## Step 3: Sales Order (VA01)
- Reference: QT-0000018 | Type: OR | ATP: PASS | Credit: PASS
- Output: SO-0000321

## Step 4: Outbound Delivery (VL01N)
- Reference: SO-0000321 | Shipping Point: SP01 | Delivery: 28.04.2026
- Picking: 100 units from SL01 | PGI Movement Type: 601
- FI: COGS Dr / Inventory Cr INR 4,50,000
- Output: DEL-0000289

## Step 5: Billing (VF01)
- Reference: DEL-0000289 | Type: F2
- Net: 4,94,000 + GST 18% (88,920) = INR 5,82,920
- FI: AR Dr 5,82,920 / Revenue Cr 4,94,000 / GST Cr 88,920
- Output: INV-0000156

## Step 6: Payment Clearing (F-28)
- Amount: INR 5,82,920 | Date: 05.05.2026 | Bank: 100001
- Open item INV-0000156 cleared
- FI: Bank Dr / AR Cr INR 5,82,920
- O2C Cycle COMPLETE
