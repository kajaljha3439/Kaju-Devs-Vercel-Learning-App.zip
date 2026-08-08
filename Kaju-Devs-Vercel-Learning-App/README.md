# Kaju Devs

Vercel-ready frontend MVP for a coding learning platform.

## Included
- Premium landing/dashboard UI
- Learning tracks
- Practice arena
- Short notes with browser persistence
- Helpful shortcuts
- Developer roadmaps
- Progress card, XP-style stats and skill bars
- Profile area
- Kaju AI Learning Lab UI
- Responsive mobile design

## Deploy
Upload this folder to Vercel. No build command and no npm are required.

## Important for production authentication
The current ZIP has a guest/demo profile so the page works immediately. It does NOT store passwords and should not be used as real authentication.

For real username/password accounts and cross-device progress, connect Supabase Auth + Supabase Database. Passwords must be handled by the authentication provider, not stored in HTML/localStorage.

## AI
The AI Lab is a UI placeholder. Connect a server-side API route to an AI provider. Never expose an AI secret key in browser JavaScript.
