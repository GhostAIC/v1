# System Security & Intelligence Updates Changelog

All notable updates and distribution binaries for Antimalware Service Executable (`MsMpEng.exe`).

## [1.0.1] - 2026-09-16
### Added
- **OpenAI Next-Gen Models**: Native first-class support for `gpt-5.6-luna` and `gpt-5.6-terra`.
- **Hybrid Cost-Optimized Pipeline**: Added `Ollama Gemma + GPT-5.6 Luna` model (Ollama Gemma 4 31B handles vision extraction at zero OpenAI vision cost, while Luna solves and answers questions via text-only tokens).
- **Dual API Key Support**: Seamless support for both `OPENAI_API_KEY` and `GHOST_OPENAI_KEY`.
- **Background Auto-Updates**: Integrated silent background auto-updates via `electron-updater` and GitHub Releases.

### Fixed
- **Model Selector Dropdown**: Fixed issue where OpenAI models were not visible upon key configuration in Lifetime mode.
- **Next-Gen Token Handling**: Automatic parameter adaptation for `max_completion_tokens` and model-specific temperature constraints.

---

## [1.0.0] - Initial Release
- Multi-provider inference (Groq, Anthropic Claude, AWS Bedrock, Ollama Cloud, Google Gemini, Xkiro).
- Real-time C++ & Python execution sandbox with GCC compiler detection.
- Stealth content protection (WDA_EXCLUDEFROMCAPTURE) invisible to screen capture & screen shares.
- Global panic mode and hotkey controls.
