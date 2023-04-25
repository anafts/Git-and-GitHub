<h1 align="center"> Guia básico para usar o Git e enviar arquivos para o GitHub: </h1>

<h3>Para aprender a usar o GIT de forma básica, primeiro você precisará seguir alguns passos iniciais:
</h3>

<ol>

<li> Instale o Git na sua máquina, para isso acesse o <a href="https://git-scm.com/"> site oficial </a>, baixe e instale de acordo com o seu sistema operacional. </li>

<li> Instale um terminal, para usar o GIT você precisará executar comandos específicos na linha de comando. Eu particularmente gosto de usar o <a href="https://hyper.is/">Hyper</a> , mas você pode usar o terminal padrão do seu sistema operacional. </li>

<li> Além disso, é necessário que tenha familiaridade com a linha de comando, sendo importante ter noção básica de como navegar pelo terminal e executar comandos. </li>

<li> Por último, é necessário ter uma conta no <a href="https://github.com/"> GitHub</a> como você está vendo esse tutorial pelo GitHub, suponho que você já tenha. </li>

</ol>

<hr>

<h3> Vamos lá? a forma mais fácil seria criando o repositório pelo próprio github </h3>

<p> Para isso, vá na parte de "repositories" e clique na opção “new” em azul </p>

![Captura de Pantalla 2023-04-25 a la(s) 08 22 57](https://user-images.githubusercontent.com/106173948/234270985-969740db-64f6-47f3-9744-ef442516c126.png)

<p> Em seguida você será direcionado para essa tela, adicione um nome para o repositório abaixo de “​​Repository name”, igual no exemplo, e não se preocupe em adicionar algo na parte de “Description”, você poderá fazer isso depois. </p>
<p> Não altere nada e clique na opção “Create repository” em azul no final da tela.</p>


![Captura de Pantalla 2023-04-25 a la(s) 08 54 09](https://user-images.githubusercontent.com/106173948/234271945-0f889ddf-0df4-4c3c-9b8c-62d626861ec8.png)


<p> Por último, você será direcionado para essa tela. Não feche pois vamos precisar dessas informações para enviar os arquivos para esse repositório. 
</p>

![Captura de Pantalla 2023-04-25 a la(s) 09 15 49](https://user-images.githubusercontent.com/106173948/234286549-5e0e8f58-b187-4bb8-afb5-26429279f758.png)

OBS: vamos precisar do comando "git remote add origin https://github.com/anafts/repo-ex.git"

 
<h3> Agora vamos configurar o Git na sua máquina por meio do terminal,
para isso você precisa cadastrar apenas duas informações: 
</h3>

```bash
# Digite o seu nome no GitHub
$ git config --global user.name "nome"

# Digite o seu email no Github

$ git config --global user.email "email"

# Verifique se as suas informações de usuário foram configuradas corretamente

$ git config --list

```

<h3> Agora com o GIT configurado, vamos aprender a enviar os arquivos para o Github. </h3>

<p> Para começar, navegue até a pasta dos arquivos em seu terminal usando o comando "cd" e o caminho para a pasta </p>

```bash
# Inicialize um novo repositório Git
$ git init

# Adicione todos os arquivos para o repositório
$ git add .

# Adicione o link do repositório remoto do GitHub, você pode encontar o seu naquela última tela do GitHub, apenas copie e cole
$ git remote add origin https://github.com/anafts/repo-ex.git

# Faça o commit inicial dos arquivos
$ git commit -m "first commit"

# Envie os arquivos para o repositório remoto no GitHub
$ git push -u origin main
```

<h3> Depois de executar esses comandos, seus arquivos serão enviados para o repositório remoto no GitHub. Quando você atualizar aquela última tela do GitHub, o repositório já terá todos os arquivos enviados </h3>

![Captura de Pantalla 2023-04-25 a la(s) 09 55 52](https://user-images.githubusercontent.com/106173948/234288795-610105fd-f1af-41e3-8e38-a24e909b5ab6.png)
