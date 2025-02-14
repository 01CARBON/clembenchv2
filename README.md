### Updates
(November 2024): We have updated the framework code (again). If you have written games using v_1, see [this guide](docs/howto_update_to_v2.md) on how to update your game and [these instructions](docs/01_how_to_get_started.md) on how the new framework works.

(February 2024): We have updated the framework code. If you have written games using the initial release version, see [this guide](docs/howto_update_to_v1.md) on how to update your game.

# clembench: A Framework for the Systematic Evaluation of Chat-Optimized Language Models as Conversational Agents

The cLLM (chat-optimized Large Language Model, "clem") framework tests such models' ability to engage in games – rule-constituted activities played using language.
The framework is a systematic way of probing for the situated language understanding of language using agents.

This repository contains the code for setting up the framework that is discussed in 

> Chalamalasetti, K., Götze, J., Hakimov, S., Madureira, B., Sadler, P., & Schlangen, D. (2023). clembench: Using Game Play to Evaluate Chat-Optimized Language Models as Conversational Agents (arXiv:2305.13455). arXiv. https://doi.org/10.48550/arXiv.2305.13455

### Evaluation Results

On the [main project website](https://clembench.github.io) , under [leaderboard](https://clembench.github.io/leaderboard.html).

### Game details

see [games repository](https://github.com/clp-research/clemgames)
- A Simple Word Game: [taboo](docs/taboo.md)
- A Word-Guessing Game Based on Clues: [wordle](docs/wordle.md)
- Drawing Instruction Giving and Following: [image](docs/image.md)
- An ASCII Picture Reference Game: [reference](docs/reference.md)
- Scorekeeping: [private and shared](docs/privateshared.md)

## Using the benchmark

This repository is tested on `Python 3.8+`

We welcome you to contribute to or extend the framework with your own games and models. 
Please simply open a pull request. You can find more information on how to use the framework in the links below.

- [How to run the benchmark and evaluation locally](docs/howto_run_benchmark.md) # TODO: update
- [How to run the benchmark, update leaderboard workflow](docs/howto_benchmark_workflow.md) # TODO: update
- [How to add a new model](docs/howto_add_models.md)
- [How to add and run your own game](docs/howto_add_games.md) # TODO: update
- [How to integrate with Slurk](docs/howto_slurk.md)
