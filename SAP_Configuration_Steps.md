# SAP Configuration and Master Data
## Student: Swarnim Kumar | Roll No: 2329159

## Org Structure (SPRO)
- Company Code: VEL1 — Vertex Enterprises Ltd. | Currency: INR | Country: IN
- Sales Org: 1000 | Dist. Channel: 10 (Direct) | Division: 00 | Plant: P001 | Storage: SL01

## Customer Master (XD01)
- CUST-001: ABC Retail Pvt. Ltd. | Mumbai | Recon A/c: 14000 | Terms: NET30

## Material Master (MM01)
- MAT-1001: Industrial Switch 16 Port | FERT | Standard Price: INR 4,500

## Pricing (VK11)
- PR00: INR 5,200/EA | K007: 5% discount for CUST-001 + MAT-1001

## SPRO Key Config
1. Sales Doc Types: OR, QT, IN defined
2. Item Category: TAN (standard)
3. Shipping Point SP01 → Plant P001
4. Output: Order Confirm, Delivery Note, Invoice
5. Account Determination (VKOA): Revenue → G/L 40000
