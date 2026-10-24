# toolbox

[![License: MIT](https://img.shields.io/github/license/aerodiduch/toolbox)](LICENSE) ![macOS](https://img.shields.io/badge/macOS-555555?logo=apple&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-mods-D97757)

[Español](README.es.md)

I spend my day on a MacBook, mostly inside Claude Code in iTerm2. The tools on this list came out of things that bugged me in that day-to-day, and I use every one of them, every day. Each one has its own repo with the code and the install steps; the list grows every time I add one.

## LidMute

I'd close the MacBook, go to bed and remember I'd left the sound on. I had to get up, open it and mute it. LidMute mutes it when you close the lid and doesn't unmute it when you open it. It listens to the lid, not to sleep, so it works even when Amphetamine keeps the Mac awake.

- Mutes the output in use: the speakers, AirPods, a USB interface.
- Turns on and off from an icon in the menu bar.
- If you plug in a monitor with the lid closed, it doesn't mute you again.

```sh
git clone https://github.com/aerodiduch/lid-mute.git && bash lid-mute/install.sh
```

macOS, Swift with no dependencies. [Repo and details](https://github.com/aerodiduch/lid-mute).

## Image Links

![Claude Code with three images as chips above the prompt and one open next to the pointer](https://github.com/aerodiduch/claude-image-links/raw/main/docs/cover.jpg)

Claude sends me screenshots all the time, of a screen it just built or of a test run, and they stayed as file paths I had to open by hand. This mod turns them into chips above the prompt: hover one and the picture shows next to the pointer, and a click opens it in Preview.

- Picks up the images Claude sends you and the paths it writes in its answer.
- The preview window never takes the focus: you keep typing in the terminal.
- They clear when you send your next prompt.

```sh
claude plugin install image-links --marketplace aerodiduch/claude-image-links
```

A Claude Code mod; the preview works on macOS. It needs the fullscreen interface (`"tui": "fullscreen"`). [Repo and details](https://github.com/aerodiduch/claude-image-links).

## License

MIT. Each tool has its own license in its repo.
