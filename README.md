# Asura AI

An unrestricted, uncensored mobile-optimized conversational AI chat interface.

## Features
- **Uncensored System Engine**: Injects explicit directives to bypass corporate refusal filters and moralizing preambles.
- **Dynamic Free Compute**: Pre-configured with OpenRouter's official `$0.00` dynamic router (`openrouter/free`) and active frontier checkpoints (`nemotron-3-super-120b`, `laguna-m.1`).
- **Mobile-First Layout**: Fully responsive drawer sidebar, touch manipulation optimizations, and smooth scrolling.
- **Copy Code Blocks**: Automatic language tag headers with a one-click clipboard copy feature.
- **Automated Web Reading**: Live link extraction and content grounding using Jina AI reader.
- **Dark/Light Theme**: Persistent local storage theme switching.

## Deployment (Termux)
```bash
cd AsuraAI
python3 -m http.server 8080
```
Open `http://127.0.0.1:8080` in Chrome.
