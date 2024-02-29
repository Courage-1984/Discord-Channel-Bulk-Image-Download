# Discord-Channel-Bulk-Image-Download
How to download all of a Discord Channel's Images

### This is a guide on how to download all of the images in a Discord channel that your Discord account has access to/is a part of.

# Steps:

1. Head over to:
```sh
  https://github.com/hydrusnetwork/hydrus
```


then on the right click on the latest Version just below the "**Releases**" heading.

2. Scroll to the bottom until you reach the "**Assets**" heading and
3. Download the appropriate install file for your OS.
4. Install the software.
5. After installation is completed, run the "**hydrus client**".
6. Save the following image:

![discord channels 2022-01-13](https://github.com/Courage-1984/Discord-Channel-Bulk-Image-Download/assets/18268669/f128d5e1-9ac4-4349-9f5f-a84fee8d0c8a)

7. In the "**hydrus client**" click: `network -> downloaders -> import downloaders` through the toolbar.
8. A little image-panel will appear onto which you can drag-and-drop the image you saved in step 6.
9. Click next/ok for the next two windows that pop up, then after it says it was successful you can close the little image-panel.

10. You need an authorisation token to access what your Discord account can access.
11. Head over to:

```sh
  https://discord.com/
```

on your browser and log in to your Discord account.

12. Press `Ctrl+Shift+I`
13. Navigate to the **Network** tab and then click on the **XHR** button.
14. In the table look at the **File** column and look for and click on either the line named "**library**" OR the line named "**country-code**". Refresh if you don't see anything.
15. In the right section, under headers, look for the authorisation line.
16. Copy the text next to authorisation.
17. In Hydrus, navigate to the `network -> data -> manage http headers` through the toolbar.
18. Replace the "PUT TOKEN HERE" with the token you copied in step 16.
19. Click "Apply" twice.

20. Now head back over to Discord, for the next steps you can either use the browser version or the app.
21. Make sure **Developer Mode** is switched on in your Discord settings and head over to the channel which you wish to bulk download from.
22. Right Click Channel Name > Click **Copy Channel ID**.

23. If you struggle with step 21 & 22 watch the following:

https://github.com/Courage-1984/Discord-Channel-Bulk-Image-Download/assets/18268669/749e7846-5d3f-405d-b948-f952f408bc26

[VIDEO SOURCE](https://youtu.be/NLWtSHWKbAI?si=mZcBc3kOLAiEXQb1)

24. Next, follow the steps in the following .gif:

![2-29-2024 (16-12-29)](https://github.com/Courage-1984/Discord-Channel-Bulk-Image-Download/assets/18268669/ef27ac21-e7ba-403d-9cdc-c737f6d62e83)

25. First Update the value of: "stop after this many files:" to your preference.
26. Now paste the **Channel ID** you copied in step 22 into the input which says: "enter channel numeric id"
27. Press **Enter** and it should automatically start downloading all the images from your chosen channel

# NEXT Steps:

I am not yet too sure how Hydrus works (the ins & outs) but here is what I do after all the images from a channel has been downloaded:

1. Click on a image, and press: "Ctrl + A"
2. Create a folder somewhere where you would like to store those images.
3. Drag 'n Drop the selected images into your chosen folder and commence copying them all to that folder.
4. After the copy has completed, make sure all the images are selected and press "Delete" > "Apply".
5. Press the "Esc" button.
6. Select again only one image and then press: "Ctrl + A"
7. Now again make sure all the images are selected and press "Delete" > "Apply".
8. Next Delete the selected item in the following image > click "yes":

![2024-02-29 17 03 11 main - hydrus client 564](https://github.com/Courage-1984/Discord-Channel-Bulk-Image-Download/assets/18268669/d44e2679-7a67-4724-a618-864a09ac20ff)

10. Give the image deletion process some time as it may take a while to delete all of them espescially if you downloaded a big gallery.

TA-DA! **ENJOY**

***

## SOME ADDITIONAL RESOURCES YOU SHOULD CHECK OUT:

- [Hydrus Network (Client and Server) - Github](https://github.com/hydrusnetwork/hydrus)

- [hydrus network - client and server - Website](https://hydrusnetwork.github.io/hydrus/)

- [How to Hydrus - YouTube Playlist](https://youtube.com/playlist?list=PLD4r6M35XTXNb6vse1urIhJPCjsZL9mru&si=q3smaRHSo7U2Aqyn)

- [adding new downloaders](https://hydrusnetwork.github.io/hydrus/adding_new_downloaders.html)

- [Discord Downloader](https://github.com/CuddleBear92/Hydrus-Presets-and-Scripts/tree/master/Downloaders/Discord)

- [Hydrus Presets, Scripts & Issue Tracker](https://github.com/CuddleBear92/Hydrus-Presets-and-Scripts)

