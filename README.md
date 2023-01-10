# My-Notes
## Valgrind
Use the valgrind as a wrapper for running the binary and perform stress testing:<br>
	**valgrind --leak-check=yes --log-file=valgrind.rpt a.out**<br>
Memory access checking is enabled by default. The --leak-check option runs the memory leak detector when the binary exits. If you specify its value as summary, it reports how many leaks occurred. A value of full or yes displays the details of each individual leak.
