# gotetris: Tetris Written in Go

This is a console-based version of Tetris written in Go.

![alt text][logo]
[logo]: https://raw.githubusercontent.com/jjinux/gotetris/master/screen_shot.png "Screen shot"

## Install

	go get github.com/jjinux/gotetris

## Working on the Code

See [How to Write Go Code](https://golang.org/doc/code.html).

Setup your Go workspace:

	mkdir -p gotetris/src/github.com/echochio-tw
	cd gotetris
	(cd src/github.com/echochio-tw &&
	  git clone https://github.com/echochio-tw/gotetris.git)

	# Do this each time to work on the code from the top-level
	# gotetris directory.
	export GOPATH=`pwd`
	export PATH=$PATH:$GOPATH/bin

	# Install dependencies.
	go get -u github.com/nsf/termbox-go

Build:

	go install github.com/echochio-tw/gotetris

Execute:

	gotetris

## Credits

gotetris is built on top of the excellent
[termbox-go](https://github.com/nsf/termbox-go) library.

It was inspired by [Alexei Kourbatov](http://www.javascripter.net) as
well as my port of [Tetris to Dart](http://code.google.com/p/tetris-in-dart/).
