# bin-dotfiles

Personal shell scripts for productivity. Intended to be cloned into `~/bin` and used globally.

---

## 🚀 Setup on a new machine


### One-line setup (zshrc)
```bash
cd ~ && git clone git@github.com:lhoogenraad/bin-dotfiles.git bin && \
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc && \
source ~/.zshrc && \
cd ~/bin && chmod +x *
```



### 1. Clone the repo into `~/bin`

```bash
cd ~
git clone git@github.com:lhoogenraad/bin-dotfiles.git bin
```

### 2. Add ~/bin to PATH

On Zsh:
```bash
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```


On Bash:
```bash
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```


### 3. Make all scripts executable
```bash
cd ~/bin
chmod +x *
```
