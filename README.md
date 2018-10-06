# Little Bird Arduino Boards

This repository contains support for the following Little Bird Arduino-compatible development boards.

#### AVR Boards
* [Shakey](#)



### Installation Instructions

To add board support for our products, start Arduino and open the Preferences window (**File** > **Preferences**). Now copy and paste the following URL into the 'Additional Boards Manager URLs' input field:

	https://raw.githubusercontent.com/littlebirdelectronics/Arduino_Boards/master/IDE_Board_Manager/package_little_bird_index.json

<!-- ![Location of Additional Boards Manager URL input field](prefs-arrow.png) -->

If there is already an URL from another manufacturer in that field, click the button at the right end of the field. This will open an editing window allowing you to paste the above URL onto a new line.

### AVR Instructions

Open the Boards Manager window by selecting **Tools** > **Board**, scroll to the top of the board list, and select **Boards Manager**.

<!-- ![Boards Manager Menu](manager-menu.png) -->

If you type "Little Bird" (without quotes) into the "filter your search" field, you will see options to install Little Bird's AVR and ESP board files. Click in the desired box, and click the "Install" button that appears. Once installed, the boards will appear at the bottom of the board list.

<!-- ![Little Bird Boards](Little Birdboards.png) -->


### Notes

* Some boards such as the Arduino Pro and Pro Mini come in more than one flavor.  For these **you must select the correct processor** in the 'Tools' menu.
* Information on compiling and programming the bootloaders can be found in the bootloaders directory.

**Have fun!**<br>
\-Your friends at Little Bird
