![img](images/important_fixes/i-f+ws.png)

This section would ensure that you are all quickly set up to have an decent playable experience. After following the steps in this section, you should be good enough to properly play the game from start to finish without facing any technical issues.

## The FF13 fix
Most of the technical problems can be solved with this fan made fix made by rebtd7. thank you so much for this fix if you are reading this guide rebtd7.

- Download the latest version of the fix from their github releases page:
<br>https://github.com/rebtd7/FF13Fix/releases

- After the file is downloaded right-click on the file and extract it with WinRAR software's Extract Here option.
  
<br>You can see the below image for reference:
![img](images/important_fixes/ff13fix/fix_1-2.png)

<br>If you are using 7Zip software then right click, select 7Zip and the Extract Here option.
<br>You can once again see the image for reference:
![img](images/important_fixes/ff13fix/fix_1.png)

<br>

- Go into the extracted FF13Fix_164 folder, and select all of the files inside it. right click and select Copy.
  ![img](images/important_fixes/ff13fix/fix_2.png)

<br>

We will now have to copy these files to the location where the game's main executable file is present. the location is give below:
<br>``steamapps\common\FINAL FANTASY XIII\ white_data\ prog\ win\ bin``

To get to this location first select this game title on your Steam library, right click and select Properties. then in the new window go to **LOCAL FILES** and select the *Browse...* option.

This should open the root directory from where you can get to the **bin** sub folder where the main executable file is present.

You can now follow the screenshots linked below to get to the bin folder and paste the files there.

- Open the **white_data** folder
![img](images/important_fixes/ff13fix/fix_3.png)

- Open the **prog** folder
![img](images/important_fixes/ff13fix/fix_4.png)

- Open the **win** folder
![img](images/important_fixes/ff13fix/fix_5.png)

- Open the **bin** folder
![img](images/important_fixes/ff13fix/fix_6.png)

- Right click and select the Paste option here. that should copy the fix's files in here and it should look like this after copying the files:
![img](images/important_fixes/ff13fix/fix_7.png)

And that's it.

If you want to turn off vibration, decrease the vibration strength (max 2.0) or cap your frame limit to 30 or 60, then you can do all of this by editing the values in the FF13Fix.ini file that you copied here.
There's information provided in the ini file itself on what values to edit and what to change, so please follow that correctly if you want to make any changes.

If you are using an AMD RDNA GPU, you can set this **DiscardUIVertexBuffer** option to true and see if it improves the performance a bit.
Be warned that this particular option is still experimental and if its causing any graphical issues in game, then set it back to **false**.
