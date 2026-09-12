TRADING STRATEGY VAULT — FINAL v7

New / updated:
- AI Analysis uses 3-model consensus: OpenAI + Gemini + Groq.
- Chart screenshot is sent to all 3 vision-capable AI models.
- Final UP/DOWN/STOP follows the existing majority/STOP safety logic.
- Future Signals can use the same 3 AI providers.
- Groq is configured with qwen/qwen3.6-27b for image analysis.

API config:
- Edit ai-config.js and paste your own OpenAI, Gemini and Groq API keys.
- Groq API keys start with gsk_ and are created in GroqCloud Console.
- The provided gsk_ key was NOT embedded into the final ZIP.

SECURITY WARNING:
This is a GitHub-only frontend. Any API key placed in ai-config.js is visible to site visitors.
Use restricted/test keys and spending/usage limits. For real secret protection, route requests through a backend/proxy.

Important:
AI outputs are estimates only. The site does not guarantee market outcomes or profits and does not have a live Quotex market feed.
