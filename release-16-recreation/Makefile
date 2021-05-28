all : curses.z5

curses.z5 : *.inf
	inform -xr curses.inf curses.z5

commit : 
	git add *.inf
	git commit -m "Curses r16 recreation $(date '+%F %T')" && git push
