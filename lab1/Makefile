compileBison:
	bison -d bisonGrammar.y
compileFlex:
	lex flexGrammar.lex
build: compileBison compileFlex
	cc -ly lex.yy.c bisonGrammar.tab.c
clear:
	rm bisonGrammar.tab* lex.yy*  a.out