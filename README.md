# mkdocs
Simple Docker container to build your [mkdocs](https://github.com/mkdocs/mkdocs)

I wrote this because I like mkdocs but I didn't want to introduce a global python dependency into
my node project and install it on my CI server. Docker to the rescue.

##usage

From your mkdocs directory:

    docker run -v `pwd`:/mkdocs csats/mkdocs build

That'll build it into a "sites" directory. You're done!
