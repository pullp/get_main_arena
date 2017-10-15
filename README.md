# get_main_arena
simple script to get main arena offset to a given libc

# usage
First, install pwntools.
Then, use this like this:
```
./main_arena_offset [libc name]
```

# example
```
./main_arena_offset /usr/lib/libc.so.6
[+] finding offset...: main arena offset:0x39fae0
```
