# 📦 Cargo Document Processor

## Project Overview
An intelligent AI-powered n8n workflow that automatically processes cargo shipment documents uploaded to Google Drive. It extracts key shipment details using Google Gemini AI, logs everything to Google Sheets, and sends a professional summary email via Gmail, all without any human intervention.

---

## Real World Use Case
Built for **Chosen-Stars Cargo and Logistics Services Limited**, this workflow solves a real logistics problem: manually reading and processing shipment documents is time-consuming and error-prone. This automation handles the entire process in seconds from document upload to email notification.

---

## What This Workflow Does
1. **Watches a Google Drive folder** for new PDF shipment documents
2. **Downloads the PDF** automatically when detected
3. **Extracts all text** from the PDF document
4. **Uses Google Gemini AI** to intelligently extract key shipment fields
5. **Saves the structured data** to a Google Sheets log
6. **Sends a professional summary email** via Gmail to notify the team

---

## Tools and Technologies Used
- **n8n** (self-hosted, v2.19.4)
- **Google Drive API** (file watching and download)
- **Google Gemini AI** (models/gemini-3-flash-preview) (intelligent data extraction)
- **Google Sheets API** (data logging)
- **Gmail API** (automated email notification)
- **OAuth2 Authentication** (Google Cloud Console)

---

## Workflow Nodes
| Node | Purpose |
|---|---|
| Google Drive Trigger | Watches Cargo Documents Inbox folder for new PDFs |
| Download File | Downloads the detected PDF from Google Drive |
| Extract from File | Extracts all text content from the PDF |
| Information Extractor | Uses Gemini AI to extract structured shipment data |
| Google Gemini Chat Model | AI model connected to Information Extractor |
| Append Row in Sheet | Saves extracted data to Cargo Shipment Log |
| Send Email (Gmail) | Sends professional HTML summary email |

---

## Data Extracted by AI
| Field | Example Value |
|---|---|
| Waybill Number | CS-ABJ-2026-00847 |
| Consignee Name | Abuja Pharma Distributors Limited |
| Cargo Description | Pharmaceutical Tablets, Medical Syringes |
| Total Weight | 966 kg |
| Total Value | USD 26,950.00 |
| Total Charges | NGN 2,491,625.00 |
| Date Processed | 2026-07-12 |

---

## Google Sheets Output Structure
| Column | Data |
|---|---|
| Waybill Number | Unique shipment reference |
| Shipper Name | Sender company name |
| Consignee Name | Receiver company name |
| Cargo Description | Description of goods |
| Total Weight | Combined weight of shipment |
| Total Value | Declared value of cargo |
| Total Charges | Total freight charges |
| Date Processed | Date workflow processed the document |

---

## Email Notification Sample
**Subject:** New Cargo Shipment Received - CS-ABJ-2026-00847

**Body includes:**
- Waybill number
- Consignee details
- Full cargo description
- Weight, value and charges
- Automatic footer: "This email was generated automatically by Chosen-Stars Cargo Document Processor"

---

## How to Set Up This Workflow
1. Import the JSON file into your n8n instance
2. Create a folder in Google Drive called **Cargo Documents Inbox**
3. Create a Google Sheet called **Cargo Shipment Log** with the headers above
4. Set up Google Drive OAuth2 credentials in Google Cloud Console
5. Enable Google Drive API in your Google Cloud project
6. Connect Gmail credential in n8n
7. Connect Google Sheets credential in n8n
8. Add your Gemini API key to the Google Gemini Chat Model node
9. Activate the workflow
10. Upload any PDF cargo document to the folder and watch it process automatically

---

## Key Technical Concepts Demonstrated
- Google Drive webhook trigger with OAuth2
- Binary file handling and PDF text extraction
- AI-powered information extraction using LLM
- Structured data logging to Google Sheets
- Automated HTML email generation
- End to end document processing pipeline

---

## Business Impact
- Reduces document processing time from 15 minutes to under 30 seconds
- Eliminates manual data entry errors
- Creates automatic audit trail in Google Sheets
- Notifies team instantly via email
- Scales to handle unlimited documents

---

## Author
**Rainat Iyabo Lawal (Remmy)**
AI Automation Specialist | TechCrush Bootcamp Capstone Project
GitHub: github.com/qbeauty2021-tech
Portfolio: rainat-lawal.netlify.app

---

*This project was built as part of the TechCrush AI Automation Specialist Bootcamp capstone project, inspired by real logistics and clearing/forwarding industry experience.*
