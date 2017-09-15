# Setup Git on Mac OS X

There are two easy ways to install Git on OS X. 

## Git by XCode 
Xcode is an integrated development environment for OS X, it contains a suite of software development tools developed by Apple. You can install XCode by App Store. 

![image](https://github.com/wYaobiz/YaoAt505/blob/master/screenshot/macosxSetup/2.png)

Once you have installed XCode, Git will be integerated. 
To verify if Git has been installed, using Terminal.app to enter command ```git --version```. 

![image](https://github.com/wYaobiz/YaoAt505/blob/master/screenshot/macosxSetup/1.png)

## Use Mac Installer 
If you don't want to install XCode, you can try to get the offical Git Insstaller for Mac OS X. 

### 1. Get the lastest installer file
You can always find it at

*[Official Source](https://sourceforge.net/projects/git-osx-installer/files/), 

or  

*[GitHub Repo](https://github.com/timcharper/git_osx_installer)

### 2. Open the installer .pkg files, follow the prompts. 
If you are under a higher version OS X, you might be not allowed to open it, because it is from an unidentified developer.

![image](https://github.com/wYaobiz/YaoAt505/blob/master/screenshot/macosxSetup/3.png)

If this happened, go to 'System Preferencs' -> 'Security & Privacy', under the 'General' Tab, you'll find previous warning message about refusing to open installer. Click the 'Open Anyway' button. Then you can go through the installation process step by step. 

![image](https://github.com/wYaobiz/YaoAt505/blob/master/screenshot/macosxSetup/4.png)

### 3. Verify
Use the Terminal.app to verify the installation, open it and enter ```git --version```.

It would be successfully installed if Terminal could retrieve the right git version number. 

![image](https://github.com/wYaobiz/YaoAt505/blob/master/screenshot/macosxSetup/5.png)

    

