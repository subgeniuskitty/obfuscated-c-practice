# Uncomment these lines to use GCC.
CC      := gcc
CC_OPTS := -trigraphs -w

# Uncomment these lines to use Clang.
#CC      := cc
#CC_OPTS := -trigraphs -Wno-everything

################################################################################

all:
	@$(CC) $(CC_OPTS) -o main main.c

clean:
	@rm -f main main.core

run: all
	@./main
