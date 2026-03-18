# starship
Patrick's custom starship config file.

# Set up

1. Install starship:

```bash 
curl -sS https://starship.rs/install.sh | sh
```

2. Add the following to .bashrc:

```bash 
export STARSHIP_CONFIG="$HOME/.config/starship/starship.toml"

eval "$(starship init bash)"
# Or eval "$(starship init zsh)" for zsh users
```

3. If Nerd Fonts are not installed, install them!

```bash
# Example (JetBrains Mono Nerd Font)
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts
wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip
unzip JetBrainsMono.zip
fc-cache -fv
```
