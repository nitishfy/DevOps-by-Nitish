At the beginning stage, you'd have a lot of questions out of which some are listed below:

1. What is DevOps?
2. What is the problem that DevOps is solving?
3. How did the term 'DevOps' rise?
   
Before answering all these questions, we actually need to understand a very important concept in the Computer Science which is called as Virtualization.

Again, before understanding the concept of Virtualization, we need to understand what used to happen before virtualization, why was there a need of virtualization at the first place and most important what exactly is virtualization?

## Before Virtualization

Earlier before the concept of virtualization was introducted, the different services of an application used to run on different servers. This means that only one service can run on one server. For eg. Web service of an application can run only on one server whereas Database service of the same application would require to run on some different server. 

**Remember:** One Service, One Server, One Operating System.

Now, as we know servers are costly. So if your application contains multiple services, you'd require multiple servers to run multiple services. 

Well in today's time, this is not the case on how you run serivces. In today's time, you can run multiple services on one server itself with the help of virtualization.

Cost is not the only factor here. Imagine due to some reasons one server goes down. Not only the service of an application would go down but it would take additional cost to set up the server once again along with other setup to be implemented as well.

### Who solved this problem?

 VMware.

VMware is a company which actually solved this problem by introducing the concept of virtualization.

With the help of virtualization, you can run multiple services on one server itself. But how?

Virtualisation is the concept in which multiple Virtual Machine/Multiple Operating system can run on single server/computer with the help of a software called as Hypervisor. Consider various OS like Windows & Linux. With virtualization, one can run both the OS on a single machine. This means that if you're using a machine with Windows OS as the host OS, you can also install Linux Kernel on the same windows machine. It is to be noted that both the OS would run in isolation. This furthre means that Windows OS would run acting like if it is the only OS on the machine whereas Linux would run acting like if it is the only OS in the machine.

In other words, virtualization or virtualisation is the act of creating a virtual version of something at the same abstraction level, including virtual computer hardware platforms, storage devices, and computer network resources.

You might have various questions like what is an Host OS, how does virtualization take place?

Take a pause here and ask yourself - Did you understand why was there a need ot virtualization?

**How do virtualization take place?**

Hypervisor is the software which enables the process of virtualization. Look at the picture below:

![Virtual Machine!](/01-Virtualization/images/VM.png)

It is to be noted that a VM takes the storage as well as networking resources from the underlying computer/Host OS.

A Host OS is the OS/computer which is being virtualized.
A Guest OS is the OS which results as a byproduct after the Host OS has been virtualized.

Here's an interesting thing to know about. When you dual boot your machine, you're not making a virtual machine out of it. Dual booting is not creating a VM. In virtualisation, you can access both Operating System simulatenously. However in dual boot, you can't access/use both Operating System simultaneousy. 

Hypervisor partitions the hardware of host OS and assigns the required resources to the virtual machines you created. 

There are two types of Hypervisor:
1. Type-1
2. Type-2

- **Type-2:** This type of hypervisor sits on the top of the Host OS and takes the resources from the Host OS. Type 2 is basically used by personal computers. For eg. Oracle VirtualBox.
  
- **Type-1:** This type of hypervisor performs exactly the same way as Type 2 hypervisor just the major difference is that in Type 1 hypervisor, the hypervisor sits on the top of the Hardware and takes resources from the Hardware itself instead of any Host OS. Type 1 is mainly used in production. For eg. Microsoft HV.

![Hypervisor!](/01-Virtualization/images/Hypervisor-01.png)
![Hypervisor-!](/01-Virtualization/images/Hypervisor.png)

Apart from reading this, it is highly recommend to go through the following [resource](https://youtu.be/mQP0wqNT_DI) to get a better understanding about virtualization.

That's it about Virtualization. Did you have an answer to the following questions now:

1. What is Virtualization?
2. What is the need of virtualization?
3. How does virtualization take place?
