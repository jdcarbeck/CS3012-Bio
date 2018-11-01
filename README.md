# Programming as we know it

React, Java, C++, C, Swift, all these languages and many more, and the software written in them, would not be around today if it wasn't for the A-0 (Arithmetic Language version 0) the first compiler for computers, which led to the creation of COBOL, arguably the most important programming languages of the 20th century.


Modern software is almost completely based upon the ability to compile higher level programming languages into the machine code that can be run on the CPUs of computers. The creation of compilers has had a massive impact on the way software can be developed and the problems software can address. With out compiler based programming there would not be languages that are almost as easy to understand as plain text.

```c
int min(int a, int b, int c) {
  int v=1;
  if(b < v){
    v = b;
  }
  if(c < v){
    v = c;
  }
}
return 0;
```

```assembly
min:    mov rax, rcx
        cmp rdx, rax
        jge min0
        mov rax, rdx
min0:   cmp r8, rax
        jge min1
        mov rax, r8
min1:   ret 0
```

 Above the example of a min function in both c and assembly shows compilers are able to abstract machine code into something that is easier to understand ultimately allowing for the creation of more complex programs.

Easier to write languages has meant that more and more people have been able to learn how write software and ultimately provide better solutions to the worlds problems. This significant advancement describing solutions to problems in a form that is more natural to humans yet translatable for execution on computers is largely result of one women, Grace Brewster Murray Hopper.

## Grace Brewster Murray Hopper

<p align="center">
  <img src="https://news.yale.edu/sites/default/files/styles/horizontal_image/public/d6_files/YaleNews_hopper-grace.UNIVAC.102635875-CC_0.jpg?itok=4HL3ETlO"/>
</p>

### Life

Grace Brewster Murray Hopper was born in New York City on December 9th 1906. Hopper received a BA in mathematics and physics from Vassar College in 1928. Hopper then went on to receive MA in 1930 and a PhD in mathematics at Yale University in 1934.

In December of 1943, Hopper joined the US Naval Reserve. From here she gained experienced with the Mark I computer, one of the computation machines. With the Mark I Hopper did various mathematical calculations as well as creating a manual for this computational machine. This manual explained how to set up the Mark I as well as the operating principals of computing machines in a general sense.

In 1949 Hopper was appointed as a research fellow in Computation Laboratory at Harvard University. She stayed here until she retired in 1971. It was at her time as a researcher that the A-0 compiler and the COBOL programming Language were developed.

### A-0 and COBOL

In 1951 Hopper designed the first compiler, A-0. Hoppers concept compilers differs from what a compiler is today but her implementation of the A-0 and subsequently the A-2 (1953) was based on the idea of building a easy to understand macro assembler.

The A-0 system was a set of instruction that described symbolic mathematical code into machine language. Hopper took all the subroutines that she had written over there years and gave them a call number so that the machine could find the location of the subroutine on the tape. As Hopper described:

> "All I had to do was to write down a set of call numbers, let the computer find them on the tape, bring them over and do the additions. This was the first compiler."

Her work on the A-0 and A-2 led her to her to the development of the first English-language data processing compiler, B-0. The A-2 compiler was the first compiler to be used extensively, grandmother to all modern programming language compilers.

## Impact on Me and Software Development

* Haskell and functional programming
* accessibility to software Development
* future software
