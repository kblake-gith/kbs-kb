# kb. A minimalist knowledge base manager

Forked from [gnebbia/kb](https://github.com/gnebbia/kb)

## Purpose

Cheatsheets are helpful, especially everyone on a team is using the
same cheatsheets.

--- 
## Installation

### Make sure you're running a current version of Python

```sh
python --version
```

If you don't have **Python 3.6** or above installed, ask for help.


### Step 1: Clone this repo and checkout the last stable release

1. In the local directory you use to store repos:

```sh
git clone git@github.com:ryandeussing/kb.git
```

2. Checkout the last stable release:

```sh
git checkout v0.1.6
```

### Step 2: Install the `kb` app dependencies

*cd into the the `kb` directory you just cloned* and then run the command for your operating system

A. On MacOS:

```sh
pip3 install -r requirements.txt
```

B. On RHEL CSB:

```sh
sudo pip3 install -r requirements.txt
```

### Step 3: Install the `kb` app

Run the command for your operating system

A. On MacOS:

```sh
python setup.py install
```

B. On RHEL CSB:

```sh
sudo python setup.py install
```

### Step 4: Make sure your PATH is setup 

Quit and restart your terminal.

Then run the command

```sh
kb -h
```

If that doesn't print out a list of commands, ask for help. 


### Step 5: Setup and test sync 

1. Remove any `~/.kb` directory that may exist

```
rm -rf ~/.kb
```

2. Clone our shared cheatsheets into a `~/.kb` directory

```sh
git clone git@github.com:ryandeussing/kbsync.git ~/.kb
```

3. Open a new terminal window and run

```sh
kb list
```

If you don't see a list of cheatsheets, ask for help.

4. Sync changes

```sh
kb sync pull
```

If you don't see `Repository correctly synchronized from remote!`, ask for help.


### Usage

`kb list` will list the cheatsheets in the knowlege base

`kb view 0` will print out the contents of the cheatsheet in position 0

Note, it may be useful to us `kb` in a separate terminal tab so cheatsheet
content doesn't interrupt your terminal workflow.

---
#### COPYRIGHT

Copyright 2020 Giuseppe Nebbione.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
