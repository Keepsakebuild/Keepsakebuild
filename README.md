<img width="1500" height="500" alt="keepsake-x-banner-v6" src="https://github.com/user-attachments/assets/732c69a9-1167-4ff3-8f16-b5d834e39d3f" />
Keepsake

The memory layer for AI agents and apps.

Keepsake is dedicated memory infrastructure for AI. It gives stateless large language models (LLMs) the ability to store, update, and recall information across separate chat sessions. Say it once, and Claude, ChatGPT, and Codex all know it, while every key stays in your hands.

Website · X · Telegram · GitHub

The problem

Your AI forgets you. Every new chat starts from zero. You repeat yourself, re-explain, and start again.

Keepsake fixes that with one private memory that every agent can use.

What it does
Step	What happens
Store	Save facts, preferences, and decisions outside the chat.
Update	Replace what is stale so memory stays current.
Recall	Bring the right context into any new session.
How it works
Remember

Preferences, project context, and decisions are saved outside any single chat. Tell Claude you prefer TypeScript, and Codex already knows when you ask.

Connect

Claude, ChatGPT, Codex, and any client that speaks MCP connect the same way. Add one in a few taps, with no wallet and no seed phrase.

Control
Group memories into spaces and choose which agent reads each one.
Sensitive details, such as health information, are suggested and never saved silently.
Review activity and revoke access in one tap.

Memories are encrypted on your device before they are stored, so not even Keepsake can read them.

Services

Keepsake gives the agents you use and the apps you build one shared, permissioned memory they can all rely on. Personal memory stays personal, and company memory stays with the company.

For	What you get
AI agents	Memory that follows Claude, ChatGPT, and Codex across sessions, with per-agent permissions and an activity log.
Apps	An SDK and MCP connection to add store, update, and recall to your product, with encryption and per-space access built in.

To talk to the team about your use case, reach out through the links above.

Repository layout
keepsake/
├── README.md
├── LICENSE
├── index.html        # the website
└── assets/
    ├── logo.png
    └── banner.png
Run the website locally

The website is a single static page. Open index.html in your browser, or serve the folder with any static server:

bash
python3 -m http.server 8000
# then open http://localhost:8000
The $KEEP token

$KEEP is a planned token to power the Keepsake network. It is coming soon on Robinhood. The contract address (CA) will be announced on our website and official social media accounts.

Planned uses:

Pay for storage: pay for the decentralized storage that holds your memories.
Govern the network: vote on upgrades, supported storage networks, and how the protocol grows.
Support builders: reward the developers and operators who keep the network running.
Unlock services: access higher limits and advanced features for agents and apps.

These are planned uses only. Nothing here is final, an offer to sell, or investment advice.

Security notes
Keepsake will never ask you for funds or private keys.
Only trust the official X, GitHub, and Telegram links in this repository and on the website.
No contract address has been announced. Beware of fake tokens that use the same or a similar name.
Community
X: @keepsakebuild
Telegram: t.me/keepsakebuild
GitHub: Keepsakebuild/keepsake
License

Add a LICENSE file and name it here once you have chosen one (for example, MIT).
