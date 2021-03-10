# Raspotify

Spotify connect server, see [the github page](https://github.com/dtcooper/raspotify) for more info.
Isn't built with pulseaudio, if there is any interest I could probably add that, let me know.

Configurable through the supervisor interface. Username and password are optional, if you just want to cast locally from your phone you can leave them blank.

Works great with Forked-DAAPD through a pipe, just use 
```yaml
backend: pipe
device: /share/forked-daapd/music/Raspotify
```
in the add-on configuration.

[Read the full add-on documentation](raspotify/DOCS.md).

