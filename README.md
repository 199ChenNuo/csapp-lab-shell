1 chmod  
====  
 - chmod +x checktsh.pl  
 - chmod +x grade-shlab.pl  
 - chmod +x myint.c  
 - chmod +x myspin.c  
 - chmod +x mysplit.c  
 - chmod +x mystop.c  
 - chmod +x sdriver.pl  
 - chmod +x tsh.c  
 - chmod +x tshref  
----  
2 check tsh  
====  
## 1 checktsh.pl   
only print out differneces from refrence output  
- check signle file   
  ./checktsh.pl -t tracexx.txt  
- check all  
  ./checktsh.pl
- help  
  ./checktsh.pl -h
## 2 grade-shlab.pl  
- give the grade of tsh.c  
./grade-shlab.pl -f tsh.c  
## 3 make testxx  
- check single tracexx( using tsh )  
## 4 make rtestxx  
- check single refrence outout for tracexx( using tshref )  

----
3 other files' uses  
==== 
## 1 used in tsh/tshref
program that used in tsh/tshref  
- myint.c  
- myspin.c  
- mysplit.c  
- mystop.c  
## 2 trace file  
used for grade  
- trace01.txt
- ...
- trace16.txt  
## 3 tsh.c  
the program we should focus on  
## 4 tshref  
standard tiny shell  
## 5 tshref.out  
standard output of the tiny shell  
