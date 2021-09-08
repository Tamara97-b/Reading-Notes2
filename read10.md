## What is a ‘call’?
The call() allows for a function/method belonging to one object to be assigned and called for a different object. call() provides a new value of this to the function/method. With call() , you can write a method once and then inherit it in another object, without having to rewrite the method for the new object.
## How many ‘calls’ can happen at once?
The maximal number of nested calls (including the first one) is called recursion depth. In our case, it will be exactly n . The maximal recursion depth is limited by JavaScript engine. We can rely on it being 10000, some engines allow more, but 100000 is probably out of limit for the majority of them
## What does LIFO mean?
is a method used to account for inventory that records the most recently produced items as sold first.
## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
#include <stdio.h> 
 2: 
 3: int mogrify(int a, int b){
 4:   int tmp = a*4 - b / 3;                  // First line of mogrify (mogrify)
 5:   return tmp;                             // (mogrify_return)
 6: }
 7: double truly_half(int x){
 8:   double tmp = x / 2.0;                   // First line of turly_half (truly_half)
 9:   return tmp;                             // (truly_half_return)
10: }
11: int main(){
12:   int a = 7, y = 17;                      // First line of main (main)
13:   int mog = mogrify(a,y);                 // Call to mogrify (mogrify_call)
14:   printf("Done with mogrify\n");          // (first_print)
15: 
16:   double x = truly_half(y);               // Call to truly_half (truly_half_call)
17:   printf("Done with truly_half\n");       // (second_print)
18: 
19:   a = mogrify(x,mog);                     // (mogrify2)
20: 
21:   printf("Results: %d %lf\n",mog,x);      // (last_print)
22:   return 0;                               // (main_return)
23: }
## What causes a Stack Overflow?
The most-common cause of stack overflow is excessively deep or infinite recursion, in which a function calls itself so many times that the space needed to store the variables and information associated with each call is more than can fit on the stack.
## What is a ‘refrence error’?
thrown when a code attempts to reference a non-existing variable.
## What is a ‘syntax error’?
are mistakes in using the language. Examples of syntax errors are missing a comma or a quotation mark, or misspelling a word. MATLAB itself will flag syntax errors and give an error message.
## What is a ‘range error’?
 thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value
## What is a ‘tyep error’?
object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.
## What is a breakpoint?
is an intentional stopping or pausing place in a program, put in place for debugging purposes. It is also sometimes simply referred to as a pause.
## What does the word ‘debugger’ do in your code?
used to identify coding errors at various development stages. They are used to reproduce the conditions in which error has occurred, then examine the program state at that time and locate the cause.
## Things I want to know more about
errors