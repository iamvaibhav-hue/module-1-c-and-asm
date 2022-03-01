# Module-1 Week-2.5+4 (C and Assembly)

Welcome to the last week of Module-1 of YoS!! <br>
We will study **C programming** and **x86 assembly** for this week (and a half). <br>

**C** is a general-purpose programming language like **Python**. **C** is compiled language, unlike Python, which is interpreted.
The difference between compiled and interpreted languages is in their methods of execution. <br>
<br>
First, a bit of background... <br>
Computers can understand and run only machine instructions, but programmers usually code in high–level programming languages, such as C, Python, or Javascript. This is because high–level programming languages are easier to work with and resemble human languages and mathematical notation. However, computers cannot run the code written in a high–level language and hence, there is a need to translate it into simple machine instructions. <br>
As an aside, an **ELF** file essentially only stores these machine instructions (!!) and runs them on your CPU when you execute it through the command line. Assembly, which is also a part of this week's content, is just these machine instructions written down in a human-readable format.

<p align="center">
<img src="http://0x0.st/oPiH.jpg" alt="drawing" width="400"/>
</p>

Coming back to the point, to do this translation from programming language to machine instructions, we use **compilers** and **interpreters**. 
**Compilers** take a whole program as input and translate it to an executable binary code. The compilation step is required only once. Afterwards, we can run the binary code any number of times. **Interpreters** read and execute the program at hand instruction by instruction. After being read, each instruction is translated into the machine's binary code and run. Unlike compilers, the interpreters do not produce a binary executable file. Each time we run a program, we invoke the interpreter. It then reads and executes the program one instruction at a time. <br>
<br>
C is one of the earliest programming languages but is still in use today. As we have seen in the previous weeks, Linux and Python were both written in C! This makes learning C worthwhile. Also, C provides constructs that map directly to machine instructions, so it is better to learn C alongside Assembly. <br>

<p align="center">
  <img src="https://i.postimg.cc/hcDmyCZF/Screenshot-from-2022-03-01-12-14-32.png" alt="drawing" width="800"/> <br>
  Comparison of "Hello world" programs in Python, C and Assembly respectively
</p>

```
NOTE : We do not expect you to understand all the details of Assembly. We have two modules
       [Reverse Engineering and Binary Exploitation] to deal with them in greater depth.
       This week's content aims to teach you just the very basics.
```

### Introductory Videos
1. [C: Hello World!](https://www.youtube.com/watch?v=BuiX6vsiEfo) (9 mins)
2. [C: Pointers](https://www.youtube.com/watch?v=egRIkkBEttg) (8 mins)
3. [C: Arrays](https://www.youtube.com/watch?v=wbSj-Hq_b9s) (10 mins)
4. [x86 Assembly: Hello World!](https://www.youtube.com/watch?v=HgEGAaYdABA) (14 mins)
5. [Comparing C to machine language](https://www.youtube.com/watch?v=yOyaJXpAYZQ) (10 mins)
