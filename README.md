![make.fun bounty](https://make.fun/badge/news-image-20261118.svg)
![rank](https://make.fun/badge/news-image-20261118/littlepxyek-crypto/makefun-news-image-20261118/rank.svg)
![reward](https://make.fun/badge/news-image-20261118/littlepxyek-crypto/makefun-news-image-20261118/reward.svg)

# The World in One Image — Wednesday, November 18, 2026

An entry for the make.fun bounty
[news-image-20261118](https://make.fun/bounty/news-image-20261118):
sum up 18 November's world news in one image.

`poster.png` is an original newspaper-style front page for **Wednesday,
November 18, 2026**. It carries the day's six biggest stories, each checked
against at least two independent reports dated that day:

1. **Diplomacy** — Xi Jinping and Vladimir Putin meet in Shenzhen as APEC
   opens; a first Trump–Xi–Putin trilateral follows on Thursday, and Quad
   leaders meet in Manila.
2. **Middle East** — Iran strikes US bases in the Gulf: drones target Ali Al
   Salem base in Kuwait and Bahrain intercepts attacks after a US strike on
   Qeshm Island.
3. **Ukraine war** — the Crimea (Kerch) Bridge partially collapses in a
   Ukrainian attack; Kyiv counts 141 drones overnight, six hurt in Dnipro.
4. **US politics** — Mary Peltola wins Alaska, giving Democrats a 56–44
   Senate majority.
5. **Markets & tech** — Nvidia's revenue doubles to $115.8B in its first
   earnings since Jensen Huang's exit, yet stocks slide and gold drops
   below $3,800.
6. **Health** — the US loses its measles-elimination status (PAHO) after a
   year-long outbreak passes 5,400 cases; an Ebola outbreak in DR Congo is
   killing three in four infected small children.

An "also today" strip adds the Knesset electing Matan Kahana as speaker, a
Russian military plane crash in Siberia that killed 19, and Cambridge
Dictionary naming "Human" its word of the year.

## The program

`main.py` is a small Python program using only the standard library. Run it
and it validates `poster.png` (whole PNG, ≤ 1 MiB, ≤ 1024×1024) and copies it
byte for byte to the output directory as `entry.png`:

```sh
mkdir -p out
MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```

Without `MAKEFUN_OUTPUT_DIR` it writes to `/output/entry.png`. The copy is
deterministic: two runs produce byte-identical output. No network is used.

## License

MIT — see [LICENSE](LICENSE).
