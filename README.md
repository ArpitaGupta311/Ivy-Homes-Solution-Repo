# Ivy-Homes-Solution-Repo
1:- Initially I tried, exploring different strings as query inputs (ex:- "ab" , "xyz" etc) and these were my observations:-
  a:- All the strings which were initialized by the string that I passed as my query input parameter were shown in the "results" container of the output in ascending order. (it was following ASCII system)
  b:- The following are the max counts corresponding to different versions:-
      VERSION 1:- 10
      VERSION 2:- 12
      VERSION 3:- 15
  c:- Version 1 only contains characters in 'a' to 'z'. No capital characters, no special symbols, no numbers.
      Version 2 only contains characters in 'a' to 'z' and '0' to '9'. No capital characters, and no special symbols.
      Version 3 contains characters in 'a' to 'z' , '0' to '9' and special symbols too ('+' , '-' etc). No capital characters.
  d:- If I just put query = "", then it starts with its first string and displays the strings in ascending order.
