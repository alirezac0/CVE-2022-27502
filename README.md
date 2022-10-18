# RealVNC server up to 6.9.0 DLL Hijacking Exploit (CVE-2022-27502)


You can use pre-compiled version (64-bit) of it from [HERE](https://github.com/alirezac0/CVE-2022-27502/blob/main/x64/Release/adsldpc.dll)
Copy it to %TEMP% and initiate a repair of RealVNC Server from add or remove programs.
It will write the output of `whoami` command in %TEMP%\output.txt

If you want to change the executed command, change line [191 of dllmain.cpp](https://github.com/alirezac0/CVE-2022-27502/blob/main/adsldpc/dllmain.cpp#L191) and recompile it
