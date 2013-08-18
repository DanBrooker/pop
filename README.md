# pop
### pop some files into existence 

I'm pretty sure you need a 1MB file of a's, perhaps a Gigabyte, why not a Terrabyte.

## disclaimer

I have no idea how long it would take to allocate a Terrabyte or if your computer can actually handle it.

## install

pop is a [ruby script][bin], for creating files of a specific size.
Add it to your dotfiles or check out [mine][dotfiles].

## usage

Just run `pop` and pass in a size and file

    $ pop 1MB file.txt
    > Populated file.txt with 1048576 bytes
  
    $ pop 1.15GB file.txt
    > Populated file.txt with 1342177280 bytes

Invoke help with `pop -h`.

    $ pop -h
    > USAGE: pop <size>[,B,KB,MB,GB] <filename>

[dotfiles]: https://github.com/danbrooker/dotfiles
[bin]:      https://github.com/danbrooker/pop/blob/master/pop
