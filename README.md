# TRABALHO DE PI:  Título do Trabalho
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado


# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Halisson Julio Lopes:email_primeiro_componente@dominio.com<br>
Paulo Victor:paulovictoralves.contato@gmail.com<br>
Pedro Antônio:naosei@gmail.com<br>
Ricardo Leite Rodrigues:ricardoleiterodriguesbe@gmail.com<br>

### 2.MINIMUNDO<br>

> Você já teve dificuldades em achar receitas com os ingredientes que possui em casa? Já desistiu de cozinhar por causa disto? Gostaria de uma ferramenta que ajudasse a encontrar receitas com os ingredientes disponíveis?
Nosso sistema proporciona uma forma de resolver estas questões, possuindo também uma interface agradável, que possibilita mostrar receitas de acordo com suas necessidades. 
O sistema conterá informações sobre os usuários, receitas, 
O usuário terá que registrar um nome, um email, uma senha e uma data de nascimento, além disso ele terá um código no sistema que o identifica, ele poderá enviar receitas, bem como pesquisar, avaliar, favoritar e comentar em outras receitas.
Para cadastrar uma receita o usuário deverá preencher um nome,  um tempo de preparo, seu rendimento e  sua dificuldade, ao criar a receita ela receberá um código que a identifica no sistema. A receita pode conter um ou mais ingredientes.
Os ingredientes são gerais para todas as receitas e terão um código no sistema e o nome deles e poderão ser registrados no sistema.
Assim como os ingredientes, as restrições alimentícias terão um código no sistema e um nome, mas não poderão ser registradas no sistema.
Cada receita pode conter um ou vários ingredientes, porém pode ter nenhuma ou várias restrições.

### 3.PMC<br>
a) inclusão do PMC desenvolvido pelo grupo <br>
![Exemplo de PMC](arquivos/PMC.jpg)

#### 3.1. EAP - Estrutura Analítica do Projeto
a) Incluír imagem da EAP ![ChefEmCasa](arquivos/EAP_Modelo.png)<br> 
b) Dicinário da EAP ![ChefEmCasa](arquivos/EAP_Dicio1.png)<br> ![ChefEmCasa](arquivos/EAP_Dicio2.png)<br> ![ChefEmCasa](arquivos/EAP_Dicio3.png)<br>

#### 3.2. Requisitos funcionais e não funcionais
![ChefEmCasa](arquivos/Requisitos_funcionais.png)<br> 
![ChefEmCasa](arquivos/Requisitos_n_funcionais.png) <br> ![ChefEmCasa](arquivos/Requisitos_n_funcionais2.png) <br>

#### 3.3 Validação da Ideia.
a) Link do formulário desenvolvido
b) Link para Relatório/Apresentação de resultados obtidos

### 4.Personas e Histórias de usuário<br>
a) inclusão dos Persons desenvolvidos pelo grupo<br>
1- <br>
Chef Profissional <br>
Nome: Ana Silva <br>
Idade: 35 anos <br>
Profissão: Chef de cozinha <br>
Descrição: Ana é uma chef profissional renomada, com anos de experiência em culinária gourmet. Ela está sempre buscando novas receitas e técnicas culinárias para aprimorar suas habilidades. Ana precisa de um site que acelere uma ampla variedade de receitas sofisticadas, ingredientes de alta qualidade e instruções específicas para aprendê-la a criar pratos inovadores.<br>

2-<br>
Estudante Universitária <br>
Nome: Marina Oliveira <br>
Idade: 20 anos <br>
Profissão: Estudante universitária <br>
Descrição: Marina é uma estudante universitária ocupada, que está constantemente equilibrando seus estudos com outras responsabilidades. Ela precisa de receitas rápidas e acessíveis, que podem ser preparadas com ingredientes simples e disponíveis em um orçamento limitado. Marina está em busca de um site de receitas que gosta de opções saudáveis ​​e práticas para o seu estilo de vida agitado.<br>
<br>
b) inclusão das Histórias de usuário desenvolvidas pelo grupo<br>
1-<br>
História de usuário: Como uma chef profissional, Ana precisa acessar um site de receitas que seja confiável e inspirada para seus pratos gourmet. Ela deseja encontrar receitas exclusivas, com ingredientes de alta qualidade e técnicas avançadas. Ana também procura por um site que possua uma comunidade ativa, onde ela possa compartilhar suas criações e trocar ideias com outros chefs.<br>
<br>
2-<br>
História de usuário: Marina tem uma vida movimentada devido aos seus estudos e atividades extracurriculares. Ela precisa de um site de receitas que dê opções rápidas e fáceis de preparar, para que possa se alimentar de forma saudável mesmo com pouco tempo disponível. Marina também gostaria de encontrar dicas de refeições para emagrecer e sugestões para aproveitar ao máximo os ingredientes básicos que ela tem em casa.<br>

<br>


### 5. PROTÓTIPOS DO SISTEMA<br>
Neste ponto a codificação não e necessária, somente as ideias de telas devem ser desenvolvidas. O princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas e/ou descartadas <br>

Sugestão: https://balsamiq.com/products/mockups/<br>

![Alt text](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/balsamiq.png?raw=true "Title")
![Arquivo PDF do Protótipo Balsamiq feito para Empresa Devcom](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/EmpresaDevcom.pdf?raw=true "Empresa Devcom")

#### 5.1 PROTÓTIPO DO SISTEMA MOBILE <br>
https://app.quant-ux.com/#/test.html?h=a2aa10aJ9AiqXUmfxAqY1GRvdOALyFry8XEWzhL4Phs213oDw0fw1E5Q4Ree&ln=en<br>
#### 5.2 PROTÓTIPO DO SISTEMA WEB<br>

#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?
    
> A Empresa Chef em Casa precisa inicialmente dos seguintes relatórios:
* Relatório de quais são as receitas mais bem avaliadas pelos usuários.
* Receitas com filtros escolhidos pelos usuários (pelas restrições ou pelas categorias).
* Relatório sobre o perfil do usuário (quantidade de usuários que ele segue ou tem de seguidores).
* Relátório sobre as receitas que o usuário enviou (quantas pessoas curtiram, quantas comentaram, quantas favoritaram).
* Relatório de quem são os usuários normais mais seguidos (caso um usuário tenha reeitas bem avaliadas ele vira um chef).

 ### 6.MODELO CONCEITUAL<br>
  
![ChefEmCasa](arquivos/Modelo_Conceitual.png)
      
    
#### 7 Descrição dos dados <br> 
PERFIL: Tabela que armazena as informações relativas ao peril<br>
cod_perfil: campo que armazena o número de registro do perfil no banco.<br>
nome: campo que armazena o nome do perfil.<br>
email: campo que armazena o email do perfil.<br>
senha: campo que armazena a senha do perfil.<br>
dta_nasc: campo que armazena a data de nascimento do perfil.<br>
tipo: campo que armazena o tipo do perfil.<br>

RECEITA: Tabela que armazenas as informações das receitas<br>
	cod_rec: campo que armazena o número de registro da receita no banco.<br>
	nome: campo que armazena o nome da receita.<br>
	temp_preparo: campo que armazena o tempo de preparo (em minutos) da receita.<br>
	porcao: campo que armazena a quantidade de pessoas que dá para alimentar.<br>
	dta_lanc: campo que armazena a data de lançamento da receita.<br>
	status: campo que fala se a receita foi aceita ou não.<br>

RESTRICAO: Tabela que armazenas as informações das restricoes<br>
	cod_rest: campo que armazena o número de registro da restição no banco.<br>
	restricao: informa qual a restrição<br>

CATEGORIA: Tabela que armazenas as informações das categorias<br>
	cod_cat: campo que armazena o número de registro da categoria no banco.<br>
	restricao: informa qual a categoria<br>

INGREDIENTE: Tabela que armazena as informações relativas aos ingredientes<br>
	cod_ingrediente: campo que armazena o número de registro do ingrediente no banco.<br>
	nome: informa qual é o ingrediente<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
![ChefEmCasa](arquivos/Modelo_Logico.png)

### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados 
 <br> + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL

#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>

    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
