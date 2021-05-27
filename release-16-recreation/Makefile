all : curses.z5

curses.z5 : curses.inf house.inf
	git add *.inf
	git commit -m "Curses r16 recreation $(date '+%F %T')" && git push
	inform -xr curses.inf curses.z5
