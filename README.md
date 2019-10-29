# Go snake!

This is just a small project I made in an afternoon just to write something in Golang, a great language that I love!
It's a simple snake game that uses the [termbox-go](https://github.com/nsf/termbox-go) library to build the user interface and so the game itself.

I implemented some cool options to like the speed selection and the "pacman effect" (that allows you to go through walls and end up on the other side, not related to any flat earth conspiracy).

# Play

In order to play the game you'll need to build it first.<br/>
These are the steps you have to follow:

-   Install [go](https://golang.org/dl/) if you don't have it on your system already
-   Open a terminal
-   Go into the `go-snake` directory
-   Run this command

```bash
go build -ldflags="-s -w" -o snake main.go
```

-   This will create a `snake` binary that you can execute by running `./snake`

## Have fun!

If you are a master gopher and you notice some mistake or you just want to give me some coding advice, feel free to create an issue! I'm always happy to learn something!
<br/>
<br/>
<img src="https://raw.githubusercontent.com/egonelbre/gophers/master/.thumb/animation/gopher-dance-long-3x.gif" height="150"/>
