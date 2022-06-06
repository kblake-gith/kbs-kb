<p align="center">
    <img src="img/kb_logo.png?raw=true" width="200"/>
</p>

# kb. A minimalist knowledge base manager

Forked from [gnebbia/kb](https://github.com/gnebbia/kb)

## Purpose

Cheatsheets are helpful, but only when everyone on a team is using the
same cheatsheet, and that content is maintained and kept accurate.

That's what this tool does:


- collects cheatsheets with standardized info and processes in an
  organized knowledge base
- makes the knowledge base easy to share
- keeps the knowledge base up-to-date 

## Installation

**You should have Python 3.6 or above installed.**

```sh
python --version
```

If you have Python 3.6 or higher installed, just type:
```sh
 pip install -U git+https://github.com/ryandeussing/kb.git@40d361d420baab260e6a57a21f4908f1a8a283ee
```

If that worked, you've installed kb - but your knowledge base is empty.

### Import the Insights Docs knowledge base

To import the Insights Docs knowledge base:

1. download the most recent knowledge base archive

2. import the archive with this command:

```sh
kb import {path-to-file-that-ends-in-tar.gz}
```


## Usage



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
