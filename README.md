# shortest-C-coredump
quick (and shortest?) way to coredump C with GCC (default settings)

# build locally
```
$ : git clone https://github.com/cristeigabriel/shortest-C-coredump;
$ : cd shortest-C-coredump/;
$ shortest-C-coredump/: gcc coredump.c
```

# run
```
$ shortest-C-coredump/: ./a.out
```

# explaination
this example tries to call an inexistent/unreadable memory address by prototyping it to a callable function, this resulting in a coredump
