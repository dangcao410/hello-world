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

Bash
-----
```bash
#!/usr/bin/bash

echo "Hello World";
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

Elixir
-----
```elixir
IO.puts "Hello World"
```

Erlang
-----
```erlang
% Module deliberately misspelt to avoid conflict with system module with same
-module(erlaang).
-export([hello_world/0]).

hello_world() -> io:fwrite("Hello World\n").
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

Haskell
-----
```haskell
main :: IO()
main = putStrLn "Hello World"
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


