#############################################################
# ~/.Brewfile - Software Installs for MacOS                 #
#                                                           #
# List of packages to be installed / updated via Homebrew   #
# Apps are sorted by category, and arranged alphabetically  #
# Be sure to delete / comment out anything you do not need  #
# Usage, run: $ brew bundle --global --file $HOME/.Brewfile #
# Source GH repository: https://github.com/lissy93/Brewfile #
# See brew docs for more info: https://docs.brew.sh/Manpage #
#                                                           #
# License: MIT © Alicia Sykes 2022 <https://aliciasykes.com>#
#############################################################

# Options
cask_args appdir: '~/Applications', require_sha: true

# Taps
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'homebrew/services'
tap 'blacktop/tap'
tap 'jesseduffield/lazygit'
tap 'koekeishiya/formulae'
tap 'kdash-rs/kdash'
tap 'derailed/k9s'

#############################################################
# Command Line                                              #
#############################################################

# CLI Essentials
brew 'git'          # Version control

# CLI Basics
brew 'aria2'        # Resuming download util (better wget)
brew 'bat'          # Output highlighting (better cat)
brew 'broot'        # Interactive directory navigation
brew 'ctags'        # Indexing of file info + headers
brew 'diff-so-fancy'# Readable file compares (better diff)
brew 'duf'          # Get info on mounted disks (better df)
brew 'entr'         # Run command whenever file changes
brew 'exa'          # Listing files with info (better ls)
brew 'fzf'          # Fuzzy file finder and filtering
brew 'hyperfine'    # Benchmarking for arbitrary commands
brew 'jdupes'       # Duplicate file finder
brew 'jq'           # JSON parser, output and query files
brew 'most'         # Multi-window scroll pager (better less)
brew 'procs'        # Advanced process viewer (better ps)
brew 'ripgrep'      # Searching within files (better grep)
brew 'rsync'        # Fast incremental file transfer
brew 'sd'           # RegEx find and replace (better sed)
brew 'thefuck'      # Auto-correct miss-typed commands
brew 'tldr'         # Community-maintained docs (better man)
brew 'tokei'        # Count lines of code (better cloc)
brew 'tre'          # Directory hierarchy (better tree)
brew 'trash-cli'    # Record and restore removed files
brew 'watch'        # Run commands periorically
brew 'xsel'         # Copy paste access to the X clipboard
brew 'zoxide'       # Auto-learning navigation (better cd)

# CLI Monitoring and Performance Apps
brew 'bmon'         # Bandwidth utilization monitor
brew 'ctop'         # Container metrics and monitoring
brew 'bpytop'       # Resource monitoring (like htop)
brew 'dua-cli'      # Disk usage analyzer and monitor (better du)
brew 'glances'      # Resource monitor + web and API
brew 'gping'        # Interactive ping tool, with graph
brew 'speedtest-cli'# Command line speed test utility

# CLI Development Suits
brew 'httpie'       # HTTP / API testing testing client
brew 'kdash'        # Kubernetes dashboard app

# CLI External Sercvices
brew 'navi'         # Browse, search, read cheat sheets

# CLI Fun
brew 'neofetch'     # Show system data and ditstro info

#############################################################
# Software Development                                      #
#############################################################

# Development Apps
cask 'boop'           # Text transformation tool
brew 'gradle'         # Build automation for Java
brew 'maven'          # Dependency manager for Java
cask 'iterm2'         # Better terminal emulator
cask 'postman'        # HTTP API testing app
cask 'visual-studio-code' # Code editor

# Development Langs, Compilers, Package Managers and SDKs
brew 'gcc'            # GNU C++ compilers
brew 'go'             # Compiler for Go Lang
brew 'openjdk'        # Java development kit
brew 'python'         # Python interpriter

# DevOps
brew 'docker'         # Containers

# Development Utils
brew 'gh'             # Interact with GitHub PRs, issues, repos
brew 'git-extras'     # Extra git commands for common tasks

# Security Utilities
brew 'bcrypt'         # Encryption utility, using blowfish
brew 'clamav'         # Open source virus scanning suite
brew 'lynis'          # Scan system for common security issues
brew 'openssl'        # Cryptography and SSL/TLS Toolkit
brew 'rkhunter'       # Search / detect potential root kits

#############################################################
# Desktop Applications                                      #
#############################################################

# Media
cask 'calibre'      # E-Book reader
cask 'spotify', args: { require_sha: false } # Proprietary music streaming
cask 'transmission' # Torrent client
brew 'pandoc'       # Universal file converter

# Personal Applications
cask '1password'      # Password manager (proprietary)
cask 'obsidian'       # Markdown notes

# Browsers
cask 'chromium', args: { require_sha: false }

#############################################################
# MacOS-Specific Stuff                                      #
#############################################################

# Fonts
tap 'homebrew/cask-fonts'
cask 'font-fira-code'
cask 'font-hack'
cask 'font-meslo-lg-nerd-font'

# # Mac OS Quick-Look Plugins
# cask 'qlcolorcode'    # QL for code with highlighting
# cask 'qlimagesize'    # QL for size info for images
# cask 'qlmarkdown'     # QL for markdown files
# cask 'qlprettypatch'  # QL for patch / diff files
# cask 'qlstephen'      # QL for dev text files
# cask 'qlvideo'        # QL for video formats
# cask 'quicklook-csv'  # QL for tables in CSV format
# cask 'quicklook-json', args: { require_sha: false } # QL for JSON, with trees
# cask 'quicklookapk',   args: { require_sha: false } # QL for Android APKs
# cask 'webpquicklook',  args: { require_sha: false } # QL for WebP image files

# Mac OS Mods and Improvements
cask 'alt-tab'        # Much better alt-tab window switcher
cask 'copyclip', args: { require_sha: false } # Clipboard manager
cask 'raycast', args: { require_sha: false }  # Spotlight alternative
cask 'santa'          # Binary authorization for securityba
cask 'stats'          # System resource usage in menubar

# Mac OS Utility Apps
cask 'coteditor'      # Just a simple plain-text editor
cask 'little-snitch'  # Firewall app viewing / blocking traffic
cask 'keka'           # File archiver and extractor
cask 'nordvpn'        # VPN Client
cask 'clocker'        # Multiple clocks
brew 'helm'
brew 'kotlin'
brew 'kubectx'
brew 'octant'
brew 'skaffold'
brew 'terraform'
cask 'google-cloud-sdk', args: { require_sha: false }
brew 'awscli'
cask 'intellij-idea'
cask 'telegram'
cask 'zoom'
brew 'yq'
brew 'k9s'

# EOF