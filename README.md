WoT-Battle-Results-To-JSON 
------------------------------------
Version 9.10 / wotbr2j.pyc

* Author: Marius Czyz aka Phalynx
* Contact: marius.czyz@gmail.com
* Website: http://www.vbaddict.net
* Wiki: http://wiki.vbaddict.net
* Repo: https://github.com/Phalynx/WoT-Battle-Results-To-JSON
* Binaries: http://www.vbaddict.net/content/39-Battle-Results-to-JSON-Parser
* tanks.json and maps.json: https://github.com/Phalynx/WoT-Dossier-Cache-to-JSON


## Respect for my work
Please respect my work invested in this project. You have to give me credit on your application or website.

## Supported Versions
	* WoT 0.8.0 up to WoT 0.9.10
	
## Requirements

### Python
* You need Python 2.7, or just use the compiled version wotbr2j.exe

## Usage
	wotbr2j.pyc <battleresult.dat>

Example:
	python.exe wotbr2j.pyc 314161038711889.dat

## Output
	wotbr2j.pyc creates a text file with the name of the battle result where the extension has been replaced by ".json"

## Structure:
	* parser[result] = "ok" or "error"
	* parser[message] = detailed error, otherwise "ok"