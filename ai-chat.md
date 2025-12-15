# AI Chat

Purpose
- Notes for adding an AI-powered chat/help widget to this portfolio site.

Overview
- This file contains quick integration pointers and a minimal example for a static site.

Local testing
- Open `index.html` in your browser to test local UI/layout.

Integration options
- Client-only widget (embed a third-party chat/snippet)
- Self-hosted backend (run an API that proxies to an LLM service)

Minimal HTML snippet

<div id="ai-chat-root"></div>

<script>
// Minimal placeholder for a chat widget
const root = document.getElementById('ai-chat-root');
root.innerHTML = '<button id="start-chat">Start Chat</button>';
document.getElementById('start-chat').addEventListener('click', () => {
  alert('Replace this with your chat implementation.');
});
</script>

Notes
- For production, use a secure backend to store API keys and rate-limit requests.
- Consider accessibility: keyboard focus, ARIA labels, contrast.

Next steps
- Tell me if you want a third-party embed snippet, a self-hosted example, or a complete JS widget integrated into `index.html`.
