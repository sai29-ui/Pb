# Dev Environment Setup Note

Running `gcc` initially failed with an "unrecognized command" error because the compiler path was missing from the system PATH.
I resolved this by adding the GCC compiler binaries directory to the Windows System Environment Variables and restarting the terminal.
Terminal navigation errors (such as typing `cd PB` inside a subfolder instead of `cd ..`) were fixed by checking current paths with standard shell commands[cite: 5].
After updating VS Code configuration and installing the C/C++ extension, `gcc --version` executed successfully[cite: 5].
This verified that the C development environment and compiler toolchain were fully working.