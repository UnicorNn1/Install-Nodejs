## Build Nodejs
1. To install Node.js on a Linux system using the package manager for your specific distribution, you can use the following commands:

For Debian or Ubuntu:
  ```bash
  curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs
  ```
For CentOS/RHEL 8 or Fedora:
  ```bash
  sudo dnf module install nodejs:18/common
  ```
For Alpine Linux:
  ```bash
  sudo apk add nodejs npm
  ```
For Gentoo Linux:
```bash
  sudo emerge nodejs
  ```
These commands will install the latest LTS (Long Term Support) version of Node.js on your system. You can replace "18" in the command for CentOS/RHEL 8 or Fedora with the major version number of the Node.js release you want to install.

You can also install a specific version of Node.js using a version manager like nvm (Node Version Manager) or fnm (Fast Node Manager). Here are the commands to install and use nvm:

1-Install nvm using the following command:
```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
  ```
2-Restart your terminal.

3-Install a specific version of Node.js using nvm:
  ```bash
  nvm install 16.14.0
  ```
4-Set the installed version of Node.js as the default:
```bash
  nvm alias default 16.14.0
  ```
5-Verify the installed version of Node.js:
  ```bash
  node -v
  ```
## Install Nodejs
```bash
sudo apt install -y nodejs
```
```bash
sudo apt install -y npm
```
```bash
curl -sL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
```
```bash
sudo npm install -g npm@latest
```
## or
```bash
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.39.0/install.sh | bash
source ~/.profile
```
```bash
nvm ls-remote
```
```bash
nvm install 16.17.0
```
## with different command
```bash
curl -Ls https://deb.nodesource.com/setup_16.x | sudo bash
```
```bash
curl -Ls https://dl.yarnpkg.com/debian/pubkey.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/yarnkey.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/yarnkey.gpg] https://dl.yarnpkg.com/debian stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```
```bash
sudo apt -q update
sudo apt -qy install curl git jq lz4 build-essential nodejs=16.* yarn
sudo apt -qy upgrade
```
