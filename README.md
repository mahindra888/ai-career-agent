# Autonomous AI Career Agent (v3.0) 🚀

> **Autonomous Executive Job Hunting, Cloud Workspace Provisioning, ATS Resume Tailoring & Multi-Platform Application Automation**

[License: MIT](https://www.google.com/search?q=https%3A%2F%2Fopensource.org%2Flicenses%2FMIT)
[Google Workspace](https://www.google.com/search?q=https%3A%2F%2Fworkspace.google.com%2F)
[Gemini](https://www.google.com/search?q=https%3A%2F%2Fdeepmind.google%2Ftechnologies%2Fgemini%2F)

The **Autonomous AI Career Agent** is a production-ready, zero-touch career operations engine. It automates the entire daily job application workflow:

1. **Autonomous Cloud Workspace Provisioning:** Automatically creates a structured Google Drive directory and formatted 16-column Google Sheet tracker.

2. **Multi-Platform Job Discovery:** Scans top boards daily, filtering by experience, tech stack, and notice period.

3. **Link Priority Verification:** Ranks verified application links in strict hierarchy (Company Career Site > LinkedIn > Naukri > Foundit > Indeed).

4. **Tailored ATS Resumes:** Autonomously writes custom Google Doc resumes matched to each specific job description.

5. **Technical Mock Interview Guides:** Formulates 8–10 company-specific technical interview questions with scenario-based answers in STAR format.

6. **Recruiter Outreach Drafts:** Prepares ready-to-send Gmail drafts for open talent acquisition inboxes.

## 📁 Repository Structure

```
├── README.md                                          # Complete documentation & quickstart guide
├── prompts/
│   └── AI_Career_Agent_Master_Prompt_v3.txt           # Turnkey, parameterized master system prompt
├── templates/
│   ├── Google_Sheets_Tracker_Schema.csv               # 16-column application tracker CSV schema
│   └── Google_Sheets_Master_Template_Link.md          # Direct link to pre-built Google Sheet template
├── docs/
│   ├── AI_Career_Agent_Setup_and_Onboarding_Manual.md # Client onboarding guide & 5-minute daily workflow
│   └── Commercial_Agency_Monetization_Guide.md        # 4 business models, pricing tiers & sales copy
└── LICENSE                                            # MIT Commercial License

```

## ⚡ Quickstart: 3-Minute Setup

### 1. Configure the Master Prompt

Open [prompts/AI_Career_Agent_Master_Prompt_v3.txt](https://www.google.com/search?q=prompts%2FAI_Career_Agent_Master_Prompt_v3.txt) and fill in your target profile variables:

```
Candidate Name: [Your Full Name]
Target Roles: [e.g., Citrix Systems Administrator, VDI Engineer]
Total Experience: [e.g., 3.9 Years IT / 3+ Years in Primary Tech]
Notice Period: [e.g., 15 Days or Immediate Joiner]
Preferred Locations: [e.g., Hyderabad, Bengaluru, Remote India]
Current CTC / Target CTC: [e.g., 7.0 LPA / 10.0 LPA]
Google Drive Master Folder ID: [Leave blank to auto-create]

```

### 2. Activate in Your AI Assistant

1. Paste the configured prompt into **Gemini** (or your preferred LLM assistant with Workspace tool integrations).

2. Set a daily schedule (e.g., **7:45 AM local time**, Monday–Saturday).

### 3. Autonomous Zero-Touch Provisioning

On its initial run, the agent automatically provisions your Google Drive:

* `Job Application Automation/` (Root)

  * `01_Master_Resume/` (Store your baseline master resume here)

  * `02_Job_Descriptions/` (Where analyzed JDs are stored)

  * `03_Tailored_Resumes/` (Where custom ATS Google Doc resumes are generated)

  * `04_Application_Tracker/` (Contains your live 16-column Google Sheet tracker)

  * `05_Recruiter_Messages/` (Outreach email drafts & follow-up templates)

  * `06_Mock_Interview_Questions/` (Company-specific technical interview preparation guides)

## 🎯 Verified Multi-Platform Link Hierarchy

To prevent broken links, expired listings, and aggregator delays, the agent strictly prioritizes links in this order:

| Priority | Platform | Routing Logic | 
| ----- | ----- | ----- | 
| **Tier 1** | **Official Company Career Site / ATS Portal** | Direct apply link on Workday, Taleo, Greenhouse, Lever, SmartRecruiters, or iCIMS. | 
| **Tier 2** | **LinkedIn Jobs** | Direct job view link (`https://www.linkedin.com/jobs/view/[ID]`). | 
| **Tier 3** | **Naukri.com** | Direct opening link + 1-Tap Google search forward syntax. | 
| **Tier 4** | **Foundit (Monster India)** | Direct verified posting link. | 
| **Tier 5** | **Indeed** | Direct verified job post link. | 

## 🔒 Security & Account Safety Principles

Unlike browser bots (Selenium/Puppeteer) that risk account suspensions by auto-clicking buttons on personal profiles:

* **Zero Credential Storage:** The agent never requests or stores login passwords, cookies, or 2FA codes.

* **1-Click Human-in-the-Loop:** The agent completes 95% of the preparation (resumes, verified links, screening answers). The candidate clicks the direct link, uploads the tailored resume, and submits in under 30 seconds.

## 📄 License

This project is open-sourced under the [MIT License](https://www.google.com/search?q=LICENSE) — free for personal and commercial use.
