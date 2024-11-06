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
1. const :
  1. once the variable is assigned can be changed. the error will be thrown during compilation.
  2. the variable need to be initialised during declaration
  3. a pointer cant point to a const variable. Only a const pointer can point to a const variable (int *const p = &x)
  4. const reference does not require a memory variable to initialised.
2. auto :
   1. it is used to auto assignment of type during compilation.

## pointer
1. void pointer : this can point to any type of variable
2. pointer should always be initialised, else it will throw compilation error
3. pointer can assign to null pointer (nullptr)

## Reference 
int x =10
int y = 20
int &ref = x
ref = y 
print(ref,x,y)
ref = 20, x= 20, y=20

here x is referent, ref is reference, y is just a value
when reference need to point to some referent '&' is used 
reference cant be initialised without initialisation 
reference point to memory location of referent 
if reference is assigned to some value, referent also changed 
reference is just a different name of referent 

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

