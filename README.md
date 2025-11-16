# Remoto Backend Setup
### This model uses the `Anthropic` python library

## In your `.env`, you must provide:

```
CLAUDE_MODEL=claude-sonnet-4-5-20250929
ANTHROPIC_API_KEY=YOUR_API_KEY_HERE
```

### To generate the exposed backend server URL, open a new terminal (like Git Bash) and run the following command:
```
cloudflared tunnel --url http://localhost:8000
```

Copy paste the output https URL outlined in a formatted box and paste the URL into the "AI Model URL" field on the config page of the frontend after logging into your account



