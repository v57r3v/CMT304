java c
Module Code:  CMT304 
Module Title:  Programming   Paradigms 
Assessment Title: Logic   Programming 
Assignment 
Consider the following situation:Patent   requests   are   submitted   to   the   patent   office   and   are   reviewed   by   members   of   the   tech-   nical board.   To find a   good   match between   patent   requests and   board   members   (referees),   every   member   of   the   technical   board   declares   their   expertise   for   each   submitted   request   that   needs   to   be   reviewed:
EXPERT,   KNOWLEDGEABLE,   FAMILIAR   or   INEXPERTFor   example,   declaring   EXPERT   for   a   given   patent   request,   means   “I   am   an   expert   on   the   topic   of   this   request”   .   The   goal   is   to   write   a   program   to   automate   this   process.   Using   a   list   of bids,   indicating the   level   of   expertise for   each   patent   request   and   board   member,   it   should   assign   each   submitted   patent   request   to   a   specific   number   of   n   members   of   the   technical   board such that
•   the   workloads   of   the   technical   board   members   are   approximately   equal, that   is, do   not differ by   more   than   m;
•    no   member of the technical   board   is   required to   review a   submission   that   is   placed   in   the   INEXPERT   category;
•    no member of the technical board is   required to   review   more thank   submissions from   the   FAMILIAR   category;
•   the total   number of cases when a   submission   is   assigned   to   a   member   who   placed   it   in the   EXPERT   category   is as   large as   possible.
The parameters n, mandk are arguments set when   calling the   program.
Task 1: Write   a   logic   program   in   ASP   which   finds   all   solutions   to   the   problem, given   n,   m,   k.Task   1:    Write   an   ASP   program   (coursework.lp)   that   solves   the   problem   for   any   instance.   Your   program   will   receive   as   input   a   set   bid/3 of   triples   mem, req, exp, such   that   the   member mem   has   declared   to   have   expertise   exp   for   request   req.    The   output   of   your   program   is   a set   assign/2   of   pairs   mem   and   req   such   that   the   member   mem   has   been   assigned   to   review request req.
Make   sure   you   document   your   code   so   it   is   clear   how   it   should   be   used   and   what   the   approach to solving the problem   is.   Document your code so the   following   is   clear.
1.    How   it   should   be   used.
2.   What   the   approach   to   solving   the   problem   is.    In   particular, you   need   to   explain what each   rule   achieves   and how the   rule   achieves   it.
Include your   name and student   id   in the comments.
Task 2: Write   a   short   report   on   logic   programming   related   to   the   problem:
1.    Provide, in   up   to   300 words, an   analysis   of   the   design   and   functioning   of   your   program   in   terms   of   the   Guess-and-Test   modeling   methodology.
The   word   limits   are   an   upper   limit,   not   a   target   length.    Text   longer   than   the   wor代 写CMT304 Logic ProgrammingR
代做程序编程语言d   limit   for   each point will   be   ignored.
Learning Outcomes Assessed 
•    Explain   the   conceptual   foundations, evaluate   and   apply   various   programming   paradigms,   such   as   logic,   functional,   scripting,   filter-based   programming,   pattern   matching   and   quantum computing, to solve practical   problems.
•    Discuss   and   contrast   the   issues, features, design   and   concepts   of   a   range   of   program-   ming paradigms and languages to be able to select   a   suitable   programming   paradigm   to   solve   a   problem.
Criteria for assessment 
Task 1: maximum   50   marks, assessed   according   to   the   following   scale
Fail 
0 
No code has been submitted. 
1 − 14 
Code does not run or does not produce valid output for any valid input; little to no relevant documentation. 
15 − 24 Code is valid without syntax errors and creates a valid output for every valid input (or produces a suitable error message for valid cases it cannot process). Even if the output is not a solution, a suitable attempt to solve the problem is visible. An attempt to document the code has been made. 
Pass 
25 − 29 Code is valid without syntax errors and creates a valid output for every valid input (or produces a suitable error message for valid cases it cannot process). A suitable attempt to solve the problem has been made, that will often find at least one solution (if there is any).    The attempt has been reasonably documented, but no consideration has been given to optimise the program’s performance. 
Merit 
30 − 34 Code is valid without syntax errors and creates a valid output for every valid input (or produces a suitable error message for valid cases it cannot process). A suitable attempt to solve the problem has been made, that will find all solutions (if there are any). The attempt has been well documented. 
Distinction 
35 − 50 Code is valid without syntax errors and creates a valid output for every valid input. A suitable attempt to solve the problem has been made, that will find all solutions (if there are any) for all problems, with excellent performance. The attempt has been well documented and clearly shows an effort to op- timise the program’s performance, e.g. by using efficient algorithms and data repres1entations and also some heuristics. 
Task 2: maximum   50   marks, assessed   according   to   the   following   scale
Fail 
0 
No document has been submitted. 
1 − 14 
At most an incomplete attempt to analyse the design and functioning of the program has been made. 
15 − 24 
An attempt has been made to analyse the design and functioning of the program. 
Pass 
25 − 29 
A suitable attempt has been made to analyse the design and functioning of the program. 
Merit 
30 − 34 
The analysis of the design and functioning of the program is well-developed, showing a clear understanding of the Guess-and-Test methodology. 
Distinction 
35 − 50 The analysis of the design and functioning of the program shows a clear understanding of the Guess-and-Test methodology and shows an under- standing of related performance issues. 





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
