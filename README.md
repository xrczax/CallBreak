# CallBreak
# Callbreak Digital Scorecard

A lightweight, responsive, and feature-rich digital scorecard web application built specifically for physical **Callbreak** card games. No backend required—runs entirely in your browser with persistent local storage support.

## Features

- **Custom Setup:** Enter custom names for all 4 players and configure the match length (between 5 to 8 rounds).
- **Two-Phase Workflow:** 
  - **Bidding Phase:** Record each player's bids (hands declared) before the round begins.
  - **Result Phase:** Input actual hands made after the physical game concludes.
- **Custom Scoring Engine:** Implements the exact rule set:
  - *Success Zone:* Exact match multiplies base bid by 10 (e.g., $4 \rightarrow +40$), with $+1$ or $+2$ points added for 1 or 2 extra hands won.
  - *Penalty Zone:* Failing to meet the bid or over-bidding by 3 or more hands incurs a negative penalty ($-\text{Bid} \times 10$).
- **Live Tracking:** Tracks the rotating dealer and displays the active Trump Card (Hukam) for each round.
- **Master History Matrix:** View a complete round-by-round breakdown of bids, actual results, round points, and cumulative running totals.
- **Data Persistence:** Automatically saves your match progress using browser `localStorage` so accidental refreshes or closures won't erase your game.
- **Edit & Undo:** Easily fix or update scores if an entry mistake is made.
- **Final Podium & Image Export:** Generates a celebratory standings screen at the end of the match and allows you to download the complete scorecard as a clean image (PNG) to share with friends.
- **Sleek UI/UX:** Styled with a modern "Night Card Table" dark theme, smooth glassmorphism effects, and optimized typography.

## Getting Started

1. Download or copy the `callbreak-scorecard.html` file to your device.
2. Double-click the file to open it in any modern web browser (Chrome, Safari, Firefox, Edge).
3. Enter player names, choose your round length, and start tracking your game!
4. 
