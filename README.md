# No Code Zapier Automation - Machine Learning PaperStream🤖📚

## 🧠 Overview
As a ML Researcher, who is always wanderding around the webs for searching updated or new ML Papers. This automation is a gift which collects all the latest **machine learning papers** from multiple arXiv RSS feeds and compiles them into a single weekly digest email. Built entirely with Zapier, it eliminates manual tracking of new research and delivers a clean summary straight to your inbox.

## ⚙️ Features
- **Automated collection** of new ML papers from arXiv RSS feeds.  
- **Weekly digest batching** using Zapier’s Digest app.  
- **Email delivery** of all collected papers in one organized message.  
- **Scalable setup** — easily add more feeds (e.g., cs.CV, stat.ML, cs.AI).  
- **No coding required**, fully built with Zapier’s visual workflow editor.

## 🖼️ Screenshots

- Zap A: RSS → Digest (Collect papers)

<img width="505" height="466" alt="Screenshot 2026-06-03 114240" src="https://github.com/user-attachments/assets/58081aca-c4df-45e6-8cc0-e05240cbc05d" />



- Zap B: Digest Released → Email (Send weekly digest)

  <img width="444" height="552" alt="Screenshot 2026-06-03 114306" src="https://github.com/user-attachments/assets/28bece8d-0245-45d2-9eb1-433021fa2b28" />



## 🧰 Tech Stack
| Tool | Purpose |
|------|----------|
| **Zapier** | Automation platform |
| **RSS by Zapier** | Fetches new arXiv papers |
| **Digest by Zapier** | Batches entries for weekly release |
| **Email by Zapier / Gmail** | Sends the digest email |
| **arXiv RSS Feeds** | Source of ML research papers |

## 🔄 Workflow Diagram
The workflow consists of two Zaps working together:
1. **Zap A (Collect)** — Triggers whenever new papers appear in the RSS feed and appends them to the digest named `Weekly ML Papers`.  
2. **Zap B (Release)** — Fires when the digest is released (weekly) and sends the compiled list via email.  

![Workflow Diagram](assets/workflow.png)

This diagram shows how both Zaps share the same digest name to stay connected, ensuring smooth weekly automation.

## 🚀 Quick Start
Follow these steps to set up your own version:

1. **Create Zap A (Collect)**  
   - Trigger: RSS by Zapier → New Item in Feed  
   - Action: Digest by Zapier → Append Entry and Schedule Digest  
   - Digest name: `Weekly ML Papers`

2. **Create Zap B (Release)**  
   - Trigger: Digest by Zapier → Digest Released  
   - Action: Email by Zapier → Send Outbound Email  
   - Use the same digest name: `Weekly ML Papers`

3. **Schedule release** for Saturday 10 AM IST.  
4. **Test manually** by releasing the digest from *Apps → Digest by Zapier → Manage digests → Release now*.  
5. **Publish both Zaps** and enjoy your automated weekly ML paper digest!

---

