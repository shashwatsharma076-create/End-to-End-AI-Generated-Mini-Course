# ⚠️ SECURITY NOTICE

## API Keys & Secrets - DO NOT COMMIT!

This is a reminder to NEVER commit API keys, secrets, or credentials to GitHub.

### ✅ Safe to Share:
- Public voice IDs (like ElevenLabs Rachel)
- Public model names (like "gpt-4", "gpt-3.5-turbo")
- Course scripts and content
- Configuration settings (non-secret)

### ❌ Never Commit:
- OpenAI API keys (sk-...)
- AWS Access Keys (AKIA...)
- Database passwords
- Environment variables (.env files)
- Personal tokens
- Private credentials

### Before You Commit:
```bash
# Check for secrets before pushing
grep -r "sk-" . --include="*.py" --include="*.js"
grep -r "AKIA" . --include="*.py"
```

### Recommended Practice:
- Use `.env` files for local development
- Add secrets to GitHub Secrets for CI/CD
- Never commit any file named `.env`
- Use `.gitignore` to exclude sensitive files

---

**We clean-checked this repo - no secrets found!** ✓