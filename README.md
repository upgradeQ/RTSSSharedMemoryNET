RTSSSharedMemoryNET
===================

.NET implementation for the RivaTuner Statistics Server shared memory feature,
build with msbuild.exe 64 bit version. Unlock .dll via RMB Properties>General> Unblock . Python version (64 or 32 bit)  must match library version.  
Fork notes:
- added UpdatePosition, UpdateColor
- max 7 entries, position and color are global for all of them.
- entry can contain newlines `\n`
- Text should be no longer than 4095 chars once converted to ANSI. Lower case looks awful.

See also:
https://github.com/mkullber/HWiNFO-RTSS
