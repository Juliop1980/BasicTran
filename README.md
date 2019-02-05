# BasicTran

Traductor de BasicTran a Python usando la libreria PLY.

### Requisitos

Python 3.-

### Prueba ejemplo

Programa que recibe un entero y lo convierte a binario.

	with

		var a : int
		var temp : int
		var c: array [32] of int
		var aux: array[32] of int
		var k : int


	begin
		print 'I'; print 'n'; print 't'; print 'r'; print 'o'; print 'd'; print 'u'; print 'z'; print 'c'; print 'a';print ' ';
		print 'e';
		print 'l';
		print 'n';
		print 'u';
		print 'm';
		print 'e';
		print 'r';
		print 'o';
		print '\n';

		read(a);

		temp <- 0;
		while a /= 0 ->


			if (a%2 = 0) ->
				aux[temp] <- 0;

			otherwise ->
				aux[temp] <- 1;

			end

			a <- a/2;

			temp <- temp + 1;
		end

		k <-0;


		for k from 0 to temp-1 ->

			c[k] <- aux[temp- k- 1];

		end

		k <- 0;
		print('-');

		for k from 0 to temp-1->

			print(c[k]);

		end
	end

### Ejecucion
Se ejecuta ./BasicTran <Programa>


## Autores

Leonardo Lopez Almazan,  
Julio Perez


