Laptop
======

Laptop is a script to set up an OS X laptop for web development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Requirements
------------
Must have Xcode installed.

We support:

* OS X Mavericks (10.9)
* OS X Yosemite (10.10)
* OS X El Capitan (10.11)

Older versions may work but aren't regularly tested. Bug reports for older
versions are welcome.

Install
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/gtoma4/laptop/master/mac
less mac
sh mac 2>&1 | tee ~/laptop.log
```

Optionally, [install thoughtbot/dotfiles][dotfiles].

[dotfiles]: https://github.com/thoughtbot/dotfiles#install
