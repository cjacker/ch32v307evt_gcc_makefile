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

The default part is set to 'ch32v307vct6', you can change it with `./setpart.sh <part>`. the corresponding 'Link.ld' will update automatically from the template.

The default 'User' codes is 'GPIO_Toggle' from the EVT example, all examples shipped in original EVT package provided in 'Examples' dir.

To build the project, type `make`.

