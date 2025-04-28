# 💼 ClaimEase – Reimbursement Management System

ClaimEase is a simple **ServiceNow-based Reimbursement Management System** designed to streamline the claim process for employees, approvers, and finance teams. Whether it's travel expenses, medical reimbursements, or any custom claim types, ClaimEase ensures smooth submission, approval, and processing – all within the ServiceNow platform.

---

## 🚀 Key Features

### 🧾 Claim Submission
- Employees (Claimants) can submit reimbursement claims via a **Record Producer**.

### ✅ Approval Workflow
- Claims are routed to the appropriate **Approvers**.
- Approvers can **review**, **approve**, or **reject** claims.

### 💰 Finance Processing
- Once approved, claims are visible to the **Finance group** for final processing.
---

## 🛠️ Modules & Components

| Module              | Description                                  |
|---------------------|----------------------------------------------|
| 🎫 Record Producer  | For claim submissions                        |
| 🔄 Flow Designer    | Handles approval process         |
| 📜 Business Rules, Script Includes   | Enforces automatic restriction of duplicate claim submissions       |
| 📅 Scheduled Job  | Ensures the approved and rejected claims, opened on last month are closed       |
| ⏱️ SLA Definitions  | Monitors and ensures timely approval and processing of claims       |
| 📊 Reports & Dashboards | Track pending, approved, and processed claims |

---

## 📥 How to Import the Update Set

1. **Download the update set XML file** from this repository (`/update_sets/[XML File]`).
2. In your ServiceNow instance:
   - Navigate to **System Update Sets → Retrieved Update Sets**.
   - Click **Import Update Set from XML**.
   - Upload the `[XML File]` file.
3. Once imported, open the update set and **Preview** it.
4. If no errors, click **Commit Update Set**.

---

> Built with ❤️ on ServiceNow by Subhash G Kashyap
