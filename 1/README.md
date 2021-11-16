#### 1. Explain Working mechanism of Virtual Machine.

The Virtual Machine (VM) uses a technique known as virtualization to function. Virtualization is a technique that manages, shares, and allocates hardware resources to virtual machines to create a suitable virtual environment. The virtual machine is installed on top of a hypervisor, which is a virtualization layer that sits on top of computer hardware. The hypervisor is in charge of managing virtual machines. It functions as a middleman between the hardware and the virtual machine. This allows a computer to operate multiple virtual computers at the same time. A feature called passthrough is utilized when some hardware has to be accessed directly by a VM. The hypervisor emulates all resources such as CPU, RAM, network connections, and storage so that a virtual machine seems to be running on real hardware.

There are two types of hypervisors:

Type 1 hypervisors, often known as bare-metal hypervisors, run directly on the actual host computer and have full access to its hardware. Type 1 hypervisors, which operate on server computers, are more efficient and perform better than Type 2 hypervisors, making them ideal for server, desktop, and application virtualization. Microsoft Hyper-V and VMware ESXi are examples of Type 1 hypervisors.

Type 2 hypervisors, also known as hosted hypervisors, are placed on top of the host machine's operating system and handle calls to hardware resources. End-user systems with Type 2 hypervisors are often used for specialized use cases. A developer, for example, may use a Type 2 hypervisor to establish a specialized environment in which to develop an application, or a data analyst might use it to test an application in isolation. VMware Workstation and Oracle VirtualBox are examples of Type 2 hypervisors.

![enter image description here](https://miro.medium.com/max/1838/0*uOG3TpWM2BlBYkbg)
