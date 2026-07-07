# Daily Log

## Day 001 — July 4, 2026 — Initial Setup

### What I Did

- Created the GitHub repository for the LB project
- Set up the project as a public documentation and progress log
- Decided the repo will track the planning, goals, roadmap, and daily progress of building LB
- Started organizing the project into separate files instead of putting everything in one large README

### Notes

Day 1 was focused on getting the project started and creating a clean foundation.

## Day 002 — July 5, 2026 — Project Planning and Documentation

### Summary

Worked on defining the overall purpose of LB and organizing the project documentation.

### What I Did

- Wrote the main project goals
- Added a clear description of what LB is intended to become
- Added personal automation goals such as resale help, trading research, email, scheduling, and weekly tee times
- Added a small security-focused note about safe handling of accounts, permissions, API keys, and personal data
- Created technical information for the project
- Documented the main hardware being used for the project
- Listed planned software and tools such as Claude, Python, GitHub, Discord, eBay, Telegram, and Skylight Calendar

### Notes

Day 2 was focused on making the project look organized and intentional before jumping deeper into code.

## Day 003 — July 6, 2026 — Telegram and News Source Testing

### Summary

Worked on early testing for LB by experimenting with Telegram alerts and news source connections.

### What I Did

- Started setting up Telegram as a future alert system for LB
- Looked into how LB could send messages to Telegram when something needs my attention
- Tested the idea of using Telegram as the main notification method instead of relying on constant phone notifications
- Began exploring news sources that LB could eventually read and filter
- Tried connecting or using a news source link, but the link did not work correctly
- Documented the issue instead of skipping over it
- Continued thinking through how LB could use news, market updates, and other information sources for decision support

### Notes

Telegram was successfully completed and is now up and running as a notification option for LB. This gives the project a working alert path that can be used later when LB finds something important.

I also tested the idea of connecting LB to news sources. The news source test did not fully work because the link failed, but it still helped identify an area that needs more testing.

Some news sources appear to block bot traffic, so I need to either find the correct accessible link, use a supported feed/API, or build a cleaner workaround for reliable access.

---

## Day 003 — July 7, 2026 — Discord-to-eBay Planning

### Summary

Today is focused on planning the first major LB workflow: connecting Discord deal alerts to eBay resale research.

### What I Am Working On

- Identify how LB will read deal alerts from Discord
- Decide which Discord channels or alert sources should be monitored first
- Start planning how LB will pull useful information from each alert
- Focus on key details like item name, price, store, link, and category
- Plan the first filter rules, including ignoring Pokémon-related items
- Research how LB can check eBay sold comps for matching items
- Start thinking through how profit will be estimated after fees, shipping, and item cost
- Connect the Discord alert process to the Telegram notification system that was completed on Day 2

### Goal for Today

The main goal is to define the first working Discord-to-eBay pipeline.

The planned flow is:

1. LB reads a Discord deal alert
2. LB extracts the useful item information
3. LB ignores alerts that do not match my buying criteria
4. LB checks eBay sold comps
5. LB estimates whether the item has resale value
6. LB sends a Telegram alert if the item looks worth buying

### Notes

