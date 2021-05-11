First Formal System
===================

Render PDF
----------

```
$ cp *.ttf ./local/share/fonts
$ sudo apt install texlive-full
$ sudo fc-cache -f
$ fc-match Geometria
```

```
$ cd tex/dissertation/monography
$ make
```

