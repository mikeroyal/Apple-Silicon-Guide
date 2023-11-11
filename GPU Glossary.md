# GPU Glossary

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614121-28110c11-cc0b-4115-8335-8cb30a6bfe32.png">
<br />
How the CPU and GPU work together when running application code.
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/138614114-a0fdd83a-b885-42b8-849f-f45691091454.png">
<br />
Unified Memory Architecture
</p>


A

  [Application Specific Integrated Circuits (ASICs)](https://en.wikipedia.org/wiki/Application-specific_integrated_circuit) is an integrated circuit (IC) chip customized for a particular use in embedded systems, mobile phones, personal computers, professional workstations, rather than intended for general use.
  
  [Apple Hypervisor](https://developer.apple.com/documentation/hypervisor) is a frameowrk that builds virtualization solutions on top of a lightweight hypervisor, without third-party kernel extensions. Hypervisor provides C APIs so you can interact with virtualization technologies in user space, without writing kernel extensions (KEXTs). As a result, the apps you create using this framework are suitable for distribution on the [Mac App Store](https://www.appstore.com/).

   [Apple Virtualization Framework](https://developer.apple.com/documentation/virtualization) is a framework that provides high-level APIs for creating and managing virtual machines on Apple silicon and Intel-based Mac computers. This framework is used to boot and run a Linux-based operating system in a custom environment that you define. It also supports the [Virtio specification](https://www.redhat.com/en/virtio-networking-series), which defines standard interfaces for many device types, including network, socket, serial port, storage, entropy, and memory-balloon devices.

   [Apple Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.
  
B


C
   
   [Central Processing Unit (CPU)](https://en.wikipedia.org/wiki/Central_processing_unit) is a circuit that's composed of multiple cores that executes instructions comprising a computer program. The CPU performs basic arithmetic, logic, controlling, and input/output (I/O) operations specified by the instructions in the program. This is different from other external components such as main memory, I/O circuitry, and graphics processing units (GPUs).
   
   [CMOS (Complementary Metal-Oxide Semiconductor)](https://www.computerhope.com/jargon/c/cmos.htm) is a small amount of memory on a computer motherboard that stores the BIOS settings. These BIOS settings include the system time and date, as well as hardware settings.

D

**[Dynamic Caching](https://patents.google.com/patent/US20210271606A1/)** is Apple's new GPU process on M3-series chips that allocates the use of local memory in real time. This ensures the precise amount of memory required is spent on that particular task such as Gaming, Video rendering, and 3D graphics. 

E

 [Error Correction Code (ECC) memory](https://www.crucial.com/products/memory/server/ecc) is a method of detecting and then correcting single-bit memory errors. A single-bit memory error is a data error in server output or production, and the presence of errors can have a big impact on server performance. The two types of single-bit memory errors: **hard errors and soft errors**. **Hard errors** are caused by physical factors, such as excessive temperature variation, voltage stress, or physical stress brought upon the memory bits. **Soft errors** occur when data is written or read differently than originally intended, such as variations in voltage on the motherboard, to cosmic rays or radioactive decay that can cause bits in the memory to flip.

  [EEPROM (Electrically Erasable Programmable Read-Only Memory)](https://www.futureelectronics.com/c/semiconductors/memory--RAM--eeprom) is a type of non-volatile memory used in integrated in microcontrollers for smart cards/remote keyless systems, and other electronic devices to store relatively small amounts of data by allowing individual bytes to be erased and reprogrammed as needed in an application.

  [EPROM](https://www.minitool.com/lib/eprom.html) is a memory chip that does not lose data even when the power is switched off. This is a non-volatile memory type so it retains data even when the power is switched off. Each EPROM is individually programmed by an electronic device.

F 

G 

   [Graphics Processing Unit (GPU)](https://en.wikipedia.org/wiki/Graphics_processing_unit) is a circuit that's composed of hundreds of cores that can handle thousands of threads simultaneously. GPUS can rapidly manipulate and alter memory to accelerate the creation of images in a frame buffer intended for output to a display device. They are used in embedded systems, mobile phones, personal computers, professional workstations, and game consoles.
   
   
   [Graphics Double Data Rate (GDDR) SDRAM](https://en.wikipedia.org/wiki/GDDR6_SDRAM#GDDR6X) is a type of synchronous graphics random-access memory (SGRAM) with a high bandwidth ("double data rate") interface designed for use in graphics cards, game consoles, and high-performance computing.

H

  [HVM (Hardware Virtual Machine)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html) is a virtualization type that provides the ability to run an operating system directly on top of a virtual machine without any modification, as if it were run on the bare-metal hardware.

I

  [Image Signal Processing (ISP)](https://en.wikipedia.org/wiki/Image_processor) is the processs of converting an image into digital form by performing operations like noise reduction, auto exposure, autofocus, auto white balance, HDR correction, and image sharpening with a Specialized type of media processor.

J 

K 

  [KVM (for Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page) is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module, kvm-intel.ko or kvm-amd.ko.

L 

M

   [Memory module](https://en.wikipedia.org/wiki/Memory_module) is a printed circuit board on which memory integrated circuits are mounted. Memory modules permit easy installation and replacement in electronic systems such as personal computers, workstations, and servers.

N

  [Network interface cards (NICs)](https://www.ni.com/en-us/support/documentation/supplemental/11/best-practices-for-using-multiple-network-interfaces--nics--with.html) is a network interface controller, network adapter, or Local Area Network ( LAN) adapter. It provides network connections for devices like computers and servers.
  
  [Non-Transparent Bridging (NTB)](https://docs.nvidia.com/drive/drive_os_5.1.6.1L/nvvib_docs/index.html#page/DRIVE_OS_Linux_SDK_Development_Guide/System%20Programming/sys_components_non_transparent_bridging.html#) is a process that enables a inter-domain communication, facilitating communication between devices in different switch partitions. This ability enables both hosts and EPs to initiate transactions to hosts and/or EPs in another switch partition. An NTB or NT Interconnection consists of two or more PCI functions each defined by a Type 0 PCI header that are interconnected by a bridging function. The Type 0 PCI functions are referred to as Non-Transparent EPs (NT EP). Each partition can have at most one NT EP.

O 


   [oVirt](https://www.ovirt.org) is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible.Founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based allowing for centralized management of virtual machines, compute, storage and networking resources, from an easy-to-use web-based front-end with platform independent access.

  [Open vSwitch(OVS)](https://www.openvswitch.org/)is an open source production quality, multilayer virtual switch licensed under the open source Apache 2.0 license. It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).

P 

  [PV(ParaVirtualization)](https://wiki.xenproject.org/wiki/Paravirtualization_(PV)) is an efficient and lightweight virtualization technique introduced by the Xen Project team, later adopted by other virtualization solutions. PV does not require virtualization extensions from the host CPU and thus enables virtualization on hardware architectures that do not support Hardware-assisted virtualization.

Q 

  [QEMU](https://www.qemu.org) is a fast processor emulator using a portable dynamic translator. QEMU emulates a full system, including a processor and various peripherals. It can be used to launch a different Operating System without rebooting the PC or to debug system code.

R

  [Random Access Memory (RAM)](https://en.wikipedia.org/wiki/Random-access_memory) is a form of computer memory that can be read and changed in any order, typically used to store working data and machine code. A random access memory device allows data items to be read or written in almost the same amount of time irrespective of the physical location of data inside the memory, in contrast with other direct-access data storage media. 
  
  [Remote Direct Memory Access(RDMA)fabrics](https://core.vmware.com/resource/basics-remote-direct-memory-access-rdma-vsphere) is an extenion of the Direct Memory Acces (DMA) technology, which is the ability to access host memory directly without CPU intervention. RDMA allows for accessing memory data from one host to another. A key charateric for RDMA is that it greatly improves throughput and performance because less CPU cycles are needed to process the network packets.
  
  [RT (Real-time ray tracing) Cores](https://developer.nvidia.com/blog/nvidia-turing-architecture-in-depth/) is a hardware-based ray tracing acceleration accelerate Bounding Volume Hierarchy (BVH) traversal and ray/triangle intersection testing (ray casting) functions. RT Cores perform visibility testing on behalf of threads running in the SM, allowing it to handle another vertex, pixel, and compute shading work.

S 

  [Single Instruction, Multiple Data (SIMD)](https://en.wikipedia.org/wiki/SIMD) is a type of parallel processing that describes computers with multiple processing elements that perform the same operation on multiple data points simultaneously.
  
  [Secure virtual memory](https://support.apple.com/guide/mac-help/what-is-secure-virtual-memory-on-mac-mh11852/mac) is a technique used in macOS that encrypts the data in virtual memory. Secure virtual memory is always on, so data is kept secure while it’s swapped between your hard disk and RAM. The RAM on your Mac contains no information when it’s off.

T 

   [Transaction Layer Packets (TLPs)](https://www.oreilly.com/library/view/pci-express-system/0321156307/0321156307_ch04lev1sec5.html) is the starting point in the assembly of outbound Transaction Layer Packets (TLPs), and the end point for disassembly of inbound TLPs at the receiver. Along the way, the Data Link Layer and Physical Layer of each device contribute to the packet assembly and disassembly.

U

   [Universal Flash Storage (UFS)](https://www.jedec.org/standards-documents/focus/flash/universal-flash-storage-ufs) is an open standard, high-performance interface designed for use in applications where power consumption needs to be minimized, including mobile systems such as smartphones and tablets as well as automotive applications. Its high-speed serial interface and optimized protocol enable significant improvements in throughput and system performance.

  **UFS-based multichip packages (uMCPs)** is a process that takes advantage of the ultra-fast Universal Flash Storage (UFS) controller to provide big performance and power savings in a small footprint for slim designs. Available in 10 GB or 12 GB memory modules.

V

  [Video Random Access Memory (VRAM)](https://en.wikipedia.org/wiki/VRAM) is the RAM allocated to store image or graphics related data. It functions in the same way as RAM, storing specific data for easier access and performance. Image data is first read by the processor and written on the VRAM. It is then converted by a [RAMDAC](https://en.wikipedia.org/wiki/RAMDAC) or a RAM digital-to-analog converter and display as graphics output.
  
  [Vector Processor](https://en.wikipedia.org/wiki/Vector_processor) is a central processing unit (CPU) that implements an instruction set where its instructions are designed to operate efficiently and effectively on large one-dimensional arrays of data called vectors.
  
  [Virtual memory](https://en.wikipedia.org/wiki/Virtual_memory) is a memory management technique that is implemented by using both hardware (central processing unit (CPU)) and software. It makes a program think it has available storage space or address space. When actually virtual memory usually is divided into several physical memory fragments, and stored on the disk storage(SSD or HDD) which can be used to exchange data when needed. On Windows this is called a [Pagefile](https://docs.microsoft.com/en-us/windows/client-management/introduction-page-file) or on Linux a [Swap space](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/storage_administration_guide/ch-swapspace).

W 

X 

Y 

Z
