# install-VScode-in-KaliLinux
----
copia los siguientes comandos en tu terminal
----

*1- sudo apt update*

*2- sudo apt install curl gpg software-properties-common apt-transport-https*

*3- curl -sSL https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -*

*4- echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list*

*5- sudo apt update*

*6- sudo apt install code*
