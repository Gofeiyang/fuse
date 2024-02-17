all: twofs

clean:
	rm -f twofs

twofs: bbfs.c log.c
	gcc -Wall $^ `pkg-config fuse --cflags --libs` -o $@
