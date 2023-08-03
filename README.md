# scripter

Allows the loading of commands from a commands text file into the MacOS buffer (pbcopy) based on a key word in the file.

"script" as in a movie script you write to demonstrate something on a command line. The "script" is the command listing file.

The file contents look like what's in the command.txt file, where commands are "key:command"

## usage

```
scripter key
```

Where `key` is a key from the commands input file.

`scripter` takes a `-f` flag that can be used to specify a different commands input file.

I use an alias to reference a particular command file and load up commands quickly to the buffer, and paste them into while giving a demonstration.
