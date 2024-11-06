Ref : https://samsungu.csod.com/ui/lms-learning-details/app/onlineContent/79a6e877-c580-5b2c-bfe8-9ab91d2840fe

## Advantages of CPP compare to java
1. better performance, stability and portability
2. Available on almost all operating systems
3. No dependency on separate runtime
4. small memory foot print
5. standard c++ code can be easily ported to multiple platforms ( one app for window, android, ios) 

## build process 
1. preprocessing : 
the preprocessor process all the statements which starts with # or bound sign.
The header files is replaces by contain of the file. 
Every macros are expanded.
2. Compilation : 
checks the syntax and converts to object code
3. Linking :
The Object code is linked with the standard libraries

## Primitive Type 
### modifier : 
eg: signed,unsigned.short,long
### qualifiers : 
eg: const, volatile, static

## pointer
1. void pointer : this can point to any type of variable
2. pointer should always be initialised, else it will throw compilation error 
## Useful tips 
1. in cpp header file : limits.h all integeral limits (macros) are mentioned
2. in header file : cfloat.h all float limits (macros) are mentioned
3. any integer variable can be initialised with just curly bresses
   eg: int i = 5 === int i {1}
4. 

## important methods : 
1. cin.getline(<variable char array>,<max number of character expected>,<delimiter === the character to stop geting inputs eg: enter==='\n'>): takes input as string of size max size given, until the delimiter character is entered

## development tips : 
1. avoid copy initialisation (int i = 1). Prefer direct initialisation (int i {1})

