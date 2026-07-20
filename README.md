# Dice Game

A small prediction game built with Next.js, TypeScript, and Material UI. Choose
whether the next number will be under or over your threshold, then press Play to
see the result.

Live demo: [dice-game-dusky-phi.vercel.app](https://dice-game-dusky-phi.vercel.app)
## Tech stack

- Next.js 16 with the App Router
- React 19 and TypeScript
- Material UI 9 with Emotion
- Vitest and React Testing Library
- Playwright

## Game rules

- Under wins when the result is strictly lower than the selected threshold.
- Over wins when the result is strictly higher than the selected threshold.
- An equal result is a loss.
- Game history is stored in memory and resets when the page is refreshed.

