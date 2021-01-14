#Rise-Q

###What is this?
This is a collection of "extensions" for Rise-Q for Galaxy A5 and A7 2017.
For now, it only contains a template zip to restore an EFS backup created during installation of Rise-Q.

###How do I use this?
With a few short steps, you will create your own flashable zip that will restore your EFS backup.
Follow these steps:

1. Download the Template-zip from [here]() and extract it.
2. Copy your EFS backup to your computer. The file is located in /data/media/0/EFS_Backup.img. Alternatively, look into your internal storage in any file manager.
3. The extracted zip file will contain a folder called "EFS-RestoreTool". Place the .img file in this folder, so you have "META-INF" and "EFS_Backup.img" in the same folder.
4. Now, the only thing you need to do is to make a zip out of it.
   - On Windows, select "META-INF" and "EFS_Backup.img", hit the right-click on your mouse and choose "Send to", then "Zip compressed folder". Copy the resulting .zip file to your phone and flash it.
   - On Linux, run `zip -r9 EFS-restoreTool_flashable.zip META-INF/ *.img` to create the zip. Copy it to your phone and flash it.
5. Your EFS backup will be restored and you will be rebooted to recovery to finish the process.
6. Reboot to system and you're finished!

![Exynos 7880](https://forum.xda-developers.com/proxy.php?image=https%3A%2F%2Fi.ibb.co%2FwsqPkyw%2Frise-Q.png&hash=7f5f1020afda12cbfed68669643c3f43)
