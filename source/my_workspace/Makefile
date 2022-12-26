CC=arm-none-eabi-gcc
MARCH=cortex-m4
CFLAGS= -c -mcpu=$(MARCH) -mthumb -std=gnu11 -Wall -O0

all:main.o led.o STM32_startup.o

main.o:main.c
	$(CC) $(CFLAGS) $^ -o $@

led.o:led.c
	$(CC) $(CFLAGS) $^ -o $@

STM32_startup.o:STM32_startup.c
	$(CC) $(CFLAGS) $^ -o $@

clean:rm -rf *.o *.elf