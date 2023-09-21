# Entorno en WSL (Ubuntu 18.04) y Vim con Plugins 
Instalación y Archivos de Configuración

## WSL
1. Instalar WSL, Windows Terminal, NVM, Node.js (necesario para algunos plugin de vim) y Npm con esta práctica guía de Microsoft, puedes omitir la instalación de Visual Studio Code sí estas interesado en usar Vim + Plugins [Install Node.js on Windows Subsystem for Linux (WSL2)](https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl)
## Vim + Plugins
1. Es recomendable usar la versión mas reciente de vim (8.2 al escribir esta referencia) para asegurar completa compatibilidad de los plugins, por ello recomiendo seguir esta guía de los amigos de [It's FOSS](https://itsfoss.com/vim-8-release-install/)
2. Ahora podemos ir convirtiendo vim en nuestro nuevo IDE favorito con la ayuda de un gestor de plugins que nos permitirá agregar uno a uno los que vayamos necesitando en el camino, en este caso usaremos [vim-plug](https://github.com/junegunn/vim-plug) como gestor, a la fecha vengo utilizando los siguientes:
- 'easymotion/vim-easymotion' - Para busqueda rápida de texto
- 'preservim/nerdtree' - Arbol de archivos
- 'christoomey/vim-tmux-navigator' - Moverse entre paneles
- 'neoclide/coc.nvim' - Completar código
- 'honza/vim-snippets' - Snippets, depende de COC.vim
- 'vim-airline/vim-airline' - Barra inferior de estado
- 'vim-airline/vim-airline-themes' - Temas para la barra de estado
- 'tpope/vim-fugitive' - 
- 'junegunn/fzf' - Busqueda de archivos por nombre y contenido
- 'junegunn/fzf.vim' - comandos para fzf
- 'airblade/vim-rooter' - 
- 'tpope/vim-surround' " Surround ysm)
- 'tpope/vim-commentary' - Para comentar lineas y bloques
- 'ap/vim-css-color' - Preview de colores en CSS
- 'ryanoasis/vim-devicons' - Iconos para Developer en nerdtree
- 'preservim/tagbar' " Barra superior de tabs
- 'mg979/vim-visual-multi' - CTRL + N para multiples cursores
1. 