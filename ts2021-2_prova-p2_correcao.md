<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: **201804642**

Nome: **Carlos Henrique Silva Bispo Rodrigues**

<p><font color="red">Nota 5,95</font></p>


1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware.

      <p>
      Processo de Testes de Software representa uma estruturação de etapas, atividades, artefatos, papéis e responsabilidades que buscam a padronização dos trabalhos e ampliar a organização e controle dos projetos de testes.

      Projeto de Teste de Software refina a abordagem apresentada no Plano de Teste e identifica as funcionalidades e características a serem testadas pelo projeto e por seus testes associados. Este documento também identifica os casos e os procedimentos de teste, se existirem, e apresenta os critérios de aprovação.

      O Plano de Teste de Software é um documento que descreve o escopo, os recursos e o cronograma das atividades de teste. Identifica itens e funcionalidades a serem testados, as tarefas a serem realizadas e os riscos associados com a atividade de teste.
      </p>

      <p><font color="red">Nota 0,5</font></p>

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.
      <p>
      Processo de Teste de Software é um método de teste, que terceiros possam instanciar o processo de teste de acordo com suas necessidades. O Plano de Teste de Software é uma fase do Processo de Teste, que apresenta o planejamento para execução do teste, que por sua vez, é utilizado no Projeto de Teste de Software.
      </p>

      <p><font color="red">Nota 0,2</font></p>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.
      <p>
      A aplicação de teste ágil proporciona diversas melhorias, não só a nível de qualidade do processo, como também na qualidade do produto. Entregas em partes e pode ser realizada por todos os membros do time, Foco em várias tarefas simultaneamente, Planejamento iterativo e incremental, Ocorre durante o desenvolvimento em ciclos frequentes e contínuos.
      </p>
      <p><font color="red">Nota 1,0</font></p>

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório.
      <p>
      • Resultados de teste, casos de teste e documentação de teste são geradas a medida que os testes são realizados.
      </p>
      <p>
      • Heurísticas, são diretrizes ou regras que o ajudam a decidir o que fazer. Este procedimento emprega um número de heurísticas que ajudam a decidir o que deve ser testado e como testá-lo.
      </p>
      <p>
      • Os testadores iniciantes ou menos experientes observam apenas o que a funcionalidade lhes diz, enquanto um testador exploratório deve procurar qualquer comportamento incomum ou misterioso no sistema.
      </p>
      <p>
      • Nos testes exploratórios de estilo livre, o aplicativo é testado de maneira ad-hoc e não há muitas diretrizes ou procedimentos para o teste.
      </p>

      <p><font color="red">Nota 1,0</font></p>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   1. (2.0 Pontos) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

|Caso de Teste|Cenário|Informações|
|---|---|---|
|01|Criar Banco|Informar número e nome do Banco|
|02|Criar Agencias|Informar número e nome da Agencia, cidade e o Banco referenciado|
|03|Criar Conta|Informar dados para criar conta e agência referenciada|

<p><font color="red">Nota 0,5</font></p>

   2. (2.0) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

**BANCO**
|CT|Valores de Entrada|Resultado esperado|
|---|---|---|
|01|10 Numero, "Bradesco" nome|Valor Inválido|
|02|-100 Numero, "Bradesco" nome|Valor Inválido|
|03|1010 Numero, "Bradesco" nome|Valor Inválido|
|04|103 Numero, "Bradesco33" nome|Valor Inválido|
|05|103 Numero, "BB" nome|Valor Inválido|
|06|103 Numero, "Bradesco103" nome|Valor Inválido|
|07|103 Numero, "BBBBraaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaadddddessssssssssssssssssssssssssssscccccccccooooooooooooo" nome|Valor Inválido|
|08|103 Numero, "Bradesco" nome|Valor Válido|

**AGENCIA**
|CT|Valores de Entrada|Resultado esperado|
|---|---|---|
|09|10 Numero, "Central" nome, "Anicuns" cidade|Valor Inválido|
|10|101010 Numero, "Central" nome, "Anicuns" cidade|Valor Inválido|
|11|1051 Numero, "Central" nome, "Anicuns" cidade|Valor Válido|
|12|1051 Numero, "Central23" nome, "Anicuns" cidade|Valor Inválido|
|13|1051 Numero, "Cent" nome, "Anicuns" cidade|Valor Inválido|
|14|1051 Numero, "Ceeeeeeeeeeeeeeeeeeeeeeeeeeeeeennnnnnnnnnnnnnnnnnnnnnnnntttttttttttttttttttttrrrrrrrrrrrrrrrrralllllll" nome, "Anicuns" cidade|Valor Inválido|
|15|1051 Numero, "Central" nome, "Anicuns1" cidade|Valor Inválido|
|16|1051 Numero, "Central" nome, "Anu" cidade|Valor Inválido|
|17|1051 Numero, "Central" nome, ""Annnnnnnnnnnnnnnnnnnnnnnnnnnnniiiiiiiiiiiiiiiiiiiiiiiiccccccccccccccccunnnnnnnnnnnnnnnnnnnsssssssssssssssss" cidade|Valor Inválido|

**CONTA**
|CT|Valores de Entrada|Resultado esperado|
|---|---|---|
|18|1245798 Numero, "Corrente" tipo|Valor Inválido|
|19|124578 Numero, "Corrente" tipo|Valor Válido|

<p><font color="red">Nota 1,5</font></p>

   3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.

<p><font color="red">Nota 1,25</font></p>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
