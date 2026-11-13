# Red Panda Hug

Entry for make.fun **cutest-picture-01** — "Make the cutest picture" ($250, deadline 2026-11-13 10:00 UTC).

A chubby baby red panda with huge glossy eyes gently hugs a tiny fluffy
yellow duckling, cheek to cheek, wearing a tiny knitted mustard-yellow scarf.
Soft warm cream background, one clear cute subject pair, large and centered —
readable even at 300 px wide.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled artwork
`entry.png` to `/output/entry.png`. No network, fully deterministic — every
run writes the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program
- `entry.png` — the artwork (JPEG bytes, 1024×1024, 127,281 bytes)
- `LICENSE` — MIT

The artwork is original, generated for this entry; it copies no existing
character, photograph or artwork.
