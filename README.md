a mech keeb macropad. it is named burnt keeb in files

I designed it using a xppen ack05 and one of those osu double keys at the bottom

I made these mostly to play osu, and to use kirita

I could have added a rotary encoder but I chose not to, and to add a screen instead where I plan to try to add Luna to it.

Luna is a keyboard pet that moves faster the faster you type and whatnot, it will be linked to this repo (If I can figure out how to do that)

it Is a matrix of 12 keys, and naturally a USB c female port, that's linked to a xaio rp2040, and I've moved the matrix capisators to the right to be seen since I thought that looked cool in the example macropad

I'm sorry I'm really unsure what more to put here? most of it is in the logs in the stardance thing, also I'm using qmk for this

this is the schematic

<img width="1038" height="474" alt="image" src="https://github.com/user-attachments/assets/f73a8700-0e88-4cec-8cf6-3c6876756d0e" />

this is the pcb

![Uploading image.png…]()
/>

and this is the 3d model

and do pardon the stray resistor, I accidently moved it but it really shouldn't affect the print since I'm not printing that part

<img src="https://stardance.hackclub.com/rails/active_storage/representations/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MzM5MDA0LCJwdXIiOiJibG9iX2lkIn19--ba9b52067b0a5a85459ac87b7c788959b9194c7e/eyJfcmFpbHMiOnsiZGF0YSI6eyJmb3JtYXQiOiJ3ZWJwIiwicmVzaXplX3RvX2xpbWl0IjpbMTYwMCw5MDBdLCJzYXZlciI6eyJzdHJpcCI6dHJ1ZSwicXVhbGl0eSI6NzV9fSwicHVyIjoidmFyaWF0aW9uIn19--5394ecd620f1b8ee9be71be3f37cd22b8a88953c/image.png"/>

do note, a certain macropad.zip is the kaicad file, I cant use a windows ./ Linux laptop for a bit and am on a Chromebook so I'm not really able to access it

BOM
- 3d printed case (I'll leave this one to printing legion, I don't know much about it even if I'm trying to get into it)
- the pcb (through PCB way)
- a soldering iron grant would be nice but I can borrow a friend's if needed 
- xaio rp2040
- 12x through hole diodes
- 1x 0.91 inch OLED display
- 12x mx style switches
- 2x 1.25u keycaps, 10 1u keycaps
- 8x heatset inserts,  4 short 4 long, exacts in the CSV
- 4 screws 
