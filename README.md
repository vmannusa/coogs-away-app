# Coogs Away Game App

Brings the home-game push-up tradition to away games and watch parties. One phone, one Bluetooth speaker.

**Live app:** https://vmannusa.github.io/coogs-away-app/

## How it works
1. Open the app, connect a Bluetooth speaker, tap **Game Time** (unlocks audio + keeps the screen awake).
2. The app finds today's UH game on ESPN and refreshes the score automatically (every 15s by default, and instantly when you switch back to the app).
3. When UH scores, the **GO COOGS** button lights up.
4. Tap it: the fight song plays, then a "dink" plays once for every point of UH's score while a giant counter counts the push-ups.

## Settings
- **Fight song:** pick an MP3 from your phone once; it's saved in the browser (no audio is hosted in this repo).
- Song length, count speed, dink sound (cowbell / bell / drum).
- Manual score override if ESPN is down or behind.

## Tech
Single `index.html` (vanilla HTML/CSS/JS) hosted on GitHub Pages. Scores come from ESPN's public, unofficial scoreboard data (team id 248), so it could change without notice. Use `?team=<espn id>` to point it at another team.
