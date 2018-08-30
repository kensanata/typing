# Typing of Emacs

This is a game inspired by
[The Typing Of The Dead](https://en.wikipedia.org/wiki/The_Typing_of_the_Dead)
on the Dreamcast. That game itself is a parody of
[The House Of The Dead](https://en.wikipedia.org/wiki/The_House_of_the_Dead_(video_game)).
In the latter, players use a light gun to shoot zombies and
other undead. In the former, players have to *type* the names of the
undead in order to shoot them. *The Typing Of Emacs* is the parody of
the parody, since there are no undead (except possibly for the user
staring at Emacs).

In order to install, put this file somewhere on your `load-path` and
add `(autoload 'typing-of-emacs "The Typing Of Emacs, a game." t)` to
your `~/.emacs` file (or your `~/emacs.d/init.el`).

In order to play, choose any buffer containing some text and use `M-x
typing-of-emacs` to start the game. Traditionally, the source code of
the package, the Emacs NEWS file, and the `words` file are used.

Note that this package creates a highscore list for you. The name of
the file is stored in `toe-highscore-file`. Set it to nil if you don't
want yet another dot file to clutter your home directory.
