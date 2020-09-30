## References

Reference notes for the *Creating a Command Line Driven Development
Environment* talk.

Here's a direct link to [download the
slides](https://github.com/nickjj/nyhackr-cli-dev-env/raw/master/nyhackr-cli-dev-env.pdf)
and the [video is available on
YouTube](https://www.youtube.com/watch?v=-eASvILZj6w). Thanks for having me
[nyhackr](https://nyhackr.org/)!

- [Nick's Sites](#nicks-sites)
- [Parsing Data on the Command Line](#parsing-data-on-the-command-line)
- [Terminal](#terminal)
- [Open Source Projects](#open-source-projects)
- [Tmux and Vim](#tmux-and-vim)
- [Dotfiles](#dotfiles)

### Nick's Sites

#### Blog / Podcast

- <https://nickjanetakis.com>
- <https://runninginproduction.com>

#### Twitter / YouTube

- <https://twitter.com/nickjanetakis>
- <https://www.youtube.com/c/nickjanetakis>

#### Courses

- <https://diveintodocker.com>
- <https://buildasaasappwithflask.com>

### Parsing Data on the Command Line

The CSV file and command examples are [in this
directory](https://github.com/nickjj/nyhackr-cli-dev-env/tree/master/parsing-csv-example/).

- [Jeroen Janssens' talk on using the command line](https://www.youtube.com/watch?v=QxpOKbv-KQU)

### Terminal

#### Emulators

Feel free to pick a different emulator if you don't like any of the ones below.

- <https://github.com/microsoft/terminal> (Windows)
- <https://invisible-island.net/xterm/> (Linux)
- <https://github.com/gnachman/iTerm2> (macOS)
- <https://github.com/alacritty/alacritty> (Cross platform)

#### Shells

I prefer using Bash but here's a few alternative options to explore.

- <https://www.gnu.org/software/bash/>
- <https://github.com/zsh-users/zsh>
- <https://fishshell.com/>

#### Prompt / Colors

I'm all for a minimal prompt that focuses on the commands being run and their
output.

- <https://starship.rs/> (batteries included prompt if you prefer this instead)
- <https://www.gnu.org/software/bash/manual/html_node/Controlling-the-Prompt.html>
- <https://en.wikipedia.org/wiki/ANSI_escape_code#Colors>

### Open Source Projects

Here's a few open source tools I created. Feel free to use them as references.

#### Shell Scripts

- <https://github.com/nickjj/latest-releases>
- <https://github.com/nickjj/wait-until>
- <https://github.com/nickjj/invoice>
- <https://github.com/nickjj/notes>

#### Python Scripts

- <https://github.com/nickjj/webserver>
- <https://github.com/nickjj/title-case-converter>
- <https://github.com/nickjj/verdiff>

### Tmux and Vim

- [Tmux / Vim specific blog posts and videos](https://nickjanetakis.com/blog/tag/vim-tips-tricks-and-tutorials)
- [Tmux cheat sheet](https://gist.github.com/henrik/1967800)

### Dotfiles

The README file in my dotfiles repo contains installation instructions for
all of the tools that I use on the command line. It's catered towards native
Linux (Debian / Ubuntu) and WSL but there's macOS instructions too.

This link leads to the master branch of my dotfiles:

- <https://github.com/nickjj/dotfiles>

Here's a list of specific config files as they were at the time of this talk:

- [.profile](https://github.com/nickjj/dotfiles/blob/73ed4a38d66fc2a2fb45bec112680a1bae2cff75/.profile)
- [.bashrc](https://github.com/nickjj/dotfiles/blob/73ed4a38d66fc2a2fb45bec112680a1bae2cff75/.bashrc)
- [.aliases](https://github.com/nickjj/dotfiles/blob/73ed4a38d66fc2a2fb45bec112680a1bae2cff75/.aliases)
- [.tmux.conf](https://github.com/nickjj/dotfiles/blob/73ed4a38d66fc2a2fb45bec112680a1bae2cff75/.tmux.conf)
- [.vimrc](https://github.com/nickjj/dotfiles/blob/73ed4a38d66fc2a2fb45bec112680a1bae2cff75/.vimrc)

#### Notable Tools

In case something crazy happens with my dotfiles repo in the future, here's a
list of command line tools mentioned and demonstrated in the talk:

- <https://github.com/tmux/tmux>
- <https://github.com/vim/vim>
- <https://github.com/junegunn/fzf>
- <https://github.com/BurntSushi/ripgrep>

#### Getting set up with WSL 2

This video goes over my entire WSL 2 set up and also includes non-command line
tools that I use on Windows. It's basically a 30 minute drive-by of everything
I use and how I have everything configured.

- <https://nickjanetakis.com/blog/a-linux-dev-environment-on-windows-with-wsl-2-docker-desktop-and-more>

Also, here's a [a complete list of all of the tools I
use](https://nickjanetakis.com/blog/the-tools-i-use) on Windows in text form.

#### Dotfiles Management

If you don't want to use symlinks, there are dedicated tools such as
<https://yadm.io/> and many others.

Also, check out the [XDG Base Directory
Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html)
to learn more about where user specific files should go.
