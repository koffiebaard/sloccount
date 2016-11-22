# sloccount
Fork of David A. Wheeler's sloccount, which can be found [here](http://www.dwheeler.com/sloccount/). I added support for Javascript, Go and PDE (arduino), and added a bunch of bugfixes, like the faulty loc counting for GIT repos

It can count the lines of code in any project with the following languages:

Ada (.ada, .ads, .adb)
Assembly (.s, .S, .asm)
awk (.awk)
Bourne shell and variants (.sh)
C (.c)
C++ (.C, .cpp, .cxx, .cc)
C shell (.csh)
COBOL (.cob, .cbl) as of version 2.10
C# (.cs) as of version 2.11
Expect (.exp)
Fortran (.f)
Haskell (.hs) as of version 2.11
Java (.java)
lex/flex (.l)
LISP/Scheme (.el, .scm, .lsp, .jl)
Makefile (makefile) - not normally shown.
Modula-3 (.m3, .i3) as of version 2.07
Objective-C (.m)
Pascal (.p, .pas)
Perl (.pl, .pm, .perl)
PHP (.php, .php[3456], .inc) as of version 2.05
Python (.py)
Ruby (.rb) as of version 2.09
sed (.sed)
SQL (.sql) - not normally shown.
TCL (.tcl, .tk, .itk)
Yacc/Bison (.y)
Javascript (.js)
Go (.go)
Arduino (.pde)

To install sloccount from here, just `clone` & run `make install`. A more expanded explanation:

1) Clone the project

```
git clone git@github.com:wisc/sloccount.git
```

2) Install
```
cd sloccount
make install
```

3) Use it
```
sloccount ~/awesome_project/
```

Done!
