# GIT / GITHUB

Instalar o Git pelo link:

[Git](https://git-scm.com/downloads)

Depois no prompt (cmd) / terminal digitar:

`git --version` -> para saber a versão e depois configurar o básico:

`git config --global user.name "Seu Nome"` -> para definir o nome de usuário

`git config --global user.email seuemail@provedor.com` -> para defenir o email do usuário

`git config --global --list` -> para listar todas as configurações

### Para gerenciar uma pasta como git

Para definir uma pasta como repositório git digite no terminal|prompt|GitBash:

`git init`

### Comandos Git

| **Comando**                                                         | **Descrição**                                                                                                                                           |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `git init`                                                          | Inicializar a pasta como repositório git                                                                                                                |
| `git status`                                                        | Verificar o status                                                                                                                                      |
| `git add `*arquivo(s)\|pasta(s)*                                    | Preparar arquivos para commitar (staging area)                                                                                                          |
| `git add .`                                                         | Para preparar todos os arquivos da pasta atual                                                                                                          |
| `git commit`                                                        | Commitar os arquivos da Staging Area                                                                                                                    |
| `git commit -m "Frase / mensagem do tipo de commit (first commit)"` | Commita e insere uma "mensagem no commit" \| descrição do commit                                                                                        |
| `git log`                                                           | Commits feitos e logs                                                                                                                                   |
| `git log --oneline`                                                 | Commits feitos e logs Online                                                                                                                            |
| `git push`                                                          | Commitar na nuvem                                                                                                                                       |
| `git fetch`                                                         | Verifica os arquivos no repositório da nuvem                                                                                                            |
| `git pull`                                                          | Baixa as modificações do repositório online                                                                                                             |
| `git reset`                                                         | Tira do Staged todos os arquivos                                                                                                                        |
| `git reset --"nome do arquivo"`                                     | Tira do Staged o arquivo\|pasta                                                                                                                         |
| `git reset --hard`                                                  | Remove do Staged e desfaz as modificações                                                                                                               |
| `git reset HEAD~1`                                                  | Remove o ultimo commit e volta um estagio anterior                                                                                                      |
| `git reset aas151564dasASDag...`                                    | Desfaz os commits para até o hash do commit                                                                                                             |
| `git push --force` ou `git push -f`                                 | Forçar a push na nuvem atropelando tudo e igualando a nuvem o local                                                                                     |
| `git reset origin/main`                                             | Deixa o repositório local igual o da nuvem. Caso tenha usado o "git push -f" avisar todos os que estiver utilizando o repositório para dar esse comando |
| `git reset origin/main --hard`                                      | Igual ao de cima mais forçando                                                                                                                          |
| `git revert hash`                                                   | Revert um commit, iserindo a hash do commit que queira desfazer                                                                                         |
