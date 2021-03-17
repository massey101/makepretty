BIN = test.exe other.exe

all: $(BIN)

%.o: %.c
	cp $^ $@

%.exe: %.o
	cp $^ $@

clean:
	rm -f *.exe *.o

.PHONY: all clean
.PRECIOUS: %.o
