# Configurações do Vim/Neovim

Este repositório contém arquivos de configuração personalizados para o Vim e Neovim, otimizados para desenvolvimento com várias funcionalidades e plugins.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Plugins](#plugins)
- [Instalação](#instalação)
- [Configurando o Vim](#configurando-o-vim)
- [Configurando o Neovim](#configurando-o-neovim)
- [Atualizando as Configurações](#atualizando-as-configurações)
- [Temas](#temas)

## Pré-requisitos

Antes de começar, certifique-se de que você tenha o Vim ou o Neovim instalados no seu sistema.

- **Instalar Vim**:
  ```bash
  apt install vim
  ```
- **Instalar Neovim**:
  ```bash
  apt install neovim
  ```
  
## Plugins
Instale o Vim Plug seguinte o tutorial oficial:
https://github.com/junegunn/vim-plug

## Configurando o Vim

Siga os passos abaixo para baixar e aplicar as configurações deste repositório.

1. **Clone este repositório:**

   No terminal, execute o comando:

   ```bash
   git clone https://github.com/Maycon40/config_nvim.git
   ```
   
2. **Navegue até o diretório do repositório:**
   ```bash
   cd config-nvim
   ```
   
3. **Copie o arquivo .vimrc para o diretório home:**
   ```bash
   cp config.vim ~/.vimrc
   ```

4. **Instale os plugins:**
   ```bash
   vim +PlugInstall +qall
   ```
   
## Configurando o Neovim
   
1. **Crie o diretório de configuração do Neovim, se necessário:**
   ```bash
   mkdir -p ~/.config/nvim
   ```

2. **Copie o arquivo init.vim para o diretório de configuração do Neovim:**
   ```bash
   cp config.vim ~/.config/nvim/init.vim
   ```

3. **Instale os plugins:**
   ```bash
   nvim +PlugInstall +qall
   ```
