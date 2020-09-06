# GIT E GITHUB

#### Instalação 

https://git-scm.com/download

# 📌 Passo Para adicionar repositório no Github

1. git config --global user.name "nome do usuário github"
2. git config --global user.email "email correspondente"
3. git init
4. touch .gitignore && echo "node_modules/">> .gitignore (caso queira ignorar a pasta de node_modules)
5. git add .
6. git commit -m "nome do commit ou qualquer coisa"
7. os últimos passos poderás encontrar os comandos gerados após criar o repositório no github nesse caso o remote

# 🎴 SCENES (Possíveis situações para usar o git)

[x] Você deseja criar pontos na história da produção do seu projeto.
[x] Você deseja verificar mudanças feitas no seu projeto.
[x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
[x] Você adiciona as novas funcionalidades ao seu projeto em produção.
[x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.
[x] Você quer colocar seu projeto na nuvem.
[x] Você vai pegar um projeto já iniciado, para trabalhar com o time.
[x] Você precisa resolver um conflito.
[x] Antes de enviar a resolução, precisamos atualizar o projeto local.
[x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
[x] Você precisa recuperar algo deletado.


# 📎 Comandos

- ```git init```: Inicia a linha do tempo.
- ```git add```: Adiciona ou atualiza mudanças para irem para a linha do tempo.
- ```git commit```: Adiciona ou atualiza mudanças para irem para a linha do tempo.
- ```git log```: Visualiza os pontos na linha do tempo / commit.
- ```git status```: Informa o estado das alterações do nosso projeto.
- ```git show```: Apresenta determinado ponto na história.
- ```git branch```: Gerenciar novas linhas do tempo.
- ```git checkout```: Manipula as linhas do tempo.
- ```git merge```: Manipula as linhas do tempo.
- ```git push```: Envia alterações locais para o repositório remoto.
- ```git clone```: Clonar um projeto / repositório.
- ```git pull```: Puxa do repositório remoto.

# 🎁 Extras

- git branch nome_da_branch [criar uma nova linha de tempo]
- git checkout nome_da_branch [mudar para uma linha de tempo]
- git checkout master [ver todas as linhas do tempo] 
- git branch [listar todas as linhas de tempo]
- git merge nome_da_branch [Unir linhas de tempo]
- git branch -D nome_da_branch [Deletar uma branch]
- git -remote -v [Para ver os meus repositórios]
- git config credential.helper store [Sem precisar fazer login sempre que fizer um push]
- git clone https://github.com/user_name/nome_do_repositorio.git [Clonar um repositório na sua máquina local]
- git checkout -b test [Criar uma branch nova e mudar logo para lá]
- git commit -am "update ficheiros" [Adicionar e commitar]
- git checkout número_do_ponto -- nome_do_arquivo_deletado [Para recuperar um arquivo perdido que ainda está na linha de tempo, use o git log para verificar se consta na linha de tempo]




