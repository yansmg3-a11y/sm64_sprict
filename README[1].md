# Mario 64 Pursuitcore

Files in this repo:
- `Mario_Pursuitcore.lua`: the Mario 64 script (Pursuitcore mode optional, off by default)
- `pc_lms.mp3`: Powerful Mario (plays when you are the last person standing)
- `pc_chase.mp3`: The Steps Behind You (plays during a chase)
- `loader.lua`: the one line you run in your executor

## Use
1. Edit `MUSIC_BASE` near the top of `Mario_Pursuitcore.lua` to `https://raw.githubusercontent.com/YOUR_USER/YOUR_REPO/main/`
2. Run the line from `loader.lua` (with your user and repo name).
3. Turn on Pursuitcore mode in the SM64 menu, then use PC > Test music.

The music is downloaded and saved by the script the first time, so it needs an executor with `writefile`, `getcustomasset` and `game:HttpGet`.
