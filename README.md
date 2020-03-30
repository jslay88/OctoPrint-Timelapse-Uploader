# OctoPrint-Timelapse-Uploader

Automatically upload rendered timelapses to various cloud storage services. Can also delete after upload to save space on the Raspberry Pi
SD Card.

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/jslay88/OctoPrint-Timelapse-Uploader/archive/master.zip

## Configuration

### Dropbox
You must provide an API Token to be able to upload rendered timelapses to Dropbox.
To do this, [create a Dropbox App](https://www.dropbox.com/developers/apps/create)
select `Dropbox API` -> `App Folder` -> Provide Folder Name.
Once the app is created, scroll down to the `OAuth 2` section, and click `Generate Token`. Paste the token into the
settings pane.
