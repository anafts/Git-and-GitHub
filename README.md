<h1 align="center"> Guia básico para usar o Git e enviar arquivos para o GitHub: </h1>

<h3>Para aprender a usar o GIT de forma básica, primeiro você precisará seguir alguns passos iniciais:
</h3>

<ol>

<li> Instale o Git na sua máquina, para isso acesse o [site oficial] (https://git-scm.com/), baixe e instale de acordo com o seu sistema operacional. </li>

<li> Instale um terminal, para usar o GIT você precisará executar comandos específicos na linha de comando. Eu particularmente gosto de usar o [Hyper] (https://hyper.is/), mas você pode usar o terminal padrão do seu sistema operacional. </li>

<li> Além disso, é necessário que tenha familiaridade com a linha de comando, sendo importante ter noção básica de como navegar pelo terminal e executar comandos. </li>

<li> Por último, é necessário ter uma conta no [GitHub](https://github.com/) como você está vendo esse tutorial pelo GitHub, suponho que você já tenha.  </li>
</ol>

<h3> Vamos lá? a forma mais fácil seria criando o repositório pelo próprio github </h3>

<p> Para isso, vá na parte de "repositories" e clique na opção “new” em azul </p>

![Captura de Pantalla 2023-04-25 a la(s) 08 22 57](https://user-images.githubusercontent.com/106173948/234270985-969740db-64f6-47f3-9744-ef442516c126.png)

<p> Em seguida você será direcionado para essa tela, adicione um nome para o repositório abaixo de “​​Repository name” e não se preocupe em adicionar algo na parte de “Description”, você poderá fazer isso depois. </p>
<p> Não altere nada e clique na opção “Create repository” em azul no final da tela.</p>


![Captura de Pantalla 2023-04-25 a la(s) 08 54 09](https://user-images.githubusercontent.com/106173948/234271945-0f889ddf-0df4-4c3c-9b8c-62d626861ec8.png)




 


```bash
# Clone este repositório
$ git init

# Acesse a pasta do projeto no terminal/cmd
$ git commit -m "first commit"

# Instale as dependências
$ git remote add origin https://github.com/anafts/repo-ex.git

# Execute a aplicação em modo de desenvolvimento
$ npm start

# O servidor inciará na porta:80 - acesse http://localhost:80 

```