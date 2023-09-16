# Hello, Stranger!

This is a template that includes Raylib-cs, tag v4.5.0.4 from
[ChrisDill/Raylib-cs](https://github.com/ChrisDill/Raylib-cs), as well as the dynamic libraries from
Raylib for Win64 and macOS already included. It should work on .net5.0 and .net6.0.

Your project is in the 'gmae' directory. You shouldn't need to touch the 'Raylib-cs' directory at
all.

- run `dotnet build` in the 'gmae' directory to build your project
- run `dotnet run` in the 'gmae' directory to run your project

You can also find the executable for your project in the bin directory
('gmae/bin/{Debug,Release}/{net5.0,net6.0}/').

You may `dotnet run` and get an error that looks like this:

```
Unhandled exception. System.DllNotFoundException: Unable to load DLL 'raylib' or one of its dependencies: The specified module could not be found. (0x8007007E)
```

In this case, copy the `raylib.dll` (on Windows) or `libraylib.dylib` (on macOS) from the runtimes
subdirectory in the build directory to the build directory itself, right next to your executable.

Happy coding!
