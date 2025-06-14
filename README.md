# micro-cheat

A plugin for the [Micro](https://github.com/zyedidia/micro) terminal based editor to provide a markdown cheatsheet for the language you're editing.

## Usage

Edit a source code file with micro. Press **Cmd + F1**. 

A cheatsheet for the language opens. If you're editing Python, it's a Python cheatsheet. If Go, then Go cheatsheet.
Press Ctrl-Q to close the cheatsheet tab and return to editing. 

For your convenience, micro-cheat also provides a command 'cheat' that you can bind to any key or run with ctrl-E. 

<details>
        <summary><b>Tested with...</b></summary>
	<ul>
            	<li>Python</li>
		<li>Go (Golang)</li>
		<li>Lua</li>
		<li>Javascript</li>
		<li>CSS (cascading style sheets)</li>
		<li>HTML</li>
		<li>HAML (HTML abstraction markup language)</li>
		<li>Vagrantfile (by filename)</li>
		<li>Dockerfile (by filename)</li>
		<li>Makefile</li>
		<li>JavaScript (ECMAScript)</li>
		<li>TypeScript</li>
		<li>YAML (yet another markup language)</li>
		<li>BASH (shell)</li>
		<li>MarkDown</li>
		<li>SASS (by suffix)</li>
        </ul>
    </details>

## Installation

Micro-cheat is now part of official Micro plugin-channel.

	$ micro --plugin install cheat
 
 	or
  
  	With the Micro editor open:
   		Ctrl + e
     	> plugin install cheat

Alternatively, a development install

	$ cd $HOME/.config/micro/plug/
	$ git clone https://github.com/nomadicGopher/micro-cheat

## Limitations

All cheatsheets included in cheatsheets/ directory are not supported yet. Micro-cheat has only been tested on Linux. 

## Todo

* Bibtex references cheatsheet. Should be MIT licensed to be included in this plugin. 

## Adminstrivia

Cheatsheets are from https://devhints.io project, copyright (c) 2021 Rico Sta. Cruz and contributors, received under MIT license.

Micro-cheat plugin is Copyright 2022-2024 Tero Karvinen https://TeroKarvinen.com, MIT license.

Forked by [GitHub.com/nomadicGopher](https://github.com/nomadicGopher/micro-cheat), MIT license.
- Includes bug fixes & README enhancements (6/2025)
