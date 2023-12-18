# devenv

🍭 Configuration of my local development environment.

❗️ This is my personal configuration.
Please be attentive if you are going to reuse it.
Before applying this configuration, check it carefully and make sure it won't cause damage to your system.

📝 If you see that something could be improved, don't hesitate to offer a pull request.

## How to apply

### Brew
1. Install brew:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. Install development tools and applications:
```bash
brew bundle --file ./Brewfile.work
```

### Powerlevel10k
1. Make `powerlevel10k` theme default:
```bash
echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

