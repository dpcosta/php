# Variáveis e estruturas de controle

Faça uma página PHP que receba dois valores da query string, um para o peso e outro para a altura. Com esses dois valores, calcule o IMC segundo a fórmula abaixo. Exiba seu valor junto com uma mensagem de diagnóstico em um quadro com o seguinte comportamento: se o imc for menor que 20, o quadro será verde. Se estiver no intervalo 20 a 25, o quadro será amarelo. Se estiver acima de 25, o quadro será vermelho. Use as classes do Bootstrap para exibir o quadro com suas cores específicas.

## Fórmula do IMC
IMC = peso / (altura * altura)

## Exemplos para teste

| Peso (kg) | Altura (cm) | IMC   | Resultado |
|-----------|-------------|-------|-----------|
| 80        | 190         | 22,16 | Normal    |
| 93        | 181         | 28,39 | Sobrepeso |
| 87        | 162         | 33,15 | Obeso     |

## Diagnóstico

| Condição | Mensagem | Cor | 
| IMC entre 20 e 24,99 | Peso é normal.  | Verde  | 
| IMC entre 25 e 29,99 | Em sobrepeso.  | Amarelo  | 
| IMC acima de 30 | Em obesidade. | Vermelho | 
