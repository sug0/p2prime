# p2prime

A Golang port of [peerflix](https://github.com/mafintosh/peerflix).

<img src="https://api.travis-ci.org/sug0/p2prime.svg?branch=master" />

Start watching the movie while your torrent is still downloading!
![Working of go-peerflix](./images/demo.gif)

## Installation

```sh
go get github.com/sug0/p2prime
```

## Usage

Access the stream on [http://localhost:8080/](http://localhost:8080/)
```sh
p2prime [magnet url|torrent path|torrent url]
```

To start playing in VLC:
```sh
p2prime -player vlc [magnet url|torrent path|torrent url]
```

Currently supported players are: VLC, MPlayer and MPV

## Build

```bash
go build
```

## License

[MIT](https://raw.githubusercontent.com/sug0/p2prime/master/LICENSE)
