# ⭐ Branches
É uma linha de desenvolvimento separada no controle de versão. Permitindo que a gente trabalhe em modificações no código sem afetar diretamente o código principal (geralmente chamado de main ou master) Depois de concluir as alterações em uma branch, você pode mesclar essas alterações de volta ao branch principal.


# ⭐ Pull Resquest (PR)
É um pedido de mesclagem, recurso comum em plataformas de hospedagem de código-fonte colaborativo, como o GitHub. Ele propoe alterações em um repositório e solicita que essas alterações sejam revisadas e mescladas (merged) no código principal.


# ⭐ Merge
É uma operação no controle de versão que combina as alterações de duas branches diferentes. Quando concluímos o desenvolvimento em uma branch e desejamos incorporar essas alterações de volta a brach principal, realizamos uma merge.

# ⭐ Fork
É uma cópia de um repositório (um projeto de software) de outra pessoa para o seu próprio espaço no GitHub. Permitindo que faça alterações no código sem afetar o projeto final. Se você quiser contribuir de colta, pode enviar um "pull request" para que o dono do projeto original considere suas mudanças e as incorpore.

# Comando básicos no GitHub


## ls
Ver o que tem dentro da pasta.

## git init
Para iniciar o repositório dentro do Open Git Bash Here.
    
## git branch -M main 
Sair da Branch (master) e entrar na Branch (main).

## git commit -m "" + o nome do repositório


## git remote add origin
Adicionar de forma remota o repositório.

## git push -u origin main
Empurrar tudo que temos no nosso repositório local vamos colocar no repositório remoto.

## git clone 
Para puxar um repositório do GitHub para a máquina local.

## cd + o nome do repositório no GitHub
Continuar dentro deste repositório.

## ctrl + C
O terminal encerrra

## git status
Verificar o que tem dentro das pastas ou terminal

## git add
Adicionar a alteração realizada no repositório.

## git push origin main
Ele informa todas as alterações realizadas anteriormente.

## git brach + nome 
Criar Brach

## git checkout 
Entrar na Branch

## git merge + o nome da versão

# TAG's

Marcar versões específicas dentro do código

## -a <== anotação
## git tag -a v1.1 -m "Versao 1.1" 
Definir a versão 

## git push origin v1.1 
Puxar a tag para o repositório remoto

# Releases

Um Release é uma versão do software publicada no repositório, geralmente associada a uma tag do Git.
Facilitar que usuários e desenvolvedores baixem uma versão estável do projeto sem precisar compilar ou navegar pelo histórico do código.

Conteúdo típico:

Código fonte empacotado em ZIP ou tarball.
Notas de versão (changelog) explicando mudanças, correções e novidades.
Binários ou executáveis prontos para uso.
Links para documentação ou recursos adicionais.

# Gists 

São “mini-repositórios” que permitem salvar e compartilhar pedaços de código ou texto.
Facilitar a troca de exemplos, snippets e anotações sem precisar criar um repositório completo.
Podem ser públicos (qualquer pessoa pode ver) ou secretos (apenas quem tiver o link pode acessar).

# Issues

São registros de problemas, sugestões ou tarefas relacionadas ao projeto.
Facilitar a comunicação e o acompanhamento de atividades entre desenvolvedores e usuários.
Cada issue é uma página com título, descrição, comentários e etiquetas.

# Wikis

Uma wiki é uma coleção de páginas editáveis que servem para documentar o projeto.
Centralizar instruções, guias, tutoriais e informações técnicas para facilitar o uso e a contribuição.
Cada página é escrita em Markdown, o que permite incluir texto formatado, links, imagens e exemplos de código.



