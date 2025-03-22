# Helloworld Programs

![Hello, World!](helloworld.png)

We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!". Thespecified compiler or interpreter is required for each programming languages.

The table below summarizes the programs:

| Language | Language (Spec) Site | Section | Build / RunToolchain | Debian / UbuntuPackages |
| -------- | -------------------- | ------- | -------------------- | ----------------------- |
| C | The Standard - C | C | GCC | build-essential |
| C++ | The Standard - C++ | C++ | GCC / G++ |build-essential ,  g++ |
| Dlang | D Programming Language:Home | Dlang | GCC / GDC | build-essential ,  gdc |
| Go | The Go Programming Language | Go | Go | golang |
| Rust | Rust Programming Language | Rust | Rust |(Crate) rustlang |
| Java | Java Programming Language | Java | JDK |openjdk-17-jdk |
| x86_64assembly | x86 and amd64 instruction reference | x86_64 Assembly | GCC / GAS | build-essential |
| ARM64assembly | Arm A64 Instruction Set Architecture | ARM64 Assembly | GCC / GAS(AArch64) | build-essential |
| Bash | Bash Reference Manual | Bash | Bash | bash |
| Python | Welcome to Python.org | Python | Python | python |
| Ruby | Ruby Programming Language | Ruby | Ruby | ruby |
| PHP | PHP: Hypertext Preprocessor | PHP | PHP | php |
| Perl | The Perl Programming Language | Perl | Perl | perl |
| Lua | The Programming Language Lua | Lua | Lua | lua |

## C

```c
#include <stdio.h>

int main(void)
{       
    puts("Hello, World!");
    return 0;
}
```

Build with:

```console
gcc -Wall -o helloworld helloworld.c
```

Run with:

```console
./helloworld
```

## C++

```c++
# include <iostream>

int main()
{        
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

Build with:

```console
g++ -Wall -o helloworld helloworld.cpp
```

Run with:

```console
./helloworld
```

## Dlang

```D
import std.stdio;
void main()
{    
    writeln("Hello, World!");
}
```

Build with:

```console
gdc -Wall -o hellowor10/26/24, 10:32 AM workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md 9/9ld helloworld.cpp
```

Run with:

```console
./helloworld
```

## Go

```go
package main
import "fmt"
func main() {    
    fmt.Println("Hello, World!")
}
```

Build and run with:

```console
go run helloworld.go
```

## Rust

```Rust
fn main() {    
    println!("Hello, World");
}
```

Build with:

```console
rustc hello.rs
```

Run with:

```console
./helloworld
```

## Java

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");    
    }
}
```

Build with:

```console
javac HelloWorld.java
```

Run with:

```console
java HelloWorld
```

## x86_64 Assembly

Build with:

```console
TODO
```

Run with:

```console
./helloworld
```

## ARM64 Assembly

Build with:

```console
TODO
```

Run with;

```console
./helloworld
```

## Bash

```bash
echo "Hello, World!"
```

Run with:

```console
bash helloworld.sh
```

## Python

```python
print("Hello, World!")
```

Run with;

```console
python helloworld.py
```

## Ruby

```ruby
puts "Hello, World!"
```

Run with:

```console
ruby helloworld.rb
```

## PHP

```php
<?phpecho "Hello, World!"?>
```

Run with;

```console
./helloworld
```

## Perl

```perl
print("Hello, World!\n")
```

Run with:

```console
perl helloworld.pl
```

## Lua

```lua
print("Hello, World!")
```

Run with:

```console
lua helloworld.lua
```
