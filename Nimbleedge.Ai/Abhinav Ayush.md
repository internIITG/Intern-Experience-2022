### Name : Abhinav Ayush
### Branch : CSE
### Email : Abhinav.ayush@iitg.ac.in
### Offer : Accepted

## Coding Round Experience
There were two CP questions. Both of them were based on dynamic programming, and were basic in nature. One was of knapsack type, and other was DP on trees. We had to solve both of them in about 1 hour, which was more than enough.

## Technical Round 1 Experience
- Duration : 1 hour
- Number of interviewers : 1
- This was conducted by professionals from an interview platform - InterviewVector. He first asked me to introduce myself and asked about one of my projects. I was asked to open my leetcode account, and the interviewer gave me a problem. This was already solved by me, which he could see by my submissions. After 4  such problems, we finally reached an unsolved problem, which was https://leetcode.com/problems/design-underground-system/.  I solved it with two unordered maps, and the interviewer was satisfied. He then asked me moderate questions from DBMS, mainly on indexing and how to do it, benefits and drawbacks of B-trees and hashing, which I was able to solve. He then asked me if I knew anything about System Design and its types. I didn’t. He then asked pretty easy questions from OOPs, and difficult ones based on pointers and the like. I was able to answer all from OOPs, and most of them from pointers. He then ended the interview and asked me if I had any questions. I asked about my performance, and he said that my speaking skills and solving skills were good, and I had to brush up on basic portions of C and DBMS. 
- Overall, this interview went well for me. This interview was one of the tougher ones I had given, and required knowledge from all topics - DBMS, OOPs, pointers, CP, etc. Prepare for all topics, and also System Design (if you can). All topics need not be good, but you should be good in CP, as he will ask questions about your code, and why you did what you did in quite detail. 

## Hr Experience
- Duration : 50 minutes
- Number of interviewers : 2
- This round was supposed to be of 30 minutes, but went on for about 50 minutes. It was taken by the two founders of the company, but one of them (the ML head) was silent for the entire interview (He was the main interviewer in the ML selection). The interviewer was very friendly and asked me to introduce myself first, and asked me why I wanted to join the SD role. He then gave me a problem with nested list:

 Given a nested list, determine the maximum depth.
 It is given in the form: [1,2,[3,4,[5,6],[7,[8],9]],11] 
 The brackets represent the next child.

 I said that I didn’t know the list data structure, and he asked me to take the input in whatever form I wanted. I took the input in string form, and solved it with the following algorithm:

 Int var=0, ans=0; 
 If (s[i]= ‘[‘) var++, ans= max(ans,var);
 If (s[i]= ‘]’) var–;

 The maximum depth is represented by ans. The interviewers were very surprised by my method, which took me about 2-3 minutes. He then asked me the time complexity, which is O(len), where len= length of the string. The rest of the interview was based on the actual work done by the company, and hence were very different from normal interview questions. He first asked me that if we had a pointer in Kotlin language, and it pointed to a certain location, and we had to use that data in C language, what would be the most appropriate steps. I answered that I would store the address of the pointer, and use the data stored from the pointer in C language with a header file (he said they existed) and something using a void pointer. The answer was wrong, but he was satisfied. He then asked questions like, 

- How would you delete the data used in Kotlin when writing code in C language?
- How would you implement garbage collection in C++?
- How would you check if a variable is useless in C++ (It is only declared and never used)?
- How would you use the string pointer from Kotlin as a char pointer in C?
- How would you implement your own smart pointer which works in GPU? (I didn’t even know what was GPU)

I didn’t know the answer to most of the problems, but I answered whatever I could think of, which he was apparently satisfied by. He then asked me basic questions from Automata Theory, DBMS and OOPs, which I was able to answer. Then we said our goodbyes and he ended the meeting.


## Company specific Tips/Some resources
- Prepare for all standard topics, and practice Competitive Programming regularly. 
- Study System Design if you get the time, and be familiar with all the concepts taught in CS101 and stuff related to it.