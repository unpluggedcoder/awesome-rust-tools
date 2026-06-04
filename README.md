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
  - [Security](#security)

## Search

- [fd](https://github.com/sharkdp/fd) — A simple, fast and user-friendly alternative to 'find'.
- [igrep](https://github.com/konradsz/igrep) — Interactive Grep. Runs grep (ripgrep's library) in the background, allows interactively pick its results and open selected match in text editor of choice (vim by default).
- [MeiliSearch](https://github.com/meilisearch/MeiliSearch) — Lightning Fast, Ultra Relevant, and Typo-Tolerant Search Engine.
- [repgrep](https://github.com/acheronfail/repgrep) — An interactive replacer for ripgrep that makes it easy to find and replace across files on the command line.
- [ripgrep](https://github.com/BurntSushi/ripgrep) — A line-oriented search tool that recursively searches your current directory for a regex pattern.
- [television](https://github.com/alexpasmantier/television) — General purpose fuzzy finder TUI.
- [skim](https://github.com/lotabout/skim) — Fuzzy Finder in rust!
- [scout](https://github.com/jhbabon/scout) — Your friendly fuzzy finder.
- [Reflex](https://github.com/reflex-search/reflex) — Local-first, trigram-indexed full-text code search engine for large codebases. Sub-100ms queries, JSON output, and MCP server for AI agent workflows.
- [sweep-rs](https://github.com/aslpavel/sweep-rs) — Sweep is a tool for interactive search through a list of entries. It is inspired by fzf.

## FileSystem

- [diskus](https://github.com/sharkdp/diskus) — A minimal, fast alternative to 'du -sh'.
- [broot](https://github.com/Canop/broot) — A new way to see and navigate directory trees.
- [dua-cli](https://github.com/Byron/dua-cli) — A tool to conveniently learn about the disk usage of directories, fast!
- [dust](https://github.com/bootandy/dust) — A more intuitive version of `du` in rust.
- [dutree](https://github.com/nachoparker/dutree) — A tool to analyze file system usage written in Rust.
- [eza](https://github.com/eza-community/eza) — A modern alternative to ls.
- [felix](https://github.com/kyoheiu/felix) – tui file manager with vim-like key mapping.
- [fselect](https://github.com/jhspetersson/fselect) — Find files with SQL-like queries.
- [httm](https://github.com/kimono-koans/httm) – Interactive, file-level Time Machine-like tool for ZFS/btrfs/nilfs2 (and even Time Machine and Restic backups!).
- [lscolors](https://github.com/sharkdp/lscolors) – A Rust library and tool to colorize paths using LS_COLORS.
- [lsd](https://github.com/Peltoche/lsd) — The next gen ls command.
- [rip](https://github.com/nivekuil/rip) — A safe and ergonomic alternative to rm.
- [spacedrive](https://github.com/spacedriveapp/spacedrive) — Spacedrive is an open source cross-platform file explorer, powered by a virtual distributed filesystem written in Rust.
- [trashy](https://github.com/oberblastmeister/trashy) — a cli system trash manager, alternative to rm and trash-cli.
- [yazi](https://github.com/sxyazi/yazi) — 💥 Blazing fast terminal file manager written in Rust, based on async I/O.
- [zoxide](https://github.com/ajeetdsouza/zoxide) — A smarter cd command. Supports all major shells.

## File

- [bat](https://github.com/sharkdp/bat)— A `cat(1)` clone with wings.
- [csvlens](https://github.com/YS-L/csvlens) — Command line csv viewer.
- [hck](https://github.com/sstadick/hck) — A sharp cut(1) clone.
- [hex](https://github.com/sitkevij/hex) — 🔮 Futuristic take on hexdump, made in Rust.
- [hexyl](https://github.com/sharkdp/hexyl) — A command-line hex viewer.
- [intermodal](https://github.com/casey/intermodal) — Intermodal is a user-friendly and featureful command-line BitTorrent metainfo utility. The binary is called imdl and runs on Linux, Windows, and macOS.
- [lemmeknow](https://github.com/swanandx/lemmeknow) — The fastest way to identify anything!
- [Oculante](https://github.com/woelper/oculante) — A fast and simple image viewer / editor for many operating systems. 
- [ouch](https://github.com/ouch-org/ouch) — Painless compression and decompression in the terminal.
- [runiq](https://github.com/whitfin/runiq) — An efficient way to filter duplicate lines from input, à la uniq.
- [ruplacer](https://github.com/your-tools/ruplacer) — Find and replace text in source files.
- [termscp](https://github.com/veeso/termscp) – 🖥 A feature rich terminal UI file transfer and explorer with support for SCP/SFTP/FTP/S3/SMB.
- [xcp](https://github.com/tarka/xcp) — An extended `cp`.
- [xplr](https://github.com/sayanarijit/xplr) — A hackable, minimal, fast TUI file explorer.

## System Monitor

- [bandwhich](https://github.com/imsnif/bandwhich) — Terminal bandwidth utilization tool.
- [below](https://github.com/facebookincubator/below) — A time traveling resource monitor for modern Linux systems.
- [bottom](https://github.com/ClementTsang/bottom) — A customizable cross-platform graphical process/system monitor for the terminal.
- [bpftop](https://github.com/Netflix/bpftop) – bpftop provides a dynamic real-time view of running eBPF programs.
- [diskonaut](https://github.com/imsnif/diskonaut) — Terminal disk space navigator 🔭 .
- [netscanner](https://github.com/Chleba/netscanner) - All-in-one Network scanner.
- [macchina](https://github.com/Macchina-CLI/macchina) — A system information frontend with an emphasis on performance.
- [macmon](https://github.com/vladkens/macmon) - Sudoless performance / power monitoring for Apple Silicon processors.
- [pik](https://github.com/jacek-kurlit/pik) – Process Interactive Kill.
- [procs](https://github.com/dalance/procs) — **procs** is a replacement for `ps` written in [Rust](https://www.rust-lang.org/).
- [rsftch](https://github.com/charklie/rsftch) — Lightning fast hardware fetch written in rust.
- [rustnet](https://github.com/domcyrus/rustnet) - A cross-platform Terminal UI for real-time network monitoring with process identification and deep packet inspection.
- [RustScan](https://github.com/RustScan/RustScan) — 🤖 The Modern Port Scanner 🤖 .
- [sniffnet](https://github.com/GyulyVGC/sniffnet) — Cross-platform application to monitor your network traffic with ease.
- [trippy](https://github.com/fujiapple852/trippy) — A network diagnostic tool.
- [ytop(Archived)](https://github.com/cjbassi/ytop) - A TUI system monitor written in Rust.
- [Zenith](https://github.com/bvaisvil/zenith) — Sort of like top or htop but with zoom-able charts, network, and disk usage.
- [macdisp](https://github.com/noworrieseh/macdisp) – macOS command-line tool for changing the display.

## Shell/Terminal

- [alacritty](https://github.com/alacritty/alacritty) — A cross-platform, GPU-accelerated terminal emulator.
- [atuin](https://github.com/atuinsh/atuin) – ✨ Magical shell history.
- [createnv](https://github.com/cuducos/createnv) - 🧞‍♀️Automagically creates .env files.
- [handlr-regex](https://github.com/Anomalocaridid/handlr-regex) — A fork of `handlr` an `xdg-utils` alternative.
- [just](https://github.com/casey/just) — 🤖 Just a command runner.
- [mprocs](https://github.com/pvolok/mprocs) — Run multiple commands in parallel.
- [navi](https://github.com/denisidoro/navi) — An interactive cheatsheet tool for the command-line and application launchers.
- [nushell](https://github.com/nushell/nushell) — A modern shell written in Rust.
- [rargs](https://github.com/lotabout/rargs) – Rargs is kind of xargs + awk with pattern-matching support.
- [rio](https://github.com/raphamorim/rio) — A hardware-accelerated GPU terminal emulator focusing to run in desktops and browsers.
- [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) — Fast command line app in rust/tokio to execute commands in parallel. Similar interface to GNU parallel or xargs.
- [sd](https://github.com/chmln/sd) — Intuitive find & replace CLI (sed alternative).
- [shrs](https://github.com/MrPicklePinosaur/shrs) – The rusty shell toolkit for hackers.
- [splashboard](https://github.com/unhappychoice/splashboard) - A customizable terminal splash rendered on shell startup and on directory change, with per-directory dashboards.
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
- [difftastic](https://github.com/Wilfred/difftastic) — A structural diff that understands syntax 🟥🟩.
- [dnspeep](https://github.com/jvns/dnspeep) – spy on the DNS queries your computer is making.
- [dotter](https://github.com/SuperCuber/dotter) — A dotfile manager and templater written in rust 🦀.
- [dtool](https://github.com/guoxbin/dtool) — A command-line tool collection to assist development.
- [eva](https://github.com/nerdypepper/eva) – A calculator REPL, similar to bc(1).
- [fnm](https://github.com/Schniz/fnm) — 🚀 Fast and simple Node.js version manager, built in Rust.
- [forge](https://github.com/antinomyhq/forge) — A terminal-based AI pair programmer for software development, providing intelligent code assistance and collaboration features.
- [octomind](https://github.com/muvon/octomind) — Session-based AI development assistant with MCP support, 7 LLM providers, and extensible architecture.
- [fw](https://github.com/brocode/fw) — Workspace productivity booster.
- [git-absorb](https://github.com/tummychow/git-absorb) — git commit --fixup, but automatic.
- [gitlogue](https://github.com/unhappychoice/gitlogue) - A cinematic Git commit history replay for the terminal.
- [gitoxide](https://github.com/Byron/gitoxide) — An idiomatic, lean, fast & safe pure Rust implementation of Git.
- [gitui](https://github.com/extrawurst/gitui) — Blazing fast terminal-ui for git written in rust.
- [gity](https://github.com/neul-labs/gity) — A cross-platform Rust daemon that accelerates Git on large repos via the fsmonitor protocol.
- [gpg-tui](https://github.com/orhun/gpg-tui) – Manage your GnuPG keys with ease! 🔐.
- [grex](https://github.com/pemistahl/grex) - A command-line tool and library for generating regular expressions from user-provided test cases.
- [hurl](https://github.com/Orange-OpenSource/hurl) — Hurl, run and test HTTP requests with plain text.
- [jaq](https://github.com/01mf02/jaq) — A jq clone focussed on correctness, speed, and simplicity.
- [jj](https://github.com/martinvonz/jj) — A Git-compatible VCS that is both simple and powerful.
- [jless](https://github.com/PaulJuliusMartinez/jless) — jless is a command-line JSON viewer designed for reading, exploring, and searching through JSON data.
- [lurk](https://github.com/JakWai01/lurk) — A pretty (simple) alternative to strace.
- [mask](https://github.com/jacobdeichert/mask) — 🎭 A CLI task runner defined by a simple markdown file.
- [mise](https://github.com/jdx/mise) –  dev tools, env vars, task runner.
- [onefetch](https://github.com/o2sh/onefetch) – Command-line Git information tool.
- [omnigraph](https://github.com/ModernRelay/omnigraph) — "Typed graph database where agents branch and merge like Git. S3-native, traversal + vector + BM25 in one runtime."
- [pastel](https://github.com/sharkdp/pastel) — A command-line tool to generate, analyze, convert and manipulate colors.
- [qsv](https://github.com/dathere/qsv) — Blazing-fast Data-Wrangling toolkit.
- [riff](https://github.com/walles/riff) – A diff filter highlighting which line parts have changed.
- [rust_sqlite](https://github.com/joaoh82/rust_sqlite) — Simple embedded database modeled off SQLite in Rust
- [rust_kanban](https://github.com/yashs662/rust_kanban) — A kanban board for the terminal built with ❤️ in Rust.
- [sccache](https://github.com/mozilla/sccache) — sccache is a [ccache](https://ccache.dev/)-like compiler caching tool.
- [silicon](https://github.com/Aloxaf/silicon) — Silicon is an alternative to [Carbon](https://github.com/dawnlabs/carbon) implemented in Rust. It can render your source code into a beautiful image.
- [slumber](https://github.com/LucasPickering/slumber) — Terminal-based HTTP/REST client.
- [sqleibniz](https://github.com/xNaCly/sqleibniz) – LSP and analysis cli for sql. Check for valid syntax, semantics and perform dynamic analysis.
- [steel](https://github.com/mattwparas/steel) — An embedded scheme interpreter in Rust.
- [StyLua](https://github.com/JohnnyMorganz/StyLua) — An opinionated Lua code formatter.
- [tealdeer](https://github.com/dbrgn/tealdeer) — A very fast implementation of tldr in Rust.
- [tlrc](https://github.com/tldr-pages/tlrc) — A tldr client written in Rust.
- [tinty](https://github.com/tinted-theming/tinty) — A base16 and base24 color scheme manager.
- [tokei](https://github.com/XAMPPRocky/tokei) — Count your code, quickly.
- [ugdb](https://github.com/ftilde/ugdb) — An alternative TUI for gdb wrote in Rust.
- [xsv](https://github.com/BurntSushi/xsv) — A fast CSV command line toolkit written in Rust.

## Editor

- [amp](https://github.com/jmacdonald/amp) — A text editor for your terminal.
- [gnvim](https://github.com/vhakulinen/gnvim) — GNvim, Neovim GUI aiming for rich code editing experience without any unnecessary web bloat.
- [helix](https://github.com/helix-editor/helix) — A post-modern modal text editor.
- [iota](https://github.com/gchp/iota) — A terminal-based text editor written in Rust.
- [lapce](https://github.com/lapce/lapce) — Lightning-fast and Powerful Code Editor written in Rust.
- [neovide](https://github.com/Kethku/neovide) — No Nonsense Neovim Client in Rust.
- [qnote](https://github.com/Omibranch/qnote) — Minimal frameless notepad for Linux with Markdown preview, PDF export via Typst, OCR via Tesseract, and version history. Built with Tauri 2.
- [rnote](https://github.com/flxzt/rnote) — Sketch and take handwritten notes.
- [TUI-Journal](https://github.com/AmmarAbouZor/tui-journal) — Your journal app if you live in a terminal.
- [xi-editor](https://github.com/xi-editor/xi-editor) — A modern editor with a backend written in Rust.
- [zed](https://github.com/zed-industries/zed) — Code at the speed of thought.

## Others

- [bartib](https://github.com/nikolassv/bartib) - A simple timetracker for the command line.
- [coreutils](https://github.com/uutils/coreutils) – Cross-platform Rust rewrite of the GNU coreutils.
- [fend](https://github.com/printfn/fend) — Arbitrary-precision unit-aware calculator.
- [gittype](https://github.com/unhappychoice/gittype) - A code-typing game that turns your source code into typing challenges.
- [himalaya](https://github.com/soywod/himalaya) – 📫 CLI email client written in Rust.
- [inlyne](https://github.com/Inlyne-Project/inlyne) — A GPU powered yet browserless tool to help you quickly view markdown files in the blink of an eye.
- [kanata](https://github.com/jtroo/kanata) - Improve keyboard comfort and usability with advanced customization.
- [md-tui](https://github.com/henriklovhaug/md-tui) - A TUI application for viewing markdown files.
- [see](https://github.com/guilhermeprokisch/see) - A file visualization tool for terminal, offering advanced code viewing capabilities, Markdown rendering, and more. It provides syntax highlighting, emoji support, and image rendering capabilities, offering a visually appealing way to view various file types directly in your console.
- [poketex](https://github.com/ckaznable/poketex) – Simple Pokedex based on TUI(Terminal User Interface).
- [ratatui](https://github.com/ratatui/ratatui) — A Rust crate for cooking up terminal user interfaces (TUIs).
- [rustdesk](https://github.com/rustdesk/rustdesk) — The best open source remote desktop client software.
- [shadowsocks-rust](https://github.com/shadowsocks/shadowsocks-rust) — A Rust port of shadowsocks
- [sudo.rs](https://github.com/memorysafety/sudo-rs) — A safety oriented and memory safe implementation of sudo and su written in Rust.
- [vaultwarden](https://github.com/dani-garcia/vaultwarden) — Unofficial Bitwarden compatible server written in Rust, formerly known as bitwarden_rs.
- [youtube-tui](https://github.com/Siriusmart/youtube-tui) – An aesthetically pleasing YouTube TUI written in Rust.
- [ytermusic](https://github.com/ccgauche/ytermusic) — An in terminal youtube music client with focus on privacy, simplicity and performance.
- [zola](https://github.com/getzola/zola) — A fast static site generator in a single binary with everything built-in. https://www.getzola.org
- [zerobrew](https://github.com/lucasgelfond/zerobrew) – A drop-in, 5-20x faster, experimental Homebrew alternative.

## Security

- [n01d-forge](https://github.com/bad-antics/n01d-forge) — Native GUI image burner with LUKS/VeraCrypt encryption support for creating secure bootable drives.
- [n01d-machine](https://github.com/bad-antics/n01d-machine) — Secure VM manager with Tor/VPN integration, sandbox isolation, and network compartmentalization.

Thanks these authors.
