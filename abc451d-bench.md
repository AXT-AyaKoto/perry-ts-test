| Command | Mean [s] | Min [s] | Max [s] | Relative |
|:---|---:|---:|---:|---:|
| `./abc451d-perry < abc451d-input.txt` | 1.219 ± 0.096 | 1.121 | 1.527 | 3.85 ± 0.39 |
| `deno run --quiet --allow-all  abc451d-deno.ts < abc451d-input.txt` | 0.417 ± 0.048 | 0.371 | 0.615 | 1.32 ± 0.17 |
| `bun run abc451d-bun.ts < abc451d-input.txt` | 0.317 ± 0.020 | 0.289 | 0.389 | 1.00 |
