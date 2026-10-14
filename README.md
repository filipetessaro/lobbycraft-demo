# Lobbycraft Demo

Playable Windows demo of **Lobbycraft**, one online API for Steam and Epic Online Services in Unreal Engine: sessions,
crossplay, a waiting room with voice, achievements, stats, leaderboards and cloud saves. It is the plugin's example,
packaged as a Shipping build with UE 5.8.

**Download:** [LobbycraftDemo_Windows.zip](https://github.com/filipetessaro/lobbycraft-demo/releases/latest/download/LobbycraftDemo_Windows.zip)
(265 MB). No engine needed.

- **One PC:** run `Two players on this PC.bat`. Two windows open on the local network, without Steam. Press Host in
  one; in the other, press Join on the game in the list. Both land in the waiting room: ready, chat and Start Game.
- **Two PCs with Steam:** sign in to Steam on both, with two different accounts, and run `LobbycraftDemo.exe`. It uses
  Valve's test app 480 (Spacewar), so the list can also show other developers' test games. On the same network, tick
  Local network.

The demo has no EOS credentials, so it runs on Steam or the local network only. Crossplay with Epic needs your own
EOS product.

Docs: https://lobbycraft.tessaroapps.com/
