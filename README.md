# EZDrop
An application for automatic multithreaded import of photos and videos from Sony cameras sorted by date with progress tracking!
### An example of the work:
We have photos on the camera, the location of which:
+ `F:\DCIM\100MSDCF` - Here are **100 photos from June 20, 2023** and **50 photos from June 25, 2023**
+ `F:\DCIM\101MSDCF` - There are **30 photos from June 25, 2023** and **200 photos from June 30, 2023**

We also have video recordings, the location of which:
+ `F:\PRIVATE\M4ROOT\CLIP` - There are MP4 files and XML information about them, **10 videos from June 20, 2023** and **50 videos from June 25, 2023**

Then when we connect the memory card or camera to the computer and launch this application, this is what will happen:
1. You will see a console in which the progress of copying several items will be shown at the same time (indicating the name, speed, size of each file and the progress bar).
2. When the copying of the items is completed, you will see in the folder `H:\MEDIA` - `PHOTO` and `VIDEO` folders, inside which there will be folders with dates and everything will be arranged as indicated below.

In the `PHOTO` folder you will find **3 new folders**:
+ `23.06.20` - There will be 100 photos inside,
+ `23.06.25` - There will be 80 photos inside,
+ `23.06.30` - There will be 200 photos inside.
  
In the `VIDEO` folder you will find **2 new folders**:
+ `23.06.20` - There will be 10 videos inside,
+ `23.06.25` - There will be 50 videos inside.

You can choose a different date format when creating folders, for example `20.06.2023`

### Some more chips:
+ If any of the photos (or videos) you have already uploaded files before, then with the help of a smart, safety and fast algorithm, the files will not be copied again.
+ If the copying is interrupted for some reason right during the process, the broken files will be replaced when copying again.
+ If a file with the same name already exists in this folder with the date, but it is a different photo (or video), then a prefix will be added to this file.
  
More in the "Functions" section

# Install
Just run [EZDrop_v5.0.exe](https://github.com/mediahope/EZDrop/releases) _(or a newer version)_

# Update
After the program is finished, if there is a new version of the program, the program will offer to update it.<br />
It's quite simple, follow the instructions.<br />
**You can simply run the program "idle" to check for updates.**

# Functions
1. Multithreaded high-speed copying
2. Real-time tracking of progress bar
3. Tracking file size during copying
4. Real-time copy speed tracking
5. Add a prefix if another file with the same name already exists
6. If the copying is interrupted for some reason right during the process, the broken files will be replaced when copying again.
7. If any of the photos (or videos) you have already uploaded files before, then with the help of a smart, safety and fast algorithm, the files will not be copied again.
8. The distribution of files into folders according to the type of files (photo or video), as well as the date of shooting (with your time zone).
9. Choosing the date format when creating new folders
