Teste de Python:

Neo tem um script de matriz complexo. O script da matriz é uma grade N X M de strings. Ele consiste em caracteres alfanuméricos, espaços e símbolos (!,@,#,$,%,&).
Para decodificar o script, Neo precisa ler cada coluna e selecionar apenas os caracteres alfanuméricos e conectá-los. Neo lê a coluna de cima para baixo e começa a leitura pela coluna mais à esquerda.

Se houver símbolos ou espaços entre dois caracteres alfanuméricos no script decodificado, Neo os substitui por um único espaço ' ' para melhorar a legibilidade.

Neo sente que não há necessidade de usar condições 'if' para a decodificação.

Formato de entrada:
A primeira linha contém dois inteiros separados por espaço, N (linhas) e M (colunas), respectivamente.
As próximas N linhas contêm os elementos das linhas da matriz script.

Restrições:
 • 0 < 𝑁
 • M < 100

Formato de saída:
Imprimir o script da matriz decodificado.

Amostra de Entrada:
Tsi
h%x
i #
sM 
$a 
#t%
ir!

Saída esperada:
This is Matrix#  %!

Explicação:
O script decodificado é:
This$#is% Matrix#  %!

Neo substitui os símbolos ou espaços entre dois caracteres alfanuméricos por um único espaço ' ' para melhor legibilidade.
Portanto, o script decodificado final é:
This is Matrix#  %!
