**__This latest version uses RIFE to ensure your interpolated videos are smooth when resampled on the relevant video editing program to 60 FPS.__**

# SYSTEM REQUIREMENTS
CPU: Minimum 6 cores (Ryzen 5/Intel i5 and above, best 8 cores)
GPU: Minimum 4GB VRAM (best 8GB VRAM)
RAM: 16GB (best 32GB RAM if you would like to do interpolation to higher framerate such as 1000, 2000 etc.)

# BEST CODEC TO USE

H264 is the most preferred codec to use. X264/X265 are known to be slow at processing higher framerate videos and they are not recommended in most cases due to the fact that it uses processor power. For the best experience, use a higher-end GPU like an GTX 1070/RX 5700 XT and above.

If you are storage concerned, use H265 as it gives a smaller file size.

Maximum resolution for each codec:
H264/X264: 4K
H265/X265: 8K

# DISCLAIMER

This program may have bugs. If you do encounter any, report it on the issues in GitHub.

Support for Mac and Linux coming soon. (Or maybe not)

Please note that this program is only available to run on Windows as of now.

# DOWNLOAD

All you have to do is to download [Frame_Interpolation.zip](https://github.com/KrisDreemurrYT/Frame_Interpolation/releases/download/Frame_Interpolation/Frame_Interpolation.zip) on the releases section. Extract the zip file into your C: or D: Drive or otherwise there will be issues if you don't.

If you are using a D: drive, please change the python codes via notepad from C: to D:, along with the run.bat file too.

**DO NOT CHANGE ANYTHING IN THE CODE OTHERWISE IT WILL NOT WORK AS INTENDED!**

# BEFORE YOU RUN THE PROGRAM
Select your input video from the directory you chose, then the output directory where you want the video's output to be at. Select the target FPS between 1 to 1,000,000 FPS, select your encoder (H264 by default), X264, H265 or X265 with main10 (only for H265 and X265.)

**DO NOT CHANGE ANYTHING ON THE PYTHON CODE OR THE .BAT FILE!**

# WHEN PROGRAM IS RUNNING THE FRAME INTERPOLATION
DO NOT add more stress to your GPU by playing video games, watching videos (especially at 2k, 4k or 8k) etc. Let it do it's thing. Otherwise you may run into issues.

Frame skips are NORMAL as RIFE may not accurately get all of the frame of the interpolated images right. (May usually happen if you go above 240fps). Try not to go too high on FPS because your storage may become full as more FPS you decide to put in will take more storage space.

If ffmpeg.exe / rife-ncnn-vulkan.exe are opened in command prompt, DO NOT CLOSE THEM. It is doing it's job to get your interpolated video done within hours or days. If you do, the process will be aborted!

# WHEN PROGRAM HAS FINISHED
You can now find the outputted video on the output directory folder you have selected. Make sure to resample it to 60fps via Vegas/Premiere Pro/Da Vinci as Windows won't run higher framerate videos properly.

And that's it! You're done!

Tutorials on how to frame blend/sampling:
[DaVinci](https://www.youtube.com/watch?v=B_4R6m13w6k) /
[Premiere Pro](https://youtu.be/EQl82Hxn-H4?si=IELH-VBDDdt7rNCA&t=425) /
[Vegas](https://www.vegascreativesoftware.info/download/file/mediacenter/l2adhc58saef/04WnMMI4o4DGXnL03XlG0InRoX4RM0DR) (**Right click the video, select switches, choose either Use Project Resample Mode or Force Resample**)
