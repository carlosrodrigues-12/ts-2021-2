<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: **201804642**</br>
Nome: **Carlos Henrique Silva Bispo Rodrigues**</br>

<p><font color=red><b>O Nome do arquivo entregue não atendeu à especificação</b></font></p>

<p><font color=green>Nota: 8,5</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software?
      <p>O objetivo primário, é revelar a presença de defeitos/erros nos softwares testados. <font color=green>Certo</font></p>
   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário?
      <p>O software vai estar sujeito a defeitos, erros e falhas. Por um acaso, o usuário do software pode realizar uma ação não contemplada na implementação dos testes. <font color=red>Errado</font></p>
2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível.
      <p>O teste exaustivo é um teste que da garantia de qualidade em que todas as combinações possíveis de cenários de uso são considerados, bem como situações e entradas aleatórias.</p>
      <p>A execução do teste exaustivo não é possível, pois dependendo do cenário, o número de teste tem possiblidades elevadas em uma progressão geométrica, que demandaria muito tempo e custo dos testes. <font color=green>Certo</font></p>
3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural.

      <p>

      **Limitações da Técnica de Teste Funcional:**</br> Limitações das abordagens combinatórias</br>Partição em classes de equivalência e Análise de Valores-Limite: Não levam em conta combinações de valores difícil testar situações em que diferentes combinações levam a diferentes saídas do sistema;</br>Partição por categorias e Árvore de classificação: Visam as combinações de valores (com restrições). Partem de especificações informais, não levam em conta modelos de especificação; <font color=red>Errado.</font></br>

      **Limitações da Técnica de Teste Estrutural:**</br>Infelizmente, o teste exaustivo de todos os possíveis caminhos de fluxo de controle possui várias desvantagens: O número de caminhos pode ser infinito ou muito grande. Cada decisão dobra e cada loop multiplica o número de caminhos;</br>Caminhos presentes na especificação podem ser esquecidos na implementação;</br>Defeitos podem existir mesmo com o fluxo de controle correto;</br>Um módulo pode executar corretamente para diversos casos de testes e falhar para alguns. <font color=green>Certo. Nota: 0,5.</font></br>
      </p>
4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada.
      <p>

      **Teste de Integração:** O objetivo é garantir que duas ou mais unidades possa funcionar juntas. Testar grupos de unidades integradas para criar um sistema ou um subsistema. Os testes se concentram nas interfaces de comunicação entre unidades.
      <br>Tipos de Testes: **Integração top-down** -> Desenvolver o esqueleto do sistema e preenchê-lo com componentes.</br>**Integração bottom-up** -> Integrar componentes de infra-estrutura, e depois, adicionar componentes funcionais. <font color=green>Certo</font></p>
5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivlência.
      <p>Este critério propõe a divisão dos domínios de entrada e saída em partições, válidas e inválidas. Tais partições são classificadas como equivalentes, tais classes são equivalentes em relação à capacidade de revelar ou não a presença de defeitos. O objetivo principal é a redução da quantidade de casos de testes necessários. <font color=green>Certo</font></p>
6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados.
      <p>Sim, existe. São diferentes níveis de cobertura, contabilizando 8. Podem ser definidos em função dos elementos do GFC. Quanto maior o nível, maior o rigor do critério de teste, ou seja, mais caso de teste ele exige para ser satisfeito.</br>Nível 1: 100% de cobertura de comandos, também chamado de cobertura de nós (critério **todos-nós**).</br>Nível 2: 100% de cobertura de decisões. Também chamado de cobertura de arcos/arestas (critério **todos-arcos**).</br>Nível 7: 100% de cobertura de caminhos. Também conhecido como critério **todos-caminhos**. <font color=green>Certo</font></p>
7. Considere a especificação, a seguir, de um hipotético programa que objtiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A).
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida;
         • Escaleno = quando todos os seus lados têm medidas diferentes;
         • Equilátero = quando todos os lados tem a mesma medida;
         • Acutângulo = quando o quadrado de um dos seus lados é menor que a soma do quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).
         • Obtusângulo: quando o quadrado de um dos seus lados é maior que a soma do quadrado dois outros dois. A<sup>2</sup> > B<sup>2</sup> + C<sup>2</sup>.

7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.

<div align=center>
  <img src="tabela_decisao.jpg">
</div>


<font color=orange>Parcialmente correto. Nota 1,5.</font>

7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
|01 |30 |30 |40 |Triângulo-Isósceles|
|02 |20 |50 |35 |Triângulo-Escaleno|
|03 |50 |50 |50 |Triângulo-Equilátero|
|04 |40 |40 |25 |Triângulo-Isósceles|
|05 |0  |0  |0  |Não-Triângulo|


INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
