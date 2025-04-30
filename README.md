# Brocode Canada Business Directory

Welcome to the **Brocode Canada Business Directory** — an interactive, searchable, and sortable web directory of businesses offered by the members of Brocode Canada.

This project is hosted entirely on **GitHub Pages** and uses a **CSV file** as the data source. No backend, no database — just clean, simple HTML, JavaScript, and client-side CSV parsing.

## 📌 Features

- 🔍 Searchable and sortable business directory
- 📂 Powered by a simple CSV file
- 🚀 Hosted on GitHub Pages for free
- ✅ No backend required
- 📱 Mobile-friendly and responsive

## 🗂 Directory Sample Fields

The directory uses the following CSV columns:

```csv
Name,Company,Phone,Website,City,Category

Example row:
Muhammad Suhaib,Nemsel Inc.,437-533-5966,,Mississauga,IT Consultancy

🚀 Getting Started
1. Clone the Repo
git clone https://github.com/brocode-canada/yellowpages.git
cd YOUR_REPO
2. Add or Edit Businesses
Edit directory.csv in any spreadsheet editor (Google Sheets, Excel, etc.). Then save it back as a CSV and commit your changes.

3. View Locally (optional)
To test it locally:

# If Python is installed
python3 -m http.server 8080
# Open http://localhost:8080 in your browser
4. Deploy to GitHub Pages
Go to:

Settings → Pages

Set source to main branch → / (root)

Click Save

Directory is live at:
https://brocode-canada.github.io/yellopages/

🔧 Tech Used
PapaParse for CSV parsing

DataTables.js for table interactivity

jQuery for simplicity

Pure HTML, CSS, JS (no frameworks or backend)

📄 File Structure
├── index.html          # Main web page that loads and displays the directory
├── directory.csv       # CSV data file for businesses
└── README.md           # This file


Made with ❤️ by Brocode Canada
