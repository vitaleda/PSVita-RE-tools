CC=gcc
CFLAGS=-static -Os -s
LDFLAGS=
SOURCES=main.c
EXECUTABLE=kernel_bootimage_extract

all:
	$(CC) $(CFLAGS) $(SOURCES) $(LDFLAGS) -o $(EXECUTABLE)

clean:
	rm -rf $(EXECUTABLE)