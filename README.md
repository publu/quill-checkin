JAFRS Check-In & Label Printing
==============
An easy to deploy check-in and label printing web application for JAFRS like registration systems.

## Deploy
This is a static web application with bundled dependencies.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https://github.com/techx/jafrs-checkin)
#### or Local Testing
```
python -m SimpleHTTPServer
```

## Configure

Use the `js/configure.js` file to set the `API_ROOT` and `APP_NAME` to work with your database.

## Usage

* Install the printer driver for [Windows][dymo-win] or [Mac][dymo-mac]
* Start the web application and log in.
* Type in the name/email/team of the person you're checking in.
* Click the "Check-In & Print" button.
* A new tab will open, hit `Ctrl+P`
* Set these settings in the print dialog (you won't need to do this for subsequent prints)

![Image](http://i.imgur.com/WuCxJb2.png)

* Hit Print!

## Troubleshooting

#### Heroku doesn't deploy! Wot do?
This is a private repository. Make sure your heroku application is associated with a github account that has access to this.

[dymo-win]: http://download.dymo.com/dymo/Software/Win/DLS8Setup.8.5.1.exe
[dymo-mac]: http://download.dymo.com/dymo/Software/Mac/DLS8Setup.8.5.2.dmg
