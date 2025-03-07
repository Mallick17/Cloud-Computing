# Virtual Machine
A virtual machine (VM) is a software-based computer that exists within another computer’s operating system, often used for the purposes of testing, backing up data, or running SaaS applications.

## What is an operating system?
Traditional computers are built out of physical hardware, including hard disk drives, processor chips, RAM, and more. In order to utilize this hardware, computers rely on a type of software known as an operating system (OS). Some common examples of OSes are Mac OSX, Microsoft Windows, Linux, and Android.

The OS is what manages the computer’s hardware in ways that are useful to the user. For example, if the user wants to access the Internet, the OS directs the network interface card to make the connection. If the user wants to download a file, the OS will partition space on the hard drive for that file. The OS also runs and manages other pieces of software. For example, it can run a web browser and provide the browser with enough random access memory (RAM) to operate smoothly.

## Can you have two or more operating systems on one computer?
It is possible to run multiple operating systems on one computer. This can be achieved through a process called virtualization. In virtualization, a piece of software behaves as if it were an independent computer. This piece of software is called a virtual machine, also known as a ‘guest’ computer. (The computer on which the VM is running is called the ‘host’.) The guest has an OS as well as its own virtual hardware.

‘Virtual hardware’ may sound like an oxymoron. In fact, a VM's 'hard drive' is really just a file on the host computer’s hard drive. However, a virtual hard drive fulfills the same function as a physical one.

The number of VMs that can run on one host is limited only by the host’s available resources. The user can run the OS of a VM in a window like any other program, or they can run it in fullscreen so that it looks and feels like a genuine host OS.

## What are virtual machines used for?
Common use cases for virtual machines on single computers include:
- **Testing** - Software developers often want to test their applications in different environments. They can use virtual machines to run their applications in various OSes on one computer. This is simpler and more cost-effective than testing on several different physical machines.
- **Running software designed for other OSes** - Although certain software applications are only available for a single platform, a VM can run software designed for a different OS. For example, a Mac user who wants to run software designed for Windows can run a Windows VM on their Mac host.
- **Running outdated software** - Some pieces of older software can’t be run in modern OSes. Users who want to run these applications can run an old OS on a virtual machine.

## How does cloud computing use virtual machines?
Several cloud providers offer virtual machines to their customers. These virtual machines typically live on powerful servers that can act as a host to multiple VMs and can be used for a variety of reasons that wouldn’t be practical with a locally-hosted VM. These include:
- **Running SaaS applications**
  - Software-as-a-service, or SaaS for short, is a cloud-based method of providing software to users, in which an application is served to user over the Internet rather than running on their computers. Often, it is virtual machines in the cloud that do the computation for SaaS applications as well as delivering them to users. If the cloud provider has a geographically distributed network edge, then the application will run closer to the user, resulting in faster performance.
- **Backing up data**
  - Cloud-based VM services are popular for backing up data, because the data can be accessed from anywhere. Plus, cloud VMs provide better redundancy, require less maintenance, and generally scale better than physical data centers. (For example, it’s relatively easy to buy an extra gigabyte of storage space from a cloud VM provider, but much more difficult to build a new local data server for that extra gigabyte of data.)
- **Hosting services like email and access management**
  - Hosting these services on cloud VMs is generally faster and more cost-effective, and helps minimize maintenance and offload security concerns as well.
