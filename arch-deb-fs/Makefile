CC=gcc
CFLAGS=`pkg-config --cflags gtk+-3.0 fuse3`
LIBS=`pkg-config --libs gtk+-3.0 fuse3`

all: fs_gui

fs_gui: src/main.o
	$(CC) -o $@ $^ $(LIBS)

src/main.o: src/main.c
	$(CC) $(CFLAGS) -c -o $@ $<

clean:
	rm -f src/*.o fs_gui
