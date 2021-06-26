---


---

<h1 id="prova-estrutura-metodo-de-ordenacao">PROVA-ESTRUTURA-METODO-DE-ORDENACAO</h1>
<h1 id="º-a.a.r.e---estrutura-de-dados"><img src="https://www.calendariodovestibular.com.br/wp-content/uploads/2013/03/post_unipar.png" alt="UNIPAR "><br>
2º A.A.R.E - ESTRUTURA DE DADOS</h1>
<h2 id="métodos-de-ordenação">Métodos de Ordenação</h2>
<h3 id="acadêmico-felipe-castro-pontes">Acadêmico: Felipe Castro Pontes</h3>
<h3 id="r.a-00210466">R.A: 00210466</h3>
<h3 id="orientador-geferson-luis-simonette">Orientador: Geferson Luis Simonette</h3>
<hr>
<h5 id="toledo-27062021">Toledo, 27/06/2021</h5>
<hr>
<h2 id="bubble-sort">Bubble Sort</h2>
<ul>
<li>O Bubble-Sort basicamente consiste em percorrer os N elementos de um vetor, para cada vez percorrida, todos os elementos são comparados com o seu próximo, para verificar se estão na ordem desejada. <img src="http://www.universidadejava.com.br/images/2020-05-17-bubble-sort-01.png" alt="Execução do algoritmo Bubble Sort."></li>
<li>Na primeira iteração, é encontrado o maior elemento e o mesmo é deslocado até a ultima posição. Na segunda iteração, é encontrado o segundo maior elemento e o mesmo é deslocado até a penúltima posição. Continua até que todos os elementos serem ordenados.</li>
<li>O Bubble Sort realiza múltiplas passagem por uma lista. Ele compara itens adjacentes e troca aqueles que estão fora de ordem. Cada passagem pela lista coloca o próximo maior valor na sua posição correta. Em essência, cada item se desloca como uma “bolha” para a posição à qual pertence. A ideia fundamental é fazer uma série de comparações entre os elementos do vetor.</li>
<li>Quando dois elementos estão fora de ordem, há uma inversão e esses dois elementos são trocados de posição, ficando em ordem correta. Assim, o primeiro elemento é comparado com o segundo. Se uma inversão for encontrada, a troca é feita.</li>
<li>Em seguida, independente se houve ou não troca após a primeira comparação, o segundo elemento é comparado com o terceiro, e, caso uma inversão seja encontrada, a troca é feita. O processo continua até que o penúltimo elemento seja comparado com o último.</li>
<li>Com este processo, garante-se que o elemento de maior valor do vetor será levado para a última posição. A ordenação continua, posicionando o segundo maior  elemento, o terceiro, etc., até que todo o vetor esteja ordenado.</li>
</ul>
<ul>
<li>Uma função que implementa esse algoritmo. A função recebe como parâmetros o número de elementos e o ponteiro do primeiro elemento do vetor que se deseja ordenar.</li>
</ul>
<h1 id="ordenação-de-dados">Ordenação de Dados</h1>
<p>Ordenação é o ato de se colocar os elementos de uma sequência de informações,<br>
ou dados, em uma ordem predefinida. O termo técnico em inglês para ordenação é sorting, cuja tradução literal é “classificação”</p>
<hr>
<hr>
<h2 id="selection-sort">Selection Sort</h2>
<ul>
<li>
<ul>
<li>É basicamente um algoritmo de classificação que seleciona o menor elemento de uma lista não classificada em cada iteração e coloca esse elemento no início da lista não classificada. Ordenação por seleção do inglês, “selection sort” é um algoritmo de ordenação baseado em se passar sempre o menor valor do vetor para a primeira posição ou o maior dependendo da ordem requerida, depois o de segundo menor valor para a segunda posição, e assim é feito sucessivamente com os {n-1} n-1 elementos restantes, até os últimos dois elementos.</li>
</ul>
</li>
<li>
<ul>
<li>O selection sort compara a cada interação um elemento com os outros, visando encontrar o menor. Dessa forma, podemos entender que não existe um melhor caso mesmo que o vetor esteja ordenado ou em ordem inversa serão executados os dois laços do algoritmo, o externo e o interno. Algoritmo breve de como faz para ordenar os números, assumimos que o menor elemento está no índice 0: encontra o índice do menor elemento</li>
</ul>
</li>
</ul>
<h3 id="exemplo">Exemplo</h3>
<ol>
<li>
<p>Defina o primeiro elemento como <code>minimum</code>.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/w1ZKsO2Obaw1WV03_lamX22SVyapwhbiKoLkT5Raiiw/mtime:1582112622/sites/tutorial2program/files/Selection-sort-0-initial-array.png" alt="Etapas de classificação de seleção" title="Nova matriz inicializada"></p>
<p>Selecione o primeiro elemento como mínimo</p>
</li>
<li>
<p>Compare <code>minimum</code>com o segundo elemento. Se o segundo elemento for menor que <code>minimum</code>, atribua o segundo elemento como <code>minimum</code>.</p>
<p>Compare <code>minimum</code>com o terceiro elemento. Novamente, se o terceiro elemento for menor, atribua <code>minimum</code>ao terceiro elemento, caso contrário, não faça nada. O processo continua até o último elemento.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/9jjqXX0fGtJE2ul2Mga20fvf_GkNlFAFsDMwrrwFzbQ/mtime:1582112622/sites/tutorial2program/files/Selection-sort-0-comparision.png" alt="Etapas de classificação de seleção" title="comparação"></p>
<p>Compare o mínimo com os elementos restantes</p>
</li>
<li>
<p>Após cada iteração, <code>minimum</code>é colocado na frente da lista não classificada.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/6o-qergdHNq6D7eBxBi87yIuCLc7MJy2BHR4QHeNxxQ/mtime:1582112622/sites/tutorial2program/files/Selection-sort-0-swapping.png" alt="Etapas de classificação de seleção" title="trocando"></p>
<p>Troque o primeiro pelo mínimo</p>
</li>
<li>
<p>Para cada iteração, a indexação começa a partir do primeiro elemento não classificado. As etapas 1 a 3 são repetidas até que todos os elementos sejam colocados em suas posições corretas.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/VPGtdVYag2vfHBotOaFEiYLqvWAD_Jwfnwur_AtKQHo/mtime:1582112622/sites/tutorial2program/files/Selection-sort-0.png" alt="Etapas de classificação de seleção" title="Etapa 0 de classificação de seleção"></p>
<p>A primeira iteração</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/hgxXpCSrHui7tbyJUQNnh8N5l8MPbdbL6dlstS4-G3M/mtime:1582112622/sites/tutorial2program/files/Selection-sort-1.png" alt="Etapas de classificação de seleção" title="Etapas de classificação de seleção 1"></p>
<p>A segunda iteração</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/mDT4W_wUoS9eYT1JoUWjZuh4XBVXGDuiV9cr4Rylggk/mtime:1582112622/sites/tutorial2program/files/Selection-sort-2.png" alt="Etapas de classificação de seleção" title="Etapas de classificação de seleção 2"></p>
<p>A terceira iteração</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/dsZIa58W_SRP0yB21QmrWGQvrmob8yAVa94iCtIPWoo/mtime:1582112622/sites/tutorial2program/files/Selection-sort-3_1.png" alt="Etapas de classificação de seleção" title="Etapas de classificação de seleção 3"></p>
<p>A quarta iteração</p>
</li>
</ol>
<hr>
<h2 id="insertion-sort">Insertion Sort</h2>
<ul>
<li>Insertion sort funciona basicamente assim, primeiro compara-se dois elementos. Se o primeiro for maior que o segundo, compara-se o elemento com os seus anteriores até encontrar um elemento anterior menor.  É feita uma única passagem, mas com vários retornos.  O procedimento é encerrado quando ordena-se o elemento da última posição do vetor</li>
<li>O Insertion Sort inicia a ordenação dividindo o vetor em duas partições: uma ordenada à esquerda e outra não ordenada à direita. Inicialmente, a partição esquerda só terá um elemento é o caso trivial da ordenação.</li>
<li>A inserção dos elementos na partição ordenada é realizada em duas etapas. Na primeira etapa, procuramos a posição de inserção. Na segunda etapa, deslocamos os elementos da esquerda para a direita para que a posição de inserção fique livre para que o elemento seja inserido.</li>
<li>A classificação por inserção é um algoritmo de classificação que coloca um elemento não classificado em seu lugar adequado em cada iteração. A classificação por inserção funciona da mesma forma que classificamos as cartas em nossa mão em um jogo de cartas. Presumimos que o primeiro cartão já está classificado, então selecionamos um cartão não classificado. Se o cartão não classificado for maior do que o cartão em mãos, ele é colocado à direita, caso contrário, à esquerda. Da mesma forma, outras cartas não classificadas são retiradas e colocadas em seus devidos lugares.</li>
</ul>
<h3 id="exemplo-1">Exemplo</h3>
<p>Suponha que precisamos classificar o seguinte array.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/K-kSm72ww4_afH0mQJDuR3Y-fPZYgBYo_Pclx7WlYUo/mtime:1582112622/sites/tutorial2program/files/Frame%204_0.png" alt="Etapas de classificação de inserção" title="Matriz inicial"></p>
<p>Matriz inicial</p>
<ol>
<li>
<p>O primeiro elemento na matriz é considerado classificado. Pegue o segundo elemento e armazene-o separadamente em <code>key</code>.</p>
<p>Compare <code>key</code>com o primeiro elemento. Se o primeiro elemento for maior que <code>key</code>, entãochave é colocado na frente do primeiro elemento.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/l-X2VCkF2rp4i0X8mZX6BGJL_FQW9EL8PkKhBswQfpc/mtime:1582112622/sites/tutorial2program/files/Insertion-sort-0_1.png" alt="Etapas de classificação de inserção" title="Etapa 0 de classificação por inserção"></p>
<p>Se o primeiro elemento for maior que a chave, a chave será colocada na frente do primeiro elemento.</p>
</li>
<li>
<p>Agora, os primeiros dois elementos estão classificados.</p>
<p>Pegue o terceiro elemento e compare-o com os elementos à esquerda dele. Coloque-o logo atrás do elemento menor que ele. Se não houver nenhum elemento menor do que ele, coloque-o no início da matriz.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/MqcrLAaQHEhcuJTmF_m712GG_wMemTY9AID0J9w4T6E/mtime:1582112622/sites/tutorial2program/files/Insertion-sort-1_1.png" alt="Etapas de classificação de inserção" title="Etapa 1 de classificação por inserção"></p>
<p>Coloque 1 no início</p>
</li>
<li>
<p>Da mesma forma, coloque cada elemento não classificado em sua posição correta.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/hWFdFWWU0lZD2xWGz0CoMDESnjYa9Wg1HwpH99jTTH0/mtime:1582112622/sites/tutorial2program/files/Insertion-sort-2_2.png" alt="Etapas de classificação de inserção" title="Etapa 2 de classificação por inserção"></p>
<p>Coloque 4 atrás de 1</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/TxAcrgHKfahw_BPEIKwCWB9BY2GNiI91yzWeetMfG9Q/mtime:1582112622/sites/tutorial2program/files/Insertion-sort-3_2.png" alt="Etapas de classificação de inserção" title="Etapa 3 de classificação por inserção"></p>
<p>Coloque 3 atrás de 1 e a matriz é classificada</p>
</li>
</ol>
<hr>
<h2 id="quick-sort">Quick sort</h2>
<ul>
<li>
<ul>
<li>O algoritmo quicksort é o algoritmo de ordenação interna mais rápido que se conhece para uma ampla variedade de situações.</li>
</ul>
</li>
<li>A idéia básica é dividir o problema de ordenar um conjunto com n itens em dois sub-problemas menores.  Os problemas menores são ordenados independentemente.  Os resultados são combinados para produzir a solução final.</li>
<li>Algoritmo de ordenação mais utilizado no desenvolvimento de aplicações. Mesmo quando temos os dados organizados em listas encadeadas, e precisamos colocá-los de forma ordenada, em geral, optamos por criar um vetor temporário com ponteiros para os nós da lista, fazer a ordenação usando quicksort e reencadear os nós montando a lista ordenada.</li>
</ul>
<h3 id="exemplo-2">Exemplo</h3>
<p><strong>1. Selecione o elemento pivô</strong></p>
<p>Existem diferentes variações de quicksort, onde o elemento pivô é selecionado em diferentes posições. Aqui, estaremos selecionando o elemento mais à direita da matriz como o elemento pivô.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/7qpYqe1UtqYbKzIBY_W8ljqkUz9iS6jZGobim6LDhtM/mtime:1582112622/sites/tutorial2program/files/quick-sort-0.1_0.png" alt="Etapas de classificação rápida" title="Seleção do elemento mais à direita"></p>
<p>Selecione um elemento pivô</p>
<p><strong>2. Reorganizar a matriz</strong></p>
<p>Agora, os elementos da matriz são reorganizados de forma que os elementos menores que o pivô sejam colocados à esquerda e os elementos maiores que o pivô à direita.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/1Xn_e4xeHQjOsXExVhTgVbggPgpMk9WV4Z8gxmZgdyg/mtime:1582112622/sites/tutorial2program/files/quick-sort-0.2_0.png" alt="Etapas de classificação rápida" title="girando"></p>
<p>Coloque todos os elementos menores à esquerda e maiores à direita do elemento pivô</p>
<p>Veja como reorganizamos a matriz:</p>
<ol>
<li>
<p>Um ponteiro é fixado no elemento pivô. O elemento pivô é comparado com os elementos que começam no primeiro índice.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/zaN86RZ0WfV0PhWpWDhis-f9lWlfgKJt_liYoGjZAIk/mtime:1617189498/sites/tutorial2program/files/quick-sort-partition-first-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>Comparação do elemento pivô com o elemento começando no primeiro índice</p>
</li>
<li>
<p>Se o elemento for maior do que o elemento pivô, um segundo ponteiro é definido para esse elemento.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/RzFeResnC88JRu9IFh2YqUKZMXltQ51EeiioINCMcEA/mtime:1617189487/sites/tutorial2program/files/quick-sort-partition-second-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>Se o elemento for maior do que o elemento pivô, um segundo ponteiro é definido para esse elemento.</p>
</li>
<li>
<p>Agora, o pivô é comparado com outros elementos. Se um elemento menor que o elemento pivô for alcançado, o elemento menor será trocado pelo elemento maior encontrado anteriormente.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/QA-TsXFkcz3cNyJikcbIWxepFVDu8ntl220KzlG8zdw/mtime:1617189492/sites/tutorial2program/files/quick-sort-partition-third-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>O pivô é comparado com outros elementos.</p>
</li>
<li>
<p>Novamente, o processo é repetido para definir o próximo elemento maior como o segundo ponteiro. E, troque-o por outro elemento menor.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/tMmdAbX5gev9K20XI1kzQ3n932vSjnN1MszZouHV7Yc/mtime:1617189469/sites/tutorial2program/files/quick-sort-partition-fourth-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>O processo é repetido para definir o próximo elemento maior como o segundo ponteiro.</p>
</li>
<li>
<p>O processo continua até que o penúltimo elemento seja alcançado.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/MNYV977xf4N3cgCpAtkB1KDyPqyG9OvlKSkHSdd0kys/mtime:1617189475/sites/tutorial2program/files/quick-sort-partition-fifth-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>O processo continua até que o penúltimo elemento seja alcançado.</p>
</li>
<li>
<p>Finalmente, o elemento pivô é trocado pelo segundo ponteiro.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/lAMcHRRzL8TJEh7bjY3rAufTTy3y5-o4Nt0z5L1AB8A/mtime:1617189481/sites/tutorial2program/files/quick-sort-partition-sixth-step.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>Finalmente, o elemento pivô é trocado pelo segundo ponteiro.</p>
</li>
</ol>
<p><strong>3. Divide Subarrays</strong></p>
<p>Os elementos do pivô são novamente escolhidos para as subpartes esquerda e direita separadamente. E, a <strong>etapa 2</strong> é repetida.</p>
<p><img src="https://cdn.programiz.com/cdn/farfuture/dK3pGyiHqFZOYklwABPBZ4zq_VZU1dMWBIbWhHJ-Rgw/mtime:1617189464/sites/tutorial2program/files/quick-sort_1.png" alt="Etapas de classificação rápida" title="Etapas de classificação rápida"></p>
<p>Selecione o elemento pivô de em cada metade e coloque no lugar correto usando recursão</p>
<p>Os subarrays são divididos até que cada subarray seja formado por um único elemento. Neste ponto, a matriz já está classificada.</p>
<h3 id="estudo-dos-casos-de-uso">Estudo dos casos de uso</h3>
<p>– Foram testadas 3 ordens de listas com 3 tamanhos diferentes cada:</p>
<ul>
<li>Ordem 1: lista ordenada em ordem crescente.</li>
<li>Ordem 2: lista ordenada em ordem decrescente.</li>
<li>Ordem 3: lista desordenada com números aleatórios.</li>
</ul>
<hr>
<h3 id="lista-1---comparativos">Lista 1 - Comparativos</h3>
<ul>
<li><strong>Tamanho do vetor: 100</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>0,0988</td>
<td>5050</td>
<td>0</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>0,0602</td>
<td>4950</td>
<td>297</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>0,0038</td>
<td>99</td>
<td>198</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,0141</td>
<td>606</td>
<td>189</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 1000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>9,5451</td>
<td>500500</td>
<td>0</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>5,4587</td>
<td>499500</td>
<td>2997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>0,0359</td>
<td>999</td>
<td>1998</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,1602</td>
<td>9009</td>
<td>1533</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 10000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>934,5364</td>
<td>50005000</td>
<td>0</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>508,5891</td>
<td>49995000</td>
<td>29997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>0,3558</td>
<td>9999</td>
<td>19998</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>2,0824</td>
<td>125439</td>
<td>17712</td>
</tr>
</tbody>
</table><hr>
<h3 id="lista-2---comparativos">Lista 2 - Comparativos</h3>
<ul>
<li><strong>Tamanho do vetor: 100</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>0,2045</td>
<td>5050</td>
<td>14850</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>0,0750</td>
<td>4950</td>
<td>297</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>0,1173</td>
<td>99</td>
<td>5148</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,0147</td>
<td>610</td>
<td>336</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 1000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>20,3377</td>
<td>500500</td>
<td>1498500</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>6,9038</td>
<td>499500</td>
<td>2997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>11,4277</td>
<td>999</td>
<td>501498</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,1622</td>
<td>9016</td>
<td>3030</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 10000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>1838,0272</td>
<td>50005000</td>
<td>149985000</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>665,2050</td>
<td>49995000</td>
<td>29997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>1074,1171</td>
<td>9999</td>
<td>50014998</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>2,1279</td>
<td>125452</td>
<td>32712</td>
</tr>
</tbody>
</table><hr>
<h3 id="lista-3---comparativos">Lista 3 - Comparativos</h3>
<ul>
<li><strong>Tamanho do vetor: 100</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>0,1596</td>
<td>5050</td>
<td>6777</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>0,0698</td>
<td>4950</td>
<td>297</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>0,0570</td>
<td>99</td>
<td>2457</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,0314</td>
<td>897</td>
<td>576</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 1000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>16,6730</td>
<td>500500</td>
<td>756840</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>5,6664</td>
<td>499500</td>
<td>2997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>5,7523</td>
<td>999</td>
<td>254278</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>0,3725</td>
<td>13138</td>
<td>7983</td>
</tr>
</tbody>
</table><ul>
<li><strong>Tamanho do vetor: 10000</strong></li>
</ul>

<table>
<thead>
<tr>
<th>Algoritmo</th>
<th>Tempo (ms)</th>
<th>Comparações</th>
<th>Movimentações</th>
</tr>
</thead>
<tbody>
<tr>
<td>Bubble Sort</td>
<td>1455,9734</td>
<td>50005000</td>
<td>74237889</td>
</tr>
<tr>
<td>Selection Sort</td>
<td>545,1068</td>
<td>49995000</td>
<td>29997</td>
</tr>
<tr>
<td>Insertion Sort</td>
<td>539,6891</td>
<td>9999</td>
<td>24765961</td>
</tr>
<tr>
<td>Quick Sort</td>
<td>4,5072</td>
<td>176065</td>
<td>103635</td>
</tr>
</tbody>
</table><hr>
<h2 id="conclusão">Conclusão</h2>
<ul>
<li>O algoritmo <strong>Bubble Sort</strong>,  é considerado o método de ordenação mais ineficiente, já que ele precisa realizar a troca de itens sem saber qual será sua posição final. Essas trocas “desnecessárias” são muito custosas. Contudo, justamente por realizar passagens pela porção desordenada da lista, o bubble sort consegue fazer o que a maioria dos outros algoritmos de ordenação não consegue. Em particular, se durante uma passagem não houver trocas, então sabemos que a lista está ordenada. O bubble sort pode ser modificado para terminar antes se descobrir que a lista ficou ordenada. Isso significa que para listas que requerem apenas algumas passagens, o bubble sort pode ter a vantagem de reconhecer a lista ordenada e parar.</li>
</ul>
<ul>
<li><strong>Selection Sort</strong> Pontos positivos – Custo linear no tamanho da entrada para o número de movimentos de elementos.</li>
</ul>
<ul>
<li>Pontos negativos – Não adaptável. – Não estável.</li>
<li>A vantagem de seu uso ocorre quando se trabalha com componentes em que, quanto mais se escreve, ou reescreve, mais se desgasta, e, consequentemente, perdem sua eficiência, como é o caso das memórias EEPROM e FL</li>
<li>Ele é um pouco mais eficiente que o Insertion sort em relação ao tempo e a quantidade de movimentações na lista de ordem 2.<br>
Ele torna-se útil em estruturas lineares similares ao do Insertion Sort, porém, com o número de elementos consideravelmente maior, já que, o número de trocas é muito inferior ao número de comparações, consumindo, assim, mais tempo de leitura e menos de escrita. A vantagem de seu uso ocorre quando se trabalha com componentes em que, quanto mais se escreve, ou reescreve, mais se desgasta, e, consequentemente, perdem sua eficiência, como é o caso das memórias EEPROM e FL</li>
</ul>
<ul>
<li>
<p><strong>Insertion Sort</strong> Comparado a outros métodos de ordenação considerados básicos, como o Blubble Sort e o Selection Sort, o método de inserção é considerado o mais rápido entre eles. Já em comparação a outros métodos de divisão e conquista, como o Merge Sort e Quick Sort, ele se apresenta menos eficiente. Esse método de ordenação é bem simples e de fácil implementação, consome pouca memória no disco e é muito estável. Ele se sai melhor para ordenar poucos números, pois devido a sua forma de comparação de todos os índices, ele levaria muito tempo para ordenar muitos números.  Concluímos então, que o Insetion Sort é um método de ordenação muito útil, uma vez que é rápido, estável e versátil. Ele se comporta melhor quando usado para ordenar poucos números e tem pouco custo computacional.</p>
</li>
<li>
<p><strong>Quick Sort</strong> Apesar dele ser um pouco mais complicado, na maioria das implementações ele é mais eficiente do que o Mergesort e raramente alcança o pior caso de O(n2). O desempenho do quicksort depende do particionamento ser balanceado ou não balanceado. Um particionamento balanceado divide o conjunto a ser ordenado em duas Listas L1 e L2 de “mesmo tamanho”. Pior caso ocorre quando o particionamento é totalmente não balanceado. Melhor caso ocorre quando o particionamento é totalmente balanceado.</p>
</li>
</ul>
<h1 id="referência">Referência</h1>
<ul>
<li><a href="http://www.universidadejava.com.br/pesquisa_ordenacao/bubble-sort/">Bubble Sort</a></li>
<li><a href="https://www.programiz.com/dsa/quick-sort">Quick Sort</a></li>
<li><a href="https://www.programiz.com/dsa/insertion-sort">Insertion Sort</a></li>
<li><a href="https://www.programiz.com/dsa/selection-sort">Selection Sort</a></li>
<li><a href="https://homepages.dcc.ufmg.br/~cunha/teaching/20121/aeds2/sortingcmp.pdf">Métodos de Ordenação</a></li>
<li><a href="https://www.devmedia.com.br/algoritmos-de-ordenacao-analise-e-comparacao/28261">Comparativos</a></li>
</ul>

