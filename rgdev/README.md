# whaledo/rgdev

A Docker setup for creating a reproducible development environment for
working on RubyGems, because Hoe is difficult for many contributors.

Part of [whaledo-containers](https://github.com/duckinator/whaledo-containers).

## Usage

    $ pip install whaledo
    $ git clone https://github.com/rubygems/rubygems.git
    $ cd rubygems
    $ whaledo rgdev setup
    <work on code>
    $ whaledo rgdev rake test

OR:

    $ gem install rgdev
    $ git clone https://github.com/rubygems/rubygems.git
    $ cd rubygems
    $ rgdev setup
    <work on code a bit>
    $ rgdev rake test
