# piano-rs

Play piano in the terminal using PC keyboard.

## Screenshots

<img src="http://i.imgur.com/33s2XDW.png" width="900">

## Compiling

```
$ git clone https://github.com/ritiek/piano-rs
$ cd piano-rs
$ cargo build --release
```
## Usage

Once it compiles, run the binary in `./target/release/piano-rs`:

```
$ ./target/release/piano-rs -h

Play piano in the terminal using PC keyboard.

USAGE:
    piano-rs [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -c, --color <COLOR>          Color of block to generate when a note is played (Default: "red")
    -d, --duration <DURATION>    Duration to play each note for, where 0 means till the end of note (Default: 0)
    -s, --sequence <SEQUENCE>    Frequency sequence from 0 to 5 to begin with (Default: 2)
```

- Press keys on your PC keyboard to play the notes.
- Adjust note frequency while playing using <kbd>←</kbd> and <kbd>→</kbd>.
- Adjust note duration while playing using <kbd>↑</kbd> and <kbd>↓</kbd>.

## Resources

- piano-rs uses the same notes and key bindings as [multiplayerpiano.com](http://multiplayerpiano.com).

- You can use this [paste](https://pastebin.com/CX1ew0uB) to learn to play various popular songs.

## License

`The MIT License`
