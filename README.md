# SentinelMesh

App Demo:

https://4itu41hmggopkd91uxl8.share.dreamflow.app


<img width="1024" height="1536" alt="IMG_1359" src="https://github.com/user-attachments/assets/940bbd71-5035-4924-b1c8-e7b2a530bc04" />


Agentic AI for Real-Time Cyber Fraud Defense. Core Idea SentinelMesh is an AI agent system that: Detects fraud patterns in real-time Identifies scam messages (romance scams, phishing, social engineering) Monitors suspicious financial activity Issues alerts Provides human-readable explanations Auto-generates fraud evidence packages (PDF or structure

SentinelMesh envisions a world where everyday people, enterprises, and financial institutions are protected from the fastest-growing digital threat category:
AI-augmented social-engineering fraud — including romance scams, phishing, impersonation, deepfake voice calls, and malicious persuasion attacks.
In a future where attackers increasingly operate with autonomous AI tools, we believe defense must also become autonomous, intelligent, and explainable.
Our vision:
▶️ Build the world’s first consumer-friendly, agentic AI fraud guardian that detects, explains, and packages evidence of scam activity in real time.
SentinelMesh turns suspicious messages, voice transcripts, screenshots, emails, and chat logs into actionable risk assessments, structured forensics, and legally usable “evidence packs.” It gives ordinary users the same level of intelligence support that only cybersecurity experts previously had.
By blending multi-agent AI, behavioral signals, vector intelligence, and automated evidence generation, SentinelMesh becomes an always-on “co-pilot for digital safety.”
This is not only a tool — it’s a digital defender mesh, designed to scale globally as an open, modular, explainable, and community-driven system.
🛠 Build Description — How SentinelMesh Works
SentinelMesh is built as a multi-agent cybersecurity pipeline, powered end-to-end by Amazon Q Developer and Amazon Kiro IDE, showcasing autonomous agents, code generation, and spec-driven development.
🔧 1. Agentic Architecture (Kiro Specification)
SentinelMesh uses 5 specialized agents defined in Amazon Kiro:
IngestionAgent
Cleans text, extracts metadata, OCRs images, transcribes audio.
DetectionAgent
Vector similarity search
LLM risk scoring
Pattern & rules engine (love-bombing, urgency, financial ask, impersonation)
ForensicsAgent
Entity extraction
Timeline reconstruction
Reverse image hints
Behavioral anomaly mapping
EvidenceAgent
Generates a detailed PDF report + JSON evidence pack
Summaries suitable for law enforcement or internal review
NotifierAgent
Sends alerts to user / webhook / email
Suggests next actions (report, block, verify identity)
Kiro handles agent definitions, state transitions, interface contracts, and orchestration logic generation, drastically reducing complexity.
💻 2. Backend (FastAPI + Lambda + Q Developer)
Primary services:
FastAPI microservice (demo)
AWS Lambda function for risk scoring (Terraform deployable)
FAISS / SQLite for vector search
S3 (optional) for evidence storage
Amazon Q Developer used for:
Generating FastAPI endpoint scaffolds
Creating unit tests automatically
Refactoring the evidence engine
Improving type-safety & documentation
Building the Terraform module boilerplate
Generating the Lambda handler prototype
The backend processes user input → routes it through the agent pipeline → produces structured results.
📱 3. Frontend (React or Expo)
A simple UI allows users to:
Paste suspicious messages
Upload screenshots
Upload audio or transcripts
View risk score (0–100)
View explanation and flags
Download the forensic PDF
See step-by-step agent reasoning
UI interactions call the FastAPI or Lambda API.
Amazon Q Developer was used inside the IDE to:
Generate UI components
Fix state management
Implement fetching hooks
Build demo mock screens quickly
🧠 4. AI & Detection Model Logic
SentinelMesh uses a hybrid detection approach:
A. Behavioral Heuristics
Rapid intimacy
Urgent financial request
Fake military / offshore worker scenario
Inconsistent identity markers
Emotional manipulation patterns
B. Vector Intelligence
Embedding text vs. known scam corpus
Similarity thresholding
C. LLM Interpretability
“Explain why this message is suspicious”
“Highlight manipulative strategies”
“Rate the risk from 0 to 1 based on 12 criteria”
D. Explainability
Every detection run contains:
final score
contributing features
agent-level reasoning
trace ID
evidence bundle
📄 5. Evidence Pack Generator
A core innovation is the automatic PDF evidence pack, containing:
timeline
flagged statements
risk scoring
metadata
summarized transcript
extracted entities
vector similarity report
recommended next steps
This is designed for:
banks
victims
cybersecurity teams
law enforcement
Amazon Q Developer helped generate:
PDF template
auto documentation
post-processing utilities
JSON schema
☁️ 6. Infrastructure (Terraform + Lambda)
Included in your build:
Terraform module
Lambda deployment ZIP
IAM roles
Basic execution policy
API-ready function code
This allows SentinelMesh to run completely serverlessly.
🌍 7. Impact Summary
SentinelMesh tackles a global crisis:
$10B+ in losses annually from romance scams
500% increase in AI-driven impersonation
Victims often lack tools to recognize manipulation
Digital literacy gaps are widening
SentinelMesh empowers everyday users with autonomous AI defense, delivering:
Early warning
Psychological manipulation detection
Clear explanations
Digital evidence
Guidance and education
This unlocks new possibilities for:
banks (fraud prevention)
online platforms
hotline support services
cybersecurity firms
public safety agencies
