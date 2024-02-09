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



