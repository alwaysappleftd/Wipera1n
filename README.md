# Wipera1n
This is a tool that I coded to help people when they want to erase a checkm8-compatible device without losing the iOS version. The new Wipera1n version 1.3 now supports the iPhone 5s and iPhone 6! I have updated this repository with the latest Wipera1n executable. I am still in testing phases though, so there may be a few more updates to come. iPhone 6s to iPhone X should work seamlessly though. This tool doesn't require any special dependencies. All you need to do is enter DFU mode on your iDevice and the tool will work. 

Before first use, please check to make sure
you have the following
installed. If not, then
please install these
from the instructions below:

1. Git (You can install by installing Homebrew, instructions are at https://brew.sh , then once installed type into a new Terminal window "brew install git" without the qoutes. You can check if you already have Git installed by typing "which git", without the quotes, into a new Terminal window.
If Terminal doesn't output anything, then it's not installed.

2. Python3 (This is required to install Python2, which is needed for the script to remove signature checks. If you have IDLE or Python Launcher in your Applications folder then you quite likely have it installed. Just open the IDLE Appliation and see the gray title bar for the version. Any version of 3 is fine, just not "2". Just incase you need it, here's the link to download the latest version of Python3:

https://www.python.org/ftp/python/3.12.0/python-3.12.0-macos11.pkg

Click or paste this whole link into any
web browser to download.
Once everything here is done,
click OK to continue.

HOW TO USE WIPERA1N:
1. Connect your iDevice in normal mode.
2. Open Terminal which can be found in the Other folder in your Launchpad. Once you have a new window open, type 'cd' all lower case, and without the quotes. Put a space, then, drag and drop the Wipera1n folder you downloaded from here into the Terminal window. Now press enter.
3. Type './Wipera1n' without the quotes, and with a capital W. If you want, to make things quicker, you can type './Wi' with a capital W and without the quotes, then press the tab key on your keyboard to fill in the whole filename.
4. If there is a passcode on your device, then you can enter DFU mode, click Erase, and then click yes when you see the pop-up that asks if your device is in DFU mode already. Enter your iOS version with the steps listed in the text field, and Wipera1n will erase your device.
5. If you have not followed the steps above, and your device is unlocked in Normal mode, then first, click the Erase Device button. Once Wipera1n detects your iOS version, it will prompt you to enter DFU mode now. You can find out how to enter DFU mode on your device by Googling "How to enter DFU mode on" and then your iPhone model. Example might be "How to enter DFU mode on iPhone 7".
6. Once in DFU mode, click the OK button and the erase will start.

Please keep in mind:

If the device you are using is passcode locked or disabled, you may not know the iOS version of it. In this case, you can just put "12.0" in the version input text box. Remember that I fixed the issue where the user had to only put the first number in the version a few months ago, so you can put the entire full version with the in-between versions. So if your device was running iOS 13.4.1, you would put all of that into the box.
Also, if the device you are trying to wipe is an iPhone 5s, then I don't believe that that model had USB restrictions on it so you could technically just start Wipera1n from Normal mode. I am unsure if this works though, so don't get annoyed at me if it doesn’t work. I have never tested this method, it's just an idea.

Hope that you find Wipera1n useful.
Enjoy!
