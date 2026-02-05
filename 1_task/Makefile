TARGET = my_program
SRC = main.c
CC = gcc
CFLAGS = -Wall -g

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

clean:
	rm -f $(TARGET)

install: all
	cp $(TARGET) /usr/local/bin/



