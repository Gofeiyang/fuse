all:twofs

clean:
	rm -f twofs

twofs: twofs.c log.c
	gcc -Wall $^ `pkg-config fuse --cflags --libs` -o $@

