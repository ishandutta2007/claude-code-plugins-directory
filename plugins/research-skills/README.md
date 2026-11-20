# research-skills

research-skills is an MIT-licensed Claude Code plugin marketplace of Agent Skills for designing questionnaires and analyzing survey data. Skills that compute results ship small Python scripts (Python 3.9 or later, standard library only, no network calls) with tests.

Repository: https://github.com/questionpunk/research-skills

## What it covers

- Survey design: questionnaire wording checks, surveys designed from the decision they inform, recruiting screeners, sample size and power, Qualtrics QSF conversion
- Pricing research: Van Westendorp, Gabor-Granger, MaxDiff and conjoint design and analysis
- Feedback analysis: NPS, CSAT and CES, product-market fit, Likert scales, UX scales such as SUS, Kano, crosstabs, weighting, data cleaning and open-ended coding
- Interviews: turning a discussion guide into a brief for an AI moderator

## Install

Run these commands in Claude Code:

```text
/plugin marketplace add questionpunk/research-skills
/plugin install research-skills@research-skills
```

The marketplace also has one plugin per method group: `survey-design`, `pricing-research`, `feedback-analysis` and `interviews`.

## Examples

Give Claude a questionnaire or a survey data file and describe the result you need:

- "Review questionnaire.md for leading and double-barreled questions. Quote each problem question and suggest a rewrite."
- "Read the 0-10 recommendation scores in feedback.csv and report NPS with its margin of error."
- "Compute the Van Westendorp acceptable price range from the answers in pricing.csv."

## Notes

- The skills work on local files and need no account.
- Some skills end with an optional "Field it" step that uses QuestionPunk's MCP server (OAuth sign-in) to create, change or publish a survey in the user's own QuestionPunk account. The skills tell the agent to ask before creating, changing or publishing anything.
- The marketplace also lists an optional `questionpunk` plugin (questionpunk/claude-plugin) that connects that MCP server.
