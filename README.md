# Arc

Minimalistic Kernel for Learning

### Todo

- [x] Bootloader
  - [x] Real Mode
  - [x] Protected Mode
  - [x] Long Mode
  - [x] Give control to Kernel
- [ ] Includes
  - [x] Ample
    - [x] Printing Utilities (`<arc/print.h>` - `printk`)
  - [ ] LibC
    - [x] Stdio
      - [x] `sprintf` - format string
    - [ ] Stdlib
      - [x] `intlen` - return length of an integer
      - [ ] `malloc` - allocate memory
      - [ ] `free` - free memory
    - [x] String
      - [x] `strlen` - give length of a string
      - [x] `memset` - set memory of a buffer to a value
    - [x] Stdarg
      - [x] Variadic Functions (`va_list`, `va_start`, `va_arg`)
- [ ] Kernel
  - [ ] Interrupts
  - [ ] Virtual File System (VFS)
  - [ ] Processes
  - [ ] Threads
  - [ ] Scheduler - Priority Round Robin
  - [ ] Memory Allocation (`lib/stdlib.h`)
    - [ ] `malloc`
    - [ ] `free`
  - [ ] User Mode
    - [ ] Switch to user mode
    - [ ] Stdin
    - [ ] Stdout
  - [ ] System Calls
- [ ] Shell (`ash`)
  - [ ] Logs
  - [ ] Initialize keyboard input
  - [ ] Commands
      - [ ] `pwd`
      - [ ] `ls`
      - [ ] `cd`
      - [ ] `mkdir`
      - [ ] `touch`
      - [ ] `cat`
      - [ ] `echo`

<!-- Also needs: GUI - Window Manager -->
<!-- Also needs: Syntax for `ash` - Based on 'sh' -->
<!-- Also needs: Book -->
<!-- Also needs: Specific Arch Support (bootloader) -->

## License

Licensed under the [MIT License](https://kbrsh.github.io/license) by [Kabir Shah](https://kabir.ml)
