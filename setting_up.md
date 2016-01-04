##Setting up for the Media^Alps Workshop on Mac OS X##

**Please note, Mac OS 10.9 (Mavericks) or higher is recommended. If possible, please update your operating system to at least 10.9.**

1. Open up a Terminal on your Mac. You can find Terminal within the Applications folder on your computer. It may be within a folder called "Utilities" You can also use Spotlight (by pressing ⌘ + spacebar) to search for "Terminal"

2. Install Xcode command-line developer tools. At the Terminal prompt, which ends with a $, type
```
xcode-select --install
```
Now press enter. This should start the installation process for the Xcode command line tools. Alternatively, you can download the complete Xcode package from the Mac App Store. Just search for Xcode.

3. Install Homebrew. This is a package manager that will allow you to easily install all of the software necessary for this workshop. To install Homebrew paste this command into your Terminal and press enter to run it. 
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
4. When Homebrew is finished installing type
```
brew update
```
And press enter. Homebrew will either update itself or display a message that it is already up-to-date. 

5. Install git. This is the version control software that we will use. Installing git will allow us to work with GitHub. To install git type
```
brew install git
```
and press enter. Now wait for Homebrew to install git. 
6. Install vrecord. Vrecord is open-source video capture software for archivists and conservators. First type
```
brew tap amiaopensource/amiaos
```
And press enter. Now type
```
brew install vrecord
```
and press enter. This will install vrecord as well as video transcoding software called ffmpeg. We will discuss vrecord and ffmpeg during the workshop.  
You may be interested in checking out the vrecord project at https://github.com/amiaopensource/vrecord

##Questions and Issues##
If you have any questions or issues with the installation instructors. Please contact the Media^Alps organizers.  




