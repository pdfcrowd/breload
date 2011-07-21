# breload

Tired of switching between your editor and the browser and hitting the
refresh button?

breload is a utility which automatically refreshes the browser whenewer
you save a file in your project folder.

## Usage

1. run `breload ~/code/myproject/`
2. click the browser window

Now you can edit your project files and enjoy automatic browser refresh.
        
Run `breload -h` to see available options.

## Dependencies

breload requires `xwininfo`, `xdotool`, and `inotifywait`.

If you are on Debian/Ubuntu, just run:

    $ sudo apt-get install inotify-tools xdotool x11-utils
       
Supported OSes: Linux
    
