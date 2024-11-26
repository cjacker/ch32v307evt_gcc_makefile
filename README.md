# ch32v103evt with gcc and makefile support

This is pre-converted ch32v307 firmware library with gcc and makefile support from WCH official CH32V307EVT.ZIP. 

It is converted by '[ch32v_evt_makefile_gcc_project_template](https://github.com/cjacker/ch32v_evt_makefile_gcc_project_template)'

This firmware library support below parts from WCH:

- ch32v303cbt6
- ch32v303rbt6
- ch32v303rct6
- ch32v303vct6
- ch32v305fbp6
- ch32v305rbt6
- ch32v307rct6
- ch32v307wcu6
- ch32v307vct6

The default part is set to 'ch32v307vct6', you can change it with `./setpart.sh <part>`, it will setup correct flash/ram size, linker script and startup file automatically.

All examples shipped in original EVT package provided in 'Examples' dir.

The default 'User' codes is 'GPIO_Toggle' example, the default system frequency is set to 'SYSCLK_FREQ_96MHz_HSI' in 'User/system_ch32v30x.c'.

To build the project, type `make`.

## Note

Please refer to [opensource-toolchain-ch32v tutorial](https://github.com/cjacker/opensource-toolchain-ch32v) for more info.

And you must use [this latest WCH OpenOCD](https://github.com/cjacker/wch-openocd).

