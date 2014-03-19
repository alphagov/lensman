# Lensman

Simple wrapper around webkit2png (or other command-line screengrab tool) to
take multiple screengrabs at multiple sizes easily.


## Using

1.  Copy `lensman` into your `$PATH` and ensure it is executable
1.  Create a configuration file (see `example.conf` for inspiration)
1.  Running `lensman <config_file>` will call `webkit2png` on each 
    path in the configuration file.
