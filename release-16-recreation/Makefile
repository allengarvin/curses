
all : curses.z8

curses.z8 : *.inf
	inform-6.31 '$$huge' -v8 -xr curses.inf curses.z8

commit : 
	git add *.inf *.z8
	git commit -m "Curses r16 recreation $(date '+%F %T')" && git push
