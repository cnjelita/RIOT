APPLICATION = posix_semaphore
include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := chronos mbed_lpc1768 msb-430 msb-430h nrf6310 \
                             nucleo32-f031 nucleo32-f042 nucleo-f030 nucleo-f334 \
                             nucleo-l053 pca10000 pca10005 spark-core \
                             stm32f0discovery weio yunjia-nrf51822

USEMODULE += fmt
USEMODULE += posix_semaphore

DISABLE_MODULE += auto_init

include $(RIOTBASE)/Makefile.include

test:
	tests/01-run.py
