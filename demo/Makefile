CC = gcc
CFLAGS = -I../src -Wall -Werror -Wextra -g # -O3
LIBS = ../src/libao_fec.a

demo: demo.o $(LIBS)
	$(CC) $(CFLAGS) -o demo demo.o $(LIBS)

$(LIBS): frc
	cd ../src && make

clean:
	-rm -f demo demo.o

frc:

demo.o: ../src/ao_fec.h
