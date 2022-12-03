# Steam Deck Ansible setup.

`bootstrap_steam_deck.yml` should go to your SDCard.

- Ensures the presence of a ssh public key for steam deck


- Installs the following as part of the baseline
- [Homebrew](https://brew.sh/)
- [Btop] (https://github.com/aristocratos/btop)

- Installs the following as homebrew formulae
    - neofetch
    - kubectl

- Installs the following as flatpaks
    - vscode