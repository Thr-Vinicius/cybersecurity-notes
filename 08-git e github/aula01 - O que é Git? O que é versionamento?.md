# Aula 01 — O que é Git? O que é versionamento?

## Conteúdo

Nesta aula fomos introduzidos aos conceitos de Git, GitHub e controle de versão.

## Características

- Git e GitHub são ferramentas diferentes.
- O Git pode ser usado com qualquer linguagem de programação.
- Ele não é obrigatório para aprender programação, mas é muito importante
  para organizar projetos e trabalhar profissionalmente.

## Controle de versão

Um sistema de controle de versão registra diferentes estados de um projeto
ao longo do tempo.

Ele permite:

- acompanhar alterações;
- recuperar versões anteriores;
- identificar quem realizou cada mudança;
- organizar o trabalho individual ou em equipe;
- testar modificações sem comprometer a versão principal.

## Git

O Git é um sistema distribuído de controle de versão.

Ao inicializar o Git em uma pasta, ele cria um repositório local por meio
da pasta oculta `.git`, na qual são armazenadas as informações e o
histórico do projeto.

### Funcionamento básico

O projeto possui três áreas principais:

1. Área de trabalho: onde os arquivos são criados e modificados.
2. Staging area: onde selecionamos as alterações que entrarão no próximo commit.
3. Repositório local: onde os commits ficam registrados.

Fluxo básico:

- `git status`: mostra a situação dos arquivos.
- `git add`: prepara alterações para o próximo commit.
- `git commit`: registra uma nova versão no repositório local.
- `git log`: exibe o histórico de commits.

Cada commit representa um estado do projeto em determinado momento e contém:

- identificador;
- autor;
- data;
- mensagem;
- referência à versão anterior.

## Modelo centralizado e distribuído

### Modelo centralizado

O histórico principal fica armazenado em um servidor central.

Exemplos:

- CVS;
- SVN.

### Modelo distribuído

Cada cópia do repositório pode possuir os arquivos e o histórico completo
do projeto.

Exemplos:

- Git;
- Mercurial;
- BitKeeper.

O Git pode funcionar localmente sem internet ou servidor remoto.

## Repositório remoto

Um repositório remoto é uma cópia do projeto hospedada em outra máquina
ou plataforma.

Ele pode ser utilizado para:

- sincronizar o projeto;
- compartilhar código;
- colaborar com outras pessoas;
- manter uma cópia remota do histórico.

O comando `git push` envia commits locais ao repositório remoto.

## Principais vantagens

- Controle do histórico;
- Recuperação de versões anteriores;
- Trabalho em equipe;
- Organização;
- Segurança durante alterações;
- Criação de ramificações do projeto;
- Identificação das mudanças realizadas.

## GitHub

O GitHub é uma plataforma online de hospedagem de repositórios Git.

Ele permite:

- armazenar repositórios;
- compartilhar projetos;
- colaborar com outras pessoas;
- acompanhar alterações;
- divulgar trabalhos;
- participar de comunidades de desenvolvimento.
