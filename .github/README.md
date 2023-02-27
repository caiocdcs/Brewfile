
<h1 align="center">caiocdcs/Brewfile</h1>
<p align="center"><i>My list of *nix packages to be installed on MacOS via Homebrew, for the ultimate dev setup</i></p>
<p align="center"><i><a href="https://github.com/Lissy93/Brewfile">Inspired by Lissy93/Brewfile</a></i></p>
<p align="center">
  <a href="https://github.com/caiocdcs/brewfile/">
    <img width="120" src="https://i.ibb.co/LhhDNg7/brewfile-repo-logo.png" />
  </a>
</p>


## Getting Started

To get started, just run the setup script:

```bash
bash <(curl -s https://caiocdcs.github.io/Brewfile/install.sh)
```

Alternatively, you can just download the [`Brewfile`](https://github.com/caiocdcs/Brewfile/blob/master/Brewfile) to `~/.Brewfile`, make any desired changes, then run `brew bundle --global` to install the listed packages.

---

## About Homebrew

[Homebrew](https://brew.sh/) is an unofficial package manager for MacOS, that makes installing, updating and managing user applications easier.

It only ever installs packages within it's prefix, but then symlinks them to the appropriate place on disk. And since it's just Git and Ruby underneath, it's easy to modify to your liking, and roll back changes if necissary.

Homebrew is used via the terminal, with the `brew` command, but there is an unofficial GUI, [Cakebrew](https://github.com/brunophilipe/Cakebrew). For more infomation, take a look at the [Documentation](https://docs.brew.sh/).

---

## Understanding the Brewfile

The Brewfile defines a list of packages, that you'd like to install on your system.

It includes several keywords, like `brew`, `cask`, `tap`, `mas`, etc - this is explained in detail in the [terminology](https://docs.brew.sh/Manpage#terminology) section of the docs. But in short: Lines which start with brew are packages that are installed via their pre-compiled binaries. Where as casks are applications that require an installer (typically GUI apps). Taps just add additional repositories, and are used when an app's formula isn't published to the main Homebrew repo. And mas is a plugin that enables you to install apps from the Apple App Store from within your Brewfile.

---

## Package List

The following packages will be installed, with the aim to setup a fully-featured development machine.

<details>
<summary><b>Click to expand full package list</b> ↕️</summary>

> **Note**: _Be sure to remove anything that you do not need before installing._

### Command Line

<details>
<summary>CLI Essentials</summary>

- [`git`](https://git-scm.com/) - Version control

</details>

<details>
<summary>CLI Basics</summary>

- [`aria2`](https://github.com/aria2/aria2) - Resuming download util _(better wget)_
- [`bat`](https://github.com/sharkdp/bat) - Output highlighting _(better cat)_
- [`ctags`](https://github.com/universal-ctags/ctags) - Indexing of file info + headers
- [`diff-so-fancy`](https://github.com/so-fancy/diff-so-fancy) - Readable file compares _(better diff)_
- [`entr`](https://eradman.com/entrproject/) - Run command whenever file changes
- [`duf`](https://github.com/muesli/duf) - Get info on mounted disks _(better df)_
- [`exa`](https://github.com/ogham/exa) - Listing files with info _(better ls)_
- [`fdupes`](https://github.com/jbruchon/jdupes) - Duplicate file finder
- [`fzf`](https://github.com/junegunn/fzf) - Fuzzy file finder and filtering
- [`hyperfine`](https://github.com/sharkdp/hyperfine) - Benchmarking for arbitrary commands
- [`jq`](https://github.com/stedolan/jq) - JSON parser
- [`most`](https://www.jedsoft.org/most/) - Multi-window scroll pager _(better less)_
- [`procs`](https://github.com/dalance/procs) - Advanced process viewer _(better ps)_
- [`ripgrep`](https://github.com/BurntSushi/ripgrep) - Searching within files _(better grep)_
- [`rsync`](https://rsync.samba.org/) - Fast, incremental file transfer
- [`scc`](https://github.com/boyter/scc) - Count lines of code _(better cloc)_
- [`sd`](https://github.com/chmln/sd) - RegEx find and replace _(better sed)_
- [`thefuck`](https://github.com/nvbn/thefuck) - Auto-correct miss-typed commands
- [`tldr`](https://github.com/tldr-pages/tldr) - Community-maintained docs _(better man)_
- [`tre`](https://github.com/dduan/tre) - Directory hierarchy (better tree)
- [`trash-cli`](https://github.com/andreafrancia/trash-cli) - Record + restore removed files
- [`watch`](https://gitlab.com/procps-ng/procps) - Run commands periorically
- [`xsel`](https://github.com/kfish/xsel) - Copy paste access to X clipboard
- [`zoxide`](https://github.com/ajeetdsouza/zoxide) - Easy navigation _(better cd)_

</details>

<details>
<summary>CLI Monitoring and Performance Apps</summary>

- [`bandwhich`](https://github.com/imsnif/bandwhich) - Bandwidth utilization monitor 
- [`ctop`](https://github.com/bcicen/ctop) - Container metrics and monitoring
- [`bpytop`](https://github.com/aristocratos/bpytop) - Resource monitoring _(like htop)_
- [`glances`](https://github.com/nicolargo/glances) - Resource monitor + web and API
- [`gping`](https://github.com/orf/gping) - Interactive ping tool, with graph
- [`ncdu`](https://dev.yorhel.nl/ncdu) - Disk usage analyzer and monitor _(better du)_
- [`speedtest-cli`](https://github.com/sivel/speedtest-cli) - Command line speed test utility

</details>

<details>
<summary>CLI Dev Suits</summary>

- [`httpie`](https://httpie.io/) - HTTP / API testing testing client
- [`kdash`](https://kdash.cli.rs/) - Kubernetes dashboard app

</details>

<details>
<summary>CLI External Services</summary>

- [`navi`](https://github.com/denisidoro/navi) - Browse, search, read cheat sheets

</details>

<details>
<summary>CLI Fun</summary>

- [`neofetch`](https://github.com/dylanaraps/neofetch) - Show system data and ditstro info

</details>

### Software Development

<details>
<summary>Development Apps</summary>

- [Boop](https://github.com/IvanMathy/Boop) - Test transformation tool _(MacOS Only)_
- [iterm2](https://iterm2.com/) - Better terminal emulator _(MacOS Only)_
- [Postman](https://www.postman.com/) - HTTP API testing app
- [VS Code](https://code.visualstudio.com/) - Code editor

</details>

<details>
<summary>Development Langs, Compilers, Package Managers and SDKs</summary>

- `docker` - Containers
- `gcc` - GNU C++ compilers
- `go` - Compiler for Go Lang
- `gradle` - Build tool for Java
- `maven` - Dependency Manager for Java
- `openjdk` - Java development kit
- `python` - Python interpriter

</details>

<details>
<summary>Development Utils</summary>

- [`gh`](https://cli.github.com/) - Interact with GitHub PRs, issues, repos

</details>

<details>
<summary>Security Utilities</summary>

- [`bcrypt`](https://bcrypt.sourceforge.net/) - Encryption utility, using blowfish
- [`clamav`](https://www.clamav.net/) - Open source virus scanning suite
- [`lynis`](https://cisofy.com/lynis/) - Scan system for common security issues
- [`openssl`](https://www.openssl.org/) - Cryptography and SSL/TLS Toolkit
- [`rkhunter`](https://rkhunter.sourceforge.net/) - Search / detect potential root kits

</details>

### Desktop Applications

<details>
<summary>Media</summary>

- [Calibre](https://calibre-ebook.com/) - E-Book reader
- [Spotify](https://spotify.com) - Propietary music streaming
- [Transmission](https://transmissionbt.com/) - Torrent client
- [Pandoc](https://pandoc.org/) - Universal file converter

</details>

<details>
<summary>Personal Applications</summary>

- [1Password](https://1password.com/) - Password manager _(proprietary)_
- [Obsidian](https://obsidian.md/) - Markdown notes

</details>

<details>
<summary>Browsers</summary>

- [Google Chrome](https://www.google.com/chrome/)

</details>

### MacOS Apps

<details>
<summary>MacOS Mods and Improvements</summary>

- `alt-tab` - Much better alt-tab window switcher
- `copyclip` - Clipboard manager
- `lporg` - Backup and restore launchpad layout
- `raycast` - Spotlight alternative
- `santa` - Binary authorization for security
- `stats` - System resource usage in menubar

</details>

</details>

---

## License

> **Note** For licenses for each package listed here, see their websites _(linked to [above](#package-list))_.

> _**[Lissy93/Brewfile](https://github.com/Lissy93/Brewfile)** is licensed under [MIT](https://github.com/Lissy93/Brewfile/blob/HEAD/LICENSE) © [Alicia Sykes](https://aliciasykes.com) 2022._<br>
> <sup align="right">For information, see <a href="https://tldrlegal.com/license/mit-license">TLDR Legal > MIT</a></sup>

<details>
<summary>Expand License</summary>

```
The MIT License (MIT)
Copyright (c) Alicia Sykes <alicia@omg.com> 

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sub-license, and/or sell 
copies of the Software, and to permit persons to whom the Software is furnished 
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included install 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANT ABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

</details>

---

<!-- License + Copyright -->
<p  align="center">
  <i>Licensed under <a href="https://gist.github.com/Lissy93/143d2ee01ccc5c052a17">MIT</a></i><br>
  <a href="https://github.com/lissy93"><img src="https://i.ibb.co/4KtpYxb/octocat-clean-mini.png" /></a><br>
  <sup>Thanks for visiting :)</sup>
</p>