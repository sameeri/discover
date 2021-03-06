
### Windows Fundamentals (From a programming standpoint)

https://msdn.microsoft.com/en-us/library/windows/desktop/ms632597(v=vs.85).aspx

https://msdn.microsoft.com/en-us/library/windows/desktop/ms632599(v=vs.85).aspx

### WinMain - Entry point

https://msdn.microsoft.com/en-us/library/windows/desktop/ms633559(v=vs.85).aspx

### Windows Classes

https://msdn.microsoft.com/en-us/library/windows/desktop/ms632596(v=vs.85).aspx

### Windows Procedures

https://msdn.microsoft.com/en-us/library/windows/desktop/ms632593(v=vs.85).aspx

### Messaging

Events, Messaging, Messages & the Message loop are the core concepts of the Windows Architecture. These are never discussed & never surface up, untill you choose to program at the bare metal level. This is how the OS actually works and it is indeed important to understand these elements.

https://msdn.microsoft.com/en-us/library/windows/desktop/ms632590(v=vs.85).aspx

https://msdn.microsoft.com/en-us/library/windows/desktop/ms644927(v=vs.85).aspx

http://www.drdobbs.com/windows/inside-the-windows-messaging-system/184408943

https://en.wikipedia.org/wiki/Message_loop_in_Microsoft_Windows

https://xavierantony.wordpress.com/2010/08/24/windows-messaging-architecture/

[Windows is a message oriented OS](https://msdn.microsoft.com/en-us/library/0x0cx6b1.aspx)

http://flylib.com/books/en/4.453.1.76/1/

https://www.microsoft.com/msj/0795/dilascia/dilascia.aspx

http://edn.embarcadero.com/article/38447

https://msdn.microsoft.com/en-us/library/aa383682.aspx

https://msdn.microsoft.com/en-us/library/windows/desktop/ms644928(v=vs.85).aspx

http://www.winprog.org/tutorial/message_loop.html

https://en.wikibooks.org/wiki/Windows_Programming/Message_Loop_Architecture

http://parallel.vub.ac.be/education/modula2/technology/Win32_tutorial/message_loop.html

http://www.drdobbs.com/windows/inside-the-windows-messaging-system/184408943

https://stackoverflow.com/questions/2443867/message-pump-in-net-windows-service


### Windows API

Application programs access the Windows API system functions to do things. Most of this is abstracted away by frameworks, but it is very import to understand the notion of the Windows API and the various services/functions it provides.

[Windows API](https://msdn.microsoft.com/en-us/library/windows/desktop/hh920508(v=vs.85).aspx)

[Windows Data Types](https://msdn.microsoft.com/en-us/library/windows/desktop/aa383751(v=vs.85).aspx)


### Windows Native Programming

Not everyone programs in .NET languages. Some develop in C, C++. Others use the 'newer' languages. It depends. It depends on the problem that people are trying to solve. When it comes to developing Windows Apps, core desktop apps use C & C++. In addition to the widely used .NET and related frameworks such as WPF. The Windows native programming brings in to light the Architecture of Windows that is hidden away to the .NET realm.

[Technology choices for Windows App development](https://msdn.microsoft.com/en-us/library/windows/desktop/ee663266.aspx)

[Win Programming in C++](https://msdn.microsoft.com/en-us/library/windows/desktop/ff381399(v=vs.85).aspx)

[Windows Coding conventions](https://msdn.microsoft.com/en-us/library/windows/desktop/ff381404(v=vs.85).aspx)

[Windows Strings](https://msdn.microsoft.com/en-us/library/windows/desktop/ff381407(v=vs.85).aspx)

[Window - Fundamental concepts] (https://msdn.microsoft.com/en-us/library/windows/desktop/ff381403(v=vs.85).aspx)

[Windows Application Entry point](https://msdn.microsoft.com/en-us/library/windows/desktop/ff381406(v=vs.85).aspx)


### Windows CRT

[C/C++ Complete Stack](https://msdn.microsoft.com/en-us/library/hh875057.aspx)

[Microsoft C runtime library (CRT)](https://msdn.microsoft.com/en-us/library/59ey50w6.aspx)

http://www.codeproject.com/Articles/22642/What-Every-Computer-Programmer-Should-Know-About-W


### Windows Driver Development

What is a Windows Driver? How does the Kernel communicate with the drivers? What are I/O request packets? What are software drivers?
How to write a driver? Who provides drivers for the devices we use? What are the various driver framework models?

These are important things to know, as they can teach us more about how the OS works, how the kernel works and how core building blocks are created and tested.

https://msdn.microsoft.com/en-us/library/windows/hardware/ff554690(v=vs.85).aspx

https://msdn.microsoft.com/en-us/library/windows/hardware/ff557560(v=vs.85).aspx

### Kernel mode Architecture

The `kernel` is the most significant part of the OS. Understand the kernel, and understand the system.

https://msdn.microsoft.com/en-us/library/windows/hardware/ff553208(v=vs.85).aspx

### Windows Registry

Oh that! That is stored in the Registry. Don't touch the registry. You will f. the system up! What the hell is the registry and why is it so important and so mysterious? 

It is time to understand the simple `object` database that stores data in `key-value` pairs.

https://msdn.microsoft.com/en-us/library/windows/desktop/ms724871(v=vs.85).aspx


### Handles and Objects & the Object Manager

OS manages resources. OS is code. How do we represent the notion of some resource. Physical or otherwise. Enter `Objects`. Files, Sockets, Processes, Threads & more are represented as Objects. The `Object manager` is the guy who manages all the objects and in a program system resources are all accessed by obtaining `handles` to objects.

https://msdn.microsoft.com/en-us/library/windows/desktop/ms724457(v=vs.85).aspx

### System Services

https://msdn.microsoft.com/en-us/library/windows/desktop/ee663297(v=vs.85).aspx

### Windows Networking

https://msdn.microsoft.com/en-us/library/windows/desktop/ee663286(v=vs.85).aspx


### Interesting Articles

http://www.codeproject.com/Articles/559385/Custom-Controls-in-Win32-API-The-Basics


### Tools

[Spy ++](https://msdn.microsoft.com/en-us/library/aa264374(v=vs.60).aspx)

Dependency Walker

SysInternals suite

Windows SDK tools

Windows DDK tools


