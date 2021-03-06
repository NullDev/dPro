# dPro

<p align="center">
<img height="150" width="auto" src="https://raw.githubusercontent.com/NullDev/dPro/master/src/icon/icon-full.png" /><br>
:bar_chart: dPro Analytics and Statistics
</p>

## :information_source: About

This is/was a school project for the [HTL Bulme](http://bulme.at) where a water bottle with logging functionality was built. <br>
The repository here includes the code for the software which reads out the data of the bottle. 

**Website:** [https://dpro.at/](https://dpro.at/)

## :camera: Screenhots 

<p align="center">
<br>
<div style="display:flex;">
<img height="275" width="auto" src="https://raw.githubusercontent.com/NullDev/dPro/master/demo/screen1.png" />
<img height="275" width="auto" src="https://raw.githubusercontent.com/NullDev/dPro/master/demo/screen2.png" />
</div>
<br>
</p>

<hr>

## :bulb: Usage

**No** deployment version yet and you need [electron](https://electronjs.org/) installed. <br>

0. Open up your terminal (and navigate somewhere you want to download the repository to) <br><br>
1. Make sure you have nodejs installed. Test by  entering <br>
$ `node -v` <br>
If this returns a version number, NodeJS is installed. **If not**, get NodeJS [here](https://nodejs.org/en/download/package-manager/)</a>. <br><br>
2. Make sure electron is installed <br>
$ `electron -v` <br>
If this returns a version number, Electron is installed. **If not**, get it by typing <br>
$ `sudo npm install -g electron` <br><br>
3. Clone the repository and navigate to it. You can either download it [here](https://github.com/NullDev/dPro/archive/master.zip) or if you have Git installed, type <br>
$ `git clone https://github.com/NullDev/dPro.git && cd dPro` <br><br>
4. Install all dependencies <br>
$ `npm install` <br><br>
5. Wait for it to finish. After installation is done, run the programm with <br>
$ `npm start` <br><br>
6. (Optional): To enable debugging mode and skip the splash screen type <br>
$ `npm test` <br>

<hr>

## :wrench: CLI Arguments

The script takes sever CommandLine Arguments

| Argument | Alias | Function |
| -------- | ----- | -------- |
| `--debug` | `-d` | Enables debugging features such as resizeable screen and "inspect elements". |
| `--skip-splash` | `-s` | Skips the splash screen and jumpts to the main window instantly. |
| `--low-res` | `-l` | Does not load some CSS definitions and animations. |

<hr>

## :copyright: Copyright

`Copyright (c) NullDev`
