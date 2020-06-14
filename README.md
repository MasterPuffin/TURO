<img width="200" alt="Logo" src="https://cdn.trueforce.ca/Logos/Logo_text_wide_small.png">


# TURO
Welcome to TURO - the Trueforce Unified Radio OS
## Goal
The goal of TURO is to create a single, unified list of frequencies and optimized settings for usage in HAM radios especially for users who are not that experienced with radio usage. It consists of two parts: A list of channels and corresponding frequencies which can be used with any programmable radio and images for the most used radios with optimized settings.
## Frequencies
TURO contains a .csv file with the above mentioned list of frequencies and channels. These file can be imported in radio programming software such as [CHIRP](https://chirp.danplanet.com)  to build individual images for radios not supported by TURO. It can be fund in the [releases tab](https://github.com/MasterPuffin/TURO/releases). Furthermore a printable PDF version is also available.
## Images
Images are radio specific and contain optimized settings such as disabling of transmitting sounds when pressing the emergency button and above mentioned frequencies. There are currently the following versions with support the listed radios:

 * **Version U** *(Baofeng F8HP Family)*
   * Baofeng GT-3TP
   * Baofeng UV-5R Plus 
   * Baofeng UV-5RTP 
   * Baofeng UV-5R EX
 * **Version G** *(Baofeng F8HP Family)*
   * Baofeng GT-3
 ## Interoperability
Versions with the same version code will guaranteed work together when selecting the same channel. Minor versions such as *v.1.**1**_U* and *v.1.**2**_U* will probably work as they only contain bugfixes.
The letter after the version number specifies the device version the image is. This means *v.1.2_**U*** and *v.1.2_**B*** for example, share the same settings and frequencies.
## Installation
To flash the image to your radio you need [CHIRP](https://chirp.danplanet.com) or a similar software and a programming cable.
 
 1. Download the corresponding image for your device [here](https://github.com/MasterPuffin/TURO/releases) (distinguishable by the letter at the end of the version number)
 2. Open CHIRP and go to File > Open and open the downloaded file
 3. Go to Device > Upload to device
 4. Select the right port (COM3 on Windows, USB0 on Linux), Vendor and Model
 5. Click OK and follow the onscreen instructions
## Read More
Check out this great [Baofeng Cheat Sheet](https://w7apk.com/baofeng), which contains all you must know for programming your radio in the field
