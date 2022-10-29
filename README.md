# RTL Core Library

This is a set of common RTL cores that I've developed over time and organized into a FuseSoC library.

## Adding The Library To FuseSoC

1. Add this library to your set of cores

`fusesoc library add --sync-type git --global midi-cores https://github.com/midimaster21b/rtl-core-library.git`

2. Verify that the library is present

   `fusesoc library list`

   Expect something like this on the output:

   ```
   Name       : Location                                            : Sync type : Sync URI                                              : Auto sync
   midi-cores : /home/midimaster21b/.local/share/fusesoc/midi-cores : git       : https://github.com/midimaster21b/rtl-core-library.git : y
   ```

3. View your shiny new cores!

   `fusesoc list-cores`

And just like that, you have access to all the cores I've made available!
