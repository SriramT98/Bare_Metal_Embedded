CC=arm-none-eabi-gcc
MARCH=cortex-m4
CFLAGS= -c -mcpu=$(MARCH) -mthumb -std=gnu11 -O0

main.o:main.c
	$(CC) $(CFLAGS) $^ -o $@
