##Description of z/OS

###Architecture:
z/OS is a 64-bit operating system for IBM mainframes, produced by IBM. Mainframes are large computer systems.
It was written in PL/X(a.k.a. Programming Language/Systems, is a "machine-oriented" programming language), HLASM (High Level Assembler) and C/C++.
It offers the attributes of modern operating systems but also has functionalities from the 1960s.
It supports stable mainframe systems such as CICS(Customer Information Control System), IMS(Information Management System) and others.
It also supports Java, C, C++, and UNIX APIs.


IBM ended its support for z/OS in 2007. Now z/OS is only supported on z/Architecture mainframes and only runs in 64-bit mode.
z/OS was IBM's flagship operating system, which was perfect for high volume operations with high stability and security.

z/OS is available after buying a licence, which starts at $125/month.


###Features
-z/OS has 64-bit memory support. Wihin each address space, it permits the placement of data over the 2GB bar for perfomance reasons, but there are no impediments to allowing more than 2GB of code per space.
-It features some technologies like RACF (Resource Access Control Facility that helps secure an installation's data, protects system resources and controls permissions).
-z/OS also has a Workload Manager(WLM), which controls the access to system resources. It also supports tri-modal addressing(24-bit, 31-bit and 64-bit) because it was meant to function on older hardware that doesn't have a 64-bit support.
-Generation Data Group (GDG) is a special type of file used by z/OS. The GDG is a description of how many generations of a file are to be kept and how old the oldest generation must be at least before it is deleted. When a new generation is created, the system checks if one or more obsolete generations have to be deleted and, if necessary, deletes them.
