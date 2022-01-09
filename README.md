# Darknet Player

A Bash tool to download and play episodes of Jack Rhysider's podcast, Darknet Diaries, in the terminal.

Check out [Jack's website](https://darknetdiaries.com/).

Support him on [his Patreon](https://www.patreon.com/darknetdiaries), if you like the podcast!

## Dependencies

The versions are purely orientative. It's just what I had when I wrote it and tested it. It most likely works with older versions too. Open an issue if you tested it on an older version of any of those and I'll update the dependencies.

```
bash 5.1.8
wget 1.21
mpv  0.33.1
```

## Installation

Firstly, make sure all the above dependencies are installed. Afterwards, at the command-line:

```
$ git clone https://github.com/Costinteo/darknet-player.git
$ cd darknet-player
$ cp darknet-player /usr/local/bin/
# you can change the destination (/usr/local/bin) to any place on PATH
# to check path use:
$ echo $PATH
```

## Usage

Runing ``$ darknet-player -h`` will print out this usage text:


```
Usage: darknet-player [OPTIONS]...
Download and play Darknet Diaries episodes in the terminal.

Options:
    -h, --help               print this text and exit
        --license            print license and exit
        --no-color           suppress colored output
    -p, --play <EP>          download & play episode <EP>
    -k, --keep               don't remove episode after playing

Darknet Diaries is made by Jack Rhysider. <https://darknetdiaries.com/>
The script is written by Costinteo. <https://github.com/Costinteo>
Licensed under GNU GPL v3. <https://www.gnu.org/licenses/gpl-3.0.en.html>
```

## Contributing

Open issues for bug-fixing or even pull requests if you want to fix them yourself. :)

There are still features to be made. If you have any proposals, open an issue.
