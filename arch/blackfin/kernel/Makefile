#
# arch/blackfin/kernel/Makefile
#

extra-y := init_task.o vmlinux.lds

obj-y := \
	entry.o process.o bfin_ksyms.o ptrace.o setup.o signal.o \
	sys_bfin.o time.o traps.o irqchip.o dma-mapping.o flat.o \
	fixed_code.o reboot.o bfin_gpio.o

obj-$(CONFIG_BFIN_GPTIMERS)          += gptimers.o
obj-$(CONFIG_MODULES)                += module.o
obj-$(CONFIG_BFIN_DMA_5XX)           += bfin_dma_5xx.o
obj-$(CONFIG_DUAL_CORE_TEST_MODULE)  += dualcore_test.o
obj-$(CONFIG_KGDB)                   += kgdb.o
obj-$(CONFIG_EARLY_PRINTK)           += early_printk.o
