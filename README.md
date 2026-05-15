# HTML Driven Tesla Dashcam Viewer
An extremely simple HTML Dashcam Viewer that has a simple installation set up, does not require any web server or software installation other than a functioning browser.

## Installation
Place the `index.html` file anywhere — inside the `TeslaCam` folder, alongside it, or on a different drive entirely. It uses blob URLs from the browser file picker, so its location doesn't matter.

## Running
Double check on `index.html` and open in any browser of your preference

The address bar should show `file://<PATH TO INDEX FILE>/index.html`

![UI](https://github.com/Lythinari/TeslaCamViewer/blob/main/instructions/main.png)


| Browser Name             | Windows         | Mac             |
| ------------------------ | --------------- | --------------- |
| Chrome                   |                 | 130.0.6723.117  |
| Edge                     | 130.0.2849.68   |                 |
| Firefox                  | 132.0.1         | 132.0.1         |
| Safari                   |                 | 17.5            |



## Notes
- Tested running `index.html` on macOS — you may need to close the browser before ejecting the USB.
- Select the `TeslaCam` folder (or a parent containing it) in the file picker. Selecting sub-folders like "Saved Clips" or "Sentry" directly will not work.
- Cameras not present in older clips (e.g. pillar cams) are automatically hidden.
