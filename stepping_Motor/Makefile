CC=gcc
CFLAGS= -g -Wall  
LDLIBS= -lpigpiod_if2 -pthread
all:singlePhaseForward singlePhaseBackward doublePhaseForward doublePhaseBackward halfStepForward halfStepBackward

singlePhaseForward:singlePhaseForward.o
singlePhaseBackward:singlePhaseBackward.o
doublePhaseForward:doublePhaseForward.o
doublePhaseBackward:doublePhaseBackward.o
halfStepForward:halfStepForward.o
halfStepBackward:halfStepBackward.o



clean:
	rm -f *.o*~ singlePhaseForward singlePhaseBackward doublePhaseForward doublePhaseBackward halfStepForward halfStepBackward
