# Lensman

Simple wrapper around webkit2png (or other command-line screengrab tool) to
take multiple screengrabs at multiple sizes easily.


## Using

1.  Copy `lensman` into your `$PATH` and ensure it is executable
1.  Create a configuration file (see `example.conf` for inspiration)
1.  Running `lensman <config_file>` will call `webkit2png` on each 
    path in the configuration file.


## Multiple widths

Lensman can grab pages at multiple widths. Currently it uses the method
in the [multiple widths][branch] on the [alphagov fork of webkit2png][fork]
as this means the page doesn't need to be reloaded over and over.

[branch]:https://github.com/alphagov/webkit2png/tree/multiple-widths
[fork]:https://github.com/alphagov/webkit2png/
