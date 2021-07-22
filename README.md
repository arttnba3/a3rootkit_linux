# a3rootkit_linux

my personal learning of rootkit under linux

more information at [my blog](https://arttnba3.cn/2021/06/30/CODE-0X01-ROOTKIT/)

# function

- hide module itself (`/proc/modules`, `/sys/modules`)
- hide device file (`/dev/device_name`)
- provide root backdoor
- hide file (VFS)
- hide process(`/proc`(pid list), task\_struct list)

# to do

- improve existed functions
- hidding network
- hidding file (EXT4)
- hidding module itself (`/sys/devices`)
- change PCB based memory (from specific kmem\_cache to some annoymous pages)
- long live on the machine
- ...