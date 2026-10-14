# ridjex/tap

Homebrew formulae for [lightkeeper](https://github.com/ridjex/lightkeeper), a tool that reviews GitHub pull
requests in your name by plain-language rules through your own `gh` and `claude` logins.

```sh
brew install ridjex/tap/lightkeeper
lightkeeper --init          # creates ~/.config/lightkeeper/{settings.toml,rules.md}
lightkeeper --once --plain  # one dry-run pass
lightkeeper                 # the screen; or: brew services start lightkeeper
```

Prerequisites: the GitHub CLI (`gh`, installed as a dependency) logged in as you, and the Claude Code CLI
(`claude`) installed and logged in. Updates: `brew upgrade lightkeeper` (stop the service first).
