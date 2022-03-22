# validador-cpf
Projeto rápido com algoritmo para validar um CPF

# como funciona o calculo: 

705.484.450-52 - 070.987.720-03 <br>

Primeiro digito: <br>

7x 0x 5x 4x 8x 4x 4x 5x 0x <br>
10 9  8  7  6  5  4  3  2 <br>
70 0  40 28 48 20 16 15 0 = 237 total da soma de todos os numeros <br>

11 - (237 % 11) = 5 (Primeiro dígito) / se for > 9 = 0 <br>


Segundo digito: <br>

7x 0x 5x 4x 8x 4x 4x 5x 0x 5x <br>
11 10 9  8  7  6  5  4  3  2 <br>
77 0  45 32 56 24 20 20 0  10 = 284 <br>

11 - (284 % 11) = 2 (Primeiro dígito) / se for > 9 = 0 <br>

