# Valor

Subspace-alike game written in CoffeeScript/HTML5.

[Current state](http://perplexes.github.io/valor/Subspace.html)

## Other SubSpace projects

* [dotproduct](https://github.com/sharvil/dotproduct), another HTML5 SubSpace. [Play here](http://dev.nanavati.net:8000)
* [Discretion](http://ss-discretion.sourceforge.net)
* [ASSS](http://asss.minegoboom.com/)
* [Continuum](http://www.getcontinuum.com/)

## Development Setup

After cloning, run the following commands:

    yarn install
    make setup # fetch dependencies
    make compile # build
    make server & # start the game server
    make # start the web server
    
Now you can navigate to http://localhost:8000/Subspace.html to join the game.

## Contributing

* Fork the project.
* Make your feature addition or bug fix.
* Add tests for it. This is important so I don't break it in a future version unintentionally.
* Commit, do not mess with Rakefile (or Makefile), Version, or History. (If you want to have your own version, that is fine but bump version in a commit by itself -- I can ignore when I pull)
* Send me a pull request. Bonus points for topic branches.
