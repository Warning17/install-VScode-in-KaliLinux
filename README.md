# install-VScode-in-KaliLinux
----
copia los siguientes comandos en tu terminal
----

*1- sudo apt update & apt upgrade*

*2- sudo apt install curl gpg software-properties-common apt-transport-https*

*3- sudo curl -sSL https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -*

*4- sudo echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list*

*5- sudo apt update & apt upgrade*

*6- sudo apt install code*
