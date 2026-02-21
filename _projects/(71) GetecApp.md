---
name: GetecApp – Internal Process Automation with AI
tools: [C#, .NET, WPF, OpenAI API, PDF Processing, Excel Integration]
image: /renereisenhofer/assets/images/main.png
description: An internal desktop application developed to automate document-based business processes using software engineering and AI integration.
---

# GetecApp – Internal Automation Tool

![Main Interface](/renereisenhofer/assets/images/main.png)

### 🛠 Tech Stack

- C# (.NET)
- WPF (Desktop UI)
- OpenAI API (GPT integration)
- JSON / HTTP Client
- Excel & PDF processing

---

### 🧠 Project Overview

GetecApp is an internal desktop application developed to automate document-based workflows within the company.

The goal was to reduce manual administrative effort by extracting structured information from PDFs and Excel files, validating content, and generating automated analyses using AI where beneficial.

The application combines classical software engineering (data processing, validation, structured workflows) with controlled AI integration for complex text analysis tasks.

---

### 🚀 Core Features

#### 1️⃣ AGB Analysis (AI-Supported Legal Review)

![AGB Analyse](/renereisenhofer/assets/images/agb_analyse.png)

- Upload of AGB (terms & conditions) documents
- Automated legal-style analysis
- Detection of:
  - Potential risks
  - Unfair clauses
  - Violations of ÖNORM B 2110
- Optional custom user instructions
- Structured AI output processing

The OpenAI API is used with deterministic settings (temperature = 0.0) to ensure consistent and reproducible results.

---

#### 2️⃣ Price Sheet Automation (Preisspiegel)

![Preisspiegel](/renereisenhofer/assets/images/preisspiegel.png)

- Upload of Excel sheets and offer PDFs
- Automated extraction of offered prices
- Parsing structured JSON results from AI responses
- Automatic insertion into internal price comparison sheets (complex excel files)
- Reduction of manual data transfer work

---

#### 3️⃣ Minute Rate Processing

![Minutensätze](/renereisenhofer/assets/images/minutensaetze.png)

- Excel import of position lists
- Matching with reference datasets
- Automatic assignment of minute rates
- Conflict handling and safe overwriting logic

---

### 🔧 Technical Implementation Highlights

- Modular service-based architecture
- Dedicated OpenAI service wrapper for:
  - Request building
  - Authentication handling
  - Error management (401 / 403 handling)
  - Structured JSON extraction
- Clean separation between:
  - UI logic (WPF)
  - Business logic
  - AI integration layer
- Strong input validation and defensive error handling
- Asynchronous HTTP communication with proper exception management

Example responsibilities included:
- Building structured prompt instructions
- Enforcing deterministic AI responses
- Extracting structured JSON objects from model output
- Handling API errors securely

---

### 📈 Business Impact

- Reduced manual document review time
- Automated repetitive Excel/PDF workflows
- Standardized legal document checks
- Increased internal efficiency
- Demonstrated practical AI integration in a production-like environment

---

### 📌 Project Status

Internal company software.  
Actively used within the organization.  
Not publicly released.
