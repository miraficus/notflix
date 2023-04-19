<h1 align="center">NOTFLIX</h1>
<p align="center">f@#k netflix use notflix a tool which search magnet links and stream it with peerflix</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>

> Watch this video to understand - [bugswriter's notflix](https://youtu.be/FbE19_omaWY)

### How does this work?

This is a shell script. It scapes 1337x or Sktorrent and gets the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Usage

```sh
notflix moviename
```

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh

git clone https://github.com/miraficus/notflix.git
mv notflix ~/bin/notflix
mv mpv ~/bin/mpv
chmod +x ~/bin/notflix
chmod +x ~/bin/mpv
```
- To update, just do `git fetch`, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f ~/bin/notflix.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

