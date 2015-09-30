.PHONY : all clean

player : player.c
	gcc -g -c -I ~/jin/hw0923/include player.c -o player.o
	gcc -o player -L ~/jin/hw0923/lib player.o -lfuncs

clean :
	rm -f *.o player
