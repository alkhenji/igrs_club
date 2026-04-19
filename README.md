# Intergalactic Gaming Club

Website for the Intergalactic (IG) gaming club — a casual-competitive community across the GCC with chapters in Doha, Lusail (Qatar), Manama (Bahrain), and Riyadh (Saudi Arabia).

## Games
- Rocket League
- Pokémon

## Stack
Single `index.html` — plain HTML, CSS, and vanilla JavaScript. No frameworks, no build tools.

## Features
- Animated starfield background
- Achievement Wall with game filter
- Member profiles with ranks
- Live challenge countdown timer
- Rules & About accordion
- Mobile-responsive

## Data
All content lives in a `DATA` object at the top of the `<script>` tag. It's structured to mirror a Google Sheets layout — swap in a `fetch()` to a published Sheet JSON endpoint when ready (marked with a `TODO` comment in the code).
