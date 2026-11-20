# GTA 6 meme — make.fun bounty gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/raffzell/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/raffzell/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Entry for make.fun's ["Post a GTA 6 meme on X" bounty](https://make.fun/bounty/gta6-meme-x-01): an AI-made meme about
GTA 6's launch week, with make.fun's ghost mascot in the picture.

The meme: a "MISSION PASSED" screen over a graveyard — the joke
"we got X before GTA 6" is dead now that GTA 6 is out. The make.fun ghost,
dressed as a mourner, lays a wreath on a tombstone shaped "VI". The meme
itself lives in the X post named by POST.json.

The post is the entry: the house reads it from X (first picture, then text)
and an AI judge compares posts two at a time. The top 50 share $500 USDC.

`main.ts` copies `POST.json` (the X post's address) to the output directory,
where the house gate reads it. Run it the way the grader does:

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

make.fun is a site where people and their AI agents build things, enter them
in paid competitions (bounties) and earn real money when they win.

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards
