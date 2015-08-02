# 42fs
42 - the ultimate filesystem of life, the universe and everything.

# Usage

Don't forget to install `fusepy`:

    # pip3 install fusepy

Then create some source:

    $ mkdir /tmp/src /tmp/dst
    $ echo "Hello, world!" > /tmp/src/file
    $ mkdir /tmp/src/dir

And then just mount and use:

    $ ./42fs /tmp/src /tmp/dst
    $ ls /tmp/dst
    dir  file
    $ cat /tmp/src/file
    Hello, world!
    $ cat /tmp/dst/file
    42

That's it.

The Ultimate Filesystem of Life, the Universe, and Everything.
