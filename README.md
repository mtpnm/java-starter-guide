### Install GIT
Type in `git` in `Terminal` a popup should appear to install xcode development tools, install that.

### Install a package manager for mac to install Java package
The package manager is called Homebrew for Mac. It is available at `www.brew.sh` or just google `homebrew for mac`. After visting the site there is a command similar to:

    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    
 Copy and paste it in `Terminal` app in mac.
 Follow the steps, it should ask for your mac user once or twice. Once its completed you can verify its installation by typing `brew` in `Terminal`.
 
 ### Install Java with the Brew package manager
 Enter the following two commands in `Terminal` to install Java 11 LTS(Long term support).
 
    brew tap AdoptOpenJDK/openjdk
    brew cask install adoptopenjdk11
    
 Verify that java has been installed using command `java -version`
 
 ### Install IntelliJ IDE
 Google `intellij mac download` and navigate to the following website:

    https://www.jetbrains.com/idea/download/#section=mac
    
 Download the `Community Edition` since its free.
 
