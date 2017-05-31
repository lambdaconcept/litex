include ../variables.mak
LDFLAGS += -lSDL2 -lSDL2_image img.o

all: img.o $(OBJ_DIR)/spartan3.so

img.o:
	ld -r -b binary -o $@ img/*.png

include ../rules.mak
