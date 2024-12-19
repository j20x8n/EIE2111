java c
Department of Electronic and Information Engineering 
EIE2111 Lab 6: Arrays and Vectors
Introduction 
This laboratory exercise is designed to give you hand-on   experience   in Arrays and Vectors.
Questions 
1.       A small   airline   has just purchased   a   computer   for   its   new   automated   reservation   system. You   have   been   asked   to   program   the   new   system. You   write   a   program   to   assign   seats   on   each   flight   of the   airline   (capacity:   6   seats). Your   program   should   display   the   following   menu   —Please   type   ‘0’ for   reservation, type ‘1’ for   checking   and type   ‘2’ for   exit.   If the person   types   0,   your   program   should prompt the user to input his/her name, the type of   seats (first class or economy class) and the number of   seats. Use   a   one-dimensional   array   of   objects   to   represent   the   seating   chart   of   the   plane. A   class should   be   provided   for   creating   objects   in   the   array.   The   class   should   include   two   parameters:   the   passenger’s name (a   string) and an integer to indicate whether   a   seat   is   occupied   or not.   Initialize   all   the   elements   (objects)   of the   array to   indicate that   all   seats   are   empty.   When   a   seat   is   assigned,   set   the corresponding integer to   1 to indicate that the seat is no longer available and also the passenger’s   name to reserve such seat. Your program should, of   course, never assign a seat that has   already been   assigned. When the   first   class   section is   full, your program   should   ask the   person   if   it   is   acceptable   to   be   placed    in   the    economy    section    (and   vice    versa).    If   yes,   then   make   the    appropriate    seat assignment. If   no, then print the message "Next flight leaves in   3 hours."  
The following is an example to create   an   array   of   objects:<代 写EIE2111 Lab 6: Arrays and VectorsC/C++
代做程序编程语言br>class   abc
{      }… 
int   main()
{
abc   arrayOfObjects   [10];
… 
}You may have a problem if   you use both   cin   and   getline   to read the input.   If   you   use   cin   first   and   then   getline,   you   need   to   put   a   dummy   getline   between   them   to   remove   the   newline   character from   cin.
2.       Write   a program   that   simulates   the   rolling   of two   dices.   The program   should use   rand   to   roll   the   first dice and should use   rand   again to roll the second   dice.   The   sum   of   the   two   values   should   then   be   calculated.   [Note: Each   dice   can   show   an   integer value between    1   and   6,   so   the   sum   of   the two   values   will   vary   from   2   to   12,   with   7   being   the   most   frequent   sum   and   2   and   12   being   the   least   frequent sums.] Note that there are 36 possible combinations of   the   two   dices. Your program   should   roll the two   dices   3,600 times. Use   a   one-dimensional   array to   store   the   frequencies   of   the   sums   of   the two   dices. Print the results in   a   tabular   format. Also,   determine   if   the   totals   are   reasonable   (i.e.,   there are six ways to roll a 7,   so approximately   one-sixth   of   all   the   rolls   should be   7).
3.       Combine the above two programs into one. The following   is   the   sample   output:

Instructions 
a.      You   are   required   to   submit   your   C++ programs   (the   whole   projects   created   in   Microsoft Visual   Studio 2019) in Question 3 to Blackboard. Zip all   of   them   into   a   single   file.
b.      The   deadline   of   the   submission: Check the course information.
c.      It is not required to create   any header   files   for the   above   exercises.   It   is   fine   if   all   program   codes   are in the main program.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
