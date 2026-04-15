💎 Sims 4 Mod ZIP Manager
A beautiful and simple desktop app to batch extract Sims 4 mod ZIP files into one organized folder.

✨ Built with Tauri + React + TypeScript

🌸 Features
📦 Batch Extraction: Extract all ZIP/RAR files in one click.

📁 Custom Output Folder: Choose exactly where your mods go.

🎮 Quick Access: Open your Sims 4 Mods folder instantly.

🔍 Search & Filter: Quickly find ZIP or extracted files.

🌍 Multi-language Support: English / 中文 / 日本語 / 한국어.

🎨 Clean UI: Soft pink aesthetic, Sims-inspired design.

🖥️ Download
👉 Windows Installer (.exe) Download the latest version from the releases page:

➡️ Download Latest Release

📸 Preview
Splash Screen
Zip Vault
Extracted Files
🚀 Getting Started (Development)
Follow these steps to run the app locally:

1. Clone the repo

Bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
2. Install dependencies

Bash
npm install
3. Run the app

Bash
npx tauri dev
📦 Build
To build the installer for production, run:

Bash
npx tauri build
Note: Your installer will be generated and located at:

src-tauri/target/release/bundle/nsis/

⚙️ Tech Stack
⚛️ React + TypeScript - Frontend UI

🦀 Tauri (Rust) - Core backend

🎨 Custom CSS - Styling and UI

📦 Rust ZIP/RAR libraries - Fast file extraction

💡 Why this project?
Managing Sims 4 mods can get messy really fast:

❌ Too many ZIP files clogging up your Downloads folder

❌ Tedious manual extraction

❌ Scattered folders and disorganized CC

This tool solves that with: 👉 One-click batch extraction + an automatically organized output folder.

🛣️ Roadmap
[ ] Auto-detect Sims 4 Mods folder

[ ] Drag & drop ZIP support

[ ] Mod conflict detection

[ ] Auto-update system

[ ] macOS version

📂 Project Structure
Plaintext
├── src/            → React frontend
├── src-tauri/      → Rust backend
└── icons/          → App icons
🧑‍💻 Author
Louisa Liu 🎓 NYU Computer Science

💡 Interested in Product + Engineering

💖 Acknowledgements
Inspired by:

The incredibly creative Sims 4 Modding Community.

The sheer need for better, aesthetically pleasing mod management tools.

📜 License
This project is licensed under the MIT License.
