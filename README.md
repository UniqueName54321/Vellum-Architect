# Vellum Architect (fork of The Story Nexus)

**Unofficial fork. Not affiliated with The Story Nexus or its author.**  
This project adds portable Windows and Linux builds, plus small UX tweaks, while preserving upstream functionality (chapters, concepts/lore, OpenRouter BYOK, etc.).

## Why this fork
- Portable Windows build (no installer)
- Native Linux build (AppImage/DEB)
- Minor UX fixes (status bar, clearer AI endpoint setup)

## Install
**Windows (portable):**
- Download the ZIP, extract, run `VellumArchitect.exe`.

**Linux:**
- Download `.AppImage` → `chmod +x` → run; or install the `.deb` for Debian/Ubuntu.

## Data & privacy
All project data is stored locally. AI calls only go to the endpoint you configure (e.g., OpenRouter) using your own key.

## Configure AI (OpenRouter BYOK)
- Settings → Providers → Custom/OpenAI-compatible  
- Base URL: `https://openrouter.ai/api/v1/chat/completions`  
- API Key: `sk-or-v1-...`  
- Model: e.g., `openrouter/your-model`

## Status
Actively rebasing on upstream. See CHANGELOG for fork-specific changes.

## Credits & License
Based on **The Story Nexus** (AGPL-3.0).  
© Original authors. This fork © 2025 You. Licensed **AGPL-3.0**.  
Source for binaries is available in this repository.
