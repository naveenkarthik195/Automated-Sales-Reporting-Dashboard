Automated Sales Reporting Dashboard with Real-Time Notifications

1. Introduction
In modern business environments, decision-making depends heavily on real-time data insights. Manual reporting processes are time-consuming, error-prone, and inefficient. This project focuses on building an automated business intelligence reporting workflow that updates dashboards automatically when data changes and delivers timely notifications to stakeholders.

The project demonstrates how data analytics, automation, and visualization tools can work together to create a practical and scalable reporting system.

2. Project Objective
• To build a sales analytics dashboard that updates automatically when data changes
• To design an automation workflow that detects data updates
• To deliver real-time dashboard notifications via Telegram
• To understand real-world BI workflows and automation concepts
• To implement secure access control for dashboards

3. Project Scope
• Automated dashboard refresh based on data updates
• Automated notification delivery
• Rule-based data validation
• Secure dashboard access
• Documentation and workflow explanation

4. System Architecture
Google Sheets (Data Source)
        ↓
Looker Studio (Dashboard Visualization)
        ↓
Zapier (Automation Workflow)
        ↓
Telegram Bot (Notification Delivery)
The dashboard is designed once and continuously updated through automated data refresh, while notifications are triggered through Zapier.

5. Tools and Technologies Used
5.1 Google Sheets
• Acts as the primary data source
• Stores sales transaction data
• Supports real-time updates
5.2 Looker Studio
• Used for data visualization and dashboards
• Automatically refreshes when the data source changes
• Provides interactive charts, KPIs, and filters
• Access-controlled (viewer-only permissions)
5.3 Zapier
• Used to create automation workflows
• Detects new or updated rows in Google Sheets
• Triggers notifications automatically
5.4 Formatter by Zapier
• Standardize text formats
• Prepare data for workflow processing
• Does not modify dashboard data directly
5.5 Telegram Bot
• Used to send real-time dashboard notifications
• Delivers the dashboard link securely to authorized users

6. Dataset Description
The dataset represents sales transactions for a men’s clothing store, including:
• Customer details
• Purchased items
• Quantity and price
• Transaction date
• Location information
• Sample or anonymized data is used for demonstration purposes.


7. Dashboard Design:
The dashboard is designed to provide a clear and intuitive overview of men’s store sales performance using visually simple and business-focused charts. 
The dashboard includes the following components:
• KPI Scorecards
• Total Customers 
• Total Quantity 
• Total Revenue 
• Average Order Value
• Price Over Time 
• Visualizes sales price trends across dates
• Helps identify fluctuations and patterns over time
• Price by Product 
• Compares total sales price across different product categories
• Helps identify top-performing and low-performing products
• Product by Price 
• Shows the percentage contribution of each product to total sales
• Provides a quick comparative view of product performance
• Location by Total 
• Displays sales distribution across different store locations
• Helps analyze region-wise contribution to total sales
The dashboard is connected directly to Google Sheets, and any data updates in the sheet are reflected automatically in the visuals after refresh. Filters and interactive elements allow users to explore the data efficiently.

8. Automation Workflow
Trigger:
• New or updated row in Google Sheets
Actions:
• Formatter by Zapier prepares the data
• Zapier sends a notification via Telegram
• Notification contains the live dashboard link
• Automation Characteristics:
• No manual refresh required
• Runs continuously once published
• Works in the background

9. Security and Access Control
• Looker Studio dashboard access is restricted
• Only authorized users (owner and client) can view the dashboard
• Downloading, copying, and sharing permissions are disabled
• Live dashboard links are not shared publicly
• GitHub repository contains documentation only

10. GitHub Repository Usage
• Project documentation
• Architecture explanation
• Screenshots of dashboard and workflows
• Live systems (dashboard, automation, bots) are not executed from GitHub.

11. Limitations
• Dashboard creation is manual (designed once)
• Data cleaning requires predefined rules
• Automation does not generate new dashboards
• Live system access must be granted manually
• These limitations reflect real-world BI practices.

12. Learning Outcomes
• Business Intelligence workflow design
• Data visualization using Looker Studio
• Automation using Zapier
• Understanding data validation and cleaning concepts
• Secure dashboard sharing and access control
• Professional documentation practices

13. Conclusion
This project successfully demonstrates a practical and realistic automated reporting system. By combining Google Sheets, Looker Studio, Zapier, and Telegram, the system delivers timely insights while maintaining data security and workflow efficiency.
The project aligns with industry standards and provides a strong foundation for roles in Data Analytics and Business Intelligence.

