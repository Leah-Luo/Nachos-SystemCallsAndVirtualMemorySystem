# Nachos-SystemCallsAndVirutalMemorySystem
In a real operating system, the kernel not only uses its procedures internally, but also allows user programs
to access some of its routines via system calls. In this assignment, we use Nachos to implement system
calls and virtual memory system 
<br /> Since Nachos executes MIPS instructions, these user programs must be compiled into MIPS
format using the cross compiler. 
<br />The project should be compiled well on Unix/Linux (lcs-vc-cis468.syr.edu)


<b>Features</b>
<br /> Basic System Calls Handlers: Read, Write, Exec, Fork, Add, Halt, Exit
<br /> Multiprogramming with Round Robin scheduler, allows user to define tiem slice quantum as well
<br /> Virtual Memory System Management. SwapSpace for reserve/allocate a dedicated space on the disk. Page Fault handler and LRU page replacement algorithm for physical memory.


<p><b>How to build Nachos?</p></b>
<pre><code>run the following commands under /build.linux directory:
make clean
make depend
make
</code></pre>