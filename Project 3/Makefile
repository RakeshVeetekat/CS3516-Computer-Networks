CC = gcc
CFLAGS = -g -Wall

all: project3

project3: project3.o node0.o node1.o node2.o node3.o helper.o
	$(CC) $(CFLAGS) project3.o node0.o node1.o node2.o node3.o helper.o -o project3

project3.o: project3.c
	$(CC) $(CFLAGS) -c project3.c

node0.o: node0.c
	$(CC) $(CFLAGS) -c node0.c

node1.o: node1.c
	$(CC) $(CFLAGS) -c node1.c

node2.o: node2.c
	$(CC) $(CFLAGS) -c node2.c

node3.o: node3.c
	$(CC) $(CFLAGS) -c node3.c

node_helper.o: helper.c
	$(CC) $(CFLAGS) -c helper.c

clean:
	rm -rf project3
	rm -rf *.o
