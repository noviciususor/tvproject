<img width="2172" height="724" alt="logo" src="https://github.com/user-attachments/assets/3ebe24c0-f7ed-4653-b8b5-675bab565bb1" />


# IPTV Project

Greek and Russian IPTV playlists maintained by **noviciususor** for IPTV applications, Android TV and media players that support the M3U format.

> GitHub stores only the M3U playlist files. It does not host, relay or retransmit the live video streams.

## Playlists

| Playlist | File | Channels | Categories |
|---|---|---:|---:|
| Greek IPTV | `greekiptvplaylist.m3u` | 44 | 9 |
| Russian IPTV | `russianiptvplaylist.m3u` | 209 | 12 |

### Greek IPTV

```text
https://raw.githubusercontent.com/noviciususor/tvproject/main/greekiptvplaylist.m3u
```

### Russian IPTV

```text
https://raw.githubusercontent.com/noviciususor/tvproject/main/russianiptvplaylist.m3u
```

## Installation

### Android IPTV application

1. Open the IPTV application.
2. Select **Add playlist** or **Add URL**.
3. Paste one of the Raw playlist URLs shown above.
4. Save the playlist and refresh the channel list.

If an older version remains cached, remove the playlist, force-stop the application, clear its cache and add the URL again. A cache-busting value can also be appended to the URL, for example:

```text
?v=20261004
```

### VLC Media Player

1. Open **Media → Open Network Stream**.
2. Paste the Raw playlist URL.
3. Select **Play**.

## Playlist maintenance

- Channel links are collected and maintained through public GitHub IPTV repositories.
- Streams are checked before being added whenever possible.
- Time-zone variants are identified separately when known.
- Broken or unstable streams may be replaced during future updates.

Live-stream availability is controlled by the individual stream providers and can change without notice. A channel working today is not guaranteed to remain available permanently.

## Disclaimer

This repository does not host any television streams or copyrighted video content. It contains M3U indexes that reference publicly accessible third-party streams. All channel names, logos and content belong to their respective owners. If a rights holder requests the removal of a link, it will be reviewed and removed where appropriate.

## Author

Created and maintained by [noviciususor](https://github.com/noviciususor).
