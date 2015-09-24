# ppa-tools

Manipulate PPA's individually or in bulk from the command line and via GUI.

Installation
------------

To install scripts locally:

    install ppa-cli ppa-tool $HOME/.local/bin

To install scripts to the computer:

    sudo install ppa-cli ppa-tool /usr/local/bin

Requirements
------------

To make use of `ppa-tool`, ensure the following package is installed on your system:

    yad

You can do the following to install a recent version of `yad`:

    sudo add-apt-repository ppa://nilarimogard/webupd8
    sudo apt-get update
    sudo apt-get install yad

Usage
-----

`ppa-tool` is a GUI tool that can be used to add, remove, or list PPA's.

`ppa-cli` is a command-line tool that can be used to add or remove individual PPA's. Additionally, and potentially most usefully, it can be used to manipulate PPA' in bulk.

To list all installed PPA's to STDOUT:

    ppa-cli list

To backup a list of all installed PPA's to FILE

    ppa-cli list > FILE

To install a list of PPA's from FILE:

    ppa-cli install FILE

License
-------

Copyright (c) 2015 Six <brbsix@gmail.com>

Licensed under the GPLv3 license.
