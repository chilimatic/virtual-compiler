# virtual-compiler
building a visualization for the basic compiler components with GO!


# Main Purpose

is Visualisation of what is really happening inside the machine on an abstract level. 
So I will add an virtual "visual" representation where you can step through the CPU cycles and see how the Parse tree is transformed into the Assembly Code and then executed. Based on the analysis of your code.

The CPU will be abstract and since modern CPUs are getting rather complex with multicores and associative caches plus DDR and DRAM and other combinations. And I only know the fundamentals about the mechatronics this maybe gets added some day.

It will be done with the Backus-Naur form.


# Project Outlines
- the user can define the tokens [lexical analysis]
- the user can define their parse rules [based on them a parse tree will be generated]
- the user can define their basic semantic rules and the code will be generated in  
- the user can store and load his project on my server as a git repository *
- the environment for the compiler will be inside a docker / rkt container so I can scale it better
- the user will get one of the l8er mentioned Compiled outputs


# Personal Targets
- based on the users syntax / token definition he can add a color for the semantics and should get syntax highlighting
- the user can see the visual representation of his AST transform to a assembler code and than be processed by the CPU**
- create some prepared programming language concepts to visualize for learning purposes
- add Left or Right Binary Trees for the AST


# Bonus Targets
- create an !!abstract!! visual representation of motherboard and show what's happening in this "virtual machine" per HZ so you can actually see what is happening inside a rudimentary computer built on the common  CPU architecture ! Maybe lateron with multicore setups etc but this would be getting ahead of myself.



# This project is planned to support the following OUTPUT CODES 
- MIPS with SPIM (as mentioned in COOL)
- GO! (main project for the compiled Code -> they compile really fast so i actually can let u use my server for compilations)
- C (for the purpose of beeing "old school")
- antlr (for the University Students - since java is a very ressource consuming language this will be last)

as you know there is a lot of semantic loss when you cross compile languages so the optimization, which is one of the major parts of modern language design,  will be left out for the moment. But you get the output code you can take it -> It's your property :) 



- * this so I can control the amount of data and what's in there.
- ** this will only be virtual to visualize what's happening
- *** the idea is to give the user something like the t. languages of Professor Achim Clausing or COOL of Professor Alexander Aiken
