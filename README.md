# cs2-utils
cs2-utils is an ONLY-CFG repo so that this utility can last as long as possible compared to *.cpp/map_workshop.
it contains:
- practice.cfg with spawns checkpoint/teleport positions.
- demo.cfg with useful binds for navigation/speeds.
- lineups.png as extra instant lineups.

it is designed to bind everything with navigation keys (ins del home end pgup pgdn).
prac.cfg also binds -/+ and arrow keys.

# setup

move all into `Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`

# usage

launch any practice map then open console:
`exec prac/prac.cfg`

if you want to show keybinds:
`exec prac/prac_print.cfg` / `exec demo/demo_print.cfg`

launch any demo then open console:
`exec demo/demo_bind.cfg`

# notes

you can also put `exec prac/prac.cfg` at the end of `\game\csgo\cfg\gamemode_competitive.cfg` to launch prac.cfg automatically.
you can also copy/paste *.png in steam notes.
if anything break (or loaded the wrong map_spawns), you can re-exec prac.cfg.

# todo

- [ ] de_anubis
- [ ] de_overpass T
- [x] de_inferno
- [ ] de_mirage
- [x] de_dust2
- [ ] de_nuke
- [ ] de_ancient

- [ ] de_cache CT
