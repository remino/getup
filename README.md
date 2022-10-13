getup
=====

By Rémino Rem <https://remino.net/>

Get up and run some things.

## Installation

```sh
brew tap remino/remino
brew install getup
```

## Usage

```
getup 1.0.0

Usage: getup [<options>] <command>

Get up and run some things.

SETUP PORTIONS:

	asdf          Install asdf and pugins.
	brewapps      Install Homebrew apps (non-cask).
	brewcask      Install Homebrew cask apps.
	crontab       Install crontab.
	darkmode      Enable Dark Mode.
	dotfiles      Clone and set up dot files using yadm from DOTFILES_REPO_URL.
	dock          Set up Dock.
	cleanup       Clean up after setup.
	finder        Set up Finder.
	gcloud        Install GCloud.
	gpg           Import private GPG key.
	homebrew      Install Homebrew (not apps).
	masapps       Install Mac App Store apps using mas.
	mkdirs        Create extra empty dirs.
	ohmyzsh       Install Oh My Zsh.
	omzplugins    Install Oh My Zsh custom plugins.
	pamtouchid    Enable Touch ID for sudo via PAM.
	python        Install Python 2 and Python 3 using asdf.
	reminoutils   Clone and link Rémino util repos.
	safari        Set up Safari. Includes: safaridev.
	safaridev     Enable Develop menu in Safari.
	secrets       Clone secret files from git repo at SECRETS_REPO_URL.
	settings      Set up macOS preferences. Includes: dock, finder, safari.
	shell         Change default shell to Zsh.
	sshkey        Add setup SSH key.
	workspace     Clone and set up workspace from WORKSPACE_REPO_URL.

COMMANDS:

	all           Setup all the portions listed above.
	fulldisk      Check whether or not script has Full Disk Access.
	help          Show this help screen.
	version       Show version.

OPTIONS:

	-h            Show this help screen.
	-v            Show version.

```
