# conway-php

Conway's Game of Life in PHP.

![glider gun](doc/gosper-glider-gun.gif)

## Usage

### Run

To run an example, just execute the `run` command and pass the file containing
the world definition.

    $ bin/conway run examples/gosper-glider-gun.php

## Gif

You can render a run into an animated gif using the `gif` command. It's a good
idea to provide the number of generations with `-n`.

    $ bin/conway gif -n 300 examples/gosper-glider-gun.php doc/gosper-glider-gun.gif

Note that performance is quite sluggish. On this machine it takes about 40
seconds to render 300 generations on the standard size grid of 120x50 cells.

## Installation

The `gif` command requires [gifsicle](http://www.lcdf.org/gifsicle/) to be
installed.

## Further reading

* [Conway's Game of Life - Wikipedia](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
* [LifeWiki](http://www.conwaylife.com/wiki/Main_Page)
* [Life Lexicon](http://www.argentum.freeserve.co.uk/lex.htm)
* [Golly](http://golly.sourceforge.net/)

## Thanks

* [@__edorian](https://twitter.com/__edorian) for inspiration and hospitality
