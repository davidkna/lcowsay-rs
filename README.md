# lcowsay-rs
```
 ___________
< Hello 🌍! >
 -----------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

Cowsay, but combined with lolcat.


## Flags
```
USAGE:
    lcowsay [FLAGS] [OPTIONS] [TEXT]...

ARGS:
    <TEXT>...    [default: ]

FLAGS:
    -h, --help                    Prints help information
        --no-lolcat
    -n, --shift-sign-no-random    Don't randomize sign of col and row shift values
    -V, --version                 Prints version information

OPTIONS:
    -H, --hue <hue>                  Sets initial hue of text color in degress [default: random]
    -W, --max-length <max-length>    [default: 40]
    -f, --cow-shape <shape>          [default: cow] [possible values: clippy, cow, moose, ferris]
    -C, --shift-col <shift-col>      How many degrees to shift text color hue for every column
                                     [default: 1.6]
    -R, --shift-row <shift-row>      How many degrees to shift text color hue for every row
                                     [default: 3.2]
    -s, --style <style>              Rainbow mode [default: rainbow] [possible values: rainbow,
                                     sinebow]
