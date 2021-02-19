# Google Summer of Code (GSoC) 2021 - BlackArch Linux

This page contains information on BlackArch’s participation in Google Summer of Code (GSoC). 
Feel free to contact us for clarifications and more information.


You can reach out to us via [email](mailto:team@blackarch.org), 
[IRC](https://webchat.freenode.net/#blackarch) or [Discord](https://discord.gg/xMHt8dW).

> If you have an idea for BlackArch Linux you would like to introduce, 
> please open a pull request and discuss it with us.

## What can I do today?
BlackArch is still in the process of applying to be a mentoring organization. 
While we wait for a response from Google OSPO, please read the 
[GSoC Student Guide](https://google.github.io/gsocguides/student/)

## Project Ideas

If you are a student looking forward to participating in Google Summer of Code with BlackArch,
please browse this idea list.
__Note that there may be additional ideas added during the application period.__

Do not hesitate to contact the mentors or contributors listed on this page 
for any questions or clarification. You can find helpful people on our 
communication channels.


## Idea List

- [CLI installer redesign](#cli-installer)
- [Graphical package manager interface](#graphical-package-manager-interface)
- [Blackman rewrite](#blackman-redesign)
- [Python 3 Migration](#migrate-tools-to-python-3)
- [BlackArch on WSL](#create-wsl-blackarch-package)
- [BlackArch Template for Qubes OS](#create-qubes-os-template)
- [Blackarch Tool documentation](#blackarch-tool-documentation)
- [Search Tool for BlackArch packages](#search-tool-for-blackarch-packages)
- [None of the above](#none-of-the-above)

### CLI installer redesign

* **Difficulty**  : Intermediate
* **Technology**  : Linux, Bash, Scripting
* **Mentor(s)**   : _TBD_

#### Description

The current CLI installer is pretty straight forward, and gets the job done.
However, as BlackArch aims to become more user friendly, especially during the install process, 
we need to make sure that all edge cases are handled and accidental exits (during partitioning, locale selection, etc.)
are handled gracefully.

Overall, goal of this project is to improve the usability, user experience and features of the installer.

#### Deliverables

As a GSoC intern, you will be responsible for:
- Gathering community feedback on CLI installer
- Enhancing the overall 'look and feel' of the CLI installer
- Adding additional tests, checks and error recovery mechanisms
- Implemeting dialog interface
- Scripting in ability to resume installations _(streach goal)_

---

### Graphical package manager interface

If you decide to take this project, you would be responsible to create a graphical interface for Blackarch repositories.
- allow installation of tools from graphical front end
- allow installation from command line
- allow additional repositories to be added

### Blackman redesign

Blackman, the emerge like tool for BlackArch is outdated and lacks some functions.
We would like you to rewrite this tool in either Python 3 or Rust.
Currently Blackman is written in Shell script.
With Blackman you can build BlackArch packages and it's dependencies from source.

- build BlackArch packages from source
- build BlackArch dependencies from source
- allow additional repositories to build from source

### Migrate tools to Python 3

There are several useful tools, that rely on Python 2 as interpreter.
As Python 2 reached end of life, we would like to change it.
If you want to take up this project please name the tool(s) you would like to
port and provide a time table. Please join our discord or IRC channel for
further discussion prior.


### Create WSL BlackArch package

Windows Subsystem for Linux allows user to run a Linux distribution under Windows. 
It would be handy to have the full power of the BlackArch repository available under Windows using WSL.
Therefore you would need to create the base structure with automation for updates in mind and documentation for users and developers alike.

### Create Qubes OS Template

Qubes OS uses a strong isolation to provide security with Xen-based virtualization. There have been user requests to add a template for BlackArch on Qubes Is template system.
Therefore you would need to create the template itself with automation for updates in mind. In addition you should create documentation for user and developers alike.


### Blackarch Tool documentation

Currently BlackArch provides a guide on how to get started, but none for the individual tools. 
Therefore it would be up to you to extract the instructions on how to use each tool from the projects side and make them available in Markdown as well as on our website. Your software should be designed in a way, that it can handle most new packages without problems as well.


### Search Tool for BlackArch packages

Often potential user reach out over our communication channels to ask if a certain tool is available, or certain techniques are supported with tools on BlackArch.
Therefore you would create a search tool for the package repository based on tool names and keywords.
In addition these tools should show the version available online and available in the BlackArch repository.

### None of the above
Your favorite idea isn't in here? Feel free to open a Pull Request and explain your idea to us, or join our irc/matrix/discord and talk to us.
