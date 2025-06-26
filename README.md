# Making 8-bit Music From Scratch at the Commodore 64 BASIC Prompt

Thank you to the wonderful Linus Akesson for this

https://www.linusakesson.net/

https://www.youtube.com/watch?v=ly5BhGOt2vE



# personal notes from the youtube video

## coding tricks

LIST1-99 will list lines in a range

If program crashes ?VAR to see its value at crash time like a debugger.

## integer overflow

11:04 in video, 

having the code @ this version of line 40, will generate an example of an overflow of a signed 16 bit range

fixed by altering line 30 to be 0 to 116 instead of 0 to 255

30 F=40:FORI=0TO116

?F and ?I used to inspect variable like a debugger is cool!

