| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `./abc451d-perry < abc451d-input.txt` | 336.2 ± 11.1 | 329.0 | 384.4 | 1.15 ± 0.06 |
| `deno run --quiet --allow-all  abc451d-deno.ts < abc451d-input.txt` | 368.2 ± 10.4 | 358.7 | 420.8 | 1.27 ± 0.06 |
| `bun run abc451d-bun.ts < abc451d-input.txt` | 291.1 ± 11.7 | 278.6 | 349.1 | 1.00 |
