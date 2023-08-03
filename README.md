# scripter

Allows the loading of commands from a commands text file into the MacOS buffer (pbcopy) based on a key word in the file.

The file contents look like what's in the command.txt file, where commands are "key:command"

## usage

```
scripter key
```

Where `key` is a key from the commands input file.

`scripter` takes a `-f` flag that can be used to specify a different commands input file.
