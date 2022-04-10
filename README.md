# youtubedl-material-stack

[YoutubeDL-Material](https://github.com/Tzahi12345/YoutubeDL-Material) stack used for self-hosting a youtube-dl Web UI. Setup towards using Traefik as reverse proxy and JSON file as a database.

Required ENV vars with their description:

| Var                  | Description                               |
| -------------------- | ----------------------------------------- |
| YTDLM_HOSTNAME       | Hostname of the YoutubeDL-Material UI     |
| AUDIO_VOLUME         | Mounted volume for audio downloads        |
| SUBSCRIPTIONS_VOLUME | Mounted volume for playlist subscriptions |
| VIDEO_VOLUME         | Mounted volume for video downloads        |
