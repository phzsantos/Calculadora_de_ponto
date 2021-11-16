# Calculadora de ponto

**Calculadora de ponto para voltar do almoço**

Eu criei esse programa com intuito de calcular que horas eu vou voltar do almoço no trabalho, é, eu sei... dá pra fazer de cabeça, porém nada como automatizar coisas maçantes né....

**Logica por trás**

Primeiro eu tive que pegar 4 inputs do usuário, os dois primeiros sendo os da hora inicial e os dois ultimos sendo as horas que irão somar.

Segundo, eu somei tanto os minutos quanto as horas.

Terceiro, para resolver o problema de quando os minutos baterem 60 acrescentar 1 hora. Eu fiz um loop while:

```
Enquanto( total de minutos >= 60 )
{
	total de minutos = total de minutos - 60;
	horas++
}
```

Desse jeito, toda vez que os minutos passarem ou forem igual a 60, vai adicionar 1 hora no contador de hora e para não ficarmos no loop infinito, o total de minutos tem subtraido 60 minutos.

Quarto, apenas imprimi o resultado.

## Um pouco mais sobre esse projeto:

Originalmente esse repositorio foi originado de [Playing_with_cpp](https://github.com/phzsantos/Playing_with_CPP/tree/master/05-CalculadoraPonto), eu criei o repositorio Playing_with_cpp para fazer pequenos programas, fazer testes e etc. Porém, um dos programas em particular o 05 - Calculadora de ponto, eu uso quase todo dia e é o mais atualizado dentro do repositorio. Por isso, decidi separa-lo em um repositorio a parte para que no futuro eu consiga criar outras versões (mobile e desktop) e focar mais nele como um projeto em si. 
