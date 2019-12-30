# Plex Tube

Plex Tube provides a simple way to download YouTube videos onto a Plex server.
It takes the form of an iOS app and a server daemon (written in Crystal).
Users will find a video on YouTube they'd like to download, share its link to the Plex Tube app, then Plex Tube will forward that link to the daemon. 
The Plex Tube daemon will use youtube-dl and attempt to download the video, saving it to a previously specified directory.

Roadmap:
- server daemon to provide a simple API for youtube-dl
- iOS app that provides a way to specify a server
- iOS app that presents a text field and a submit button that calls the API
- iOS app that works as a share sheet
- the ability to submit a custom name for the file
- the ability to list the previously submitted files (client-side)
- the ability to list the already existing files (api change needed)
