
Ever since you signed up for the October hackathon with ACM, you’ve had a spooky feeling that Halloween wasn’t going to be the same this year. While at last weeks meeting, you stumbled across an old file that had somehow gotten onto your computer. You decide to read the spooky.txt file. <br>

*Sir, these files contain the number of soldiers who were infected with the B-12 virus in the past 100 years. For each file I have indicated the number of lines contained. On each line I have written the year and the number of infected. I went ahead and encoded them using our cold war system.* <br>

Luckily, ACM has been able to decipher their numbering system. Your job is to transcribe the data, and let us know the sum of how many soldiers were infected between (x,y) years. <br>


The numbering system works using string of letters, where the sum of the letters values indicates the strings value.

C = 1 <br>
O = 5 <br>
L = 10 <br>
D = 50 <br>
W = 100 <br>
A = 500 <br>
R = 1000 <br>

COLDWAR = 1666 <br> 

Format of input: <br>
t a <br>
t a <br>
t a <br>
x y <br>

Where t is the number infected, and a is the year
x is the first year, and y is the last year for in which need to be summed

Constraints: <br>
0 <= t <= 1,000,000 <br>
0 < a <= 1,000,000 <br>

A sample input: <br>
~~~~
WORRLD WARR 
COLDWAR WARR 
WARCOLD WAR 
RRAW RRAWC
WAOLRD WOARDL 
WRRAAARR LRRA 
RWAOLDA WROLA 
RRA RRAWLCC
~~~~
A sample output:
~~~~
Total number infected between 2500 and 2612 is 12031
~~~~












