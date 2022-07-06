# ubuntu-config
Guide for installing my production environment

## Installations

- [Google Chrome](#google-chrome) - [Homepage](https://www.google.com/chrome/)
- [cURL](#curl) - [Homepage](https://curl.se/)
- [Git](#git) - [Homepage](https://git-scm.com/)
- [Vim](#vim) - [Homepage](https://www.vim.org/)
- [Screenfetch](#screenfetch) - [Official repository](https://github.com/KittyKatt/screenFetch)
- [Zsh](#zsh) - [Homepage](https://www.zsh.org/)
- [Oh My ZSH](#oh-my-zsh) - [Homepage](https://ohmyz.sh/)
- [Tmux](#tmux) - [Official repository](https://github.com/tmux/tmux)
- [NVM](#nvm) (Node Version Manager) - [Official repository](https://github.com/nvm-sh/nvm)
- [Neovim](#neovim) - [Homepage](https://neovim.io/)
- [Postman](#postman) - [Homepage](https://www.postman.com/)

### Google Chrome
1. [Download the installer](https://www.google.com/chrome/)
2. Open your downloads folder in the terminal and install chrome with the following command, you can use the <b>tab</b> key to autocomplete your version of chrome download
    <pre><code>sudo dpkg -i google-chrome-[REPLACE WITH YOUR DOWNLOADED VERSION]</code></pre>

### cURL
1. Update your Ubuntu with the following command
    <pre><code>sudo apt update && sudo apt upgrade</code></pre>
2. Install cURL with the following command
    <pre><code>sudo apt install curl</code></pre>

### Git
1. Run the following command
    <pre><code>sudo apt install git</code></pre>

### Vim
1. Run the following command
    <pre><code>sudo apt install vim-gtk3</code></pre>
    **Or**
    <pre><code>sudo add-apt-repository ppa:jonathonf/vim</code></pre>
    <pre><code>sudo apt update</code></pre>
    <pre><code>sudo apt install vim</code></pre>

### Screenfetch
1. Run the following command
    <pre><code>sudo apt install screenfetch</code></pre>

### Zsh
1. Run the following commands and configure your zsh
    <pre><code>sudo apt install zsh</code></pre>
    <pre><code>zsh</code></pre>
    <b>If you plan to use Oh My ZSH! press the "q" key, otherwise press the number "2"</b>

### Oh My ZSH
1. Installation instructions in its [official repository](https://github.com/ohmyzsh/ohmyzsh#basic-installation)
2. <b>(optional)</b> [Install my setup](https://github.com/enzoarguello512/oh-my-zsh-config)

### Tmux
1. Run the following command
    <pre><code>sudo apt install tmux</code></pre>
    
### NVM
1. Installation instructions in its [official repository](https://github.com/nvm-sh/nvm#installing-and-updating)
2. The other option is to continue with these commands <b>(outdated)</b>
    <pre><code>curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash</code></pre>
    <pre><code>source ~/.bashrc # update your current shell environment</code></pre>
    <pre><code>nvm install node # "node" is an alias for the latest version</code></pre>

### Neovim
1. Run the following command
    <pre><code>sudo add-apt-repository ppa:neovim-ppa/unstable</code></pre>
    <pre><code>sudo apt-get update</code></pre>
    <pre><code>sudo apt-get install neovim</code></pre>
2. <b>(optional)</b> install dependencies
    <pre>
    <code>sudo apt install python3-pip</code>
    
    <code>sudo apt install python3-venv</code>
    
    <code>npm install -g neovim</code></pre>

### Postman
1. Run the following command
    <pre><code>sudo snap install postman</code></pre>

