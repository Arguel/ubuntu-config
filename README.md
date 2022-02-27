# ubuntu-config
Guide for installing my production environment

## Installations

- [Google Chrome](#google-chrome) - [Homepage](https://www.google.com/chrome/)
- [cURL](#curl) - [Homepage](https://curl.se/)
- [NVM](#nvm) (Node Version Manager) - [Official repository](https://github.com/nvm-sh/nvm)
- [Git](#git) - [Homepage](https://git-scm.com/)
- [Vim](#vim) - [Homepage](https://www.vim.org/)
- [Neovim](#neovim) - [Homepage](https://neovim.io/)
- [Screenfetch](#screenfetch) - [Official repository](https://github.com/KittyKatt/screenFetch)
- [Zsh](#zsh) - [Homepage](https://www.zsh.org/)
- [Oh My ZSH!](#oh-my-zsh!) - [Homepage](https://ohmyz.sh/)


### Google Chrome
1. [Download the installer](https://www.google.com/chrome/)
2. Open your downloads folder in the terminal and install chrome with the following command, you can use the <b>tab</b> key to autocomplete your version of chrome download
    <pre><code>sudo dpkg -i google-chrome-[REPLACE WITH YOUR DOWNLOADED VERSION]</code></pre>

### cURL
1. Update your Ubuntu with the following command
    <pre><code>sudo apt update && sudo apt upgrade</code></pre>
2. Install cURL with the following command
    <pre><code>sudo apt install curl</code></pre>

### NVM
1. Installation instructions in its [official repository](https://github.com/nvm-sh/nvm#installing-and-updating)
2. The other option is to continue with these commands <b>(outdated)</b>
    <pre><code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash</code></pre>
    <pre><code>source ~/.bashrc # update your current shell environment</code></pre>
    <pre><code>nvm install node # "node" is an alias for the latest version</code></pre>

### Git
1. Run the following command
    <pre><code>sudo apt install git</code></pre>

### Vim
1. Run the following command
    <pre><code>sudo apt install vim</code></pre>

### Neovim
1. Run the following command
    <pre><code>sudo apt install neovim</code></pre>

### Screenfetch
1. Run the following command
    <pre><code>sudo apt install screenfetch</code></pre>

### Zsh
1. Run the following commands and configure your zsh
    <pre><code>sudo apt install zsh</code></pre>
    <pre><code>zsh -v</code></pre>
    <b>If you plan to use Oh My ZSH! press the "q" key, otherwise press the number "2"</b>

