# corten
Operating System for x68 written in rust and assembler

# background
Way back in the days of DOS and floppy disks i wrote a small boot loader that lived on a floppy disk, booted my machine and printed some lines of text to the screen. I just did this as en exercise to better understand the workings of my computer on a low level, with no greater ambitions that to see how it works. Last xmas i was pondering on what to do for a holiday project, and since rust is now gaining more traction in the software community at large i thought it would be interesting to do the same thing i did so may years ago, but in rust, and maybe taking it bit further this time. Investigating this a bit further and talking to some friends i soon realised that a lot has change since the good old days of DOS, and booting a modern computer into protected 64bit mode is a bit harder then booting 16bit real mode. So i decided to do something else and shelved the idea, until this summer, when i decided to have a look at it again. I found two great articles online, one about booting a modern computer and the steps needed to get it into 64bit protected mode, and another about writing an operating system in rust, so i decided to use these as a starting point for my project, with no other goal then to learn a bit more rust and to update my knowledge about the boot process of a modern computer.

# references
This project has its basis in the following articles:
* https://thasso.xyz/2024/07/13/setting-up-an-x86-cpu.html
* https://os.phil-opp.com/
