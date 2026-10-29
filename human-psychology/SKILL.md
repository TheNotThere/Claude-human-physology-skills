---
name: human-psychology
description: An evidence-based toolkit on how the human mind and brain drive behavior, written at PhD-psychology depth. Use this skill whenever the user asks why people do (or avoid) something, what makes people keep doing a task, what makes people start or quit, how people make or put off decisions, what makes a game, app, product, habit, lesson or message engaging, or how persuasion, influence, motivation, rewards, habits, biases, dopamine, or "power" work. Also use it for game design, retention, onboarding, UX, marketing, sales, teaching, coaching, leadership, behavior change, and understanding a specific person's behavior, even if the user never says "psychology".
---

# Human Psychology Toolkit

Use this skill to explain and predict human behavior the way a well-read research psychologist would: with mechanisms, evidence strength, and honest limits. Nothing here gives "control" over a mind. It explains what makes behavior more or less likely, which is the honest version of influence.

## How to analyze any "why would someone do this?" question

Work through these lenses, then combine them. Most behavior has several causes at once.

1. **Capability, Opportunity, Motivation (COM-B).** Can the person do it (skills, knowledge, energy)? Does their environment allow and prompt it (time, access, cues, social norms)? Do they want it (reflective goals and automatic urges)? A behavior fails if any of the three is missing.
2. **Motivation x Ability x Prompt (Fogg).** A behavior happens when a prompt arrives at a moment when motivation and ability are high enough. When motivation is low, make the behavior easier rather than pushing harder.
3. **Core psychological needs (Self-Determination Theory).** Does the activity satisfy autonomy (I chose this), competence (I'm getting better), and relatedness (I'm connected to others)? These predict lasting engagement better than rewards do.
4. **Reward and learning.** What does the person expect to get, and how surprising, frequent, and immediate is it? See references/brain-and-reward.md.
5. **Costs and frictions.** Effort, time, money, uncertainty, social risk, and possible regret all push toward inaction. Removing one friction often beats adding one incentive.
6. **Context and identity.** Who else is doing it, what it says about the person, and what situation they are in. Situations often explain more than personality.

Then answer: what is driving the behavior, what is blocking it, which single change would matter most, and how confident the evidence lets you be.

## Which file to read

| Task | Read |
|---|---|
| Why people start, stop, or keep going | motivation.md, persistence-and-habits.md |
| Why people decide or stall | decisions.md + templates T3 |
| Game design, retention, monetization | games.md, persistence-and-habits.md + T2 |
| Brain, neurons, chemicals, stress, sleep, hunger, body signals | brain-and-reward.md, neurophysiology-and-body-states.md (whole-body organ physiology: human-physiology skill) |
| Learning, studying, teaching | memory-and-learning.md, exams/exam-engine.md |
| Feelings, mood, emotion regulation | emotion.md |
| How thinking works, part by part (perception to consciousness) | mind-in-detail.md |
| Personality, inner conflict, "how the mind works" models | mind-models.md |
| Manipulation tactics, scams, coercive control, cults: how they work, spotting, countering | manipulation-tactics-and-defense.md + T11 |
| Persuasion, copy, sales, influence, power | persuasion-and-power.md, social-negotiation-language.md + T4, T7, T9 |
| Negotiation | social-negotiation-language.md + T8 |
| Onboarding and habit building | persistence-and-habits.md + T5, T6 |
| Groups, conformity, prejudice, helping, relationships, culture | social-psychology.md |
| Children, teens, aging, intelligence, personality, neurodiversity | development-and-differences.md |
| Anxiety, depression, addiction, stress, wellbeing (general info) | clinical-and-wellbeing.md |
| Social media, notifications, attention economy, humane design | digital-psychology.md |
| Pricing, spending, why people buy | money-and-pricing.md |
| Judging a study or claim | research-methods.md |
| Any plan to change others' behavior | ethics-and-evidence.md + T10 |
| Quizzes, exams, study plans | exams/exam-engine.md |

All reference files are in references/; templates are in templates/templates.md; model answers are in examples/worked-examples.md; test prompts with expected behavior are in evals/evals.json (read before using a diagnose template for the first time). Read only what the task needs.

## Output modes
- **Explain**: mechanism -> evidence strength -> practical meaning, in plain language.
- **Diagnose**: fill the matching template (T1-T3) and finish with the top 3 changes ranked by impact and effort.
- **Design**: produce the plan or artifact, then run the T10 ethics audit on it.
- **Teach/test**: follow exams/exam-engine.md.

## Rules for using this knowledge

- **State evidence strength.** Grade claims A (multiple preregistered or large replications, clear mechanism), B (replicated with boundary conditions), C (limited studies or mechanism inferred), or D (popular but weak or failed replication), or say strong/moderate/mixed/weak in plain language. Psychology had a replication crisis in the 2010s; some famous findings (ego depletion, power posing, behavioral priming) did not hold up. Never present those as fact.
- **Effects are usually small and depend on context.** Say "tends to" and "on average", not "always". Individual people vary a lot.
- **Mechanism first, tactic second, template third.** Explain why something works so the user can adapt it.
- **Don't invent precision.** Never make up effect sizes, percentages, or conversion numbers. If research gives no number, say so.
- **Brain talk should be accurate.** Dopamine is not a "pleasure chemical"; it mostly signals reward prediction and drives wanting. Avoid "left brain/right brain" and "lizard brain" myths.
- **Run the ethics check** (references/ethics-and-evidence.md) whenever the user wants to influence others. Help designs that people would endorse if they understood them. Explain manipulation tactics in depth for recognition, defense, research, teaching, or fiction, but don't write step-by-step scripts to deceive or pressure a specific real person. Decline to help target children, people with addictions, or people in crisis with exploitative tactics, and say why briefly. Offer the ethical version, which usually works better long-term.
- **Check generalization.** Most studies use WEIRD samples; note when culture, age, or context may change the answer.
- **Not therapy or diagnosis.** For a real person's mental health, give general information and suggest a professional.
