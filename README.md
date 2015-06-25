# Coding Interview

Recruiter notes: whiteboard only, problems focused on 
time and space complexity, algo, datastructures. Not
a memory test.

## Study guide:

### Need to have:

- CTCI 0-13, 15-18 ( skip java chapter )
- practice coding on whiteboard
- TODO: ask interviewer what languages are expected

### Nice to have:
- practice all the questions in C
- mock interview(s) with dave and wes
- review all datastructures from c_skelly
- write questions in python with ctypes + c modules

# Systems Interview

Two parts: roleplay troubleshooting and linux internals

### Need to have:

- review all basic tools for debugging major subsystems ( cpu, mem, network, storage )
- gdb and strace for debugging processes
- go over processes ( including int 0x80 )
- go over fork, exec, proc management syscalls
- go over signals + processes
- memory layout / tools to analyze memory and shared libs
- system setup / configuration for maintainability, security, high-avail.
- create RAID flashcards
- review RAID flashcards each night

### Nice to have
- look up any tools to simulate problems and try to look at the symptoms they create
- go over as much as https://github.com/0xAX/linux-insides as possible, especially sections about
networking and storage

# Networking

### Need to have

- TCP
- UDP
- IP
- layer 2 switching / networking
- DNS
- packet structure / encapsulation, what common data / headers are present
- what does different traffic look like under wireshark / tcpdump
- in depth how does networking work ( ex: what is sent when you visit fb.com )
- know one networking protocol in depth ( I'm going to use SSH cuz SSH is awesome )

### Nice to have

- more advanced network topologies
- BGP
- OSPF
- network design
- routing and switching hardware

# Design and Arch

### Need to have

- practice with a mock question about how to deploy something to 10k servers 
- practice with a mock question about how you would design facebook if you were going to build it from
scratch
- practice being given vague questions and needing to pull out requirements

# Manager Interview

### Need to have

- one time about failure, what did you do, how did you fix it, how did you ensure the mistake
wasn't made again

- conflict with a collegue, how did you keep it professional, not personal
