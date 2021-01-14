# Steps to restore an EFS backup in .img format

1. Download the Template-zip from [here](https://github.com/Simon1511/Rise-Q_stuff/archive/master.zip) and extract it.
2. Copy your EFS backup to your computer. The file is located in /data/media/0/EFS_Backup.img. Alternatively, look into your internal storage in any file manager.
3. The extracted zip file will contain a folder called "EFS-RestoreTool". Place the .img file in this folder, so you have "META-INF" and "EFS_Backup.img" in the same folder.
4. Now, the only thing you need to do is to make a zip out of it.
   - On Windows, select "META-INF" and "EFS_Backup.img", hit the right-click on your mouse and choose "Send to", then "Zip compressed folder". Copy the resulting .zip file to your phone and flash it.
   - On Linux, run `zip -r9 EFS-restoreTool_flashable.zip META-INF/ *.img` to create the zip. Copy it to your phone and flash it.
5. Your EFS backup will be restored and you will be rebooted to recovery to finish the process.
6. Reboot to system and you're finished!
