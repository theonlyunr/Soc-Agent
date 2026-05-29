# Autonomous Cloud Incident Response Agent

An AI-powered security agent that automates the ingestion, detection, and analysis of AWS VPC Flow Logs.

## 🚀 Features
- **Intelligent Ingestion:** Normalizes raw VPC Flow Logs for analysis.
- **Rule-Based Engine:** Rapidly filters logs for T1046, T1110, T1048, and other MITRE ATT&CK techniques.
- **AI Agentic Loop:** Uses GPT-4o-mini to perform deep analysis, confirm threats, and provide remediation steps.
- **OSINT Enrichment:** Automatically queries AbuseIPDB and IP-API for external threat context.
- **Automated Reporting:** Generates beautiful, human-readable HTML incident reports.

## 🛠️ Setup Instructions

### 1. Requirements
- Python 3.10+
- An OpenAI API Key (or GitHub PAT for GitHub Models)
- AbuseIPDB API Key (optional but recommended)

### 2. Installation
```bash
# Clone the repository
git clone [https://github.com/yourusername/soc-agent.git](https://github.com/theonlyunr/Soc-Agent.git)
cd soc-agent

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt
