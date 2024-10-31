server: main.o 
		gcc -o server main.o\
		-Lpackages/sqlite/ -lsqlite3\
		-Lpackages/curl/include -lcurl

main.o : main.c
			gcc -c main.c