# Tulman
Tunneling Manager - Tool to facilitate ssh tunneling bind</br>
See [example](https://github.com/choiman1559/tulman/blob/master/example/example.conf) to know how to write your own tulman configuration.

Usage:
```angular2html
Usage: "tulman {{start|stop|restart|status|help}} [ARCHIVE extension:conf]"
Arguments:
        (-s|--stub-test)    =>  Not executing commands to run ssh, but just print them out to the terminal for debug purpose.
        (-e|--disable-expr) =>  Disables all prefix syntax and scoping syntax used in conf file.
        (-d|--debug)        =>  Prints debugging logs during parsing.
```
