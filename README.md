# Advent of Code

My [Advent of Code](https://adventofcode.com) solutions in Rust, run with [elfcode](https://github.com/maartenpeels/elfcode).

Solutions live in `src/y{YYYY}/day{DD}.rs`. Each day's examples live in `data/{YYYY}/{DD}/examples.toml`. Puzzle inputs and texts are not committed, as Advent of Code asks.

## Usage

```sh
cargo install cargo-elfcode
cargo elfcode login <session-cookie>

cargo elfcode scaffold 3            # create day 3 and fetch its input
cargo test                          # check the examples
cargo elfcode run 3                 # solve both parts
cargo elfcode run 3 --submit 1      # submit part 1
```

Add `--year 2024` to work on an earlier event.
