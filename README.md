# MEGA65 = Enhanced c65 running in FPGA.

Refer to "[./docs/index.md](./docs/index.md)" for the index file of the main DOC documentation.  
This documentation is best viewed using the github web-interface at:  
https://github.com/MEGA65/mega65-core/blob/master/README.md

You will optionally need the a C65 ROM file, if you wish to use BASIC 10:

http://www.zimmers.net/anonftp/pub/cbm/firmware/computers/c65/911001.bin  
renamed to MEGA65.ROM, is 128k in size

If you do not have such a file, the MEGA65 contains the free and open-source
OpenROM alternative.


# Building:

Easiest way to build the core is using Linux, e.g. Debian.

You will need exomizer. Get it via:

```git clone https://bitbucket.org/magli143/exomizer.git```

Enter the source directory and compile

```
cd exomizer/src/
make
```

After building, copy the executable to a suitable location e.g.

```sudo cp exomizer /usr/local/bin/```

