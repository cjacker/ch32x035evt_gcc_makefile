# ch32x035evt with gcc and makefile support

This is pre-converted ch32x035 firmware library with gcc and makefile support from WCH official CH32X035EVT.ZIP.

It is converted by '[ch32v_evt_makefile_gcc_project_template](https://github.com/cjacker/ch32v_evt_makefile_gcc_project_template)'

This firmware library support below parts from WCH:

- CH32X035R8T6
- CH32X035C8T6
- CH32X035G8U6
- CH32X035G8R6
- CH32X035F8U6
- CH32X035F7P6
- CH32X033F8P6

The default part is set to 'ch32x035f8u6', you can change it with `./setpart.sh <part>`. the corresponding 'Link.ld' will update automatically from the template.

The default 'User' codes is 'GPIO_Toggle' from the EVT example, all examples shipped in original EVT package provided in 'Examples' dir.

To build the project, type `make`.

## Note

Please refer to [opensource-toolchain-ch32v tutorial](https://github.com/cjacker/opensource-toolchain-ch32v) for more info.

And you must use [this latest WCH OpenOCD](https://github.com/cjacker/wch-openocd).

