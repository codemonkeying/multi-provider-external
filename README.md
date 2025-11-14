# Multi Provider External Pipe

**Multi-Provider LLM Integration w/ Auto-Discovery, Custom Branding, & Complete Model Support**

A powerful OpenWebUI pipe that automatically discovers and integrates the latest models from OpenAI, Anthropic, and Google APIs with zero manual updates required.

## ✨ Key Features

- **🔄 Auto-Discovery**: Automatically finds new models as they're released
- **🎨 Custom Branding**: Configurable model prefixes (MPE:, External:, etc.)
- **🔓 Permissive by Default**: No content filtering on Google models
- **⚡ Smart Caching**: 60-minute cache for optimal performance
- **🛡️ Bulletproof Fallbacks**: Hardcoded models if discovery fails
- **🔧 Fully Configurable**: All settings controllable via valves

## 🚀 Supported Providers

- **OpenAI**: GPT-4o, GPT-4o Mini, o1-preview, o1-mini, GPT-3.5 Turbo + auto-discovery
- **Anthropic**: Claude 3.5 Sonnet/Haiku, Claude 3 Opus/Sonnet/Haiku + auto-discovery  
- **Google**: Gemini 1.5 Pro/Flash, Gemini Pro + auto-discovery

## 📦 Installation

1. Copy the pipe code into OpenWebUI
2. Configure your API keys in the valves:
   - OPENAI_API_KEY
   - ANTHROPIC_API_KEY 
   - GOOGLE_API_KEY
3. Customize settings as needed
4. Enjoy automatic model discovery!

## ⚙️ Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| MODEL_PREFIX | "MPE:" | Custom prefix for model names |
| AUTO_DISCOVER_MODELS | true | Enable automatic model discovery |
| CACHE_DURATION_MINUTES | 60 | How long to cache discovered models |
| USE_PERMISSIVE_SAFETY | true | Disable Google content filtering |

## 🎯 Why Use This Pipe?

- **Stay Current**: Never miss new model releases again
- **Zero Maintenance**: No manual updates required
- **Maximum Flexibility**: Use all major LLM providers in one place
- **Professional**: Clean, branded model names in your dropdown

## 🔧 Requirements

pydantic>=2.0.0
requests>=2.0.0
google-generativeai>=0.3.0

## 🌟 Repository

Find the latest version and contribute at: https://github.com/codemonkeying/multi-provider-external

## 📝 License

MIT License - Feel free to modify and distribute!

---

**Built by Tom Miles** | Version 1.2.1
