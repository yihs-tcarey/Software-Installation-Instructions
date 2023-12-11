# Software-Installation-Instructions


## Installing Git

### Windows
If you are on Windows, download and install Git-Bash from the following link:

[64-bit Git for Windows](https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe)

### Mac
If you are on Mac, you will have to install HomeBrew first. Open a terminal and run:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Follow the installation prompts for Home-brew accepting all defaults. Once it completes, you can install Git by running:
```
brew install git
```

### Linux
If you are on Linux, you likely already have Git installed. Check by typing the command:
```
git -—version 
```


If git is not already installed on your Linux system, run:
```
sudo apt install git
```

## Digital Circuit Simulator
Download the zip file from the following link and extract to your home folder:
```
https://github.com/hneemann/Digital/releases/latest/download/Digital.zip
```


Open your terminal, navigate to the “Digital” folder under your home folder with the following command:
```
cd ~/Digital
```


Then, to run the program, enter the command:
```
java -jar Digital.jar
```
