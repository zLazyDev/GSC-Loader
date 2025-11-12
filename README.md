How this gsc loader works 

you will need to compile with gsc-tool its pretty simple to use compile to your selected game 

Supported Games


COD2 MP, SP

COD4 SP, MP

COD4 PROTOTYPE MARCH 23RD (MP), MAY 4TH (SP/MP), APRIL 11TH (MP), JUNE 11TH (SP/ MP)

WAW SP, MP, ZM

WAW PROTOTYPE MARCH 27TH ( MP ), MAY 11TH ( SP )

MW2 SP

MW2 PROTOTYPE JULY 13TH MP, SP

BO1 SP, ZM, MP

MW3 SP, MP

BO2 SP, MP, ZM

GHOSTS MP, EX, SP

GHOSTS PROTOTYPE MAY 21ST (iw6mp_fast_server.exe) MAY 9TH (iw6mp_fast_server.exe) JULY 19TH (iw6mp_fast_server.exe)

AW ZM, ES, MP, SP

BO3 MP, ZM

007 QOS MP, SP

NX1 SP, MP



How load the files


COD4 - WAW 

place file in game folder in raw script.gsc for MP SPscript.gsc for SP/ZM

MW3 AW Ghosts 

place file in game folder in raw script.gscbin

BO2 BO3

place file in game folder in raw script.gsc

BO1, NX1, MW2 PROTOTYPE, MW2 RETAIL, GHOSTS PROTOTYPES

works kinda how infinity ops works same style

raw->maps->mp->gametypes->_playercards.gsc or _clientids.gsc (MP)
raw->maps->_hud.gsc (SP)

How Memory Options Work

Supported Games COD4 MP, 007 QOS MP

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
