# better-shell

Where to find better shell resources?

Shell programming, in `/bin/sh`, is great.
The command line is powerful, and you can harness the same power both interactively and in scripts.
It's at the heart of Unix, and it binds everything together.
We'll still be shell programming in 100 years' time (for better or worse).

The problem with shell programming is that it all started 40 years ago;
it has acquired features, folklore, and hacks in an incremental piecemeal fashion.
In the good old days, computers were bad, and we had to do bad things to make them good.
We no longer have to do those things, but a lot of the habits picked up by beardy Unix wizards have stuck and you still see them in shell programs today.
There are web pages that tell you how to write a shell script that works both on a Sun SPARC II running SunOS 4.0.4 and on an IBM RS6000 running AIX 4.3 and it's still possible to find them when searching for advice.

So, how do we find resources that give good advice for modern shell progamming?

The book that starts it all off for me is «[The KornShell Command and Programming Language](https://www.amazon.co.uk/dp/0135169720/)».
Yes it's ancient (1988, there is a newer edition that I haven't read), but `KornShell` kicked off the modern shell programming movement.
People mostly use `bash` nowadays, but `KornShell` was a heavy influencer of the POSIX standard so a lot of stuff works in both (and indeed, other) shells.

