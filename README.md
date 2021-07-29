# Inq-mc-aixi
This place primary prupose is to hold my ideas about this topic and to act as an initial sparking point to create useable, effective AIXI approximations. 
Don't forget the option to spot possible conclusion errors or similiar. 
I can also provide some terminal prompt commands in order to provide information on how to get started, such as how to compile Joel Venness's implementation.
When I succesfully manage to code the required changes, they will of course also be found here. I'm unfortunately not that experienced in programming.

## Main problem of current MC-AIXI approximations
According to my understanding the theory for how to build quite capable MC-AIXI's has been already elaborated by insanely intelligent humans.
My conclusion about the primary previous limiter for MC-AIXI's is: 

- An computationally affordable exploration method, that consists not of random exploration!!
Even when it would cost some precious calculations, random exploring exhibits the same intelligence as a toast that has not yet been toasted.
Intelligent exploration makes up the other 50% of an RE agent's intelligent behavior. Random exploration becomes in later stages so ineffective and inefficient for environments that consists of challenging state spaces (like playing partially observable pacman).

The solution for this has been worked out in the paper: A Strongly Asymptotically Optimal Agent in General Environments.  
Available at arXiv.org under the serial arXiv:1903.01021

## Overview of existing work
- There is one open source C++ MC (FAC-CTW) AIXI agent approximation out there, that is capable of performing multi thread MC tree search. This makes it a very important work. The creator is Joel Veness, his work can be downloaded from his homepage.
- A javaScript demo implementing an Inq-MC-AIXI agent approximation + demo environment. It's license is GPL-3.0. 
Found at GitHub: ejcatt/aixijs  ---> It's also very helpful since it is implementing the Inq algorithmus in programming language.  

[WIP]
