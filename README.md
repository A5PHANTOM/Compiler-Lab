**For LEX+ YACC**

yacc –d  prgrmname.y

lex   prgrmname.l

gcc  y.tab.c  lex.yy.c  –ll -o prgrmname

./prgrmname


**FOR LEX**

lex FILENAME.l

gcc lex.yy.c 

./a.out

