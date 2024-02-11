# openbox-config

Configurações do OpenBox localizada em  ~/.config/openbox


Instalação do OpenBox nas distribuições Linux:

Void Linux

xbps-install -Suvy openbox


Pré-requisitos para usar essas configurações do OpenBox:

- obconf (Editor de configuracões gerais para OpenBox)
- nitrogen (Para trocar o Wallpaper)
- conky (Monitor de sistema)
- polkit-gnome (polkit-gnome-authentication-agent-1)
- compton (Para os efeitos com janelas)
- scrot ou xfce4-screenshooter (Captura de tela)
- htop ou xfce4-taskmanager (Gerenciador de tarefas)
- tint2  (Painel)
- thunar (Gerenciador de arquivo)
- xfce4-terminal ou xterm (Terminal)
- plank (Dock)
- xkill (Em caso de travamento ou congelamento inesperado de um determinado programa grafico)
- gedit (Editor de texto)
- gmrun (Caixa executar podendo ser adicionada ao menu do OpenBox, no painel e ser acionada por tecla de atalho.)
- lxappearance lxappearance-obconf
- wmctrl
- numlockx (ligar o teclado numérico na inicialização)
- volumeicon (volume de som)
- neofetch
- gthumb
- galculator
- qmmp
- dropbox
- masterpdfeditor
- Firefox
- Google Chrome
- Thunderbird
- ClipGrab
- vlc
- GIMP
- LibreOffice
- xsane
- ssr
- wget
- ffmpeg
- xrandr

 

Instalação:

Clonando o repositório

$ cd ~/.config/ && git clone https://github.com/tuxslack/openbox-config.git

$ rm -Rf ~/.config/openbox
$ mv  -i ~/.config/openbox-config    ~/.config/openbox
$ rm -Rf ~/.config/openbox/.git      ~/.config/openbox/README.md


Para atualizar as configurações do OpenBox

$ openbox --reconfigure

