# Aurelith AI — mobile-first starter

A static, installable PWA prototype for a voice-first AI command center.

## Current capabilities
- Mobile-first responsive interface and bottom navigation
- PWA manifest and service worker for app-style installation and shell caching
- Browser speech synthesis with a preference for available `en-GB` voices
- Optional browser speech recognition when supported
- No API keys or paid services embedded in the frontend

## Important limitations
This is a frontend starter, not a complete secure AI product yet. Chat submission intentionally reports that the backend is not connected. Do not add private API keys to `index.html` or any public repository.

Next implementation stages:
1. Deploy static frontend to Cloudflare Pages.
2. Add authentication using a free service whose current terms and limits fit the $0 requirement.
3. Add a server-side AI router with explicit allowlists for free providers and no paid fallback.
4. Add privacy controls, secure conversation storage, rate limiting and security testing.

Free-plan limits and provider terms can change. No service can guarantee unlimited free AI tokens.
