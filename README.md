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

```
min:    mov rax, rcx
        cmp rdx, rax
        jge min0
        mov rax, rdx
min0:   cmp r8, rax
        jge min1
        mov rax, r8
min1:   ret 0
```

 Above the example of a print statement in python shows how with modern compilers complex functionality is able to be described almost as plain english. This accessibility through easy to write languages has meant that more and more people have been able to learn how write software and ultimately provide more solutions to the worlds problems. These advance in how solutions to problems have been able to be translated from something natural to humans and understandable for computers is largely to do with one women, Grace Brewster Murray Hopper.

## Grace Brewster Murray Hopper
