# Coogs Away Game App
## Project Overview for AI Assistants
You are an expert frontend developer building a mobile-first web app tailored for University of Houston Cougars fans and tailgaters. The app tracks away games, calculates game-day traditions (like mascot push-ups), and manages tailgate logistics. It must be a static, serverless site built with HTML, CSS, and Vanilla JS, deployable on GitHub Pages.

## Core Features
1. **Shasta Push-Up Tracker:** A dynamic tracker that calculates the cumulative number of push-ups the mascot owes based on the live score. (Formula: Add the total current score after every scoring event).
2. **Traditions Hub:** A reference section for the Alma Mater, Fight Song, and game-day chants.
3. **Tailgate Logistics Tracker:** A persistent checklist for game-day operations, tailored for enclosed trailer setups and generator-powered tailgates.

## Technology Stack
*   **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+).
*   **Styling Theme:** University of Houston colors (Cougar Red `#C8102E`, White, and Silver/Grey accents).
*   **Data/Storage:** External sports API fetching (via `fetch`) for live scores, and `localStorage` for saving tailgate checklist states.

## AI Implementation Instructions
*   Ensure all touch targets are large and accessible for mobile users out in the sun.
*   Implement a mock-data toggle for the scoreboard API so UI development can continue without a live game.
*   Store the checklist state in `localStorage` so users don't lose their packing list when switching apps.
