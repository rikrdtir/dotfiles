<h1>
  My configs to linux
</h1>


# My terminal
<a href="https://gnunn1.github.io/tilix-web/">Tilix</a>
  # Zsh

<h4>Plugins</h4>
To improve my experience with the terminal, I use the following plugins

  1. <a href="https://github.com/zdharma-continuum/fast-syntax-highlighting">fast-syntax-highlighting</a>

     ```
       source ~/path/to/fsh/fast-syntax-highlighting.plugin.zsh
     ```
  3. <a href="">zsh-autosuggestions</a>
  
     ```
      git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
     ```
  3. <a href="https://github.com/jeffreytse/zsh-vi-mode">Zsh Vi Mode</a>
  
     ```
     git clone https://github.com/jeffreytse/zsh-vi-mode \
     $ZSH_CUSTOM/plugins/zsh-vi-mode
     ```
     ```
     source $HOME/.zsh-vi-mode/zsh-vi-mode.plugin.zsh
     ```
  4. LSD (LSDeluxe): Apareace of icons to files in terminal
     ```
     sudo dnf install lsd
     ```
<h2>Prompt <a href="https://starship.rs/">starship</a> </h2>
  
  1. Install startship
     
     ```
     curl -sS https://starship.rs/install.sh | sh
     ``` 
  3. Add the following to the end of ```~/.zshrc```:

     ```
     eval "$(starship init zsh)"
     ```
  

<h2>My theme</h2>


