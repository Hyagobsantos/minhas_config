# minhas_config
Repositório para minhas configurações padrão


## .Bashrc 
### Alterando as cores do bash + mostrar a brach 

- Edite o Arquivo .bashrc e insira essas linas no final do arquivo e salve

```bash
export PS1='\[\033[0;33m\]\u\[\033[0;33m\]@\h\[\033[0;32m\] \w\[\033[1;31m\]$(__git_ps1 " (%s)")\[\033[0;32m\]$\[\033[00m\] '
```
```bash
export LS_COLORS='di=1;36'
```

## Tmux - Multplexidor 

- update e upgrade
  
```bash
sudo apt-get upgrade -y && sudo apt-get updade
```

- Instalar o Tmux
  
```bash
sudo apt-get install tmux 
```

- Verificar versão do tmux 
  
```bash
tmux -V
```

- Instalar o TPM (Tmux Plugin Manager)
  
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```








```
```
