# Git e GitHub

Guia pratico para iniciantes.

### Instalação.

https://git-scm.com/download

# scenes

- [x] Você deseja criar pontos na história da produção do seu projeto.
- [x] Você deseja verificar mudanças feitas no seu projeto.
- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona novas funcionalidades ão seu projeto em produção.
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar ão seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time.
- [x] Você precisa resolver um conflito.
- [x] antes de enviarmos a solução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para linha do tempo.
- `git add .` // Adicionar todos os arquivos/diretórios.
- `git commit arquivo.txt` // Comitar um arquivo.
- `git commit --amend -m "Minha nova mensagem"` // Alterando mensagens de commit.
- `git log` // vizualiza os pontos na linha do tempo / commit.
- `git status` // informa o estado das alterações do nosso projeto.
- `git show` // apresenta determinado ponto na história.
- `git branch` // Listar branches.
- `git branch bug-123` // Criando um novo branch.
- `git branch -d bug-123` // Apagando um branch.
- `git branch -v` // Listar branches com informações dos últimos commits.
- `git branch --merged` // Listar branches que já foram fundidos (merged) com o master.
- `git push` // envia alterações locais para o repositório remoto.
- `git push -u origin master` // Enviar arquivos/diretórios para o repositório remoto
  O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.
- `git push origin:bug-123` // Apagar branch remoto.
- `git push origin vs-1.2` // Criando tags no repositório remoto.
- `git push origin --tags` // Criando todas as tags locais no repositório remoto.
- `git push origin bug-123` // Criando um branch remoto com o mesmo nome.
- `git push origin bug-123:new-branch` // Criando um branch remoto com nome diferente.
- `git checkout -b bug-123 origin/bug-123` // Baixar um branch remoto para edição.
- `git checkout bug-123` // Trocando para um branch existente.
- `git checkout -b bug-123` // Criar um novo branch e trocar.
- `git merge bug-123` // unir as braches. OBS: é necessário estar no branch que deverá receber as alterações.
- `git help` // ajuda
- `git config --global user.name "Marcos"` // Setar usuário.
- `git config --global user.email viniciosmarvin1995@gmail.com` // Setar email.
- `git config --global core.excludesfile ~/.gitignore` // Setar arquivos a serem ignorados.
- `git add -f arquivo_no_gitignore.txt` // Adicionar um arquivo que esta listado no .gitignore (geral ou do .repositório)
- `git rm meu_arquivo.txt` // Remover arquivo.
- `git rm -r diretorio` // Remover diretório.
- `git log -p -2` // Exibir histórico com diff das duas últimas alterações.
- `git log --stat` // Exibir resumo do histórico (hash completa, autor, data, comentário e qtde de alterações (+/-)).
- `git remote ou git remote -v` // Exibir os repositórios remotos.
- `git remote add origin git@github.com:MarvinGit-25/testeGit.git` // Vincular repositório local com um repositório remoto.
- `git remote show origin` // Exibir informações dos repositórios remotos.
- `git remote rename origin curso-git` // Renomear um repositório remoto.
- `git remote rm curso-git` // Desvincular um repositório remoto.
- `git pull` // Atualizar repositório local de acordo com o repositório remoto
  Atualizar os arquivos no branch atual.
- `git tag vs-1.1` // Criando uma tag leve.
- `git stash` // Criar um stash. O Stash como se fosse um branch temporário que contem apenas as alterações ainda não commitadas.
- `git stash list` // Listar stashes.
- `git stash apply` // Voltar para o último stash.
- `git stash apply stash@{2}` // Voltar para um stash específico.
- `git stash branch meu_branch` // Criar um branch a partir de um stash.
- `git clone git@github.com:MarvinGit-25/testeGit.git` // Clonar um repositório remoto já existente.
- `` //
