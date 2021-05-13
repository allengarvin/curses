Curses was written by Graham Nelson between 1993 and 1995 in versions
of Inform between 1 and 6, a simple C-like programming language for
interactive fiction. That language was the ancestor of today's Inform 7,
but it's a very different experience to read (or to write). For more on
that early language, see:

https://www.inform-fiction.org/manual/download_dm4.html

The original source code has been lost.  According to
https://www.filfre.net/2019/11/new-tricks-for-an-old-z-machine-part-2-hacking-deeper-or-follies-of-graham-nelsons-youth/,
in Graham's words:

        To my great regret, the source code for Curses is now lost. It
        was for a while on a disk promisingly labelled “Curses source
        code”, but that disk is unreadable, and not for want of
        trying. Somewhere in my many changes of address and computer,
        I lost the necessary tech, or damaged it. (And Jigsaw too,
        alas.) It wouldn’t be hard to resurrect something, by working
        from a disassembly of the story file: there’s actually a
        tool to turn story files into Inform 6 out there somewhere. I
        occasionally think of asking if anyone would like to do that,
        and perhaps produce a faithful Inform 7 implementation.

This is a fairly faithful attempt to recreate Curses by decompiling
the original byte code, and then recreating it in the latest version of
Inform 6 (with the most recent Inform library). It is divided
into each public release, from the original release 7, announced on
rec.arts.int-fiction in the Spring of 1993, until the final, far larger
release 16 in 1995.
