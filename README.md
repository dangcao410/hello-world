![poster](img/hello-world.jpg)


Abap
-----
```abap
REPORT TEST.
WRITE 'Hello World'.
```

Ada
-----
```ada
with Ada.Text_IO;
use Ada.Text_IO;
procedure AdaHelloWorld is
begin
     Put_Line ("Hello World");
end AdaHelloWorld;
```

Algol
-----
```algol
BEGIN
FILE F (KIND=REMOTE);
EBCDIC ARRAY E [0:11];
REPLACE E BY "HELLO WORLD";
WHILE TRUE DO
  BEGIN
  WRITE (F, *, E);
  END;
END.
```

Amiga E
-----
```amiga_e
PROC main()
    WriteF('Hello, world\n')
ENDPROC
```

Apl
-----
```apl
'Hello, world'
```

Applescript
-----
```applescript
display dialog "Hello, world"
```

Arc
-----
```arc
(prn "Hello, World")
```

AutoIt
-----
```autoit
MsgBox( 0, "Hello World", "Hello, world" )
Exit
```

Awk
-----
```awk
BEGIN { print "Hello, world" }
```

Basic
-----
```basic
10 PRINT "Hello World"
20 END
```

Bash
-----
```bash
#!/usr/bin/bash

echo "Hello World";
```

Befunge
-----
```befunge
"dlroW olleH">:v
             ^,_@
```

Boo
-----
```boo
print "Hello, world"
```

Brainfuck
-----
```brainfuck
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++
..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
```

Casio BASIC
-----
```casiobasic
"HELLO, WORLD"
```

Ceylon
-----
```ceylon
void  hello ( )   { 
     print ( "Hello, World" ) ; 
  } 
```

Clojure
-----
```clojure
(ns hello-world.core
  (:gen-class))

(defn -main [& args]
  (println "Hello World"))
```

COBOL
-----
```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
    DISPLAY 'Hello, world'.
    STOP RUN.
```

CoffeeScript
-----
```coffeescript
hello = ->
  alert "Hello, world"
hello()
```

Common Lisp
-----
```commonlisp
(defun foo ()
  (format t "Hello, world"))

(with-output-to-string (*standard-output*)
  (foo))
```

C#
-----
```c#
using System;

class Program {
  static void Main() {
    Console.WriteLine("Hello World");
  }
}
```

C++
-----
```c++
#include <iostream>

int main(int argc, char** argv) {
  std::cout << "Hello World" << std::endl;
  return 0;
}
```

C
-----
```c
#include <stdio.h>

int main(int argc, char** argv) {
  printf("Hello World\n");
  return 0;
}
```

CSS
-----
```css
body::after {
  content: "Hello World";
}
```

Dart
-----
```dart
main()
{
  print('Hello world');
}
```

D
-----
```d
import std.stdio;

void main()
{
    writeln("Hello World");
}
```

Delphi
-----
```delphi
program ObjectPascalExample;

type
  THelloWorld = class
    procedure Put;
  end;

procedure THelloWorld.Put;
begin
  Writeln('Hello World');
end;

var
  HelloWorld: THelloWorld;

begin
  HelloWorld := THelloWorld.Create;
  HelloWorld.Put;
  HelloWorld.Free;
end.
```

ECL
-----
```ecl
D := DATASET([{'Hello'},{'World'}],{STRING Value;});
SD := SORT(D,Value);
output(SD)
```

Eiffel
-----
```eiffel
class
    HELLO_WORLD
create
    make
feature
    make
        do
            print ("Hello, world%N")
        end
end
```

Elixir
-----
```elixir
IO.puts "Hello World"
```

Emacs Lisp
-----
```emacslisp
( message  "Hello World" ) 
```

Erlang
-----
```erlang
% Module deliberately misspelt to avoid conflict with system module with same
-module(erlaang).
-export([hello_world/0]).

hello_world() -> io:fwrite("Hello World\n").
```

Forth
-----
```forth
: HELLO  ( -- )  CR ." Hello world" ; 

HELLO <cr>
Hello world
```

Fortran
-----
```fortran
program helloworld
     print *, "Hello world"
end program helloworld
```

F#
-----
```f#
printfn "Hello World\n"
```

Golang
-----
```golang
package main;

import "fmt"

func main() {
  fmt.Println("Hello World")
}
```

Golo
-----
```golo
module helloworld

function main = |args| {
  println("Hello World")
}
```

Gosu
-----
```gosu
print("Hello World")
```

Groovy
-----
```groovy
public class Main
{
  public static void main(String[] arguments)
  {
    println "Hello World"
  }
}
```

Haskell
-----
```haskell
main :: IO()
main = putStrLn "Hello World"
```

Hop
-----
```hop
( define - service  ( hello - world ) 
    ( < HTML > 
       ( < HEAD >  
 	 ( < TITLE >   "Hello world" ) ) 
       ( < BODY > 
 	 "Hello world" ) ) ) 
```

Html
-----
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Document</title>
</head>
<body>
  <h1>Hello World</h1>
</body>
</html>
```

Idris
-----
```idris
main: IO ()
main = putStrLn "Hello world"
```

Io
-----
```io
"Hello World" println
```

Java
-----
```Java
class Java {

  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

JavaScript
-----
```javascript
console.log("Hello World");
```

Julia
-----
```julia
println("Hello world")
```

Kotlin
-----
```kotlin
fun main(args : Array<String>) {
  println("Hello world")
}
```

LaTeX
-----
```latex
\documentclass{plain}
\begin{document}
Hello world
\end{document}
```

LiveScript
-----
```livescript
console.log "Hello world"
```

Logo
-----
```logo
print   [ Hello  world ] 
```

Logtalk
-----
```logtalk
?- write('Hello world'), nl.
Hello world
true.
```

LOLCODE
-----
```lolcode
HAI
CAN HAS STDIO?
VISIBLE "HAI WORLD"
KTHXBYE
```

Lua
-----
```lua
print("Hello World")
```

m4
-----
```m4
Hello world
```

Magic
-----
```magic
HELLO.WORLD

"Hello world"^#;
```

Mathematica
-----
```mathematica
Print [ "Hello world" ] 
```

MATLAB
-----
```matlab
classdef hello
    methods
        function doit(this)
            disp('Hello world')
        end
    end
end
```

Modula-2
-----
```modula2
MODULE HelloWorld;
FROM STextIO IMPORT WriteString;
BEGIN
  WriteString("Hello world");
END HelloWorld.
```

Nemerle
-----
```nemerle
class Hello
{
  static Main () : void
  {
    System.Console.WriteLine ("Hello world");
  }
}
```

Objective-C
-----
```cbjectivec
#import <Foundation/Foundation.h>

int main (int argc, const char * argv[])
{
        NSLog (@"Hello World");
        return 0;
}
```

Ocaml
-----
```ocaml
open Printf;;
Printf.printf "Hello World\n";;
```

Pascal
-----
```pascal
program HelloWorld(output);
begin
  WriteLn('Hello world')
end.
```

Perl
-----
```perl
#!/usr/bin/perl

print "Hello World\n"
```

PHP
-----
```php
<?php
    print 'Hello world';
?>
```

PL/SQL
-----
```pl-sql
SET  SERVEROUTPUT  ON ; 
  BEGIN 
      DBMS_OUTPUT . PUT_LINE ( 'Hello world' ) ; 
  END ; 
```

PostScript
-----
```postscript
%!
/Times-Roman 12 selectfont
20 20 moveto
(Hello world) show
showpage
```

Powershell
-----
```powershell
Write-Host "Hello, World"
```

Processing
-----
```processing
size(128, 128);
background(0);
textAlign(CENTER, CENTER);
fill(255);
text("Hello World", width / 2, height / 2);
```

Prolog
-----
```prolog
:- initialization(main).
main :- writef("%s\n", ["Hello World"]).
```

Pure
-----
```pure
extern int puts(char*);
hello = puts "Hello world";
hello;
```

Python
-----
```python
#!/usr/bin/env python

if __name__ == '__main__':
    print("Hello World")
```

QBasic
-----
```qbasic
PRINT "Hello World"
```

R
-----
```r
print("Hello World")
```

Racket
-----
```racket
#lang racket

(displayln "Hello world")
```

Rebol
-----
```rebol
view layout [text "Hello world" button "Quit" [quit]]
```

Rexx
-----
```rexx
say "Hello world"
```

Ruby
-----
```ruby
#!/usr/bin/ruby

print "Hello World\n"
```

Rust
-----
```rust
fn main() {
  println!("Hello World");
}
```

Scala
-----
```scala
object HelloWorld extends App {
  println("Hello world")
}
```

Scheme
-----
```scheme
(let ((hello0 (lambda() (display "Hello world") (newline))))
  (hello0))
```

Scm_Chicken
-----
```SCM_Chicken
(print "Hello World");
```

Shakespeare
-----
```shakespeare
Romeo, a young man with a remarkable patience.
Juliet, a likewise young woman of remarkable grace.
Ophelia, a remarkable woman much in dispute with Hamlet.
Hamlet, the flatterer of Andersen Insulting A/S.

                   Act I: Hamlet's insults and flattery.
                   Scene I: The insulting of Romeo.
[Enter Hamlet and Romeo]
Hamlet:
You lying stupid fatherless big smelly half-witted coward! You are as
stupid as the difference between a handsome rich brave hero and thyself!
Speak your mind!
You are as brave as the sum of your fat little stuffed misused dusty
old rotten codpiece and a beautiful fair warm peaceful sunny summer's
day. You are as healthy as the difference between the sum of the
sweetest reddest rose and my father and yourself! Speak your mind!
You are as cowardly as the sum of yourself and the difference
between a big mighty proud kingdom and a horse. Speak your mind.
Speak your mind!
[Exit Romeo]
                   Scene II: The praising of Juliet.
[Enter Juliet]
Hamlet:
Thou art as sweet as the sum of the sum of Romeo and his horse and his
black cat! Speak thy mind!
[Exit Juliet]
                   Scene III: The praising of Ophelia.
[Enter Ophelia]
Hamlet:
Thou art as lovely as the product of a large rural town and my amazing
bottomless embroidered purse. Speak thy mind!
Thou art as loving as the product of the bluest clearest sweetest sky
and the sum of a squirrel and a white horse. Thou art as beautiful as
the difference between Juliet and thyself. Speak thy mind!
[Exeunt Ophelia and Hamlet]

                   Act II: Behind Hamlet's back.
                   Scene I: Romeo and Juliet's conversation.
[Enter Romeo and Juliet]
Romeo:
Speak your mind. You are as worried as the sum of yourself and the
difference between my small smooth hamster and my nose. Speak your
mind!
Juliet:
Speak YOUR mind! You are as bad as Hamlet! You are as small as the
difference between the square of the difference between my little pony
and your big hairy hound and the cube of your sorry little
codpiece. Speak your mind!
[Exit Romeo]
                   Scene II: Juliet and Ophelia's conversation.
[Enter Ophelia]
Juliet:
Thou art as good as the quotient between Romeo and the sum of a small
furry animal and a leech. Speak your mind!
Ophelia:
Thou art as disgusting as the quotient between Romeo and twice the
difference between a mistletoe and an oozing infected blister! Speak
your mind!
[Exeunt]
```

Shellcode
-----
```shellcode
\xe9\x1e\x00\x00\x00  //          jmp    8048083 <MESSAGE>
\xb8\x04\x00\x00\x00  //          mov    $0x4,%eax
\xbb\x01\x00\x00\x00  //          mov    $0x1,%ebx
\x59                  //          pop    %ecx
\xba\x0f\x00\x00\x00  //          mov    $0xf,%edx
\xcd\x80              //          int    $0x80
\xb8\x01\x00\x00\x00  //          mov    $0x1,%eax
\xbb\x00\x00\x00\x00  //          mov    $0x0,%ebx
\xcd\x80              //          int    $0x80
\xe8\xdd\xff\xff\xff  //          call   8048065 <GOBACK>
\x48\x65\x6c\x6c\x6f\x2c\x20  //  "Hello, "
\x57\x6f\x72\x6c\x64\x21\x0d\x0a//"World\r\n"
```

Shell
-----
```shell
echo "Hello world"
```

Small Basic
-----
```smallbasic
TextWindow.WriteLine ( "Hello World" ) 
```

Smalltalk
-----
```smalltalk
Transcript show: 'Hello world'.
```

SNOBOL
-----
```snobol
  OUTPUT = 'Hello world'
 END
```
