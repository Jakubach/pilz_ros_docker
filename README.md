# Configuration of ROS2 (GUI) inside Docker with VSCode

## Ubuntu 

Ubuntu guide is in official documentation:
https://docs.ros.org/en/humble/How-To-Guides/Setup-ROS-2-with-VSCode-and-Docker-Container.html

## Windows

### XLaunch Server for displaying GUI

#### 1. Install Xlaunch Server for displaying GUI:

https://sourceforge.net/projects/vcxsrv/

#### 2. Run Xlaunch Server and setup a display with port 0

Modified files for Windows are available within this repository.
- Changed `DISPLAY` from X11 to Xlaunch
- Changed GPU access for compatibility with Windows (https://stackoverflow.com/questions/49589229/is-gpu-pass-through-possible-with-docker-for-windows)

### VS code

#### 1. Install VS Code:

https://code.visualstudio.com/download

#### 2. Within VS Code search in Extensions (CTRL+SHIFT+X) for the "Remote Development" extension and install it.

### Docker

#### Install Docker Desktop:

https://docs.docker.com/desktop/install/windows-install/

### Running:

#### 1. Run Docker Desktop (into the background)

#### 2. Follow the steps:

![Alt text](https://images2.imgbox.com/81/14/L3HKlegP_o.png)

