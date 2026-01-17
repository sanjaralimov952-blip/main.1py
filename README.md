#!/bin/bash

echo "Системаны жаңыртуу башталды..."
sudo apt update
sudo apt upgrade -y

echo "Visual Studio Code орнотулуп жатат..."
sudo snap install code --classic

echo "Орнотуу аяктады!"
echo "VS Code иштетүү үчүн терминалга: code"
