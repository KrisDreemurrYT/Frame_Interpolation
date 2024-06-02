# SYSTEM REQUIREMENTS
CPU: Minimum 6 cores (Ryzen 5/Intel i5 and above, best 8 cores)
GPU: Minimum 4GB VRAM (best 8GB VRAM)
RAM: 16GB (best 32GB RAM if you would like to do interpolation to higher framerate such as 1000, 2000 etc.)

# BEST CODEC TO USE

H264 is the most preferred codec to use. X264/X265 are known to be slow at processing higher framerate videos and they are not recommended in most cases. For the best experience, use a higher-end GPU like an GTX 1070/RX 5700 XT and above.

Maximum resolution for each codec:
H264/X264: 4K,
H265/X265: 8K

# DISCLAIMER

This program may have bugs. If you do encounter any, report it on the issues in GitHub.

There is no support for Mac or Linux as this application is only for Windows.

# DOWNLOAD

All you have to do is to download [Frame_Interpolation.zip](https://github.com/KrisDreemurrYT/Frame_Interpolation/releases/download/Frame_Interpolation/Frame_Interpolation.zip) on the releases section. Extract the zip file into your C: or D: Drive or otherwise there will be issues if you don't.

If you are using a D: drive, please change the python codes via notepad from C: to D:, along with the run.bat file too.

**DO NOT CHANGE ANYTHING IN THE CODE OTHERWISE IT WILL NOT WORK AS INTENDED!**

# BEFORE YOU RUN THE PROGRAM
Put your input file ONLY on the ffmpeg/bin folder. Make sure that it is renamed to input.mp4, otherwise the program can't run.

Once that is done, right click on the encoder (usually H264 is best), edit it with notepad, and change 60 to any framerate you like.

Command to run (EXAMPLE): python increase_fps_h264.py "C:\Frame_Interpolation\ffmpeg\bin\input.mp4" "C:\Frame_Interpolation\ffmpeg\bin\output.mp4" 60 nvidia (Please note that it is already included in the run.bat folder. All you have to do is to edit the .bat file and change the FPS to whatever you want and specify the encoder on this list below.)
Encoder to use (nvidia, amd, nvidia_h265, amd_h265, nvidia_h265_main10, amd_h265_main10, x264, x265, x265_main10)

**DO NOT CHANGE ANYTHING ON THE PYTHON CODE OR THE .BAT FILE!**

# WHEN PROGRAM IS RUNNING THE FRAME INTERPOLATION
DO NOT add more stress to your GPU by playing video games, watching videos etc. Let it do it's thing. Otherwise you may run into issues.

# WHEN PROGRAM HAS FINISHED
You can now find the outputted video on the ffmpeg/bin folder. Make sure to resample it to 60fps via Vegas/Premiere Pro/Da Vinci as Windows won't run higher framerate videos properly.

And that's it! You're done!

Tutorials on how to frame blend/sampling:
[DaVinci](https://www.youtube.com/watch?v=B_4R6m13w6k) /
[Premiere Pro](https://youtu.be/EQl82Hxn-H4?si=IELH-VBDDdt7rNCA&t=425) /
[Vegas](https://www.vegascreativesoftware.info/download/file/mediacenter/l2adhc58saef/04WnMMI4o4DGXnL03XlG0InRoX4RM0DR) (**Right click the video, select switches, choose either Use Project Resample Mode or Force Resample**)
