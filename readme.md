# 📊 Excel Fast-Moving Inventory AI Prompt

[![AI Prompt](https://img.shields.io/badge/Type-AI%20Prompt-blue.svg)](#)
[![Domain](https://img.shields.io/badge/Domain-Inventory%20Management-green.svg)](#)
[![Output](https://img.shields.io/badge/Output-Excel%20%7C%20Python%20%7C%20Markdown-orange.svg)](#)

## 📖 Overview

Welcome to the **Excel Fast-Moving Inventory** repository. This project contains a highly engineered, comprehensive AI prompt designed to instruct Large Language Models (LLMs) to act as an Excel automation specialist and inventory-control analyst. 

When executed, this "mega-prompt" commands an AI to generate a complete, small-business inventory management ecosystem from scratch. It goes far beyond a simple spreadsheet, requesting a fully structured relational workbook, automation scripts, and professional corporate documentation.

The core asset of this repository is the prompt file: **`Excel_Fast-Moving-Inventory_AI-Prompt.md`**.

---

## 🎯 What Does the Prompt Do?

By feeding `Excel_Fast-Moving-Inventory_AI-Prompt.md` into an advanced LLM (such as GPT-4, Claude 3.5 Sonnet, or Gemini Advanced), you instruct the AI to build a customized, robust inventory tracker optimized for fast-moving consumer goods (FMCG).

The prompt forces the AI to adhere to strict business logic, data validation, and professional design standards, ensuring the output is immediately usable for real-world operations or as a high-quality portfolio piece.

### Architecture of the Generated Output

The prompt specifically directs the AI to architect an Excel workbook featuring seven distinct, interconnected sheets:
1. **Read Me:** Operational instructions, data limitations, and system purpose.
2. **Product Master:** The central database for Lot numbers, SKUs, reorder levels, and unit costs.
3. **Stock Movements:** A transactional ledger tracking RECEIPTS, SALES, and ADJUSTMENTS.
4. **Current Stock:** A dynamic, calculated view of on-hand quantities, stock value, and reorder statuses.
5. **Fast Movers:** A ranking engine utilizing transparent velocity metrics to identify top-performing products.
6. **Dashboard:** A management-level view containing KPIs, formula-driven charts, and business observations.
7. **Data Checks:** Built-in error handling to flag negative stock, duplicate SKUs, and invalid movement types.

---

## 📦 Commanded Deliverables

The prompt is designed to act as a project manager, requiring the AI to output not just the Excel file, but a full suite of accompanying files:

*   `Fast_Moving_Inventory.xlsx` (The main application)
*   `scripts/build_inventory.py` (A Python script using `openpyxl` to build/refresh the workbook)
*   `data/products.csv` & `data/stock_movements.csv` (Sample datasets)
*   `docs/Data_Dictionary.md` (Technical field definitions)
*   `docs/User_Guide.md` (End-user instructions)
*   `docs/Monthly_Inventory_Report.md` (A sample management report)
*   `docs/Office_Memo.md` (Change-management communication)

---

## ⚙️ Key Business Metrics & Logic Built-In

The AI is instructed to calculate and visualize critical inventory KPIs without relying on overly complex macros (unless requested). Metrics include:
*   Total distinct SKUs and total units on-hand.
*   Total aggregate inventory value.
*   Automated alerts for products at or below their reorder threshold.
*   Top 10 fast-moving products calculated over a selected time frame.
*   Estimated weeks of stock remaining based on average weekly sales velocity.

---

## 🚀 How to Use This Repository

1. **Access the Prompt:** Open the `Excel_Fast-Moving-Inventory_AI-Prompt.md` file in this repository.
2. **Copy the Content:** Copy the entire markdown text.
3. **Customize (Optional):** At the top of the prompt under "Business scenario," you can fill in your specific Business Name, SKU count, and product categories, or leave it blank to let the AI hallucinate a realistic fictional business.
4. **Execute:** Paste the prompt into your preferred advanced AI model. 
5. **Download & Deploy:** Download the generated Python scripts, Excel files, and Markdown documentation provided by the AI in its response.

---

## 💡 Who is this for?

*   **Small Business Owners:** Seeking a lightweight, robust alternative to expensive ERP software.
*   **Data Analysts & Excel Enthusiasts:** Looking to study advanced formula-driven architectures and dashboard design.
*   **Job Seekers:** Needing a comprehensive, professional project to showcase in a data analytics or supply chain management career portfolio.
*   **Prompt Engineers:** Studying how to constrain and direct LLMs to produce complex, multi-file software and documentation suites.

---

## 🛡️ Standards and Best Practices Enforced

The `Excel_Fast-Moving-Inventory_AI-Prompt.md` file enforces strict professional standards on the AI's output:
*   **No "Black Box" Formulas:** Volatile functions are avoided. Formulas must be readable.
*   **Data Integrity First:** Requires the AI to establish data validation, flag unknown SKUs, and prevent silent overwriting of source files.
*   **Professional Aesthetics:** Mandates a restrained, corporate visual style, avoiding unnecessary decorative charts or clutter, utilizing conditional formatting strictly for business alerts (e.g., low stock warnings).