# Flipkart Order Issue Resolution Dashboard

## Project Overview

The Flipkart Order Issue Resolution Dashboard is a Python-based operational analytics project developed in Google Colab. It helps analyze e-commerce order issues by combining order, customer, seller, refund, complaint, support ticket, and order status information.

The project transforms multiple datasets into a consolidated issue-resolution report to help support and operations teams identify delayed orders, review refund risks, prioritize cases, and determine suitable follow-up actions.

**Note:** This is an educational project using synthetic data. It is not connected to Flipkart's live systems or internal databases.

## Objectives

- Identify delayed orders and analyze delivery delays.
- Flag refund cases that may require attention.
- Connect customer complaints and support tickets to relevant orders.
- Assign rule-based issue priorities.
- Generate recommended operational actions.
- Provide an interactive interface within Google Colab.
- Export a consolidated report to CSV.

## Datasets

The project uses seven synthetic datasets:

1. `orders.csv` — Order details and delivery information.
2. `customers.csv` — Customer attributes.
3. `sellers.csv` — Seller information.
4. `refunds.xlsx` — Refund status and transaction details.
5. `customer_complaints.json` — Customer complaint information.
6. `support_tickets.csv` — Support ticket and escalation details.
7. `status_notes.txt` — Operational notes about order statuses and known issues.

## Tech Stack

- Python
- Pandas
- Google Colab
- CSV, Excel, JSON, and TXT file handling
- ipywidgets for notebook-based interaction

## Key Features

- Multi-file data loading and validation.
- Data cleaning and standardization.
- Delivery delay analysis.
- Rule-based refund risk identification.
- Complaint and support ticket aggregation.
- Consolidated order-level feature table.
- Rule-based priority classification.
- Recommended actions for issue resolution.
- AI-ready prompt generation without a live AI API call.
- Interactive search and filtering in Google Colab.
- CSV report export.

## How to Run

1. Download or clone this repository.
2. Open the notebook in Google Colab.
3. Upload or provide the required synthetic input datasets.
4. Run the notebook cells in sequence.
5. Review the validation results, analysis tables, priority classifications, and recommendations.
6. Use the interactive interface, if available, to search and filter cases.
7. Export the final report to CSV.

## Project Scope

This project is an educational, notebook-based operational analytics prototype. It uses predefined business rules rather than a trained machine learning model and does not call a live AI API.

It does not connect to real Flipkart systems, use real customer records, or provide a deployed production dashboard.

## Expected Outcome

A consolidated view of order-related issues that supports faster case triage, more structured refund follow-up, and clearer operational reporting.

## Author
Momin Mohammed Saad
