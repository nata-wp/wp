#!/bin/sh
pkg update
pkg install wget -y
wget -O $PREFIX/bin/tbot https://raw.githubusercontent.com/TecnicalBot/tbot/main/tbot.sh
chmod +x $PREFIX/bin/tbot
echo "launch now "
tbot
