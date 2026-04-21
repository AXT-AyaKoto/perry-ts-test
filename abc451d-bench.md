| Command | Mean [s] | Min [s] | Max [s] | Relative |
|:---|---:|---:|---:|---:|
| `./abc451d-perry < abc451d-input.txt` | 1.368 ± 0.162 | 1.154 | 1.890 | 3.77 ± 0.90 |
| `deno run --quiet --allow-all  abc451d-deno.ts < abc451d-input.txt` | 0.483 ± 0.080 | 0.390 | 0.698 | 1.33 ± 0.35 |
| `bun run abc451d-bun.ts < abc451d-input.txt` | 0.363 ± 0.075 | 0.305 | 0.613 | 1.00 |
