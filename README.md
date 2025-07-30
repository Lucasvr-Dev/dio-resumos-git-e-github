
# | Resumos Git e GitHub |

Repositório para armazenar resumos sobre Git e GitHub
do curso de Versionamento de Código com Git e GitHub da 
[Digital Innovation One](https://www.dio.me/)

## 🔧 Ferramentas
[![Documentação Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=orange&labelColor=000000)](https://git-scm.com/)
[![Documentação GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white&labelColor=000000)](https://github.com/seurepositorio)

## 💻 Links das Aulas

| Aulas | Resumos |
|------|---------|
| Criando e Clonando Repositórios | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/a377a00b-461c-4ab0-8258-3addd2fef14c?autoplay=1)
| Salvando Alterações no Repositório Local | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/599dd3dd-d189-474f-a55c-22f37b4472da?autoplay=1)
| Desfazendo Alterações no Repositório Local | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023?autoplay=1)
| Enviando e baixando Alterações com o Repositório Remoto | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/dd17c56e-2327-493c-942a-358a49a26549?autoplay=1)
| Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando conflitos | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/2c7fd2b1-e7c4-4947-9b07-ffcbfb4bd689?autoplay=1)
| Trabalhando com Branches - Comandos Úteis no Dia a Dia | [![Static Badge](https://img.shields.io/badge/Ver%20Material-blue)](https://web.dio.me/track/gft-start-7-java/course/406684a4-396d-4160-94b9-ead934e18564/learning/80018fab-daac-4917-8527-a6be2e0c3cf0?autoplay=1)


## 👨🏽‍💻Comandos Principais:

```
git init  //inicia pasta como repositório git

git add . ou git add <nome_do_arquivo> //adiciona todos os arquivos alterados na "stage area"

git commit -m "nome do commit"

git push -u origin main //faz upload para repositório remoto dos arquivos "comitados"

git pull //puxa todos os arquivos alterados no repositório remoto (GitHub) para o repositório local (PC)

git status //verifica status da branch
git log //verifica log de commits

git reset --soft <hash de identificação do commit> //reseta commit feito para a "stage area". aqui é só dar um <add .> ou <add nome_do_arquivo>

git reset --mixed <hash de identificação do commit> //reseta commit feito para a "untreacked file"

git reset --hard <hash de identificação do commit> //apaga commit feito

git checkout -b <nome_da_branch> //cria e troca para outra branch

git checkout <nome_da_branch> //troca para outra branch

git branch //lista todas as branches existentes no repositório
git branch -v //lista o último commit de cada branch
git branch -d <nome_da_branch> //deleta a branch informada

git merge <nome_da_branch> //mescla a branch informada com a branch atual.

git fetch <repositório_branch> (exemplo: git fetch origin main) //baixa as alterações sem mesclar no repositório local (para mesclar, deve usar o "git merge")

git diff <branch_repositório/branch> (exemplo: git diff main origin/main) //mostra as diferenças entre o repositório local e o remoto

git stash //arquiva modificações feitas. Aquelas que você não quer que subam para a branch

git stash list //lista as modificações arquivadas

git stash pop //para trazer as alterações e excluir a alteração mais recente da lista

git stash apply //se quiser manter a alteração na lista para um uso posterior
```

## 👨🏽‍💻Comandos Úteis:

```
mkdir <nome_do_arquivo> //cria repositório

touch <nome_arquivo> //cria arquivo

echo "#commit-2-branch-main" > commit-2-branch-main.txt //exibe texto no terminal ou para escrever texto em um arquivo. primeiro vai o que estará dentro do arquivo, seguido pelo nome do arquivo
```

## 🔍 Referências
- [Digital Innovation One](https://www.dio.me/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Documentation](https://docs.github.com/pt)

#

 <p align="center">Made with ❤️ by Lvrr</p>


#

