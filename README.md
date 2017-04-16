Quill Check-In & Label Printing
==============
An easy to deploy check-in and label printing web application for [Quill](https://github.com/techx/quill).

## Deploy
This is a static web application with bundled dependencies.

#### Host on any static server like an S3 bucket
#### or Locally
```
python -m SimpleHTTPServer
```

## Configure

Use the `js/configure.js` file to set the `API_ROOT` and `APP_NAME` to work with your database.

Change the `img/footer.png` to change the label image that will be printer. The file must be exactly `520x299`.

## Usage

* Install the printer driver for [Windows][dymo-win] or [Mac][dymo-mac]
* Start the web application and log in.
* Type in the name/email/team of the person you're checking in.
* Click the "Check-In & Print" button.
* A new tab will open, hit `Ctrl+P`
* Set these settings in the print dialog (you won't need to do this for subsequent prints)

![Image](http://i.imgur.com/WuCxJb2.png)

* Hit Print!

[dymo-win]: http://download.dymo.com/dymo/Software/Win/DLS8Setup.8.5.1.exe
[dymo-mac]: http://download.dymo.com/dymo/Software/Mac/DLS8Setup.8.5.2.dmg
