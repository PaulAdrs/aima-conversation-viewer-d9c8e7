# Messaging Agent Viewer

A static page for browsing an AI messaging agent's conversations: pick an
agent, open a conversation, and read the thread (customer messages, agent
replies, and the tool calls in between), or export conversations as JSON.

The page talks to a separately deployed, access-code-protected backend. It
holds no data, credentials or account identifiers itself.

To publish: set `WORKER_URL` in `docs/index.html`, then enable GitHub Pages
from `main` / `/docs`.
