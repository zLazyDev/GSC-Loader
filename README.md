How this gsc loader works 

you will need to compile with gsc-tool its pretty simple to use compile to your selected game 

Supported Games



COD4 SP, MP

COD4 Portotype MARCH 23RD (MP), MAY 4TH (SP/MP), APRIL 11TH (MP), JUNE 11TH (SP/ MP)

WAW SP, MP, ZM

MW3 SP, MP

Ghosts MP, EX, SP

AW ZM, ES, MP, SP

BO3 MP, ZM

BO2 SP, MP, ZM

Ghosts Prototype May 21ST

007 QOS MP, SP

BO1 SP, ZM, MP

COD2 MP



How load the files


COD4 - WAW 

place file in game folder in raw script.gsc for MP SPscript.gsc for SP/ZM

MW3 AW Ghosts 

place file in game folder in raw script.gscbin

BO2 BO3

place file in game folder in raw script.gsc

BO1 

works kinda how infinity ops works same style

How Memory Options Work

WriteByte("address", "byte");

WriteBytes("address", "byte", "byte");

WriteString("Address", "string");

most is the same as WriteByte

RPC Example RPC("0x82239FD0", "0", "jump_height 999;"); <--- cbuf addtext

Read Memory is like Write

ReadByte("address");

ReadBytes("address", "how many to read - 4") will read 4 bytes

its all simple if you have any questions or issues message me on discord my discord is skidful

i will be updating this with new games as time goes on :)
