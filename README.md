📦 Releases

The latest stable build of **NeoShell** is now available in the [Releases](https://github.com/AseenaSulthana/NeoShell/releases) section of this repository.  

👉 Download the release package and follow the instructions to set it up quickly without cloning the entire repo.  

⚡ NeoShell – AI-Powered Terminal

NeoShell is an AI-enhanced, Python-based terminal built in just 22 hours during #SRMHacksWithCodemate. It redefines the traditional terminal experience by integrating AI-driven command execution, cybersecurity monitoring, and Git simulation — delivering a smarter, secure, and efficient developer tool.

✨ Features

🤖 AI-Powered Command Execution – Converts natural language into terminal commands with high accuracy.

🔒 Cybersecurity Dashboard – Tracks failed logins, monitors threats, and displays system health.

🛠️ Git Command Simulation – Integrated version control experience within the terminal.

📂 Interactive File System – File navigation and management inside the terminal.

📝 Built-in Nano Editor – Edit files directly without leaving NeoShell.

⚡ Real-Time Monitoring – System stats updated live with WebSocket support.

🛠️ Tech Stack

Frontend: Next.js, TypeScript, Tailwind CSS, Framer Motion

Backend: Python, FastAPI, WebSockets

DevOps: Docker, Redis

AI/ML: OpenAI API (for NLP-driven commands)

🎯 Why NeoShell

✅ Traditional terminals are powerful but lack intuitive AI integration.

✅ Developers need security visibility and version control built-in.

✅ Hackathon-ready, built to show how AI + Cybersecurity + DevOps can merge into one tool.

✅ Achieved ~85–90% efficiency in interpreting commands during testing.

⚙️ Installation
1. Clone the Repository
git clone https://github.com/AseenaSulthana/NeoShell.git
cd NeoShell

2. Run with Docker (Recommended)
docker build -t neoshell .
docker run -p 8080:8080 neoshell

3. Manual Setup (For Devs)

Install dependencies: pip install -r requirements.txt

Start backend: uvicorn app.main:app --reload

Start frontend: npm run dev

🚀 Usage

Open http://localhost:3000 in your browser.

Type commands in natural language (e.g., “show me active processes”).

Explore the Cybersecurity Dashboard and Git Simulation features.

📦 Releases

Latest stable builds are available under GitHub Releases
.
👉 Download, extract, and run without cloning the entire repo.

🔒 Security

NeoShell provides:

Failed login attempt detection

Real-time threat alerts

Basic system health checks

⚠️ Disclaimer: NeoShell is a hackathon prototype and should not replace enterprise-grade security solutions.

📊 Performance

⏱️ Built in just 22 hours during the hackathon.

🎯 Achieved ~85–90% command interpretation accuracy in test scenarios.

⚡ Optimized with WebSockets for real-time interaction.

🤝 Acknowledgements

💡 Hackathon: #SRMHacksWithCodemate

🤖 AI Assistance: CodeMate.ai (for faster coding & debugging)

🚀 Hosting: aseenasulthana.site

📂 Repository: GitHub – NeoShell

🔗 Built with passion for innovation in AI, Cybersecurity, and Developer Tools.
