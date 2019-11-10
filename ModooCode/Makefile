CC = g++
CFLAGS = -W -Wall
TARGET = main

$(TARGET) : ch6_2_Virtual.o main.o
		$(CC) $(CFLAGS) -g -o $(TARGET) ch6_2_Virtual.o main.o

ch6_2_Virtual.o : ch6_2_Virtual.cpp
		$(CC) $(CFLAGS) -g -c -o ch6_2_Virtual.o ch6_2_Virtual.cpp

main.o : main.cpp
		$(CC) $(CFLAGS) -g -c -o main.o main.cpp

clean :
		rm *.o main						