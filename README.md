# Luna on ProgramLab PoC20: scores by organisation setting

`scores.csv` gives, for each of 20 ProgramLab tasks, the score of GPT-6 Luna under four settings.

## Columns
- `task`: the ProgramLab task (repository and commit).
- `single`: one agent working alone.
- `1x5`: one group of 5 agents
- `2x5`: two groups of 5 agents each.
- `1x10`: one group of 10 agents.

## Setup
- Model: GPT-6 Luna, Codex harness, reasoning effort medium.
- Time limit: 30 minutes per episode.
- Tasks: PoC20, 20 ProgramLab tasks (7 hard, 13 medium), chosen as the decomposable tasks on which a single agent scored lowest in a screening run.

## Score
- The fraction of the task's hidden tests passed by the code. Range 0 to 1.
