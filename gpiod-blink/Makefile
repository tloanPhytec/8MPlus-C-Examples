PROJ=libgpiod-led
SRC=gpiod-blink.c
LIBS=-lgpiod
CFLAGS=-D CONSUMER=\"$(PROJ)\"

all:
	$(CC) $(SRC) $(LIBS) $(CFLAGS) -o $(PROJ)

clean:
	rm $(PROJ)
