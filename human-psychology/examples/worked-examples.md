# Worked Examples (model outputs)

Use these as the quality bar for diagnose-mode answers.

## Example 1: "Why do people abandon our app's signup halfway?" (T1)
```
Target behavior: complete signup (5 screens)
Who: first-time mobile visitors from social ads | Context: phone, short sessions
Capability gaps: none major; password rules unclear
Opportunity gaps: signup asks for credit card on screen 3 before any value shown
Motivation: moderate curiosity from ad; no proof of value yet
Strongest friction: card request; 11 form fields; forced email verification mid-flow
Rewards now: none until signup ends (delayed)
Biggest single barrier: asking for payment before value (perceived risk + effort)
Top 3 interventions:
 1. Show a working demo before signup (value first -> higher expectancy)
 2. Cut to email + password; delay profile fields (fewer steps -> ability up, Fogg)
 3. Move card to after the first success, with clear free-trial terms (lower risk)
Measure: completion rate per screen | Stop if: completion drops or refund requests rise
Evidence strength: friction reduction and defaults strong; exact gains vary, so A/B test
Ethics check: passed if trial terms and cancellation are clear and easy
```

## Example 2: "Players quit our mobile puzzle game around day 3" (T2, condensed)
```
Players: casual, mastery- and completion-motivated
First 5 min: first win at 20s; good
Core loop: swap -> match -> score -> next level; strong juice
Difficulty: spike at level 18 (completion drops sharply) -> competence frustration
Progression: levels only; no mid-term goals after day 2 -> no new goals
Autonomy: none (linear path)  Competence: unclear why you failed  Relatedness: none
Likely quit reasons: day 3 spike plus no mid-term goals
Top fixes: (1) smooth level 18 and show a hint after 3 fails; (2) add weekly collection goal;
 (3) optional friend leaderboard
Monetization: energy timer at level 15 feels like a paywall -> test removing for first week
Metrics: D1/D3/D7 retention; fail count per level
```

## Answer style reminders
Name the mechanism, grade the evidence, give the top 3 actions ranked, say how to measure, and run the ethics check. Keep explanations plain.
