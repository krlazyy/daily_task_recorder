# Weekwell

Weekwell is a static weekly routine planner. No build step or server-side environment variables are required. Vercel serves the root index.html file and applies security headers from vercel.json.

## Deploy to Vercel

1. Import this repository into Vercel, or run the Vercel CLI from the project directory.
2. Use the project root as the Root Directory.
3. Leave the Framework Preset as Other. No build command is needed; deploy the project root as the output directory.

## Data and privacy

Routine data is stored in the browser local storage for the current site origin. The app has no server, user accounts, or cloud sync. Each visitor gets data in their own browser profile; clearing site data removes it. Do not add secrets to this static project.

The Content Security Policy allows the Google Fonts stylesheet and font files used by the page. If those services are unavailable, the page falls back to system sans-serif fonts.
