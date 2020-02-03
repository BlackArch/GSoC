# BlackArch GSoC 2020 Ideas

If you have an idea for BlackArch Linux you would like to
introduce just open a pull request and discuss it with us.


Our poject ideas so far are:

- [Graphical Installer](#graphical-installer)
- [Cli installer redesign](#cli-installer)
- [Graphical package manager interface](#graphical-package-manager-interface)
- [Blackman rewrite](#blackman-redesign)
- [Python 3 Migration](#migrate-tools-to-python-3)

#### Graphical installer
Create a graphical installer, based on calamares, or similar.


#### Cli installer redesign
Redesign the command line installer with dialog.
If you chose this project you would need some shell scripting skills.
- add error handling to existing functions
- add tests to existing functions
- add dialog interface

#### Graphical package manager interface
If you decide to take this project, you would be responsible to create a graphical interface for Blackarch repositories.
- allow installation of tools from graphical front end
- allow installation from command line
- Allow additional repositories to be added

#### Blackman redesign
Blackman, the emerge like tool for BlackArch is outdated and lacks some functions.
We would like you to rewrite this tool in either Python or Rust.
Currently Blackman is written in Shell script.
With Blackman you can build BlackArch packages and it's dependencies from source.

- build BlackArch packages from source
- build BlackArch dependencies from source
- allow additional repositories to build from source

#### Migrate tools to Python 3
There are several useful tools, that rely on Python 2 as interpreter.
As Python 2 reached end of life, we would like to change it.
If you want to take up this project please name the tool(s) you would like to
port and provide a time table. Please join our discord or IRC channel.
