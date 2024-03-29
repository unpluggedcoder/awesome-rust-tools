# Awesome Rust Tools

Harness the power of Rust. Those fast productivity tools based on Rust.

## Table of contents

- [Awesome Rust Tools](#awesome-rust-tools)
  - [Table of contents](#table-of-contents)
  - [Search](#search)
  - [FileSystem](#filesystem)
  - [File](#file)
  - [System Monitor](#system-monitor)
  - [Shell/Terminal](#shellterminal)
  - [Performance](#performance)
  - [Dev-Utilities](#dev-utilities)
  - [Editor](#editor)
  - [Others](#others)

## Search

- [fd](https://github.com/sharkdp/fd) — A simple, fast and user-friendly alternative to 'find'.
- [igrep](https://github.com/konradsz/igrep) — Interactive Grep. Runs grep (ripgrep's library) in the background, allows interactively pick its results and open selected match in text editor of choice (vim by default).
- [MeiliSearch](https://github.com/meilisearch/MeiliSearch) — Lightning Fast, Ultra Relevant, and Typo-Tolerant Search Engine.
- [ripgrep](https://github.com/BurntSushi/ripgrep) — A line-oriented search tool that recursively searches your current directory for a regex pattern.
- [skim](https://github.com/lotabout/skim) — Fuzzy Finder in rust!

## FileSystem

- [broot](https://github.com/Canop/broot) — A new way to see and navigate directory trees.
- [dua-cli](https://github.com/Byron/dua-cli) — A tool to conveniently learn about the disk usage of directories, fast!
- [dust](https://github.com/bootandy/dust) — A more intuitive version of `du` in rust.
- [dutree](https://github.com/nachoparker/dutree) — A tool to analyze file system usage written in Rust.
- [felix](https://github.com/kyoheiu/felix) – tui file manager with vim-like key mapping.
- [fselect](https://github.com/jhspetersson/fselect) — Find files with SQL-like queries.
- [lscolors](https://github.com/sharkdp/lscolors) – A Rust library and tool to colorize paths using LS_COLORS.
- [lsd](https://github.com/Peltoche/lsd) — The next gen ls command.
- [zoxide](https://github.com/ajeetdsouza/zoxide) — A smarter cd command. Supports all major shells.

## File

- [bat](https://github.com/sharkdp/bat)— A `cat(1)` clone with wings.
- [csvlens](https://github.com/YS-L/csvlens) — Command line csv viewer.
- [hexyl](https://github.com/sharkdp/hexyl) — A command-line hex viewer.
- [intermodal](https://github.com/casey/intermodal) — Intermodal is a user-friendly and featureful command-line BitTorrent metainfo utility. The binary is called imdl and runs on Linux, Windows, and macOS.
- [lemmeknow](https://github.com/swanandx/lemmeknow) — The fastest way to identify anything!
- [ouch](https://github.com/ouch-org/ouch) — Painless compression and decompression in the terminal.
- [xcp](https://github.com/tarka/xcp) — An extended `cp`.
- [xplr](https://github.com/sayanarijit/xplr) — A hackable, minimal, fast TUI file explorer.

## System Monitor

- [bandwhich](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool.
- [bottom](https://github.com/ClementTsang/bottom) — A customizable cross-platform graphical process/system monitor for the terminal.
- [bpftop](https://github.com/Netflix/bpftop) – bpftop provides a dynamic real-time view of running eBPF programs.
- [netscanner](https://github.com/Chleba/netscanner) - All-in-one Network scanner.
- [procs](https://github.com/dalance/procs) — **procs** is a replacement for `ps` written in [Rust](https://www.rust-lang.org/).
- [RustScan](https://github.com/RustScan/RustScan) — 🤖 The Modern Port Scanner 🤖 .
- [sniffnet](https://github.com/GyulyVGC/sniffnet) — Cross-platform application to monitor your network traffic with ease.
- [trippy](https://github.com/fujiapple852/trippy) — A network diagnostic tool.
- [ytop(Archived)](https://github.com/cjbassi/ytop) - A TUI system monitor written in Rust.
- [Zenith](https://github.com/bvaisvil/zenith) — Sort of like top or htop but with zoom-able charts, network, and disk usage.

## Shell/Terminal

- [alacritty](https://github.com/alacritty/alacritty) — A cross-platform, GPU-accelerated terminal emulator.
- [atuin](https://github.com/atuinsh/atuin) – ✨ Magical shell history.
- [atuin](https://github.com/ellie/atuin) — 🐢 Magical shell history.
- [just](https://github.com/casey/just) — 🤖 Just a command runner.
- [mprocs](https://github.com/pvolok/mprocs) — Run multiple commands in parallel.
- [navi](https://github.com/denisidoro/navi) — An interactive cheatsheet tool for the command-line and application launchers.
- [nushell](https://github.com/nushell/nushell) — A modern shell written in Rust.
- [rio](https://github.com/raphamorim/rio) — A hardware-accelerated GPU terminal emulator focusing to run in desktops and browsers.
- [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) — Fast command line app in rust/tokio to execute commands in parallel. Similar interface to GNU parallel or xargs.
- [sd](https://github.com/chmln/sd) — Intuitive find & replace CLI (sed alternative).
- [shrs](https://github.com/MrPicklePinosaur/shrs) – The rusty shell toolkit for hackers.
- [starship](https://github.com/starship/starship) — ☄🌌️ The minimal, blazing-fast, and infinitely customizable prompt for any shell! [https://starship.rs](https://starship.rs/)
- [wezterm](https://github.com/wez/wezterm) — A GPU-accelerated cross-platform terminal emulator and multiplexer written by @wez and implemented in Rust.
- [zellij](https://github.com/zellij-org/zellij) — A terminal workspace with batteries included.

## Performance

- [cargo-flamegraph](https://github.com/ferrous-systems/cargo-flamegraph) — Easy flamegraphs for Rust projects and everything else, without Perl or pipes <3.
- [hyperfine](https://github.com/sharkdp/hyperfine) — A command-line benchmarking tool.
- [inferno](https://github.com/jonhoo/inferno) — A Rust port of FlameGraph. 18x~20x faster than [flamegraph.pl](https://github.com/brendangregg/FlameGraph/blob/master/flamegraph.pl).
- [py-spy](https://github.com/benfred/py-spy) — Sampling profiler for Python programs.

## Dev-Utilities

- [bytehound](https://github.com/koute/memory-profiler) — A memory profiler for Linux.
- [delta](https://github.com/dandavison/delta) — A syntax-highlighting pager for git, diff, and grep output.
- [dnspeep](https://github.com/jvns/dnspeep) – spy on the DNS queries your computer is making.
- [dotter](https://github.com/SuperCuber/dotter) — A dotfile manager and templater written in rust 🦀.
- [dtool](https://github.com/guoxbin/dtool) — A command-line tool collection to assist development.
- [eva](https://github.com/nerdypepper/eva) – A calculator REPL, similar to bc(1).
- [fnm](https://github.com/Schniz/fnm) — 🚀 Fast and simple Node.js version manager, built in Rust.
- [git-absorb](https://github.com/tummychow/git-absorb) — git commit --fixup, but automatic.
- [gitoxide](https://github.com/Byron/gitoxide) — An idiomatic, lean, fast & safe pure Rust implementation of Git.
- [gitui](https://github.com/extrawurst/gitui) — Blazing fast terminal-ui for git written in rust.
- [gpg-tui](https://github.com/orhun/gpg-tui) – Manage your GnuPG keys with ease! 🔐.
- [grex](https://github.com/pemistahl/grex) - A command-line tool and library for generating regular expressions from user-provided test cases.
- [hurl](https://github.com/Orange-OpenSource/hurl) — Hurl, run and test HTTP requests with plain text.
- [jaq](https://github.com/01mf02/jaq) — A jq clone focussed on correctness, speed, and simplicity.
- [jless](https://github.com/PaulJuliusMartinez/jless) — jless is a command-line JSON viewer designed for reading, exploring, and searching through JSON data.
- [lurk](https://github.com/JakWai01/lurk) — A pretty (simple) alternative to strace.
- [onefetch](https://github.com/o2sh/onefetch) – Command-line Git information tool.
- [pastel](https://github.com/sharkdp/pastel) — A command-line tool to generate, analyze, convert and manipulate colors.
- [rust_sqlite](https://github.com/joaoh82/rust_sqlite) — Simple embedded database modeled off SQLite in Rust
- [sccache](https://github.com/mozilla/sccache) — sccache is a [ccache](https://ccache.dev/)-like compiler caching tool.
- [silicon](https://github.com/Aloxaf/silicon) — Silicon is an alternative to [Carbon](https://github.com/dawnlabs/carbon) implemented in Rust. It can render your source code into a beautiful image.
- [steel](https://github.com/mattwparas/steel) — An embedded scheme interpreter in Rust.
- [StyLua](https://github.com/JohnnyMorganz/StyLua) — An opinionated Lua code formatter.
- [tealdeer](https://github.com/dbrgn/tealdeer) — A very fast implementation of tldr in Rust.
- [ugdb](https://github.com/ftilde/ugdb) — An alternative TUI for gdb wrote in Rust.
- [xsv](https://github.com/BurntSushi/xsv) — A fast CSV command line toolkit written in Rust.

## Editor

- [amp](https://github.com/jmacdonald/amp) — A text editor for your terminal.
- [gnvim](https://github.com/vhakulinen/gnvim) — GNvim, Neovim GUI aiming for rich code editing experience without any unnecessary web bloat.
- [lapce](https://github.com/lapce/lapce) — Lightning-fast and Powerful Code Editor written in Rust.
- [neovide](https://github.com/Kethku/neovide) — No Nonsense Neovim Client in Rust.
- [rnote](https://github.com/flxzt/rnote) — Sketch and take handwritten notes.
- [TUI-Journal](https://github.com/AmmarAbouZor/tui-journal) — Your journal app if you live in a terminal.
- [xi-editor](https://github.com/xi-editor/xi-editor) — A modern editor with a backend written in Rust.

## Others

- [bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs) — Unofficial Bitwarden compatible server written in Rust
- [coreutils](https://github.com/uutils/coreutils) – Cross-platform Rust rewrite of the GNU coreutils
- [fend](https://github.com/printfn/fend) — Arbitrary-precision unit-aware calculator.
- [himalaya](https://github.com/soywod/himalaya) – 📫 CLI email client written in Rust.
- [poketex](https://github.com/ckaznable/poketex) – Simple Pokedex based on TUI(Terminal User Interface).
- [rustdesk](https://github.com/rustdesk/rustdesk) — The best open source remote desktop client software.
- [shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) — A Rust port of shadowsocks
- [tui-rs](https://github.com/fdehau/tui-rs) — A [Rust](https://www.rust-lang.org/) library to build rich terminal user interfaces and dashboards.
- [zola](https://github.com/getzola/zola) — A fast static site generator in a single binary with everything built-in. https://www.getzola.org

Thanks these authors.
