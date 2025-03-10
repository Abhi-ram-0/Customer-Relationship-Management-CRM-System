# Customer-Relationship-Management-CRM-System
A Customer Relationship Management (CRM) System is designed to help businesses manage customer interactions, track sales opportunities, handle customer queries, and automate workflows for sales and marketing processes. 
# Customer Relationship Management (CRM) System

## Overview:
The CRM System helps businesses manage customer interactions, sales opportunities, and communication logs. This system allows the tracking of customer information, sales activities, and generating reports on sales performance.

## Features:
- Add, edit, and manage customer details.
- Track sales opportunities by stages.
- Log communication with customers (calls, emails, meetings).
- Track sales activities and generate performance reports.
- Store and manage payment details related to opportunities.

## Database Schema:
This project uses a MySQL database with the following key tables:
1. **Customers**: Stores customer information.
2. **Sales_Reps**: Tracks sales representatives.
3. **Opportunities**: Records potential sales opportunities.
4. **Sales_Activities**: Logs activities related to sales opportunities.
5. **Communication_Logs**: Stores communication logs with customers.
6. **Payments**: Records payments made by customers.

## Setup:
1. Import the schema from `schema.sql` to create the database and tables.
2. Insert sample data by running `sample_data.sql`.
3. Run queries from `queries.sql` to generate reports and analyze data.

## Example Queries:
- Get total sales for a specific sales rep.
- List customers and their latest communication.
- Track opportunities by stage.
- Get top 5 customers by opportunity value.
