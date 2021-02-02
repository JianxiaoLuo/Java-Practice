# Core Java Volume 1 - Fundamental
## 2.2
### How to understand the portability across operating systems, and automatic garbage collection?
Java has a fixed size for number types, which eliminates a major porting headache. Binary data is stored and transmitted in a fixed format, eliminating confusion about byte
ordering. Strings are saved in a standard Unicode format. The libraries that are a part of the system define portable interfaces. For
example, there is an abstract Window class and implementations of it for
UNIX, Windows, and the Macintosh.

The Java interpreter can execute Java bytecodes directly on any machine to
which the interpreter has been ported. Since linking is a more incremental
and lightweight process, the development process can be much more rapid
and exploratory.

### Dynamic
This is an important feature in situations where code needs to be added to a
running program. A prime example is code that is downloaded from the Internet
to run in a browser.