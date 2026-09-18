
 # <p align="center">__Anotações do Curso na Dio Sobre Github__ 




### ⭐ __Branches__
- É uma linha de desenvolvimento separada no controle de versão. Permitindo que a gente trabalhe em modificações no código sem afetar diretamente o código principal (geralmente chamado de main ou master) Depois de concluir as alterações em uma branch, você pode mesclar essas alterações de volta ao branch principal.


### ⭐ __Pull Resquest (PR)__
- É um pedido de mesclagem, recurso comum em plataformas de hospedagem de código-fonte colaborativo, como o GitHub. Ele propoe alterações em um repositório e solicita que essas alterações sejam revisadas e mescladas (merged) no código principal.


### ⭐ __Merge__
- É uma operação no controle de versão que combina as alterações de duas branches diferentes. Quando concluímos o desenvolvimento em uma branch e desejamos incorporar essas alterações de volta a brach principal, realizamos uma merge.

### ⭐ __Fork__
- É uma cópia de um repositório (um projeto de software) de outra pessoa para o seu próprio espaço no GitHub. Permitindo que faça alterações no código sem afetar o projeto final. Se você quiser contribuir de colta, pode enviar um "pull request" para que o dono do projeto original considere suas mudanças e as incorpore.

### ⭐ __Markdown__

<br>

📌 __Estrutura de Títulos:__ 

       # Teste 1
       ## Teste 2
       ### Teste 3
       #### Teste 4
       ##### Teste 5
       ###### Teste 6


📌 __Itálico:__

       *Teste* ou _Teste_


📌  __Negrito:__

       **Teste** ou __Teste__


📌 __Negrito e Itálico:__

       ___Teste___


📌 __Lista não ordenada:__

       - Teste 1
       - Teste 2
         - Sublista Teste 3 (Dois espaços e um -)

 
📌 __Lista ordenada:__
  
       1. Teste 1
       2. Teste 2
         1. Sublista teste


 📌 __Link:__

         [Texto da imagem](https://static.escolakids.uol.com.br/2024/07/as-oito-fases-da-lua-ilustradas-em-ceu-escuro-sobre-arvores.jpg)
  
  <br>

       ![Texto da imagem](https://static.escolakids.uol.com.br/2024/07/as-oito-fases-da-lua-ilustradas-em-ceu-escuro-sobre-arvores.jpg)


📌 __Crases:__

       `system.out.println();`

<br>

       ```system.out.println();system.out.println();system.out.println();system.out.println();system.out.println();```

📌 __Citações:__

       > Texto exemplo


📌 __Tabelas__

(Ao colocar traços se transforma em uma linha)

       | Cbeçalho 1 | Cabeçalho 2 |
       |------------| ------------|
       | Teste 1    | Teste 2     |
       | Teste 3    | Teste 4     |



📌 __Diminuir a imagem no git__

           //<img src="Link da imagem escolhida"
           width="100px">




# <p align="center">__Comando básicos no GitHub__

- Ver o que tem dentro da pasta.

        ls

- Iniciar o repositório dentro do Open Git Bash Here.

        git init

- Sair da Branch (master) e entrar na Branch (main).

        git branch -M main 

- Registrar o nome do repositório

        git commit -m "meu-projeto"


- Adicionar de forma remota o repositório.

        git remote add origin

- Empurrar tudo que temos no nosso repositório local vamos colocar no repositório remoto.

        git push -u origin main

- Para puxar um repositório do GitHub para a máquina local.

        git clone 

- Continuar dentro deste repositório.

        cd meu-projeto

- O terminal encerrra

        ctrl + C

- Verificar o que tem dentro das pastas ou terminal

        git status

- Adicionar a alteração realizada no repositório.

        git add

- Ele informa todas as alterações realizadas anteriormente.

        git push origin main

- Cria uma nova branch chamada minha-feature no repositório local.

        git branch <nome-da-branch>

- Entrar na Branch

        git checkout 

- Mescla uma branch ou versão especificada com a branch atual em que você 

        git merge <nome-da-versao>

- São usadas para marcar versões específicas dentro do código
 
    -  tags

      git tag -a v1.0 -m "Versão 1.0 estável"

- Definir a versão 

        -a <== anotação
       git tag -a v1.1 -m "Versao 1.1" 

- Puxar a tag para o repositório remoto

      git push origin v1.1 



# <p align="center">__Releases__

Um Release é uma versão do software publicada no repositório, geralmente associada a uma tag do Git.
Facilitar que usuários e desenvolvedores baixem uma versão estável do projeto sem precisar compilar ou navegar pelo histórico do código.

 Conteúdo típico:

 Código fonte empacotado em ZIP ou tarball.
Notas de versão (changelog) explicando mudanças, correções e novidades.
Binários ou executáveis prontos para uso.
Links para documentação ou recursos adicionais.

# <p align="center">__Gists__

São “mini-repositórios” que permitem salvar e compartilhar pedaços de código ou texto.
Facilitar a troca de exemplos, snippets e anotações sem precisar criar um repositório completo.
Podem ser públicos (qualquer pessoa pode ver) ou secretos (apenas quem tiver o link pode acessar).

# <p align="center">__Issues__

São registros de problemas, sugestões ou tarefas relacionadas ao projeto.
 Facilitar a comunicação e o acompanhamento de atividades entre desenvolvedores e usuários.
 Cada issue é uma página com título, descrição, comentários e etiquetas.

# <p align="center">__Wikis__

Uma wiki é uma coleção de páginas editáveis que servem para documentar o projeto.
Centralizar instruções, guias, tutoriais e informações técnicas para facilitar o uso e a contribuição.
Cada página é escrita em Markdown, o que permite incluir texto formatado, links, imagens e exemplos de código.

<br>

# <p align="center">__Autenticando pelo Terminal__



### Configuração de forma global o meu usuário

    git config --global user.name "Araujo77"

### Configurar o meu e-mail cadastrado no github

    git config --global user.email "nanda.araujo7@hotmail.com"

### Retornara uma lista conas configurações corretas

    git config --list

### Vai abrir a tela para logar no Github

    git push origin main



<br>

# <p align="center">🎯 __Desafios de Código - Formação GitHub Certification__

 **1- Clonando Repositórios**
 
- Recebe a URL do repositório como entrada
      
        repository_url = input()

- Escreve o comando Git para clonar o repositório

       git_command = "git clone"

- Imprime o comando Git seguido da URL do repositório recebida como entrada

      print(git_command, repository_url)

<br>

**2- Adicionando um Arquivo**
- Recebe os nomes dos arquivos ou o padrão para adição como entrada

      files_to_add = input()

- Escreve o comando Git para adicionar os arquivos especificados

      git_command = "git add"

- Imprime o comando Git seguido dos nomes dos arquivos ou do padrão recebido como entrada

      print(git_command, files_to_add)

<br>

**3- Criando uma Branch**
- Recebe o nome da nova branch como entrada

      new_branch_name = input()

- Escreve o comando Git para criar a nova branch

      git_command = "git branch"

- Imprime o comando Git seguido do nome da nova branch recebido como entrada

      print(git_command, new_branch_name)

<br>

**4- Alterando uma Branch**
- Recebe o nome da branch como entrada

      branch_name = input()

- Escreve o comando Git para mudar para a branch especificada

      git_command = "git checkout"

- Imprime o comando Git seguido do nome da branch recebido como entrada
             
      print(git_command, branch_name)
<br>

**5- Mesclando uma Branch** 
- Recebe o nome da branch a ser mesclada como entrada

      branch_to_merge = input()
- Escreve o comando Git para mesclar a branch especificada com a branch atual

      git_command = "git merge"
- Imprime o comando Git seguido do nome da branch a ser mesclada recebido como entrada

      print(git_command, branch_to_merge)       









