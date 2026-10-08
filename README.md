⚡ Suprabhat Agent - Multi-Provider AI Coding Assistant
Suprabhat Agent is an autonomous agentic AI pair programmer for VS Code supporting all major AI providers (Omni Route, OpenAI, Anthropic Claude, Google Gemini, Groq, DeepSeek, OpenRouter, and local Ollama).

👤 Developer Details
Developer: Prabhat Kumar Nahak
Extension: Suprabhat Agent
Version: 0.2.0
✨ Features
🌐 Multi-Provider AI Engine:
Omni Route / Custom Server: Fully compatible with Token Aliasing (gpt-5.6-sol-medium, etc.)
Google Gemini: Gemini 2.5 Flash, Gemini 2.5 Pro, Gemini 2.0 Flash
Anthropic Claude: Claude 3.7 Sonnet (Hybrid Reasoning), Claude 3.5 Sonnet, Claude 3.5 Haiku
OpenAI: GPT-4o, GPT-4o-mini, o3-mini, o1
Groq: LPU-accelerated Llama 3.3 70B, DeepSeek R1 Distill (300+ tokens/sec)
DeepSeek: DeepSeek V3, DeepSeek R1 (Thinking)
OpenRouter: Unified access to 100+ open and commercial LLMs
Ollama: 100% offline, private local models (qwen2.5-coder, deepseek-r1, llama3.3)
🤖 5 Operational Modes:
💬 Ask: Instant Q&A, syntax guidance, and code explanation.
📋 Plan: Generates comprehensive step-by-step architectural roadmaps.
🤖 Agent: Autonomous multi-step coding, file creation, editing, and tool execution.
🐛 Debug: Deep workspace error analysis using active compiler/linter diagnostics.
🔍 Review: In-depth code reviews, security scans, and optimization suggestions.
⚡ Full Agent Autonomy (Auto Mode) (New in v0.2.0):
Toggle Auto Mode in the sidebar toolbar to grant the agent full permission.
In Auto Mode, all tool calls (file writes, edits, terminal commands) execute instantly without asking for approval.
In Safe Mode (default), each destructive action still requires manual Accept/Reject.
🛡️ Safe Diff & Command Approval (Safe Mode):
Interactive Accept / Reject diff previews before files are written.
User confirmation gate for terminal command execution.
🎨 Premium Redesigned UI (New in v0.2.0):
Dark glassmorphism design with Inter font.
Animated message bubbles with real-time streaming cursor.
Tool call cards with icons, auto/pending/approved/rejected states.
Glowing mode pills and smooth transitions throughout.

📋 Changelog
v0.2.0
⚡ Auto Mode toggle — grant full agent autonomy with one click
🎨 Premium UI redesign — Inter font, dark glassmorphism, animated bubbles
🔧 Improved tool cards — icons per tool type, auto/pending/approved/rejected states
📝 Better markdown — headings, lists, bold/italic all rendered properly
🐛 Various UX improvements — streaming cursor, inline error display, smooth scroll
v0.1.2
Initial release with multi-provider support and 5 agent modes
