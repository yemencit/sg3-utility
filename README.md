# sg3-utility
Can’t format hard disk from 528 to 512 have this problem failed: Illegal request because my hard disk is flash hard disk mean only read date can’t write in hard disk

users \Administrator\Desktop\sg3 utils-1.46mgw64›sg_format
--format --size 512 -V PD1
IBM-SSG
IBM-SSGSSH51P9
E1A2
peripheral type: disk [exe]
PROTECT=0
Unit serial number: HLK04EEJ0000822150Z3
LU name: 5000c500a181e568
mode sense (10) cdb: [5a 00 01 00 ee de ee de fe ee]
lode Sense (block descriptor) data, prior to changes:
Number of blocks=3637089792 [@xd8c99600]
Block size=528 [0x210]
mode select (10) cdb: [55 11 00 00 00 00 00 de 10 00]
node select (10):
ixed format, current; Sense key: Illegal Request
Idditional sense: Invalid field in parameter list
Field replaceable unit code: 17
Sense Key Specific: Error in Data parameters: byte 13 bit 7
ry MODE SELECT again with SP-@ this time
mode select (10) cob: [55 10 00 00 de de 00 00 1c 00]
ode select (10):
ixed format, current; Sense key: Illegal Request
dditional sense: Invalid field in parameter list
Field replaceable unit code: 17
Sense Key Specific: Error in Data parameters: byte 13 bit 7
ODE SELECT command: Illegal request, type: sense key, apart from Invalid opcode
