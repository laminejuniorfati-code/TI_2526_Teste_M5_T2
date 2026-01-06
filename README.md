# Ficha de Avaliação - Folha de Cálculo - Turno 2 

## Instruções

* Esta avaliação é individual.

* Podes rever os exercícios previamente realizados.

* Faz um ***fork*** deste repositório.

![alt text](img/image.png)

* No teu ***fork***, edita o ficheiro **README.md**

![alt text](img/image-1.png)

* Utiliza os espaços indicados para responderes às questões.

* Não desformates o ficheiro.

* Quando terminares, realiza um ***Commit***

![alt text](img/image-2.png)

## Exercícios

1. Explica para que serve o sinal = numa folha de cálculo.
Indica duas situações em que se deve usar uma fórmula.
(3 valores)

Para calcular a soma de valores em um intervalo de células, como =SOMA(A1:A10).
Para determinar a média de um conjunto de dados, como =MÉDIA(B1:B5).


3. O que acontece a uma fórmula quando é copiada para outra célula?
Explica a tua resposta usando o conceito de referências de células.
(3 valores)
Quando uma fórmula é copiada para outra célula, as referências de células podem ser ajustadas automaticamente dependendo do tipo de referência usado Referências relativas (como A1) mudam relativamente à nova posição da célula, enquanto referências absolutas (como $ A $ 1) permanecem fixas. Por exemplo, se uma fórmula com referência relativa A1 for copiada de B2 para C3, ela se tornará B2 (ajustando linhas e colunas). Isso permite reutilizar fórmulas de forma eficiente, sem precisar editá-las manualmente.
        

4. Observa a seguinte fórmula, escrita na célula E4:

        =C4*$A$1

    a) Que tipo de referência é usada em A1? (1 valor)

        Resposta: ... Referência absoluta devido aos cifrões $ antes da letra e do número.

    b) O que acontece à referência C4 se a fórmula for copiada para E5? (1 valor)

        Resposta: ...A referência C4 muda para C5 porque é relativa, ajustando a linha.

5. Explica o que é a formatação condicional e indica duas regras que podem ser aplicadas a uma tabela.
(3 valores)

        Resposta: ...A formatação condicional é uma ferramenta que permite alterar automaticamente a aparência das células como cor de fundo, fonte ou bordas.
   Regra 1-Destacar células maiores que um valor específico, como células com vendas acima de 1000€ em verde.
   2-Formatar células que contenham texto específico, como células com "Aprovado" em preto.

7. Para que serve um filtro automático numa folha de cálculo?
Dá um exemplo prático relacionado com um inventário ou lista de dados.
(2 valores)

        Resposta: ...O filtro automático serve para exibir apenas as linhas de dados que atendem a critérios específicos, ocultando temporariamente os outros, ou que facilitam a análise de subconjuntos de informações sem alterar os dados originais.
   exemplo:Em um inventário de produtos, aplique um filtro para mostrar apenas itens com estoque abaixo de 10 unidades, ajudando a identificar produtos que precisam ser reabastecidos rapidamente.

9. Completa a frase corretamente (2 valores):

    Ordenar dados serve para ____________, enquanto filtrar dados serve para _____________.

        Resposta 1: ... organizar os dados em uma ordem específica
        Resposta 2: ...exibir apenas os dados que atendem a determinados critérios .

10. Para que serve um gráfico numa folha de cálculo?
Escolhe um tipo de gráfico e refere uma situação concreta em que possa ser usado.
(3 valores)

        Resposta: ...Um gráfico serve para representar visualmente dados numéricos de uma folha de cálculo facilitando a interpretação de tendências comparações e padrões de forma mais intuitiva do que tabelas de texto
  ESCOLHE  Gráfico de barras: um gráfico de barras pode ser usado para comparar as vendas de diferentes produtos ao longo de 12 meses, destacando quais produtos venderam mais em cada mês .
12. Escreve a fórmula necessária para calcular a prestação mensal de um empréstimo de 1000 €, a pagar em 24 meses, com taxa anual de 4%.
Não é necessário calcular o valor final.
(2 valores)

        Resposta: ...A fórmula no Excel para calcular a prestação mensal usando a função PMT é: =PMT(4%/12; 24; -1000).
Nota: A taxa é dividida por 12 para mensalmente, o número de períodos é 24, e o valor presente é negativo para indicação de empréstimo.
