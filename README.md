# Puppetcam

Example to export chrome tab as a video


1. Exported videos are stored in Downloads folder
2. Specify bitrate to control quality of the exported video by adjusting `videoBitsPerSecond` property in `background.js`


### Dependencies

1. xvfb
2. npm modules listed in package.json

### Usage

```sh
npm install
node export.js http://tobiasahlin.com/spinkit/ spinner.webm
```


Thanks to [@cretz](https://github.com/cretz) for helping with automatic tab selection and avoiding the permission dialog

#### Motivation

Was looking for a method to export a video of user actions rendered using our custom player used in [uxlens](https://uxlens.com). Export has to happen on a server in an automated fashion and hence the usage of xvfb.

#### Sample video
[![Puppetcam](https://img.youtube.com/vi/f7Vdd0ExWiY/0.jpg)](https://www.youtube.com/watch?v=f7Vdd0ExWiY "Puppetcam")
