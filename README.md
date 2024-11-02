# 🔮 Mastermind - A Second Brain for Spymasters

Mastermind is a CLI tool designed to generate clue words for spymasters in the game of **Codenames**, leveraging large language models (LLMs) of your choice!

Written in Rust 🦀, because why not?

![GitHub License](https://img.shields.io/github/license/theoforger/mastermind)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/theoforger/mastermind/.github%2Fworkflows%2Frust.yml)

<img src="images/demo.gif" alt="A gif demo of the basic functions of this program."/>

## 💻 Usage

To get started, prepare two text files:

1. **Words to Link Together** - Contains the words from your own team.
2. **Words to Avoid** - Contains:
    - Your opponent's words
    - Neutral words
    - The assassin word

One word per line. Refer to the [`examples`](examples) directory for sample files.

Run the tool with:

```bash
mastermind [TO_LINK] [TO_AVOID]
```

Feel free to run the program multiple times to get the best result!

### Options

- `-g`, `--get-models` : Print all available language models
- `-m`, `--set-models` : Select language model(s)
- `-o`, `--output` : Specify an output file
- `-t`, `--token-usage` : Print token usage
- `-h`, `--help` : Print help
- `-V`, `--version` : Print version
