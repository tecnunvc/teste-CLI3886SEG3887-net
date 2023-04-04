# Teste Desenvolvedor .NET
<picture>
  <img alt="Tecnun Soluções" src="https://user-images.githubusercontent.com/129311001/228670655-39f2504b-5c03-4305-932c-06eb7f6be457.jpeg" height="20%" width="20%">
</picture>
</p></p>

## O Desafio
O desafio a seguir foi criado para entender melhor a sua forma de desenvolver. São 17 exercícios de diversos níveis e você deverá nos encaminhar os scripts e a solution (Sem a pasta bin) do projeto conforme sessão abaixo require "Entregas".
Pedimos que você nos envie o resultado em até 2 dias úteis (média 48h) após o recebimento do e-mail. 

O prazo faz parte do desafio e é importante você se concentrar em desenvolver o máximo possível dos itens, ainda que não conclua todos.

### Requisitos
Esses requisitos são obrigatórios e devem ser desenvolvidos para a entrega do teste

### Premissa para todos os exercícios:
Todos os métodos e funções devem possuir tratamento para erros, à escolha do desenvolvedor.

### O que é permitido
+ Linguagem C#, WCF etc
+ Bootstrap, React, Angular
+ .NET Framework ou .NET Core ou .NET 5
+ PostgreSQL, MySQL, Oracle, etc
+ Mapeamento objeto-relacional (ORM)
+ Qualquer tecnologia complementar as citadas anteriormente são permitidas desde que seu uso seja justificável

### O que não é permitido
+ Bancos de Dados não relacionais.
+ Utilizar bibliotecas ou códigos de terceiros que implementem algum dos requisitos.

### Recomendações
+ Linter: Desenvolva o projeto utilizando algum padrão de formatação de código.

### Extras
Aqui são listados algumas sugestões para você que quer ir além do desafio inicial. Lembrando que você não precisa se limitar a essas sugestões, se tiver pensado em outra funcionalidade que considera relevante ao escopo dos execicios fique à vontade para implementá-la.
+ Documentação: Gerar a documentação da API de forma automatizada, utilizando o `swagger ou equivalentes
+ Containerização: Realizar a conteinerização da aplicação utilizando Docker
+ Front-end da aplicação: Se seu foco é ser fullstack, você pode explorar isso desenvolvendo um front-end para a aplicação, seja em tecnologia .NET (MVC, Razor, Blazor) ou javacript (VueJS, Angular, ReactJS, etc.)

### Entregas
Para realizar a entrega do teste você deve:
+ Relizar o fork e clonar esse repositório para sua máquina
+ Criar uma branch com o nome de `teste/[SEU NOME]`
  - `[SEU NOME]`: Seu nome
  - Exemplo: `teste/fulano-da-silva`
+ Faça um commit da sua branch com a implementação do teste
+ Realize o pull request da sua branch nesse repositório

### Diferencial (não obrigatório)
Além do pull request você pode gravar um vídeo de no máximo 30 minutos mostrando o que foi desenvolvido, falando sobre as decisões que foram tomadas, as tecnologias utilizadas, arquitetura e tudo que você achar relevante. A facecam é opcional, mas é um extra desejável. Esse vídeo deve ser postado no youtube (pode ser não listado) e seu link deve estar no README.md do projeto.

## Execícios
entregas

#### 1) Faça um algoritmo que calcule e exiba o salário reajustado de dez funcionários de acordo com a seguinte regra: 
	- Salário até 300, reajuste de 50%; 
	- Salários maiores que 300, reajuste de 30%.

#### 2) Utilizando estruturas de repetição e array (vetor), dada uma sequência de n números, imprimi-la na ordem inversa à da leitura.

#### 3) Utilizando listas e LINQ ou lambdas, dada uma lista com n alunos, imprimi-la de forma ordenada pela matricula. A classe aluno deverá conter as seguintes propriedades:
	•	Nome
	•	Idade
	•	Matricula

#### 4) Crie um método de extensão que converta um valor de data (Datetime) para o formato Ano Mês (AAAAMM) com tipo de saída inteiro (Int).

#### 5) Crie um serviço WCF que receba a posição n de um número da sequência de Fibonacci e mostre o valor da sequência na posição subsequente. 
	Exemplo: Se informado a 5ª posição (valor 3), o método deverá retornar o valor contido na 6ª posição (valor 5)

#### 6) Crie um serviço WEB API que possibilite a criação, alteração e pesquisa de um aluno (Baseado na entidade descrita no exercício 3).

#### 7) Ler o arquivo [Contribution guidelines for this project](docs/CONTRIBUTING.md) e [extrato de vendas](anexos/extrato de vendas.csv) e apresentar os vendedores com maior valor de venda por região.

#### 8) Crie um teste unitário para o exercício 4.

#### 9) Crie um teste unitário para o exercício 5.

#### 10) Crie uma classe chamada Ingresso que possua um atributo valor e um método toString que retorne à informação do valor do ingresso.
	•	Crie uma classe IngressoVIP, que herda de Ingresso e possui um atributo valor
	•	Adicional. O método toString da classe IngressoVIP deve considerar que o valor do ingresso é o valor da superclasse somado ao valor Adicional do IngressoVIP.
	•	Crie uma classe para testar os objetos das classes Ingresso e IngressoVIP. 

#### 11) Utilizando LINQ ou Lambda, dados os valores de orçado e realizado de um vendedor, calcule os percentuais de atingimento de um vendedor.

#### 12) Crie uma tabela de alunos com as propriedades: Matricula (inteiro), Nome (Texto) e Idade (inteiro), Estado (texto).

#### 13) Insira, de uma só vez, os registros abaixo na tabela criada
	Nome	Idade	Estado
	Maria	18		Rio_de_Janeiro
	João	22		Sao_Paulo
	Lucas	25		Minas_Gerais
	Matheus	19		Minas_Gerais
	Carlos	23		Sao_paulo

#### 14) Crie uma procedure que permita alterar a idade de um aluno para 22 anos na tabela criada.

#### 15) Crie uma tabela que guarde as informações de campus contendo as seguintes propriedades: 
	Id (inteiro), Nome do campus (texto), Estado (texto)

##### 15.1) - Insira, de uma só vez, os registros abaixo na tabela criada
	1	São_Paulo_Centro	Sao_Paulo
	2	São_Paulo_Interior	Sao_Paulo
	3	Rio_de_Janeiro_Niteroi	Rio_de_Janeiro
	4	Minas_Gerais_Contagem	Minas_Gerais 

##### 15.2) – Crie uma consulta que cruze a tabela de alunos e a tabela de campus e identifique em quais campus cada aluno estuda.

##### 15.3) – Você acha possível melhorar a consulta do item 15.2? Se sim, como?

#### 16) – Remova todos os alunos com menos de 20 anos e que o nome possua mais de 5 caracteres.

#### 17) – Dado uma gravadora, crie um sistema em que seja possível:
##### 17.1	Cadastrar um novo artista ou banda (Nome, Quantidade de integrantes, Ritmo)
##### 17.2	Alterar informações de um artista cadastrado
##### 17.3	Remover artista do portfolio
##### 17.4	Consultar os artistas do portfolio
##### 17.5	Cadastrar álbuns (Nome, artista, Ritmo)
##### 17.6	Alterar informações de um álbum cadastrado
##### 17.7	Remover álbum do portfolio
##### 17.8	Consultar os álbuns do portfolio
