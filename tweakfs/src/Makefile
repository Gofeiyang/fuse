all: tweakfs

clean:
	rm -f tweakfs

tweakfs: tweakfs.c log.c
	gcc -Wall $^ `pkg-config fuse --cflags --libs` -o $@

