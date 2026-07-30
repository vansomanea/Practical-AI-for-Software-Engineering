# Lab notes

*Fill this in as you go — it's part of your submission (Lab 0).*

## Statelessness
What happened when you sent only the latest message vs. the full history?
Sending only the latest message reduces context, but increases efficiency. Full history provides more context, but can be verbose. I'm set for concise responses.


## Temperature
How did `--temp 0.2` compare to `--temp 1.3` on the same prompt?
`--temp 0.2` yields more deterministic, less creative responses. `--temp 1.3` produces more varied, potentially less accurate output. Current setting: `--temp 0.2` for direct answers.


## Tokens
What did you notice about token counts as prompts got longer?
Longer prompts hit token limits, get truncated. Keep it short.

## Anything that surprised you or broke
When I asked the same question again, it gives me shorter answers the more I asked.
