SRC = $(shell find ./src/ -name '*.c')
#SRC = ./src/main.c ./src/display.c
INC = ./inc

all :
	gcc $(SRC) -I$(INC) -o mainapp
	#gcc $(SRC) -I$(INC) -o mainapp
	#gcc ./src/main.c ./src/display.c  -I./inc -o mainapp

clean :
	rm -f mainapp
