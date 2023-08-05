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

