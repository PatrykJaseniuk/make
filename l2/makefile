program: object.o
	cc object.o -o program

program2: object2.o
	cc object2

object.o: source.c
	cc -c source.c -o object.o 

source.c: 									
	echo "int main(){return 0;}" > source.c

