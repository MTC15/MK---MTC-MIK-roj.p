# MK---MTC-MIK-roj.p

 Elektronska ključavnica 1: Na voljo imate 9 tipk (številke 1 do 9 na tipkovnici 4x4 "keypad"). S pravilno kombinacijo 4 številk (npr. 6789) odpremo ključavnico (oranžna  LED).Pri vsaki drugi kombinaciji se ne spremeni nič. Da programsko kodo izbrišemo iz sistema pa pritisnemo *.



Kosovnica:
Arduino UNO,
Keypad 4x4,
vezalne žičke,
LED-dioda ( zelena),
upor 220E


Priredbeni seznam:

![image](https://user-images.githubusercontent.com/97598894/173774028-1476724b-74fe-4a5c-b422-83b7de21cc2b.png)





Vezalna shema frietzing:
  
![image](https://user-images.githubusercontent.com/97598894/173762098-50076617-0373-4181-ac34-dc1fc090e78c.png)




Slika vezja:



![20220615_085613](https://user-images.githubusercontent.com/97598894/173763056-f0a592fe-f7a8-43d1-b8a1-975bd0ba2b4e.jpg)



Videoposnetek delovanja:




https://user-images.githubusercontent.com/97598894/173775031-925a5fe5-35a4-4836-8981-bb6cd2c8eafa.mp4


Komentar na delovanje:
Program deluje v programskem jeziku C++, s pomočjo arduina,  LED-diod in keypad tipkovnice sva sprogramirala električno ključavnico. Deluje s pritiskom kode (2248) ki sproži signal za odklenitev ključavnice ( v tem primeru z zeleno LED-diodo). Če vtipkamo napačno kodo se signal ne sproži in vrne program v prvotno stanje.



