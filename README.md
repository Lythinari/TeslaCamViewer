# HTML Driven Tesla Dashcam Viewer
An extremely simple HTML Dashcam Viewer

The `index.html` file should be able to run straight in a browser. No server support has been coded into this file.

Copy the `TeslaCam` folder from your USB to the same directory as `index.html`
```
Root Folder
|- index.html
|- TeslaCam(USB Drive Top Level Folder)
    |- Saved Clips
    |- Sentry Videos
    |- ...
```
Open the `index.html` file. This should open it in a browser window and you'll be greeted with a very plain looking HTML page with a textarea at the bottom.


Run the following *nix command to get a list of files 
```
find ./TeslaCam -print | sort -n | grep back.mp4
```
Or the windows command
```
dir /a-D /S /B /ON *-back.mp4
```
The output file should look like the following(It should only be rear camera videos in the list);
```
./TeslaCam/SavedClips/2022-04-11_19-23-07/2022-04-11_19-12-27-back.mp4
./TeslaCam/SavedClips/2022-04-11_19-23-07/2022-04-11_19-13-27-back.mp4
./TeslaCam/SavedClips/2022-04-11_19-23-07/2022-04-11_19-14-27-back.mp4
```

Copy the contents into the `textarea` in the webpage and push the `Set Video` button.
This will load the videos and play them accordingly.
