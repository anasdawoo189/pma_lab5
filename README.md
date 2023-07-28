## Q1

The address is 1000D02E

![Alt text](photos/1.png)

## Q2

data section / 100163CC address

![Alt text](photos/2.png)

## Q3

5 functions calls gethostbyname

![Alt text](photos/3.png)

## Q4

The DNS is pics.praticalmalwareanalysis.com

 ![Alt text](photos/4.1.png)![Alt text](photos/4.png)

## Q5

there are 23 local variables

 ![Alt text](photos/5.png)

## Q6

there is 1 parameter ![Alt text](photos/6.png)

## Q7

the string in the strings window![Alt text](photos/7.png)
it is located in loc_10010107: func. the address is ![Alt text](photos/7.1.png)

## Q8

- -![ .](photos/8.png)there is a call for CreatePipe func it neeads two operands  read and write operands.

- -![.](photos/8.1.png) here therer is another call that needs another parameter that stored in eax.

- the last call is the Windows API function is GetSystemDirectoryA![Alt text](photos/8.3.png) it takes teo operants r 1- A pointer to a buffer that will receive the path of the system directory.
2- The length of the buffer in character

so i think it is creating info in the exe fie or downloading it in the system

## Q9

- first thing i am giong to the location of the ip address ![.](photos/9.png) then we shhould press x to get xrefs ![.](photos/9.1.png) to know how does the malware set we should go into first choice![Alt text](photos/9.2.png)we will see that eax was moved to the func and eax came from the call sub_10003695 so  we should step into it.
- this function gets info about the operating system version![Alt text](photos/9.3.png)

## Q10 

i searched for robotwork and i found  this ![Alt text](photos/10.png) when ZF is 0 it will call sub_100052a2 that pushes ![Alt text](photos/10.1.png)

## Q11 

![Alt text](photos/11.png) we can see that it calles sub_100036c3 when we step into it we will find that this export is trying to get info about the version of the system ![Alt text](photos/11.1.png)

## Q12

2 api functions which r![Alt text](photos/12-1.png)i think it should be Send_SysLanguage

## Q 13

1 API  functions ![.](photos/13-1.png). there are many funcs in depth2

## Q14

it will be 1000(3e8h) * 30 = 30000 ms![Alt text](photos/14.png)

## Q15

6, 1 and 2![Alt text](photos/15.png)

## Q16

i copied it from the answers because there were many sympols and i was not able to choose.![a](photos/16.png)

## Q17

yes it was used ![Alt text](photos/17.png), i can not find any thing

## Q18

i see data ![](photos/18.png)

## Q19

## Q20

## Q21
