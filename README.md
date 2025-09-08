# 🧵 TextileERP – Modern Garment ERP System  
**From Sampling to Shipment | AI-Ready | Department VIZ | PHP & MySQL Ready**

> Built for: **Rehbar Majeed Textiles Pvt Ltd**  
> Customer: **LYP1st(MD)**  
> Shipment Date: **21-05-2025**  
> Total Garments: **250 PCS** | Total CBM: **0.3456 m³**

---

## 📌 Overview

A **next-generation ERP system** for garment manufacturers that digitizes the entire workflow from **sampling to shipment**, including **costing, production tracking, inventory, accounts, and logistics visualization**.

This system is designed to:
- Automate data from Excel shipment plans
- Track **sampling cost & approval**
- Record **every operation detail** for future reference
- Store **product & sample images**
- Manage **consumables & labor cost**
- Visualize **container/pallet loading**
- Calculate **shipment cost (air/sea)**
- Generate **financial reports & P&L**

---

## 📥 Input Data Summary (From Excel)

| Field | Value |
|------|-------|
| **Customer** | LYP1st(MD) |
| **Shipment Date** | 21-05-2025 |
| **Product** | T-Shirt 100% Cotton Combed Jersey, 240 GSM |
| **Packing** | 1 PCS per polybag with tag |
| **Total Qty** | 250 PCS |
| **Total Cartons** | 3.788 |
| **Total CBM** | 0.3456 m³ |
| **Carton Dimensions** | 60.96 × 36.83 × 40.64 cm |
| **Colors** | Blue, Beige, Pink, Black |
| **Sizes** | S, M, L, XL |
| **Remarks** | Color & GSM as per sample, Approx Dimension |

> ✅ All 16 rows auto-processed into ERP.

---

## 🚀 Core Modules

### 1. 🧪 **Sampling Management**
- Record sample types: Proto, Fit, Sales, PP
- Capture sample images & tech packs
- Track approval status (Approved/Rejected)
- Auto-calculate **sampling cost** (fabric, trims, labor)

### 2. 💵 **Costing Engine**
- Full BOM (Bill of Materials)
- Fabric, consumables, labor, overhead
- Profit margin calculation
- Export costing sheet

### 3. 🏭 **Production Order (VIZ)**
- Department-wise workflow:
  ```mermaid
  graph LR
    A[Sample] --> B[Yarn]
    B --> C[Knitting/Weaving]
    C --> D[Fabric Store]
    D --> E[Cutting]
    E --> F[Sewing]
    F --> G[Finishing]
    G --> H[Packing]
    H --> I[Shipment]
