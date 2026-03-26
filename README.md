# Legacy Lens 🔍

**Legacy Lens** is an AI-powered developer tool that instantly transforms undocumented GitHub repositories into comprehensive, interactive documentation suites. It helps developers learn faster, work smarter, and become more productive while building or understanding technology.

---

### 💡 Problem Statement
The goal is to build an AI-powered solution that helps people learn faster and work smarter. Legacy Lens ensures that no institutional knowledge is lost when developers leave or projects age by automating the understanding of existing codebases.

---

### ✨ Key Features & USP
* **Living Documentation:** Documentation that updates itself automatically in real-time whenever new code is committed.  
* **Visual Architecture Generation:** Instantly converts raw code into flowcharts and interactive diagrams.  
* **"Why" Engine:** A chat interface that explains the historical design decisions behind complex code blocks.  
* **Contextual Q&A:** Chat with your codebase to locate specific logic, such as authentication.  
* **Onboarding Checklist:** Automatically generates step-by-step "Getting Started" guides for new members.  
* **Legacy Risk Audit:** Scans for and flags deprecated libraries or potential security vulnerabilities in older code.  

---

### 🛠 Tech Stack
* **GenAI Model:** AWS Bedrock (Claude 3 Sonnet & Titan)  
* **Compute:** AWS Lambda (Serverless)  
* **Storage:** Amazon S3 & DynamoDB  
* **Frontend:** React / Next.js  
* **DevOps:** GitHub Actions  

---

### 📊 Comparison: Why Legacy Lens?
Unlike standard "AI Copilots" (like GitHub Copilot) that focus on writing new code, Legacy Lens focuses exclusively on understanding existing code. While others fix bugs line-by-line, Legacy Lens analyzes the entire repository to explain how the system works as a whole.

---

### 💰 Estimated Implementation Cost
* **Cost Model:** Pay-per-use (Serverless)  
* **Estimate:** <$5.00 per 100 repositories processed  
* **Development:** Free tier eligible for initial phases  
