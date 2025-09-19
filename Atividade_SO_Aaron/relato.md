# Atividade 01 – Introdução a Linux usando Docker no Windows

**Aluno:** Aaron Guerra Goldberg
**Matrícula:** 20251014040042 
**Data:** (18/09/2025)  
**Disciplina:** Sistemas Operacionais  
**Professor:** Leonardo A. Minora  

---

## Introdução
O objetivo desta atividade foi praticar comandos básicos do Linux em um contêiner Docker utilizando a imagem Fedora.  
Assim, foi possível compreender conceitos como navegação em diretórios, manipulação de arquivos, permissões, processos e gerenciamento de pacotes.

## Observação
O Docker Engine foi utilizado através do Docker Desktop, disponível para Windows.

---

## Relato das Atividades

### 1. Iniciando o contêiner Fedora
- Comando utilizado:
```bash
docker run -it --name fedora-tutorial fedora:latest /bin/bash
```
- O contêiner foi iniciado em modo interativo com a imagem Fedora.
- Prints dos resultados estão na pasta **/imagens**.

### 2. Navegação básica
- Comandos utilizados: `pwd`, `cd ~`, `ls`, `mkdir atividades`, `cd atividades`, `cd ..`
- Prints dos resultados estão na pasta **/imagens**.

### 3. Manipulação de arquivos
- Criação, renomeação, cópia e exclusão de arquivos.  
- Exemplo: `touch arquivo1.txt`, `mv arquivo1.txt documento.txt`, `cp documento.txt backup/`, `rm documento.txt`.
- Prints dos resultados estão na pasta **/imagens**.

### 4. Gerenciamento de pacotes
- Atualização e instalação de pacotes com `dnf`.  
- Exemplo: `dnf update -y`, `dnf install nano -y`, `nano --version`, `dnf remove nano -y`.
- Prints dos resultados estão na pasta **/imagens**.

### 5. Permissões de arquivos
- Alteração de permissões com `chmod`.  
- Exemplo: `chmod u+x script.sh`.
- Prints dos resultados estão na pasta **/imagens**.

### 6. Processos em execução
- Listagem e encerramento de processos com `ps aux`, `sleep 60 &`, `kill <PID>`.
- Prints dos resultados estão na pasta **/imagens**.

### 7. Encerrando o contêiner
- Comandos finais: `exit`, `docker rm fedora-tutorial`.
- Prints dos resultados estão na pasta **/imagens**.

---

## Conclusão
A atividade permitiu conhecer e praticar comandos fundamentais do Linux em um ambiente isolado usando Docker.  
Consegui compreender melhor como navegar pelo sistema, criar e manipular arquivos, gerenciar permissões, pacotes e processos.  

A principal dificuldade foi adaptar-me à sintaxe dos comandos do Docker/Linux, mas com a prática ficou mais claro.  
Essa experiência será útil em futuras disciplinas e no uso profissional de ambientes Linux.

---

## Observação
Os prints de cada etapa estão na pasta **/imagens** para comprovação da execução.
