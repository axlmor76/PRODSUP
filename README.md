# PRODSUP Question 1
1)fork the branch 
2 2)run test 
3 3)it hungs 
4 4)check changes 
5 5) there is some strange for 72000 + wait(1000) - try to speed up 
6 6) looks like the method is called many times.  
7 7) I don't see logic in this code. 
8 private void validate() throws IllegalArgumentException { 
9         for (int i=0; i<20*60*60; i++) { 
10             System.out.print('.'); 
11             try { 
12                 Thread.currentThread().sleep(1000); 
13             } catch (InterruptedException e) { 
14                 break; 
15             } 
16         } 
17 8) works without above code. 

