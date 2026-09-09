# cs2-utils
cs2-utils is an CFG ONLY repo so it can last as long as possible compared to *.cpp/map_workshop.
it contains:
- practice.cfg with spawns checkpoint/teleport positions.
- demo.cfg with useful binds for navigation/speeds.
- lineups.png as extra instant lineups.

it is designed to bind everything with navigation keys (ins del home end pgup pgdn).
prac.cfg also binds -/+ and arrow keys.

# setup

move all into `Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

# usage

<p align="center">
<img align=center src="https://github.com/m-curto/cs2-utils/blob/main/others/readme/console.png">
</p>

launch any practice map then open console:
`exec prac.cfg`

launch any demo then open console:
`exec demo.cfg`

# notes

`exec path\to\cfg` starts from the `game\csgo\cfg` directory.
you can also put `exec prac.cfg` at the end of `\game\csgo\cfg\gamemode_competitive.cfg` to launch prac.cfg automatically.
you can also copy/paste *.png in steam notes.
if anything break (or loaded the wrong map_spawns), you can re-exec prac.cfg.

# todo

- [x] de_ancient
- [x] de_anubis
- [ ] de_cache CT
- [x] de_dust2
- [x] de_inferno
- [ ] de_mirage
- [x] de_nuke
- [ ] de_overpass T

