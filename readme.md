## Shell do Kali no Ubuntu

### 1. Instalando Pacotes Necessários:

> sudo apt update

> sudo apt install zsh

### 2. Instalando Plugins ZShell:

> sudo apt install zsh-syntax-highlighting

> zsh-autosuggestions

### 3. Instalando Fontes, QTerminal e Gnome-Tweaks:

> sudo apt install qterminal fonts-firacode gnome-tweaks

### 4. Modificar o arquivo .zshrc

#### 4.1 Substitua o arquivo .zshrc pelo arquivo .zshrc disponível neste repositório.

#### 4.2 - Efetivando as alterações:

> source .zshrc

#### 5. Color Scheme e Themes:

> git clone https://github.com/linuxopsys/ubuntu-to-kali-terminal.git

> cd ubuntu-to-kali-terminal/

> tar -xvf color-schemes.tar

> tar -xvf kali-dark-theme.tar

##### Após a extração será observado um diretório usr dentro de ubuntu-to-kali-terminal/

> ls


##### Vamos agora remover o atual diretório qtermwidget5/ e substituílo pelo presente dentro desse usr/:

$ sudo rm -rf /usr/share/qtermwidget5

$ sudo mv -f usr/share/qtermwidget5 /usr/share

### 6. Alterando Configurações no Terminal:

##### Abrir o QTerminal :
##### e em Arquivo > Preferências

###### Selecionar o Esquema de Cores Kali-Dark;
###### Em Transparência de Aplicativo: 5%;
###### Em Transparência de Terminal: 0%
###### Apply e Ok

### Para alternar entre o bash e o zsh:
##### Para zsh:
> zsh
##### Para bash:
> bash

### Ref.:
https://plus.diolinux.com.br/t/shell-do-kali-no-ubuntu/62773





