CC=gcc
CFLAGS= -g -Wall  -I/opt/ucc/include
LDFLAGS= -L/opt/ucc/lib
LDLIBS= -lpigpioErr -lpigpiod_if2  -pthread
all:dac

dac:dac.o

clean:
	rm -f *.o*~ dac dac.o
run:
	  ./dac
