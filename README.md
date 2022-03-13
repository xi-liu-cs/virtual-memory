# virtual memory project
Xi Liu </br>
2021 </br>
* implementation of process creation,
isolated kernel memory,
isolated process address space,
page table translation facilities,
and the fork() system call 
* implementation of hardware-related functions such as 
virtual_memory_map() that maps an interval of
virtual memory to another interval of physical 
memory
* maintains a pageinfo[] array that records 
information about each physical page (which process
owns the page and reference count)
* displays dynamic memory allocation to the 
color graphics adapter console
