# FinSight AI 💰🤖

### AI-Powered BFSI Financial Decision Support Platform

FinSight AI is a web-based financial decision-support platform designed to help users understand their financial situation through AI-powered insights and financial calculations.

## 🚀 Features

* 🏦 **Loan Eligibility Checker**

  * Estimates loan eligibility using income, expenses, age, credit score and employment details.
  * Provides an estimated eligibility score and financial risk factors.

* 📊 **Credit Score Analyzer**

  * Analyzes an entered credit score.
  * Provides an estimated risk category and improvement suggestions.

* 🧮 **EMI Calculator**

  * Calculates monthly EMI in real time.
  * Displays total interest and total amount payable.

* 🤖 **AI Financial Advisor**

  * Provides personalized educational financial insights.
  * Designed for integration with Anthropic Claude API.

* 📱 **Responsive UI**

  * Works on desktop, tablet and mobile devices.
  * Modern dark glassmorphism design.

* 🔐 **Security-Focused Architecture**

  * API keys should be stored using environment variables.
  * Sensitive credentials should never be exposed in frontend code.

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Anthropic Claude API
* Google Sheets API
* Vercel / Netlify

## 📂 Project Structure

```text
finsight-ai/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
├── api/
│   ├── financial-advice.js
│   └── save-financial-record.js
│
└── assets/
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd finsight-ai
```

### 2. Run the project

Open `index.html` in a browser for the frontend demo.

For API functionality, configure the required server-side environment variables.

## 🔑 Environment Variables

Never put secret API keys directly in frontend JavaScript.

Example:

```env
ANTHROPIC_API_KEY=your_api_key_here
GOOGLE_SHEET_ID=your_sheet_id_here
```

Keep actual credentials in your deployment platform's environment-variable settings.

## 🧪 Demo Mode

The project can include demo/sample financial data so the main features can be tested without connecting external APIs.

Demo results are for educational purposes only.

## 🔒 Privacy & Security

FinSight AI is designed with security in mind.

* Do not store unnecessary sensitive financial information.
* Do not expose API credentials.
* Use HTTPS when deployed.
* Validate user input.
* Keep third-party API credentials server-side.
* Follow applicable privacy and data-protection requirements when handling real user information.

## ⚠️ Disclaimer

FinSight AI provides estimates and educational financial information based on user-provided data.

It does **not** provide guaranteed loan approval, official credit-bureau reports, or professional financial, investment, tax, or legal advice.

Actual lending decisions depend on the policies and assessment criteria of the relevant financial institution.

## 🔮 Future Enhancements

* User authentication
* Secure database integration
* Machine-learning loan prediction
* Real credit-bureau integration
* PDF financial reports
* Expense tracking
* Financial goal tracking
* Email reports
* Multi-language support
* Bank API integrations

## 👨‍💻 Project Purpose

This project is developed as an AI & Data Science academic project to demonstrate the application of web development, financial calculations, AI integration, data handling and user-centric UI/UX design.
