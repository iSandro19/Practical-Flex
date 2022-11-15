FUENTE = practica1

PRUEBA1 = test/test1.txt
PRUEBA2 = test/test2.txt
PRUEBA3 = test/test3.txt
PRUEBA4 = test/test4.txt
PRUEBA5 = test/test5.txt
PRUEBA6 = test/test6.txt
PRUEBA7 = test/test7.txt
PRUEBA8 = test/test8.txt
PRUEBA9 = test/test9.txt

LIB = lfl

all: compile run

compile:
	flex $(FUENTE).l
	gcc -o $(FUENTE) lex.yy.c -$(LIB)

run:
	@echo -n "" > test/test1rtdo
	@./practica1 < test/test1.txt >> test/test1rtdo
	@cmp -s test/test1rtdo test/test1rtdo.txt && echo '### TEST 1: SUCCESS ###' || echo '### TEST 1: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test2rtdo
	@./practica1 < test/test2.txt >> test/test2rtdo
	@cmp -s test/test2rtdo test/test2rtdo.txt && echo '### TEST 2: SUCCESS ###' || echo '### TEST 2: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test3rtdo
	@./practica1 < test/test3.txt >> test/test3rtdo
	@cmp -s test/test3rtdo test/test3rtdo.txt && echo '### TEST 3: SUCCESS ###' || echo '### TEST 3: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test4rtdo
	@./practica1 < test/test4.txt >> test/test4rtdo
	@cmp -s test/test4rtdo test/test4rtdo.txt && echo '### TEST 4: SUCCESS ###' || echo '### TEST 4: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test5rtdo
	@./practica1 < test/test5.txt >> test/test5rtdo
	@cmp -s test/test5rtdo test/test5rtdo.txt && echo '### TEST 5: SUCCESS ###' || echo '### TEST 5: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test6rtdo
	@./practica1 < test/test6.txt >> test/test6rtdo
	@cmp -s test/test6rtdo test/test6rtdo.txt && echo '### TEST 6: SUCCESS ###' || echo '### TEST 6: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test7rtdo
	@./practica1 < test/test7.txt >> test/test7rtdo
	@cmp -s test/test7rtdo test/test7rtdo.txt && echo '### TEST 7: SUCCESS ###' || echo '### TEST 7: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test8rtdo
	@./practica1 < test/test8.txt >> test/test8rtdo
	@cmp -s test/test8rtdo test/test8rtdo.txt && echo '### TEST 8: SUCCESS ###' || echo '### TEST 8: WARNING (Files Are Not Identical!) ###'

	@echo -n "" > test/test9rtdo
	@./practica1 < test/test9.txt >> test/test9rtdo
	@cmp -s test/test9rtdo test/test9rtdo.txt && echo '### TEST 9: SUCCESS ###' || echo '### TEST 9: WARNING (Files Are Not Identical!) ###'

run1:
	@echo -n "" > test/test1rtdo
	@./practica1 < test/test1.txt >> test/test1rtdo
	@cat test/test1.txt
	@echo "\n\n"
	@cmp -s test/test1rtdo test/test1rtdo.txt && echo '### TEST 1: SUCCESS ###' || echo '### TEST 1: WARNING (Files Are Not Identical!) ###'

run2:
	@echo -n "" > test/test2rtdo
	@./practica1 < test/test2.txt >> test/test2rtdo
	@cat test/test2.txt
	@echo "\n\n"
	@cmp -s test/test2rtdo test/test2rtdo.txt && echo '### TEST 2: SUCCESS ###' || echo '### TEST 2: WARNING (Files Are Not Identical!) ###'

run3:
	@echo -n "" > test/test3rtdo
	@./practica1 < test/test3.txt >> test/test3rtdo
	@cat test/test3.txt
	@echo "\n\n"
	@cmp -s test/test3rtdo test/test3rtdo.txt && echo '### TEST 3: SUCCESS ###' || echo '### TEST 3: WARNING (Files Are Not Identical!) ###'

run4:
	@echo -n "" > test/test4rtdo
	@./practica1 < test/test4.txt >> test/test4rtdo
	@cat test/test4.txt
	@echo "\n\n"
	@cmp -s test/test4rtdo test/test4rtdo.txt && echo '### TEST 4: SUCCESS ###' || echo '### TEST 4: WARNING (Files Are Not Identical!) ###'

run5:
	@echo -n "" > test/test5rtdo
	@./practica1 < test/test5.txt >> test/test5rtdo
	@cat test/test5.txt
	@echo "\n\n"
	@cmp -s test/test5rtdo test/test5rtdo.txt && echo '### TEST 5: SUCCESS ###' || echo '### TEST 5: WARNING (Files Are Not Identical!) ###'

run6:
	@echo -n "" > test/test6rtdo
	@./practica1 < test/test6.txt >> test/test6rtdo
	@cat test/test6.txt
	@echo "\n\n"
	@cmp -s test/test6rtdo test/test6rtdo.txt && echo '### TEST 6: SUCCESS ###' || echo '### TEST 6: WARNING (Files Are Not Identical!) ###'

run7:
	@echo -n "" > test/test7rtdo
	@./practica1 < test/test7.txt >> test/test7rtdo
	@cat test/test7.txt
	@echo "\n\n"
	@cmp -s test/test7rtdo test/test7rtdo.txt && echo '### TEST 7: SUCCESS ###' || echo '### TEST 7: WARNING (Files Are Not Identical!) ###'

run8:
	@echo -n "" > test/test8rtdo
	@./practica1 < test/test8.txt >> test/test8rtdo
	@cat test/test8.txt
	@echo "\n\n"
	@cmp -s test/test8rtdo test/test8rtdo.txt && echo '### TEST 8: SUCCESS ###' || echo '### TEST 8: WARNING (Files Are Not Identical!) ###'

run9:
	@echo -n "" > test/test9rtdo
	@./practica1 < test/test9.txt >> test/test9rtdo
	@cat test/test9.txt
	@echo "\n\n"
	@cmp -s test/test9rtdo test/test9rtdo.txt && echo '### TEST 9: SUCCESS ###' || echo '### TEST 9: WARNING (Files Are Not Identical!) ###'

clean:
	rm $(FUENTE) lex.yy.c 