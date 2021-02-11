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

Lua
-----
```lua
print("Hello World")
```

Ocaml
-----
```ocaml
open Printf;;
Printf.printf "Hello World\n";;
```

Perl
-----
```perl
#!/usr/bin/perl

print "Hello World\n"
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

Python
-----
```python
#!/usr/bin/env python

if __name__ == '__main__':
    print("Hello World")
```

R
-----
```r
print("Hello World")
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

Scm_Chicken
-----
```SCM_Chicken
(print "Hello World");
```


