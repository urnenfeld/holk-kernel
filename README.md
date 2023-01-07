# holk-kernel
Kernel for Holk, This is currently a fork of cosmoe library kernel to be used inside the holk project.

## Investigations
This sections describes the investigations followed to cover the requirements of Haiku Kernel with a Linux Kernel

### Of threads and proceses
* [What is scheduleable](https://stackoverflow.com/questions/15601155/does-linux-schedule-a-process-or-a-thread)

### Suspend Thread
* [Not implemented](https://stackoverflow.com/questions/11468333/linux-threads-suspend-resume)
* [Oposite of this](https://stackoverflow.com/questions/6227926/ask-scheduler-to-schedule-a-certain-thread)

### Syscalls
## Adding / Replacing
* [Misc](https://bbs.archlinux.org/viewtopic.php?id=159391)
* [Adding](https://medium.com/@ssreehari/implementing-a-system-call-in-linux-kernel-4-7-1-6f98250a8c38)

## Intercepting
* [Loadable Kernel Module Programming and System Call Interception](https://www.linuxjournal.com/article/4378)
* [Example](https://lib.void.so/replace-the-system-call-in-linux-using-the-kernel-module/)
* [Wrapping](http://samanbarghi.com/blog/2014/09/05/how-to-wrap-a-system-call-libc-function-in-linux/)
