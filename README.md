# Everyday or Sometimes? The Kids' Food Game

A food game for kids ages 5 to 10, built by a parent in one night with AI.

Kids sort real foods into "everyday fuel" and "sometimes treats," make smarter swaps, rank foods into word tiers, play label detective with (clearly fictional) nutrition labels, and finish a five-question daily quiz. The library has 109 foods: breakfasts, lunchbox staples, family dinners, snacks, drinks, and the treats kids actually ask for.

## Play it

Open `index.html` in any browser. No install, no account, no server. To host it free: drop the file in a GitHub repository, turn on GitHub Pages, done.

## How it plays

- **Today's Five:** a daily five-question quiz, the same all day, fresh tomorrow. Finishing earns a Show-Up Star, any score.
- **Play:** an endless mixed rotation of every question type.
- **Family Missions:** one mission a week for the whole family, like a grocery store fruit hunt.
- Missed questions come back a few questions later for another try. First-try answers are what count in the daily quiz.

## The design rules (the point of the project)

This game was built because the app stores did not have one like it. Most kids' food games moralize, grade, or pretend treats do not exist. This one follows different rules:

1. **Everyday vs. sometimes, never good vs. bad.** Treats are part of the game and part of life. They are just outnumbered.
2. **No letter grades.** Foods rank into four word tiers (Power Fuel, Everyday, Middle, Sometimes). A near miss gets "Close!" and an explanation, not a failure.
3. **No weight, body, size, or diet talk anywhere.** The confidence questions are about what bodies can do, never how they look.
4. **Stars reward showing up, never performance.** One star per day the daily quiz is finished, any score. Stars never disappear, and there is no streak to break.
5. **Every explanation has to be defensible out loud to another parent.** Each answer explains what is inside a food and what it does for you, in plain words a six-year-old can follow.
6. **Two numbers, max.** Today's score and the star count. Nothing else to compare yourself against.

## Privacy

- No personal information, no names, no accounts, no tracking, no ads.
- The only thing the game stores is the list of days the daily quiz was finished, in the browser's local storage on that device. Nothing leaves the device.
- A note for grown-ups is included in the game: some everyday foods (peanut, milk, egg) are allergens for some kids, and the game is general learning, not medical advice.

## Tech

One self-contained HTML file. No build step, no dependencies, no backend. The nutrition labels in Label Detective mode are fictional and labeled as such.

## Why it exists

A parent looked for a game that teaches kids about food without shame, grades, or body talk, could not find one, and built it instead, with AI writing the code and the content and a second AI audit pass catching the claims that were overstated. The full story is AI Lab Experiment 015 at liamdarmody.ai.

Built by Liam Darmody. More at LIAMDARMODY.ai
