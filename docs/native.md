# Native installation

## Requirements

* Jellyfin 10.8.0
* Compiled [jellyfin-web](https://github.com/Bobby306/jellyfin-web/tree/intros) interface with intro skip button

## Instructions

1. Download and extract the latest modified web interface from [GitHub releases](https://github.com/Bobby306/intro-skipper/releases)
    1. Click the most recent version tag
    2. Download the included .tar.gz.zip file
2. Make a backup of the original web interface
    1. On Linux, the web interface is located in `/usr/share/jellyfin/web/`
    2. On Windows, the web interface is located in `C:\Program Files\Jellyfin\Server\jellyfin-web`
3. Copy the contents of the `dist` folder you downloaded in step 1 into Jellyfin's web folder
4. Follow the plugin installation steps from the readme
