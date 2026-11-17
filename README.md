# VSHARK CRM — live demo

**▶ Open the demo: https://vsharkindia.github.io/crm-demo/**

A business-management web app built by VShark Solutions. The CRM, quotation, project
and invoicing modules are based on the system an engineering-services and equipment-trading
company uses day to day across India, the USA and the UAE. The Finance dashboard was
added for this demo to show the kind of reporting we can build.

This online version runs the **real application code** entirely in your browser, with
sample data. Nothing you do is sent anywhere, and you can reset it at any time.

## Demo logins

One-click buttons are on the sign-in page. All passwords are `demo1234`.

| Role | Email | What you'll see |
| --- | --- | --- |
| Admin / Management | `admin@vshark.demo` | Everything: Finance dashboard, approvals, expenses, settings, both business lines |
| Project Manager + Sales | `sales@vshark.demo` | Role-restricted: no finance, expenses or settings |
| Product Sales | `arjun.sales@vshark.demo` | Scanner-trading line: suppliers, purchase orders, sales quotes |

## Things to try

- **Finance**: 12 months of revenue vs. expenses, cash position, receivables aging, overdue payments, revenue by market (India / USA / UAE) and project margins.
- **Quotes**: open a quote and click *Download PDF* for a branded quotation, generated in the browser. Try the Draft → Approval → Submitted → Won workflow. Winning a quote creates the project and its invoice automatically.
- **Invoices**: 50/30/20 milestone billing, multi-currency payments, GST / non-GST.
- **Sales line** (switch at the top left): suppliers, purchase orders with shipping and customs tracking, GST-aware sales quotes (CGST + SGST vs. IGST).

## Built with

React 18 · TypeScript · Vite · Node.js / Express · SQLite · pdfkit · Recharts.
In this demo the Express API and SQLite database run in the browser using WebAssembly
(sql.js), so it can be hosted as a static site.

File uploads and email/Telegram notifications are turned off in the online demo.
