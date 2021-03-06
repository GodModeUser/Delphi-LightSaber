# Delphi-LightSaber

The LightSaber contains lots and lots of "goodie" functions - functions that make your life easier, and visual controls. 
More than 15 years of development have been put in this library. 
The library also wants to be a lightweight replacement for the mammoth Delphi Jedi library.

Note: This library is freeware (see included copyright notice) but it cannot be used in the invading Russia!  

**The library is split into 7 sub-libraries (repositories)**

•	Core - The Core sub-library provides basic functionality for all other sub-libraries.  
•	Visual Log - A simple but effective visual log control/library. The programmer can send messages to a log window from anywhere in his code.  The Log window can be set to automatically pop up when an error message is sent to it. Depending on the chosen verbosity level of the log (see the Verbosity property) low-level messages (like verbose/debug messages) are shown or not.  
•	Common – Lots and lots of useful functions   
•	Proteus - Proteus is a licensing system. It helps you to convert your program to a commercial program that you can deliver as a trial or sell to your customers. You only need to call one line of code in your program.  
•	Internet - Internet and HTML related functions  
•	Graphics - Functions for opening graphic files (BMP, animated GIFs, PNG, Jpeg2000, etc.), converting between file formats, resizing images while preserving sharpness, video files, alpha transparency, etc.  
•	Visual controls - More than 70 visual controls that you can drag and drop on your form at design time.  
 
Note:   
Not all sub-libraries listed above are yet available on GitHub.   
I still need time to properly curate and comment on my code. I hope I can publish one sub-library every six months.  

**Filename convention**  
The following filename convention is used in LightSaber libraries:  
•	'c' -> The first c stands for 'cubic'  
•	'c' -> The second 'c' stands for 'core'. All files I posted in library/repository are 'core' because other libraries will be based on them.  
•	'v'-> visual component  
•	'Graph'-> graphic library  
• 'l' -> Log library
• 'i' -> Internet library
• 'm' -> Common library

Example:  
•	ccBinary.pas (Cubic core library)  
•	cvMemo.pas (Cubic visual component)  
•	cGraphFX.pas (Cubic graphic library)  
•	clVisLog.pas (Cubic log library)  
•	ciEmailSender.pas (Cubic internet library)  
•	cmPowerUtils.pas (Cubic common library)  

**How to download LightSaber?**  
There is no code in this repository.  
As explaind above, Delphi LightSaber is split in 7 sub-libraries.   
Go directly to my profile's root and there you will find the repositories (available at this point).   

Each library depends on the previous one, in the order specified above.  
LightSaber Core does not depend on any other library.   
Therefore, if you want the LightSaber Log repository, you need to download also the LightSaber Core repository.
Unzip all repositories in a single folder.
