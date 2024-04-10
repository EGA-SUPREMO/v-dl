# Yet Another Video Downloader (YAVD)

YAVD is a bash script designed to simplify the process of downloading videos(by using as few keystrokes as possible!) from YouTube at various quality levels along with additional options such as downloading subtitles, audio-only, etc. It uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) under the hood

## Usage

```bash
./.dv <quality> <link> [localization] [extra]
```

- `quality`: Maximum quality of the video (e.g., 240, 360, etc.).
- `link`: Link of the video, YouTube video ID, or full YouTube video URL.
- `localization`: Localization of the downloaded file. Defaults to `~/Downloads`.
- `extra`: Additional options (see below).

## Extra Options

- `wa`: Downloads the video with the worst audio available.
- `nv`: Downloads only audio (no video).
- `na`: Downloads only video (no audio).
- `sub`: Downloads subtitles in English and Spanish.
- `mp4`: Downloads video in MP4 format.

## Aliases

YAVD provides some convenient aliases:

- `dv2`, `dv3`, `dv4`, `dv7`, `dv10`: Download videos at specific quality levels (240p, 360p, 480p, 720p, 1080p respectively).
- `dv2m`, `dv3m`, `dv4m`, `dv7m`, `dv10m`: Download videos at specific quality levels to the Music directory.
- `dv2v`, `dv3v`, `dv4v`, `dv7v`, `dv10v`: Download videos at specific quality levels to the Videos directory.

## Additional Notes

- The order of arguments cannot be changed.
- Feel free to contribute by submitting pull requests on GitHub.

## License

This project is licensed under the [GNU General Public License (GPL) version 3](LICENSE)
