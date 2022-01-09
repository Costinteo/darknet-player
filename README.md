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

## Contributing

Open issues for bug-fixing or even pull requests if you want to fix them yourself. :)

There are still features to be made. If you have any proposals, open an issue.
