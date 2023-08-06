# Comandos do Git - Exemplo

Este repositório de exemplo mostra uma sequência de comandos do Git utilizados para criar um novo repositório, adicionar um arquivo e enviar as alterações para um repositório remoto.

### 1. git init

Este comando inicializa um novo repositório Git vazio no diretório atual. Ele cria um diretório oculto chamado ".git", onde são armazenados os metadados e o histórico do repositório.

### 2. git add Readme.md

O comando `git add` adiciona o arquivo "Readme.md" à área de preparação (index ou staging area). Isso indica que as mudanças feitas no arquivo "Readme.md" serão incluídas no próximo commit.

### 3. git status

O comando `git status` mostra o estado atual do repositório Git. Ele exibe informações sobre o branch atual, as mudanças que foram preparadas no index e outras informações úteis sobre o estado do repositório.

### 4. git commit -m "primeiro commit"

O comando `git commit` cria um novo commit no repositório, registrando as mudanças que foram adicionadas ao index. A opção "-m" permite adicionar uma mensagem descritiva ao commit, tornando mais fácil entender as alterações realizadas.

### 5. git config --global user.email "brunovitalino01@hotmail.com"

O comando `git config` é usado para configurar opções do Git. Neste caso, estamos configurando o email do usuário globalmente para ser usado em todos os repositórios.

### 6. git config --global user.name "BRUNO VITALINO RODRIGUES"

O comando `git config` também é usado para configurar opções do Git. Aqui, estamos configurando o nome do usuário globalmente para ser usado em todos os repositórios.

### 7. git branch -M "main"

O comando `git branch` é usado para criar, listar e gerenciar branches. Neste caso, estamos renomeando o branch atual de "master" para "main", uma mudança de nomenclatura comum para promover a inclusividade.

### 8. git remote add origin https://github.com/brunovitalinocbx/Compass.git

O comando `git remote add` é usado para adicionar um repositório remoto ao seu repositório local. Aqui, estamos adicionando um repositório remoto com o apelido "origin" e o URL especificado.

### 9. git push -u origin main

O comando `git push` é usado para enviar commits locais para um repositório remoto. A opção "-u" é usada para configurar a branch local "main" para rastrear a branch remota "origin/main". Isso facilita o envio de commits futuros para o repositório remoto sem especificar a branch a cada push.

### 10. git add .

O comando `git add .` adiciona todas as mudanças pendentes (novos arquivos, alterações e exclusões) à área de preparação (index) para serem incluídas no próximo commit.

### 11. git commit -m "segundo commit"

O comando `git commit` cria um novo commit no repositório para registrar as mudanças adicionadas ao index. A opção "-m" permite adicionar uma mensagem descritiva ao commit.

### 12. git push -u origin main

O comando `git push` é novamente utilizado para enviar os commits locais para o repositório remoto na branch "main", que foi previamente configurada para rastrear a branch remota "origin/main".

### 13. git checkout -b "novo-botao"

O comando `git checkout -b` cria uma nova branch chamada "novo-botao" e muda o HEAD para essa nova branch. Essa branch será criada a partir do ponto onde a branch atual (main) está.

### 14. git add .

O comando `git add .` é novamente usado para adicionar todas as mudanças pendentes à área de preparação na nova branch "novo-botao".

### 15. git commit -m "novo botao"

O comando `git commit` cria um novo commit na branch "novo-botao" para registrar as mudanças adicionadas ao index. A opção "-m" permite adicionar uma mensagem descritiva ao commit.

### 16. git push -u origin novo-botao

O comando `git push` é usado para enviar os commits locais da branch "novo-botao" para o repositório remoto na branch "novo-botao", que foi criada no repositório remoto.

### 17. git checkout "main"

O comando `git checkout` é usado para alternar entre branches existentes. Neste caso, estamos mudando para a branch "main".

### 18. git merge novo-botao

O comando `git merge` é usado para mesclar alterações de uma branch em outra. Neste caso, estamos mesclando as alterações feitas na branch "novo-botao" para a branch "main".

### 19. git push -u origin main

O comando `git push` é novamente usado para enviar os commits da branch "main", que agora inclui as alterações da branch "novo-botao", para o repositório remoto.

