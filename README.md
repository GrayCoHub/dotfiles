# My Dotfiles

These are my dotfiles. To set up a new machine with my preferred configuration, follow these steps:

1. Install zsh: `sudo apt-get install zsh`
2. Install Chezmoi: `curl -sfL https://git.io/chezmoi | sh`
3. Clone this repository: `chezmoi init https://github.com/yourusername/dotfiles.git`
4. Apply the dotfiles: `chezmoi apply`
5. Install Oh My Zsh: `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
6. Copy the `.zshrc` file to the dotfiles repository: `cp ~/.zshrc path/to/dotfiles/repository/`
7. Push changes to Github: `chezmoi cd && git add . && git commit -m "Added my-oh-zsh dotfile" && git push`

Entirely questionable response from OpenAI dude.

