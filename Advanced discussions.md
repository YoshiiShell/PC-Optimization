# Dual channel memory

RAM brings it's contents to the CPU to be processed. In one or three sticks of memory, there is only one line, a bus.
When two or four are in however, dual-channel memory is on, which adds another bus, doubling the space from 64 bit space to 128 bit space.
The performance gains are noticable and is highly recommended.

# My attack on RGB

I don't like RGB from a pure optimization standpoint. It takes power (even if minimal) away from what you need, and is just yet another thing you have to handle. 
In my opinion, sleeper builds are best for performence, although I am biased (I have an older sleeper build)

# start ms-cxh:localonly, how does it work?

CXH stands for Cloud Experience Host, which hosts OOBE, and is actually a standalone program with its own commands. A lot of the heavy work on research was done by [Hexacorn](https://www.hexacorn.com/blog/2022/01/16/ms-cxh-and-ms-cxh-full-handlers/) and [Enderman](https://enderman.ch/blog/the-windows-oobe). 

One of those commands is to start its failsafe program. When OOBE fails, there is another type of OOBE that is pulled. This command launches that in its local only form. 
It's also weird in that it only asks for a username, optional password, and that's really it. You will be taken to privacy settings after however.
