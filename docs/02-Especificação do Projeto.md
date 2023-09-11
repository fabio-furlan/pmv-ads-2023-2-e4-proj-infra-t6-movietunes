# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.


## Personas

 ![docs/img/Captura de tela 2023-09-10 211617.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20211617.png)

 ![docs/img/Captura de tela 2023-09-10 211623.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20211623.png)

 ![docs/img/Captura de tela 2023-09-10 211628.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20211628.png)

![docs/Captura de tela 2023-09-10 211634.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/Captura%20de%20tela%202023-09-10%20211634.png)


## Histórias de Usuários

![docs/img/Captura de tela 2023-09-10 211644.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20211644.png)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Inicialmente, o aplicativo terá uma tela principal com dois botões : Um para cadastro e outro para entrar no aplicativo . Após o login , o usuário visualiza os filmes listados por gênero e também os filmes mais vistos dos últimos tempos. Ao clicar no filme , é possível visualizar o poster e o trailer . Além disso, estará descrito informações do filme. Abaixo das informações , estará os campos de escreva seu comentário, onde será possível também apagar o que foi comentado. Também haverá um campo com a descrição da trilha sonora deste filme. 

### Descrição Geral da Proposta

Por se  tratar de um projeto acadêmico, poderá haver mudanças na configuração do Sistema, a fim de melhorar a usabilidade e entendimento  do aplicativo para o usuário. A forma da disposição e conecção entre as informações também dependerá da experiência e limitações do grupo . 

### Processo 1 – Início do cadastro


![docs/img/Captura de tela 2023-09-10 092121.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20092121.png)

### Processo 2 – Realizar um comentário no filme


![docs/img/Captura de tela 2023-09-10 092328.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20092328.png)

### Processo 3 – Tela Incial para ver Informações sobre o filme e ver os filmes por gênero e classificação 


![docs/img/Captura de tela 2023-09-10 092518.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20092518.png)

### Processo 4 – Avaliar por estrelas


![docs/img/Captura de tela 2023-09-10 092720.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20092720.png)

### Processo 5 – Ver pôster do filme 


![docs/img/Captura de tela 2023-09-10 092720.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20092720.png)

### Processo 6 – Visualizar trilha sonora do filme 


![docs/img/Captura de tela 2023-09-10 093120.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-10%20093120.png)

## Indicadores de Desempenho



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O software deve apresentar uma tela de cadastro| MÉDIA | 
|RF-002|O software deve notificar o usuário quando sua mensagem foi curtida ou respondida.    | ALTA|
|RF-003| O software deve permitir que o usuário crie mensagem utilizando o nome de usuário (nick-name)   | BAIXA|
|RF-004|  O software deve permitir que o usuário exclua suas mensagens de texto.   | ALTA|
|RF-005|O software deve permitir mais informações do filme   | ALTA|
|RF-006|O software deve sugerir no mínimo 2 filmes de cada gênero (romance, terror, ficção científica, etc )    | ALTA|
|RF-007|O software deve destacar os filmes mais vistos dos últimos tempos   | BAIXA|
|RF-008|O software deve permitir que o usuário avalie o filme por estrelas   | MÉDIA|
|RF-009|O software deve permitir a visualização do trailer e do poster  | ALTA|
|RF-010|O software deve permitir que o usuário veja o nome da trilha sonora dos filmes  |ALTA|

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s |  BAIXA |
|RNF-003| O sistema deverá atender às normas legais, tais como padrões, leis, etc. |  BAIXA | 
|RNF-004| O sistema deverá se comunicar com o NoSQL. |  Alta | 
|RNF-005| O sistema deverá rodar nas plataformas web e mobile. |  BAIXA | 
|RNF-006| O sistema não apresentará aos outros usuários quaisquer dados de cunho privativo. |  Alta | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                             |
|--|-----------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre                 |
|02| O sistema deverá ser desenvolvido na linguagem proposta pelo Projeto no Canvas ou pelo Professor Orientador|
|03| A equipe não pode utilizar profissionais fora do grupo                |
|04| O custo do projeto não poderá ultrapassar até 20% a mais do orçamento |


## Diagrama de Casos de Uso

![docs/img/WhatsApp Image 2023-09-09 at 12.36.49.jpeg](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/WhatsApp%20Image%202023-09-09%20at%2012.36.49.jpeg)

# Matriz de Rastreabilidade




# Gerenciamento de Projeto

## Gerenciamento de Tempo

Os nomes das pessoas das respectivas funções abaixo são de maneira fictícia. Por se tratar de um projeto acadêmico , ele é realizado por todos os alunos. Os nomes das tarefass são de acordo com as orientações de  Projeto descritas no Canvas e foram utilizadas de maneira fictícia para organizar o projeto.

![docs/img/Captura de tela 2023-09-09 193607.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-09%20193607.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. O gráfico abaixo foi realizado seguindo a ordem cornológica do projeto. As tarefas são dispostas de acordo com o projeto acadêmico , como descrito anteriormente. 

![docs/img/Captura de tela 2023-09-05 203831.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-05%20203831.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Feito de acordo com as mesmas informações descritas acima. 

![docs/img/Captura de tela 2023-09-05 210116.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-05%20210116.png)

## Gestão de Orçamento
O orçamento foi feito baseado em pesquisas na internet sobre os custos de Hardware e Software. Este orçamento é de maneira fictícia.

![docs/img/Captura de tela 2023-09-05 204301.png](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2023-2-e4-proj-infra-t6-movietunes/blob/main/docs/img/Captura%20de%20tela%202023-09-05%20204301.png)
