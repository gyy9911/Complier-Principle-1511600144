Compiler: lexical.l syntax.y main.c
	bison -d syntax.y
	flex lexical.l
	gcc main.c syntax.tab.c -lfl -ly -o complier
make clean:
	rm lex.yy.c
	rm syntax.tab.c
	rm syntax.tab.h
	rm complier

