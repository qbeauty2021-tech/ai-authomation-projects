# AI Automation Projects 

Learning AI Automation — building real workflows with n8n, Python, Cursor and Node.js.
Projects from the TechCrush AI Automation Specialist Bootcamp.

## 🗂️ Projects

### Week 2 — Auto Save Orders to Google Sheets
**File:** `week2-google-sheets-automation.json`

#### What It Does
This workflow automatically saves customer order data from an 
n8n automation into a Google Sheets spreadsheet without any 
manual input.

#### What I Was Trying To Build
A real-world order management system for my SoftWear Abuja 
drop-shipping business. Instead of manually recording every 
customer order, this workflow captures the order details and 
saves them automatically to Google Sheets — even while I sleep.

#### How It Works
1. **Manual Trigger** — starts the workflow
2. **Edit Fields node** — creates the customer order data 
   (name, product, size, price, date)
3. **Google Sheets node** — automatically appends a new row 
   to the SoftWear Orders spreadsheet

#### How To Use It
1. Import the JSON file into your n8n instance
2. Set up Google Sheets credentials (OAuth2)
3. Create a Google Sheet with these headers:
   - customerName, product, size, price, orderDate
4. Connect the Google Sheets node to your spreadsheet
5. Click Execute Workflow
6. Check your Google Sheet — a new row will appear automatically!

#### Tools Used
- n8n (workflow automation)
- Google Sheets API
- Google OAuth2 Authentication

## 🛠️ Tools I'm Using
- **n8n** — workflow automation
- **Python** — scripting and AI integration
- **Cursor** — AI-powered code editor
- **Node.js** — JavaScript runtime
- **Git & GitHub** — version control and portfolio

## 👤 About Me
AI Automation Specialist in training at TechCrush Bootcamp.
Building real automations for real businesses.
