# CTH-ProLink
Controls ProPresenter effortlessly through SCS 11 or any application that can run a Windows Batch file, allowing you to control your music and your slides all in the same place.

# Installation
Unless a computer system change has occurred recently, the necessary programs should already be installed and you may skip this section. However, if you have reason to believe this program is not already installed, [click here](INSTALL.md).

>On Windows, you can check if it is installed by seeing if there is a folder named __ProPresenter__ in the __Desktop__ folder.

>On MacOS, you can check if it is installed by seeing if __ProPresenter Remote__ is configured in the ProPresenter settings.

# Creating a ProPresenter Slideshow
Creating a ProPresenter slideshow is the same process regardless of whether you use this software. Once you have a slideshow created, continue to the [next section](#creating-projector-cues-in-scs-11)

# Creating Projector Cues in SCS 11
1. Open your SCS 11 show file and navigate to the SCS 11 "Editor" window.
1. In the toolbar, select "Cue". A dropdown will appear, where you will select "Run External Program"
1. Select the __...__ button next to the "File or Program to Run" textfield. Navigate to where the __ProLink.exe__ file is and select it. If installed properly, this should be located at C:\Users\{home dir}\Desktop\ProLink.exe
1. In "Command Line Parameters", simply type the slide number as it appears in ProPresenter.
1. Save the cue and test it--everything should work.

# If it doesn't work...
1. Make sure both computers are connected to the same network
1. Try running the set-up procedure again by double clicking on the __ProLink.exe__ file. See [INSTALL.md](INSTALL.md) for more information.
1. Try reinstalling __ProLink.exe__, and deleting the old one. __Make sure to put the new version in the same directory as the old version so the file path is the same. Otherwise, SCS will have the wrong file path--which no longer exists--and old cues will be broken.__

### Support Options
Still can't get it to work? I can help. Email Andrew Wilson at [andrewdwilson214@gmail.com](mailto:andrewdwilson214@gmail.com)
