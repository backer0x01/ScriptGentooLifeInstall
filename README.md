# Instalação do Gentoo de forma automatizada!

# Como que faz?
### Antes de começar atualize seu repositório.
emerge --sync && emerge-webrsync && emerge --update --deep --with-bdeps=y --newuse @world
### E execute os comandos abaixo, mas com cuidado!

emerge -av github-cli

emerge --sync

emerge -u github-cli

emerge --ask app-shells/bash-completion

emerge --ask dev-vcs/git

gh repo clone git@github.com:backer0x01/ScriptGentooLifeInstall.git
ou
git clone https://github.com/backer0x01/ScriptGentooLifeInstall.git
# Instalação Final do Script
### Execute os comandos abaixo, mas com cuidado!
cd ScriptGentooLifeInstall

chmod 777 ScriptGentooLifeInstall.sh

bash ScriptGentooLifeInstall.sh
# Pronto!!!
### Aguarde a instalação.
