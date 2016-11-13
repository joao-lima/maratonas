FLAGS=-O2 

CC=icc

RM=rm -f

EXEC=3sat

all: $(EXEC)

$(EXEC):
	$(CC) $(FLAGS) 3sat.c -c -o 3sat.o
	$(CC) $(FLAGS) 3sat.o -o $(EXEC)

run:
	./$(EXEC) < input

clean:
	$(RM) 3sat.o $(EXEC)
