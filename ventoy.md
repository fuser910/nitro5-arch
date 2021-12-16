## Making Bootable Multiboot USB with Ventoy
1. Download [latest Ventoy release](https://github.com/ventoy/Ventoy/releases) based on your current OS and run it.
   - Windows: Download ventoy-X.X.XX-windows.zip , extract folder and run Ventoy2Disk.exe
   - Linux: Download ventoy-X.X.XX-linux.tar.gz , extract folder and run VentoyGUI.x86_64 (if its not launchable, just run it in terminal, otherwise open README for other method of running ventoy
2. ⚠️**Make Sure to backup your USB drive data somewhere else as it will be wipe clean for later steps**⚠️
3. Plug in your USB drive to the pc. (Note that you can basically use any kind of external storage for this such as external HDD) and click on green circle icon ![image](https://user-images.githubusercontent.com/44937271/146333813-53be6307-3bd6-41fb-af17-2d6b57b768a0.png) to refresh the drive list. 
4. Select your USB drive properly from the Drive list so that you do not accidently format the other drive connected to the PC. You can unplug refresh and plug and refresh to confirm the drive.
5. For some reason, some newer laptop/pc hates MBR UEFI boot therefore you need to change the partition style to GPT through "Option > Partition Style > GPT". That is unless your machine is too old and do not support UEFI then its fine to skip this step.
   - ![image](https://user-images.githubusercontent.com/44937271/146333685-9db32186-08c2-46b4-af87-da5012924853.png)
7. Click on Install and wait until it finish formatting your USB drive.
8. After it finish installing, a folder named Ventoy will be created. Move your desired iso into that folder.
