cat > portfolio.md << 'EOF'
# Marla Daniella – AI Automation & Workflow Systems Builder

I design and deploy automation systems that eliminate repetitive work, reduce processing time, and improve business operations.

## What I Do
I build end-to-end AI-powered workflows for recruitment, lead generation, and content automation using APIs, Python, and no-code tools.

- Replace manual processes with automation  
- Integrate AI into real business workflows  
- Build scalable systems for operations and growth  

---

## Featured Projects

### 1. 🎬 YT Long-to-Short Automation System
AI-powered system that converts long YouTube videos into Shorts with zero manual editing

🔗 https://github.com/MDanieechi14/yt-long-to-short-automation-system

**Problem**
Content creators spend hours manually clipping, editing, and uploading YouTube Shorts from long-form videos.

**Solution**
Built a fully automated pipeline that:
- Accepts a YouTube URL via Google Sheets
- Downloads and transcribes the video using AI
- Automatically detects and slices highlight clips
- Burns captions onto clips (local)
- Uploads directly to YouTube as a Private draft
- Updates Google Sheets with the clip URL

**System Architecture**
\`\`\`
Google Sheets (URL input)
        ↓
n8n (workflow automation)
        ↓
Flask REST API (Render)
        ↓
yt-dlp → AssemblyAI → ffmpeg
        ↓
YouTube Draft Upload ✅
\`\`\`

**Tech Stack**
Python • Flask • AssemblyAI • ffmpeg • yt-dlp • n8n • Render • YouTube Data API v3 • Google Sheets API

**Impact**
- Reduces manual video editing to zero
- Fully automated from URL input to YouTube draft
- Cloud-deployed and always-on via Render + cron-job.org
- Scalable architecture ready for production upgrade

**Proof**
- Live API: https://yt-long-to-short-automation-system.onrender.com/health
- Workflow screenshots
- Google Sheets input/output samples
- YouTube Shorts draft output

---

### 2. 🤖 AI Recruitment Automation System
AI-powered resume screening and candidate outreach workflow

🔗 https://github.com/MDanieechi14/ai-recruitment-automation-n8n

**Problem**
Manual resume screening is time-consuming and inconsistent, especially with large volumes of applicants.

**Solution**
Built an automated system that:
- Parses resumes and extracts structured data
- Scores candidates using AI based on job criteria
- Ranks applicants automatically
- Generates email drafts for outreach
- Stores and tracks results in Google Sheets

**Tech Stack**
Python • OpenAI API • Render • Google Sheets

**Impact**
- Reduced screening time from ~3 hours to ~20 minutes per batch
- Improved consistency in candidate evaluation
- Enabled automated outreach with minimal manual input

**Proof**
- Workflow screenshots
- Google Sheets output samples
- Source code and backend logic

---

### 3. 📱 TikTok Affiliate Content & Lead Automation Bot
Telegram-based AI assistant for instant product input, content generation, and automatic data logging

🔗 https://github.com/MDanieechi14/tiktok-affiliate-content-bot-n8n

**Problem**
TikTok affiliates struggle with:
- Deciding what content to post daily
- Manually logging products into spreadsheets
- Switching between multiple tools

**Solution**
Built a chat-based automation system that:
- Accepts product input via Telegram (no need to open spreadsheets)
- Instantly generates TikTok-ready hooks, scripts, and captions
- Automatically saves all data into Google Sheets
- Connects to a daily content delivery system

**System Architecture**
- Input Workflow: Telegram → AI → Google Sheets
- Delivery Workflow: Google Sheets → Telegram (daily content ideas)

**Tech Stack**
n8n • OpenAI / Groq • Telegram Bot API • Google Sheets

**Impact**
- Eliminates manual data entry
- Saves 1–2 hours daily on content ideation
- Simplifies workflow into a single chat command
- Creates a structured, reusable content system

**Proof**
- Workflow screenshots (input + delivery systems)
- Sample TikTok content outputs
- Exported n8n workflows

---

### 4. 📦 TikTok Affiliate Promo Generator (Bulk Automation)
Automated daily content production pipeline for affiliate products

🔗 https://github.com/MDanieechi14/tiktok-affiliate-promo-generator-n8n

**Problem**
Affiliate creators need to produce multiple content pieces daily, which is time-consuming and difficult to scale.

**Solution**
Built a scheduled automation system that:
- Pulls product data from Google Sheets
- Generates Taglish TikTok promo content (script, caption, hashtags)
- Cleans and structures AI output
- Stores results in a separate "Generated Promos" database
- Sends Telegram notifications upon completion

**Tech Stack**
n8n • Groq API • Google Sheets • Telegram API

**Impact**
- Automates bulk content creation
- Enables consistent daily posting
- Reduces manual content writing
- Scales affiliate content production

**Proof**
- Workflow screenshots
- Generated promo samples
- n8n workflow JSON

---

## Skills

**Automation & Systems**
- n8n Workflow Automation
- End-to-End System Design
- REST API Development

**AI Integration**
- AssemblyAI (transcription + highlights)
- OpenAI API (scoring, generation, parsing)
- Groq API (fast, cost-efficient generation)

**Backend & Deployment**
- Python (automation scripts, APIs)
- Flask + Gunicorn
- Render deployment
- ffmpeg video processing

**Data & Operations**
- Google Sheets automation
- Data structuring and workflow tracking
- YouTube Data API v3

---

## How I Build Systems
1. Identify repetitive and time-consuming workflows
2. Design automation logic and system flow
3. Integrate APIs and AI tools
4. Deploy, test, and optimize for reliability

---

## Availability

Open to:
- Remote roles (AI Automation / Workflow Engineer / Tech VA)
- Freelance automation projects
- Workflow system building for businesses

📩 Email: marladaniella.baay@gmail.com
📍 Location: Antipolo, Philippines
EOF
