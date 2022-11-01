INCLUDE_DIRS = ../inc
CFLAGS += -O2

c_kzg_4844.o: c_kzg_4844.c Makefile
	clang -DCKZG_USE_PTHREAD -Wall -I$(INCLUDE_DIRS) $(CFLAGS) -c $<
