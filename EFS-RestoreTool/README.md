# Steps to restore an EFS backup in .img format

1. Download the Template-zip from [here](https://github.com/Simon1511/Rise-Q_stuff/archive/master.zip) and extract it.
2. Copy your EFS backup to your computer. The file is located in /data/media/0/EFS_Backup.img. Alternatively, look into your internal storage in any file manager.
3. The extracted zip file will contain a folder called "EFS-RestoreTool". Place the .img file in this folder, so you have "META-INF" and "EFS_Backup.img" in the same folder.
4. Now, the only thing you need to do is to make a zip out of it.
   - On Windows, make sure to have 7zip or WinRar installed. After that, select "META-INF" and "EFS_Backup.img" and zip them using one of these programs. Make sure to select the **lowest** compression level!
   - On Linux, open a terminal in the "EFS-RestoreTool"-directory and run `zip -r0 EFS-restoreTool_flashable.zip META-INF/ *.img` to create the zip.
5. Copy the finished .zip file to your phone's storage and flash it in recovery.
6. Your EFS backup will be restored and you will be rebooted to recovery again to finish the process.
7. At last, reboot to system and you're finished!

#### **WARNING**
- Dealing with EFS is always a dangerous part. I am **NOT** responsible for any damage that may be done to your device through flashing this!
- Do **NOT** restore EFS backups from other devices or device models as it will **damage** your device.
- Do **NOT** restore backups all the time. Flashing the RestoreTool once is **enough**!
- You are **NOT** allowed to re-upload this or publish it under your own name!
