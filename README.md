getup
=====

By Rémino Rem <https://remino.net/>

Get up and run some things.

- [Description](#description)
- [Installation](#installation)
	- [Using Homebrew on macOS](#using-homebrew-on-macos)
	- [Using Git](#using-git)
	- [Using cURL](#using-curl)
- [Usage](#usage)
- [Manual Settings](#manual-settings)

## Description

This is a personal script to help me set up common things on a new computer,
usually a Mac. Instead of having to remember all the steps to set up everything,
I copy this script to the new computer and run it, or just run the parts I need.

This script is not meant to be run as root, but it will ask for your password
when it needs to.

## Installation

### Using Homebrew on macOS

```sh
brew tap remino/remino
brew install getup
getup
```

### Using Git

```sh
git clone git@github.com:remino/getup.git
cd getup
./getup
```

### Using cURL

```sh
curl -sL https://raw.githubusercontent.com/remino/getup/master/getup > getup
chmod a+x getup
./getup
```

## Usage

```
getup 1.2.0

Usage: getup [<options>] <command>

Get up and run some things.

SETUP PORTIONS:

	asdf          Install asdf and pugins.
	brewapps      Install Homebrew apps (non-cask).
	brewcask      Install Homebrew cask apps.
	crontab       Install crontab.
	darkmode      Enable Dark Mode. (macOS only.)
	dotfiles      Clone and set up dot files using yadm from DOTFILES_REPO_URL.
	dock          Set up Dock. (macOS only.)
	cleanup       Clean up after setup.
	finder        Set up Finder. (macOS only.)
	gcloud        Install GCloud.
	gpg           Import private GPG key.
	homebrew      Install Homebrew (not apps).
	masapps       Install Mac App Store apps using mas. (macOS only.)
	mkdirs        Create extra empty dirs.
	ohmyzsh       Install Oh My Zsh.
	omzplugins    Install Oh My Zsh custom plugins.
	pamtouchid    Enable Touch ID for sudo via PAM. (macOS only.)
	python        Install Python 2 and Python 3 using asdf.
	reminoutils   Clone and link Rémino util repos.
	safari        Set up Safari. Includes: safaridev. (macOS only.)
	safaridev     Enable Develop menu in Safari. (macOS only.)
	secrets       Clone secret files from git repo at SECRETS_REPO_URL.
	settings      Set up macOS preferences. Includes: dock, finder, safari.
	shell         Change default shell to Zsh.
	sshkey        Add setup SSH key.
	workspace     Clone and set up workspace from WORKSPACE_REPO_URL.

COMMANDS:

	all           Setup all the portions listed above.
	config        Show options set by .getuprc.
	fulldisk      Check whether or not script has Full Disk Access.
	help          Show this help screen.
	prep          Generate blank .getuprc option file in current directory.
	update        Update script itself.
	version       Show version.

OPTIONS:

	-h            Show this help screen.
	-v            Show version.

```

## Manual Settings

This script cannot set up everything. For what I normally have to set manually,
see [Manual Settings](settings.md).
