# QA Technical Assignment – 8byte Platform

## 📌 Purpose of This Repository
This repository contains my **end-to-end Quality Assurance technical assignment** prepared as part of the **8byte Quality Analyst hiring process**.

The goal of this assignment is to demonstrate:
- A **quality-first mindset**
- Strong **test design and execution skills**
- Ability to think from **both user and system perspectives**
- Clear **documentation, defect reporting, and risk analysis**
- Practical **regression and prevention strategy**

All artifacts are structured to reflect **real-world QA processes** followed in professional product teams.

---

## 🧭 What This Repository Covers (At a Glance)

✔ Complete **Test Planning**  
✔ Detailed **Test Scenarios & Test Cases**  
✔ Real **Test Execution with Actual Results**  
✔ Logged **UI, Functional & Navigation Defects**  
✔ **Final Test Summary Report** for stakeholders  

This README explains **what was tested, how it was tested, what issues were found, and the overall quality status**—without requiring you to open individual documents.

---

## 📂 Repository Structure & Direct Links

| QA Artifact | Description | Link |
|------------|------------|------|
| **Test Plan** | Overall QA strategy, scope, assumptions, risks, test approach, entry/exit criteria | 📄 [View Test Plan](https://docs.google.com/document/d/1Z1BoPNHm5Lm7DELu6yYURBySmwVL67Y7desVfMskl8U/edit?usp=sharing) |
| **Test Scenarios** | High-level scenarios covering complete product functionality | 📊 [View Test Scenarios](https://docs.google.com/spreadsheets/d/1gvMlYfA4ohLdmGcROST5dPkzA54wJ9jJvGi0ZNnpd-Y/edit?usp=sharing) |
| **Test Cases** | Detailed step-by-step test cases with expected & actual results | 🧪 [View Test Cases](https://docs.google.com/spreadsheets/d/1gvMlYfA4ohLdmGcROST5dPkzA54wJ9jJvGi0ZNnpd-Y/edit?usp=sharing) |
| **Bug Reports** | Logged defects with severity, priority, reproducibility & observations | 🐞 [View Bug Reports](https://docs.google.com/spreadsheets/d/12MXChACeXkIOv5VMZBzdKNVTIiq6mnJMz5026puDQ88/edit?usp=sharing) |
| **Final Test Summary Report** | Management-level test execution summary & release assessment | 📘 [View Test Summary Report](https://docs.google.com/document/d/1x-KfAYbUHdyVvELq2OVu5WoVvkCPhA8i3QVB2uRSBa8/edit?usp=sharing) |

---

## 🧪 Testing Scope (What Was Tested)

The following functional areas were tested thoroughly:

### 1️⃣ Homepage & Core Navigation
- Page load behavior
- UI consistency
- Responsiveness across devices (desktop, tablet)
- Navigation redirections

### 2️⃣ Header Navigation
- Product, Solutions, AI Agents, Resources, Company sections
- Correct redirection & dropdown behavior

### 3️⃣ Industry Solutions Pages
Validated content & navigation for:
- Banking & Lending  
- Asset Management  
- Corporate Finance  
- Private Equity & VC  
- Insurance  
- Fintech Platforms  

### 4️⃣ AI Agents
- AI Decisions Agents listing
- Agent detail pages
- Navigation consistency
- Non-functional / Coming Soon handling

### 5️⃣ Pricing Page
- Pricing clarity & accuracy
- UI alignment & content consistency
- Call-to-action behavior

### 6️⃣ Resources, FAQs & Knowledge Center
- Insights
- FAQs
- Data Privacy & Security  
(All currently redirecting to **404 / Coming Soon** pages with working fallback navigation)

### 7️⃣ Company Pages
- About Us
- Careers
- Contact Us  
(Currently showing **“Something exciting is on the way”** pages)

### 8️⃣ Book Demo & Try Octa Agent
- Calendar scheduling behavior
- Availability logic (date/time restrictions)
- Login form validation
- UI error indicators (red highlights)

### 9️⃣ Footer Links & Legal Pages
- Industry links
- Use cases
- AI agents
- Resources
- Company & legal links  
(Multiple broken / non-working links identified and logged)

---

## 🐞 Defect Overview (High-Level)

During execution, multiple issues were identified and logged professionally, including:

- ❌ Non-working navigation links
- ❌ Industry & use-case pages not opening
- ❌ Broken footer links
- ⚠ UI responsiveness issues (tablet view)
- ⚠ Overlapping UI elements
- ⚠ Audio issues on specific devices
- ℹ “Coming Soon” pages without clear timelines

Each defect includes:
- Clear **steps to reproduce**
- **Expected vs actual results**
- **Severity & priority**
- Impact assessment

---

## 📊 Overall Quality Assessment

| Area | Status |
|----|----|
| Functional Stability | ⚠ Needs Improvement |
| Navigation & Redirection | ❌ Multiple Failures |
| UI Consistency | ⚠ Minor to Moderate Issues |
| Error Handling | ✅ Acceptable |
| Release Readiness | ❌ Not Recommended |

📌 **Recommendation:**  
The product requires **navigation fixes, broken-link resolution, and responsive UI corrections** before production readiness.

---

## 🔁 Regression & Quality Strategy

Suggested prevention strategy includes:
- Automated smoke tests for navigation
- Regression suite for header & footer links
- Device-based UI validation
- Pre-release broken-link scanning
- “Coming Soon” pages tracked as known risks

---

## 👤 Author

**Paras Kumar Zambarlal Sanghvi**  
Quality Analyst  
Manual & Automation Testing  
HTML | CSS | JavaScript | QA Methodologies  

---

## 📌 Important Note
This assignment is **100% original work**, created specifically for evaluation purposes.  
All testing was performed manually following **industry-standard QA practices** with a strong focus on **usability, reliability, and long-term quality**.

---

### ✅ Thank you for reviewing this QA assignment.
