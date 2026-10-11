CC     = gcc
CFLAGS = -Wall -Wextra -O2
TARGET = perfmon
SRCS   = main.c

$(TARGET): $(SRCS)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRCS)

clean:
	rm -f $(TARGET) *.o

.PHONY: clean
