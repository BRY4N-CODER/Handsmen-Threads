🧵 HandsMen Threads — Salesforce Capstone Project
Elevating the Art of Sophistication Through Automation

Welcome to the official documentation for the HandsMen Threads Salesforce Capstone Project.
This system was designed to support a luxury men’s fashion brand through centralized operations, automated communication, and intelligent inventory control — turning manual tasks into a smooth and efficient digital workflow.

🚀 Project Overview

HandsMen Threads required a solution capable of managing:

High-end customers with personalized records

Orders tied directly to product availability

Inventory levels that update in real-time

Automated emails for customer updates and stock alerts

This led to the development of a custom Salesforce application utilizing:

Component	Purpose
Custom Objects	Replace spreadsheets with structured & relational data
Record-Triggered Flows	Automate email alerts and transactional processes
Validation Rules	Protect inventory and prevent data errors
Email Alerts + Classic Templates	Ensure prompt communication with both clients & managers
Users & Profiles	Define secure access based on responsibility
🏗️ System Architecture
🔹 Custom Objects

The following custom objects were built to model the real business workflow:

HandsMen Customers

HandsMen Orders

HandsMen Products

HandsMen Inventory

HandsMen Marketing Campaigns

Each object is relational, ensuring that every order ties back to both the customer and the inventory in a single connected ecosystem.

💼 Key Business Process Automations
✔️ Customer Order Confirmation Workflow

When an order is created:

Record is saved

Flow is triggered

Customer receives a branded Order Confirmation Email

This eliminates the need for manual messaging and ensures professional consistency.

✔️ Inventory Protection System

This system contains two safety layers:

🔐 Validation Rule

Prevents orders from being submitted when the requested quantity exceeds available stock.

⚠️ Low Stock Alert Flow

When an item falls below 10 units:

Triggered automatically in Flow

Sends a Low Stock Alert Email to the warehouse manager

Prevents stockouts and sales loss

📊 Reports, Dashboards & Security
Dashboards & Analytics

Sales and inventory data can be analyzed at a glance for:

Sales performance

Product popularity

Stock levels over time

User Profiles

Access is permission-based:

Role	Capability
Sales Agent	Customer & order access only
Warehouse Manager	Full inventory access
Administrator	Full access across all features

🎥 Demo Video Flow ([https://drive.google.com/file/d/1ZscSS0A6oEUfDc4TKDQYN7ZJ71bHwX6m/view?usp=sharing](https://drive.google.com/file/d/1s8NqMzmC2evbHKbVZ6ow6IKgqCyXF1S0/view?usp=sharing))

🏁 Conclusion

The HandsMen Threads app is not just a Salesforce build — it is a complete business digitalization initiative.
By combining structured data models, automation, and intelligent validation, the system empowers the brand to:

✨ minimize human errors
✨ build stronger customer trust
✨ prevent stock loss
✨ focus more on fashion and less on administration

👨‍💻 Developer

Jamiel Bryan T. Reaño

Polytechnic University of the Philippines

Salesforce Developer — Capstone Project AY 2024–2025
