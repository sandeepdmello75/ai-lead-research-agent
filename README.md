 🤖 AI Lead Research + Outreach Agent

An AI agent built with n8n that automatically researches companies on LinkedIn,
generates personalized cold emails using Groq AI, and sends drafts to your Gmail
for human review before sending.

Built by Sandeep — AI Engineering Student at Srinivas University.

---

 🎯 What Problem Does This Solve

Sales teams and job seekers spend 2-3 hours daily manually researching companies
and writing personalized outreach emails. This agent does it automatically in minutes.

- Manual research per company → 20-30 minutes
- With this agent → 30 seconds
- Time saved per day → 2-3 hours

---

⚙️ What It Does

- Reads target companies from Google Sheets automatically
- Scrapes LinkedIn company data via Apify
- Extracts clean company info — name, industry, size, description, location
- Uses Groq AI (LLaMA 3.3 70B) to write personalized cold emails
- Sends draft emails to your Gmail inbox for human review
- Updates Google Sheet status after processing
- Runs every day at 9 AM automatically on schedule

---
 🏗️ Workflow Architecture
