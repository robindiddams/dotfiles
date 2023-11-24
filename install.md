
### installation

copy everything into ~

install starship:

```bash
#load aliases

cp .aliases ~ && echo "source .aliases" >> ~/.zshrc

# install starship
brew install starship
echo 'eval "$(starship init zsh)"' >>~/.zshrc

# install fira code

brew tap homebrew/cask-fonts && brew install --cask font-fira-code-nerd-font

```
