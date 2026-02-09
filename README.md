<p align="center">
<img src="assets/vibecode.png" alt="VibeCode Logo" width="100%" style="max-width: 760px; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);" />
</p>

<p align="center">
<a href="https://github.com/huseyinhobek/n8n-workflow-templates-tr/stargazers">
<img alt="Stars" src="https://www.google.com/search?q=https://img.shields.io/github/stars/huseyinhobek/n8n-workflow-templates-tr%3Fstyle%3Dfor-the-badge%26logo%3Dgithub%26color%3Df4f4f5%26labelColor%3D18181b">
</a>
<a href="https://github.com/huseyinhobek/n8n-workflow-templates-tr/network/members">
<img alt="Forks" src="https://www.google.com/search?q=https://img.shields.io/github/forks/huseyinhobek/n8n-workflow-templates-tr%3Fstyle%3Dfor-the-badge%26logo%3Dgithub%26color%3Df4f4f5%26labelColor%3D18181b">
</a>
<a href="https://n8n.io/">
<img alt="n8n" src="https://www.google.com/search?q=https://img.shields.io/badge/n8n-Workflows-FF6B6B%3Fstyle%3Dfor-the-badge%26logo%3Dn8n%26logoColor%3Dwhite">
</a>
<a href="#">
<img alt="No Code" src="https://www.google.com/search?q=https://img.shields.io/badge/Auto-No_Code-7C3AED%3Fstyle%3Dfor-the-badge">
</a>
</p>

<p align="center">
<b>🚀 Curated n8n workflow templates. Organized for fast discovery, learning, and reuse.</b>





<sub>🇹🇷 Repo name includes <code>-tr</code>, but content is <b>English-first</b> for global utility.</sub>
</p>

⚡ Quick Links

🌐 Official n8n Library: n8n.io/workflows (7,800+ templates)

💼 Collab / Training / Consulting: info@huseyinhobek.com

📦 What’s Inside

This repository provides ready-to-import n8n JSON workflows categorized into two main collections:

Directory

Description

templates/

💎 Curated: Hand-picked templates gathered from public sources. Optimized for quality.

workflows/

📚 Library: Bulk imported workflow archives (e.g., from Zie619). Useful for deep searching.

🛠️ How to Use (Import Guide)

Run any workflow in your n8n instance in 5 steps:

Select: Open any *.json file under templates/ or workflows/.

Copy: Copy the raw JSON content (or download the file).

Import: In your n8n dashboard, go to Workflows → Import from File (or press Ctrl+V to paste from clipboard).

Configure: Click on nodes with red warning signs to add your own Credentials (API Keys, OAuth, etc.).

Launch: Test and toggle to "Active". 🟢

📂 Folder Structure

.
├── templates/                 # Hand-picked templates
│   └── <category>/
│       └── <workflow>.json
│
└── workflows/                 # Extended library
    └── <category>/
        └── <workflow>.json


📊 Stats:
To count total workflows locally, run:

find templates workflows -type f -name "*.json" | wc -l


🛡️ Security & Hygiene

[!WARNING]
Check for Secrets: While this repository strives to be clean, public workflow JSON files may occasionally contain leftover API keys or tokens from their original authors.

ALWAYS check the credential fields inside nodes before activating.

Reporting Secrets: If you find a leftover secret, please open an issue or email info@huseyinhobek.com with the file path and line number.

⚖️ Disclaimer & Attribution

This repo is an aggregation for educational and convenience purposes.

Ownership: We do not claim ownership of third-party workflows unless explicitly stated. All rights belong to their respective authors.

Licenses: Each workflow is subject to its original author's license. If none is included, assume all rights are reserved by the original author.

Takedown Requests: If you are a rights holder and want content removed, please open an issue with the original source link.

🌟 Credits / Upstream Sources

enescingoz/awesome-n8n-templates

Zie619/n8n-workflows

Official n8n Library

🤝 Contributing (Strict Rules)

PRs are welcome if you provide:

🔗 Original source link.

✍️ Author attribution (where available).

📝 Short description + required credentials.

🔑 NO secrets/API keys in the JSON.

<p align="center">
<i>Automation for everyone.</i>
</p>
