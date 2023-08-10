Note about buildroot config file:

In Toolchain --> Host GDB Options --> Build cross gdb for the host option was enabled.
As a result, gdbserver has to be installed on the target. That gdbserver is bound to take extra space, and isn't needed in the final design.
Thus, this option should be disabled in the production version.