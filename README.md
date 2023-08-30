# install-docker

docker run -p 6080:80 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc

nomachine:

curl -sLkO https://is.gd/nomachinewindows10 ; bash nomachinewindows10

curl -sLkO https://is.gd/nomachinewine ; bash nomachinewine

curl -sLkO https://is.gd/nomachineMATE ; bash nomachineMATE

curl -sLkO https://is.gd/nomachinexfce4 ; bash nomachinexfce4

# install-Git

sudo apt-get update

sudo apt-get install git -y

git clone https://github.com/ophigeni/selenium-ophigeni


# install-selenium-and-ect

wget -nc https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo apt update

sudo apt install -f ./google-chrome-stable_current_amd64.deb -y

mkdir tests && cd tests

apt-get install python3-venv -y

python3 -m venv venv

source venv/bin/activate

pip install selenium webdriver-manager
