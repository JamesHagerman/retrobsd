BUILDPATH = ../../../tools/configsys/../../sys/pic32
H         = ../../../tools/configsys/../../sys/include
M         = ../../../tools/configsys/../../sys/pic32
S         = ../../../tools/configsys/../../sys/kernel

vpath %.c $(M):$(S)
vpath %.S $(M):$(S)

KERNOBJ += adc.o clock.o cons.o devsw.o exception.o exec_aout.o exec_conf.o exec_elf.o exec_script.o exec_subr.o gpio.o hx8357.o init_main.o init_sysent.o kern_clock.o kern_descrip.o kern_exec.o kern_exit.o kern_fork.o kern_mman.o kern_proc.o kern_prot.o kern_prot2.o kern_resource.o kern_sig.o kern_sig2.o kern_subr.o kern_synch.o kern_sysctl.o kern_time.o machdep.o mem.o rd_sd.o rd_spirams.o rdisk.o signal.o spi_bus.o startup.o subr_prf.o subr_rmap.o swap.o sys_generic.o sys_inode.o sys_pipe.o sys_process.o syscalls.o sysctl.o tty.o tty_subr.o tty_tty.o uart.o ufs_alloc.o ufs_bio.o ufs_bmap.o ufs_dsort.o ufs_fio.o ufs_inode.o ufs_mount.o ufs_namei.o ufs_subr.o ufs_syscalls.o ufs_syscalls2.o vers.o vfs_vnops.o vm_sched.o vm_swap.o vm_swp.o 
EXTRA_TARGETS = 

DEFS += -DADC_ENABLED=YES
DEFS += -DBUS_DIV=1
DEFS += -DBUS_KHZ=80000
DEFS += -DCONSOLE_DEVICE=tft0
DEFS += -DCPU_IDIV=2
DEFS += -DCPU_KHZ=80000
DEFS += -DCPU_MUL=20
DEFS += -DCPU_ODIV=1
DEFS += -DCRYSTAL=8
DEFS += -DDC0_DEBUG=DEVCFG0_DEBUG_DISABLED
DEFS += -DDC0_ICE=0
DEFS += -DDC1_CKM=0
DEFS += -DDC1_CKS=0
DEFS += -DDC1_FNOSC=DEVCFG1_FNOSC_PRIPLL
DEFS += -DDC1_IESO=DEVCFG1_IESO
DEFS += -DDC1_OSCIOFNC=0
DEFS += -DDC1_PBDIV=DEVCFG1_FPBDIV_1
DEFS += -DDC1_POSCMOD=DEVCFG1_POSCMOD_HS
DEFS += -DDC1_SOSC=0
DEFS += -DDC1_WDTEN=0
DEFS += -DDC1_WDTPS=DEVCFG1_WDTPS_1
DEFS += -DDC2_PLLIDIV=DEVCFG2_FPLLIDIV_2
DEFS += -DDC2_PLLMUL=DEVCFG2_FPLLMUL_20
DEFS += -DDC2_PLLODIV=DEVCFG2_FPLLODIV_1
DEFS += -DDC2_UPLL=0
DEFS += -DDC2_UPLLIDIV=DEVCFG2_UPLLIDIV_2
DEFS += -DDC3_CAN=DEVCFG3_FCANIO
DEFS += -DDC3_ETH=DEVCFG3_FETHIO
DEFS += -DDC3_MII=DEVCFG3_FMIIEN
DEFS += -DDC3_SRS=DEVCFG3_FSRSSEL_7
DEFS += -DDC3_USBID=DEVCFG3_FUSBIDIO
DEFS += -DDC3_USERID=0xffff
DEFS += -DDC3_VBUSON=DEVCFG3_FVBUSONIO
DEFS += -DEXEC_AOUT
DEFS += -DEXEC_ELF
DEFS += -DEXEC_SCRIPT
DEFS += -DGPIO_ENABLED=YES
DEFS += -DHX8357_ENABLED
DEFS += -DKERNEL
DEFS += -DPARTITION="spirams0:sa@2040"
DEFS += -DPIC32MX7
DEFS += -DSD0_CS_PIN=9
DEFS += -DSD0_CS_PORT=TRISG
DEFS += -DSD0_PORT=2
DEFS += -DSPIRAMS_CHIPS=16
DEFS += -DSPIRAMS_CHIPSIZE=128
DEFS += -DSPIRAMS_CS0_PIN=0
DEFS += -DSPIRAMS_CS0_PORT=TRISA
DEFS += -DSPIRAMS_CS10_PIN=6
DEFS += -DSPIRAMS_CS10_PORT=TRISA
DEFS += -DSPIRAMS_CS11_PIN=7
DEFS += -DSPIRAMS_CS11_PORT=TRISA
DEFS += -DSPIRAMS_CS12_PIN=14
DEFS += -DSPIRAMS_CS12_PORT=TRISG
DEFS += -DSPIRAMS_CS13_PIN=12
DEFS += -DSPIRAMS_CS13_PORT=TRISG
DEFS += -DSPIRAMS_CS14_PIN=13
DEFS += -DSPIRAMS_CS14_PORT=TRISG
DEFS += -DSPIRAMS_CS15_PIN=5
DEFS += -DSPIRAMS_CS15_PORT=TRISF
DEFS += -DSPIRAMS_CS1_PIN=1
DEFS += -DSPIRAMS_CS1_PORT=TRISA
DEFS += -DSPIRAMS_CS2_PIN=4
DEFS += -DSPIRAMS_CS2_PORT=TRISA
DEFS += -DSPIRAMS_CS3_PIN=5
DEFS += -DSPIRAMS_CS3_PORT=TRISA
DEFS += -DSPIRAMS_CS4_PIN=2
DEFS += -DSPIRAMS_CS4_PORT=TRISA
DEFS += -DSPIRAMS_CS5_PIN=1
DEFS += -DSPIRAMS_CS5_PORT=TRISD
DEFS += -DSPIRAMS_CS6_PIN=2
DEFS += -DSPIRAMS_CS6_PORT=TRISD
DEFS += -DSPIRAMS_CS7_PIN=14
DEFS += -DSPIRAMS_CS7_PORT=TRISB
DEFS += -DSPIRAMS_CS8_PIN=14
DEFS += -DSPIRAMS_CS8_PORT=TRISD
DEFS += -DSPIRAMS_CS9_PIN=8
DEFS += -DSPIRAMS_CS9_PORT=TRISD
DEFS += -DSPIRAMS_ENABLED
DEFS += -DSPIRAMS_PORT=4
DEFS += -DUART1_BAUD=115200
DEFS += -DUART1_ENABLED=YES
DEFS += -DUCB_METER


LDSCRIPT = ../../../tools/configsys/../../sys/pic32/cfg/bootloader-max32.ld

CONFIG = PICADILLO_RAMBO
CONFIGPATH = ../../../tools/configsys

include ../../../tools/configsys/../../sys/pic32/kernel-post.mk
