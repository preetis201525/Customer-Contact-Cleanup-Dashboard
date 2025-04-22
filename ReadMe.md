# Customer Contact Clean-up Dashboard

This project demonstrates how to clean messy customer contact data using Power BI and basic data transformation techniques.

## Steps Followed:
- Imported customer dataset (Emails, Phone Numbers, Addresses)
- Applied basic validation for Email structure (using `Text.Contains` checks)
- Cleaned phone numbers (kept only digits) and addresses (removed special characters)
- Built key KPI Cards:
  - Total Customers
  - % Valid Emails
  - % Clean Phone Numbers
- Displayed clean customer data table

## Tools Used:
- Power BI Desktop
- Power Query Editor (Text Functions like Text.Select, Text.Contains)

---
Raw customer contact dataset uploaded without cleaning. All cleaning operations are demonstrated inside the Power BI .pbix project file.

> **Note:** This project uses basic text validation for Emails and Phone Numbers.  
> In larger real-world datasets, advanced Regex or Python preprocessing might be recommended.

---
