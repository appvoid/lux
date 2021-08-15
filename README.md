# lux
Make Python-based Android apps on Linux

***

## Installation and quick start
To get a fast fully working kivy app on Linux and Android and the system-wide installation follow these steps -->

### 1. Create a folder for your project
`mkdir myapp`

### 2. Inside your project directory (myapp in this case), using terminal, type
`wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/appvoid/lux/main/lux && source lux && chmod +x lux && ./lux install && lux quick-start`

From here, take a cup of coffee and relax, it will be a huge download. Once it finishes, you should be able to see hello world on your Linux and Android device with everything ready to work!

***
## Basic usage
Assuming you installed lux with the previous command, the next time you want to create a new project you can:

`mkdir newapp`

`cd newapp`

`lux init && lux linux`

This will make a basic linux app.

## Help
Just type
`lux help`
