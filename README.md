# Repositório para guardar anotações

Este repositório foi criado como parte do desafio de Git/Github proposto pelo curso de desenvolvimento de jogos da DIO.

## Conteúdo

Neste repositório há um documento README.md e um documento .docx com as anotações das aulas até aqui que serão, ainda, atualizadas conforme progresso nas aulas.
Ainda o repositório exerto foi inicialmente criado no github e depois utilizando o git bash foi criado o arquivo README.md e feitos os procedimentos para adicionar
o repositório local, adicionar os arquivos na stage area, fazer o commit e depois o push.

## Comandos Git utilizados:


|Comando Git|Descrição|
|-----------|---------|
| ``` git init ```| Inicia o repositório local|
| ```git config --global user.name "username"```| Configura o nome de usuário|
|```git config --global user.email "e-mail"```| Configura o e-mail de usuário|
|```git remote add origin url-do-repositório-externo```| Associa o repositório git local ao repositório remoto (no github) e o define como origin| 
|```touch README.md```| Cria o arquivo README.md no repositório local|
|```git remot -v```| Mostra a URL do repositório externo ao qual o repositório git local está associado|
|```git status```| Exibe o estado atual dos arquivos no repositório Git local, destacando as modificações, os arquivos não rastreados e o estado das branches.|
|```git add .```| Adiciona todas as alterações e arquivos não rastreados no diretório de trabalho atual ao índice (staging area) do Git, preparando-os para serem incluídos no próximo commit.|
|```git commit -m "mensagem do commit"```| Cria um novo commit no repositório Git, registrando as alterações previamente adicionadas ao índice (staging area) com uma mensagem descritiva. Esse commit representa uma etapa no histórico de versão do projeto e inclui as modificações feitas.|
|```git log```| Visualiza o histórico de commits do repositório Git, mostrando informações detalhadas, como os hashes de commit, autores, datas e mensagens de commit, permitindo que você acompanhe as alterações e a evolução do projeto ao longo do tempo.|
|```git push -u origin main```| Envia as alterações do ramo local "main" para o repositório remoto "origin," estabelecendo uma associação entre o ramo local "main" e o ramo "main" no repositório remoto "origin," e enviando as alterações.|
