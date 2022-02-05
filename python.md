install python 3.10.x on ubuntu

go to https://www.python.org/downloads/source/
download desired version
unzip and cd into extracted directory

sudo apt update

sudo apt install build-essential zlib1g-dev libffi-dev

./configure --enable-optimizations
sudo make install
python3 --version

picharm installation
download and install
then add environment that uses 3.10.x version or whichever version is installed