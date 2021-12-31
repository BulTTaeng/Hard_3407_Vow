# Hard_3407_Vow

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/Hard_3407_Vow/blob/main/3407_pro.PNG)

## What Algorithm should I use?

BFS and dynamic programing

## What was the key point and the hard part?

*Failed to solve by myself*

The length of the words in the list is 1 or 2.

Let's think that we are starting from the start of the target word.

For example, international.

There is 2 options at the front. i or in.

In here we notice that we can make a word i and in.

So, we will check the visit array [1] [2].

Then push the length of maded word ( until now maded word is i and in so we push 1 and 2)

After that we pop one element from the queue(that is gonaa be 1) and we start to compare target word[1] and word[1] + word[2].

we will doing this until we make a length of target array. If it is not possible , return NO.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
