# MIPS Reverse Engineering Workshop at Recon 2026

You'll find the class slide deck, the lab exercise and the sample here, accompanied by a Binary Ninja .bndb with recovered LIBC library function names. The sample is encrypted, the password is 'infected'. Do not unpack this on a host thats running an AV, your AV will delete it. Do not worry about this malware infecting anything, if you're not trying to analyze it on your Playstation2, you should be fine. And Playstation2 doesn't even have the right MIPS version, duh.

## Sales Pitch :)

Curious about expanding your reverse engineering skills to another architecture? Lets go learn MIPS! Both x86-64 and ARM reverse engineering knowledge transfer really well to MIPS, and with some basics and an instruction cheat sheet we're on our way in no time. We'll analyze AcidRain, a piece of MIPS-32 malware, a Russian wiper malware none the less. The sample is stripped, and we'll learn how to quickly recover essential libc functions, to then reconstruct the malware's code flow.

### Outline

Workshop outline (45 min lecture / 45 min lab / 30 min discussion of solutions):

- MIPS architecture 101 and a brief history
- The MIPS pipeline
- Delay slots
- Instruction categories
- MIPS registers and their purpose
- The MIPS stack
- The O32 calling convention 
- Syscall calling convention and numbering
- Function prologues/epilogues
- Other MIPS architectures and their calling conventions, briefly
- Hands on: AcidRain
-- Challenge 1: Understand daemonization
-- Challenge 2: Reconstruct wiping code flow

A lot of us are stuck on one architecture, and its not actually that hard learning another one, since we don't need to learn *from scratch* but can easily transfer understanding of one architecture to another. This workshop will show how, with the example of MIPS, assuming that many students are not familiar with this somewhat obscure architecture. That, while the basics of MIPS are actually rather simple, especially AcidWiper is quite easy to read once the basics are understood.
