workstation-bootstrapper
========================

Setting up a new machine is a PTA. This makes it easier.

The script itself installs only the basics like homebrew and rvm.
However, a dotfiles repository can be provided that can be automatically
installed.

## Usage

zsh < <(curl -s https://raw.github.com/effkay/workstation-bootstrapper/master/bootstrap.sh)

## Inspired by and with snippets from:

- puppet-workstation: https://github.com/effkay/puppet-workstation

- mathiasbynens OSX dotfiles:
  https://github.com/mathiasbynens/dotfiles/blob/master/.osx?os-x-10.8

- Various Thoughtbot resources:

  - Playbook:
    http://playbook.thoughtbot.com/tooling-development-process/laptop/

  - Laptop Install Script:
    https://github.com/thoughtbot/laptop/blob/master/mac

  - The Hitchhiker’s Guide to Riding a Mountain Lion:
    http://robots.thoughtbot.com/post/27985816073/the-hitchhikers-guide-to-riding-a-mountain-lion

