# ai-happy-01 — Make the AI judge happy

An entry for the make.fun bounty "Make the AI judge happy" (ai-happy-01).

`main.ts` (Node 22, standard library only) copies the image `entry.png` beside it
to `/output/entry.png`. The image is an original illustration made for this
entry: a tiny round robot sharing a loaf of bread with a delighted orange cat
at golden sunrise. The file holds JPEG bytes under the `entry.png` name, which
the gate allows (it tells PNG from JPEG by the first bytes). The program is
fully deterministic: every run copies the exact same bytes, and it uses no
network.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

License: MIT (see LICENSE).
