# :hammer: Comandos git
- `git log`: Mostra todos os log de todos os commits
  - `-p`: para visualizar as alterações em cada arquivo modificado;
  - `--oneline`: para visualizar cada commit de forma resumida em uma única linha;
  - `--graph`: para visualizar a linha do tempo dos commits com suas ramificações;
  - `--pretty` ou `--format`: para especificar com detalhes o que será exibido

- `git show`: para visualizar o trabalho realizado em algum commit específico
- `git diff`: exibe a diferença entre 2 pontos da linha do tempo de nosso repositório
-  `git branch`: para visualizar as branch existentes;
-  `git switch -c[nome_branch]`: cria uma nova branch
-  `git switch main`: volta para branch main
-  `git rebase main`: aplica os novos commit da main ao inicio da branch criada
-  `git merge`: mescla a branch main com nova criada(_fast forward_)
