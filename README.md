# BeatBot - audio streaming Discord bot

## Introduction
Beatbot is a self-hostable, single-server, home-made audio streaming bot that can
take input from YouTube, SoundCloud and virtually every platform `youtube-dl` supports.

Some CTF tools are also include

## Getting started

```shell
git clone https://github.com/Pluppo/BeatBot_V2 beatbot
cd beatbot
pip install -r requirement.txt
edit .env.sample with your creds and save it as .env
./beatbot.py
```


## @TODO
- [ ] Fix vocal channel management
  - [ ] Quit all vocal channels when exiting
  - [ ] Auto-select a vocal channel when instigator isn't connected to any
  - [ ] Stabilize hard-reboot
- [ ] Rebase Docker image on `python:3.7-alpine`
- [ ] Finish reaction-based control
  - [ ] Implement button-like reactions
  - [ ] Improve embed filter for initial reaction (slash-command ?)
- [ ] Implement slash-command controls
