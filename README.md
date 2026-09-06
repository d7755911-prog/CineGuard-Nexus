# 🎬 CineGuard-Nexus: Autonomous Hollywood Studio Governance Engine

> **Hackathon Grand Prize Submission** | Multi-Cloud Enterprise Pipeline combining **IBM watsonx.ai**, **IBM Cloud IAM**, **Google Cloud Vertex AI**, and **Gemini 1.5 Pro**.

---

## 🚀 Overview
**CineGuard-Nexus** is an autonomous, cross-cloud studio platform designed to bridge creative AI direction with ironclad enterprise copyright enforcement and secure multi-agent rendering. 

When a director inputs a natural language scene description:
1. **Gemini 1.5 Pro (Layer 1)** parses the script into deterministic execution task graphs and procedural asset matrices.
2. **IBM watsonx.ai Frankfurt Endpoint (Layer 2)** scans the asset metadata and intent against deep IP vector registries to prevent copyright infringement.
3. **IBM Cloud IAM (Layer 3)** evaluates the security gate and issues a cryptographic role-based execution token (`IBMC-TOK-...`).
4. **Google Cloud Agent Builder & Vertex AI (Layer 4)** receives the verified token and dispatches parallel cluster rendering nodes.

---

## 🛠️ Quickstart Guide (Under 5 Minutes for Judges)

Follow these simple terminal commands to clone, setup, and run the entire pipeline locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/CineGuard-Nexus.git](https://github.com/your-username/CineGuard-Nexus.git)
cd CineGuard-Nexus

2. Set Up Virtual Environment & Dependencies
Bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

pip install ibm-watsonx-ai google-cloud-aiplatform vertexai streamlit
3. Run the Terminal Master Pipeline (CLI Mode)
To test the complete end-to-end multi-cloud security and rendering workflow with rich color-coded logs:

Bash
python main.py
4. Launch the Streamlit Enterprise Dashboard (Web Mode)
To spin up the futuristic dark-mode UI control center where judges can test live natural language prompts and view real-time compliance telemetry:

Bash
streamlit run app.py
📂 Project Architecture
main.py — Unified core integration script containing all 4 security & execution layers.

app.py — Streamlit web interface with real-time logging and visual feedback tabs.

studio_payload.json — Pre-structured Hollywood production metadata schema.

LICENSE — Open-source MIT License.

Built with passion for autonomous enterprise cloud systems.


---

### 🧪 Step 2: Local Dry-Run Test (Terminal Verification)
Bhai, apne terminal mein ek baar fresh test chala kar verify kar lo ki sab kuch ekdum smooth chal raha hai:

1. Virtual environment activate karo:
   ```bash
   venv\Scripts\activate
Core script run karke check karo:

Bash
python main.py
(Tumhe terminal par [IBM watsonx.ai Status] ✅ Connection Established Successfully!, [Gemini Enterprise Agent], aur final JSON execution receipt bilkul color-coded format mein dikhegi.)

Dashboard boot karke check karo:

Bash
streamlit run app.py