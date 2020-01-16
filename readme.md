# Mat-Ro

Mat-Ro is an icon pack inspired by the design ethos of Microsoft's 'Metro' design,
and Google's 'Material' design - the name being a portmanteu of the two. 


### About Mat-Ro

When designing Mat-Ro, I aimed for a consistent style throughout - all main icons 
follow the same rounded-square shape, with transparency subtracting the shape where 
applicable. The material design palette has been used throughout to lend a consistent 
and vibrant colour scheme, whilst a soft shadow has been utilised to provide depth 
where applicable.

### Installation Instructions

#### Application Icons
To install, simply download the repository and unzip to a location on your machine. 
Then, find the application, folder or shortcut you wish to change the icon for and
right-click it, selecting 'Properties':

![Properties Dialog](https://github.com/Jimmytheconman/Matro/Readme_Media/change-icon-screenshot.png "Properties Dialog")

Then, click 'Change Icon', navigate to the unzipped Mat-Ro folder and choose the 
appropriate icon, and you are all set!

#### File Type Icons
For file types, I reccomend using a 3rd-party tool [File Types Manager](https://www.nirsoft.net/utils/file_types_manager.html).
This tool allows you to repoint file type icons for all recognised file types, and 
save your configuration. This is very handy as any applications that apply their 
own file type icons (Office, Adober Reader, etc.) will overwrite your changes 
when updating, so having a separate config you can just load in is easier than
updating them by hand every time!


#### System Icons
To change many of the Windows system icons (hard drives, printer, default 
folder/library icons), you need to edit two system files:

C:\Windows\SystemResources\imageres.dll.mun
C:\Windows\SystemResources\shell32.dll.mun

If you change the extension from .mun to .dll, you can edit the icons stored
within using a tool such as [Resource Hacker](http://www.angusj.com/resourcehacker/), save, and
then change the extension back to .mun.